# Web-Design-Challenge

Web Design Homework - Web Visualization Dashboard (Latitude)
Background
Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.
![image](https://user-images.githubusercontent.com/75258480/118603002-f920c400-b7e5-11eb-87c2-d788a7a28574.png)

Before You Begin


1.Create a new repository for this project called Web-Design-Challenge. Do not add this homework to an existing repository.

2.Clone the new repository to your computer.

3.Inside your local git repository, create a directory for the web challenge. Use a folder name to correspond to the challenge: WebVisualizations.

4.Add your html files to this folder as well as your assets, Resources and visualizations folders.

5.Push the above changes to GitHub or GitLab.

6.Deploy to GitHub pages.

Latitude - Latitude Analysis Dashboard with Attitude
For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting weather data.
In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

Website Requirements
For reference, see the "Screenshots" section below.
The website must consist of 7 pages total, including:

A landing page containing:

An explanation of the project.
Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.


Four visualization pages, each with:

A descriptive title and heading tag.
The plot/visualization itself for the selected comparison.
A paragraph describing the plot and its significance.


A "Comparisons" page that:

Contains all of the visualizations on the same page so we can easily visually compare them.
Uses a Bootstrap grid for the visualizations.

The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.




A "Data" page that:

Displays a responsive table containing the data used in the visualizations.

The table must be a bootstrap table component. Hint

The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here






The website must, at the top of every page, have a navigation menu that:

Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).

Finally, the website must be deployed to GitHub pages.
When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Considerations

You may use the weather data or choose another dataset. Alternatively, you may use the included cities dataset and pull the images from the assets folder.
You must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
Be sure to use a CSS media query for the navigation menu.
Be sure your website works at all window widths/sizes.
Feel free to take some liberty in the visual aspects, but keep the core functionality the same.


Bonuses

Use a different dataset! The requirements above still hold, but make it your own.
Use a Bootstrap theme to customize your website. You may use a tool like Bootswatch. Make it look snazzy, give it some attitude. If using this, be sure you also meet all of the requirements listed above.
Add extra visualizations! The more comparisons the better, right?
Use meaningful glyphicons next to links in the header.
Have visualization navigation on every visualizations page with an active state. See the screenshots below.


Screenshots
This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

Landing page
Large screen:
![image](https://user-images.githubusercontent.com/75258480/118603156-28cfcc00-b7e6-11eb-9c2b-4cdf400066d2.png)

![image](https://user-images.githubusercontent.com/75258480/118603179-2f5e4380-b7e6-11eb-8437-0c3a37d10664.png)

![image](https://user-images.githubusercontent.com/75258480/118603197-338a6100-b7e6-11eb-8544-d939ec6155cb.png)

Comparisons page
Large screen:
![image](https://user-images.githubusercontent.com/75258480/118603234-3d13c900-b7e6-11eb-99d3-fc41bfa4effb.png)

Small screen:
![image](https://user-images.githubusercontent.com/75258480/118603267-46049a80-b7e6-11eb-919f-0b0a98fc5c11.png)

![image](https://user-images.githubusercontent.com/75258480/118603284-4bfa7b80-b7e6-11eb-9fd6-2887cfadaeeb.png)

![image](https://user-images.githubusercontent.com/75258480/118603300-5157c600-b7e6-11eb-90f8-606d15a963be.png)

![image](https://user-images.githubusercontent.com/75258480/118603322-574da700-b7e6-11eb-9079-ec58995b7b2d.png)

Visualization pages
You'll build four of these, one for each visualization. Here's an example of one:
![image](https://user-images.githubusercontent.com/75258480/118603340-5d438800-b7e6-11eb-858d-3d4c9f3fd02a.png)

![image](https://user-images.githubusercontent.com/75258480/118603368-66345980-b7e6-11eb-9dc3-db2907a90d23.png)

![image](https://user-images.githubusercontent.com/75258480/118603383-6af90d80-b7e6-11eb-883b-435f043b6b32.png)

![image](https://user-images.githubusercontent.com/75258480/118603397-6f252b00-b7e6-11eb-9b13-ba95b4961d77.png)

![image](https://user-images.githubusercontent.com/75258480/118603413-74827580-b7e6-11eb-8183-69996824e2c7.png)



