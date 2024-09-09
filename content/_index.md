---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: newabout24
    # block: about.biography
    id: cfp
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: IWBDA-2024

  - block: markdown
    id: submission
    content:
      title: Submission Guidelines
      text: |-
        Abstracts must be submitted via [EasyChair](https://easychair.org/conferences/?conf=iwbda24). Submissions cannot exceed two pages (excluding figures and tables). If you do not have an EasyChair account, please create one by following the instructions specified [here](https://easychair.org/help/account_creation). 
        
        All abstracts must use the IWBDA template and must not exceed two pages excluding the figures and tables. The following versions of the template are available for use:
        - [Overleaf]( https://www.overleaf.com/read/wbdpqqpstxbg#02d65f.)
        - {{<staticref "uploads/IWBDA_2023_Abstract_Template.docx" "newtab">}}MS Word{{</staticref>}}
        
        All abstracts will undergo a single-blind peer review process on EasyChair. The accepted abstracts will be invited to present their work as a poster or a talk at the conference.
        
        We encourage abstracts for posters and/or talks at IWBDA 2023 on ongoing research that may be submitted as a full journal paper later. We are currently in talks with ACS Synthetic Biology to set up a special issue on bio-design automation for such extended journal submissions.
    design:
      columns: '2'   
  
  - block: markdown
    id: cfw
    content:
      title: Call for Workshops
      text: |-
        Do you have an idea for a workshop for Bio-Innovation Week? Submit a proposal for your workshop by uploading a PDF with the following information: workshop title, short description (100 words or less), overall goal(s), format, and expected length in hours for the workshop. Workshops are expected to take place on November 16 and 17. 

        Upload your proposals [here](https://forms.gle/M2641aqY6yKiDMcr6).
    design:
      columns: '2'   

  - block: contact
    id: contact
    content:
      title: Contact Us
      text: |-
        Interested in participating, organizing, or sponsoring IWBDA or Bio Innovation Week? Reach out to us for more information on how you can get involved in IWBDA, IWBMA, the Nona Works Hackathon, or SBOL Workshops. We look forward to hearing from you!
      email: bio.design.automation.inc@gmail.com
  
  - block: people
    id: organising
    content:
      title: Organising Committee
      user_groups:
      - Bio Innovation Week 2024
      - BioDesign Automation Consortium

---
