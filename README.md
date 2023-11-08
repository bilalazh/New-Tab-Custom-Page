# Chrome New Redirect  Page 

## Motivations and Design Decisions : 
I always hated how the new tab page funcioned and looked , it was missing some core function 

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



