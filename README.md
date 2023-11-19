# Chrome New Redirect  Page 

Index :
Motivations and Design Decisions : 
 Setup


Alternatives  

## Motivations and Design Decisions : 
I always hated the page that appears when you press ```CTRL+T``` in chrome , and i used to change it  to blank page or some other extensions that change it entirely like [this](https://chromewebstore.google.com/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca)

_i set few goals for the new tab page i wanted to design_
- functional -> must add functionality and does not sacrifice function for form 
- reduces visual clutter (no icons or colors keeping mono or close to mono tone )
- lets me add custom links for all the websites i visit (lets you categorize links as well)
- keyboard centric ( most or ideally all  functionalty can be performed using your keyboard)
- modular but easy to maintain (ideally a single html file)





##### Skill Issues : 
i made this without having any HTML , CSS or Js knowledge 
i just googled  my way to some how a fully functional page (read some commit messages they really show you how much fun it was **insert sarcasm**)

despite of all this it works and is easily modifiable and extensible to fit your specific needs or you can add your own links anywhere  see [[Make it your own ]] section for more information 


## Setup

## Dependencies 
-  `Custom New Tab Url` extension 

### Install Extension : 
Since the page is just an ``index.html `` file , We need a chrome extension installed to load this page everytime we press ``Ctrl + T`` and open up a new tab 

This extension named **Custom New Tab Url**
here is the link of the extension i have been using for this project 
[GO TO THIS LINK TO DOWNLOAD IT](https://chromewebstore.google.com/detail/custom-new-tab-url/mmjbdbjnoablegbkcklggeknkfcjkjia)

![image](https://github.com/bilalazh/New-Tab-Custom-Page/assets/139261053/2cb35ced-e449-419f-a2da-656607fe0669)

just click  on `add to chrome ` button to get the extension 

#### Configuring The Extension To Use Our Html Page
To configure the extesnsion to use the index.html page follow these steps 

go to the options (As shown here ) 
![image](https://github.com/bilalazh/New-Tab-Custom-Page/assets/139261053/63ee6082-b247-425b-b5a7-240d8d1b9006)

then you should see a ```URL or local file path``` Field 
and you can enter the path of your `index.html` file following this syntax 

```
file:///PATH-TO-INDEX.HTML
```
In my case it was 
```
file:///D:\tab-local\index.html
```



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



## Make It Your Own : 
