# HTML Links, JS Functions, and Intro to CSS Layout

>“You can’t stay in your corner of the Forest waiting for others to come to you. You have to go to them sometimes.”-Winnie the Pooh

## Chapter 4: Ch.4 “Links” (pp.74-93)

- Links are created using the < a> element. Users can click on anything between the opening < a> tag and the closing < /a> tag. You specify which page you want to link to using the href attribute.
- Many people navigate websites by scanning the text for links.
- To write good link text, you can think of words people mightusewhen searching for thepage that you are linking to.
- When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL.
- When you are linking to other pages within the same site,you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.
- On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.
- Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.
- To create a link that starts up the user's email program and addresses an email to a specified email address, you use the < a  href="mailto: >

## Chapter 15: “Layout” (pp.358-404)

- CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

- Block-level elements start on a new line Examples include:< h1> < p> < ul> < li>
- inline elements flow in Between surrounding text Examples include: < img> < b> < i>
- If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
- CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.
- normal flow: Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one
- relative Positioning: This moves an element from the position it would be in normal flow, shifting it to the top, right ect..
- Absolute Positioning: This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding element
- floating elements: an element allows you to take that element out of normal flow and position it to the far left or right of a containing box.
- boxes can overlap. The z-index property allows you to control which box appears on top. For example, an element with a z-index of 10 will appear over the top of one with a z-index of 5.

## Reasons for Pair Programming

- This  article is all about how to pair program and what the advantages are. a lot of people think pair programming is slower and less effiective but here are some reasons why that is not true.
  
1. Greater efficiency: over-all its better to have to pairs pf eyes working on a project than one
2. Engaged collaboration: staying engaged will help you and the partner focus and finish faster.
3. Learning from fellow students: you can watch and learn from someone youre working with and they can do the same from you.
4. Social skills: working with another is a great way to improve your social skills.
5. Job interview readiness. its common to pair program in job interviews
6. Work environment readiness: many employers use pair programming to help train new employees.
[Back to main](README.md)
