# react-monsters-rolodex

For hosting ReactJS app to github static pages do following steps.

# Step 1

git remote add origin git@github.com:bhavik103/react-monsters-rolodex.git

Here "git@github.com:bhavik103/react-monsters-rolodex.git" is your git respository ssh key.

# Step 2

npm add gh-pages

# Step 3

Add "homepage": "https://bhavik103.github.io/react-monsters-rolodex" this in package.json above "dependency".

# Step 4

Add this 2 "predeploy":"yarn build" and  "deploy": "gh-pages -d build" inside scripts object in package.json

# Step 5

Run yarn deploy command from your terminal.

# Step 6

git add *

# Step 7

git commit -m "message"

# Step 8

git push origin master
