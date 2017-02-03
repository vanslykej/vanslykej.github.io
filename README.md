You are invited to use this repository as a means for learning more about how to implement a mobile-ready web site using Jekyll. If you find this repository useful, could I trouble you to star and then acknowledge it in your own web development efforts?

If you have not already created an SSH key then you need to create one and then using "cat ~/.ssh/id_rsa.pub" in your terminal, copy this content into the window.

You then need to fork the repository and then rename it to "<your GitHub user name>.github.io" Then clone the repository using SSH, not HTTPS. Then type "bundle install --path ~/.gem" into your terminal and wait for the files to download. When this is done type "bundle exec jekyll serve" in the terminal and search for "http://127.0.0.1:4000" and you should see the development site.

Then go to GitHub Pages in your profile and click the link and you should see the live site. You can then edit the _confit.yml to fit your desired content. You can change the aboutme file especially.

Finally, git add, commit, and push this content to your live site.
