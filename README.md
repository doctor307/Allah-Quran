<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quran Search</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; direction: rtl; }
        .container { width: 80%; margin: auto; }
        .search-bar { margin: 10px; padding: 5px; width: 50%; }
        .ayah { margin: 10px 0; }
        select, input, button { margin: 10px; padding: 5px; }
    </style>
</head>
<body>
    <div class="container">
        <h1>قرآن پاک</h1>
        
        <label for="surah">سورۃ منتخب کریں:</label>
        <select id="surah">
            <option value="1">1 - الفاتحہ</option>
            <option value="2">2 - البقرہ</option>
            <option value="3">3 - آل عمران</option>
            <option value="4">4 - النساء</option>
            <!-- مزید 114 سورتیں یہاں شامل کریں -->
        </select>
        
        <label for="ayah">آیت نمبر:</label>
        <input type="number" id="ayah" min="1" placeholder="آیت نمبر درج کریں">
        
        <button onclick="searchQuran()">تلاش کریں</button>
        
        <input type="text" class="search-bar" placeholder="آیت یا سورۃ تلاش کریں...">
        
        <div id="ayahs">
            <p class="ayah">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</p>
            <p class="ayah">الْحَمْدُ لِلَّهِ رَبِّ الْعَالَمِينَ</p>
            <p class="ayah">الرَّحْمَٰنِ الرَّحِيمِ</p>
            <p class="ayah">مَٰلِكِ يَوْمِ الدِّينِ</p>
        </div>
    </div>
    
    <script>
        function searchQuran() {
            let surah = document.getElementById("surah").value;
            let ayah = document.getElementById("ayah").value;
            if (ayah) {
                let url = `https://quran.com/${surah}/${ayah}`; // اصل ڈیٹا سورس کے مطابق ایڈجسٹ کریں
                window.location.href = url;
            } else {
                alert("براہ کرم آیت نمبر درج کریں۔");
            }
        }
    </script>
</body>
</html>
