# Learning Rails

Learning Rails with a tutorial from the RailsApps project.


export MAILCHIMP_API_KEY="Your_MailChimp_API_Key"
export MAILCHIMP_LIST_ID="Your_List_ID"
export OWNER_EMAIL="example@example.com"

rails generate layout:install simple --force

Running via Spring preloader in process 40786
      remove  app/assets/stylesheets/application.css
      create  app/assets/stylesheets/application.css.scss
      create  app/assets/stylesheets/simple.css
       force  app/assets/javascripts/application.js
      remove  app/assets/stylesheets/bootstrap_and_overrides.css.scss
      remove  app/assets/stylesheets/foundation_and_overrides.css.scss
      remove  app/assets/stylesheets/1st_load_framework.css.scss
      remove  app/views/layouts/application.html.erb
      create  app/views/layouts/application.html.erb
      create  app/views/layouts/_messages.html.erb
      create  app/views/layouts/_navigation.html.erb
      create  app/views/layouts/_navigation_links.html.erb


rails generate layout:install foundation5 --force
Running via Spring preloader in process 4405
      remove  app/assets/stylesheets/application.css
   identical  app/assets/stylesheets/application.css.scss
      create  app/assets/stylesheets/1st_load_framework.css.scss
       force  app/assets/javascripts/application.js
      remove  app/assets/stylesheets/simple.css
      remove  app/assets/stylesheets/bootstrap_and_overrides.css.scss
      insert  config/application.rb
      remove  app/views/layouts/application.html.erb
      create  app/views/layouts/application.html.erb
       force  app/views/layouts/_messages.html.erb
       force  app/views/layouts/_navigation.html.erb
   identical  app/views/layouts/_navigation_links.html.erb