# EECS151/251 sp22 Course Website

## Step 0: Make sure you have write access

  - Email your SSH public keys to inst@eecs.berkeley.edu to have it added to the eecs151 classmaster account
  - Only need to do this once

## Step 1: Edit and test locally
  - Add files to respective folders
  - Edit `index.html`
  - Test locally in a browser
    ```sh
    $ open ./index.html
    ```
  
## Step 2: Publish your updates
  - Commit and push to this repo
  - 
    ```sh
    $ ssh eecs151@cory.eecs.berkeley.edu
    $ cd ~/public_html/sp22
    $ git pull
    ```