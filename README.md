# Horiseon-Refactor-Repo

Horiseon is a Social Solutions Company that offers services such as social media marketing, search engine optimization,
and online reputation management. Their website explains the importance and benefits of maintaining your company's social media 
marketing.

Horiseon provided me with the oportunity to refactor their webpage, in order to improve accessability and search engine
optimization. I was even able to clean up some of the CSS properties and HTML elements to ensure long-term stability for
Horiseon's website.

## Cleaning Up the HTML / Functionality

![Screenshot (4)](https://user-images.githubusercontent.com/102200863/162358213-5b786223-d4fb-44aa-9ec2-59f8e8be2174.png)

The screenshot above shows the addition of a consice title to the Horiseon webpage. Any webpage should have a title for optimum usability
and SEO. 

![Screenshot (7)](https://user-images.githubusercontent.com/102200863/162358815-9f32a445-60cf-4301-88a5-a2dc6679702a.png)

The first div element contains the header and the navigation links. The "search-engine-optimization" link was not functioning, but by
adding the id "search-engine-optimization" to line 35 i was able to make the link function properly, and navigate
to the correct part of the webpage (see below)

![Screenshot (9)](https://user-images.githubusercontent.com/102200863/162359223-7cd46dfe-0bc3-4d92-8826-dada6faa1bad.png)

You can see the added id element here. To meet accessibility standards, I also added alt attributes to each of the images on this
section of the webpage, with concise but detailed descriptions. Each div within the div class="content" was also
given a class of "section" instead of individual id's, in order to improve stylesheet efficiency.
 
 ## Consolidating the Stylesheet
 
When reviewing the Horiseon website's CSS stylesheet, I found a lot of repeated selectors and properties. This made the stylesheet difficult to understand, 
and it also makes it easier for errors to occur. 
 
![Screenshot (11)](https://user-images.githubusercontent.com/102200863/162474715-9ed763bd-fba1-4194-86c7-837557938cdc.png)

 In the code above, you can see that I was able to consolidate from nine different selectors among three different id's to three selectors on just one
singular class. This change makes the stylesheet much easier to comprehend. In addition, I moved these three selectors up below the ".content" selector,
to match the flow of the HTML.
 
![Screenshot (12)](https://user-images.githubusercontent.com/102200863/162476037-6a52485f-9ab9-45a8-9cee-a85dc31b5d51.png)

I was able to do the same type of consolidation in the code shown above. The ".benefits" selectors used to be spread out to 10 different selectors 
because they were assigned to four different id's in the HTML. I was able to consolidate to just three selectors, while maintaining appearance and functionality by assigning to one singular class, "benefits". 

### Link to Deployed Application

https://seanxmcdaniel.github.io/Horiseon-Refactor-Repo/

### Link to Repository 

SSH :
git@github.com:seanxmcdaniel/Horiseon-Refactor-Repo.git

HTTPS: 
https://github.com/seanxmcdaniel/Horiseon-Refactor-Repo.git
