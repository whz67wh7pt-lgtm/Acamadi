ACAMADI BLOG SETUP
==================

This folder contains ONLY the new blog/CMS files. Do not delete or replace the existing website files.

1. Upload to the repository root:
   - _config.yml
   - .pages.yml
   - blogs.html

2. Upload these folders exactly as supplied:
   - _layouts/
   - _posts/
   - images/blog/

3. Open blog-css-addition.txt, copy everything inside it, and paste it at the VERY BOTTOM of the existing styles.css file.

4. Add an Insights/Blogs link to the main navigation in index.html and the service pages:

   <a href="blogs.html">Insights</a>

5. Commit the changes and allow GitHub Pages a minute or two to rebuild.

6. Test:
   https://whz67wh7pt-lgtm.github.io/Acamadi/blogs.html

7. CMS setup:
   - Go to https://app.pagescms.org
   - Sign in with GitHub
   - Install/authorise the Pages CMS GitHub App for the Acamadi repository
   - Open the Acamadi repository
   - Pages CMS will read .pages.yml and show a "Blog posts" collection

The customer can then create/edit posts using normal fields rather than editing HTML.

IMPORTANT:
The four included posts are short ORIGINAL DEMO REWRITES based on the subjects already present on the current ACAMADI blog. They are not copies of the live articles. If the owner approves the redesign and wants the existing articles migrated word-for-word, use the owner's original source content/files or explicit permission before replacing the demo copy.

FEATURED IMAGES:
Pages CMS stores uploaded featured images in images/blog/. The article body editor is intentionally text-only for now, which avoids broken image paths while the site is previewed under the /Acamadi GitHub Pages project path. Once the final custom domain is connected, body-image uploads can be enabled easily.
