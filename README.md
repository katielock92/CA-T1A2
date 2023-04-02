# Katie's Portfolio Website *(Coder Academy Term 1 Assignment 2)*

## **About**
The purpose of this website is establish a portfolio for myself (Katie Lock) as a new web developer. This website will not only list and demonstrate the skills that I have learnt so far (both within my Coder Academy bootcamp along with prior learning), but also give the user an understanding of my personality and experience outside of coding.

The expected user of my website would be recruiters and/or hiring managers for entry-level web development/engineering roles - who either are proactively seeking out candidates, or have viewed an application that I have placed for an advertised role.

___

## **Links**
- [Published portfolio website](https://katieelsomlock.com)
- [GitHub repo](https://github.com/katielock92/portfolio)
- [Presentation video](https://www.canva.com/design/DAFeiibsjEs/r35r7yrxEIBhDT2SEvmOJA/view?utm_content=DAFeiibsjEs&utm_campaign=designshare&utm_medium=link&utm_source=recording_view)

___
## **Functionality and Features**
The key functionality and features of my portfolio website are:
- multiple pages linked from a nav bar on the main home page, including:
    - **about** - more about who I am, my background and experience prior to coding, along with my hobbies and interests
    - **portfolio** - a demonstration of my coding work so far *(with placeholders to add future work)*
    - **blog** - a place where I can write posts about topics that I am passionate about, and/or share my learnings so far in this course *(can include placeholders for future posts)*
    - **contact** - a way that users can contact me
- designed with a **mobile first** approach, using multiple break points to have suitable adapted layouts for various screen sizes
- designed with **accessibility** at front of mind:
    - a simplistic layout that does not cause sensory overload
    - alt text on all visual elements
    - colour palette designed to have meaning, even for those who are colour blind
    - semantic elements used when building layout

As I had already developed a similar website for my Diversity in Tech scholarship application, I have linked to the original website from my portfolio to demonstrate my growth since beginning this course.

___

## **Tech Stack**
When planning, developing and deploying my portfolio website, I used the following tools and languages:
- **Figma** - sitemap and wireframes
- **VS Code** - IDE for writing code
- **Markdown** - for writing README
- **HTML** - for the elements and content of web pages
- **CSS and SCSS** - styling of web pages
- **JavaScript** - for the interactivity on the mobile navigation menu
- **GitHub** - version control
- **Cloudflare** - web hosting

___
## **Sitemap, Design and Wireframes**
### **Sitemap**
This sitemap image was developed prior to commencing any coding, and remained consistent as I developed the website in terms of the structure and flow of the pages:
![Image of the sitemap for this portfolio website](./docs/Sitemap%20and%20Wireframes/Sitemap.png)

### **Design**
A font and colour palette was developed prior to commencing coding:
![Image of the font and colour palette](./docs/Sitemap%20and%20Wireframes/Font%20and%20Colour%20Palette.png)
In the end, I used *Sora* as the font across all areas of the site even though *Assistant* is still available as an option in my *_fonts.scss* file.

### **Wireframes**
Basic wireframes for each page were created in Figma prior to commencing coding. Each page has 3 versions of the wireframe for various breakpoints:
- Mobile
- Tablet
- Desktop

These wireframes are high level and not indicatative of margins, padding, font sizes, etc. to be used - but rather than overall placement of elements. The key similarities across all pages are:
- **Mobile view** only has a logo in the top-left of the header, along with a hamburger menu for navigation
- **Tablet view** expands to add my name next to the logo (similar to what will show on desktop view), but retains the hamburger navigation menu
- **Desktop view** takes advantage of the larger width to have the navigation bar visible in a row in the top-right of the header

Images of the wireframes (along with comments about any major design changes made in development) can be found below.

### **Page Design 1: Home**

*Mobile view:*

![Basic wireframe for home page in mobile view](./docs/Sitemap%20and%20Wireframes/Home%20-%20Mobile%20View.png)

*Tablet view:*

![Basic wireframe for home page in tablet view](./docs/Sitemap%20and%20Wireframes/Home%20-%20Tablet%20View.png)

*Desktop view:*

![Basic wireframe for home page in desktop view](./docs/Sitemap%20and%20Wireframes/Home%20-%20Desktop%20View.png)

### **Page Design 2: About**
Note: the two main design deviations from the wireframes below are:
- All versions have a page heading at the top, above the images but below the header bar
- The div without a border (intended to hold my work experience) was replaced with two separate divs, both with borders - one for education, and one for work experience

*Mobile view:*

![Basic wireframe for about page in mobile view](./docs/Sitemap%20and%20Wireframes/About%20-%20Mobile%20View.png)

*Tablet view:*

![Basic wireframe for about page in tablet view](./docs/Sitemap%20and%20Wireframes/About%20-%20Tablet%20View.png)

*Desktop view:*

![Basic wireframe for about page in desktop view](./docs/Sitemap%20and%20Wireframes/About%20-%20Desktop%20View.png)

### **Page Design 3: Portfolio**

*Mobile view:*

![Basic wireframe for portfolio page in mobile view](./docs/Sitemap%20and%20Wireframes/Portfolio%20-%20Mobile%20View.png)

*Tablet view:*

![Basic wireframe for portfolio page in tablet view](./docs/Sitemap%20and%20Wireframes/Portfolio%20-%20Tablet%20View.png)

*Desktop view:*

![Basic wireframe for portfolio page in desktop view](./docs/Sitemap%20and%20Wireframes/Portfolio%20-%20Desktop%20View.png)


### **Page Design 4: Individual portfolio posts**

Note: one design deviation here is that all portfolio posts will have a button at the bottom prompting the user to return to the main portfolio page. There is the option with the css to have a second button displayed alongside this button, for use when any projects can actually be directly linked.

*Mobile view:*

![Basic wireframe for individual portfolio post page in mobile view](./docs/Sitemap%20and%20Wireframes/Portfolio%20Post%20-%20Mobile%20View.png)

*Tablet view:*

![Basic wireframe for individual portfolio post page in tablet view](./docs/Sitemap%20and%20Wireframes/Portfolio%20Post%20-%20Tablet%20View.png)

*Desktop view:*

![Basic wireframe for individual portfolio post page in desktop view](./docs/Sitemap%20and%20Wireframes/Portfolio%20Post%20-%20Desktop%20View.png)

### **Page Design 5: Blog**

Note: the wireframes only show 3-4 blog posts for simplicity, however the website is set up to show a minimum of 5.

*Mobile view:*

![Basic wireframe for blog page in mobile view](./docs/Sitemap%20and%20Wireframes/Blog%20-%20Mobile%20View.png)

*Tablet view:*

![Basic wireframe for blog page in tablet view](./docs/Sitemap%20and%20Wireframes/Blog%20-%20Tablet%20View.png)

*Desktop view:*

![Basic wireframe for blog page in desktop view](./docs/Sitemap%20and%20Wireframes/Blog%20-%20Desktop%20View.png)

### **Page Design 6: Individual blog posts**

Note: similar to the portfolio post page, when developing the individual blog post page I opted to add a bottom at the bottom of the blog, which returns the user back to the main blog page.

*Mobile view:*

![Basic wireframe for individual blog post page in mobile view](./docs/Sitemap%20and%20Wireframes/Blog%20Post%20-%20Mobile%20View.png)

*Tablet view:*

![Basic wireframe for individual blog post page in tablet view](./docs/Sitemap%20and%20Wireframes/Blog%20Post%20-%20Tablet%20View.png)

*Desktop view:*

![Basic wireframe for individual blog post page in desktop view](./docs/Sitemap%20and%20Wireframes/Blog%20Post%20-%20Desktop%20View.png)

### **Page Design 7: Contact**

*Mobile view:*

![Basic wireframe for contact page in mobile view](./docs/Sitemap%20and%20Wireframes/Contact%20-%20Mobile%20View.png)

*Tablet view:*

![Basic wireframe for blog page in tablet view](./docs/Sitemap%20and%20Wireframes/Contact%20-%20Tablet%20View.png)

*Desktop view:*

![Basic wireframe for blog page in desktop view](./docs/Sitemap%20and%20Wireframes/Contact%20-%20Desktop%20View.png)

___

## **Final Result**

I am really happy with the outcome and what I have achieved! Please see below for a directory of screenshots for each page on my site, sorted by the various viewports:

### **Page 1: Home**

*Mobile view:*

![Home page of my website in mobile view](./docs/Screenshots/Home-Mobile.png)

*Tablet view:*

![Home page of my website in tablet view](./docs/Screenshots/Home-Tablet.png)

*Desktop view:*

![Home page of my website in desktop view](./docs/Screenshots/Home-Desktop.png)

### **Page 2: About**

*Mobile view:*

![About page of my website in mobile view (1/5)](./docs/Screenshots/About-Mobile-P1.png)
![About page of my website in mobile view (2/5)](./docs/Screenshots/About-Mobile-P2.png)
![About page of my website in mobile view (3/5)](./docs/Screenshots/About-Mobile-P3.png)
![About page of my website in mobile view (4/5)](./docs/Screenshots/About-Mobile-P4.png)
![About page of my website in mobile view (5/5)](./docs/Screenshots/About-Mobile-P5.png)

*Tablet view:*

![About page of my website in tablet view (1/3)](./docs/Screenshots/About-Tablet-P1.png)
![About page of my website in tablet view (2/3)](./docs/Screenshots/About-Tablet-P2.png)
![About page of my website in tablet view (3/3)](./docs/Screenshots/About-Tablet-P3.png)

*Desktop view:*

![About page of my website in desktop view (1/2)](./docs/Screenshots/About-Desktop-P1.png)
![About page of my website in desktop view (2/2)](./docs/Screenshots/About-Desktop-P2.png)

### **Page 3: Portfolio**

*Mobile view:*

![Portfolio page of my website in mobile view (1/3)](./docs/Screenshots/Portfolio-Mobile-P1.png)
![Portfolio page of my website in mobile view (2/3)](./docs/Screenshots/Portfolio-Mobile-P2.png)
![Portfolio page of my website in mobile view (3/3)](./docs/Screenshots/Portfolio-Mobile-P3.png)

*Tablet view:*

![Portfolio page of my website in tablet view (1/3)](./docs/Screenshots/Portfolio-Tablet-P1.png)
![Portfolio page of my website in tablet view (2/3)](./docs/Screenshots/Portfolio-Tablet-P2.png)
![Portfolio page of my website in tablet view (3/3)](./docs/Screenshots/Portfolio-Tablet-P3.png)

*Desktop view:*

![Portfolio page of my website in desktop view (1/2)](./docs/Screenshots/Portfolio-Desktop-P1.png)
![Portfolio page of my website in desktop view (2/2)](./docs/Screenshots/Portfolio-Desktop-P2.png)

### **Page(s) 4: Individual portfolio posts**

There are a few different posts linked, along with a placeholder version:

*Mobile view:*

![Portfolio post page of my website in mobile view (1/2)](./docs/Screenshots/PortfolioPost-Mobile-P1.png)
![Portfolio post page of my website in desktop view (2/2)](./docs/Screenshots/PortfolioPost-Mobile-P2.png)

*Tablet view:*

![Portfolio post page of my website in tablet view (1/2)](./docs/Screenshots/PortfolioPost-Tablet-P1.png)
![Portfolio post page of my website in desktop view (2/2)](./docs/Screenshots/PortfolioPost-Tablet-P2.png)

*Desktop view:*

![Portfolio post page of my website in desktop view (1/2)](./docs/Screenshots/PortfolioPost-Desktop-P1.png)
![Portfolio post page of my website in desktop view (2/2)](./docs/Screenshots/PortfolioPost-Desktop-P2.png)

### **Page 5: Blog**

*Mobile view:*

![Blog page of my website in mobile view (1/3)](./docs/Screenshots/Blog-Mobile-P1.png)
![Blog page of my website in mobile view (2/3)](./docs/Screenshots/Blog-Mobile-P2.png)
![Blog page of my website in mobile view (3/3)](./docs/Screenshots/Blog-Mobile-P3.png)

*Tablet view:*

![Blog page of my website in tablet view (1/2)](./docs/Screenshots/Blog-Tablet-P1.png)
![Blog page of my website in tablet view (2/2)](./docs/Screenshots/Blog-Tablet-P2.png)

*Desktop view:*

![Blog page of my website in desktop view (1/2)](./docs/Screenshots/Blog-Desktop-P1.png)
![Blog page of my website in desktop view (2/2)](./docs/Screenshots/Blog-Desktop-P2.png)

### **Page(s) 6: Individual blog posts**

There are a few different posts linked, along with a placeholder version:

*Mobile view:*

![Blog post page of my website in mobile view (1/4)](./docs/Screenshots/BlogPost-Mobile-P1.png)
![Blog post page of my website in mobile view (2/4)](./docs/Screenshots/BlogPost-Mobile-P2.png)
![Blog post page of my website in mobile view (3/4)](./docs/Screenshots/BlogPost-Mobile-P3.png)
![Blog post page of my website in mobile view (4/4)](./docs/Screenshots/BlogPost-Mobile-P4.png)

*Tablet view:*

![Blog post page of my website in tablet view (1/3)](./docs/Screenshots/BlogPost-Tablet-P1.png)
![Blog post page of my website in tablet view (2/3)](./docs/Screenshots/BlogPost-Tablet-P2.png)
![Blog post page of my website in tablet view (3/3)](./docs/Screenshots/BlogPost-Tablet-P3.png)

*Desktop view:*

![Blog post page of my website in desktop view (1/2)](./docs/Screenshots/BlogPost-Desktop-P1.png)
![Blog post page of my website in desktop view (2/2)](./docs/Screenshots/BlogPost-Desktop-P2.png)

### **Page 7: Contact**

*Mobile view:*

![Contact page of my website in mobile view](./docs/Screenshots/Contact-Mobile.png)

*Tablet view:*

![Contact page of my website in tablet view](./docs/Screenshots/Contact-Tablet.png)

*Desktop view:*

![Contact page of my website in desktop view](./docs/Screenshots/Contact-Desktop.png)
