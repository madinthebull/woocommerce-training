# wordpress-savas-base-project
A WP base project for the purposes of learning and easily starting new WordPress projects

## Requirements
1. Docker
  * v18.06 and above

## Local site installation
1. Clone the repository
2. In the terminal, navigate to the project and run `docker-compose up -d`
3. In your browser, navigate to localhost:8000
*note: this takes a few moments to boot up, so if there's nothing there, refresh*

#Wordpress installation
Congrats! And welcome to Wordpress. From here, install WP by following these steps:
1. Select your language (no, sarcasm is not a language)
2. Fill out the WordPress info form and select the 'Install Wordpress' button
3. Login with the credentials you chose

#If you copied this repo and need to add your progress to the git flow:
1. remove 'wp-content' from the .gitignore file
2. add:
wp-content/*
!wp-content/plugins/
!wp-content/themes/

instead
