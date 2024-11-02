# startpage

As the name suggests startpage is a **small website** that can hold your **favorite sites** (links) and **display them** for you in **one page**.   
In simpler terms: A small **Landing page**

## Screenshot 
![startpage](https://github.com/user-attachments/assets/d24fb559-c332-432a-8e5a-baea57a1e8bb)

## USAGE
1. **Download / Clone** the project
2. Configure your webserver of choice (**Apache / NGinx / Lighttpd / etc.**)
3. Navigate to the site with any modern browser (**Firefox / Brave / etc.**)

## Info
You can add your own links by editing the given **index.html** file.
```html
<div class="items">
      <h2 class="list-heading">0x01</h2>
      <ul>
        <li><a href="https://twitter.com">Twitter</a></li>
        <li><a href="https://reddit.com">Reddit</a></li>
        <li><a href="https://youtube.com">YouTube</a></li>
        <li><a href="https://bsd.network">bsd.network</a></li>
        <li><a href="https://startpage.com">Startpage</a></li>
        <li><a href="https://jhx0.github.io/">Webpage</a></li>
      </ul>
</div>
```
Every entry is a simple **"li"** entry into the **HTML** file.
