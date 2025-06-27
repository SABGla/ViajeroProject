---
layout: profiles
permalink: /team/
title: Team
description: Members and affiliates of AUGSOC
nav: true
nav_order: 7


profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: right
    image: team/mark.png
    content: team/about_mark.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>Lead Investigator</p>
  - align: left
    image: team/joseph.png
    content: team/about_joseph.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>Research Co-Investigator / Research Associate</p> 
  - align: right
    image: team/graham.jpg
    content: team/about_graham.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>Research Co-Investigator / Research Fellow</p> 
  - align: left
    image: team/Khamis.jpg
    content: team/about_mo.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>Co-Investigator</p>  
  - align: right
    content: team/about_thomas.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>Research Associate</p>  
  - align: left
    content: team/about_orla.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>PhD Student</p>  
  - align: right
    content: team/about_zayne.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>PhD Student</p>  


profiles_interns:
  - align: right
    image: team/jolie.png
    content: team/about_jolie.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>Research Intern (Summer 2022-2024)</p>
---


<form role="search" id="form">
    <input type="search" id="query" name="q" placeholder="Search..." aria-label="Search Contacts">
    <button> Search </button>
</form>

<script>
    const f = document.getElementById('form');
    const q = document.getElementById('query');
    const site = 'https://thomasnewton03.github.io/ViajeroWebsite/team/';

    function submitted(event) {
      event.preventDefault();
      const google = 'https://www.google.com/search?q=site%3A+';
      const url = google + site + '+' + q.value;
      const win = window.open(url, '_blank');
      win.focus();      
    }

    f.addEventListener('submit', submitted);
</script>
