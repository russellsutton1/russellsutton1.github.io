---
title: "R&D Engineering Intern"
categories:
  - Industry Experience
tags:
  - Resume
  - Design
  - Software
  - Hardware
header:
  teaser: /assets/images/dcusa.png
  og_image: /assets/images/dcusa.png
---

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Despite the unassuming industry of automatic door motor controllers, working at Door
Controls was exciting and full of learning. I am certain this experience has had a great impact on my trajectory as an engineer, as this introduction to embedded systems helped me find
my fascination of mediating hardware and software systems. My tenure at Door Controls was split between two projects, both of great affect to the quality assurance processes of their buisness.
 
{% capture fig_img %}
![Foo]({{ "/assets/images/dcutruck.jpeg" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>The service truck that started Door Controls USA.</figcaption>
</figure>
 
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Door Controls main operations lie in the refurbishment and development of motor controllers for automated doors. When using a handicapped equipped door, there is a good chance Door Controls has had a
hand in the distribution of the internal controller. My effort was focused on improving the refurbishment process by introducing electronically accessible records. For 25 years, Door Controls 
has managed all refurbishment records through filing cabinets and storage rooms. All knowledge pertaining to standard refurbishment procedures was held within the minds of invaluable employees.
Although all repairs are documented, the storage of them made them inaccessible outside of the most dire circumstances. Developing a method to collect electronic records of refurbishments was the primary task
of the internship period, which was successfully completed and implemented with a two intern team. Working as the lead developer was an invaluable experience, exposing me to test driven development, architecture design,
and product support.
 

{% capture fig_img1 %}
![Foo]({{ "/assets/images/pisql.jpg" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img1 | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Accessing SQL Server on Raspberry Pi's.</figcaption>
</figure>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Management's final expectation was very open ended, with the main request being records accessible in the Microsoft Office Suite through SQL Server. Twenty stations were needed, one for each
repair technician, so unit cost was a consideration during the platform selection process. The familiarity of a name brand tablet was favored, but the development time and cost of creating, as well
as maintaining either a web-app or a mobile device app made this option less that favorable. Both of these scenarios would involve a continued investment from the already short staffed IT department.
With my focus on a cheap and easily maintainable platform for simple data entry, my sights settled on a Raspberry Pi with an accompanying touchscreen. Although the familiarity of
name brand mobile devices would ease use for some users, the stability of the Raspberry Pi and software dependencies made it the favorable choice. Accessible USB and Ethernet ports give users
the ability to add peripherals as well.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Server Create, Read, Update, and Delete operations are conducted through a Python application that accepts parameters through a user interface and barcode scanner. These parameters serve to
identify the model number and the current serial number. By recording every controllers serial number as they are processed as well as the parts replaced, the life cycle of controllers can be empirically estimated
and how part replacements affect the longevity of products.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Constructing an effective user interface was challenging, but was well worth the effort seeing the benefits for the end users as well as management. Technicians were happy to be able to document
repairs from their desk, with no writing and filing, and were able to spend more time repairing. Management's new ability to instantly verify the integrity of any repair as well as
collect large sums of data to begin refining procedures through quality assurance has made the department much more accessible to new employees, in addition to streamlining their current process, and preparing 
to improve in the future. To this day, all twenty technicians record all information through their personal kisok. In the case of any incident, backup disk images were made, as well as the dependencies setup
procedure in case of any sotware lockups. With few software oriented employees at the company, clear documentation to keep this system viable was necessary.

<div style='position:relative; padding-bottom:calc(177.78% + 44px)'><iframe src='https://gfycat.com/ifr/SardonicMeatyHare' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The development of this Python application was a month long commitment, with some support necessary for the remainder of the two month period. During this support period, my attention shifted
towards developing an embedded system to automate quality control testing for their motor controllers. This project introducted me to microcontrollers, which I instantly took great intrest to.

{% capture fig_img2 %}
![Foo]({{ "/assets/images/espproto.jpg" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img2 | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>ESP32 master motor controller prototype.</figcaption>
</figure>