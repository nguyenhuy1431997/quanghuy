# Giasudanang

## How to get started
We will have 4 main branches
- Master: for product
- Develop: for coding -> we work in this branch
- Release
- Hotfix

1. Clone the git
git clone https://github.com/DungLe1603/web_giasu //default in develop

2. Checkout to a new branch
git checkout -b {new_branch}

3. Merge that branch to develop (update newest code)
git merge develop ( be aware !)

3. Push that branch back to git
-For the first: git push -u origin {name_of_branch}
-To be continue: git push

## How to run project
1. Install and update Composer
    -> composer install
    -> composer update
    
2. Enable key for the application
    -> save file .env.example as .env
    -> php artisan key:generate
    
3. You can open application by genaral way
    -> http://localhost/web_giasu/public/  // default
    
Or: Run cmd or terminal in web_giasu 
	-> php artisan serve
    
Or: Run cmd or terminal in web_giasu/public
	-> php -S localhost:8000

## How to work with git
1. Before working, please *pull and update the newest code*
git checkout develop
git pull
git checkout feature/{WORKING_BRANCH}
// git merge develop
// before merge, please create pull request to develop, so that we can review code for conflict or something wrong 
2. After working, please *push code to remote branch on git* and *create pull request to develop

