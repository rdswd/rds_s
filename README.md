rds_s
===
This is my starter theme based upon _s by automattic. Below are the instructions for search and replace to change the name of the theme (directly from _s readme only _s is changed to rds_s).


Getting Started
---------------

If you want to keep it simple, head over to http://underscores.me and generate your `_s` based theme from there. You just input the name of the theme you want to create, click the "Generate" button, and you get your ready-to-awesomize starter theme.

If you want to set things up manually, download `rds_s` from github. The first thing you want to do is copy the `rds_s` directory and change the name to something else - Like, say, `megatherium` - then you'll need to do a five-step find and replace on the name in all the templates.

1. Search for `'rds_s'` (inside single quotations) to capture the text domain.
2. Search for `rds_s_` to capture all the function names.
3. Search for `Text Domain: rds_s` in style.css.
4. Search for <code>&nbsp;rds_s</code> (with a space before it) to capture DocBlocks.
5. Search for `rds_s-` to capture prefixed handles.

OR

* Search for: `'rds_s'` and replace with: `'megatherium'`
* Search for: `rds_s_` and replace with: `megatherium_`
* Search for: `Text Domain: rds_s` and replace with: `Text Domain: megatherium` in style.css.
* Search for: <code>&nbsp;rds_s</code> and replace with: <code>&nbsp;Megatherium</code>
* Search for: `rds_s-` and replace with: `megatherium-`

Then, update the stylesheet header in style.css and the links in footer.php with your own information. Next, update or delete this readme.

Now you're ready to go! The next step is easy to say, but harder to do: make an awesome WordPress theme. :)

Good luck!
