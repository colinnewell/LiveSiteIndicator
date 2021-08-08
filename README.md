# LiveSiteExtension

A quick demo chrome extension that demonstrates adjusting the css of a site.

This was developed to allow tweaks to be made to a live site to remind you that
you are indeed visiting a live site.  Software developers and testers often
visit a test version of the site as well as the live one and it can become easy
to get confused.

The idea is to make it clear when you are on live rather than modify the test
site because you don't want to miss imperfections on the test site.  The live
site oddly enough you mostly aren't so worried about (most of the time).

I've adjusted this to point at the bbc site as a quick demo, and make a glaring
difference on the main page at least.  The idea is that you tweak it to suit
your needs.

## Installing

Go to Extensions in Chrome.  Select developer mode (top right) and then 'Load
unpacked'.  Then select the folder.

## Customisation

Update the url to target in the `manifest.json`.  That ensures that the css is
just applied to the correct site.

Then update `banner.css` to adjust the site to make it obvious you're on live.
Techniques I've used generally involve adjusting the header as that's commonly
on most pages, and gives you most bang for your buck, and potentially the
background.  A pink background where it's nomrally white can be quite a glaring
indicatory you're on live.
