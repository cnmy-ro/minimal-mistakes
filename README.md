# Personal Website
 
Based on the Jekyll theme [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes).



--------------
## Development
To set up your environment to develop this theme, run `bundle install`.

To test the theme, run `bundle exec rake preview` and open your browser at `http://localhost:4000/test/`. This starts a Jekyll server using content in the `test/` directory. As modifications are made to the theme and test site, it will regenerate and you should see the changes in the browser after a refresh.

For more information, check [GitHub Pages and Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)



------------------
## Editing content

- Artwork pages are stored as a collection. They're stored in the `_artwork` folder. The image files themselves are stored in `/assets/images/artwork_images`.

- Professional pages are stored in `_pages` to keep the projects and publications dirs together. If these 2 were to be made separate collections, they'd result in the case of including 2 collections in the `professional-overview` page, which is tricky.

- Inserting images in any page or post: 
	```html
	<figure class="full">
	    <a href="/assets/images/artwork_images/game_of_life.png">
	    	<img src="/assets/images/artwork_images/game_of_life.png" style="width:50%"></a>
	</figure>
	```



-------
## TODO

- Add dummy content to blog posts overview page
 
- Remove the search button on the mast. Or figure out how to add search functionality and make the button useful

- Should professional and open source overview pages have single or archive layout? Archive doesn't support table of contents. But, do these pages really need a table?