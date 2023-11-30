# Navigating the Digital World
## Tasks
### AU whenever
- decide on a specific style for all images and regenerate with DALL3 to demonstrate consistency
- put all pages into pros for students who didn't attend classes and can't access Listen Again

## SP
### by week 16
- finalize syllabus, speakers
- choose essay examples from last year
- invite more speakers e.g. 
   1. https://www.essex.ac.uk/people/VALEN80000/elia-valentini
   2. https://www.essex.ac.uk/people/HUGHE78004/gethin-hughes
   3. Jane
   4. Elisif
   5. someone like Schmachtenberger
   6. someone from PPS
   7. someone from Computer Science?

### by week 22
- demonstrate the making of an accessible PDF

### CS220AU next year
- change GitHub account name to krishofstadter from khofstadter
- change template repo name from CS220AU-DP to NDW-DP
- consider using a very basic jekyll theme (instead of relying on GitHub Pages' Minima theme in the background)

### later/whenever 
- essay writing tips: first write it up for a 5 year old, then make it sound more academic? Consider you essay as something in which you want to teach us something about what you have discovered. 
- https://seths.blog/2023/08/the-status-quo-is-very-good/
- could I add a visual outline of the narrative (TOC) to the top of all pages (to help understand the structure?)
  - could I make one figure that visualizes the whole module (website)?
- improve with https://pagespeed.web.dev/
- is there a 5.1 studio in Essex?
- demonstrate some methods (e.g. Skitch, Jekyll, AI generator, ChatGPT, Quillbot)
- spectrum of surveillance exampled with movies (e.g. Cloud Atlas, Matrix, Brazil, 1984)
Integrate:  
- one top figure outlining the narrative of an entire article (example in neuroscientific journal)
- "we must be thought how to think, not what to think"
- critical thinking, neuroscience of confirmation bias, sense-making
   - https://www.linkedin.com/advice/1/what-some-common-challenges-barriers-teaching-critical?trackingId=Whp4zbzgdBB6aKUYqkDS3g%3D%3D&updateUrn=urn%3Ali%3Aactivity%3A7065042585005764608&trk=fs
   - https://www.polleverywhere.com/case-studies/encouraging-critical-thinking-in-class
   - would book summaries be enough (e.g. via Blinkist)
   - compare conflicting ideas 
- increase online security
   - introduce Nord VPN, other software tracking everything and perhaps Avira (free)
 - check what's out there on you, are you OK with it? Search for data on the Net with your name (and nickname) - what is connected to you already that can be easily found by anyone
 - short film by award winning writer: None of the Above | 18+ Short Film on cyberbullying & dating
 - https://wideangle.co/blog/dark-patterns-examples-of-manipulative-consent-requests
 - https://www.makeuseof.com/why-use-multiple-web-browsers/
 - https://www.youtube.com/@ScammerPayback/videos
- demonstrate GPT commenting on the negative effects of using GPT too often (abusing it)
   1. https://learnprompting.org/
- AI safety
- Tristan Harris's [Humantech website](https://www.humanetech.com/)
- John Lilly 'foresees' AI takeover via his hyperspace journeys in his isolations tank [@DeKorne2009p.98]. Lilly probably overused ketamine.
- revise Essex marking criteria part with new file on Moodle
- https://medium.com/@junaidaw567/navigating-the-digital-world-challenges-and-opportunities-6ff34e1c8dfe
- https://www.ecorys.com/app/uploads/files/2020-09/navigating-the-digital-world%20(1).pdf
- exercise: have you ever been misunderstood on the internet and then told off, ridiculed, etc even though your comments arise from good intentions? <!-- hypnotech comments, admin upset -->
- https://www.statista.com/
- https://duckduckgo.com/?q=UK+Social+Media+Demographics+2020&t=brave&ia=web
- compare control in 1984 (book, film) with Brave New World (book, series)

## Log
2023-11-02 Asked for relevant software updates and installations on the Essex Software Hub. Amended the narrative of the project management page as indicated below. Also emailed Ellisif and Jane to find existential risk related events on campus for students to attend. Updated CS220AU and CS220SP permalinks.

2023-10-26 Revised APM and research narrative page. After the classes, I think the narrative of this page needs changing (e.g. we should first think about the more general research narrative and then about the APM framework).

2023-10-19 Revised password-management and your-website pages. Decided to keep the list (notes) form for seminars as they are more useful when talking to people than the written up prose. (Don't read sentences while presenting, especially when your audience can read them as well.) It would be best to write up the lists (notes) into prose after the seminars for students to have a better flow when they revisit the site (and for those who didn't make it to the class), but keep the lists (notes) in HTML comments for next year. This might also be useful for recontextualizing a page for another platform e.g. Medium.

2023-10-12 Refined digital-identities page and added missing files from previous repo.

2023-10-11 Refined template repository. In this repo, I added general info to home page, and refined the page for the overall CS220 file. Also updated the repository with `bundle update` via macOS Terminal.

2023-08-22 Installed Jekyll on macOS 13.5, cloned/forked (?) Just The Docs template via browser, cloned repo on localhost (laptop), installed missing Ruby gems separately with source being `https://gems.ruby-china.com` in the Gemfile, as bundle didn't work. More info in `notes\projects\ndw.md` in private repo. 

Decided to use 'navigatingthedigitalworld' name for the project (instead of CS220). Also, I bought the relevant domain name and started setting up the Just Docs Jekyll theme to us with a GitHub Pages website. After installing jekyll on this macOS, `jekyll serve` didn't run the website, there were some error messages. So, I am trying `bundler update` to install the required things, but in China I can't connect to ruby. Tried a few suggestions [here](https://stackoverflow.com/questions/49800432/gem-cannot-access-rubygems-org), but they didn't work. Then what probably worked was adding ''https:/gems.ruby-china.com' as source in the repository's Gemfile. and then instead of using `bundle install` or `bundle update`, I installed the missing gems individually e.g. with these commands: `gem install rouge -v 4.1.2` and `gem install addressable -v 2.8.4`. I had to make sure the install the specific versions of these gems specified in the Gemfile.lock, and not the most up to date once. I also looked at the https://gems.ruby-china.com/. Somewhere along this journey I also run a command (in the relevant repo) that probably updated ruby. Also, I had to remove some ruby versions manually from the `.gems` folder. There fore files in many folders (cashe, docs, gems and specifications.) After that `jekyll serve` was working. To summarize, bundler didn't work, so I had to install gems individually, and I had to make sure the specific verisons (often older) are installed (in China with using a difference source in the Gemfile.)

In the GitHub repository's Pages setup I also cancelled the DNS check, restarted it, enforced the HTTPS and within seconds the site was up.