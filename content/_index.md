---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: newabout26
    # block: about.biography
    id: cfp
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: IWBDA-2026

  - block: people
    id: keynote
    content:
      title: Keynote Speakers
      user_groups:
      - 2026 Speakers

  - block: markdown
    id: submission
    content:
      title: Submission Guidelines
      text: |-
        Abstracts and workshop proposals must be submitted via [EasyChair](https://easychair.org/conferences?conf=iwbda26). Submissions cannot exceed two pages (excluding figures and tables). If you do not have an EasyChair account, please create one by following the instructions specified [here](https://easychair.org/help/account_creation).

        All abstracts must use the IWBDA template and must not exceed two pages excluding the figures and tables. The following versions of the template are available for use:
        - [Overleaf]( https://www.overleaf.com/read/wbdpqqpstxbg#02d65f.)
        - {{<staticref "uploads/IWBDA_2023_Abstract_Template.docx" "newtab">}}MS Word{{</staticref>}}

        All abstracts will undergo a single-blind peer review process on EasyChair. The accepted abstracts will be invited to present their work as a poster or a talk at the conference.

        We encourage abstracts for posters and/or talks at IWBDA 2026 on ongoing research that may be submitted as a full journal paper later. We are currently in talks with ACS Synthetic Biology to set up a special issue on bio-design automation for such extended journal submissions. For the full CFP and the latest information, please visit: https://www.iwbdaconf.org
    design:
      columns: '2'

  - block: markdown
    id: registration
    content:
      title: Registration
      text: |-
          <div style="position:relative; width:100%; height:900px;">
              <iframe
                title="Ticketing powered by Zeffy"
                style="position:absolute; border:0; top:0; left:0; width:100%; height:100%;"
                src="https://www.zeffy.com/embed/ticketing/iwbda--2026"
                allowpaymentrequest
                allowtransparency="true">
              </iframe>
          </div>
    design:
      columns: '2'

  - block: markdown
    id: agenda
    content:
      title: Agenda
      text: |-
          ## Saturday, June 13, 2026 - Data Tutorials. Location: KOBL 352
          - **08:30-09:00** Session 1
          - **09:00-09:30** 
          - **10:00-10:30** Break
          - **10:30-11:00** Session 2
          - **11:00-11:30** 
          - **12:00-12:30** Lunch Break
          - **13:30-14:00** Session 3 
          - **14:00-14:30** 
          - **15:00-15:30** Break
          - **15:30-16:00** Session 4 
          - **16:00-16:30** 

          ## Sunday, June 14, 2026 - Infrastructure Tutorials. Location: KOBL 352
          - **08:30-09:00** Session 5 
          - **09:00-09:30** 
          - **10:00-10:30** Break
          - **10:30-11:00** Session 6 
          - **11:00-11:30** 
          - **12:00-12:30** End 

          ## Thursday, June 18, 2026 - Hybrid SEED Day. Location: KOBL 352
          - **11:00-11:30** SEED Session 
          - **13:00-13:30** Transition to Boulder 
          - **16:00-16:30** Panel Session 
          - **17:30** Reception 

          ## Friday, June 19, 2026 - Sessions + NONA. Location: ECCS 201
          - **08:30-09:00** Breakfast
          - **09:00-09:30** Invited Speaker
          - **10:00-10:30** Coffee Break
          - **10:30-11:00** Session 1
          - **12:00-12:30** Lunch
          - **13:00-13:30** Session 2
          - **14:30-15:00** Coffee Break
          - **15:00-15:30** Nonatalks 
          - **16:00-16:30** Discussion 

          ## Saturday, June 20, 2026 - Closing Sessions. Location: ECCS 201
          - **08:30-09:00** Breakfast
          - **09:00-09:30** Invited Speaker
          - **10:00-10:30** Coffee Break
          - **10:30-11:00** Session 3
          - **12:00-12:30** Lunch
          - **13:00-13:30** Session 4
          - **14:30-15:00** Coffee Break
          - **15:00-15:30** Session 5
          - **16:30-17:00** Closing Remarks 
  # - block: markdown
  #   id: parking
  #   content:
  #     title: Parking
  #     text: |-
  #         ![Parking](parking.png)

  - block: contact
    id: contact
    content:
      title: Contact Us
      text: |-
        Interested in participating, organizing, or sponsoring IWBDA or Bio Innovation Week? Reach out to us for more information on how you can get involved in IWBDA, IWBMA, the Nona Works Hackathon, or SBOL Workshops. We look forward to hearing from you!
      email: bio.design.automation.inc@gmail.com

  - block: people
    id: organizing
    content:
      title: Organizing Committee
      user_groups:
      - Bio Innovation Week 2026
  
  - block: people
    id: program
    content:
      title: Program Committee
      user_groups:
      - Bio Innovation Week 2026 program

---
