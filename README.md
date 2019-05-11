<!DOCTYPE html><!--type de document (HyperText Markup Langage-->
<html><!--conteneur de la page web-->

 <head><!--informations sur la page et contenu CSS (Cascading Style Sheet)-->
  <title>Jean-Philippe Mary</title>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!--module d'adaptation au format smartphone-->
  
  <style> /*Contenu de la mise en page en CSS */
   
   body {
    background-image: -webkit-linear-gradient(80deg, rgb(170, 150, 130), rgb(255, 250, 220));
    background-image: -o-linear-gradient(80deg, rgb(170, 150, 130), rgb(255, 250, 220));
    background-image: linear-gradient(10deg, rgb(170, 150, 130), rgb(255, 250, 220));
    background-attachment: fixed;
    background-size: 100%;
    font-family:Tahoma, sans-serif !important;
    color: #432;
    width: auto;
    min-width: 720px;
   }
   
   h3 {
    background-color: rgba(255, 255, 255, 0.2);
    margin-top: 0px;
    padding-top: 10px;
    padding-bottom: 10px;
    margin-left: -20px;
    padding-left: 20px;
    margin-right: -20px;
   }
   
   h4 {
    background-color: #321;
    color: white;
    padding-top: 20px;
    padding-bottom: 10px;
    padding-left: 20px;
    margin-top: 20px;
    margin-bottom: 0px;
   }
   
   th{
    border-bottom: 1px solid black;
    background-color: rgba(60, 40, 20, 0.1);
    padding: 25px 20px;
    text-align: center;
    font-weight: bold;
    text-transform: uppercase;
   }
   .head-td{
    padding:3px 20px 2px 10px;
    color: #632;
    font-size: 11.5px;
    font-weight: bold;
    background-color: rgba(60, 40, 20, 0.1);
    text-transform: uppercase;
   }
   .mid-td{
    padding:5px 20px 5px 20px;
    font-size: 13px;
    background-color: rgba(60, 40, 20, 0.05);
    text-transform: uppercase;
   }
   .sub-td{
    padding:0px 20px 10px 20px;
    font-size: 12px;
    border-bottom: 1px solid #876;
   }
   .p-table{
    padding:O;
    margin:0;
   }
   table{
    width: calc(100% - 10px);
    border-collapse: collapse;
    margin-bottom: 20px;
   }
   .parcours-left{
    width: 80px;
    padding-left: 10px;
    font-size:13px;
    border-right: 10px solid #876;
    border-bottom: 1px solid #876;
   }
   .table-link{
    text-decoration: none;
    font-weight: bold;
    color: #832;
   }
   
   .style-text {
    color: #833;
    font-size: 16px;
    text-decoration: none;
   }
   
   .screenbox {
    width: auto;
    min-width: 370px;
    min-height: 380px;
    margin: 110px 90px 3% 10%;
    overflow: scroll;
    border-radius: 10% 1% 10% 1%;
    border: 3px solid #987;
    -webkit-box-shadow: 0px 5px RGBa(20, 19, 18, 0.5) inset;
            box-shadow: 0px 5px RGBa(20, 19, 18, 0.5) inset;
    -webkit-animation-name: screen-start;
            animation-name: screen-start;
    -webkit-animation-duration: 3s;
            animation-duration: 3s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes screen-start {
    from {margin: 50px 90px 3% 10%; -webkit-box-shadow: -3px 50px RGBa(20, 19, 18, 0.1); box-shadow: -3px 50px RGBa(20, 19, 18, 0.1);}
    to {margin: 110px 90px 3% 10%; -webkit-box-shadow: -3px 5px RGBa(20, 19, 18, 0.3); box-shadow: -3px 5px RGBa(20, 19, 18, 0.3);}
   }
   
   @keyframes screen-start {
    from {margin: 50px 90px 3% 10%; -webkit-box-shadow: -3px 50px RGBa(20, 19, 18, 0.1); box-shadow: -3px 50px RGBa(20, 19, 18, 0.1);}
    to {margin: 110px 90px 3% 10%; -webkit-box-shadow: -3px 5px RGBa(20, 19, 18, 0.3); box-shadow: -3px 5px RGBa(20, 19, 18, 0.3);}
   }
   
   .id{
    z-index: 9;
    overflow: hidden;
    position: absolute;
    top: 15px;
    left: 20px;
    height: 90px;
    width: 90px;
    border-radius: 50%;
    background-image: -webkit-linear-gradient(80deg, rgb(170, 150, 130), rgb(255, 250, 220));
    background-image: -o-linear-gradient(80deg, rgb(170, 150, 130), rgb(255, 250, 220));
    background-image: linear-gradient(10deg, rgb(170, 150, 130), rgb(255, 250, 220));
    background-attachment: fixed;
    background-size: 100%;
    border: 3px solid #987;
    -webkit-box-shadow: -20px 80px RGBa(20, 19, 18, 0.3) inset;
            box-shadow: -20px 80px RGBa(20, 19, 18, 0.3) inset;
    -webkit-animation-name: hublot-photo;
            animation-name: hublot-photo;
    -webkit-animation-duration: 2s;
            animation-duration: 2s;
    -webkit-animation-delay: 0s;
            animation-delay: 0s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes hublot-photo {
    from {-webkit-box-shadow: -20px 80px RGBa(20, 19, 18, 0.3) inset;box-shadow: -20px 80px RGBa(20, 19, 18, 0.3) inset;}
    to {-webkit-box-shadow: 0px 0px RGBa(20, 19, 18, 0.3) inset;box-shadow: 0px 0px RGBa(20, 19, 18, 0.3) inset;}
   }
   
   @keyframes hublot-photo {
    from {-webkit-box-shadow: -20px 80px RGBa(20, 19, 18, 0.3) inset;box-shadow: -20px 80px RGBa(20, 19, 18, 0.3) inset;}
    to {-webkit-box-shadow: 0px 0px RGBa(20, 19, 18, 0.3) inset;box-shadow: 0px 0px RGBa(20, 19, 18, 0.3) inset;}
   }
   
   .photo-id {
    position: absolute;
    background-image: url(https://i.ibb.co/PY9vbSw/Photo-ID.jpg);
    background-size: 120px;
    background-position: -5px 0px;
    top: 43px;
    left: -4px;
    width: 92px;
    height: 0px;
    border-radius: 0%;
    -webkit-transform: rotate(-45deg);
        -ms-transform: rotate(-45deg);
            transform: rotate(-45deg);
    border: 3px solid #987;
    -webkit-box-shadow: 0px 5px RGBa(20, 19, 18, 0.5) inset;
            box-shadow: 0px 5px RGBa(20, 19, 18, 0.5) inset;
    -webkit-animation-name: photo-start;
            animation-name: photo-start;
    -webkit-animation-duration: 0.4s;
            animation-duration: 0.4s;
    -webkit-animation-delay: 2.2s;
            animation-delay: 2.2s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes photo-start {
    from {border-radius: 50%; top: 42px; height: 0px; -webkit-transform: rotate(-45deg); transform: rotate(-45deg);-webkit-box-shadow: 0px 50px RGBa(20, 19, 18, 0.5) inset;box-shadow: 0px 50px RGBa(20, 19, 18, 0.5) inset;}
    to {border-radius: 50%; top:-4px; height: 92px; -webkit-transform: rotate(0deg); transform: rotate(0deg);-webkit-box-shadow: 0px 5px RGBa(20, 19, 18, 0.5) inset;box-shadow: 0px 5px RGBa(20, 19, 18, 0.5) inset;}
   }
   
   @keyframes photo-start {
    from {border-radius: 50%; top: 42px; height: 0px; -webkit-transform: rotate(-45deg); transform: rotate(-45deg);-webkit-box-shadow: 0px 50px RGBa(20, 19, 18, 0.5) inset;box-shadow: 0px 50px RGBa(20, 19, 18, 0.5) inset;}
    to {border-radius: 50%; top:-4px; height: 92px; -webkit-transform: rotate(0deg); transform: rotate(0deg);-webkit-box-shadow: 0px 5px RGBa(20, 19, 18, 0.5) inset;box-shadow: 0px 5px RGBa(20, 19, 18, 0.5) inset;}
   }
   
   .name-box{
    overflow: hidden;
    -o-text-overflow: ellipsis;
       text-overflow: ellipsis;
    font-size:10px;
    padding-left: 0px;
    position: absolute;
    z-index: -1;
    top: 17px;
    left: 80px;
    width: 0px;
    height: 80px;
    border-top: 1px solid RGBa(20, 19, 18, 0.3);
    color: #876;
    -webkit-animation-name: name-start;
            animation-name: name-start;
    -webkit-animation-duration: 1s;
            animation-duration: 1s;
    -webkit-animation-delay: 2.35s;
            animation-delay: 2.35s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes name-start {
    from {padding-left: 45px; width: 0px;}
    to {padding-left: 45px; width: 240px;}
   }
   
   @keyframes name-start {
    from {padding-left: 45px; width: 0px;}
    to {padding-left: 45px; width: 240px;}
   }
   
   #name-screen {
    position: static;
    overflow: hidden;
    height: 50px;
   }
   #name {
    position: absolute;
    overflow: hidden;
    top: 27px;
    height: 0px;
    -webkit-animation-name: name-coucou;
            animation-name: name-coucou;
    -webkit-animation-duration: 1s;
            animation-duration: 1s;
    -webkit-animation-delay: 3s;
            animation-delay: 3s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes name-coucou {
    from {top: 27px; height: 0px;}
    to {top: 0px; height: 27px;}
   }
   
   @keyframes name-coucou {
    from {top: 27px; height: 0px;}
    to {top: 0px; height: 27px;}
   }
   #bar {
    position: relative;
    top: -10px;
    left: -35px;
    width: auto;
    height: 3px;
    -webkit-box-shadow: 0px 0px 0px 3px #987 inset;
            box-shadow: 0px 0px 0px 3px #987 inset;
   }
   #info-screen {
    position: relative;
    overflow: hidden;
    top: -10px;
    height: 30px;
   }
   #info {
    opacity:0;
    font-size: 14px;
    position: absolute;
    overflow: visible;
    top: -0px;
    height: 30px;
    -webkit-animation-name: info-coucou;
            animation-name: info-coucou;
    -webkit-animation-duration: 1s;
            animation-duration: 1s;
    -webkit-animation-delay: 3.5s;
            animation-delay: 3.5s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   @-webkit-keyframes info-coucou {
    from {opacity:0;}
    to {opacity:1;}
   }
   @keyframes info-coucou {
    from {opacity:0;}
    to {opacity:1;}
   }
   
   .sommaire-box {
    z-index: 10;
    overflow: visible;
    position: relative;
    float: left;
    min-width: 250px;
    max-width: 260px;
    width: 20%;
    height: 320px;
    margin: 30px 4% 0% 1%;
    border-radius: 10% 1% 1% 10%;
    -webkit-box-shadow: 0px 3px RGBa(20, 19, 18, 0.3) inset;
            box-shadow: 0px 3px RGBa(20, 19, 18, 0.3) inset;
    -webkit-animation-name: sommaire-start;
            animation-name: sommaire-start;
    -webkit-animation-duration: 3s;
            animation-duration: 3s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes sommaire-start {
    from {margin: 90px 4% 0% 1%; -webkit-box-shadow: 0px 30px RGBa(20, 19, 18, 0.3) inset; box-shadow: 0px 30px RGBa(20, 19, 18, 0.3) inset;}
    to {margin: 30px 4% 0% 1%; -webkit-box-shadow: 0px 3px RGBa(20, 19, 18, 0.3) inset; box-shadow: 0px 3px RGBa(20, 19, 18, 0.3) inset;}
   }
   
   @keyframes sommaire-start {
    from {margin: 90px 4% 0% 1%; -webkit-box-shadow: 0px 30px RGBa(20, 19, 18, 0.3) inset; box-shadow: 0px 30px RGBa(20, 19, 18, 0.3) inset;}
    to {margin: 30px 4% 0% 1%; -webkit-box-shadow: 0px 3px RGBa(20, 19, 18, 0.3) inset; box-shadow: 0px 3px RGBa(20, 19, 18, 0.3) inset;}
   }
   
   .menu-text {
    margin-left: -30px;
    text-align: left;
    color: #432;
    text-decoration: none;
    font-size: 100%;
    -webkit-transition: font-size 0.5s, color 1s;
    -o-transition: font-size 0.5s, color 1s;
    transition: font-size 0.5s, color 1s;
   }
   
   .menu-text:hover {
    color: #000;
    font-size: 110%;
   }
   
   #menu-box{
    -webkit-animation-name: titles-start;
            animation-name: titles-start;
    -webkit-animation-duration: 3s;
            animation-duration: 3s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes titles-start {
    from {margin-top: 70%; opacity:0;}
    to {margin-top: 50%;}
   }
   
   @keyframes titles-start {
    from {margin-top: 70%; opacity:0;}
    to {margin-top: 50%;}
   }
   
   
   .style-list{
    list-style: none;
   }
   
   .sub-screen{
    z-index: 10;
    overflow: hidden;
    position: relative;
    width: auto;
    height: 360px;
    margin: 1% 1% 1% 1%;
    border-radius: 10% 1% 10% 1%;
    border: 1px solid #987;
   }
   
   .megapage{
    height: 9000px;
    width: auto;
    -webkit-transition: position 1s;
    -o-transition: position 1s;
    transition: position 1s;
   }
   
   .box-page{
    text-align: justify;
    text-shadow: -0.5px 1px 2px rgba(000, 000, 000, 0.05);
    padding: 19px;
    width: auto;
    height: 360px;
    overflow-y: auto;
    background-color: RGBa(255, 255, 255, 0.1);
   }
   .box-page::-webkit-scrollbar {
    -webkit-appearance: none;
   }

   .box-page::-webkit-scrollbar:vertical {
    width: 11px;
    margin: 0;
    padding: 0;
   }

   .box-page::-webkit-scrollbar-thumb {
    border: 1px solid #876;
    background-color: rgba(0, 0, 0, .5);
   }
   
   
   .rotor{
    clear:both;
    z-index: 8;
    position: absolute;
    top: 4px;
    left: 8px;
    width: 150px;
    height: 75px;
    border-top-left-radius: 300px;
    -webkit-box-shadow: 0px 3px RGBa(20, 19, 18, 0.3) inset;
            box-shadow: 0px 3px RGBa(20, 19, 18, 0.3) inset;
    -webkit-animation-name: rotor-start;
            animation-name: rotor-start;
    -webkit-animation-duration: 3.2s;
            animation-duration: 3.2s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes rotor-start {
    from {left: -90px; top: -20px; -webkit-transform: rotate(-40deg); transform: rotate(-40deg)}
    to {left: 4px; top: 4px; -webkit-transform: rotate(0deg); transform: rotate(0deg)}
   }
   
   @keyframes rotor-start {
    from {left: -90px; top: -20px; -webkit-transform: rotate(-40deg); transform: rotate(-40deg)}
    to {left: 4px; top: 4px; -webkit-transform: rotate(0deg); transform: rotate(0deg)}
   }
   
   .div-menu {
    position: absolute;
    top:50%;
    -webkit-transform: translateY(-50%);
        -ms-transform: translateY(-50%);
            transform: translateY(-50%);
    float: left;
    width:240px;
    border-left: 10px solid #987;
    opacity: 0;
    -webkit-animation-name: div-menu-start;
            animation-name: div-menu-start;
    -webkit-animation-delay: 3s;
            animation-delay: 3s;
    -webkit-animation-duration: 3s;
            animation-duration: 3s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes div-menu-start {
    from {opacity: 0;}
    to {opacity: 1;}
   }
   
   @keyframes div-menu-start {
    from {opacity: 0;}
    to {opacity: 1;}
   }
   .p-menu {
    margin:0;
    padding:0;
    height:0;
    padding:0 7px;
    overflow:hidden;
    -webkit-transition:height .4s ease-out, padding .4s ease-out;
    -o-transition:height .4s ease-out, padding .4s ease-out;
    transition:height .4s ease-out, padding .4s ease-out;
   }
   .h1-menu {
    margin: 0;
    padding:0;
    font-size:1em;
    -webkit-transition:font-size .4s ease-out;
    -o-transition:font-size .4s ease-out;
    transition:font-size .4s ease-out;
   }
   .a-banner {
    display:block;
    height:23px;
    line-height:23px;
    margin-left: 7px;
    padding-bottom: 3px;
    color:#432;
    text-decoration:none;
    text-align:left;
    text-shadow:0 1px 0 rgba(255,255,255,.5);
    border-bottom: 2px solid #987;
    -webkit-transition:margin-left .4s ease-out;
    -o-transition:margin-left .4s ease-out;
    transition:margin-left .4s ease-out;
   }
   .a-banner:hover, .a-banner:focus {
    opacity:.9;
    font-size: 120%;
   }
   #menu-biographie:target + .p-menu {
    height:90px;
   }
   #menu-interets:target + .p-menu {
    height:110px;
   }


   .menu-focus{
    font-family:Tahoma, sans-serif !important;
    text-align: left;
    color: #432;
    font-size: 90%;
    text-decoration: none;
    -webkit-transition:font-size .4s ease-out;
    -o-transition:font-size .4s ease-out;
    transition:font-size .4s ease-out;
   }
   .menu-focus:hover{
    font-size: 95%;
   }
   
   #ancre0{
    padding-top: 90px;
    text-align: center;
    font-size: 30px;
    color: rgba(000, 000, 000, 0);
    text-shadow: -0.5px 1px 2px rgba(000, 000, 000, 0);
    -webkit-animation-name: bienvenue;
            animation-name: bienvenue;
    -webkit-animation-duration: 3.2s;
            animation-duration: 3.2s;
    -webkit-animation-delay: 1s;
            animation-delay: 1s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   @-webkit-keyframes bienvenue {
    from {color: rgba(000, 000, 000, 0); text-shadow: -0.5px 1px 2px rgba(000, 000, 000, 0);}
    to {color: rgba(060, 040, 020, 0.4)}
   }
   @keyframes bienvenue {
    from {color: rgba(000, 000, 000, 0); text-shadow: -0.5px 1px 2px rgba(000, 000, 000, 0);}
    to {color: rgba(060, 040, 020, 0.4)}
   }
   .reflet, .reflet:before, .reflet span {
    display: block;
    margin: 0;
    padding: 0;
   }
   .reflet, .reflet:before, .reflet:after {
    position: relative;
   }
   .reflet {
    top: -30px;
   }
   .reflet:before {
    content: 'Bienvenue';
    opacity: 0;
    text-shadow: 0px 0px 5px rgba(060, 040, 020, 0);
    top: 125px;
    -webkit-transform: scale(1, -1);
        -ms-transform: scale(1, -1);
            transform: scale(1, -1);
    -webkit-backface-visibility: visible;
            backface-visibility: visible;
    z-index: 1;
    -webkit-animation-name: bienvenue-reflet;
            animation-name: bienvenue-reflet;
    -webkit-animation-duration: 3.7s;
            animation-duration: 3.7s;
    -webkit-animation-delay: 1s;
            animation-delay: 1s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   @-webkit-keyframes bienvenue-reflet {
    from {opacity: 0; text-shadow: 0px 0px 5px rgba(060, 040, 020, 0);}
    to {opacity: 0.1; text-shadow: 0px 0px 5px rgba(060, 040, 020, 1);}
   }
   @keyframes bienvenue-reflet {
    from {opacity: 0; text-shadow: 0px 0px 5px rgba(060, 040, 020, 0);}
    to {opacity: 0.1; text-shadow: 0px 0px 5px rgba(060, 040, 020, 1);}
   }
   
   
   #invader{
    float: left;
    height: 30%;
    shape-outside: url(https://i.ibb.co/3dq8tYM/32287-5-space-invaders-photos-thumb.png);
    shape-image-threshold: 0.5;
    shape-margin: 10px;
    margin-right: 20px;
   }
   
   #reaktor{
    float: left;
    height: 30%;
    shape-outside: url(https://i.ibb.co/8rM65nP/reaktor.png);
    shape-image-threshold: 0.5;
    shape-margin: 10px;
    margin-right: 20px;
   }
   
   #lemur{
    float: left;
    height: 30%;
    shape-outside: url(https://i.ibb.co/THQhLr9/lemur.png);
    shape-image-threshold: 0.5;
    shape-margin: 10px;
    margin-right: 20px;
   }
   
   
   
   .temperature{
    position:fixed;
    z-index: -2;
    width: 100%;
    height: 100%;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    margin: 0;
    padding: 0;
    background-image: -webkit-linear-gradient(80deg, rgb(70, 150, 130), rgb(255, 250, 220));
    background-image: -o-linear-gradient(80deg, rgb(70, 150, 130), rgb(255, 250, 220));
    background-image: linear-gradient(10deg, rgb(70, 150, 130), rgb(255, 250, 220));
    background-attachment: fixed;
    background-size: 100%;
    opacity: 0;
    -webkit-animation-name: temp-start;
            animation-name: temp-start;
    -webkit-animation-duration: 3s;
            animation-duration: 3s;
    -webkit-animation-timing-function: ease;
            animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
            animation-iteration-count: 1;
    -webkit-animation-fill-mode: forwards;
            animation-fill-mode: forwards;
   }
   
   @-webkit-keyframes temp-start {
    from {opacity: 1;}
    to {opacity: 0;}
   }
   
   @keyframes temp-start {
    from {opacity: 1;}
    to {opacity: 0;}
   }
   
   #facebook, #flikr, #linkedin, #twitter, #vimeo, #youtube {
    height: 84px;
    width: 84px;
    display: block;
    position: absolute;
    margin: 0;
    padding: 0;
   }
   #facebook{
    background-image: url(https://i.ibb.co/g7kb5Tf/social.png);
    background-position: 0px 0px;
    left: 0px;
   }
   #flikr{
    background-image: url(https://i.ibb.co/g7kb5Tf/social.png);
    background-position: -84px 0px;
    left: 64px;
   }
   #linkedin{
    background-image: url(https://i.ibb.co/g7kb5Tf/social.png);
    background-position: -168px 0px;
    left: 128px;
   }
   #twitter{
    background-image: url(https://i.ibb.co/g7kb5Tf/social.png);
    background-position: -250px 0px;
    left: 192px;
   }
   #vimeo{
    background-image: url(https://i.ibb.co/g7kb5Tf/social.png);
    background-position: -334px 0px;
    left: 256px;
   }
   #youtube{
    background-image: url(https://i.ibb.co/g7kb5Tf/social.png);
    background-position: -418px 0px;
    left: 320px;
   }
   .sprites-bar{
    z-index: 1;
    position: absolute;
    clear: both;
    top: 570px;
    left: 50%;
    -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
            transform: translate(-50%, -50%);
    width: 416px;
    height: 100px;
   }
   
   .eye{
    position: relative;
    overflow: hidden;
    margin: auto auto;
    height: 200px;
    width: 200px;
    border-radius: 30px 140px 10px 170px;
    background-color: white;
    -webkit-filter: blur(0.1px);
            filter: blur(0.1px);
    -webkit-transform: rotate(-45deg);
        -ms-transform: rotate(-45deg);
            transform: rotate(-45deg);
    -webkit-box-shadow: 20px -12px 45px -15px #BBB inset, -2px 5px 15px 0px #CCC inset, 55px 40px 45px -25px #EEE inset, -55px -40px 75px -35px #EEE inset, 0px 0px 15px 5px #CBA, 5px 2px 5px 2px #BA9;
            box-shadow: 20px -12px 45px -15px #BBB inset, -2px 5px 15px 0px #CCC inset, 55px 40px 45px -25px #EEE inset, -55px -40px 75px -35px #EEE inset, 0px 0px 15px 5px #CBA, 5px 2px 5px 2px #BA9;
   }
   .eye-red{
    position: absolute;
    height: 240px;
    width: 240px;
    border-radius:120px;
    top: 47%; left: 53%;
    -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
            transform: translate(-50%, -50%);
    -webkit-box-shadow: 0px 0px 45px -15px #B43 inset, 0px 0px 45px -5px #B43;
            box-shadow: 0px 0px 45px -15px #B43 inset, 0px 0px 45px -5px #B43;
    -webkit-filter: blur(2px);
            filter: blur(2px);
   }
   .pupille{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 47%; left: 53%;
    -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
            transform: translate(-50%, -50%);
    background-color: blue;
    -webkit-filter: blur(0.1px);
            filter: blur(0.1px);
    border-radius: 50px;
    -webkit-box-shadow: -2px 1px 3px 1px #BBB, 0px 0px 20px 8px black inset;
            box-shadow: -2px 1px 3px 1px #BBB, 0px 0px 20px 8px black inset;
    /*animation-name: eye-moove;
    animation-duration: 3s;
    animation-timing-function: ease;
    animation-iteration-count: infinite;
    animation-fill-mode: forwards;
   }
   @keyframes eye-moove {
    0% {top: 47%; left: 53%;}
    25% {top: 55%; left: 45%;}
    50% {top: 60%; left: 60%;}
    75% {top: 40%; left: 40%;}
    100% {top: 47%; left: 53%;}*/
   }
   
   .pupille:before{
    content:"";
    height: 60px;
    width: 60px;
    position: absolute;
    top: 47%; left: 53%;
    -webkit-transform: translate(-55%, -50%);
        -ms-transform: translate(-55%, -50%);
            transform: translate(-55%, -50%);
    background-color: #4CF;
    border-radius: 50px;
    -webkit-box-shadow: -2px 0px 12px 12px #48F, -2px 0px 17px 14px #48F inset;
            box-shadow: -2px 0px 12px 12px #48F, -2px 0px 17px 14px #48F inset;
   }
   .pupille:after{
    content:"";
    height: 40px;
    width: 40px;
    position: absolute;
    top: 50%; left: 50%;
    -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
            transform: translate(-50%, -50%);
    background-color: black;
    border-radius: 20px;
    -webkit-box-shadow: 0px 0px 1px 1px black;
            box-shadow: 0px 0px 1px 1px black;
   }
   .eye-reflect{
    content:"";
    height: 40px;
    width: 40px;
    position: absolute;
    top: 50%; left: 70%;
    -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
            transform: translate(-50%, -50%);
    background-color: rgba(255, 255, 255, 0.5);
    border-radius: 20px;
    -webkit-filter: blur(1px);
            filter: blur(1px);
   }
   .eye-reflect:after{
    content:"";
    height: 20px;
    width: 20px;
    position: absolute;
    top: 0%; left: -100%;
    -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
            transform: translate(-50%, -50%);
    background-color: rgba(255, 255, 255, 0.6);
    border-radius: 10px;
   }
   
   .slide-container {
        width: 90%;
        height: auto;
        margin-left: auto;
        margin-right: auto;
        overflow: hidden;
        text-align: center;
   }
   .image-container {
        width: calc(100% * 3);
        height: auto;
        position: relative;
        -webkit-transition: left 2s;
        -o-transition: left 2s;
        transition: left 2s;
   }
   .slider-image{
        float:left;
        width: calc(100% / 3);
        margin: 0;
        padding: 0;
   }
   .button-container {
        top: -20px;
        position: relative;
   }
   .slider-button{
        display: inline-block;
        height: 10px;
        width: 10px;
        border-radius: 5px;
        background-color: white;
   }
   #slider-image-1:target ~ .image-container{
        left: 0px;
   }
   #slider-image-2:target ~ .image-container{
        left: -100%;
   }
   #slider-image-3:target ~ .image-container{
        left: -200%;
   }
   
   .image-container2 {
        width: calc(100% * 5);
        height: auto;
        position: relative;
        -webkit-transition: left 2s;
        -o-transition: left 2s;
        transition: left 2s;
   }
   .slider-image2{
        float:left;
        width: calc(100% / 5);
        margin: 0;
        padding: 0;
   }
   #slider-image-4:target ~ .image-container2{
        left: 0px;
   }
   #slider-image-5:target ~ .image-container2{
        left: -100%;
   }
   #slider-image-6:target ~ .image-container2{
        left: -200%;
   }
   #slider-image-7:target ~ .image-container2{
        left: -300%;
   }
   #slider-image-8:target ~ .image-container2{
        left: -400%;
   }
   #bk2{
    float:left;
   }
  </style>
  
 </head>
 
 <body><!--conteneur html de la page-->
  
  <div class="temperature"></div>
  
  <div class="sprites-bar">
    <a href="https://fr-fr.facebook.com/KruCrafter/" id="facebook" target="_blank"></a>
    <a href="https://www.flickr.com/photos/143637137@N05/" id="flikr" target="_blank"></a>
    <a href="https://www.linkedin.com/in/krum-lek-0b2337a1/" id="linkedin" target="_blank"></a>
    <a href="https://twitter.com/krumlek" id="twitter" target="_blank"></a>
    <a href="https://vimeo.com/user56823130" id="vimeo" target="_blank"></a>
    <a href="https://www.youtube.com/channel/UCxcgjq-ORg_1Jr7lGdcrQng" id="youtube" target="_blank"></a>
  </div>
  
  <div class="sommaire-box">
   <div class="div-menu">
    <section>
     <a class="a-banner" href="#menu-biographie" id="menu-biographie">
      <h1 class="h1-menu">Biographie</h1>
     </a>
     <p class="p-menu"><a class="menu-focus" href="#ancre1">Le code, une passion d'enfance</a><br>
      <a class="menu-focus" href="#ancre2">Modélisation UML?</a><br>
      <a class="menu-focus" href="#ancre3">Autour de JAVA</a><br>
      <a class="menu-focus" href="#ancre4">De joueur à Level Designer</a>
     </p>
    </section>
    <section>
     <a class="a-banner" href="#ancre5">
      <h1 class="h1-menu">Parcours / Diplômes</h1>
     </a>
    </section>
    <section>
     <a class="a-banner" href="#ancre6">
      <h1 class="h1-menu">Expériences</h1>
     </a>
    </section>
    <section>
     <a class="a-banner" href="#menu-interets" id="menu-interets">
      <h1 class="h1-menu">Centres d'intérêt</h1>
     </a>
     <p class="p-menu">
      <a class="menu-focus" href="#ancre7">Musique</a><br>
      <a class="menu-focus" href="#ancre8">Graphisme</a><br>
      <a class="menu-focus" href="#ancre9">Instruments virtuels</a><br>
      <a class="menu-focus" href="#ancre10">Drone</a><br>
      <a class="menu-focus" href="#ancre11">Voyages</a>
     </p>
    </section>
   </div>
  </div>
  
  <div class="id">
   <img class="photo-id">
  </div>
  <div class="rotor">
  </div>
  <div class="name-box">
   <div id="name-screen"><h1 id="name">Jean-Philippe MARY</h1></div>
   <div id="bar"></div>
   <div id="info-screen"><a class="style-text" id="info" href="mailto:?to=krumlek@hotmail.fr"> krumlek@hotmail.fr </a>

</div>
   
  </div>
  
  <div class="screenbox">
   <div class="sub-screen">
    <div class="megapage">
        
     <div class="box-page" id="ancre0"><h1 class="reflet">Bienvenue</h1></div>
     
     <div class="box-page" id="ancre1">
      <h3>Le code, une passion d'enfance</h3>
      <img id="invader" src="https://i.ibb.co/3dq8tYM/32287-5-space-invaders-photos-thumb.png" alt="32287-5-space-invaders-photos-thumb" border="0">
      <p>L'envie de m'adonner au monde de la programmation a débuté très tôt, en 1991, par le biais de calculatrices programmables: j'avais alors 11 ans.<br> 
      Une connaissance plus âgée m'avait fait jouer à un jeu entièrement créé sur une <a class="style-text" href="https://fr.wikipedia.org/wiki/HP-48" target=blank>HP-48</a>.<br>
      À 12 ans, j'ai cassé ma tirelire pour une <a class="style-text" href="https://fr.wikipedia.org/wiki/Texas_Instruments_TI-85" target=blank>TI-85</a> et appris les rudiments 
      du langage <a class="style-text" href="https://fr.wikipedia.org/wiki/TI-Basic" target=blank>TI-Basic</a> pour copier d'après des livres, modifier puis conçevoir mes propres jeux.<br>
      Il m'est arrivé plusieurs fois à cette époque de débuguer des jeux conçus par des lycéens sur leur propre <a class="style-text" href="https://fr.wikipedia.org/wiki/TI-82" target=blank>TI-82</a>,
      malgré quelques fonctionnalités différentes dans le langage utilisé.</p>
     </div>
     
     <div class="box-page" id="ancre2">
      <h3>Modélisation UML?</h3>
      <img id="reaktor" src="https://i.ibb.co/8rM65nP/reaktor.png" alt="reaktor" border="0">
      <p>En 2006 je découvre un logiciel nommé
      <a class="style-text" href="https://www.native-instruments.com/fr/products/komplete/synths/reaktor-6/" target=blank>Reaktor</a>,<br>
      un logiciel permettant de créer des instruments de musique virtuels et bien plus encore.<br>
      Tout se fait en connectant des modules entre eux via des câbles; mis à part ceux liés au son, on peut en trouver d'autres tels, par exemple, des portes logiques, des visualiseurs graphiques. Ceci ressemble en quelque sorte à de la modélisation UML.<br>
      Devant tant de possibilités j'ai imaginé, créé, optimisé et fait tester mes <a class="style-text" href="https://www.native-instruments.com/fr/reaktor-community/reaktor-user-library/all/all/all/818799/all/rating/all/" target=blank>créations</a> sur la librairie des utilisateurs, entre autres un jeu nommé
      <a class="style-text" href="https://www.native-instruments.com/fr/reaktor-community/reaktor-user-library/entry/show/7673/" target=_blank>SpaceShip Racing</a>. 
      Quelques jours plus tard j'ai reçu un mail venant des concepteurs du logiciel, impressionnés par mon travail, et m'informant que mon jeu serait présenté lors de leur prochain salon à Berlin.<br>
      <br>Ci-dessous une de mes créations sur Reaktor, un instrument générant des voix de synthèse:</p>
      <iframe style="padding-bottom:7px" src="https://player.vimeo.com/video/183784285" width="100%" height="100%" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
     </div>
     
     <div class="box-page" id="ancre3">
      <h3>Autour de JAVA</h3>
      <img id="lemur" src="https://i.ibb.co/THQhLr9/lemur.png" alt="lemur" border="0">
      <p>En 2009 je découvre <a class="style-text" href="https://processing.org/" target=blank>Processing</a>, un environnement de développement libre adapté aux arts graphiques.<br>
      Je réussis à adapter et modifier quelques projets sans vraiment comprendre le langage (ingénierie inversée) comme, par exemple, utiliser une reconnaissance faciale pour attribuer des masques à plusieurs visages en temps réel.<br>
      De par mes activités artistiques (M.A.O), j'ai été obligé de créer des interfaces sur tablette tactile pour contrôler mes instruments via le logiciel <a class="style-text" href="https://liine.net/en/products/lemur/" target=blank>Lemur</a>, un puissant outil utilisant un langage proche de Java.
      </p>
     </div>
     
     <div class="box-page" id="ancre4">
      <h3>De joueur à Level Designer</h3>
      <p>Etant passionné par Minecraft sur tablette, un jeu d'assemblage avec des possibilités complexes telles que la création de portes boléennes ou encore l'éxécution de commandes élaborées, je décide de construire un logiciel intégré à un monde permettant de créer et de jouer ses propres musiques en utilisant les sons déjà existants.<br>
      Mon projet, nommé BeatCrafter, fut téléchargé et relayé dans le monde entier en 2017.<br></p>
      <iframe style="padding-bottom:7px" width="100%" height="100%" src="https://www.youtube.com/embed/b5catMDi1AQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      Une entreprise (tourangelle!) nommée Millenium Studio m'a ensuite contacté pour que je j'intègre leur équipe au poste de level designer.<br></p>
      J'ai conçu et réalisé, grâce à plusieurs logiciels nécessitant souvent des commandes, des mondes pour des mini-jeux sur serveur privé, en architecture mais aussi en apparence. J'ai également créé des packs de ressources visuelles (via Photoshop) et sonores.<br>
      Voici une vue d'ensemble de mes créations:</p>
      <iframe style="padding-bottom:7px" width="100%" height="100%" src="https://www.youtube.com/embed/ZeGVrzsnuN0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <p>Ci-dessous un stream d'une de nos maps dont j'ai conçu le terraforming et l'implantation de la végétation via WorldPainter, les structures, les bâtiments avec WorldEdit, les textures avec Photoshop et les items avec Aseprite.</p>
      <iframe style="padding-bottom:7px" width="100%" height="100%" src="https://www.youtube.com/embed/mgp0NRnw_Yo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <p>J'ai aussi pu concevoir des niveaux pour un RPG en cours de développement et y intégrer des éléments sur Unity.</p>
      <iframe style="padding-bottom:7px" width="100%" height="100%" src="https://www.youtube.com/embed/lPSwx2E0BV0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 
     </div>
     
     <div class="box-page" id="ancre5">
      <table>
       <tr>
        <th colspan="2">Parcours / Diplômes</th>
       </tr>
       
       
       <tr>
        <td rowspan="2" class="parcours-left">1994</td>
        <td class="head-td">Brevet des collèges</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table"></td>
       </tr>
       
       <tr>
        <td rowspan="2" class="parcours-left">1996</td>
        <td class="head-td">CAP BEP ébènisterie</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
       </tr>
       
       <tr>
        <td rowspan="2" class="parcours-left">1996</td>
        <td class="head-td">Brevet de secourisme</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
       </tr>
       
       <tr>
        <td rowspan="2" class="parcours-left">1996</td>
        <td class="head-td">BAFA</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
       </tr>
       
       <tr>
        <td rowspan="2" class="parcours-left">1997</td>
        <td class="head-td">Spécialisation en restauration de meubles anciens</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
       </tr>
       
       <tr>
        <td rowspan="2" class="parcours-left">1997</td>
        <td class="head-td">Brevet de surveillant de baignade</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
       </tr>
       
       <tr>
        <td rowspan="2" class="parcours-left">2012</td>
        <td class="head-td">Permis B</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
       </tr>
       
       <tr>
        <td rowspan="2" class="parcours-left">2014</td>
        <td class="head-td">Formation aux techniques de mastering</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table"><em>Autodidacte</em>
       </tr>
       
      </table>
     </div><!--fin ancre5-->
     
     <div class="box-page" id="ancre6">
      <table>
       <tr>
        <th colspan="2">Expériences professionnelles</th>
       </tr>
       
       
       <tr>
        <td rowspan="3" class="parcours-left">1997<br>2003</td>
        <td class="head-td">Structures diverses</td>
       </tr>
       <tr>
        <td class="mid-td">Animateur, surveillant de baignade</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">Enfance & Public handicapé / Colonies et centres aérés</td>
       </tr>
       
       <tr>
        <td rowspan="3" class="parcours-left">1999<br>Aujourd'hui</td>
        <td class="head-td">Krumlek / Krum Fresh</td>
       </tr>
       <tr>
        <td class="mid-td">BeatMaker, DJ, musicien et chanteur</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        Lien <a class="table-link" href="http://www.propulson.com/propulson-le-dispositif/propulson-1-selection-2004/krumlek/" target=blank>Propul'son</a></td>
       </tr>
       
       
       <tr>
        <td rowspan="3" class="parcours-left">2006<br>2007</td>
        <td class="head-td">Sogea</td>
       </tr>
       <tr>
        <td class="mid-td">Constructeur en béton armé</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table"></td>
       </tr>
       
       <tr>
        <td rowspan="3" class="parcours-left">2009<br>2010</td>
        <td class="head-td">Del'Arte / La Scala / Irish Compagny</td>
       </tr>
       <tr>
        <td class="mid-td">Cuisinier</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table"></td>
       </tr>
       
       <tr>
        <td rowspan="3" class="parcours-left">2009<br>2011</td>
        <td class="head-td">Glumpk record</td>
       </tr>
       <tr>
        <td class="mid-td">Producteur et distributeur phonographique</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        Lien <a class="table-link" href="http://www.toolboxrecords.com/fr/search/Glumpk" target=blank>site de vente</a></td>
       </tr>
       
       <tr>
        <td rowspan="3" class="parcours-left">09/2010<br>09/2012</td>
        <td class="head-td">Sam Tach'</td>
       </tr>
       <tr>
        <td class="mid-td">BeatMaker, arrangeur et back vocal</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        <em>Coup de Coeur de Terres du Son 2012. </em>Lien <a class="table-link" href="https://samtach1.bandcamp.com/releases" target=blank>Bandcamp</a></td>
       </tr>
      
       <tr>
        <td rowspan="3" class="parcours-left">19/2011<br>Aujourd'hui</td>
        <td class="head-td">Buddy Buddah</td>
       </tr>
       <tr>
        <td class="mid-td">BeatMaker, bassiste, claviériste et chanteur</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        Lien <a class="table-link" href="https://distrokid.com/hyperfollow/buddybuddah/coconut-paradise" target=blank>Multi-plateformes</a></td>
       </tr>
      
       <tr>
        <td rowspan="5" class="parcours-left">2012<br>2015</td>
        <td class="head-td">Brutal Kawaii</td>
       </tr>
       <tr>
        <td class="mid-td">Animateur Radio et réalisateur</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        Emission dédiée la pop culture japonaise diffusée sur Radio Béton</td>
       </tr>
       <tr>
        <td class="mid-td">Réalisateur Vidéo, graphiste et voix off</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        (Photoshop, Premiere, After Effect) Chroniques diffusées sur TV Tours<br>
        Lien <a class="table-link" href="https://www.youtube.com/watch?v=KpvQksof8bA&t=10s" target=blank>Youtube</a></td>
       </tr>
       
       <tr>
        <td rowspan="5" class="parcours-left">10/2013<br>11/2013</td>
        <td class="head-td">Le petit monde / pacha uchuk festival (équateur)</td>
       </tr>
       <tr>
        <td class="mid-td">Animateur Hip-Hop dans la prison de Quito</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        Création de morceaux, prises de voix et production sur CD</td>
       </tr>
       <tr>
        <td class="mid-td">Musicien</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        Concerts à Quito, Guayaquil & Cuenca / Préparation du festival<br>
        Lien <a class="table-link" href="http://www.le-petit-monde.com/projets-phares/le-pacha-uchuk-festival-equateur/" target=blank>descriptif</a></td>
       </tr>
       
       <tr>
        <td rowspan="5" class="parcours-left">12/2013<br>Aujourd'hui</td>
        <td class="head-td">Roller79</td>
       </tr>
       <tr>
        <td class="mid-td">BeatMaker, claviériste et chanteur</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        <em>Coup de Coeur de Terres du Son 2015. </em>Lien <a class="table-link" href="https://www.facebook.com/roller79/" target=blank>Facebook</a> et
        <a class="table-link" href="https://soundcloud.com/roller79" target=blank>Soundcloud</a></td>
       </tr>
       <tr>
        <td class="mid-td">Réalisateur de Clips</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        (After Effect, Premiere, Photoshop) / Lien <a class="table-link" href="https://www.youtube.com/watch?v=LSQ3BaG7dqM" target=blank>Youtube</a></td>
       </tr>
      
       <tr>
        <td rowspan="3" class="parcours-left">08/2012<br>08/2016</td>
        <td class="head-td">Martine On The Beach</td>
       </tr>
       <tr>
        <td class="mid-td">BeatMaker, arrangeur et back vocal</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        <em>Coup de Coeur de Terres du Son 2013. </em>Lien <a class="table-link" href="https://www.facebook.com/roller79/" target=blank>Facebook</a> et
        <a class="table-link" href="https://soundcloud.com/roller79" target=blank>Soundcloud</a></td>
       </tr>
       
       <tr>
        <td rowspan="3" class="parcours-left">08/2017<br>08/2018</td>
        <td class="head-td">Millenium Studio</td>
       </tr>
       <tr>
        <td class="mid-td">Level designer, graphiste et sound designer</td>
       </tr>
       <tr>
        <td class="sub-td"><p class="p-table">
        Lien <a class="table-link" href="https://www.flickr.com/gp/143637137@N05/aC3r04" target=blank>Flickr</a></td>
       </tr>
      </table>
     </div><!--fin ancre6-->
     
     <div class="box-page" id="ancre7">
      <h3>Musique</h3>
      <p>La musique est une grande passion, en particulier la musique électronique car elle met en évidence mes compétences en matière de programmation (création d'instruments de sons ou de plateformes de contrôle). Ce fût pendant presque 20ans mon revenu principal.<br>
      Voici quelques uns de mes projets musicaux</p>
      <h4>Roller79</h4>
      <iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/123863365&color=%2308090a&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
      <iframe width="100%" height="300" src="https://www.youtube.com/embed/LSQ3BaG7dqM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      
      <h4>Buddy Buddah</h4>
      <iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/38546267&color=%236d5834&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe>
      <iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/304139679&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
      
      <h4>Martine On The Beach</h4>
      <iframe width="100%" height="300" src="https://www.youtube.com/embed/uHGiMOB5rUw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <iframe width="100%" height="300" src="https://www.youtube.com/embed/NCW1T7if7x4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      
      <h4>Krum Fresh</h4>
      <iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/330749383&color=%236d5834&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
      <iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/199200551&color=%236d5834&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
     </div>
     
     <div class="box-page" id="ancre8">
      <h3>Graphisme</h3>
      <h4>CSS Eye</h4>
      <p>L'apprentissage du CSS m'amuse depuis très peu de temps, j'ai donc créé un oeil (mon premier graphique CSS) pour cette page<br>
      J'aimerai par la suite maitriser les formes vectorielles en SVG.</p>
      <div class="eye">
       <div class="eye-red"></div>
       <div class="pupille"></div>
       <div class="eye-reflect"></div>
      </div>
      <h4>3DSmax 2010</h4>
      <p>En 2011 je découvre 3DSmax et m'exerce un peu dessus...</p>
      <div class="slide-container">
        <span id="slider-image-1"></span>
        <span id="slider-image-2"></span>
        <span id="slider-image-3"></span>
        <div class="image-container">
            <img src="https://i.ibb.co/fCvLRqT/45055837265-25513e04a0-z.jpg" class="slider-image">
            <img src="https://i.ibb.co/hLg79Pm/45055840405-6ceb26092f-z.jpg" class="slider-image">
            <img src="https://i.ibb.co/w74bzqk/45243589684-b1d57d222e-z.jpg" class="slider-image">
        </div>
        <div class="button-container">
            <a href="#slider-image-1" class="slider-button"></a>
            <a href="#slider-image-2" class="slider-button"></a>
            <a href="#slider-image-3" class="slider-button"></a>
        </div>
      </div>
      <h4>Photoshop</h4>
      <p>Mes connaissances en Photoshop m'ont permises de réaliser pas mal de choses, même au poste de Level Designer.<br>
      Ci-dessous, quelques affiches:</p>
      <img width="100%" src="https://i.ibb.co/Qkz8rM5/BRUTAL2.jpg" alt="BRUTAL1">
      <img width="50%" id="bk2" src="https://i.ibb.co/vDHy1F9/BRUTAL2-FB.jpg" alt="BRUTAL2">
      <img width="50%" src="https://i.ibb.co/6R2Cxfv/che-boon-chaaa.jpg" alt="BRUTAL2">
     </div><!--fin ancre8-->
     
     <div class="box-page" id="ancre9">
      <h3>Instruments virtuels</h3>
      <p>Mon approche dans le domaine de la création est souvent scientifique<br>
      Ci dessous, une représentation de notre systeme solaire, réalisé uniquement avec des oscillateurs hautes et basses fréquences.</p>
      <iframe style="padding-bottom:7px" width="100%" height="300" src="https://www.youtube.com/embed/BGKHMLF_aDg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
     </div>
     
     <div class="box-page" id="ancre10">
      <h3>Drone</h3>
      <p>Depuis un an je me passionne pour les drones. J'adore monter, souder, programmer puis tester mes machines.</p>
      <div class="slide-container">
        <span id="slider-image-4"></span>
        <span id="slider-image-5"></span>
        <span id="slider-image-6"></span>
        <span id="slider-image-7"></span>
        <span id="slider-image-8"></span>
        <div class="image-container2">
            <img src="https://i.ibb.co/ZzsJQs9/Drone01.jpg" class="slider-image2">
            <img src="https://i.ibb.co/Rzx5M2X/Drone02.jpg" class="slider-image2">
            <img src="https://i.ibb.co/QbGhwNC/Drone03.jpg" class="slider-image2">
            <img src="https://i.ibb.co/fFCmNhC/Drone04.jpg" class="slider-image2">
            <img src="https://i.ibb.co/2gsVr80/Drone05.jpg" class="slider-image2">
        </div>
        <div class="button-container">
            <a href="#slider-image-4" class="slider-button"></a>
            <a href="#slider-image-5" class="slider-button"></a>
            <a href="#slider-image-6" class="slider-button"></a>
            <a href="#slider-image-7" class="slider-button"></a>
            <a href="#slider-image-8" class="slider-button"></a>
        </div>
      </div>
      <iframe width="100%" height="300" src="https://www.facebook.com/plugins/video.php?href=https%3A%2F%2Fwww.facebook.com%2Fkrum.lek%2Fvideos%2F10214490841497776%2F&show_text=0&width=560" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true" allowFullScreen="true"></iframe>
      <iframe style="padding-bottom:7px" width="100%" height="300" src="https://www.youtube.com/embed/P-Q3Gt8jOh8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
     </div>
     
     <div class="box-page" id="ancre11">
      <h3>Voyages</h3>
      <ul>
       <li>Allemagne <em>(Berlin, Dusseldorf, Munich)</em></li>
       <li>Autriche <em>(Tyrol, Vienne)</em></li>
       <li>Belgique <em>(Bruges, Bruxelles, Liège)</em></li>
       <li>Espagne <em>(Barcelone, Grenade, Madrid)</em></li>
       <li>Equateur <em>(Cuenca, Guayaquil, Quito)</em></li>
       <li>Grèce <em>(Athènes, Delphes, Olympie)</em></li>
       <li>Italie <em>(Florence, Malte, Rome, Venise)</em></li>
       <li>Maroc <em>(Casablanca, Meknes)</em></li>
       <li>Pays Bas <em>(Amsterdam, Maastricht)</em></li>
       <li>Portugal <em>(Lisbonne)</em></li>
       <li>Royaumes-Unis <em>(Birmingham, Londres)</em></li>
       <li>République tchèque <em>(Prague)</em></li>
       <li>Russie <em>(Moscou, St Pétersbourg)</em></li>
       <li>Turquie <em>(Istanbul)</em></li>
      </ul>
     </div>
    </div><!--fin megapage-->
   </div><!--fin sub-screen-->
  </div><!--fin screenbox-->
  
 </body>
</html>
