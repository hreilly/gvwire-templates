# gvwire-templates
Email templates for GV Wire

Designed for use with Activecampaign

# Newsletter Template

RECOMMENDED PROGRAMS: Dreamweaver, Photoshop, Brackets, Word, RIOT, Cyberduck

CUSTOMIZATION NOTES:

1. To start, I prefer to copy everything from the .doc to a good text editor [http://brackets.io/]. It's much easier to highlight the text you want and avoid pulling in odd formatting or line breaks. *You'll still need the word document for links.*

1. For each newsletter, the featured images should be created using the included PSD template, then optimized in RIOT to under 25kb each. To work with, I just download the 750x400 image versions from both articles. I typically lead with the orange overlay, but I have switched it up on occasion. "alt_text" should be changed to reflect the content of the image.

1. The best bet for catching incorrect links is opening them all and copying the url from the browser. This lets you make sure that the link is actually what it is supposed to be and that it doesn't have a long, unnecessary tracking link from another UTM source.

1. The two featured stories link from both the image and the headline. Articles in the list only link from the single "Read More" line. If you have trouble finding placement for any of the links, you can search the document for my (href="#") placeholders. 

1. For the articles that do not come from GV Wire, alter the "Read more on ### >>" line to reflect the appropriate source. Sometimes you'll need to use this line for more than one article. If this is the case, make sure to copy the entire line including the "strong" tags and remove the "font-weight: bold" designator from the link styling.

1. All of the linked template images live in the /th.images bucket under /gvwire. Images unique to each newsletter are stored in /ftf and further broken down by week.

1. Daily newsletters and their component parts (including the original .doc and the .html) live in Marketing/41- GV Wire/First Things First 2018. The files are further broken down by month and date.

1. Once the template has been updated, run it through Litmus [https://putsmail.com/inliner]. This is probably the most important step because it pulls all of the CSS into inline styles.

1. In Activecampaign, create a new campaign and select "Build from Scratch". Choose HTML, copy in the subject line (and check the email addresses), and then paste the code from Litmus in the editor. 

1. Make sure to send a test email, even if the links have already been checked. On 

1. When everything is finished and sent, make sure to save out the original .doc and a copy of the edited template. *Select "No" when the Dreamweaver dialogue asks if you'd like to update links.*
