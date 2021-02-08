# Day 5

## Goals
* Keep working on MakersBnB
* Demo

## Thoughts on Week 5 / Day 5
* We worked on the CSS and did a couple of changes on the views
* Everyones demos were amazing! Some of them had great attributes that I liked and I want to change on ours at some point (request booking, dates, my bookings page, adding image)
* Miranda gave us a workshop on ActiveRecord
* Learned a couple of things from other people's demos :
  * To log in you need to fill out a form and have them as required. To test that using Capybara.current_driver = :selenium_headless
  * To create a logo instantly, go to canva.com
  * Adding images when creating a listing:
    form enctype = 'multipart/form data'
      label for = image_file
      input type = 'file' name =..

    In the app : path = "./public/images/#{filename}" for where the images will be saved
  * I need to have a look on ActiveRecord and understand it a bit more.
