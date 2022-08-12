.footer { text-align: center; padding: 60px 0px; background:
var(--hero-and-footer-bg-color); }

.footer\_\_flex { display: block; margin: 0; padding: 0px; list-style: none;

@media (min-width: 768px) { display: flex; justify-content: center; flex-wrap:
wrap; gap: 30px 165px; }

@media (min-width: 1200px) { display: flex; justify-content: center; text-align:
left; gap: 70px; } }

.footer-adress { margin-top: 20px; }

.footer-adress\_\_location-item { margin-top: 9px; font-family:
var(--main-font); font-style: normal; font-size: 14px; line-height: 1.7;
letter-spacing: 0.03em; color: var(--main-background-color); }

.footer-adress\_\_mail-tel-item { margin-top: 9px; font-family:
var(--main-font); font-style: normal; font-size: 14px; line-height: 1.7;
letter-spacing: 0.03em; color: var(--adress-color);

}

.footer-adress\_\_location-link { font-style: normal; font-size: 14px;
line-height: 1.71; transition: color var(--trancition-timing);

&:hover, &:focus { color: var(--hover-color); } }

.footer-adress\_\_mail-tel-link {

&:hover, &:focus { color: var(--hover-color); }

transition: color var(--trancition-timing); }

.footer .container { display: flex; align-items: baseline; }

.footer-social { display: block;

margin-top: 60px; text-align: center;

@media (min-width: 768px) { margin-top: 0px; } }

.footer-social\_\_text { margin-top: 60px;

font-weight: 700; font-size: 14px; line-height: 1.14; text-transform: uppercase;
color: var(--main-background-color);

@media (min-width: 768px) { padding-bottom: 10px; }

@media (min-width: 1200px) { text-align: left; } }

.footer-social\_\_list { display: flex; gap: 10px; margin-top: 20px; //
margin-bottom: 60px; justify-content: center; padding: 0; }

.footer-social\_\_item { width: 44px; height: 44px; }

.footer-social\_\_link { width: 44px; height: 44px; display: flex;
border-radius: 50%; color: var(--main-background-color); background-color:
#ffffff10; align-items: center; justify-content: center; transition:
background-color var(--trancition-timing);

&:hover, &:focus { background-color: var(--hover-color); } }

.footer-social\_\_icon { fill: currentColor; }

/_ --------- footer input-------- _/

.footer-input { margin-top: 60px;

@media (min-width: 768px) { margin-top: 0px; padding: 0; }

margin-left: auto; }

.footer-input\_\_title { font-weight: 700; font-size: 14px; line-height: 1.14;
letter-spacing: 0.03em; text-transform: uppercase; color:
var(--main-background-color); }

.footer-input\_\_form { display: flex; align-items: center; margin-top: 20px; }

.footer-input\_\_email { width: 358px; height: 50px; font-style: normal;
font-weight: 400; font-size: 16px; line-height: 1.25; letter-spacing: 0.03em;
display: flex; align-items: center; color: var(--main-background-color);
padding: 16px 15px; border: 1px solid rgba(255, 255, 255, 0.3); border-radius:
4px; background-color: transparent;

&::placeholder { color: rgba(255, 255, 255, 0.6); } }

.footer-input\_\_button { display: inline-flex; justify-content: center;
align-items: center; width: 200px; height: 50px; margin-left: 12px; padding:
0px; font-weight: 700; font-size: 16px; line-height: 1.88; letter-spacing:
0.06em; color: var(--main-background-color); background-color:
var(--accent-text-color); border: none; box-shadow: 0px 4px 4px rgba(0, 0, 0,
0.15); border-radius: 4px; cursor: pointer; transition: background-color 250ms
cubic-bezier(0.4, 0, 0.2, 1);

&:hover, &:focus { background-color: var(--hover-color); } }

.footer-input\_\_icon-send { margin-left: 10px; fill:
var(--main-background-color); }
