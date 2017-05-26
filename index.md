## Welcome to the NetDispenser
  **May 25, 2017**
  NetDispenser is an automated, kiosk-type platform that requires kids to complete activities in order to earn internet access.
  Last weekend, at PyCon in Portland, Kirby Urner and I gave demos of the platform at our 
  <a href="https://flic.kr/y/2GSVF7K">poster session</a>, using our tablets.
  Our goal was to collect email addresses of interested people and start building a community right there at PyCon.  
  Roughly 100 people left us their email so that we could invite them to the project once we got a bit more organized.

  This project began in 2005 when I would send email to my kids containing a couple links to articles which I thought they
  should read.  Saying "please" had no effect, and thus I developed a JavaScript paragraph-reconstruction activity called, 
  simply, Article Reader.  The Article Reader made sure that they read carefully, but they could still browse the net in 
  another tab instead of reading the article.  Thus came the concept of earning time on the internet in exchange for completing
  activities.  Early prototypes showed that this was very effective, indeed, resulting in things like children begging for
  another math exercise, and so on.  It may be for the "wrong" reasons, but it also turns out that they find themselves 
  compelled towards expedience when effort is required to complete an activity. 

  The NetDispenser is two pieces: The CreditMeter, which is a Raspberry-Pi 3 configured as a WiFi access point, and broadcasting
  the <a href="http://meter.creditfeed.me">CreditMeter website</a> locally.  This device becomes the WiFi access point for the kids.  It only gives them internet access
  when the CreditMeter application is actively consuming their credits.  When the credits are gone then the child must visit the
  <a href="http://www.creditfeed.me">CreditFeeder website</a> and perform credit-earning activities which a parent has queued for them.  Once earned, the credits are
  transferred back to the CreditMeter with the push of a single button.  The CreditFeeder website is remote so that a parent can
  assign activities from the comfort of a remote office and then rest assured that the kids are working diligently.

After PyCon my next goal is to build a core community and help each member obtain a working credit-meter.  The online credit-meter doesn't really do anything 
  except enable you to go through the motions and pretend that it's actually controlling your internet access.  But that's the
  web interface you get when you connect to the Raspberry-Pi's credit-meter website.

Building a community is really difficult!  Please don't go away without registering your interest!!  For the moment, and hopefully
  only a very short moment, please share your email directly to me: ccosse (at) gmail.com and I will send you an official invite
  through GitHub.

Screenshots of credit-meter and credit-feeder softwares can be viewed <a href="https://github.com/NetDispenser/CreditMeter">here</a> and <a href="https://github.com/NetDispenser/CreditFeeder">here</a>.


## Default Content to Delete
You can use the [editor on GitHub](https://github.com/NetDispenser/NetDispenser.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/NetDispenser/NetDispenser.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
