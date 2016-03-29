# Giving Day pre-show landing page

For local development:

- Clone this repo to your machine
- Run `bundle install` to install gems
- Then `bundle exec sass --watch main.scss:build/main.css` to compile the css file into the _build_ directory

For deployment:

- Run `bundle exec s3_website push`
- The contents of the _build_ directory will be pushed to the Amazon S3 bucket that hosts the Giving Day landing page.

Note:

- For s3_website to push to S3, you'll need to have the correct Amazon S3 credentials configured as environment variables in `~/.bash_profile`.
