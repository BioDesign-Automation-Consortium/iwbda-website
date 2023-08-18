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
    id: logistics
    content:
      title: Conference Logistics
      text: |- 
        # Location Details
        Bio-Design Week will be held at two main venues:
          - Boston University’s Center for Computing & Data Sciences, 665 Commonwealth Ave, Boston, MA 02215
          - Asimov, 201 Brookline Avenue, Boston, MA 02215
        # Hotels
        Hotels close to Boston University and Asimov during Bio-Design Week may be more expensive than usual due to a Red Sox-Yankees series happening during the same week. We recommend looking at hotels along the MBTA’s Green Line (B) or within a reasonable walking distance to Boston University. There are options over in the Longwood Medical area (~25 minute walk or ~15 min by public transportation). Hotels in Cambridge may also be less expensive, but would require a longer commute.
        # Parking
        If you require on-site parking, please let us know so we can explore some options to accommodate you. Please email [Traci](mailto:traci@asimov.com) with the specific dates that you would need parking.
        # Student funding
        We are working on securing funding for students traveling to Bio-Design Week from schools within the United States. Stay tuned for more information. This funding will be available to undergraduate and graduate students, and is intended to partially cover your travel expenses for your flights or train tickets, and/or your accommodations.
        # Registration is coming soon!
        Registration for Bio-Design Week will open next week (week of August 21st). Tickets will include access to IWBDA, community-driven workshops, and social events.
 
    design:
      columns: '2'

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
  - block: people
    content:
      title: Keynote Speakers
      user_groups:
      - Speakers
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
      - IWBDA
      - NonaWorks23

---
