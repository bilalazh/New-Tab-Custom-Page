# Chrome New Redirect  Page 

## Motivations and Design Decisions : 
I always hated the page that appears when you press ```CTRL+T``` in chrome , and i used to change it  to blank page or some other extensions that change it entirely like [this](https://chromewebstore.google.com/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca)

_i set few goals for the new tab page i wanted to design_
- functional -> must add functionality and does not sacrifice function for form 
- reduces visual clutter (no icons or colors keeping mono or close to mono tone )
- lets me add custom links for all the websites i visit (lets you categorize links as well)
- keyboard centric ( most or ideally all  functionalty can be performed using your keyboard)
- modular but easy to maintain (ideally a single html file)

i made this without having any HTML , CSS or Js knowledge 



## Setup
### Installing necessary extension : 
We need some sort of extension that lets us run ``index.html``  file when we press the new tab page 

This extension named **Custom New Tab Url**
here is the link of the extension i have been using for this project 
[GO TO THIS LINK TO DOWNLOAD IT](https://chromewebstore.google.com/detail/custom-new-tab-url/mmjbdbjnoablegbkcklggeknkfcjkjia)




 use the alternative for better results 
  - add the documentation here 
format : 
-- name 
[]()  links 
-
--- how to add the url option to make sure the page works also 

--- add screenshot here 

## Alternatives : 
- i am using this instead  (HAVE TO TEST THIS ONE FOR FUNCTONALITY AND STABILITY )
[Fast New tab redirect](https://chromewebstore.google.com/detail/ohnfdmfkceojnmepofncbddpdicdjcoi)


here is another  option 
[Custom New tab on google webstore](https://chromewebstore.google.com/detail/custom-new-tab/lfjnnkckddkopjfgmbcpdiolnmfobflj)


## Todo: 


make the page on diff broswers show at the same positoon --> calculate the viewport 


solve the zoom issues 
- how zoom will work on different browsers -> adding more java script to make this  work should be a crime 
>> ideas i have  for this for now 
-- make the tab set to  a set zoom value everytine

 use and try and run this code to make the zoom work beter again (calcualte on runtime)
```js
window.onload = function() {
    // Get the browser's zoom level
    let browserZoomLevel = window.devicePixelRatio;

    // Calculate the required zoom level for the website
    let requiredZoomLevel = 0.8 / browserZoomLevel;

    // Set the zoom level of the website
    document.body.style.zoom = requiredZoomLevel * 100 + "%";
}

```
-- refactor java script


##### possible todos: 
    - add more categories for the commands i can add 


    - modularize the comamands tab as well 
    - give the website launch new tab -> put everything into websiteurlnaviagate.js or soemthing file

 - make sure you can switch theme from command bar 

 - yt in the command bar is not working because of the damn YT> that i added and i dont know how to fix this for now 
- choose other formats for the search engine commands use the suymbols that are not used maybe 