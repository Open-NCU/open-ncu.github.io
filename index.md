---
layout: home
author_profile: true
sidebar:
  nav: shortcuts
---
This is the main site for the project *Open NCU -- Open Source, Open Science*
which focuses on promoting activities related to to the open model of doing 
research at Nicolaus Copernicus University.

The project is led by Jakub Rydzewski, within the Department of Biophysics 
at the Institute of Physics, Nicolaus Copernicus University in Torun, Poland.

The *Open NCU* project is being financed by the Polish National Agency for
Academic Exchange (NAWA). See NAWA's goals here: 
[https://nawa.gov.pl/en/nawa](https://nawa.gov.pl/en/nawa).

The *Open NCU* project is supporting the following activities:
* Funding open access fees or article publishing charges;
* Providing extended access to data storage services like 
  [GitHub](https://github.com) or [Dropbox](https://dropbox.com).

Questions related to the application in *Open NCU* can be directed to 
<jr@fizyka.umk.pl>. 

Apply by filling the following form:

Fields marked with "<sup>*</sup>" are optional

<form id="fs-frm" name="open-ncu-form" accept-charset="utf-8" action="https://formspree.io/xyygvnbv" method="post">
  <fieldset id="fs-frm-inputs">

    <label for="full-name">Contact Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">

    <label for="full-name">Project Name</label>
    <input type="text" name="project-name" id="project-name" placeholder="What's it called?" required="">

    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="your@email.com" required="">

    <label for="email-address">Department</label>
    <input type="email" name="department" id="department" placeholder="Your department" required="">

    <label for="category">Category</label>
    <select id="category" type="texy" name="category">
      <option value="Select" selected="" disabled="">Select</option>
      <option>open access</option>
      <option>article publishing charges</option>
      <option>Dropbox</option>
      <option>GitHub</option>
      <option>other</option>
    </select> 

    <label for="category">Will project data be provided without restrictions?</label>
    <select id="category" type="texy" name="category">
      <option>yes</option>
      <option>no</option>
    </select>
    
    <label for="publication">Publication</label>
    <input id="publication" type="text" name="publication" placeholder="examples: 10.1016/j.cpc.2013.09.018, unpublished" required>

    <label for="message">Explanation</label>
    <textarea rows="5" name="message" id="message" placeholder="Why should we fund your project?" required=""></textarea>

  <input type="hidden" name="_subject" id="email-subject" value="Open-NCU Form Submission">

  </fieldset>

  <input type="submit" value="Send Message">
</form>
