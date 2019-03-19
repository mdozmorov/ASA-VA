# Web page for the Virginia chapter of American Statistical Association

https://asa-va.netlify.com/

- Background image - http://unboundrva.org/learning-valley-building-impact-part-ii/
- Panel image - http://www.naturemuseum.org/the-museum/blog/archive/2017/11

## Building web site

- Copy the `*.md` files in the `static` folder into the `content` folder
- `blogdown::serve_site()` will build the site in the `public` folder and serve it. Any changes will trigger rebuilding. Note folders with the same names as the `*.md` files appear in the `public` folder.
- `blogdown::stop_server()` will stop the server
- Move the `*.md` files from the `content` folder to the `static` folder. This will ensure these `*.md` files are compiled as pages, not as blog posts.
- Push the content of the `public` folder to GitHub. Netlify should be [configured](https://bookdown.org/yihui/blogdown/netlify.html) 
