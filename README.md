<!DOCTYPE html>
<html lang="ky">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Кош-Дөбө айыл аймагы</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      color: #333;
    }
    header {
      background-color: #007BFF;
      color: white;
      padding: 20px 15px;
      text-align: center;
    }
    nav {
      background-color: #0056b3;
      display: flex;
      justify-content: space-between;
      padding: 12px 20px;
      position: sticky;
      top: 0;
      z-index: 100;
      align-items: center;
    }
    nav .nav-links {
      display: flex;
      gap: 15px;
    }
    nav .nav-links a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 7px 12px;
      border-radius: 4px;
      transition: background-color 0.3s ease;
    }
    nav .nav-links a:hover,
    nav .nav-links a:focus {
      background-color: #003d80;
      outline: none;
    }
    .burger {
      display: none;
      flex-direction: column;
      cursor: pointer;
      gap: 5px;
    }
    .burger div {
      width: 25px;
      height: 3px;
      background: white;
      border-radius: 2px;
      transition: 0.3s;
    }
    @media (max-width: 768px) {
      nav .nav-links {
        position: fixed;
        top: 60px;
        right: 0;
        background: #0056b3;
        height: calc(100% - 60px);
        flex-direction: column;
        width: 220px;
        padding-top: 20px;
        transform: translateX(100%);
        transition: transform 0.3s ease;
      }
      nav .nav-links.active {
        transform: translateX(0);
      }
      .burger {
        display: flex;
      }
    }
    section {
      background-color: white;
      margin: 20px auto;
      padding: 20px;
      border-radius: 10px;
      max-width: 900px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    h2 {
      color: #0056b3;
      margin-bottom: 15px;
    }
    ul, ol {
      margin-left: 20px;
      margin-bottom: 15px;
    }
    ul.ad-list {
      list-style: none;
      padding: 0;
    }
    ul.ad-list li {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 15px;
      margin-bottom: 12px;
      background: #e6f2ff;
      border-radius: 8px;
      box-shadow: 0 1px 3px rgba(0,0,0,0.1);
      gap: 15px;
      word-break: break-word;
    }
    ul.ad-list li a {
      color: #007BFF;
      font-weight: 600;
      text-decoration: none;
      flex-grow: 1;
    }
    ul.ad-list li a:hover {
      text-decoration: underline;
    }
    .ad-timer {
      min-width: 140px;
      color: #333;
      font-size: 0.9rem;
      white-space: nowrap;
      text-align: right;
    }
    .remove-btn {
      cursor: pointer;
      font-size: 1.2rem;
      color: red;
      user-select: none;
      margin-left: 10px;
      flex-shrink: 0;
    }
    form.upload-form {
      margin-top: 20px;
      background: #dbeeff;
      padding: 15px;
      border-radius: 10px;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      align-items: center;
      max-width: 900px;
      margin-left: auto;
      margin-right: auto;
    }
    form.upload-form label {
      font-weight: bold;
      flex-basis: 150px;
    }
    form.upload-form input[type="file"],
    form.upload-form input[type="number"] {
      padding: 8px;
      border-radius: 5px;
      border: 1px solid #ccc;
      flex-grow: 1;
      max-width: 250px;
    }
    form.upload-form button {
      background: #007BFF;
      color: white;
      border: none;
      padding: 10px 20px;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;
      flex-shrink: 0;
    }
    form.upload-form button:hover {
      background: #0056b3;
    }
    footer {
      text-align: center;
      padding: 15px 10px;
      background-color: #eee;
      font-size: 0.9rem;
      color: #555;
      margin-top: 30px;
    }
  </style>
</head>
<body>

<header>
  <h1>Кош-Дөбө айыл аймагы</h1>
  <p>Жалал-Абад облусу, Аксы району</p>
</header>

<nav>
  <div class="burger" id="burger" aria-label="Менюны ачуу/жабуу" role="button" tabindex="0">
    <div></div><div></div><div></div>
  </div>
  <div class="nav-links" id="nav-links">
    <a href="#tarh">Тарыхы</a>
    <a href="#info">Айыл аймак тууралуу</a>
    <a href="#ayildar">Айылдар</a>
    <a href="#zhery">Жер ресурстары</a>
    <a href="#zhanylyktar">Жаңылыктар</a>
  </div>
</nav>

<section id="tarh">
  <h2>Айыл аймагынын тарыхы</h2>
  <p>Ринжит өрөөнүндө биринчилерден болуп 1928-жылы Атана участкасында "Сталин" атындагы колхоз уюштурулуп, анын төрагалыгына Молдояров Кушназар дайындалган.</p>
  <p>1933-1934-жылдары "Иосиф", "Кызыл Кетмен", "Карл Маркс" колхоздору уюштурулуп, кийин "Иосиф" колхозу болуп биригишип, төрагалыгына Ботобаев Долонбай көрсөтүлгөн.</p>
  <p>1935-жылы Мундуз участкасында "Мээнеткеч" жана "Кызыл Дыйкан" колхоздору уюштурулуп, төрагалар болуп Жумабаев Жээнтай жана Эшкулов Колдош дайындалган.</p>
  <p>1941-жылы Улук, Торук участкаларында "Фрунзе" колхозу уюштурулуп, төрагасы Мавлянов Темиркул болгон.</p>
  <p>1954-1996-жылдар аралыгында колхоздор "Кош-Дөбө", "Мавлянов", "Бозбу Ата" аттары менен белгилүү болуп, кийин айыл чарба өндүрүштүк кооперативине айланган.</p>
  <p>1985–1988-жылдары айыл аймагындагы колхоздор кышкы мал багууда жана өндүрүштө жогорку көрсөткүчтөргө жетишип, Ардак грамоталар жана "Өтмө Кызыл Туу" менен сыйланышкан.</p>
  <p>1997-жылдын 17-январында расмий түрдө Кош-Дөбө айыл өкмөтү болуп түзүлгөн.</p>
</section>

<section id="info">
  <h2>Кош-Дөбө айыл аймагы тууралуу</h2>
  <ul>
    <li>Түзүлгөн жылы: 1997-жылдын 17-январы</li>
    <li>Аянты: 31,450 км²</li>
    <li>Район борбору Кербенден 20 км алыстыкта</li>
    <li>Жалал-Абад шаарынан 170 км алыстыкта</li>
    <li>Өзбекстан менен 33 км аралыкта чектешет</li>
    <li>Кожолуктун саны: 3,297</li>
    <li>Калкы: 16,013 адам</li>
    <li>Деңиз деңгээлинен бийиктиги: 800–1200 м</li>
  </ul>
</section>

<section id="ayildar">
  <h2>Айылдардын тизмеси</h2>
  <ol>
    <li>Улук</li>
    <li>Жангак</li>
    <li>Семет</li>
    <li>Торук</li>
    <li>Чие</li>
    <li>Таш-Жар</li>
    <li>Атана</li>
    <li>Сары-Кашка</li>
    <li>Мундуз</li>
  </ol>
</section>

<section id="zhery">
  <h2>Жер ресурстары</h2>
  <ul>
    <li>Жалпы жер аянты: 37,737 га</li>
    <li>Айыл чарбасына жарактуу: 31,425 га</li>
    <li>Айдоо жери: 3,423 га</li>
    <li>Сугат жери: 972 га</li>
    <li>Кайракы: 2,451 га</li>
    <li>Чабынды: 583 га</li>
  </ul>
  <p>Жер шарты мал чарбачылыгына жана дыйканчылыкка ылайыктуу.</p>
</section>

<section id="zhanylyktar">
  <h2>Жаңылыктар жана Убактылуу Жарнамалар</h2>
  <p>Бул бөлүм айыл аймагындагы акыркы жаңылыктар жана убактылуу жарнамалар үчүн арналган. PDF форматындагы файлдарды жүктөөгө болот.</p>

  <ul class="ad-list" id="ad-list"></ul>

  <form class="upload-form" id="uploadForm" enctype="multipart/form-data" aria-label="Жарнамаларды жүктөө формасы">
    <label for="adFile">Жарнама (PDF):</label>
    <input type="file" id="adFile" name="adFile" accept="application/pdf" required aria-required="true" />
    
    <label for="adDays">Жарнаманын мөөнөтү (күн):</label>
    <input type="number" id="adDays" name="adDays" min="1" max="365" value="7" required aria-required="true" />
    
    <button type="submit">Жүктөө</button>
  </form>
</section>

<footer>
  <p>© 2025 Кош-Дөбө айыл аймагы. Бардык укуктар корголгон.</p>
</footer>

<script>
  // Мобилдик меню үчүн
  const burger = document.getElementById('burger');
  const navLinks = document.getElementById('nav-links');

  burger.addEventListener('click', () => {
    navLinks.classList.toggle('active');
  });
  burger.addEventListener('keydown', e => {
    if(e.key === 'Enter' || e.key === ' ') {
      e.preventDefault();
      navLinks.classList.toggle('active');
    }
  });

  // Жарнамаларды башкаруу
  const adList = document.getElementById('ad-list');
  const uploadForm = document.getElementById('uploadForm');

  // Сактоо үчүн жарнамалар массиви
  let ads = [];

  // Жарнамаларды көрсөтүү функциясы
  function renderAds() {
    adList.innerHTML = '';
    const now = new Date();

    // Жарнамаларды мөөнөтүнө карап текшерүү, мөөнөтү өткөн жарнамаларды өчүрүү
    ads = ads.filter(ad => {
      const expireDate = new Date(ad.added.getTime() + ad.days * 24 * 60 * 60 * 1000);
      if (expireDate > now) {
        // Өтпөгөндөрүн калтыруу
        return true;
      }
      return false;
    });

    if (ads.length === 0) {
      adList.innerHTML = '<li>Жарнама жок</li>';
      return;
    }

    ads.forEach((ad, index) => {
      const expireDate = new Date(ad.added.getTime() + ad.days * 24 * 60 * 60 * 1000);
      const remainingMs = expireDate - now;
      const remainingDays = Math.floor(remainingMs / (1000 * 60 * 60 * 24));
      const remainingHours = Math.floor((remainingMs / (1000 * 60 * 60)) % 24);

      const li = document.createElement('li');
      const a = document.createElement('a');
      a.href = ad.url;
      a.target = '_blank';
      a.rel = 'noopener noreferrer';
      a.textContent = ad.filename;

      const timer = document.createElement('div');
      timer.className = 'ad-timer';
      timer.textContent = `Мөөнөт: ${remainingDays} күн ${remainingHours} саат`;

      const removeBtn = document.createElement('div');
      removeBtn.className = 'remove-btn';
      removeBtn.textContent = '×';
      removeBtn.title = 'Жарнаманы өчүрүү';
      removeBtn.setAttribute('role', 'button');
      removeBtn.tabIndex = 0;
      removeBtn.addEventListener('click', () => {
        ads.splice(index, 1);
        renderAds();
      });
      removeBtn.addEventListener('keydown', e => {
        if(e.key === 'Enter' || e.key === ' ') {
          e.preventDefault();
          ads.splice(index, 1);
          renderAds();
        }
      });

      li.appendChild(a);
      li.appendChild(timer);
      li.appendChild(removeBtn);

      adList.appendChild(li);
    });
  }

  // Файлдарды локалдык жүктөөгө мүмкүнчүлүк жок, бирок биз файлдардын URL-ин URL.createObjectURL менен жасайбыз
  uploadForm.addEventListener('submit', e => {
    e.preventDefault();

    const fileInput = document.getElementById('adFile');
    const daysInput = document.getElementById('adDays');

    if(fileInput.files.length === 0) {
      alert('PDF файлын тандаңыз!');
      return;
    }

    const file = fileInput.files[0];
    if(file.type !== 'application/pdf') {
      alert('Файл PDF форматында болушу керек!');
      return;
    }

    const days = parseInt(daysInput.value, 10);
    if(isNaN(days) || days < 1 || days > 365) {
      alert('Мөөнөтүн 1ден 365 күнгө чейин көрсөтүңүз.');
      return;
    }

    // Файлды URL катары сактоо (браузердин сессиясында гана)
    const fileUrl = URL.createObjectURL(file);

    ads.push({
      filename: file.name,
      url: fileUrl,
      days: days,
      added: new Date()
    });

    renderAds();

    // Форманы тазалоо
    uploadForm.reset();
    daysInput.value = 7;
  });

  // Башында көрсөтүү
  renderAds();

  // Ар бир мүнөт сайын мөөнөттү жаңыртуу
  setInterval(renderAds, 60000);
   ┣ 📁 pdf
 ┃ ┗ 📄 zharnama1.pdf
 ┃ ┗ 📄 zharnama2.pdf
 ┣ 📄 index.html

</script>

</body>
</html>
