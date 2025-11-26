
TASK8:

## Project overview

- Title: Modern Blog (single-page layout).
- Tech stack: HTML5, CSS3, Bootstrap 5.3 (via CDN), Bootstrap Icons (via CDN).
- Purpose: Display a basic blog landing page with navigation, featured posts, and social links.

## Features

- Responsive navbar with brand, menu links (Home, Posts, About, Contact), and collapsible toggler for mobile.
- “Latest Blog Posts” grid showing four cards with placeholder images, titles, short descriptions, and “Read More” buttons.
- Custom styling for background, typography, card radius, and gradient navbar.
- Footer with “Follow Us” text, social icons (Facebook, Instagram, X/Twitter, YouTube), and copyright.

## File structure

Recommended minimal structure:

- index.html – Main page (the code you provided).
- /assets/
  - /css/ (optional if you move styles into a separate CSS file)
  - /img/ (optional if you replace placeholder images with local ones)

You can also keep everything in a single index.html file as shown.

## Getting started

1) Prerequisites  
- A modern web browser (Chrome, Firefox, Edge, Safari).  
- A code editor (VS Code, Sublime Text, etc.).

2) How to run locally  
- Create a new folder (e.g., modern-blog).  
- Save the provided code as index.html inside that folder.  
- Double-click index.html or open it via your browser’s “Open File” option.  
- The page will load with the Bootstrap and icon CDNs as long as you are online.

3) Editing content  
- Change the brand name: In the navbar, replace “MyBlog” with your blog name.  
- Update menu links: Replace the # in href="#" with real URLs or section IDs.  
- Modify posts:  
  - Change image URLs in each <img> tag.  
  - Replace “Post One/Two/Three/Four” with your real titles.  
  - Edit the short intro text in each <p class="card-text text-muted">.  
  - Point “Read More” buttons to full post pages.  
- Update footer text and links:  
  - Replace href="#" in social links with your real profiles.  
  - Change “2024 MyBlog” to your current year and brand.

## Customization

- Colors and fonts:  
  - Adjust the body background color and font in the body CSS rule.  
  - Edit the navbar gradient in .navbar-custom.  
- Layout:  
  - Change the number of posts by adding or removing the col-md-4 col-lg-3 card columns.  
- External CSS:  
  - For larger projects, move the <style> block into style.css and link it in the <head>.

## Deployment

- Static hosting options:  
  - GitHub Pages, Netlify, or Vercel.  
- Steps (general):  
  - Push or upload index.html (and any assets) to your chosen hosting service.  
  - Configure the service to serve index.html as the default page.
 
    OUTPUT:
    <img width="1866" height="975" alt="Screenshot 2025-11-26 183512" src="https://github.com/user-attachments/assets/fb5a727d-cbfb-44bb-8c44-2b589ea5d4c1" />





