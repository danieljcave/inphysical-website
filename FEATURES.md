# **InPhysical Responsive Website Project**

## **Milestone Project 1 for Code Institute Full Stack Software Development.**
### **Author - Daniel Cave**

#### FEATURES.md is connected to **[READ.md](/README.md)** but features have been separated to keep the Readme file clean and a viewable length for users.

## Features

### Main Page & Features
The website is made of 6 pages. 
- Index.html (Home Page)
- Contact Us
- Contact Response
- Push Pull Legs
- Full Body
- Upper Lower

Along all pages they each share features used over the entire website. Navigation Bar, Hero Image and Footer. All of the Workout Plan pages share the same site structure and layout of content. Almost all of the content is located inside a width container of 1140px. This is to centralise all content and have a uniform size over the website. The advice was taken from my mentor **Spencer Barriball**.

Each of the Workout plan pages starts with a title heading of each plan. The information gives a reason to select the plan and the benefits of using the workout plan. The page then displays a guide to structure each day according to the workout plan. Followed by a brief reason for following the workout plan week structure. There is then a statement regarding all the plans having video links to follow and each plan is a guide and the user is free to edit the plan and add or remove workouts.

### **Navigation Bar**
- The Navigation bar is completely responsive on all pages and devices and has a very simplistic yet clean design.
    - In a desktop view (Screen size of 992px wide and above) the main Logo of "InPhysical" is located on the left side of the screen. All pages and information of "Home", "About Us", "Plans" and "Contact Us". These are located on the right-hand side of the screen.
    - In a tablet view (Screen size of 992px to 768px) the main logo is located on the left side of the screen along with the rest of the pages are located on the right-hand side.
    - In mobile view and smaller devices (Screen sizes under 768px) the logo "InPhysical" is located on the left side. With the small screen sizes, the Pages will move closer to the centre as the page gets smaller. Once the screen size reaches 610px Wide. The text then goes below the logo to avoid overlapping.
    - Extra small devices of 350px or below. Spacing is removed for the navigation bar to allow for no overlap and uniform style and design from small screen up to desktop design.
<details><summary>Navigation Bar Image</summary>

![Navigation Bar Image](/assets/readME/features/nav-menu.png)
</details>

### **Hero Image**
- The hero image is an image found on Pexals that is a Male using a plank pose in a large room. This image fits the dark aesthetic with a simplistic look.
    - In the desktop view the hero image is at the centre of the page due to size and design. The hero image is set to a height of 60 rem which is 960px. Rem is used as the main measurement due to it being responsive whereas pixels are not. The Hero image has a gradient cover of black with 75% visibility to the image. This was to darken the image to make the Hero Text Visible.
    - In both Mobile and table view. The image is then set to 50rem with a media query. This is to reduce the overall size and allow the user to see the hero image and not have it zoomed in.
    - The Hero Text is split into a "h2" & "h3" the size of the text is responsive to the page size. As the screen gets smaller the width reduces and accommodates screen size so there is no overlapping text.
<details><summary>Hero Image</summary>

![Hero Image](/assets/readME/features/hero-image.png)
</details>

### **Footer**
- The footer is split into 3 columns, It contains Social Media links, a Copyright text and a newsletter form.
    - The Desktop view contains all 3 columns and has each section split into 33.3% views across the 1140px size. It contains social media links from Instagram, Facebook and Twitter. The centre of the footer contains the copyright text and author/developer name. Lastly, it contains a newsletter submission for an email.
    - In the tablet and mobile view the footer shrinks into 1 column. This is to allow the responsiveness and not squish all too small to make it unreadable. Each is stacked above each other so there is no overlap on each other or the screen.
<details><summary>Footer Image</summary>

![Footer Image](/assets/readME/features/footer.png)
</details>

## **Home Page**
### **About Us**
- The homepage is split into 2 sections, About Us and Plans. This contains information about InPhysical and what the website offers. Then a brief description of which plans are available and to choose from.
    - In the desktop view. The section is split into 2 columns and the "Which plan is right for you" is in a section below the columns which is not affected. The section has a width container of 1140px and 2 columns inside of this.
    - The tablet and mobile view will condense to 1 single column and have all the context stack on top of each other. With the screen size will then add a 10% Padding to either side of the text and shrink it according to the screen size.
<details><summary>About Us Image</summary>

![About Us Image](/assets/readME/features/about-us.png)
</details>

### **Workout Plans**
- This section is split into 3 columns and contains a preview of each plan available on the website.
    - In the Desktop view of the website. There are 3 workout plans, Each contains an Image related to the specific plan. A title and information on the plan. Then a button that takes the user to the chosen plan. Each is split into a column and containers 3 per row.
    - A tablet and mobile view, the column is condensed down to 1 and each preview of the workout plan is stacked above the other.
<details><summary>Workout Plans Image</summary>

![Workout Plans Image](/assets/readME/features/plans.png)
</details>

## Workout Plan Pages
Each workout plan follows the same format and structure for all pages. This is to allow the user to view each page and not have any confusion about the information or location of the details of the plan.

### Information
- Each page starts with the same structure. The title of the page is followed by information and a descript of what each plan contains and the best way to apply it to the user. Bellow that is a weekly plan that shows the days of the week and which days are best to train on to allow for enough rest.
<details><summary>Workout Information Image</summary>

![Workout Information Image](/assets/readME/features/workout-info.png)
</details>

### Table Plan
- The plans are created in a table. The table is split into Exercises, Sets, Reps and Rest Time. The exercise row is the header and is given a 40% width. This is for the name of the exercise below. Then remaining 3 columns are given a 20% width. This is to set the tables to be responsive and shrink as the device size decreases.
<details><summary>Workout Table Image</summary>

![Workout Table Image](/assets/readME/features/workout-info.png)
</details>

## Contact Us
- The Contact Us Page contains the navigation bar, a contact form and the footer.
    - The desktop view shows the contact form at the centre of the page. The form is designed to fit 60% of the page. The form contains information requests; "First Name", "Last Name", "Email Address" and "Contact Number". The form then uses radio inputs to have the user select their exercise experience and which plan they have chosen or plan to choose. Last is a large text box for the user to enter any questions that they have and then submit them to our team. Each field is required to be filled out before submission.
    - In tablet view, the contact form is set to have a width of 75% of the screen width. This is to allow the user to still see the form and have it look as if it was on a desktop.
    - The mobile view form is set as a width of 90%. The view width has as much screen usage while still having a small border around the form so does not take the entirety of the screen.
<details><summary>Contact Form Image</summary>

![Contact Response Image](/assets/readME/features/contact-form.png)
</details>

### Contact Response Page
- The contact response page is shown to the user once they have submitted a contact request form. The text thanks the user for submitting a question and then provides a way for the user to come page to the page and continue to use the website. 
<details><summary>Contact Response Image</summary>

![Contact Response Image](/assets/readME/features/response.png)
</details>