# **Dev Interview Process Notes**

This document contains notes I gathered to prepare myself for various interviews and calls I had during my personal dev interview processes. Since it&#39;s been so long, I don&#39;t have all the links to refer to the resources, but essentially the below is an accumulation of information from my research, and bits of advice from my own experience.

![](RackMultipart20210302-4-z0qnxs_html_a0243959dbc46b8f.png)

Table of contents
=================

<!--ts-->
   * [Types of Interviews and Their Purpose](#Types-of-Interviews-and-Their-Purpose)
   * [System Design](#system-design)
   * [PM/Design led interviews](#PM-or-Design-led-interviews)
   * [Questions to ask other Devs](#Questions-to-ask-other-Devs)
   * [Questions to ask Founders](#Questions-to-ask-Founders)
   * [Salary Negotiation Script](#Salary-Negotiation-Script)
   * [Salary Stock Options](#Salary-Stock-Options)


# Types of Interviews and Their Purpose:

What interviewers are looking for:

#### Code interview

- how is this person&#39;s code, is it readable and easy to follow, do they include tests and cover all scenarios, can they talk through their implementation, afterwards can they find things they can refactor and discuss what they would&#39;ve done differently. You&#39;ll have a take home or code interview building out assessments and questionnaires - which is neat because that&#39;s the meat of our actual application, so you&#39;ll get a sense of what we actually work on.

#### System design interview

- how does this person approach architecture, do they think of the impact across systems, do they do approach it iteratively. You&#39;ll discuss how you go about designing and building something, you may be asked to discuss how you&#39;d build twitter, instagram, etc. Have a good example of a personal project, or something you owned in designing and building so you can have a good conversation about it. If asked to design something, treat it like you would a real work ticket, working with the interviewer as you would a stakeholder - asking for feedback and input. Take into account what they say in your decision process and implementation - usually there are hints to what they want you to implement or conversations they want to have with you.

#### Debugging interview

- how does this person cope when things go wrong, can they talk through a production incident, can they give thoughtful answers given hindsight. You&#39;ll discuss how you handle production incidents, logging and system tools you use, your process for debugging, how you think and go about prioritizing bugs.

#### Product interview &amp; UX Interview

- would this person be a good partner to product/design, would they think through solutions when thinking through UX and flows. Some things you may discuss are how you work with product people (or design people), examples of a good working relationship, bad relationship, what you learned from them, what could&#39;ve changed for the better, how you go about things changing mid way, how you go about planning projects, and discussing a product you&#39;re proud of, and how you worked with pms to do that.

#### Measuring a candidate

Typically a hiring decision is made by looking at these aspects of a candidate:

- Code competence, code that&#39;s easy to understand, maintainable, and extensible
- Ability to explain concepts, code implementation, preferred tools, and alternatives
- Good tests, covering all cases + exceptions
- Comfortability managing production incidents, debugging, some devops knowledge
- Ability to prioritize well, guide/lead a team, and work well with product + design
- Ability to work with stakeholders when pm&#39;s aren&#39;t available or when an engineer has to take lead
- Values high collaboration
- Is professional, kind, level headed, competent
- Has good listening skills, is receptive to feedback (some interviewees have gotten stressed and focused on getting the problem finished, or focused on their own priorities like optimizing too early - and stop listening and continue down an unnecessary path)
- &amp; whether or not this person will be happy working in a scrappy company and be pleasant to work with

## Suggestions:

- Research and read about the interview subject if you&#39;re unfamiliar. Don&#39;t hesitate to ask the hiring manager what they can tell you about the interviews objective. This shows you're proactive, and will give you an idea of what to prepare for.
- Join meetups! There are so many meetups where new and old devs come together to learn and teach each other. I gained many valuable experiences and I know many others who have gotten a lot from attending meetups. The camaraderie is also extremely encouraging for those in the beginning of their career/education dealing with the steep learning curve that coding has. There are also women only, BIPOC, LGBTQ, and many other diverse tech groups available.
- There are also slack groups, perhaps more convenient than meetups. Here are a few to check out:
  - ![](RackMultipart20210302-4-z0qnxs_html_b35869175f76e64c.png)
  - Both slack groups and meetups are great for networking, finding jobs, internships, new career opportunities, getting help on homework or general coding questions - they are both great resources to utilize for whatever it is you may need help with.
- There are apps that organize practice tech interviews conducted by experienced devs like [https://www.skilledinc.com/](https://www.skilledinc.com/), [https://interviewing.io/](https://interviewing.io/). A really neat feature is the [recordings of interviews](https://interviewing.io/recordings) available to view, this can be extremely helpful to familiarize yourself with the concept of pairing and communication, and general pairing flow and manners :)
- There are tutors available, both cheap and expensive, should you ever need help with a last minute interview question, study session, or just general, personal support. [https://www.wyzant.com/](https://www.wyzant.com/) (cheaper end), [https://www.codementor.io/](https://www.codementor.io/) (more expensive)
- Other random useful tools and docs:
  - Interview[review doc for beg-mid ruby/js](https://docs.google.com/document/d/1548nfhEOGehugTIhsMq-8m6ZTW9YeiRTWgWin2ggIMg/edit?usp=sharing)
  - [https://www.w3schools.com/sql/sql\_top.asp](https://www.w3schools.com/sql/sql_top.asp)
  - [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators)
  - [https://guides.rubyonrails.org/](https://guides.rubyonrails.org/)
  - [http://testing-for-beginners.rubymonstas.org/rspec/matchers.html](http://testing-for-beginners.rubymonstas.org/rspec/matchers.html)
  - [https://gist.github.com/kyletcarlson/6234923](https://gist.github.com/kyletcarlson/6234923)
  - [https://www.db-fiddle.com/](https://www.db-fiddle.com/)
  - [https://www.schneems.com/2016/01/25/ruby-debugging-magic-cheat-sheet.html](https://www.schneems.com/2016/01/25/ruby-debugging-magic-cheat-sheet.html)

#

## Ideal Engineer Qualities

During my interview process, I asked various devs, managers, pms, etc. how they would describe the best qualities and strengths of ideal engineers they&#39;ve worked with, the notes are listed below. It can be helpful to find examples of these traits for yourself to bring up during the interview process:

- easy to work with
  - always eager to learn and participate, took feedback with a smile.
  - good attitude who is passionate about their craft
- displaying a capacity to execute great work
- thorough as well a big picture thinker
- strived to propose new solutions to any design problems they, and the team, faced
- can adeptly meet the challenges, profoundly dedicated and responsible person

- approaches every problem from the viewpoint of our member base

- adaptable, focused, skilled, and hardworking

# System Design

Designing App Q&#39;s and Steps: The below questions can be helpful for mock interviews regarding app design (where the objective is to design the system of an application with engineers). These questions can also be helpful to bring up during interviews conducted by a PM (product manager) or product designer, or for those beginning freelance work for the first time and interviewing the client.

![](RackMultipart20210302-4-z0qnxs_html_a0243959dbc46b8f.png)

Stakeholder.

- Identify who the stakeholder is and what their interests are. (The person conducting the interview might act as the stakeholder, or may speak for them.)
  - Essentially, it&#39;s a good idea to show that you&#39;re taking into account the stakeholders interests and integrating their interests into your solutions. If you&#39;re being given a design interview as part of your process, most likely the concept of stakeholders and their needs being met is an important consideration for the hiring process.

## Questions to ask:

- Tell me about our stakeholders?

- Why do we want this app, what are we looking to accomplish with the app?
  - What is the overall objective?
  - What do you want your site to accomplish?
    - What are the primary and secondary goals to be accomplished?

- What will visitors accomplish on the app? What do you want your customers to do?

- What should the visitors expect to experience on the website
  - What is the user experience -\&gt; map out user flow:

- What is the most important information your site must relay to the user, especially on the home page?
- How many pages will the finished website be
- How much information do we want on our website?

- What types of actions do you want your visitors to take on your website?

- Who will be using the app - who is our target audience?

  - What distinguishes our target audience from others?
    - (Teens and young people may require a more advanced interface, while older audiences who may not be as technically inclined may require an easy and intuitive interface)

- What are the pains of the audience? Problems and fears complaints?

- What do current competitors&#39; websites have that you wish to have?

- What about those websites would you like to be incorporated into your website?
- What features would we rather sidestep and leave out?

## Steps to start the work:

1. Analysis - Wireframing and mockups (wireframe software)

- What will the end result look like
- What components are needed
  - Ie: navbar, footer
  - What links are included
  - Where is the main form going
- Draw each user flow
  - With necessary components and features for each action &amp; page

1. Research
  1. Research other projects that are similar
    1. Get an idea of what code will look like
    2. Sample projects
    3. Search in GitHub
  2. Set up git repo with branches
2. Html/css &amp; Model/Database
  1. Build out forms with mock data / mock routes
    1. Create database after building out each flow
    2. Finalize and run migrations
    3. Implement real routes and data creation logic
    4. Styling
  2. Create models / database
    1. Build html forms
    2. Check flow, make sure all is accounted for
    3. Styling
3. Testing

  1. Thorough testing
    1. All types testing (unit tests, etc.)
    2. Test on multiple platforms/os/ browsers
  2. End to end testing of project

## Free lance work questions:

- What is the project timeline/launch date?
  - How will progress be monitored or evaluated
- What are your top 3 frustrations with your current website?

- What are the 3 things that are most important in the design of your new website.
- Which functions or features are necessary to include:

- Which would be considered extra / nice to haves?
- What do we want the user experience / user flow to be?
- Is there anything that may considered a norm that you dislike and would rather not include in this project ( ie navbars, design patterns, features)
- Do you require your site to be mobile friendly (responsive design)?
- Is there anything I am missing?
- Do you have the content for the website or will content creation be a part of the scope of work?
- Is there an existing style guide or existing work to work off of?

- If not, what is the preferred style - simple, minimalist, classic
- Do you have any other materials that the site needs to match with in some way (brochures, press materials, etc.)?

Misc. Features to get familiar with:

- shopping cart system for e-commerce; online chat features; Profiles; blog; event calendar; rental system; multiple levels of access;

Other questions, taken from [https://www.thebrilliantassistant.com/questions-for-new-clients/](https://www.thebrilliantassistant.com/questions-for-new-clients/)

1. Describe your target audience.
2. What is the purpose of the website?
3. Describe the style of the website you want.
4. Do you have specific company colors that need to be used?
5. Can you provide the Pantone numbers for your company colors?
6. Do you have any other materials that the site needs to match with in some way (brochures, press materials, etc.)?
7. What are your top 3 frustrations with your current website?
8. What do your current competitors&#39; websites have that you wish to have?
9. Are there any websites with designs that you like? What about those websites would you like to be incorporated into your website?
  1. What types of things do you see on other websites that you really like?
  2. What types of things do you see on other websites that you really hate?
10. Name the 3 things that are most important in the design of your new website.
11. Name the 3 things that are least important in the design of your new website.

Scope &amp; Specs

1. Does your current web host meet all your new website&#39;s needs (space, bandwidth, databases, etc.)?
2. Do you plan on or need to move to a new host provider?
3. Do you need help finding the right web host?
4. Do you already have a URL you plan to use?
5. If not, do you need help selecting and registering a good URL?
6. Do you have a logo you plan to use or will one need to be created?
7. If you have one, can you provide the original artwork files?
8. Will you need a favicon created?
9. Do you have a tagline you wish to use or do you need help creating one for your site?
10. Do you have a completed site architecture for the new website or will this be part of the scope of work?
11. How many pages will the finished website be (estimated)?
12. Do you have any page wireframes ready or will those need to be produced as part of the scope of work?
13. Do you have the content for the website or will content creation be a part of the scope of work?
14. How many pages of content will need to be developed?
15. Will there be any cross promotion of content within the site?
16. Please provide details on content cross promotion.
17. Will we be importing and formatting your content, or do you plan to do this?
18. Do you or your team need training for making website updates, content publishing guidelines, etc.?
19. What types of actions do you want your visitors to take on your website?
20. Do you have any specific photos you plan to use?
21. Do you have full rights to those files?
22. Can you provide hi-res files to us?
23. Will we need to find and/or create any images for the website?
24. Will video or audio be a part of the new website?
25. Can you provide us the proper files or is creation of this content part of the scope of work?
26. How many videos or audio files will be added and/or created?
27. Will any customizations need to be made such as optimizing for search, adding content overlays, customized wrappers, etc?
28. Do you require online chat features?
29. Do you have any other media or PDF documents that need to be incorporated, or will any need to be created?
30. Will these need to be optimized for search?
31. Will your visitors require any special needs (i.e., screen reader ready, larger fonts)?
32. Do you require your site to be mobile friendly (responsive design)?
33. Do you have any specific mobile requirements?
34. Do you need multi-language support?
35. Will you need a shopping cart system for e-commerce?
36. Do you have a system you already use?
37. Are you in need of an upgrade?
38. Do you need a content management system?
39. Do you have a preference for which CMS to use? (i.e., WordPress, Joomla, Drupal, Concrete 5, Magento, etc.)
40. If not, do you need help selecting the best CMS for your needs?
41. Will you need multiple levels of access?
42. Do you need to be able to manage content publishing approval processes?
43. Does your site need a blog or a forum?
44. Will users need to log in to your site for any reason?
45. If so, why?
46. Do you need any password protected areas?
47. What kind of content will be put behind password protected areas?
48. How many web forms does your new site need?
49. What is the purpose of each?
50. How do you want the submitted info handled? (email, database, etc.)
51. Do you need any social sharing features built in (tweet, like, +1, share, etc.)?
52. Will there be any third-party applications that will need to be integrated?
53. What are they?
54. Will you need an events calendar feature?
55. Do you have any subscription services?
56. Do you use a third party for any part of subscription content delivery and/or payment?
57. Do you require printer friendly options?
58. Do you wish to employ any &quot;content-on-demand&quot; features (i.e., hidden elements that are made visible with certain actions)?
59. Do you want a fixed-width or fluid-width design?
60. What information must be on the home page?
61. What information must always be visible?
62. What features, sections or information do you want emphasized on the site?
63. How would you like that to be featured?
64. Will different sections of your site require different designs, layouts or coloring?
65. Do you have any flash elements you want included?
66. Will those be provided or do they need to be created?
67. Do you need an internal site search feature?
68. Do you want contact phone numbers prominently displayed?
69. Do you require a database?
70. What specific functionality will it need?
71. Do you have any other specifications or need specific functionality that has not been addressed?
72. What is your time frame for total project completion?

# PM or Design led interviews

## Interview session with a PM

Below are [example questions](https://www.subtraction.com/2013/05/16/when-designers-interview-engineers/) asked by a PM to an engineer candidate. One goal for the PM in this interview is to ascertain whether they would be able to work well with you. The questions below may help you get a sense of what a PM/Designer is looking for during your interview with one:

1. (I) Ask about what they&#39;re (the engineer) working on right now, and why it&#39;s important to them.
  1. Mission is important, helping users, and they measure their work against the benefits that they are able to provide to users
2. Ask about who uses something that they&#39;ve built, and why it&#39;s useful to those specific people.
3. I&#39;ve found that the easiest place to start is to inquire about the candidate&#39;s past experiences working with other designers.
  1. What was the arrangement like?
  2. Who did what?
  3. What bumps in the road did they hit?
  4. What were the easiest and hardest things about working with those designers?
  5. What did they learn about how design intersects with their job?
4. Did the engineering candidate enjoy working with designers?
5. There&#39;s also the more neutral ground of asking the candidate to talk about any products, services, features, user interface details etc. that they&#39;re fond of. The way they describe that product or feature, the details they call out, and the reasons they give for being sympathetic to it — all these things talk directly to what they value in their own work
6. Look for examples of times when they&#39;ve compromised on scope in order to deliver something quickly.
  1. Though it can be tough to build something you know is imperfect, great engineers are willing to make the compromises that deliver value to users faster. Agile engineers are able to deliver useful product iteration-by-iteration, rather than all at once. Agile engineers can find creative and innovative solutions to problems they are posed, and they are passionate about.
7. Ask about times when they&#39;ve helped to find a creative solution to an important problem.
  1. Great engineers crave the opportunity to find a solution to a problem that nobody else has thought of.
8. Ask for examples of times they worked with their team to solve a tough problem.
  1. Engineers that add to a team culture are ones that can work as part of a team. Great candidates are ones that understand that a high-performing team is greater than the sum of its members.
  2. Instead, they celebrate wins and contemplate losses together, constantly working on ways to improve their process and their dynamic
9. Ask them what their previous manager would say is their greatest weakness.
  1. Engineers that add to a team culture know when they&#39;ve made mistakes, and they work to alleviate them.
10. What do they expect at hand-off?
  1. Some engineers like designs to be redlined before implementing. Others like to be more ad-hoc and sit down with designers to get the design pixel-perfect.
11. What were their past experiences working with designers like?
12. What energizes them about their work?
13. How do they like to communicate?
  1. An engineer may ask you about previous experiences where you&#39;ve disagreed with an engineer&#39;s point of view or had to convince your engineering team to build something.
  2. Communication: They would want to understand how you generally communicate with engineers in these circumstances.
14. Engineer understands anything about typography, color, images, branding systems and logos, but I say why not? It&#39;s perfectly fair game to ask if an engineer understands why a given design solution works, why some typography looks better than others, or what makes a good design good, and a bad design bad. An engineer who understands these things is a tremendous asset in shipping great products, and designers are best equipped to assess that
15. What criteria do you generally use or weigh more heavily?

  1. Prioritization: An engineer might ask you how you think about prioritization. The main thing an engineer might be looking for here is understanding how you think about trade-offs .

Resources:

- [https://www.subtraction.com/2013/05/16/when-designers-interview-engineers/](https://www.subtraction.com/2013/05/16/when-designers-interview-engineers/)
- [https://laptrinhx.com/this-is-how-great-product-managers-interview-engineers-354624660/](https://laptrinhx.com/this-is-how-great-product-managers-interview-engineers-354624660/)
- [https://www.subtraction.com/2013/05/16/when-designers-interview-engineers/](https://www.subtraction.com/2013/05/16/when-designers-interview-engineers/)

## Questions to ask PMs/Designers:

Ask about the Product, Roadmap, and Industry with the goal being to learn about the product vision. You can help illuminate how set (or open) the high-level roadmap is, give insight into a company&#39;s unique take, and illuminate the clarity of thought (or lack thereof) in a product strategy:

Example questions:

- What are the improvements the product needs in the next five years?
- What is the most contentious feature the product team currently debates building? What are the arguments for and against it?
- What&#39;s the biggest risk to this product succeeding? What&#39;s being done to mitigate that?
- Why is now the right time to be building this product in this industry?
- engineer will probably want to hear about previous experiences where you&#39;ve worked on a project with other engineers so they can get a sense of how you work

Questions regarding the company product culture:

- How often does the whole team brainstorm and ideate together?
  - This is really asking, will there be opportunities to participate in systems design, attend other meetings that may be of interest to you, organized knowledge transfers, etc - you don&#39;t want to be siloed and told what to do every day with little room for creativity .
- How would you define the organization&#39;s product philosophy?

- extremely quantitative and do detailed analysis and experimentation before launching anything
- others rely on product intuition and belief in what users want (Apple is famously intuition driven)

- What does the lifecycle of a regular feature look like? can you tell me about the process to launch X?
  - The engineer may want to hear about your entire process of launching a feature from start to finish (i.e. do you like to do daily stand-up meetings, how do you work with engineers after you finish a spec, do you involve eng. throughout the entire product planning process, how do you manage QA&#39;ing a feature branch, etc...)
- How closely do the engineers work with you?
  - Do you typically brainstorm to align and ideate together? Are they part of the design process at any point?
- How do they like to communicate? An engineer may ask you about previous experiences where you&#39;ve disagreed with an engineer&#39;s point of view or had to convince your engineering team to build something.
  - Communication: They would want to understand how you generally communicate with engineers in these circumstances.
- What criteria do you generally use or weigh more heavily when making decisions?

  1. Prioritization: how do you think about prioritization? The main thing an engineer might be looking for here is understanding how you think about trade-offs .

- What do they expect at hand-off?
- What were their past experiences working with engineers that went well, what worked well and why?
- Tell me about a project when you felt stuck or frustrated with (engineering/design)?
  - What was difficult? Why did it end up that way?
- What energizes them about their work?

Resources:

- [https://www.mindtheproduct.com/what-questions-should-you-ask-your-product-manager-interviewers/](https://www.mindtheproduct.com/what-questions-should-you-ask-your-product-manager-interviewers/)

## Example answers to questions they may ask:

Describe your ideal PM?

- Someone who listens

- Someone who is flexible and open to brainstorm
- Someone who advocates for them
- Fosters a good relationship and dialogue between the designers and engineer, implementing either a system or a culture that allows for collaboration to flow easily
- A pm who empowers engineers on their team to build things that matter by setting clear and comprehensive goals, strategy, and initiatives.
- PMs who prioritize potential features by how well they help their company achieve its goals.

Describe your ideal Designer?

- Translate graphics into working code
- Consistency throughout the app - Consistent design, well thought out, which makes for consistent code - if each page has different designs, then you need to duplicate code and add custom design for each additional page

How do you pair with a designer/pm?

- Bug hunt together. You can be precise about the implementation feedback you give and work through any design details together.
  - These informal QA sessions are really valuable. Designers catch bugs core to the user experience and engineers are able to fix many of the bugs on the spot.See it as a process of working with a partner on solutions to the same problem, one engineer based and the other design based

- sit down with them and start a conversation, sketch out ideas on paper or on a white board.
- Get the design process out of your head and out in the open where they can see it, it can be discussed and poked at - helpful for design to come in earlier in the picture rather than later
  - Articulating your choices and considerations makes you really think through the choices you are making. It&#39;s likely that the engineers you are working with are capable of coming up with great design solutions too.

- Pairing with designers/pms also trains engineers design muscles i.e. participating in research studies, design sessions, brainstorms, and etc
  - These are opportunities to have engineers understand the problem at hand. These experiences also pay dividends in the future, when they&#39;re able to contribute valuable ideas back to the project.
  - create and share a &quot;design explorations&quot; doc with wireframes, workflows, or low-fidelity mockups and have engineers pepper the doc with questions around micro-interactions, empty states, error messages, etc. — things usually haven&#39;t been thought about yet. With these questions in mind, designers are able to account for an extra level of detail in the next iteration.
  - On larger projects, slice a project into smaller one-week or two-week milestones

## Pairing Test with a PM/Designer

If you have a pairing test with a PM/Designer, or they ask you how you would go about working with them to build a feature, consider the process flow and questions below:

1) Understand the Use Case:

- Understand why the feature is being built
- why it&#39;s designed the way it is.
- with an understanding of the product, you&#39;ll be able to consider all the different use cases and edge cases with your implementation

2) Implement UX First

- Implement the UX — the flow, functionality, and general layout of the design first.
- Get the overall feel down (don&#39;t go crazy on pixel-perfect implementations yet).
- Once the design has gone through more iterations of testing and versions have stabilized, gradually incorporate in the visual elements.

3) Push Back when helpful and with solutions

- always provide an alternative solution.

- Try, &quot;this solution will be very costly to implement, may I suggest…&quot;.
- Remember that most things can be done with the tools we have today, but that doesn&#39;t mean everything should be done. It&#39;s your job as the engineer to help the designer reach the best, most cost effective solution to a problem.

4) Check-in with Designers Often

- Communication. As you&#39;re implementing a design, make sure to consistently show the designer your progress.
  - Keeping the designer up to date with your progress will help ensure that your implementation is up to expectations
  - and there aren&#39;t any surprises down the road.
  - This is also a great opportunity to ask the designer any questions that you may have about the design, or tasks going forward.

5) Fill in the Gaps\*\*

- When implementing a design, there are always points where you need to use your own best judgement to fill in the gaps.
- \*\*But also don&#39;t go too crazy, and communicate with your designer about bigger decisions. Use your best judgement

#

# Questions to ask other Devs

If you get a chance to interview devs at the company of interest, the below questions are helpful and unique questions to get a better sense of the company culture and work life from an engineers perspective:

  - What inspired you to get involved with \_\_company\_name\_
  - What makes a coworker, more specifically a fellow engineer, easy to work with?
  - How many years have you been with \_\_company\_name\_
  - How many years have you been developing
  - What are some goals you have for yourself, career wise or tech wise?
    - How does \_\_company\_name\_ fit into them?
  - What about your job makes you enjoy going into work everyday?
  - What is something that you wish others knew about your job?
  - What are some unique things about \_\_company\_name\_ that you believe may be rare to find elsewhere?
  - What have been your favorite moments in the role?
  - What have been some of the most challenging moments?
  - What were the biggest adjustments you felt you had to make in your current position from your previous work environments or experiences?
  - On a more general level, what makes the company different from the other companies you&#39;ve worked for?
  - What do you wish you knew or could have done differently when first starting?
  - Are you involved with the outside dev community? Ie meetups hackathons or have your own passion project you work on outside of work?
  - What have been your favorite projects and why?
  - What was one of the biggest technical challenges your team has had and how was it handled?
  - What is the hardest thing about your job?
  - What does a typical day look like in your work day?
    - Is there an on-call schedule?
    - How often do you pair? Is it required or a suggestion?
  - What do you think makes someone successful there?
  - What advice would you give to a beginning engineer there?
  - What do you do with your spare time?
  - Can you tell me about the fellowship at \_\_company\_name\_? Is that new?
    - How many years has it been around?
    - How many participants do they take?
    - How many do they hire afterwards?
  - Can you tell me about the members of the team that I would be joining?
    - Who will I be working most closely with?
    - Who will my collaborators be. Their titles. It&#39;s nice to know how cross-functional the role is.
    - What are the biggest challenges facing the company/department right now?
    - Can you tell me more about the day-to-day responsibilities of this job?
  - How is the company culture here different from other tech companies?
  - Where do you think the company is headed in the next 5 years?
  - How has the company helped you achieve your career goals?
  - What do you do in your spare time?
- Can you tell me about the company&#39;s involvement with \_\_community service orgs\_\_?
  - Do you participate or volunteer at the pairing meeting up hosted by a few of the engineers at \_\_company\_name\_?

- Is there anything about my background or resume that makes you question whether I am a good fit for this role?

    - Fellowship is always available

How are product decisions made?

  - What is the mission and core competency of the company?
  - How do recent product launches fit into that?
  - What are some challenges the company needs to overcome to achieve its mission?
  - How does the company prioritize technical investments vs product investments?
- How has the company helped you achieve your career goals?
  - Do you and your manager discuss your career goals?
  - How does your manager help you define and execute on those goals?
  - What happens when your personal goals misalign with the highest impact thing you can do at the company now?
  - How do people develop and make progress in their careers within the company?
  - How much responsibility is given to new employees when they start?
- Tell me about a project you worked on in the past 6 months.
  - Who proposed this project?
  - How did it get prioritized?
  - Who was accountable for this project and how was that determined?
  - How did you resolve/escalate disagreements amongst the project team?
  - How was your manager involved in this project?
  - What was the look back process like, if there was one?
  - If you had to do this project again, would you want it to go differently?
- What opportunities are there for employees to learn new things?
  - How easy is it for people to move to different teams and try out roles that they haven&#39;t done before?
  - Are there ways to learn about a different technical area than the one you are currently working on?
  - How do people share learnings from past projects and help build common knowledge?

#

# Questions to ask Founders

**Approach:**

Be genuinely curious, look at these interviewers as people you get to learn more about, as friends you get to solve a problem with (ultimately, that could very well turn out to be true). Approaching these with genuine curiosity takes a lot of the pressure off, and makes it an enjoyable process for both you and the interviewers.

An article that I cannot locate at this time wrote about this perfectly, their notes were quite helpful and affirming to hear when I was preparing for this step:

&quot;_Don&#39;t be shy about your questions for the founders of the company. This is your time to interview them and see whether the company aligns with your goals and needs. The interview process is as much about you as it is about the companies. (Sometimes you just want a d\*mn job, i get it - the point is, you are in an empowered position as an interviewee, recognize that and own it). Who they are and how they think trickles down into almost every aspect of the company, and you&#39;ll be spending 70% of your day working for that company. You&#39;ll probably be doing them a service by not asking them the same repetitive questions they&#39;ve heard time and time again. Plus, it will be more enjoyable for everyone if you get out of the box just a tad.&quot;_

**General Questions:**

- What do you see for the engineering team in the next few years?

- In terms of culture, processes, anything that comes to mind that you&#39;d like to see instilled in the team eventually
- r anything that you feel may be missing at the moment

- From your years of experience and knowledge of the company what would you do as a beginner engineer when starting in the role

- to get a good running start and familiarize yourself with the code and company?

- How does your company develop talent?

- Is further education and training supported by the company?

- Are there opportunities for professional development and education, also attending conferences on behalf of the company?

- How does your team work on developing an employee&#39;s weaknesses and strengths?

- Day in the life

- What are the typical working hours?
- How many hours of work is in a typical work week and how often do engineers work over time?
- Is there an on call schedule in place for issues in production?

- What kind of person will succeed at your company, is there a skillset I should already be working on developing?

- What unseen opportunities did you see that resulted in making your startup a huge success?

- If it wasn&#39;t for your startup, what would you be doing now?

- What is your plan to adapt if your industry is completely disrupted?

- Who are your personal business role models and why?

**Growth Plans &amp; Exit**

- Ask what the company will look like in 5-10 years if things went according to plan.

  - If it&#39;s the plan, what would a successful exit look like
  - r is the company&#39;s goal to **go public** or get acquired?

\*Some founders are looking to **IPO** , others to be acquired, and others to stay small, nimble, private, and profitable.

- What is your vision for the business

- And what do you see as the biggest obstacles to you achieving that vision?&quot;

- Who are your biggest competitors and how do you differentiate yourself from them? Why do you think your company can beat the competition?

- Do you think this will be different in 3 years, and why?

- Which areas of the company do you see the most growth/hiring in the upcoming year?

- How do you learn to do what you are doing today?

- What&#39;s the hardest decision you&#39;ve made so far?

- Have you been in a successful startup before? What was the characteristics that led to success? Have you been in a failed start-up before? Why did it fail? what would you do differently?

- What are the future implications of the technology you are developing? Have you considered that it could have negative consequences for some people? How would you deal with that?

- _How do you define success for this business? How do you define success for yourself?_ (The overlap and interplay of these would be interesting to hear. Is the business their identity?)

- How do you manage the duality between driving new business and overseeing daily operations?

- What was the insight that drove you to form the company?

- How many hours a week do you spend on work? What about family/hobbies?

- What are your more short term goals of the company over the next 1, 3, 6 and 12 months? / What are the key company milestones for the next 6-12 months that need to be achieved?

- Is the company profitable/what is the latest valuation of the company?

- What advice would you provide to new entrepreneurs ?

# Salary Negotiation Script

You&#39;re at the salary negotiation part. Congratulations!! At this part, I had a whole process to prepare myself. I first hyped myself up by playing my favorite tunes and listening to motivational talks (athletes do before every big game!). I called my biggest supporters who always remind me of my greatness, and to never, ever settle. I then wrote and prepared a script to help stay on track if my nerves kick in. All of this was very helpful in encouraging me to stand in my power and ask for what I want.

Do what calls to you to hype yourself up and embody the most confident YOU available!

Remember, they will not take back the offer if you ask for a higher salary, or anything for that matter. Once you have the offer, it is yours - the ball is in your court and it won&#39;t disappear unless you specifically tell them you are no longer interested. So, don&#39;t be afraid to ask for things that are important for you, after all, you&#39;re going to be spending the majority of the day working for this company - there&#39;s no reason to not get the most you can for the blood and sweat you&#39;ll be pouring into your work!

My script was as such:

**KEEP IT COOL**

Hi \_\_(hiring managers name)\_, thank you for being available. I wanted to personally thank you for giving me the opportunity to interview with \_\_(company name)\_\_. And for being so helpful throughout the process. I&#39;ve truly enjoyed all of the conversations and meeting everyone on the team.

**KEEP IT COOL**

So I&#39;ve received another offer with a similar arrangement. And am still in communication with another company regarding their offer.

At this point I feel more aligned with \_(company&#39;s name of the hiring manager you&#39;re speaking to)\_ product and culture. I can see myself there for a while.

**KEEP IT COOL**

I&#39;d like the salary to still be competitive down the line so If we can increase the salary to around \_\_(10-15k more than offered. ((Or higher, who am I to stop you, shoot for the stars lol!))), I would be eager to sign and finalize the offer.

(Usually, they&#39;ll respond with something like - &#39;well, this is typically as high as we can go, I will talk with \_\_ and see, but I&#39;m not sure that we can do that&#39;)

(DON&#39;T BUCKLE!! Most often they will ALWAYS come back with a higher offer AFTER they get off the phone. DO NOT retract or settle when they say this!! Stay silent, let them speak, and stay on track.)

Sure, I understand. If you can let me know after you&#39;ve spoken with them that would be great. And I will update you if anything changes on my end.

(Again, if they gave you an offer, it is yours. Get off the phone and give them a few days or a week to come back with a better offer. The offer won&#39;t disappear so relax knowing that you will get an increase!)

# Salary Stock Options

During this step of the process, I reached out to other engineers for their advice. This is what was advised:

- Ask about (or to be shown) the pitch deck, market strategy, exit plan.
  - Does the company have a detailed exit strategy? Are they angling for a purchase? IPO? To stay independent and private (in which case your equity is likely useless to you unless you have an insanely high stake)?
  - This is a great way to learn about the health of the company, to show your interests, and whether to strongly consider investing your income in it or not. With these details, you can gage if it is a strong publicly traded company where you can easily sell it at stable prices.
- Salary is safe and simple, but for some folks the tradeoff is worth it depending on where they&#39;re at in life
- If you&#39;re considering equity over stock, consider if the equity you&#39;re being offered worth the exposure and reduced near term income
- Is the exit valuation above the post money valuation (if more liability than valuation, it&#39;ll be investors, founders and creditors getting what payday is available). More info here [https://valuation.vc/](https://valuation.vc/)
- If the company IPO&#39;s - your equity position can be a game changer. If it does not, or will not, or is unlikely to - equity is not likely to be worth the equivalent cash comp (especially factoring in the time-value of the cash comp). (And there are practically infinite caveats to the IPO scenario - long story short: if you are not a majority player, or a player with great lawyers and the cash to pay them, your equity stake is, in a lot of senses, worth as much as the majority player would like it to be worth).
- The &quot;value&quot; of equity is almost entirely situation dependent: What type of equity is it? Does the company plan to IPO or are they shooting for an acquisition? Are they actually trying to keep strike prices low for employees? What are their plans to dilute and how does it affect your grant? Do they offer exit opportunities when they do new funding rounds?

A few personal experiences:

- &quot;There&#39;s a startup we&#39;ve hired for and I know for certain they&#39;ve had folks leave huge salaries on Wall St to build this thing, I&#39;d probably be interested in equity there&quot;
- &quot;I would be suspicious of any sort of employee stock option plan for an unlisted company unless you have a lot of reasons to believe they&#39;ll go public or get acquired in a reasonable amount of time.&quot;
- &quot;90% of the time it&#39;s a gamble that won&#39;t pay off from my experience but every now and then you find a company that has a solid vision and plan to IPO and is actually trying to give their employees a very nice perk. A lot of canadian companies have really great equity packages from my experience and try to offer exit opportunities pre IPO in case you want an early out.&quot;
- &quot;Things I would look for:

- Founder(s) prior experience. Have they co-founded before? Did that company exit successfully? (ie. did investors and employees make a profit)
- Have they found product-market fit? Are the founders and investors aligned on the roadmap and have a timeline for exit or IPO?
- There are many different types of equity compensation, and I&#39;m not an expert by any means. But the key metrics you should look at are ownership percentage and how much the company has raised. I found this article to give a pretty good overview of two very common schemes[https://discover.shareworks.com/equity-administration/rsus-vs-options-why-rsus-restricted-stock-units-could-be-better-than-stock-options-at-your-private-company](https://slack-redir.net/link?url=https%3A%2F%2Fdiscover.shareworks.com%2Fequity-administration%2Frsus-vs-options-why-rsus-restricted-stock-units-could-be-better-than-stock-options-at-your-private-company)&quot;
