# Anna Raman – Quarantined Community
Milestone Project 1: User-Centric Frontend Development – Code Institute

<p>This is my website on quarantining, which I have created with the aim of providing some support and resources for all members of the public currently enduring the lockdown.</p>

The website presents 3 areas of focus; the mind, body, what we can do to help. There is a message-board page which hopes to invite users to discuss their personal experiences/recommendations. 
There is a frequently asked questions page which covers the most asked questions that members of the public have regarding the coronavirus and the quarantine. Finally, there is a contact page containing a contact form.


 
### UX
My focus with the design was to facilitate the users search for what they are looking for; hence, the simplistic and minimalist layout of the website. 
I chose a neutral colour scheme to maintain the acknowledgement of the serious nature of the lockdown, whilst making scrolling through the website as aesthetically pleasing to as many people as possible.

User Stories
1. As a member of the public enduring the quarantine i want to seek some advice so i know what i should be doing to keep safe
2. As a member of the public enduring the quarantine i want to find out about what other people are doing during the lockdown so that i can find a new hobby
3. As a member of the public enduring the quarantine i want to find some details to enable me to volunteer and help those in need

_Wireframes_
 Home: https://wireframe.cc/pro/pp/80b51b4f2341710 
 Message board: https://wireframe.cc/pro/pp/959ceb790341713
 FAQs: https://wireframe.cc/pro/pp/c1d7d8770341714
 Contact: https://wireframe.cc/pro/pp/db4f831aa341715

### Features

* The first section of the home page provides links to each section of the page, to direct the user to exactly what they are looking for. 
* The bootstrap breadcrumbs feature eases navigation by showing the user at which page they are currently located.
* The messageboard page provides a (currently static) feature which alows the user to find the answer to their exact question, had the answer not been provided on the website.
* The accordion on the FAQ page allows the user to find an answer to their question by simple on-click dropdown, whilst hiding the rest of the information that may not be of interest to them.
* The contact page provides a form for the user to fill it if they wish to get in contact. It also provides quick links to some useful websites that the user may want to seek more information from. 


#### Features Left to Implement

Going forward, I would like to add JavaScript to many aspects of my website, once I have developed the skill to do so. 
For example:
* I would like to make the message board interactive to encourage user-interaction.
* I would also use JavaScript to implement a point-scoring function on the comments, whereby users have the ability to upvote or downvote a comment so that the most relevant comments appear first in the stream.
* Finally, I would use and API to add a ‘lockdown update’ page where there would be a live stream of updates regarding the lockdown, corona cases, and recommended courses of action from a government body or news broadcasting source.



### Technologies

1.	HTML5
2.	CSS
3.	Bootstrap (4.4.1)
4.  jQuery



### Testing

The testing process intended to ensure that website was fulfilling the needs of the user. 
After running through the entire website checking links, anchors, the contactn form, website compatibility and responsiveness, it is deducible that it functions as intended.
The user stories mentinoned in the UX section have been tested and proven success. The home page provides the relevant information for the user to gain an understanding of how best to behave 
in order to keep safe in the 'How can I help' section, and, in the FAQ. The messageobard page provides a platform of communication between users, allowing them to share stories and experiences,
satisfying user story 2.  The contact page provides a contact details for those users who are seeking information regarding volunteering opportunities, with an clickable features for the telephone numbers and email addresses, for ease.

1. Contact form
  i. Go to the 'Contact' page
  ii. Leave a mandatory field empty, and you are promted to fill in the field
  iii. Enter text in the 'email' box that is not a valid email address, you will be promted to input your correct address
  iiii. Fill in all mandatory fields with an existing email address and the form submits.

All links provided on the webite have been coded with 'target="_blank"' so that that the user is able to maintain their position on the website, whilst exploring the link's destination in a new tab. 
These have been tested and proven to work efficiently. The anchor tags surrounding the 'mind', 'body' and 'how can i help section' on the homepage, are fully cuntioning and allow the user to skip to their desired section.
The accordion on the FAQ page functions as desired; once the user find the question they are looking for, the answer is presented via an on-click drop-down button.

With thanks to Bootstrap's framework, the website has been tested and is successfully responsive to different screen sizes, and the elements on the page wrap accordingly and appropriatly.
The tested mobbile devices were Iphone model 5 through to Iphone 8, Galaxy S5, pixel and pixel XL. A slight issue occurs on tablet-sized screens such as the ipad, as the videos in the 'body' section and 'how can I help' section are no-longer in perfect alignment, rather they one falls slightly lower than the other.
Further, compatibility was achieved through running the website on Chrome, Firefox, Safari and Internet Explorer.


### Deployment

This project has been deployed to Gitpages through enabling sharing and then deploment on Github **change

### Credits
#### Content

The content in the answers on the FAQ page were copied from the following sources:
* <a href="www.who.int/emergencies/diseases/novel-coronavirus-2019/question-and-answers-hub/q-a-detail/q-a-coronaviruses" >The World Health Organisation</a>
* <a href="www.bbc.co.uk/news/health-52183295">BBC</a>
* <a href="www.mind.org.uk/information-support/coronavirus/coronavirus-and-your-wellbeing/" >Mind</a>
* <a href="www.nhs.uk/conditions/coronavirus-covid-19/what-to-do-if-you-or-someone-you-live-with-has-coronavirus-symptoms/staying-at-home-if-you-or-someone-you-live-with-has-coronavirus-symptoms/">NHS</a>
* <a href="www.gov.uk/government/publications/coronavirus-outbreak-faqs-what-you-can-and-cant-do/coronavirus-outbreak-faqs-what-you-can-and-cant-do">Gov.uk</a>



#### Media
The photo used as a background image was obtained from <a href="www.pexels.com/">Pexels</a> who provide a library of stock images. 

#### Acknowledgements
I took inspiration from <a>Bootstrapious</a> when producing the layout of my contact form. I styled and modified the form so it was fitting with my website.

I took inspiration from <a>Bootstrapious</a> when producing the layout of my FAQ accordion. I styled and modified the form so it was fitting with my website.
