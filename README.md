:root { /_ -------------fonts------------- _/ --main-font: 'Roboto', sans-serif;
--secondary-fonts: 'Raleway';

/_ -------------text colors------------- _/ --main-text-color: #212121;
--other-text-color: #757575; --accent-text-color: #2196f3; --footer-text-color:
rgba(255, 255, 255, 0.6);

/_ -------------bg colors------------- _/ --main-background-color: #ffffff;
--hero-and-footer-bg-color: #2f303a; --team-background-color: #f5f4fa;

/_ -------------others------------- _/ --adress-color: #ffffff99; --credo-color:
#e5e5e5; --hover-color: #188ce8; --social-link: #afb1b8; } .body { font-family:
var(--main-font); letter-spacing: 0.03em; /_ background-color:
var(--team-background-color); _/ background-color: var(--main-background-color);
color: var(--main-text-color); font-size: 14px; --trancition-timing: 250ms
cubic-bezier(0.4, 0, 0.2, 1); }

.visually-hidden { position: absolute; width: 1px; height: 1px; margin: -1px;
border: 0; padding: 0; white-space: nowrap; clip-path: inset(100%); clip: rect(0
0 0 0); overflow: hidden; }

/_ ----------reset styles----------- _/ .link { text-decoration: none; color:
inherit; } .list { list-style: none; }

h1, h2, h3, h4, h5, h6, p, ul { margin: 0; padding: 0; }

/_ ------------- Base styles ------------- _/ .container { width: 1200px;
margin-left: auto; margin-right: auto; padding-left: 15px; padding-right: 15px;
} img { display: block; max-width: 100%; height: auto; } /_outline: 2px solid
red;_/

/_ --------------------------- Header SECT --------------------------- _/
.header { border-bottom: 1px solid #ececec; } .header-nav**flex { display: flex;
align-items: center; } .header-nav { display: flex; align-items: center; }
.header-nav**list { display: flex; margin-left: 93px; }
.header-nav**item:not(:last-child) { margin-right: 50px; } .header-nav**link {
font-weight: 500; font-size: 14px; line-height: 1.14; letter-spacing: 0.02em;
color: var(--main-text-color); padding-top: 32px; padding-bottom: 32px; display:
block;

position: relative;

transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1); } .header-contact**list {
display: flex; margin-left: auto; } .header-contact**item +
.header-contact**item { margin-left: 50px; } .header-contact**link {
font-weight: 500; font-size: 14px; line-height: 16px; letter-spacing: 0.02em;
color: var(--other-text-color); padding-top: 32px; padding-bottom: 32px;
display: flex; align-items: center;

transition: color var(--trancition-timing); } .header-contact**icon {
margin-right: 10px; fill: currentColor; } .header-nav**link:hover,
.header-nav**link:focus, .header-contact**link:hover,
.header-contact**link:focus { color: var(--accent-text-color); }
.header-nav**link.current { color: var(--accent-text-color); }
.header-nav\_\_link.current::after { position: absolute;

display: block; content: ''; width: 100%; height: 4px; border-radius: 2px;
bottom: -1px;

background-color: var(--accent-text-color); } .header-logo { font-family:
var(--secondary-fonts); font-weight: 700; font-size: 26px; letter-spacing:
0.03em; line-height: 1.19; color: var(--accent-text-color); text-shadow: 0px 4px
4px rgba(0, 0, 0, 0.25); } .header-logo\_\_accent { font-family:
var(--secondary-fonts); color: var(--main-text-color); text-shadow: 0px 4px 4px
rgba(0, 0, 0, 0.25); }

/_ ----------------------------- Main SECT ----------------------------- _/ /_
.body { background-color: var(--main-background-color); } _/

/_ ----- hero ----- _/ .hero { background-color:
var(--hero-and-footer-bg-color); padding-top: 200px; padding-bottom: 200px;
text-align: center; max-width: 1600px; min-height: 600px; margin-left: auto;
margin-right: auto; background-repeat: no-repeat; background-position: center;
background-size: cover; background-image: linear-gradient( to right, rgba(47,
48, 58, 0.4), rgba(47, 48, 58, 0.4) ), url(../images/hero.jpg); } .hero**title {
margin-bottom: 30px; margin-left: auto; margin-right: auto; max-width: 696px;
font-family: var(--main-font); font-weight: 900; font-size: 44px; line-height:
1.36; text-align: center; letter-spacing: 0.06em; text-transform: uppercase;
color: var(--main-background-color); } .hero**btn { display: inline-block;
min-width: 200px; border-radius: 4px; border: none; padding: 10px 32px;
font-family: var(--main-font); font-weight: 700; font-size: 16px; line-height:
1.88; align-items: center; text-align: center; letter-spacing: 0.06em; cursor:
pointer; color: var(--main-background-color); background-color:
var(--accent-text-color); transition: background-color var(--trancition-timing),
color var(--trancition-timing); } .hero**btn:hover, .hero**btn:focus {
background-color: var(--hover-color); }

/_ ------------------ portfolio ------------------- _/ .portfolio { padding-top:
94px; padding-bottom: 94px; } .portfolio-btns { display: flex; justify-content:
center; margin-bottom: 50px; } .portfolio-btns\_\_item:not(:last-child) {
margin-right: 8px; } .btns { display: inline-block; border-radius: 4px; border:
none; padding: 6px 22px;

font-family: var(--main-font); font-weight: 500; font-size: 16px; line-height:
calc(26 / 16); text-align: center; letter-spacing: 0.03em; color:
var(--main-text-color); background-color: var(--team-background-color); cursor:
pointer;

border-radius: 4px;

transition: background-color var(--trancition-timing), color
var(--trancition-timing), box-shadow var(--trancition-timing); } .btns:hover,
.btns:focus { background-color: var(--accent-text-color); color:
var(--main-background-color); box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.1), 0px
1px 2px rgba(0, 0, 0, 0.08), 0px 2px 2px rgba(0, 0, 0, 0.12); }

/_ ------ project ------- _/ .project-list { display: flex; flex-wrap: wrap;
margin: -15px; } .project-list**item { margin: 15px; transition: transform
var(--trancition-timing); } .project-list**link { display: block; }
.project-list**link:hover .project-list**overlay, .project-list**link:focus
.project-list**overlay { transform: translateY(0); } .project-list**link:hover,
.project-list**link:focus { box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.12), 0px 4px
4px rgba(0, 0, 0, 0.06), 1px 4px 6px rgba(0, 0, 0, 0.16); }
.project-list**description { position: relative; overflow: hidden; }
.project-list**overlay { position: absolute; display: inline-block; content: '';
width: 100%; height: 100%; top: 0; left: 0; background-color: rgba(33, 150, 243,
0.9); transform: translateY(100%); transition: transform
var(--trancition-timing); } .project-list**description-text { position:
absolute; top: 0; left: 0; padding: 63px 24px; font-size: 18px; line-height:
1.56; color: var(--main-background-color); } .project-list**border { border: 1px
solid #eeeeee; border-top: none; padding: 20px 24px; } .project-list**title {
font-weight: 700; font-size: 18px; line-height: 2; letter-spacing: 0.06em; }
.project-list**name { font-size: 16px; line-height: 1.87; color:
var(--other-text-color);

margin-top: 4px; }

/_ ------------- credo ------------- _/ .credo { padding-top: 94px;
padding-bottom: 94px; } .credo-list { display: flex; }
.credo-item:not(:last-child) { margin-right: 30px; max-width: 270px; }
.credo**icon-fon { display: flex; width: 270px; height: 120px; align-items:
center; justify-content: center; margin-bottom: 30px; background-color:
var(--team-background-color); } .credo-icon { align-items: center; }
.credo**title { font-size: 14px; font-family: var(--main-font); font-weight:
700; line-height: 1.14;

margin-bottom: 10px;

letter-spacing: 0.03em; text-transform: uppercase;

color: var(--main-text-color); } .credo\_\_text { font-family: var(--main-font);
line-height: 1.71; letter-spacing: 0.03em;

color: var(--other-text-color); }

/_ ------------- direction ------------- _/ .direction { padding-bottom: 94px; }
.direction\_\_title { font-family: var(--main-font); font-weight: 700;
font-size: 36px; line-height: 1.16; text-align: center; letter-spacing: 0.03em;

color: var(--main-text-color);

margin-bottom: 50px; } .direction-list { display: flex; }
.direction-list**item:not(:last-child) { margin-right: 30px; }
.direction-list**item { position: relative; }

.direction-list\_\_text { width: 100%; height: 70px; position: absolute; bottom:
0; left: 0; display: flex; align-items: center; justify-content: center;

/_ padding: 27px 0px; _/

font-weight: 700; line-height: 1.14; /_ text-align: center; _/ text-transform:
uppercase;

color: var(--main-background-color); background-color: rgba(47, 48, 58, 0.8); }

/_ ----------- team section ------------_/ .team { background:
var(--team-background-color); padding-top: 94px; padding-bottom: 94px; }
.team**title { font-family: var(--main-font); font-weight: 700; font-size: 36px;
line-height: 1.16; text-align: center; letter-spacing: 0.03em; color:
var(--main-text-color); margin-bottom: 50px; } .team-list { display: flex; }
.team-list**item { background: var(--main-background-color); box-shadow: 0px 1px
3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 2px 1px rgba(0, 0,
0, 0.2); border-radius: 0px 0px 4px 4px; } .team-list**item:not(:last-child) {
margin-right: 30px; } .team-list**workers { padding: 30px 0px; }
.team-list**name { font-family: var(--main-font); font-weight: 500; font-size:
16px; line-height: 1.18; text-align: center; letter-spacing: 0.03em; color:
var(--main-text-color); } .team-list**profession { margin-top: 10px;
font-family: var(--main-font); font-size: 16px; line-height: 1.18; text-align:
center; letter-spacing: 0.03em; color: var(--other-text-color); }
.team-list**social-list { display: flex; justify-content: center; gap: 10px;
margin-top: 16px; } .team-list**social-link { width: 44px; height: 44px;
display: flex; border-radius: 50%; color: var(--social-link); background-color:
var(--main-background-color); justify-content: center; align-items: center;
transition: background-color var(--trancition-timing), color
var(--trancition-timing); } .team-list**social-link:hover,
.team-list**social-link:focus { color: var(--main-background-color);
background-color: var(--accent-text-color); } .team-list\_\_social-icon { fill:
currentColor; }

/_ --------------- Clients ---------------- _/ .client { padding-top: 94px;
padding-bottom: 94px; } .client**title { margin-bottom: 50px; font-weight: 700;
font-size: 36px; line-height: 1.17; text-align: center; } .client**list {
display: flex; } .client**item:not(:last-child) { margin-right: 30px; }
.client**link { width: 170px; height: 90px; display: flex; border: 1px solid
var(--social-link); border-radius: 4px; color: var(--social-link);
background-color: var(--main-background-color); justify-content: center;
align-items: center; transition: border-color var(--trancition-timing), color
var(--trancition-timing); } .client**link:hover, .client**link:focus { color:
var(--accent-text-color); border-color: var(--accent-text-color); }
.client\_\_icon { fill: currentColor; } /_ --------------------------- Footer
section ------------------------ _/

.footer { padding-top: 60px; padding-bottom: 60px; background:
var(--hero-and-footer-bg-color); } .footer-logo { font-family:
var(--secondary-fonts); font-weight: 700; font-size: 26px; line-height: 1.19;
letter-spacing: 0.03em; text-transform: capitalize; color:
var(--accent-text-color); } .footer-logo**accent { color:
var(--main-background-color); font-family: var(--secondary-fonts);
text-transform: capitalize; } .footer-adress { margin-top: 20px; }
.footer-adress**location-item { margin-top: 9px; font-family: var(--main-font);
font-style: normal; font-size: 14px; line-height: 1.7; letter-spacing: 0.03em;
color: var(--main-background-color); }
.footer-adress**location_item:not(:last-child) { margin-bottom: 9px; }
.footer-adress**mail-tel-item { margin-top: 9px; font-family: var(--main-font);
font-style: normal; font-size: 14px; line-height: 1.7; letter-spacing: 0.03em;
color: var(--adress-color); } .footer-adress**location-link:hover,
.footer-adress**location-link:focus { color: var(--hover-color); }
.footer-adress**location-link { font-style: normal; font-size: 14px;
line-height: 1.71; transition: color var(--trancition-timing); }
.footer-adress**mail-tel-item:hover, .footer-adress**mail-tel-item:focus {
color: var(--hover-color); } .footer-adress**mail-tel-link { transition: color
var(--trancition-timing); } .footer .container { display: flex; align-items:
baseline; } .footer-social**text { margin-bottom: 20px; font-weight: 700;
font-size: 14px; line-height: 1.14; text-transform: uppercase; color:
var(--main-background-color); } .footer-social { margin-left: 70px; width:
206px; } .footer-social**list { display: flex; gap: 10px; } .footer-social**item
{ width: 44px; height: 44px; } .footer-social**link { width: 44px; height: 44px;
display: flex; border-radius: 50%; color: var(--main-background-color);
background-color: #ffffff10; align-items: center; justify-content: center;
transition: background-color var(--trancition-timing); }
.footer-social**link:hover, .footer-social**link:focus { background-color:
var(--hover-color); } .footer-social\_\_icon { fill: currentColor; }

/_ --------- footer input-------- _/

.footer-input { margin-left: auto; } .footer-input**title { font-weight: 700;
font-size: 14px; line-height: 1.14; letter-spacing: 0.03em; text-transform:
uppercase; color: var(--main-background-color); } .footer-input**form { display:
flex; align-items: center; margin-top: 20px; } .footer-input**email { width:
358px; height: 50px; font-style: normal; font-weight: 400; font-size: 16px;
line-height: 1.25; letter-spacing: 0.03em; display: flex; align-items: center;
color: var(--main-background-color); padding: 16px 15px; border: 1px solid
rgba(255, 255, 255, 0.3); border-radius: 4px; background-color: transparent; }
.footer-input**email::placeholder { color: rgba(255, 255, 255, 0.6); }
.footer-input**button { display: flex; justify-content: center; align-items:
center; width: 200px; height: 50px; margin-left: 12px; padding: 0px;
font-weight: 700; font-size: 16px; line-height: 1.88; letter-spacing: 0.06em;
color: var(--main-background-color); background-color: var(--accent-text-color);
border: none; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15); border-radius: 4px;
cursor: pointer; transition: background-color 250ms cubic-bezier(0.4, 0, 0.2,
1); } .footer-input**button:hover, .footer-input**button:focus {
background-color: var(--hover-color); } .footer-input**icon-send { margin-left:
10px; fill: var(--main-background-color); }

/_ --------- Modal window -------- _/

.backdrop { position: fixed; display: flex; align-items: center;
justify-content: center; width: 100vw; height: 100vh; background-color: rgba(0,
0, 0, 0.2); top: 0; transition: opacity var(--trancition-timing), visibility
var(--trancition-timing); } .backdrop.is-hidden { opacity: 0; visibility:
hidden; pointer-events: none; } .backdrop.is-hidden .modal { transform:
scale(2); } .modal { width: 528px; height: 581px; background-color:
var(--main-background-color); box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px
1px 1px rgba(0, 0, 0, 0.14), 0px 2px 1px rgba(0, 0, 0, 0.2); border-radius: 4px;
position: relative; transform: scale(1); transition: transform
var(--trancition-timing); } .form { padding: 40px; } .form-title { font-weight:
700; font-size: 20px; line-height: 1.15; text-align: center; margin-bottom:
10px; } .form**field { position: relative; display: flex; flex-direction:
column; margin-bottom: 10px; } .form**label, .form**comment-label { font-size:
12px; line-height: 1.17; letter-spacing: 0.01em; color: var(--other-text-color);
margin-bottom: 4px; } .form**input { width: 100%; margin: 0; padding: 11px 42px;
border: 1px solid rgba(33, 33, 33, 0.2); border-radius: 4px;

transition: border-color var(--trancition-timing); } .form**input:hover,
.form**input:focus { outline: none; border-color: var(--accent-text-color); }
.form**input-icon { position: absolute; top: 50%; left: 15px; transform:
translateY(20%); display: inline-block; width: 18px; height: 13px; transition:
fill var(--trancition-timing); } .form**input:hover ~ .form**input-icon,
.form**input:focus ~ .form**input-icon { fill: var(--accent-text-color); }
textarea { resize: none; border: 1px solid rgba(33, 33, 33, 0.2); border-radius:
4px; padding: 12px 16px; font-size: 12px; line-height: 1.17; letter-spacing:
0.01em; height: 120px; transition: border-color var(--trancition-timing); }
textarea:hover, textarea:focus { outline: none; border-color:
var(--accent-text-color); } .comment::placeholder { font-size: 12px;
line-height: 1.17; letter-spacing: 0.01em; color: rgba(117, 117, 117, 0.5); }
.modal-chek { display: inline-block; width: 16px; height: 15px; border: 2px
solid #212121; border-radius: 2px; margin-right: 7px; } .form**field-comment {
position: relative; display: flex; flex-direction: column; } .form**field-chek {
padding-left: 14px; margin-top: 20px; margin-bottom: 30px; } .form**checkbox {
position: absolute; width: 1px; height: 1px; margin: -1px; padding: 0; overflow:
hidden; border: 0; clip: rect(0 0 0 0); } .form**checkbox:checked + .modal-chek
{ background-image: url(../images/modal-check.svg); background-position: center;
background-repeat: no-repeat; background-color: var(--accent-text-color);
background-origin: border-box; border-color: var(--accent-text-color); }
.form**checkbox:focus + .modal-chek, .form**checkbox:hover + .modal-chek {
box-shadow: 0 0 0 0.1em var(--hover-color); } .form**submit-btn { display: flex;
align-items: center; justify-content: center; margin: 0 auto; padding: 10px
56px; border: none; border-radius: 4px; text-align: center; text-decoration:
none; font-family: 'Roboto'; font-style: normal; font-weight: 700; font-size:
16px; line-height: 1.87; letter-spacing: 0.06em; cursor: pointer;
background-color: var(--accent-text-color); box-shadow: 0px 4px 4px rgba(0, 0,
0, 0.15); color: var(--main-background-color); transition: background-color
var(--trancition-timing); } .form**submit-btn:hover, .form**submit-btn:focus {
background-color: var(--hover-color); } .form**close-btn-icon { fill: #000;
transition: fill var(--trancition-timing); } .form**close-btn { position:
absolute; display: flex; align-items: center; justify-content: center; right:
8px; top: 8px; background-color: transparent; border-radius: 50%; width: 30px;
height: 30px; border: 1px solid rgba(0, 0, 0, 0.1); cursor: pointer; }
.form**close-btn:focus .form**close-btn-icon, .form**close-btn:hover
.form**close-btn-icon { fill: var(--accent-text-color); } .policy-label {
display: flex; align-items: center; font-size: 14px; line-height: 1.71; color:
var(--other-text-color); } .policy-link { margin-left: 4px; color: rgba(33, 150,
243, 1); } .policy-link:hover, .policy-link:focus { color: var(--hover-color); }
