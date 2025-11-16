---
# Leave this empty to use the site title from config
title:
type: landing

# All the sections of your one-page site
sections:

  # Top section: your bio + avatar (like Belinda’s top card)
  - block: about.biography
    id: top
    content:
      title: ""
      # This must match the folder name in content/authors/
      username: admin

  # Job Market Paper section
  - block: markdown
    id: job-market-paper
    content:
      title: "Job Market Paper"
      subtitle: ""
      text: |
        **Title:** Your Job Market Paper Title Here  

        **Abstract**  
        Write your abstract here. Keep it to 1–2 short paragraphs for readability.

        You can add one or two links, for example:

        - [Download paper (PDF)](/files/jmp.pdf)  
        - [Latest version](/files/jmp-latest.pdf)

  # Working Papers section
  - block: markdown
    id: working-papers
    content:
      title: "Working Papers"
      subtitle: ""
      text: |
        1. **Working Paper 1 Title**  
           (with Coauthor Name, if any)  
           One–two sentence description.  
           [PDF](/files/wp1.pdf)

        2. **Working Paper 2 Title**  
           (with Coauthor Name, if any)  
           One–two sentence description.  
           [PDF](/files/wp2.pdf)

        3. **Working Paper 3 Title**  
           Short description.  
           [PDF](/files/wp3.pdf)

  # Contact section
  - block: markdown
    id: contact
    content:
      title: "Contact"
      subtitle: ""
      text: |
        - **Email:** [you@school.edu](mailto:you@school.edu)  
        - **Office:** Your Office Address, City, Country  
        - **Phone:** (+1) 000-000-0000  

        You can also add links, for example:

        - [Download my CV](/files/cv.pdf)

  # Committee section
  - block: markdown
    id: committee
    content:
      title: "Dissertation Committee"
      subtitle: ""
      text: |
        - Prof. Firstname Lastname (Chair), Department of XXX, University of YYY  
        - Prof. Firstname Lastname, Department of XXX, University of YYY  
        - Prof. Firstname Lastname, Department of XXX, University of YYY  
---
