+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "about"
active = true
date = "2016-04-20T00:00:00"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "CV”
subtitle = “asddfsadf”

# Order that this section will appear in.
weight = 7

# List your academic interests.
[interests]
  interests = [
	"Frustrated Magnetism",
	"Theoreis",
	"Application of high energy theories in condensed matter theory"
  ]

# List your qualifications (such as academic degrees).
[[education.courses]]
  course = "PhD in Condensed Matter Theory (expected)"
  institution = "Okinawa Institute of Science and Technology"

[[education.courses]]
  course = "Master in Physics"
  institution = "Northwester University"
  year = 2015

[[education.courses]]
  course = "Master in Applied Mathematics and Theoretical Physics"
  institution = "University of Cambridge"
  year = 2014
  
[[education.courses]]
  course = "BSc in Physics"
  institution = "University of Science and Technology of China"
  year = 2013
 
+++

This is an example of using the *custom* widget to create your own homepage section.

To remove this section, either delete `content/home/teaching.md` or edit the frontmatter of the file to deactivate the widget by setting `active = false`.