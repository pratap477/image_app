## Image Upload Demo


Application allows users to manage a list of “friends” using a basic Rails scaffold. Each friend will have a Name and Avatar. Paperclip will provide the image upload and resizing functionality. The app will demonstrate how to create different sized thumbnails, display resized images on different screens, and gracefully degrade to display missing avatars “missing.png” for friends without an avatar.

### Install Codebase

Clone the git repository

    $ git remote add origin https://github.com/pratap477/image_app.git
    $ cd image_app
    $ bundle

Create database and run migrations

    $ rake db:create db:migrate

Run the rails server

    $ rails s

### View Application

From a web browser access the site via [localhost:3000](http://localhost:3000)


