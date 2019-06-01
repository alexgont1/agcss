# agcss
Website about me (used only HTML and CSS)

STEPS FOR HEROKU DEPLOYMENT:

1. Create new app on Heroku (choose good name, min 3 symbols)
2. Create empty Git repo with the same name
3. Open project folder in terminal
4.  Git init
5.  Git add -A
6.  Git commit -m "info..."
7. Add remore origin. Example: 
    git remote add origin git@github.com:alexgont1/agcss.git
8.  git push -u origin master

10. Open root repo directory with index.html
11. Create file: composer.json
12. Add line: {}
13. Create file: index.php
14. Add line: <?php include_once("index.html"); ?>

15. Open Heroku app page
16. Choose 'Connect to GitHub'
17. Search your repo on Git and click 'Connect'
18. In the bottom click 'Deploy branch' (master)
        'Your app was successfully deployed.' Click 'View' to see your website.
address = YOURappNAME.herokuapp.com
