---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: newabout25
    # block: about.biography
    id: cfp
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: IWBDA-2025

  - block: people
    id: keynote
    content:
      title: Keynote Speakers
      user_groups:
      - 2025 Speakers

  - block: markdown
    id: submission
    content:
      title: Submission Guidelines
      text: |-

        Abstracts and workshop proposals must be submitted via [EasyChair](https://easychair.org/conferences/?conf=iwbda25). Submissions cannot exceed two pages (excluding figures and tables). If you do not have an EasyChair account, please create one by following the instructions specified [here](https://easychair.org/help/account_creation).

         All abstracts must use the IWBDA template and must not exceed two pages excluding the figures and tables. The following versions of the template are available for use:
          - [Overleaf]( https://www.overleaf.com/read/wbdpqqpstxbg#02d65f.)
          - {{<staticref "uploads/IWBDA_2023_Abstract_Template.docx" "newtab">}}MS Word{{</staticref>}}

        All abstracts will undergo a single-blind peer review process on EasyChair. The accepted abstracts will be invited to present their work as a poster or a talk at the conference.

        We encourage abstracts for talks at IWBDA 2025 on ongoing research that may be submitted as a full journal paper later. We are currently in talks with ACS Synthetic Biology to set up a special issue on bio-design automation for such extended journal submissions.
    design:
      columns: '2'

  - block: markdown
    id: registration
    content:
      title: Registration
      text: |-
          <link rel="stylesheet" type="text/css" href="https://www.brownpapertickets.com/widget_v671.css" /> <DIV ID="bpt_eventbody"><CENTER><BR><BR>Brown Paper Tickets Ticket Widget Loading...<BR><BR><A HREF="https://www.brownpapertickets.com/event/6694087">Click Here</A> to visit the Brown Paper Tickets event page.</CENTER><BR><BR></DIV> <script src="https://www.brownpapertickets.com/eventwidget.js?event=6694087&nodescription=1" type="text/javascript" language="javascript"></script> <script src="https://www.brownpapertickets.com/widget_v671.js?event=6694087" type="text/javascript" language="javascript"></script>
    design:
      columns: '2'

  - block: markdown
    id: agenda
    content:
      title: Tentative Agenda
      text: |-
          ## Sunday, September 7 - WPI Odeum 79 Park Ave, Worcester, MA 01605
          - **08:30-09:00** Registration and light breakfast
          - **09:00-09:10** Welcome and kick-off of Bio Innovation Week
          - **09:10-10:10** Workshop
          - **10:10-10:40** Coffee break
          - **10:40-12:00** Workshop
          - **12:00-13:00** Lunch
          - **13:00-14:20** IWBDA Presentations
          - **14:20-15:00** Coffee break
          - **15:00-16:00** WPI Tour

          ## Monday, September 8 - WPI Odeum 79 Park Ave, Worcester, MA 01605
          - **08:30-09:00** Registration and light breakfast
          - **09:00-10:00** Keynote - Dr. Katie Galloway: Engineering high-precision, dynamic genetic control systems for cell fate programming
          - **10:00-10:30** Coffee break
          - **10:30-11:30** Keynote - Dr. Niles A. Pierce: NUPACK: Analysis and Design of Nucleic Acid Structures, Devices, and Systems
          - **11:30-13:00** Lunch
          - **13:00-14:20** IWBDA Presentations
          - **14:30-15:00** Coffee break
          - **15:00-16:00** IWBDA Presentations
          - **17:00-19:00** Dinner

          ## Tuesday, September 9 - WPI Odeum 79 Park Ave, Worcester, MA 01605
          - **08:30-09:00** Registration and light breakfast
          - **09:00-10:00** Keynote - Dr. Samuel W. Schaffter: RNA strand exchange circuits as a general-purpose molecular programming language for synthetic biology
          - **10:00-10:30** Coffee break
          - **10:30-11:30** Keynote - Dr. Mark Knappenberger: Designing Translation-competent mRNA Origami Nanoparticles within the OxRNA Ecosystem
          - **11:30-13:00** Lunch
          - **13:00-14:20** IWBDA Presentations
          - **14:30-15:00** Coffee break
          - **15:00-16:00** IWBDA Presentations
          - **16:00-16:15** Closing Remarks

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
      - Bio Innovation Week 2025
      - BioDesign Automation Consortium

---
