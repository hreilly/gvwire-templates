# gvwire-templates
Email templates for GV Wire

Designed for use with Activecampaign

# Newsletter Template

CUSTOMIZATION NOTES:

1. For each newsletter, the featured images should be created using the included PSD template, then optimized in RIOT to under 25kb each. I typically lead with the orange overlay, but I have switched it up on occasion. "alt_text" should be changed to reflect the content of the image.

2. The two featured stories link from both the image and the headline. Articles in the list only link from the single "Read More" line. If you're unsure of where to find any of the links, you can search the document for my (href="#") placeholders. 

3. For the articles that do not come from GV Wire, alter the "Read more on ### >>" line to reflect the appropriate source. Sometimes you'll need to use this line for more than one article. If this is the case, make sure to copy the entire line including the "strong" tags and remove the "font-weight: bold" designator from the link styling.

4. All of the linked template images live in the /th.images bucket under /gvwire. Images unique to each newsletter are stored in /ftf and further broken down by week.

5. Daily newsletters and their component parts (including the original .doc and the .html) live in Marketing/41- GV Wire/First Things First 2018. The files are further broken down by month and date.

6. Once the template has been updated, run it through Litmus [https://putsmail.com/inliner]. This is probably the most important step because it pulls all of the CSS into inline styles.

7. In Activecampaign, create a new campaign and select "Build from Scratch". Choose HTML and paste the code from Litmus in the editor.
