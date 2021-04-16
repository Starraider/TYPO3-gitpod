
# TYPO3 + Gitpod

## Set up a full TYPO3 dev environment in a browser

## Try it out

1. Click on the following link https://gitpod.io/#https://github.com/Starraider/TYPO3-gitpod
2. Your environment is being prepared, wait about 40 seconds (A splash screen will appear)
3. VScode (or Theia) IDE will be displayed.
4. Note that one terminal is running sudo docker-up, and another terminal in parallel is running ddev start
5. Find your website's URL gp url 8080
6. Open your website's URL in a browser, you should see Drupal's installation screen.
7. Run in terminal ddev drush si demo_umami -y
8. Open your website's URL in a browser, you should see Drupal's Umami demo.
9. Run in terminal ddev xdebug on
10. Open VScode's debugger, place a new breakpoint in web/index.php
11. Open your website's URL in a browser.
12. 🎉
