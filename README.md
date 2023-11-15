How To Publish a Trial Website 
=================================

1. Get write permission from `pmackenz`.  If you don't know how to contact them, you are most likely not part of our team.
2. Clone this repository in a folder parallel to your source repository. Clone the `pmackenz/TheDocu6_Playground`, **do not use a fork**!
3. Build your website using `make html` or `make TOOL html`. This will generate the `./build/html` or `./build/TOOL/html` folder and files.
4. Copy the entire contents of your `./build/html` or `./build/TOOL/html` folder to `TheDocu6_Playground/docs/.`  If that folder contains any files, delete the old ones first such that only your new files are in that folder.
5. Add an empty file named `TheDocu6_Playground/docs/.nojekyll` (no extension, no contents).
6. Execute
   ```
   $ git add .
   $ git commit -m "your helpful comment"
   $ git push
   ```
   in `TheDocu6_Playground`
7. Wait for 1-5 minutes and refresh the following link: https://pmackenz.github.io/TheDocu6_Playground/

You can test your setup locally before step 6. by opening `TheDocu6_Playground/docs/index.html`-file in your browser.
