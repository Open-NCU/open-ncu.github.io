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
           placeholder="Your project's name" 
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
        Open Access Charges
      </option>
      <option>
        Data Storage
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
      Publication / Results
    </label>
    <input id="publication" 
           type="text" 
           name="publication" 
           placeholder="examples: 10.1016/j.cpc.2013.09.018, unpublished, collaboration (data storage)" 
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

    <label>
      <input type="checkbox" name="check" value="yes"> I hereby acknowledge that
      I have read and understood the Terms and Conditions and I agree to all of 
      the terms.
    </label>

  <input type="hidden" 
         name="_subject" 
         id="email-subject" 
         value="Open-NCU Form Submission">

  </fieldset>

  <input type="submit" 
         value="Send Message">
</form>
