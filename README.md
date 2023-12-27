# Chrome New Redirect  Page 

Index :
- [Motivations and Design Decisions ](#motivation)
- [Setup And Installation ](#set)
    - [Dependencies](#depend)
    - [Install Extension ](#ext)
    - [Configuring The Extension To Use Our Html Page](#ext)
 - [ANATOMY Of Page](#anatomy) 
 Features 
 Commands
 - [Themes](#theme)
    - [How to change the theme](#ct)
    - [Light theme screenshots](#Light)
    - [Dark theme screenshots](#Dark)
 Make It Your Own : 
 - Tested 
- [FAQs](#faq)



## Motivations and Design Decisions : <a name= "motivation"></a> 
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


## Setup And Installation <a name = "set"></a>
## Dependencies <a name = "depend"></a>
-  `Custom New Tab Url` extension 

### Install Extension : <a name = "ext"></a>
Since the page is just an ``index.html `` file , We need a chrome extension installed to load this page everytime we press ``Ctrl + T`` and open up a new tab 

This extension named **Custom New Tab Url**
here is the link of the extension i have been using for this project 
[GO TO THIS LINK TO DOWNLOAD IT](https://chromewebstore.google.com/detail/custom-new-tab-url/mmjbdbjnoablegbkcklggeknkfcjkjia)

![image](https://github.com/bilalazh/New-Tab-Custom-Page/assets/139261053/2cb35ced-e449-419f-a2da-656607fe0669)

just click  on `add to chrome ` button to get the extension 

#### Configuring The Extension To Use Our Html Page <a name = "conf"></a>
To configure the extesnsion to use the index.html page follow these steps 

go to the options (As shown here ) 
![image](https://github.com/bilalazh/New-Tab-Custom-Page/assets/139261053/63ee6082-b247-425b-b5a7-240d8d1b9006)

then you should see a ```URL or local file path``` Field 
and you can enter the path of your `index.html` file following this syntax 

```
file:///PATH-TO-INDEX.HTML
```
In my case the path was like this 
```
file:///D:\tab-local\index.html
```


- add the other extension here as well and if people want to use here as well


## ANATOMY Of Page: <a name = "anatomy"></a>

Here is the complete anatomy of page along with their features


##### Search 

Main search bar in the middle of screen is the main search area , it works just as a normal **Google Search** with additional super powers


#### How to use search : 

You can go to ``Search bar `` from anywhere by simply pressing the ``Tab`` key on your keyboard


**Enter your query**
When you press ``Tab `` you can enter any query in ``Search bar`` for example consider this 

```
How to take screenshot on mac 
```
press ``Enter `` and this query will be performed with  google search engines


##### Image (In the Center)
 image is sourced from the same folder see image section to know more 

### Alterantive Search Engines 

You can search`` metaphor.systems`` from ``Search bar`` by just adding ``>meta`` to your query in ``search bar``

here is a sample query to show you how this works

```
>meta latest ai papers 
```
and it will show you these [results](https://metaphor.systems/search?q=latest+ai+papers)

*More alternative search engines can be added in future as well*

### Search engines you can use right now with commands

| Search engine  | Commands to add  before query |
| -------- | -------- |
| Google search  | `google is default - no command is needed for google search`  |
|Metaphor.systems  | `>meta` |




## image

Images are loaded from images folder

Default image is AI generated and it matched the theme better so i decided to use it 

**To upload your own image** 
- put your image in the images folder located  in the same directory as the ``index.html`` file 
- add the path to iamge like this 

```
<img src="{{DRIVE LETTER}}:\{{PATH TO FOLDER}}\images\Your image.jpg" alt="Image " width="300px" height="300px">
```

Press ``Ctrl +R `` to reload the theme and you should see your image loaded 



- command bar 
- theme change 


## Commands


| Commands   | ``Function``  |
| -------- | -------- |
| theme | `changes and set defaults theme`  |
| ./news | `launches news websites` |
| ./ai | `launches news websites` |


-Type `theme` theme in command bar to change the theme 


## Themes <a name = "theme"></a>
- [Gruvbox](https://github.com/morhetz/gruvbox) and [Everforest](https://github.com/sainnhe/everforest) inspired theme , That uses colors from gruvbx but over all gives everforest kind of green vibe


### How to change the theme <a name = "ct"></a>
- Type ``theme`` in command bar your theme will be changed 
- Press ``Ctrl + y `` to change the theme quickly using keyboard






## Make It Your Own : 

if you want to make changes or add custom links here's how you can do that 

clone the project 

```
git clone link here
```

open index .html file with your favourite text editor 




### Browsers I  Tested This on  :

- Chrome 
- Chromium 
- Thorium 
- Brave 

> Those are all the broswers i have installed 
> the extension should work on any  `chromium based broswer` , and if you can install the extension that see _installation_ section for the rest of instructions 

### FAQs: <a name="faq" ></a>

 **Are you going to keep developing this ?**
- Yes , i plan to add more features and improve this over time , sicne when i made this i had no web dev experience ,  i might even do a clean better rewrite as well  


**??**
