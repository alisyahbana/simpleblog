# simpleblog
Simple Blog Application with Laravel

what is application?
- It is simple blogging app.
- users can login/register
- users can write/update blogs
- users can read blogs
- users can comment on blogs

# Installation
download source code and add .env file to blog directory. Config .env file to your database

# Database tables

    users (default + role)
    posts (id, author, title, body, slug, published_on, last_modified, active)
    comments (id, on_post, from_user, body, at_time)

# Quick Installation 
If you want to running quickly, follow these instructions:

  - Clone the repository

  - git clone https://github.com/alisyahbana/simpleblog.git [your project name]

  - Follow the Setup database instructions which includes:
      - Edit the .env.example file to match your database and rename to .env
      - Set up and run the migrations

  - Ensure that the permissions on the storage folder are set correctly. You will get a 500 error otherwise.

  - Ensure that you have set the correct image path for justboil.me to the appropriate folder or just use the default /images and make sure that folder has the correct permissions to upload images (usually owned by the webserver user).
