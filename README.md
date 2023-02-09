# Web Superhero - JavaScript!
## Case Study: Belly-Button-Challenge

![bigstock-Real-Java-Script-Code-Developi-217215433](https://user-images.githubusercontent.com/115101031/217602372-a089525f-6aa0-4611-85ce-e0ee001a287f.jpg)

JavaScript is a programming language used by web developers to create more dynamic interactions. Used in combination with HTML and CSS, JavaScript provides superior power tool for web design.  

The JavaScript programming language controls multimedia within web pages and allows them to become interactive. JavaScript empowers a developer to do many things like adding animation to images or updating content automatically on a page. 

JavaScript is what allows you to interact with the vast majority of web pages that you visit. Whether it’s filling out forms, scrolling through maps, or registering for an event, it’s most likely that JavaScript programming is what’s allowing you to do it. 

For example, if you’re on a web page that has a JavaScript-powered shopping cart, you’ll notice that it immediately shows the total cost of what you want to buy including taxes, shipping, etc. Javascript is then used when determining whether the credit card details you entered were valid before transferring those details across the net to the bank for processing. 

In our Belly Button case study, JavaScript provides a powerful web-based visualization tool.

![giphy](https://user-images.githubusercontent.com/115101031/217605273-bdbe38cb-2671-4646-bd8f-f1ae9f718eba.gif)

Sources:
* https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript
* https://codeinstitute.net/global/blog/what-is-javascript-and-why-should-i-learn-it/

#
## The Case Study

#### Belly Button Biodiversity - The coolest study of biodiversity on the human body on the planet!
The belly button is one of the habitats closest to us, and yet it remains relatively unexplored. In January 2011, we launched Belly Button Biodiversity to investigate the microbes inhabiting our navels and the factors that might influence the microscopic life calling this protected, moist patch of skin home. In addition to inspiring scientific curiosity, Belly Button Biodiversity inspired conversations about the beneficial roles microbes play in our daily lives.

The dataset catalogs the microbes that colonize human navels, and reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Source: http://robdunnlab.com/projects/belly-button-biodiversity/

#### The Scope of Our Challenge
Using Javascript, HTML, and CSS, we will create an interactive web page that explores the amazing diversity of cultured bacteria from collected from a wide range of participants’ belly buttons!

We will undertake the following steps:
* Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
* Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
* Create a bubble chart that displays each sample.
* Display the sample metadata, i.e., an individual's demographic information.
* Display each key-value pair from the metadata JSON object somewhere on the page.
* Update all the plots when a new sample is selected.

#### Methodology
Unlike prior challenges, JavaScript definitely takes some getting used to!  Given what it does, assembling the output is complex and complicated.  The language and syntax, though at time familiar and logical, was harder to grasp than prior tools in the curriculum.  The biggest challenges in navigating the project were (to name just a few!):
* The syntax can be confusing...Bracket, [content], bracket, [content], comma, [content], semi-colon, semi-colon.  Havng spent over 12+ hours just on building a stronger foundation for the language, it is clear that this is just the tip of the iceberg if I really want to feel confident about working with JS!
* The interdependency between JavaScript, HTML, and CSS.  Rather than working in one document, you are working across multiple and interdependent documents! 
* It is highly sensitive to the order of code.
* The ability to introduce HTML elements right into the JS code, while not being overwhelmed with ensuring that there is seemless "communication" between other HTML elements outside JS.
* The functionality of using the web console to track and alter output.
* The need to understand global versus local constraints and operators.
* The high degree of customization that is possible...trying to space out my plots in a pleasing way was a hours-long affair given the variety and versatility of the options available to configure elements on the page!!!

...it is BIND BLOWING stuff!!!
![utya-duck](https://user-images.githubusercontent.com/115101031/217619472-61c7db18-301d-4271-8cf5-5a01e1886af2.gif)

#### Results

This project constructs a dashboard to showcase data visualization for the belly button biodiversity dataset. This includes:
* Data visualizations that are interactive
* Manipulate and transform data
* Interactive features such as dropdowns and retrieval of data from external sources
* Deploy an interactive webpage to GitHub Pages (https://pages.github.com/)

**[Click HERE to view the live project!](https://michellecar.github.io/)
**
<img width="717" alt="Screenshot 2023-02-09 at 12 12 29 AM" src="https://user-images.githubusercontent.com/115101031/217723834-230244d5-8bc1-4340-b422-89fd24103c76.png">

Users visiting the page can select an ID number from the dropdown menu to populate the demographic information and display visualizations:
* Demographic Information - When a volunteer ID is chosen from the dropdown menu, that person's demographic information, such as location, sex, and age, will be displayed

* Top 10 Bacterial Species (OTUs) - When a volunteer ID is selected from the dropdown menu, that person's top 10 bacterial species (OTUs) are displayed in a horizontal bar chart:
<img width="505" alt="bar chart" src="https://user-images.githubusercontent.com/115101031/217724809-e809b8f5-b5f9-4c12-953f-5c8e9309e2f6.png">

* Belly Button Washing Frequency - When a volunteer ID is selected from the dropdown menu, that person's weekly washing frequency is displayed as a measure from 0-10 in a gauge chart:
<img width="390" alt="Screenshot 2023-02-09 at 12 20 30 AM" src="https://user-images.githubusercontent.com/115101031/217724999-ed55cdb7-f398-4ef0-bcca-70ed0b79e4ce.png">

* Bacteria Cultures Per Sample - When a volunteer ID is selected from the dropdown menu, that person's bacteria culture per sample (otu_ids as x-axis & sample_values as y-axis) is displayed as a bubble chart:
<img width="1142" alt="bubble chart" src="https://user-images.githubusercontent.com/115101031/217725318-a24d9807-b008-480c-ad6b-0df3642fbfef.png">

* As a new ID number is selected, the page is updated.
