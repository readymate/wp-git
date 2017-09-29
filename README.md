# WordPress Git Starter

Local Wordpress Theme Development with Git

## Table of Contents

- [Pre-Requirements](#pre-requirements)
- [Create Project Folder](#create-project-folder)
- [Wordpress Core Installation](#wordpress-core-installation)
- [Git Setup](#git-setup)
- [Support](#support)
- [Contributing](#contributing)

## Pre-Requirements
- Setup Git [More info here](https://git-scm.com/)
- Install Mysql/MariaDB Database [Mac Instructions here](https://mariadb.com/kb/en/library/installing-mariadb-on-macos-using-homebrew/)
- Install WP-CLI [Instructions here](http://wp-cli.org/)

## Create Project Folder
```sh
mkdir PROJECT_NAME
cd PROJECT_NAME
```


## Wordpress Core Installation

```sh
wp core download

wp core config --dbname=DATABASE_NAME --dbuser=DATABASE_USERNAME --dbpass=DATABASE_PASSWORD

wp core install --url=DOMAIN_NAME --title=SITE_TITLE --admin_user=ADMIN_NAME --admin_password=ADMIN_PASSWORD --admin_email=ADMIN_EMAIL
```

## Git Setup
Create .gitignore

```sh
touch .gitignore
nano .gitignore
```

Add these lines

```
wp-config.php
/wp-content
```

Initialise Git
 
```sh
git init
```

Commit Git

```sh
git add .
git commit -m "First commit"
```

## Support

Please [open an issue](https://github.com/readymate/wp-git/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/readymate/wp-git/compare/).
