---
layout: single
title: Apply
permalink: /apply/
author_profile: true
sidebar:
  nav: shortcuts
---

Apply by filling the following form:

<form id="fs-frm" 
      name="open-ncu-form" 
      accept-charset="utf-8" 
      action="https://formspree.io/xyygvnbv" 
      method="post">

  <fieldset id="fs-frm-inputs">

    <label for="full-name">
      Contact Name
    </label>
    <input type="text" 
           name="name" 
           id="full-name" 
           placeholder="First and Last" 
           required="">

    <label for="project-name">
      Project Name
    </label>
    <input type="text" 
           name="project" 
           id="project-name" 
           placeholder="Your project's name?" 
           required="">

    <label for="email-address">
      Email Address
    </label>
    <input type="email" 
           name="_replyto" 
           id="email-address" 
           placeholder="your@email.com" 
           required="">

    <label for="department-name">
      Department
    </label>
    <input type="text" 
           name="department" 
           id="department-name" 
           placeholder="Your department" 
           required="">

    <label for="category">
      Category
    </label>
    <select id="category" 
            type="texy" 
            name="category">
      <option value="Select" selected="" disabled="">
        Select
      </option>
      <option>
        Open Access Fee
      </option>
      <option>
        Article Publishing Charges
      </option>
      <option>
        Dropbox
      </option>
      <option>
        GitHub
      </option>
      <option>
        Other
      </option>
    </select> 

    <label for="data">
      Will project data be provided without restrictions?
    </label>
    <select id="data" 
            type="texy" 
            name="data">
      <option>
        Yes
      </option>
      <option>
        No
      </option>
    </select>
    
    <label for="publication">
      Publication
    </label>
    <input id="publication" 
           type="text" 
           name="publication" 
           placeholder="examples: 10.1016/j.cpc.2013.09.018, unpublished" 
           required>

    <label for="explanation">
      Explanation
    </label>
    <textarea rows="5" 
              name="exp" 
              id="explanation" 
              placeholder="Why should we fund your project?" 
              required="">
    </textarea>

    <label for="check">
      I hereby confirm that:
      <input type="checkbox" name="check" value="yes">
      I am willing to participate in the contest. I inform that I read the 
      Terms and Conditions of the contest and that I agree for processing 
      my personal data solely for the purpose of the of the contest, and 
      in case of acquiring the funding, I agree that my first and last name 
      will be published in the public ranking list  that will be published 
      at project's website.
    </label>

  <input type="hidden" 
         name="_subject" 
         id="email-subject" 
         value="Open-NCU Form Submission">

  </fieldset>

  <input type="submit" 
         value="Send Message">
</form>
