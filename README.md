<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quran Search</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        select, input, button { margin: 10px; padding: 5px; }
    </style>
</head>
<body>
    <h2>Quran Search</h2>
    
    <label for="surah">Select Surah:</label>
    <select id="surah">
        <option value="1">1 - Al Fatiha</option>
        <option value="2">2 - Al Baqara</option>
        <option value="3">3 - Aal e Imran</option>
        <option value="4">4 - An Nisa</option>
        <!-- Add all 114 Surahs here -->
    </select>
    
    <label for="ayah">Ayah Number:</label>
    <input type="number" id="ayah" min="1" placeholder="Enter Ayah No">
    
    <button onclick="searchQuran()">Go</button>
    
    <script>
        function searchQuran() {
            let surah = document.getElementById("surah").value;
            let ayah = document.getElementById("ayah").value;
            if (ayah) {
                let url = `https://quran.com/${surah}/${ayah}`; // Change to your Quran data source
                window.location.href = url;
            } else {
                alert("Please enter an Ayah number.");
            }
        }
    </script>
</body>
</html>
