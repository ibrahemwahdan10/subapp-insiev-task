# subapp-insiev-task
The project url: https://drive.google.com/file/d/17wR70iEcbHsFkbuEavyDVHzjvJCOqG1A/view?usp=drive_link

Simple subscription platform in which users can subscribe a website Whenever a new post is published on a particular website, all it's subscribers shall receive an email with the post title and description in it


To use the project:
first you should make database and run this command: php artisan migrate
to make random websites to test run this command : php artisan db:seed --class=WebsitesTableSeeder
to make random posts to test run this command : php artisan db:seed --class=PostsTableSeeder
to make random subscriptions to test run this command : php artisan db:seed --class=SubscriptionsTableSeeder 
to open the app for testing the random data you put in database open this local host url: http://127.0.0.1:8000/api/documentation
And to send mails to emails with new posts of subscriped websites run this command : php artisan app:send-posts-email
