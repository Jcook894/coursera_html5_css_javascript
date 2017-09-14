Part #1

Development Environment Setup

1. Installed Sublime
2. Installed Git

Encountered issue with Macbook security.

Resolved by going into Preferences/Security/Allow Apps downloaded from Anywhere.

Go to terminal and check.

~/coursera/html_css_javascript (master)$ git --version
git version 2.14.1
hub version 2.2.3

3. Installed Node.js

I had a lot of issues with Node versions, and after many hours of struggling, I resolved by deleting ealrier version and installing a new one. 

~/coursera/html_css_javascript (master)$ node -v
v8.4.0
~/coursera/html_css_javascript (master)$ npm -v
5.4.0


4. Installed Browser Sync

npm install -g browser-sync

~/coursera/html_css_javascript (master)$ browser-sync --version
2.18.13

5. mkdir test_site
Create index.html and put some dummy text.

6. Go into test_site

browser-sync start --server --directory --files "*"

It will serve this directory and it will look up for a change in all files.

7. Create Github repository with README.md

Go to Settings and select source as master branch. Click Save.

In the same page, choose theme. Select a Theme. Commit changes.

Navigate to http://NatasaPeic.github.io/coursera_html5_css_javascript to get to your site.

If you forget the link, go to settings again, and under Github pages you will find the link where the page got published.

8. Go to the terminal and clone this repository.

9. Checkout new branch

git checkout -b week1

10. Create new folder

11. Create index.html and some dummy text.

12. Commit all changes, merge to master since we didn't get gh-pages.

git status
git add .
git commit -m "Test page"
git push origin week1

13. Go to Github and do pull request and merge branches.

14. Go to https://natasapeic.github.io/coursera_html5_css_javascript/site/ to see your content.

15. Make changes, commit them, push, merge on Github.

16. Go to https://natasapeic.github.io/coursera_html5_css_javascript/site/ to see your content.

17. Use broswer-sync

~/coursera/html_css_javascript/coursera_html5_css_javascript/site (week1)$ browser-sync start --server --directory --files "*"