---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: newabout
    # block: about.biography
    id: cfp
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: IWBDA-2023
  - block: markdown
    id: submission-guidelines
    content:
      title: Submission Guidelines
      text: |-
        Abstracts and workshop proposals must be submitted via [EasyChair](https://easychair.org/my/conference?conf=iwbda23). Submissions cannot exceed two pages (excluding figures and tables). If you do not have an EasyChair account, please create one by following the instructions specified [here](https://easychair.org/help/account_creation).

        All abstracts must use the IWBDA template and must not exceed two pages excluding the figures and tables. The following versions of the template are available for use: 
          - [Overleaf](https://www.overleaf.com/read/wbdpqqpstxbg)
          - {{<staticref "uploads/IWBDA_2023_Abstract_Template.zip" "newtab">}}LaTeX source{{</staticref>}}
          - {{<staticref "uploads/IWBDA_2023_Abstract_Template.docx" "newtab">}}MS Word{{</staticref>}}
         
        All abstracts will undergo a single-blind peer review process on EasyChair. The accepted abstracts will be invited to present their work as a poster or a talk at the conference.

        We encourage abstracts for posters and/or talks at IWBDA 2023 on ongoing research that may be submitted as a full journal paper later. We are currently in talks with [ACS Synthetic Biology](https://pubs.acs.org/journal/asbcd6) to set up a special issue on bio-design automation for such extended journal submissions.
         
    design:
      columns: '2'
  - block: markdown
    id: cfw
    content:
      title: Call for Workshop Proposals
      text: |-
        Do you have an idea for a workshop for [Bio Design Week](#biodesignweek)? Submit a proposal for your workshop by uploading a PDF with the following information: workshop title, short description (100 words or less), overall goal(s), format, and expected length in hours for the workshop.

        Upload your proposals using [this link](https://tinyurl.com/BioDesignWeekWorkshops).

        <b>Workshop proposal deadline:</b> July 30th 2023

    design:
      columns: '2'
  - block: biodesignweek
    # block: about.biography
    id: biodesignweek
    content:
      # title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: biodesignweek-2023
  
  - block: people
    content:
      title: Organising Committee
      user_groups:
      - Chairs

---
