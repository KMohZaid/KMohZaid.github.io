# Github Pages Template

GitHub offers free web hosting for your profile and each of your repositories through a feature called [Github Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages). This template provides a starting point to easily create a professional looking *blog*, *resume*, *portfolio*, or website for further customization :fire::fire:


**Still not convinced?**
<br>
Checkout example [screenshots](#Screenshots) or visit [m8r0wn.com](https://m8r0wn.com).
<br>
<br>

## Getting Started
:fork_and_knife: **Fork this Repository:**
<br><br>
<kbd>
  <img width="700" src="https://user-images.githubusercontent.com/13889819/120089642-41839000-c0ca-11eb-981b-e7ac784cb747.png">
</div>
<br>

:open_file_folder: **Change the Repository Name**
<br>
Change the repository name to `<YOUR_USERNAME_HERE>.github.io` under **Settings > Repository name**:
<br><br>
<kbd>
  <img width="700" alt="fork_name" src="https://user-images.githubusercontent.com/13889819/120089619-2284fe00-c0ca-11eb-8e8c-d654561f2f04.png">
</kbd>
<br>
<br>

:lock: **Add HTTPS**
<br>
Add HTTPS by checking the box at **Settings > Pages > Enforce HTTPS**:
<br><br>
<kbd>
  <img width="700" alt="https" src="https://user-images.githubusercontent.com/13889819/120089629-2f095680-c0ca-11eb-8b53-691bf8252b19.png">
</kbd>
<br>
<br>

:globe_with_meridians: **Enjoy!**
<br>
Visit your new website at `https://<USERNAME>.github.io`!
<br><br>


## Features
* **Config.js** - The `config.js` file allows users to control and modify the 
site's color scheme, banner image, social media links, and more all from one place. 

* **Pre-Marked Templates** - The project's exiting directory structure and pages provide content creators with 
a great starting point. However, the template's easily marked `[EDIT]` fields supports even the most novice of users.
This helps users place site content, navigation links, even Search Engine Optimization (SEO) tags.

* **Client-Side Templating** - The site's navigation bar and footer utilize client-side templating, which allows for easy 
customization and maintenance. If needed, users can modify these objects under the `/templates/` directory.

* **Mobile Friendly** - CSS styling is used to create a responsive web design. This means the sizing of page 
elements automatically adjusts based on screen width to optimize the site for a variety of devices.
  
* **Dynamically List Blog Titles** - Users can dynamically create a blog index on the Home page by 
reading from their site's `rss.xml` feed or through a dedicated `JSON` data file. These options are clearly marked at the 
bottom of `/index.html`.
  
```text
RSSReader(RSS_Source, img=0, desc=0)
    Create a blog index using the sites own RSS feed. Provide the source url, option to include images,
    and option to include post descriptions (0=False [Default], 1=True).

JSONReader(JSON_SOURCE, img=0, desc=0)
    Create blog index by reading data from a given JSON file. Provide the source url, option to include images,
    and option to include post descriptions (0=False [Default], 1=True).

e.x: /index.html
<script>
    RSSReader('/rss.xml', img=0, desc=1);
</script>  
```
<br>

## Screenshots
![screenshot](https://user-images.githubusercontent.com/13889819/121216411-dca90200-c84e-11eb-9f3d-480a30a1d200.png)
<br>

## Resources
<p style="display:inline;">
  <a href="https://jquery.com/">
    <img width="100px" src="https://user-images.githubusercontent.com/13889819/120321084-de078700-c2b0-11eb-8e29-a76816a6fea2.png">
  </a>&nbsp;&nbsp;&nbsp;
  <a href="https://getbootstrap.com/">
    <img width="100px" src="https://user-images.githubusercontent.com/13889819/120321100-e19b0e00-c2b0-11eb-9a92-c29e3518a828.png">
  </a>&nbsp;&nbsp;&nbsp;
  <a href="https://materializecss.com/">
    <img width="100px" src="https://user-images.githubusercontent.com/13889819/120323529-92a2a800-c2b3-11eb-86eb-191f81c3912c.png">
  </a>&nbsp;&nbsp;&nbsp;
  <a href="https://highlightjs.org/">
    <img width="100px" src="https://user-images.githubusercontent.com/13889819/120506550-07e5aa00-c394-11eb-8d66-078a32216329.png">
  </a>
  
</p>
