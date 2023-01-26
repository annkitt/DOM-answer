# DOM Manipulation Assignmnt Answer
--------------------------------------------------------------------------------------------------------------------------
! 1.Website [dev to](https://dev.to/)
## Code
```
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerText = "Ankit Shukla"

document.querySelector(".side-bar .crayons-card p").innerHTML = "I write code"

```
! 2.Website [apple](https://support.apple.com/en-in)
## Code
```
let empArr = [];

document.querySelectorAll(".as-imagegrid-item").forEach((ex) => 
    empArr.push(ex.innerText.replace("\nSupport", "")));

console.log(empArr)
```
! 3.Website [youtube](https://support.google.com/youtube/#topic=9257498)
## Code 
```
const sec = document.createElement("section")

sec.innerHTML = "My New FAQ"

document.querySelector(".accordion-homepage").appendChild(sec)
```
!4.Website [oneplus](https://service.oneplus.com/in)
## Code
```
document.querySelector(".customer-support .service-number").innerText = "+91 98287 89090"
```
! 5.Website [samsung](https://www.samsung.com/in/offer/online/samsung-fest/)
## Code
```
let newid = document.querySelector(".feature-column-carousel__button .cta")

newid.setAttribute("id", "checkO")
// It sets attribute, if there is no atribute it creates one.

document.getElementById("checkO").innerText = "Check Out"
```
! 6.Website [adidas](https://www.adidas.co.in/)
## Code
```
function searchBG(){
    document.querySelector(".searchinput___zXLAR").style.backgroundColor="red";
}
document.addEventListener('mouseover',change_bg);
```
! 7.Website [MDN Web Docs](https://developer.mozilla.org/en-US/)
## Code
```
function search(text) {
	let input = document.querySelector("#top-nav-search-input");
	input.value = text;
	let btn = document.querySelector(".search-form");
	btn.submit();
}
search("Css Selector");
```
8.Website [Google](https://www.google.com/)
## Code 
```
let arr = document.querySelectorAll("#SIvCob a");

[...arr].forEach((element) => {
    var array = ["தமிழ்", "ગુજરાતી", "ಕನ್ನಡ", "മലയാളം", "ਪੰਜਾਬੀ"];
    if(array.includes(element.innerText)){
        element.remove();
    }
});
```
9.Website [Code Wars](https://www.codewars.com/)
## Code
```
document.querySelector(".content-width-extra-large .display-heading-1").style.fontFamily = "serif"

document.querySelector(".content-width-extra-large .display-heading-1").style.color = "#8B2E1D";
```
10.Website [FreeCodeCamp](https://www.freecodecamp.org/)
## Code
```
function changeBG(){
    document.querySelector(".btn-cta-big .login-btn-text").style.backgroundColor = "red";
};

document.addEventListener("click", changeBG)
```
11.Website [realme](https://www.realme.com/in/)
## Code 
```
document.querySelector(".wrapper .gtag .icon-logo ").style.backgroundImage = "url(https://ineuron.ai/images/ineuron-logo.png)";
```
12.Website [Github](https://github.com/)
## Code
```
document.querySelector(".js-repos-container h2 a").style.backgroundColor = "blue";
```
13.Website [Hackerrank](https://www.hackerrank.com/)
## Code
```
document.querySelector(".fl-module ").innerHTML = "JSBOOTCAMP"
'JSBOOTCAMP'
```
14.Website [Asus](https://www.asus.com/in/)
```
document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize = "100px";
'100px'
```
15.Website [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)
## Code
```
document.querySelector(".ps-title a").style.textAlign = "right";
```