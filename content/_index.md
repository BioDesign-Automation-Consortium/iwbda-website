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
  
  - block: people
    id: keynote
    content:
      title: Keynote Speakers
      user_groups:
      - 2024 Speakers

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
    id: registration
    content:
      title: Registration
      text: |- 
        <link rel="stylesheet" type="text/css" href="https://www.brownpapertickets.com/widget_v671.css" /> <DIV ID="bpt_eventbody"><CENTER><BR><BR>Brown Paper Tickets Ticket Widget Loading...<BR><BR><A HREF="https://www.brownpapertickets.com/event/6463652">Click Here</A> to visit the Brown Paper Tickets event page.</CENTER><BR><BR></DIV> <script src="https://www.brownpapertickets.com/eventwidget.js?event=6463652&nodescription=1" type="text/javascript" language="javascript"></script> <script src="https://www.brownpapertickets.com/widget_v671.js?event=6463652" type="text/javascript" language="javascript"></script>
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

  - block: markdown
    id: agenda
    content:
      title: Agenda
      text: |- 
          # Bio Innovation Week - November 16-19, 2024

          ## Saturday, November 16 - 610 Commonwealth Avenue, CILSE 101

          - **08:30-09:00** Registration and light breakfast
          - **09:00-09:10** Welcome and kick-off of Bio Innovation Week
          - **09:10-10:10** Keynote - Dr Roseanna N. Zia: Colloidal Physics Instantiates Life in Biological Cells
          - **10:10-10:40** Coffee break
          - **10:40-12:00** 
            - SBOL Data Model Workshop
            - NonaWorks Logistics, Examples, Demos (TBD)
          - **12:00-13:00** Lunch
          - **13:00-14:20** 
            - SBOL Visual Workshop
            - NonaWorks + Office Hours
          - **14:20-15:00** Coffee break
          - **15:00-16:00** Nona Works: Present Proposals

          ## Sunday, November 17 - 610 Commonwealth Avenue, CILSE 101

          - **08:30-09:00** Registration and light breakfast
          - **09:00-10:20** Managing lab info
          - **10:20-10:45** Coffee break
          - **10:45-12:00** Managing lab info
          - **12:00-13:00** Lunch
          - **13:00-14:20** IWBDA Talks
          - **14:20-14:40** Coffee break
          - **14:40-17:00** IWBDA Talks
          - **08:30-17:00** NonaWorks Office Hours

          ## Monday, November 18 - 8 St. Mary's Street, Photonics 906

          - **08:30-09:00** Registration and light breakfast
          - **09:00-10:00** Keynote - Dr. Michael Koeris
          - **10:00-10:25** Coffee break
          - **10:25-11:45** Synbiohub Workshop
          - **11:45-13:20** Lunch
          - **13:20-14:40** IWBMA Talks: Amplifying Science Through Automation
          - **14:40-15:10** Coffee break
          - **15:10-16:50** IWBDA Talks
          - **08:30-16:50** NonaWorks Office Hours
          - **17:00-20:30** Dinner

          ## Tuesday, November 19 - 610 Commonwealth Avenue, CILSE 101

          - **08:30-09:00** Registration and light breakfast
          - **09:00-09:45** NonaWorks Presentations and Voting
          - **09:45-10:15** Coffee break
          - **10:30-11:30** Brainstorming
          - **11:30-12:00** Brainstorming and Summary
          - **12:00-13:00** Lunch
          - **13:00-14:00** IWBMA Industry Talks
          - **14:00-15:00** IWBDA Talks
          - **13:00-15:00** NonaWorks Office Hours
          - **15:00-15:20** Awards and Closing Remarks
          - **15:20-17:30** Vendor Booths & Cocktail Hour & DAMP Lab Tours in 106B and 106D


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
