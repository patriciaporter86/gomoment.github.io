# Ivy-Docs2
a place to properly build our ivy docs. can test and compare with old

This readme should help with master plan of whats needed/missing and process for adding/updating
 - possible idea to make editable by all is to just have people create md for the pages they want. can edit already existing ones or create a new one, submit a 'PR'of sorts (just send the md) and ill update via mkdocs build. if done this way would be good to do in batches so dot have to add html features repeatedly

MAKE CHANGES IN MARKDOWN WHENEVER POSSIBLE
note to self: useful tool for converting old pages - https://domchristie.github.io/to-markdown/

Note: when you point Cname here, make whats currently at ivydocs.gomoment.com/Ivy-Docs still available for comparison as we continue to build this out  
once you change name double check robots.txt with - http://tool.motoricerca.info/robots-checker.phtml  
optional free deploy - https://surge.sh/

mk docs overwrites html with each build so some features have to be added in the site folder (html files) after running mkdocs build and before pushing.

those include:
Sections in TOC,
removing mkdocs water mark,
adding intercom widget,
make not turn color after click if (can try git ignore in css),
and image maps 
 - FOR NEXT ITERATION: forgot to add tab pages (visits tab , about, timeline, notes, etc) via mkdocs build so that content on guest profiles page will go away, will need to add next time via mkdocs build. and fix caption under image map. make it so tab names are headers and caption can be same as others (caption is click image or use links at left)
 - FOR NEXT ITERATION: caption above map in messages also will need fixing via mkdocs
 - NOTE: all image maps are agents, guest profiles, managers, messages, staff console


