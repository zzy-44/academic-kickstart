+++
# Date this page was created.
date = 2018-05-07T00:00:00

# Project title.
title = "high-speed microscopic measurement system"

# Project summary to display on homepage.
summary = " "

weight = 2

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["rladies", "software-tools", "blogs", "compbio-bioinfo", "R"]
categories = ["R"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "" # //bit.ly/rlel-github-meetup

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = "https://github.com/rladies-eastlansing"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{icon_pack = "fab", icon="twitter", name="Follow (me)", url = "https://twitter.com/janani137"}, {icon_pack = "fab", icon="twitter", name="Follow R-Ladies East Lansing", url = "https://twitter.com/RLadiesELansing"}]

# Does the project detail page use math formatting?
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
  
  # Show image only in page previews?
  preview_only = false

+++

# Summary
<img src="/interests/rladies_files/rladies.jpeg" alt="" width="200px" height="200px"/>


<p style="text-align: justify;">
    A system based on high-speed microscopic observation and dynamic measurement technology has been established in this project, microactuators’ motion states and dynamic characteristics can be tested based on this system. High-speed CMOS/CCD (240fps) combined with optical microscope is used in this system to capture the video of actuator’s movement and a sub-pixel motion analysis software is utilized to acquare the characteristics of microactuators such as deflection, amplitude, displacement and so on. This non-contact optical testing method has the advantages of non-destruction, non-contact, high-speed and high-precision.</p>
  <img src="Fig_1.png" alt="" width="400px" height="400px"/>
  <figcaption>
<h2>Procedure of the time axis fitting software</h2>
<p style="text-align: justify;">
    As is known to all, pixel is the smallest unit in the imaging system, by sub-pixel fitting we can break this limit, thus a high-precision testing system whose minimum resolution is 0.1&\mu&m can be established. Procedure of the sub-pixel fitting based analysis software (time axis) is shown as below. Similar to this time axis analysis software, spatial axis analysis software which shows the moving trail of the feature point has been constructed as well. From these two software, microactuators’ deflection, frequency, displacement and velocity can be measured precisely.</p>
  <img src="Fig_2.png" alt="" width="600px" height="600px"/>
  <figcaption>
<h2>Interface of the time axis fitting software</h2>


