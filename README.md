# gvwire-templates
Email templates for GV Wire

Designed for use with Activecampaign, though with minor modifications, they should work through an major email marketing platform.

# Welcome Letter Template

This letter will automatically send to new subscribers and won't need to be updated frequently.

*It is important to note that the linked articles should be refreshed periodically. It may be advisable to request new links from the Editor or Operations Manager on a monthly basis.*

# Newsletter Template

RECOMMENDED PROGRAMS: Editor of choice (VS Code, Atom, Sublime, Vim, Brackets), Photoshop, Word, RIOT, Cyberduck

CUSTOMIZATION NOTES:

1. To start, I prefer to copy everything from the .doc to a good simple text editor. It's much easier to highlight the text you want and avoid pulling in odd formatting or line breaks. *You'll still need the word document for links.*

1. For each newsletter, the featured images should be created using the included PSD template, then optimized in RIOT to under 25kb each, if possible (OK to save over the original). To work with, I just download the 750x400 image versions from both featured articles. If adjustments need to be made, they should focus on making these smaller images more eye-catching than the originals and also ensuring that they don't clash too intensely with the newsletter's color palette. It may be necessary to find alternative artwork in some situations. Occassionaly, reszing the artwork to cover the canvas results in losing important parts of the image. In this case, use the alternative template, applying the filters and layer styling to your image(s).

1. The best bet for catching incorrect links is opening them all and copying the url from the browser. This lets you make sure that the link is actually what it is supposed to be and that it doesn't have a long, unnecessary tracking code from another UTM source. If an article is behind a paywall, you can typically circumvent it by opening the url in icognito mode.

1. The two featured stories link from both the image and the headline. Articles in the list only link from the single "Read More" line. If you have trouble finding placement for any of the links, you can search the document for (href="#") placeholders.

1. For the articles that do not come from GV Wire, alter the "Read more on ### >>" line to reflect the appropriate source. Sometimes you'll need to use this line for more than one article. If this is the case, make sure to copy the entire line including the "strong" tags and remove the "font-weight: bold" designator from the link styling.

1. Scrub the text pretty thoroughly for grammar/spelling errors and syntax issues. Even once the content has been approved by GV Wire, there are sometimes errors that need to be corrected. Simple grammar or spelling mistakes can be fixed without approval. Any major errors should be brought to the attention of the Operations Manager for correction. *Any corrections you make should follow AP style. If you aren't sure what this should look like, consult GV Wire staff. Notice something that seems archaic? Tempted to add the beloved Oxford comma? Make sure it's not purposeful AP style before you alter it (ex. using percent instead of %).

1. All of the linked template images live in the /th.images bucket under /gvwire. Images unique to each newsletter are stored in /ftf and further broken down by week.

1. Daily newsletters and their component parts (including the original .doc and the .html) live in Marketing/41 GV Wire/First Things First 2018. The files are further broken down by month and date.

1. Once the template has been updated, run it through [Litmus](https://putsmail.com/inliner). This is probably the most important step because it pulls all of the CSS into inline styles.

1. In Activecampaign, create a new campaign and select "Build from Scratch". Choose HTML, copy in the subject line (and check the email addresses), and then paste the code from Litmus in the editor.

1. Make sure to send a test email, even if the links have already been checked. On rare occasions, there will be an issue with the inlining process that you can only catch in a test email. If this happens, simply run the original code through the inliner again and it should be resolved.

1. When everything is finished and sent, make sure to save out the original .doc and a copy of the edited template in Marketing/41 GV Wire/First Things First 2018/ (broken down by month then day).
