# Instructions for Alison

<details>
  <summary>Edit Timetable</summary>

  1. Open _includes/timetable.html
  2. Find the row you want to change  
  3. Each row has 5 sections (Day, Time, Where, Price and Details)  
    1. Change these accordingly  
    2. You can remove whole sections and you can copy an existing section and paste to create a new row in the table.
</details>

<details>
  <summary>Edit Gallery</summary>

  1. Open img/gallery/
  2. Add images here to display inside the gallery
  3. Change the order of the images by renaming them, they are automatically ordered in alphabetical order.

</details>

<details>
  <summary>Edit About Me</summary>

  1. Open _includes/about.html
  2. between the <p> and </p> is your 'About Me' paragraph. New lines don't work as normal here so '<br/>' makes a new line.

</details>

<details>
  <summary>Edit Testimonials</summary>

  1. Open _testimonials/
  2. Add or remove files here using the first name of the individual followed by '.md'
  3. Add the following at the top of the file,

    > ---
    > layout: default
    > modal-id: 3
    > date: 2014-07-15
    > img: name.jpeg
    > ---

  4. Change name.jpeg to the image filename (modal-id and date are required but not shown so these can stay the same)
  5. layout: default must not be changed and the three dashes must also be there at the beginning and end of this section.
  6. Under the dashes you can paste the testimonial inside some ""
  7. Use existing testimonials as a guide to ensure the format is correct.
  8. Finally add the image to img/testimonials/

</details>
