Hi! My name is Denis!

My contact: denisratskov@gmail.com or +375336624300

I am an engineer and a musician by education, I wanted to change something in my life, I decided to try myself in programming, again there is no such thing, but I have already made a website for myself ..

At the moment, I know a little ntml and css, according to JS, the script learned the syntax, started with python and also planned to study testing and Kotlin for android..

Starting on Epam course - stage0. Ending course ITDVN - JS Started - 86% of sertificate. Ending course ITEA online on Html & Css - give sertificate. And others..

My English range middle a1 or a2!I gradually tighten my level!

My code

My code:
<!DOCTYPE html>

<html lang="en">

<head>
<!--начинаем CSS-->

  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>

  <style>

  html, body , p {
  padding: 0;
  margin: 0;
  }

  p, li {
    font-family: 'Times New Roman', Times, serif;
  }
  
  h1 {
    font-size: 40px;
  }

  h2 {
    color: rgb(98, 98, 180);
    font-size: 36px;
  }

  .bold-text {
    font-weight: bold;
  }

  .cyan-text {
    color:rgb(255, 187, 0)
  }

  .white-text {
    color:rgb(255, 255, 255)
  }

  .golg-text {
    color:rgb(223, 224, 151)
  }
  
  .purple {
    background:rgb(73, 24, 165);
  }

  .block1 {
    width: 900px;
    margin:auto;
    padding-top: 50px;
    padding-bottom: 50px;
  }

  .block1.no-padding-top {
    padding-top: 0;
  }

  .nav {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 40px;
    letter-spacing: 6px;
    font-size: 10px;
  }

  .nav li {
    display: inline-block;
    margin: 5px;
    padding: 5px;
    cursor: pointer;
  }

  .nav li a {
    text-decoration: none;
    color: darkseagreen;
  }

  .exp {
    list-style: none;
    padding: 0;
    margin: 0;
    color:rosybrown;
  }

  .exp li {
    list-style: none;
    padding: 0;
    margin: 10px 0;
    color:rosybrown;
  }

  .achievemnts {
  list-style-image: url(./img-ok1\ -\ копия.png);
  }

  .str-point {

    list-style-image: url(./img-ok2\ -\ копия.png);

  }

  .logo-img {
  width: 980px;
  }

  .name-tag {
  font-size: 28px;
  letter-spacing: 10px;
  }

  .paragraph {
    margin: 20px 0;
    font-size: 18px;
    line-height: 30px;
  }

  .hands-bg {
    background-image: url("./wallpaper2.jpg");
    background-position: center;
    background-size: cover;
    font-size: 46px;
  }

  .circle-img {
  border-radius: 50%;
  }

  .word-spacing {
  letter-spacing: 6px;
  }

  .img-container {
    display: flex;
    justify-content: space-between;
    margin-top: 40px;
  }

  .img-container2 {
    display: flex;
    justify-content: left;
    margin-top: 100;
    height: 1120;
    width: 01;
  }

  #contact-form {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
  }

  #contact-form input, #contact-form textarea{
    padding: 20px;
    margin-bottom: 20px;
    font-size: 20px;
    font-weight: bold;
    outline: none;
    width: 853px;
    border: none;
    border: 3px solid cornflowerblue;
  }

  textarea {
    font-family: 'Times New Roman', Times, serif;
    height: 100px;
  }

  input#submit {
    width: 350px;
    cursor: pointer;
    background: rgb(189, 94, 113);
    color: gold;
    font-size: 24px;
    box-shadow: -20px -15px 15px 0px rgba(239, 255, 15, 0.863) inset;
  }

  #gototop {
    text-decoration: none;
    display: inline-block;
    height: 75px;
    width: 75px;
    background: rgb(224, 204, 86);
    font-size: 45px;
    font-weight: bold;
    text-align: center;
    border: 3px solid cornflowerblue;
    color: rgb(228, 217, 217);
    position: fixed;
    bottom: 80px;
    left: 200px;
    box-shadow: 20px 15px 15px 0px rgba(235, 229, 229, 0.863) inset;
  }

  .other {
    font-size: 12px;
    text-align: center;
    background: gold;
  }

  .logo-container {
    width: 890px;
    height: 547px;
    background-image: url("./img/+Dsc_1568.jpg");
    background-size: cover;
    box-shadow: 0px -120px 50px 0px rgba(73, 0, 165, 0.9) inset;
  } 

  .text-overlap {
    position: relative;
    padding: 0 60px ;
    top: -90px;
    margin: 0;
  }

</style>
<!--закончили CSS-->
</head>

<body>
<!--начинается верстка-->
<div>
  <div class="purple">
    <div class="block1" id="navigation"/>

      <ul class="cyan-text nav" style="padding-top: 10px;">
      <!--верхний блок-->
       <li>
         <a href="https://promodj.com/djratek/music">
         <span class="bold-text cyan-text name-tag">Д е н и C<br> 
          РАТЬКОВ </span></a> 
       </li>

       <li
         class="cyan-text">
         <a href="#experience">
            Опыт
          </a>
       </li>
        
       <li
         class="cyan-text">
          <a href="#achhievemnts">
            Достижения
          </a>
       </li>
      
       <li
         class="cyan-text">
          <a href="#strong">
           Сильные стороны
         </a>
       </li>
        
       <li
         class="cyan-text">
         <a href="#private">
           Биография
          </a>
       </li>
        
        <li
          class="cyan-text">
          <a href="#contact">
            Контакты
          </a>
       </li>
      
      </ul>

      <!--img classs="logo-img" src=./img/+Dsc_1568.jpg alt="Портрет"> -->
      <!--добавляем картинку с размытием> -->
      <div class="logo-container"></div>
      
      <!--добавляем текст, который будет внутри> -->
      <p class="golg-text paragraph text-overlap">
       Я не только начинающий программист, я много чем по жизни занимаюсь, вот решил начать с Front!
      </p>
      <!--описание к картинке-->
      <h1 class="white-text" style="margin-top: 0;">Showбиз : продюссер - музыкант - DJ - битмейкер</h1>       
    
    </div>

  </div>
      
  <div class="block1" id="experience">
  <!--блок1-->

   <h2>
     Мой Опыт работы
    </h2>

    <ol class="exp">
    
     <li>
       Python - <span class="bold-text"> 1 месяц изучения 
     </li>

     <li>
       JScript - <span class="bold-text"> 2 месяца Джавы
     </li>

     <li>
       HTML - <span class="bold-text"> 1 месяц и курсы
     </li>

     <li>
      CSS - <span class="bold-text"> 1 месяц и курсы
    </li>

    </ol>

  </div>

  <div class="block1 no-padding-top" id="achhievemnts">
  <!--блок2-->

    <h2>
     Мои Достижения
    </h2>

    <p>
      
      Самые главные из них

    </p>

    <ul class="achievemnts">

     <li><span class="bold-text">
       Начало верстки сайтов</span>
     </li>

     <li><span class="bold-text">
       JS - понимание динамики 
     </li>

     <li><span class="bold-text">
       Яндекс практикум - Python
     </li>

     <li><span class="bold-text">
      Закончил курс ITEA (верстка) 
    </li>

    </ul>

  </div>

  <div class="block1 no-padding-top" id="strong">
  <!--блок3-->

    <h2>
      Сильные стороны
    </h2>

    <ul class="cyan-text str-point">

     <li>
       уверенность
     </li>

     <li>
       стремление
     </li>

     <li>
       упорство
     </li>

     <li>
       быстро учусь
     </li>

     <li>
      быть лучшим
    </li>

    <li>
      пью - не пьянею
    </li>

    <li>
      а если пьянею
    </li>

    <li>
      то уже капец
    </li>

    <li>
      люблю девушек
    </li>

    <li>
      кстати звоните
    </li>

    </ul>

  </div>
  
  <div class="hands-bg" id="deviz">
  <!--просто картинка-->

    <div class="block1">

      <p>
        <i>Можно быть первым - и это УЖЕ доказано!</i>
      </p>

    </div>

  </div>

  <div class="block1" id="private">
  <!--блок4-->

    <h2>
      Биография
    </h2>
    
    <p class="paragraph">
      Всем привет! Меня зовут Денис! С детства увдекаюсь качественной музыкой, видимо и поэтому я стал DJ! 
      С каких-то пор я начал продюссировать молодых и талантливых, а также писать авторские треки и биты и к ним текста!
      И вообще я много чем занимался, я был и руководителем группы и наставником и главным инженером и 
      энергетиком, в компах время от времени "колупался", и "колупался" в электронике и 
      технике, так же своими руками создал много акустических систем, сам всё это дело расчитывал и измерял, вся свето-техника, что связана со свето-диодами,
      сложил велосипед под себя и проехал тысячи киллометров на нем, типа ЗОЖ, люблю легкую аттлетику, а так я ГИК, люблю новые и свежие технологии,
      тестирую в основном мобильные камеры, а так я простой человек, люблю юмор, а так же увожу соседских девочек,
      а так хакер по жизни, вот решил исправится и стать Full-Stack разработчиком! Люблю бурбон, темное пиво и темненьких чик!
    </p>

    <div class="img-container">

      <a href="https://vk.com/djratek">
      <img class="circle-img" src=./img/no1.jpg alt="pictire1">
      </a>
     <img class="circle-img" src=./img/no2.jpg alt="pictire2">
     <img class="circle-img" src=./img/no3.jpg alt="pictire3">
    
    </div>

  </div>
  
  <div class="block1 no-padding-top" id="contact">

    <h2>
     Контакты
    </h2>

    <form action="/" method="POST" id="contact-form">
      <input type="text" name="FIO" placeholder="ФИО">
      <input type="email" name="email">
      <textarea name="message" placeholder="Сообщение"></textarea>
      <input type="submit" name="submit" id="submit"
    </form>

    <div class="block1 no-padding-top" id="partner">

      <h2>
        Мои Партнеры
      </h2>

      <a href="https://www.beatport.com/artist/ratek-fleek/753821">
      <img class="circle-img" src=./img/beatport.png alt="pictire11">
      </a>
      <a href="https://promodj.com/djratek">
      <img class="circle-img" src=./img/promodj.png alt="pictire22">
      </a>
      <a href="https://soundcloud.com/djratek">
      <img class="circle-img" src=./img/soundcloud.png alt="pictire33">
      </a>
      <a href="https://music.yandex.ru/artist/5406864">
      <img class="circle-img" src=./img/яндекс.png alt="pictire44">
      </a>
      <a href="https://podcasts.apple.com/ru/podcast/vip-electro-dj-ratek/id963580874">
      <img class="circle-img" src=./img/apple.png alt="pictire55">
      </a>
      <a href="https://artists.spotify.com/c/artist/3KfNOE8a2fU5oetyNPpWGD/profile/overview">
      <img class="circle-img" src=./img/spotify.png alt="pictire66">
      </a>
      <a href="https://vk.com/freakydeejays">
      <img class="circle-img" src=./img/freaky.jpg alt="pictire77">
      </a>
      <a href="https://www.djrating.ru/dj/9094#">
      <img class="circle-img" src=./img/топ100.jpg alt="pictire88">
      </a>

    </div>
    

    <a id="gototop" href="#navigation">
      ∧
    </a>

  </div>

</div>
<!--закончили верстку, ниже JS-->

<div class="other"> Мой сайт 2021@info связь со мной VK: <a href="https://www.vk.com/denisratskov" target=_blank">@denisratskov</a> Phone: +375 33 6624300 
(email) <a href="mailto:denisratskov@gmail.com"Mailto target="_blank">@denisratskov</a></div>

<script>
  alert("Пример кода")
  //типа того что-то, а дальще - больше
</script>

</body>

</html>
