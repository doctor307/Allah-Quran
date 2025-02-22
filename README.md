<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قرآن Explorer</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; direction: rtl; }
        .container { max-width: 900px; margin: auto; padding: 20px; }
        input { width: 100%; padding: 10px; margin: 10px 0; }
        .verse { margin: 15px 0; padding: 10px; border: 1px solid #ddd; background: #f9f9f9; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Allah & Quran</h1>
        <input type="text" id="search" placeholder="آیت تلاش کریں..." onkeyup="searchVerse()">
        <div id="verses"></div>
    </div>

    <script>
        const quranVerses = [
            { arabic: "بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ", translation: "اللہ کے نام سے جو نہایت مہربان، رحم کرنے والا ہے" },
            { arabic: "الْحَمْدُ لِلَّهِ رَبِّ الْعَالَمِينَ", translation: "تمام تعریفیں اللہ کے لیے ہیں، جو تمام جہانوں کا رب ہے" }
        ];

        function displayVerses() {
            const verseContainer = document.getElementById('verses');
            verseContainer.innerHTML = '';
            quranVerses.forEach(verse => {
                let verseDiv = document.createElement('div');
                verseDiv.classList.add('verse');
                verseDiv.innerHTML = `<strong>${verse.arabic}</strong><br>${verse.translation}`;
                verseContainer.appendChild(verseDiv);
            });
        }

        function searchVerse() {
            let query = document.getElementById('search').value.toLowerCase();
            let verseContainer = document.getElementById('verses');
            verseContainer.innerHTML = '';
            quranVerses.filter(verse => 
                verse.arabic.includes(query) || verse.translation.includes(query)
            ).forEach(verse => {
                let verseDiv = document.createElement('div');
                verseDiv.classList.add('verse');
                verseDiv.innerHTML = `<strong>${verse.arabic}</strong><br>${verse.translation}`;
                verseContainer.appendChild(verseDiv);
            });
        }

        displayVerses();
    </script>
</body>
</html>
