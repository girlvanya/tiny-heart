## birthday-basic

### Description
These are the first three static web pages I ever wrote. You can customize them and give them to your friends/significant other/friends who might become your significant other after receiving them, lol.

Because these were the first web pages I wrote for someone, there might be quite a few problems. Please forgive me if you encounter any issues during use.

### Online Preview
http://119.23.212.211:8080/birthday-basic/
Username: 123 Password: 123

### Prerequisites
If you have relevant front-end development experience, you can freely modify this template. I believe the code I wrote back then will drive you crazy (manual smirk, I'm angry at myself when I look at it now).

If you don't have any front-end development experience, perhaps you should consider giving something else?

If you only have a basic understanding of relevant knowledge, you can read the guide below to understand this template.

### Template Introduction
#### Changing the Password
In the current directory, there is a js/login.js file:
```javascript
// Modify 123, 123 here to change the login username and password
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
<!-- The two divs below respectively implement the axis on the left and the small ball -->
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
If you know CSS, you can modify the width setting of the corresponding CSS based on the class name.-->
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

## How to Share with Others
1. Compress the files into an archive and send it to others.
2. Deploy to a cloud server or virtual host.
1. Deploying to a cloud server requires owning your own cloud server. There are many deployment methods; here are two recommended methods:
- Using Tomcat:
Download and extract Tomcat on the server. After extraction, open the webapps folder, and create a new folder with an English name (this will be the path name). After downloading this project, copy the current directory (note: only copy the files, including index.html and other HTML, CSS, and JS files) into the newly created folder, then restart Tomcat.
- Using Nginx:
The method is similar; I won't go into detail here, you can search for it on Baidu.
2. For deployment to a virtual host, there will be tutorials provided by the virtual host provider.

If you need to access it using a domain name, please purchase a domain name first and then follow the tutorial for DNS resolution.

## Notes
Please use the Google Chrome browser!

No mobile version available!

## Other Questions
If you have any questions, please send an email to guoxiaofeng_2015@163.com. I will continue to update the readme with common issues.

## Development Plan
1. Modify the Memories page layout to ensure widescreen adaptability.
2. Pay attention to browser compatibility.
3. Pay attention to the display on mobile devices.
4. Dynamically generate the memories module.
These will be done gradually when I have time.  Welcome to stay tuned!
