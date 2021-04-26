# CSS-Particles-background
....html....
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <script src="script.js"></script>
    <div class="purple"></div>
<div class="medium-blue"></div>
<div class="light-blue"></div>
<div class="red"></div>
<div class="orange"></div>
<div class="yellow"></div>
<div class="cyan"></div>
<div class="light-green"></div>
<div class="lime"></div>
<div class="magenta"></div>
<div class="lightish-red"></div>
<div class="pink"></div>
  </body>
</html>
....css....
body {
  background: radial-gradient(circle, #167702, #1d6e24);
  overflow: hidden;
  position: relative;
  width: 100vw;
  height: 100vh;
}
body:active div,
body:active div::before,
body:active div::after {
  padding: 40px;
}

div,
div::before,
div::after {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  opacity: 0.9;
  transform-origin: top;
  transition: all 5s linear 0s;
}

.purple {
  -webkit-animation: rgb(248, 34, 34) linear 30s alternate infinite;
          animation: rgb(230, 18, 18) linear 30s alternate infinite;
  border: 2px solid #241379;
  border-radius: 100%;
  width: 18px;
  height: 18px;
  transform: translate3d(19vw, 62vh, 0);
  z-index: 5;
}

.purple::before {
  -webkit-animation: purple-pseudo linear 15s alternate infinite;
          animation: purple-pseudo linear 15s alternate infinite;
  background: #241379;
  border: 2px solid #241379;
  width: 22px;
  height: 9px;
  transform: translate3d(27vw, -32vh, 0) rotate(169deg);
}

.purple::after {
  -webkit-animation: purple-pseudo linear 20s alternate infinite;
          animation: purple-pseudo linear 20s alternate infinite;
  border: 2px solid #241379;
  width: 27px;
  height: 35px;
  transform: translate3d(80vw, -39vh, 0) rotate(346deg);
}

@-webkit-keyframes purple {
  50% {
    transform: translate3d(51vw, 68vh, 0);
  }
  100% {
    transform: translate3d(1vw, 10vh, 0);
  }
}

@keyframes purple {
  50% {
    transform: translate3d(51vw, 68vh, 0);
  }
  100% {
    transform: translate3d(1vw, 10vh, 0);
  }
}
@-webkit-keyframes purple-pseudo {
  33% {
    transform: translate3d(-46vw, 0vh, 0) rotate(356deg);
  }
  100% {
    transform: translate3d(17vw, 73vh, 0) rotate(241deg);
  }
}
@keyframes purple-pseudo {
  33% {
    transform: translate3d(-46vw, 0vh, 0) rotate(356deg);
  }
  100% {
    transform: translate3d(17vw, 73vh, 0) rotate(241deg);
  }
}
.medium-blue {
  -webkit-animation: medium-blue linear 30s alternate infinite;
          animation: medium-blue linear 30s alternate infinite;
  border: 2px solid #2185bf;
  border-radius: 100%;
  width: 49px;
  height: 49px;
  transform: translate3d(76vw, 23vh, 0);
  z-index: 2;
}

.medium-blue::before {
  -webkit-animation: medium-blue-pseudo linear 15s alternate infinite;
          animation: medium-blue-pseudo linear 15s alternate infinite;
  background: #2185bf;
  border: 2px solid #2185bf;
  width: 10px;
  height: 26px;
  transform: translate3d(-75vw, 42vh, 0) rotate(8deg);
}

.medium-blue::after {
  -webkit-animation: medium-blue-pseudo linear 20s alternate infinite;
          animation: medium-blue-pseudo linear 20s alternate infinite;
  border: 2px solid #2185bf;
  width: 11px;
  height: 32px;
  transform: translate3d(-53vw, 76vh, 0) rotate(73deg);
}

@-webkit-keyframes medium-blue {
  50% {
    transform: translate3d(14vw, 97vh, 0);
  }
  100% {
    transform: translate3d(31vw, 85vh, 0);
  }
}

@keyframes medium-blue {
  50% {
    transform: translate3d(14vw, 97vh, 0);
  }
  100% {
    transform: translate3d(31vw, 85vh, 0);
  }
}
@-webkit-keyframes medium-blue-pseudo {
  33% {
    transform: translate3d(58vw, -12vh, 0) rotate(210deg);
  }
  100% {
    transform: translate3d(20vw, 9vh, 0) rotate(121deg);
  }
}
@keyframes medium-blue-pseudo {
  33% {
    transform: translate3d(58vw, -12vh, 0) rotate(210deg);
  }
  100% {
    transform: translate3d(20vw, 9vh, 0) rotate(121deg);
  }
}
.light-blue {
  -webkit-animation: light-blue linear 30s alternate infinite;
          animation: light-blue linear 30s alternate infinite;
  border: 2px solid #1fbce1;
  border-radius: 100%;
  width: 46px;
  height: 46px;
  transform: translate3d(40vw, 9vh, 0);
  z-index: 12;
}

.light-blue::before {
  -webkit-animation: light-blue-pseudo linear 15s alternate infinite;
          animation: light-blue-pseudo linear 15s alternate infinite;
  background: #1fbce1;
  border: 2px solid #1fbce1;
  width: 29px;
  height: 48px;
  transform: translate3d(-38vw, 82vh, 0) rotate(130deg);
}

.light-blue::after {
  -webkit-animation: light-blue-pseudo linear 20s alternate infinite;
          animation: light-blue-pseudo linear 20s alternate infinite;
  border: 2px solid #1fbce1;
  width: 7px;
  height: 43px;
  transform: translate3d(56vw, 23vh, 0) rotate(91deg);
}

@-webkit-keyframes light-blue {
  50% {
    transform: translate3d(19vw, 59vh, 0);
  }
  100% {
    transform: translate3d(81vw, 76vh, 0);
  }
}

@keyframes light-blue {
  50% {
    transform: translate3d(19vw, 59vh, 0);
  }
  100% {
    transform: translate3d(81vw, 76vh, 0);
  }
}
@-webkit-keyframes light-blue-pseudo {
  33% {
    transform: translate3d(22vw, 22vh, 0) rotate(214deg);
  }
  100% {
    transform: translate3d(-20vw, -62vh, 0) rotate(347deg);
  }
}
@keyframes light-blue-pseudo {
  33% {
    transform: translate3d(22vw, 22vh, 0) rotate(214deg);
  }
  100% {
    transform: translate3d(-20vw, -62vh, 0) rotate(347deg);
  }
}
.red {
  -webkit-animation: red linear 30s alternate infinite;
          animation: red linear 30s alternate infinite;
  border: 2px solid #b62f56;
  border-radius: 100%;
  width: 34px;
  height: 34px;
  transform: translate3d(18vw, 10vh, 0);
  z-index: 11;
}

.red::before {
  -webkit-animation: red-pseudo linear 15s alternate infinite;
          animation: red-pseudo linear 15s alternate infinite;
  background: #b62f56;
  border: 2px solid #b62f56;
  width: 24px;
  height: 16px;
  transform: translate3d(74vw, 60vh, 0) rotate(8deg);
}

.red::after {
  -webkit-animation: red-pseudo linear 20s alternate infinite;
          animation: red-pseudo linear 20s alternate infinite;
  border: 2px solid #b62f56;
  width: 25px;
  height: 9px;
  transform: translate3d(69vw, 43vh, 0) rotate(327deg);
}

@-webkit-keyframes red {
  50% {
    transform: translate3d(86vw, 38vh, 0);
  }
  100% {
    transform: translate3d(100vw, 46vh, 0);
  }
}

@keyframes red {
  50% {
    transform: translate3d(86vw, 38vh, 0);
  }
  100% {
    transform: translate3d(100vw, 46vh, 0);
  }
}
@-webkit-keyframes red-pseudo {
  33% {
    transform: translate3d(-86vw, 22vh, 0) rotate(17deg);
  }
  100% {
    transform: translate3d(-48vw, 38vh, 0) rotate(179deg);
  }
}
@keyframes red-pseudo {
  33% {
    transform: translate3d(-86vw, 22vh, 0) rotate(17deg);
  }
  100% {
    transform: translate3d(-48vw, 38vh, 0) rotate(179deg);
  }
}
.orange {
  -webkit-animation: orange linear 30s alternate infinite;
          animation: orange linear 30s alternate infinite;
  border: 2px solid #d5764c;
  border-radius: 100%;
  width: 38px;
  height: 38px;
  transform: translate3d(80vw, 89vh, 0);
  z-index: 8;
}

.orange::before {
  -webkit-animation: orange-pseudo linear 15s alternate infinite;
          animation: orange-pseudo linear 15s alternate infinite;
  background: #d5764c;
  border: 2px solid #d5764c;
  width: 47px;
  height: 26px;
  transform: translate3d(-44vw, -73vh, 0) rotate(205deg);
}

.orange::after {
  -webkit-animation: orange-pseudo linear 20s alternate infinite;
          animation: orange-pseudo linear 20s alternate infinite;
  border: 2px solid #d5764c;
  width: 26px;
  height: 28px;
  transform: translate3d(-35vw, -64vh, 0) rotate(97deg);
}

@-webkit-keyframes orange {
  50% {
    transform: translate3d(36vw, 46vh, 0);
  }
  100% {
    transform: translate3d(56vw, 58vh, 0);
  }
}

@keyframes orange {
  50% {
    transform: translate3d(36vw, 46vh, 0);
  }
  100% {
    transform: translate3d(56vw, 58vh, 0);
  }
}
@-webkit-keyframes orange-pseudo {
  33% {
    transform: translate3d(51vw, 16vh, 0) rotate(63deg);
  }
  100% {
    transform: translate3d(-35vw, -11vh, 0) rotate(58deg);
  }
}
@keyframes orange-pseudo {
  33% {
    transform: translate3d(51vw, 16vh, 0) rotate(63deg);
  }
  100% {
    transform: translate3d(-35vw, -11vh, 0) rotate(58deg);
  }
}
.yellow {
  -webkit-animation: yellow linear 30s alternate infinite;
          animation: yellow linear 30s alternate infinite;
  border: 2px solid #ffd53e;
  border-radius: 100%;
  width: 13px;
  height: 13px;
  transform: translate3d(85vw, 65vh, 0);
  z-index: 11;
}

.yellow::before {
  -webkit-animation: yellow-pseudo linear 15s alternate infinite;
          animation: yellow-pseudo linear 15s alternate infinite;
  background: #ffd53e;
  border: 2px solid #ffd53e;
  width: 12px;
  height: 6px;
  transform: translate3d(-18vw, -57vh, 0) rotate(66deg);
}

.yellow::after {
  -webkit-animation: yellow-pseudo linear 20s alternate infinite;
          animation: yellow-pseudo linear 20s alternate infinite;
  border: 2px solid #ffd53e;
  width: 9px;
  height: 9px;
  transform: translate3d(-51vw, -20vh, 0) rotate(74deg);
}

@-webkit-keyframes yellow {
  50% {
    transform: translate3d(91vw, 9vh, 0);
  }
  100% {
    transform: translate3d(85vw, 62vh, 0);
  }
}

@keyframes yellow {
  50% {
    transform: translate3d(91vw, 9vh, 0);
  }
  100% {
    transform: translate3d(85vw, 62vh, 0);
  }
}
@-webkit-keyframes yellow-pseudo {
  33% {
    transform: translate3d(-65vw, -8vh, 0) rotate(308deg);
  }
  100% {
    transform: translate3d(-14vw, -50vh, 0) rotate(88deg);
  }
}
@keyframes yellow-pseudo {
  33% {
    transform: translate3d(-65vw, -8vh, 0) rotate(308deg);
  }
  100% {
    transform: translate3d(-14vw, -50vh, 0) rotate(88deg);
  }
}
.cyan {
  -webkit-animation: cyan linear 30s alternate infinite;
          animation: cyan linear 30s alternate infinite;
  border: 2px solid #78ffba;
  border-radius: 100%;
  width: 5px;
  height: 5px;
  transform: translate3d(94vw, 50vh, 0);
  z-index: 3;
}

.cyan::before {
  -webkit-animation: cyan-pseudo linear 15s alternate infinite;
          animation: cyan-pseudo linear 15s alternate infinite;
  background: #78ffba;
  border: 2px solid #78ffba;
  width: 23px;
  height: 9px;
  transform: translate3d(-27vw, 26vh, 0) rotate(351deg);
}

.cyan::after {
  -webkit-animation: cyan-pseudo linear 20s alternate infinite;
          animation: cyan-pseudo linear 20s alternate infinite;
  border: 2px solid #78ffba;
  width: 32px;
  height: 20px;
  transform: translate3d(-62vw, 49vh, 0) rotate(83deg);
}

@-webkit-keyframes cyan {
  50% {
    transform: translate3d(40vw, 70vh, 0);
  }
  100% {
    transform: translate3d(68vw, 72vh, 0);
  }
}

@keyframes cyan {
  50% {
    transform: translate3d(40vw, 70vh, 0);
  }
  100% {
    transform: translate3d(68vw, 72vh, 0);
  }
}
@-webkit-keyframes cyan-pseudo {
  33% {
    transform: translate3d(59vw, -11vh, 0) rotate(157deg);
  }
  100% {
    transform: translate3d(-20vw, 6vh, 0) rotate(246deg);
  }
}
@keyframes cyan-pseudo {
  33% {
    transform: translate3d(59vw, -11vh, 0) rotate(157deg);
  }
  100% {
    transform: translate3d(-20vw, 6vh, 0) rotate(246deg);
  }
}
.light-green {
  -webkit-animation: light-green linear 30s alternate infinite;
          animation: light-green linear 30s alternate infinite;
  border: 2px solid #98fd85;
  border-radius: 100%;
  width: 26px;
  height: 26px;
  transform: translate3d(28vw, 13vh, 0);
  z-index: 10;
}

.light-green::before {
  -webkit-animation: light-green-pseudo linear 15s alternate infinite;
          animation: light-green-pseudo linear 15s alternate infinite;
  background: #98fd85;
  border: 2px solid #98fd85;
  width: 11px;
  height: 16px;
  transform: translate3d(15vw, 6vh, 0) rotate(82deg);
}

.light-green::after {
  -webkit-animation: light-green-pseudo linear 20s alternate infinite;
          animation: light-green-pseudo linear 20s alternate infinite;
  border: 2px solid #98fd85;
  width: 19px;
  height: 29px;
  transform: translate3d(51vw, 81vh, 0) rotate(292deg);
}

@-webkit-keyframes light-green {
  50% {
    transform: translate3d(35vw, 45vh, 0);
  }
  100% {
    transform: translate3d(56vw, 23vh, 0);
  }
}

@keyframes light-green {
  50% {
    transform: translate3d(35vw, 45vh, 0);
  }
  100% {
    transform: translate3d(56vw, 23vh, 0);
  }
}
@-webkit-keyframes light-green-pseudo {
  33% {
    transform: translate3d(-16vw, -37vh, 0) rotate(282deg);
  }
  100% {
    transform: translate3d(19vw, 6vh, 0) rotate(51deg);
  }
}
@keyframes light-green-pseudo {
  33% {
    transform: translate3d(-16vw, -37vh, 0) rotate(282deg);
  }
  100% {
    transform: translate3d(19vw, 6vh, 0) rotate(51deg);
  }
}
.lime {
  -webkit-animation: lime linear 30s alternate infinite;
          animation: lime linear 30s alternate infinite;
  border: 2px solid #befb46;
  border-radius: 100%;
  width: 33px;
  height: 33px;
  transform: translate3d(37vw, 78vh, 0);
  z-index: 2;
}

.lime::before {
  -webkit-animation: lime-pseudo linear 15s alternate infinite;
          animation: lime-pseudo linear 15s alternate infinite;
  background: #befb46;
  border: 2px solid #befb46;
  width: 16px;
  height: 17px;
  transform: translate3d(62vw, -42vh, 0) rotate(296deg);
}

.lime::after {
  -webkit-animation: lime-pseudo linear 20s alternate infinite;
          animation: lime-pseudo linear 20s alternate infinite;
  border: 2px solid #befb46;
  width: 29px;
  height: 19px;
  transform: translate3d(36vw, -44vh, 0) rotate(205deg);
}

@-webkit-keyframes lime {
  50% {
    transform: translate3d(26vw, 37vh, 0);
  }
  100% {
    transform: translate3d(63vw, 9vh, 0);
  }
}

@keyframes lime {
  50% {
    transform: translate3d(26vw, 37vh, 0);
  }
  100% {
    transform: translate3d(63vw, 9vh, 0);
  }
}
@-webkit-keyframes lime-pseudo {
  33% {
    transform: translate3d(66vw, -35vh, 0) rotate(112deg);
  }
  100% {
    transform: translate3d(10vw, 21vh, 0) rotate(3deg);
  }
}
@keyframes lime-pseudo {
  33% {
    transform: translate3d(66vw, -35vh, 0) rotate(112deg);
  }
  100% {
    transform: translate3d(10vw, 21vh, 0) rotate(3deg);
  }
}
.magenta {
  -webkit-animation: magenta linear 30s alternate infinite;
          animation: magenta linear 30s alternate infinite;
  border: 2px solid #6c046c;
  border-radius: 100%;
  width: 37px;
  height: 37px;
  transform: translate3d(13vw, 6vh, 0);
  z-index: 12;
}

.magenta::before {
  -webkit-animation: magenta-pseudo linear 15s alternate infinite;
          animation: magenta-pseudo linear 15s alternate infinite;
  background: #6c046c;
  border: 2px solid #6c046c;
  width: 42px;
  height: 17px;
  transform: translate3d(5vw, 87vh, 0) rotate(287deg);
}

.magenta::after {
  -webkit-animation: magenta-pseudo linear 20s alternate infinite;
          animation: magenta-pseudo linear 20s alternate infinite;
  border: 2px solid #6c046c;
  width: 33px;
  height: 26px;
  transform: translate3d(71vw, 72vh, 0) rotate(220deg);
}

@-webkit-keyframes magenta {
  50% {
    transform: translate3d(68vw, 14vh, 0);
  }
  100% {
    transform: translate3d(39vw, 10vh, 0);
  }
}

@keyframes magenta {
  50% {
    transform: translate3d(68vw, 14vh, 0);
  }
  100% {
    transform: translate3d(39vw, 10vh, 0);
  }
}
@-webkit-keyframes magenta-pseudo {
  33% {
    transform: translate3d(26vw, 81vh, 0) rotate(302deg);
  }
  100% {
    transform: translate3d(-19vw, 46vh, 0) rotate(20deg);
  }
}
@keyframes magenta-pseudo {
  33% {
    transform: translate3d(26vw, 81vh, 0) rotate(302deg);
  }
  100% {
    transform: translate3d(-19vw, 46vh, 0) rotate(20deg);
  }
}
.lightish-red {
  -webkit-animation: lightish-red linear 30s alternate infinite;
          animation: lightish-red linear 30s alternate infinite;
  border: 2px solid #f04c81;
  border-radius: 100%;
  width: 42px;
  height: 42px;
  transform: translate3d(31vw, 40vh, 0);
  z-index: 7;
}

.lightish-red::before {
  -webkit-animation: lightish-red-pseudo linear 15s alternate infinite;
          animation: lightish-red-pseudo linear 15s alternate infinite;
  background: #f04c81;
  border: 2px solid #f04c81;
  width: 21px;
  height: 19px;
  transform: translate3d(2vw, -35vh, 0) rotate(186deg);
}

.lightish-red::after {
  -webkit-animation: lightish-red-pseudo linear 20s alternate infinite;
          animation: lightish-red-pseudo linear 20s alternate infinite;
  border: 2px solid #f04c81;
  width: 9px;
  height: 15px;
  transform: translate3d(-23vw, 36vh, 0) rotate(278deg);
}

@-webkit-keyframes lightish-red {
  50% {
    transform: translate3d(51vw, 77vh, 0);
  }
  100% {
    transform: translate3d(31vw, 25vh, 0);
  }
}

@keyframes lightish-red {
  50% {
    transform: translate3d(51vw, 77vh, 0);
  }
  100% {
    transform: translate3d(31vw, 25vh, 0);
  }
}
@-webkit-keyframes lightish-red-pseudo {
  33% {
    transform: translate3d(-29vw, -64vh, 0) rotate(304deg);
  }
  100% {
    transform: translate3d(-1vw, 46vh, 0) rotate(184deg);
  }
}
@keyframes lightish-red-pseudo {
  33% {
    transform: translate3d(-29vw, -64vh, 0) rotate(304deg);
  }
  100% {
    transform: translate3d(-1vw, 46vh, 0) rotate(184deg);
  }
}
.pink {
  -webkit-animation: pink linear 30s alternate infinite;
          animation: pink linear 30s alternate infinite;
  border: 2px solid #ff4293;
  border-radius: 100%;
  width: 25px;
  height: 25px;
  transform: translate3d(89vw, 92vh, 0);
  z-index: 5;
}

.pink::before {
  -webkit-animation: pink-pseudo linear 15s alternate infinite;
          animation: pink-pseudo linear 15s alternate infinite;
  background: #ff4293;
  border: 2px solid #ff4293;
  width: 20px;
  height: 8px;
  transform: translate3d(-42vw, -15vh, 0) rotate(198deg);
}

.pink::after {
  -webkit-animation: pink-pseudo linear 20s alternate infinite;
          animation: pink-pseudo linear 20s alternate infinite;
  border: 2px solid #ff4293;
  width: 28px;
  height: 23px;
  transform: translate3d(-50vw, -52vh, 0) rotate(65deg);
}

@-webkit-keyframes pink {
  50% {
    transform: translate3d(63vw, 49vh, 0);
  }
  100% {
    transform: translate3d(74vw, 51vh, 0);
  }
}

@keyframes pink {
  50% {
    transform: translate3d(63vw, 49vh, 0);
  }
  100% {
    transform: translate3d(74vw, 51vh, 0);
  }
}
@-webkit-keyframes pink-pseudo {
  33% {
    transform: translate3d(-8vw, -21vh, 0) rotate(279deg);
  }
  100% {
    transform: translate3d(-55vw, -13vh, 0) rotate(357deg);
  }
}
@keyframes pink-pseudo {
  33% {
    transform: translate3d(-8vw, -21vh, 0) rotate(279deg);
  }
  100% {
    transform: translate3d(-55vw, -13vh, 0) rotate(357deg);
  }
}
