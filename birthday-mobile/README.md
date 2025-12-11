## birthday-mobile

### Description

This is a modified version of the original birthday-basic project. As the original README states:

> The code written back then will drive you crazy.

The CSS code is indeed very messy (ಡωಡ). I've made some simple modifications so that it displays correctly on both computers and mobile phones.  On iPads, the images might overlap the text; I haven't specifically adapted it for iPads, and I assume very few people will use an iPad to scan the QR code and view the webpage...

### Prerequisites

<a href="#important">Important Notes</a>

If you have relevant front-end development experience, you can freely modify this template. The code is messy, but I'm not taking the blame; I'm blaming the original author (ಡωಡ).

If you don't have any front-end development experience, perhaps you should consider giving something else as a gift?

If you only have a basic understanding of related knowledge, you can read the guide below to learn about this template. ### Template Introduction
#### Changing the Password
In the current directory, there is a `js/index.js` file:
```javascript
// Change 123, 123 here to change the login username and password
if(userName=="123" &&  pwd=="123"){
event.preventDefault();
$('form').fadeOut(500);
$('.wrapper').addClass('form-success');
setTimeout(function(){location.href="BirthdayCake.html";},2000);
}
```

#### Replacing Text and Images on the Memories Page
Taking the third screen as an example:
```html
<!--Third Screen-->

<div class="section">
<!-- The two divs below implement the timeline and the small ball on the left -->
<div class="timeline"></div>
<div class="timepoint21"></div>
<div class="ly-box21">
<div class="ly-txt21">
<!-- Change the date here -->
201X-1X-2X
</div>
<div class="ly-txt22">
<!-- Change the content here, wrap paragraphs and line breaks with <p></p> -->
<p> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</p>
<p>XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</p>
</div>
<div class="ly-imgbox21">
<!-- Change the image here. Please rename the image and place it in the img folder.
If you don't understand CSS, it's best to crop the image to a suitable size.
If you know CSS, you can modify the width setting of the corresponding CSS using the class name.-->
<img class="ly-img21" src="img/2014.11.26-1.png">
</div>
</div>
<div class="ly-triangle21"></div>

<div class="ly-box22">
<div class="ly-txt23">
<!-- Similar to the above, no further explanation needed -->
201X-1X-1X
</div>
<div class="ly-txt24">
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
</div>
<div class="ly-imgbox22">
<img class="ly-img22"
``` ```html
<div class="ly-box22">
<div class="ly-txt24">
201X-1X-1X
</div>
<div class="ly-txt25">
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
</div>
<div class="ly-imgbox22">
<img class="ly-img22" src="img/2014.12.19-1.png">
</div>
</div>
<div class="ly-triangle22"></div>

<div class="ly-box23">
<div class="ly-txt25">
201X-1X-2X
</div>
<div class="ly-txt26">
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
</div>
<div class="ly-imgbox23">
<img class="ly-img23" src="img/2014.12.20-1.jpg">
</div>
</div>
<div class="ly-triangle23"></div>
</div>
```
## How to share with others
1. Compress the files into a zip archive and send it to others.
2. Deploy to a cloud server or virtual host (requires a domain name, which is more expensive).
3. Deploy to Gitee Pages (Gitee is in China, fast speed, WeChat will not block it, no domain name or server/virtual host required, almost zero cost).

If you need to access it with a domain name, please purchase a domain name first and then follow the tutorial for DNS resolution.

##### Little suggestions (ಡωಡ):

- Deploy the page to the cloud, generate a QR code for the address, and then hand-draw or engrave the QR code. This might be a good idea to show your thoughtfulness, but use it with caution, as it might only impress yourself in the end, and you could save time doing something else (ಡωಡ).
- The QR code can be engraved on a gift, such as a wooden craft, or drawn on a card and given with the gift.

## <a id="important" style="color: #000;">Important Notes</a>

Google Chrome browser updates will block automatic music playback, there is currently no solution (I don't know if there is one, I haven't researched it (ಡωಡ)).

Other Chrome-based browsers are not affected, such as the new Edge.

Firefox has not been tested.

**Due to different mobile screen sizes, it is recommended to modify the Memories.html page according to the actual screen size to prevent images from covering the text.** ## Other Issues
If you have any questions, please email [oxygen@mapletown.xyz](oxygen@mapletown.xyz). I will continue to update the README with common issues.

## Improvement Plan
None at the moment.  I may refactor the code later (it feels like a rewrite is needed) and improve browser compatibility.

## Screenshots

#### Desktop

<img src="screenshot/11.png" style="zoom: 80%;" />

<img src="screenshot/12.png" style="zoom:80%;" />

<img src="screenshot/14.png" style="zoom:80%;" />

#### Mobile (Narrow Screen, e.g., iPhone X)

<img src="screenshot/1.png" style="zoom: 25%;" />

<img src="screenshot/3.png" style="zoom: 25%;" />

<img src="screenshot/5.png" style="zoom: 25%;" />

#### Mobile (Wide Screen, e.g., Samsung S5)

<img src="screenshot/6.png" style="zoom: 25%;" />

<img src="screenshot/9.png" style="zoom:25%;" />

<img src="screenshot/10.png" style="zoom:25%;" />
