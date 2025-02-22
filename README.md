<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quran Website</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; direction: rtl; }
        .container { width: 80%; margin: auto; }
        .search-bar { margin-bottom: 20px; }
        .ayah { margin: 10px 0; }
    </style>
</head>
<body>
    <div class="container">
        <h1>قرآن پاک</h1>
        <input type="text" class="search-bar" placeholder="آیت یا سورۃ تلاش کریں...">
       <nav class="navbar navbar-default navbar-fixed-top" role="navigation">
  <div class="container-fluid" bis_skin_checked="1">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header" bis_skin_checked="1">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="https://dailyayat.com"><h1 class="eng">Daily Ayat</h1>
      </a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1" bis_skin_checked="1">
      <ul class="nav navbar-nav">
<!--class="active"
        <li><a href="https://dailyayat.com">Home</a></li>-->
              <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown">About<span class="caret"></span></a>
          <ul class="dropdown-menu" role="menu">
            <li><a href="https://dailyayat.com/about.php">About Daily Ayat</a></li>
            <li><a href="https://dailyayat.com/contributions.php">Contributions</a></li>
          </ul>
        </li>
<!-- <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown">Al Quran <span class="caret"></span></a>
          <ul class="dropdown-menu" role="menu">
            <li><a href="https://dailyayat.com/about.php">What is Quran</a></li>
            <li><a href="https://dailyayat.com/about.php">Quran Images</a></li>
            <li><a href="https://dailyayat.com/about.php">Quran Statistics</a></li>
            <li class="divider"></li>
            <li><a href="https://dailyayat.com/about.php">Quran and Science</a></li>
            <li class="divider"></li>
            <li><a href="https://dailyayat.com/about.php">Miracles of Quran</a></li>
          </ul>
        </li> -->
       <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown">Contact<span class="caret"></span></a>
          <ul class="dropdown-menu" role="menu">
            <li><a data-toggle="modal" href="#contactUsModal">Contact Us</a></li>
            <li><a data-toggle="modal" href="#reportBug">Report Error</a></li>
           </ul>
        </li>
       <li><a data-toggle="modal" href="#subscribeModal">Subscribe for Daily Ayat</a></li>
      </ul>
<form role="form" class="navbar-form navbar-right" action="index.php" method="post">
<select name="ssid" id="surah_select" onchange="loadAyats(this.options[this.selectedIndex].getAttribute('ayats'))" class="form-control" required="required" fdprocessedid="z613ib">
<!--<option value="1">1 - Al-Fatiha</option>-->
                                                    <option ayats="7" value="1">
                          1 - Al Fatiha                          </option>
                                                    <option ayats="286" value="2">
                          2 - Al Baqara                          </option>
                                                    <option ayats="200" value="3">
                          3 - Aal e Imran                          </option>
                                                    <option ayats="176" value="4">
                          4 - An Nisa                          </option>
                                                    <option ayats="120" value="5">
                          5 - Al Meada                          </option>
                                                    <option ayats="165" value="6">
                          6 - Al Anaam                          </option>
                                                    <option ayats="206" value="7">
                          7 - Al Araf                          </option>
                                                    <option ayats="75" value="8">
                          8 - Al Anfal                          </option>
                                                    <option ayats="129" value="9">
                          9 - At Taubah                          </option>
                                                    <option ayats="109" value="10">
                          10 - Yunus                          </option>
                                                    <option ayats="123" value="11">
                          11 - Hud                          </option>
                                                    <option ayats="111" value="12">
                          12 - Yusuf                          </option>
                                                    <option ayats="43" value="13">
                          13 - Ar Rad                          </option>
                                                    <option ayats="52" value="14">
                          14 - Ibrahim                          </option>
                                                    <option ayats="99" value="15">
                          15 - Al Hijr                          </option>
                                                    <option ayats="128" value="16">
                          16 - An Nahl                          </option>
                                                    <option ayats="111" value="17">
                          17 - Al Isra                          </option>
                                                    <option ayats="110" value="18">
                          18 - Al Kahf                          </option>
                                                    <option ayats="98" value="19">
                          19 - Maryam                          </option>
                                                    <option ayats="135" value="20">
                          20 - Taha                          </option>
                                                    <option ayats="112" value="21">
                          21 - Al Anbiya                          </option>
                                                    <option ayats="78" value="22">
                          22 - Al Hajj                          </option>
                                                    <option ayats="118" value="23">
                          23 - Al Mumenoon                          </option>
                                                    <option ayats="64" value="24">
                          24 - An Noor                          </option>
                                                    <option ayats="77" value="25">
                          25 - Al Furqan                          </option>
                                                    <option ayats="227" value="26">
                          26 - Ash Shuara                          </option>
                                                    <option ayats="93" value="27">
                          27 - An Naml                          </option>
                                                    <option ayats="88" value="28">
                          28 - Al Qasas                          </option>
                                                    <option ayats="69" value="29">
                          29 - Al Ankaboot                          </option>
                                                    <option ayats="60" value="30">
                          30 - Ar Room                          </option>
                                                    <option ayats="34" value="31">
                          31 - Luqman                          </option>
                                                    <option ayats="30" value="32">
                          32 - As Sajda                          </option>
                                                    <option ayats="73" value="33">
                          33 - Al Ahzab                          </option>
                                                    <option ayats="54" value="34">
                          34 - Saba                          </option>
                                                    <option ayats="45" value="35">
                          35 - Fatir                          </option>
                                                    <option ayats="83" value="36">
                          36 - Ya Seen                          </option>
                                                    <option ayats="182" value="37">
                          37 - As Saaffat                          </option>
                                                    <option ayats="88" value="38">
                          38 - Sad                          </option>
                                                    <option ayats="75" value="39">
                          39 - Az Zumar                          </option>
                                                    <option ayats="85" value="40">
                          40 - Al Ghafir                          </option>
                                                    <option ayats="54" value="41">
                          41 - Fussilat                          </option>
                                                    <option ayats="53" value="42">
                          42 - Ash Shura                          </option>
                                                    <option ayats="89" value="43">
                          43 - Az Zukhruf                          </option>
                                                    <option ayats="59" value="44">
                          44 - Ad Dukhan                          </option>
                                                    <option ayats="37" value="45">
                          45 - Al Jathiya                          </option>
                                                    <option ayats="35" value="46">
                          46 - Al Ahqaf                          </option>
                                                    <option ayats="38" value="47">
                          47 - Muhammad                          </option>
                                                    <option ayats="29" value="48">
                          48 - Al Fath                          </option>
                                                    <option ayats="18" value="49">
                          49 - Al Hujraat                          </option>
                                                    <option ayats="45" value="50">
                          50 - Qaf                          </option>
                                                    <option ayats="60" value="51">
                          51 - Adh Dhariyat                          </option>
                                                    <option ayats="49" value="52">
                          52 - At tur                          </option>
                                                    <option ayats="62" value="53">
                          53 - An Najm                          </option>
                                                    <option ayats="55" value="54">
                          54 - Al Qamar                          </option>
                                                    <option ayats="78" value="55">
                          55 - Al Rahman                          </option>
                                                    <option ayats="96" value="56">
                          56 - Al Waqia                          </option>
                                                    <option ayats="29" value="57">
                          57 - Al Hadid                          </option>
                                                    <option ayats="22" value="58">
                          58 - Al Mujadila                          </option>
                                                    <option ayats="24" value="59">
                          59 - Al Hashr                          </option>
                                                    <option ayats="13" value="60">
                          60 - Al Mumtahina                          </option>
                                                    <option ayats="14" value="61">
                          61 - As Saff                          </option>
                                                    <option ayats="11" value="62">
                          62 - Al Jumua                          </option>
                                                    <option ayats="11" value="63">
                          63 - Al Munafiqoon                          </option>
                                                    <option ayats="18" value="64">
                          64 - At Taghabun                          </option>
                                                    <option ayats="12" value="65">
                          65 - At Talaq                          </option>
                                                    <option ayats="12" value="66">
                          66 - At Tahrim                          </option>
                                                    <option ayats="30" value="67">
                          67 - Al Mulk                          </option>
                                                    <option ayats="52" value="68">
                          68 - Al Qalam                          </option>
                                                    <option ayats="52" value="69">
                          69 - Al Haaqqa                          </option>
                                                    <option ayats="44" value="70">
                          70 - Al Maarij                          </option>
                                                    <option ayats="28" value="71">
                          71 - Nooh                          </option>
                                                    <option ayats="28" value="72">
                          72 - Al Jinn                          </option>
                                                    <option ayats="20" value="73">
                          73 - Al Muzzammil                          </option>
                                                    <option ayats="56" value="74">
                          74 - Al Muddathir                          </option>
                                                    <option ayats="40" value="75">
                          75 - Al Qiyama                          </option>
                                                    <option ayats="31" value="76">
                          76 - Al Insan                          </option>
                                                    <option ayats="50" value="77">
                          77 - Al Mursalat                          </option>
                                                    <option ayats="40" value="78">
                          78 - An Naba                          </option>
                                                    <option ayats="46" value="79">
                          79 - An Naziat                          </option>
                                                    <option ayats="42" value="80">
                          80 - Abasa                          </option>
                                                    <option ayats="29" value="81">
                          81 - At Takwir                          </option>
                                                    <option ayats="19" value="82">
                          82 - AL Infitar                          </option>
                                                    <option ayats="36" value="83">
                          83 - Al Mutaffifin                          </option>
                                                    <option ayats="25" value="84">
                          84 - Al Inshiqaq                          </option>
                                                    <option ayats="22" value="85">
                          85 - Al Burooj                          </option>
                                                    <option ayats="17" value="86">
                          86 - At Tariq                          </option>
                                                    <option ayats="19" value="87">
                          87 - Al Ala                          </option>
                                                    <option ayats="26" value="88">
                          88 - Al Ghashiya                          </option>
                                                    <option ayats="30" value="89">
                          89 - Al Fajr                          </option>
                                                    <option ayats="20" value="90">
                          90 - Al Balad                          </option>
                                                    <option ayats="15" value="91">
                          91 - Ash Shams                          </option>
                                                    <option ayats="21" value="92">
                          92 - Al Lail                          </option>
                                                    <option ayats="11" value="93">
                          93 - Ad Dhuha                          </option>
                                                    <option ayats="8" value="94">
                          94 - Al Inshirah                          </option>
                                                    <option ayats="8" value="95">
                          95 - At Tin                          </option>
                                                    <option ayats="19" value="96">
                          96 - Al Alaq                          </option>
                                                    <option ayats="5" value="97">
                          97 - Al Qadr                          </option>
                                                    <option ayats="8" value="98">
                          98 - Al Bayyina                          </option>
                                                    <option ayats="8" value="99">
                          99 - Al Zalzala                          </option>
                                                    <option ayats="11" value="100">
                          100 - Al Adiyat                          </option>
                                                    <option ayats="11" value="101">
                          101 - Al Qaria                          </option>
                                                    <option ayats="8" value="102">
                          102 - At Takathur                          </option>
                                                    <option ayats="3" value="103">
                          103 - Al Asr                          </option>
                                                    <option ayats="9" value="104">
                          104 - Al Humaza                          </option>
                                                    <option ayats="5" value="105">
                          105 - Al fil                          </option>
                                                    <option ayats="4" value="106">
                          106 - Quraish                          </option>
                                                    <option ayats="7" value="107">
                          107 - Al Maun                          </option>
                                                    <option ayats="3" value="108">
                          108 - Al Kauther                          </option>
                                                    <option ayats="6" value="109">
                          109 - Al Kafiroon                          </option>
                                                    <option ayats="3" value="110">
                          110 - An Nasr                          </option>
                                                    <option ayats="5" value="111">
                          111 - Al Masadd                          </option>
                                                    <option ayats="4" value="112">
                          112 - Al Ikhlas                          </option>
                                                    <option ayats="5" value="113">
                          113 - Al Falaq                          </option>
                                                    <option ayats="6" value="114">
                          114 - An Nas                          </option>
                                                  </select>
                      <script>

function loadAyats(a) {
var result='';
document.getElementById('ayat_id').innerHTML = '<option value=""> - </option>';
for(var i=1; i<=a;i++){
		result += '<option value="'+i+'">'+i+'</option>';
    }
document.getElementById('ayat_id').innerHTML = result;
}
</script>
                        <select name="aaid" id="ayat_id" class="form-control" required="required" fdprocessedid="vt33fr">
                                                    <option ayat_id="1" value="1">
                          1                          </option>
                                                    <option ayat_id="2" value="2">
                          2                          </option>
                                                    <option ayat_id="3" value="3">
                          3                          </option>
                                                    <option ayat_id="4" value="4">
                          4                          </option>
                                                    <option ayat_id="5" value="5">
                          5                          </option>
                                                    <option ayat_id="6" value="6">
                          6                          </option>
                                                    <option ayat_id="7" value="7">
                          7                          </option>
                                                  </select>
<button type="submit" class="btn btn-default" fdprocessedid="725uo7">Go</button>
                          </form>



    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav> <div id="ayahs">
            <p class="ayah">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</p>
            <p class="ayah">الْحَمْدُ لِلَّهِ رَبِّ الْعَالَمِينَ</p>
            <p class="ayah">الرَّحْمَٰنِ الرَّحِيمِ</p>
            <p class="ayah">مَٰلِكِ يَوْمِ الدِّينِ</p>
        </div>
    </div>
</body>
</html>
