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
  
  - block: people
    id: panelists
    content:
      title: Panelists
      user_groups:
      - 2026 Panelists
  
  - block: people
    id: sponsors
    content:
      title: Sponsors
      user_groups:
      - 2026 sponsors

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
      #|-
          # <link rel="stylesheet" type="text/css" href="https://www.brownpapertickets.com/widget_v671.css" /> <DIV ID="bpt_eventbody"><CENTER><BR><BR>Brown Paper Tickets Ticket Widget Loading...<BR><BR><A HREF="https://www.brownpapertickets.com/event/6694087">Click Here</A> to visit the Brown Paper Tickets event page.</CENTER><BR><BR></DIV> <script src="https://www.brownpapertickets.com/eventwidget.js?event=6694087&nodescription=1" type="text/javascript" language="javascript"></script> <script src="https://www.brownpapertickets.com/widget_v671.js?event=6694087" type="text/javascript" language="javascript"></script>
    design:
      columns: '2'

  - block: markdown
    id: agenda
    content:
      title: Agenda
      text: |-
          ## Saturday, June 13, 2026 - IWBDA Tutorials. Location: KOBL 352
          - **08:30-10:00** Session 1
          - **10:00-10:30** Break
          - **10:30-12:00** Session 2
          - **12:00-13:30** Lunch Break
          - **13:30-15:00** Session 3 
          - **15:00-15:30** Break
          - **15:30-17:00** Session 4 

          ## Sunday, June 14, 2026 - IWBDA Tutorials. Location: KOBL 352
          - **08:30-10:00** Session 5 
          - **10:00-10:30** Break
          - **10:30-12:00** Session 6
          - **12:00-12:30** End

          ## Thursday, June 18, 2026 - IWBDA Workshop. Location: KOBL 352
          - **16:00-17:30** Panel Session 
          - **17:30** Reception

          ## Friday, June 19, 2026 - IWBDA Workshop. Location: ECCS 201
          - **08:30-09:00** Breakfast
          - **09:00-10:00** Invited Speaker: Domitilla Del Veccio - Title TBD
          - **10:00-10:30** Coffee Break
          - **10:30-12:00** *Design Rules for Programmable Genetic Systems* (Lukas Buecherl / Eric Young)
              - **10:30 - 10:45** Masayuki Yamamura, *Rule based generation of synthetic genetic circuits - towards v 3.0*
              - **10:45 - 11:00** Ayush Pandey, *Formal specifications for the compositional design of synthetic biological circuits*
              - **11:00 - 11:15** Olivia Gallup and Harrison Steel, *Generative models for RNA genetic circuit design identify functional architectures*
              - **11:15 - 11:30** Zoila Jurado, Geoffrey Taghon and Samuel W. Schaffter, *Towards interoperable modeling of toehold mediated strand exchange circuits across DNA nanotechnology and engineering biology*
              - **11:30 - 11:45** Zachary Hastings, Zoila Jurado, Bingqing Hu, Zhen Zhang, Samuel W. Schaffter and Lukas Buecherl, *Host Aware Design of Cellular ctRSD Circuits*
              - **11:45 - 12:00** Stephen Chiu and Tae Seok Moon, *Dynamic control of metabolic flux by RNA based genetic circuits designed, built, and tested through automation*

          - **12:00-13:00** Lunch
          - **13:00-14:30** *AI, Curation, and Closed Loop Biological Discovery* (Zhen Zhang / Martín Gutiérrez)
              - **13:00 - 13:15** Niloofar Arazkhani and Natasa Miskov Zivanov, *BELL: Biomodel Evidence and LLM based Logic*
              - **13:15 - 13:30** Haomiao Luo, Niloofar Arazkhani, Difei Tang and Natasa Miskov Zivanov, *VIOLIN WEB: a web application for reconciliation and curation of molecular interaction graphs*
              - **13:30 - 13:45** Jack Dalton, *Evolution Co scientists for automated ALE*
              - **13:45 - 14:00** Robin Henry, Harrison Steel and Jean Baptiste Lugagne, *Myriad: A GPU Accelerated Platform for In Silico Prototyping of Closed Loop Single Cell Experiments*
              - **14:00 - 14:15** Bryan Tegomoh, *AI Powered Genomic Surveillance as Biodesign Automation: Lessons from Operationalizing Pathogen Detection Pipelines at Scale*
              - **14:15 - 14:30** Difei Tang and Natasa Miskov Zivanov, *CELESTA Web: An Interactive Tool for LLM Enhanced Biomedical Context Annotation*

          - **14:30-15:00** Coffee Break
          - **15:00-16:00** Nona talks 
          - **16:00-17:00** DevCell Discussion

          ## Saturday, June 20, 2026 - IWBDA Workshop. Location: ECCS 201
          - **08:30-09:00** Breakfast
          - **09:00-10:00** Invited Speaker: Emma Chory - [Navigating the Evolution Multiverse: Real-time evolution and open-source robotic platforms for engineering biology](/post/emma-chory-2026/)
          - **10:00-10:30** Coffee Break
          - **10:30-12:00** *Predictive Models of Emergent Biochemical Dynamics* (Harrison Steel / Brian Munsky)
              - **10:30 - 10:45** Colin Yancey, *EmergeX: A computational framework for designing emergent dynamics in chemical reaction networks*
              - **10:45 - 11:00** Quang Luan Dang Tran, Nguyen H.N. Tran, Derrick Osei and Ania Ariadna Baetica, *Performance of Metaheuristic Algorithms in Finding Tradeoffs in One and Two Species Biological Feedback*
              - **11:00 - 11:15** Nguyen Tran, Ania Ariadna Baetica and Samuel Schaffter, *Predictive Analysis of Amplification in Biochemical Feedback Circuits*
              - **11:15 - 11:30** Payton Thomas, Johanna Cao, Caleb Wong and Jeff Hasty, *Engineered Critical Point Dynamics in Genetic Circuits*
              - **11:30 - 11:45** Zachary Hastings and Lukas Buecherl, *Physics Informed Inference of Gene Expression Kinetics Using bioCRNpyler*
              - **11:45 - 12:00** Dimitris Papamichail, Bang Chiem and Georgios Papamichail, *Codon Pair Optimization Web Tool*
          - **12:00-13:00** Lunch
          - **13:00-14:30** *Measurement, Microphysiology, and Living Experimental Platforms* (Jeanet Mante / Gonzalo Vidal)
              - **13:00 - 13:15** Vicente Trelles Fernandez and Harrison Steel, *Novel Microfluidic Chips for Massively Parallelised Biological Data Acquisition*
              - **13:15 - 13:30** Nona Hashemi, Mahdi Hasanzadeh Hesar and Samuel M.D. Oliveira, *Microfluidic Physics Constrained Agent Based Modeling of Artificial Microbial Biofilms*
              - **13:30 - 13:45** Harman Mehta, Yusuf Ugurluoglu, Meng Zhang, Martyn Dade Robertson and Harrison Steel, *Microbial 3D Bioprinter for Novel Living Materials*
              - **13:45 - 14:00** Niall McIntyre and Nick Brooks, *Manufacturing a high throughput, label free platform for rapid screening of drug permeation across in vitro plasma membrane models*
              - **14:00 - 14:15** Evan Holbrook, Elizabeth Codd, Ron Weiss and David Kong, *TransfectionWizard: An Integrated Open Source Platform for Genetic Circuit Design and Automated Mammalian Cell Liposome Transfection for the Lab and Classroom*
              - **14:15 - 14:30** Radhakrishna Sanka, Akhilesh Maithi, Charan Manikanta and Mani Vashisth, *Pegasus: A Distributed Research Platform*
          - **14:30-15:00** Coffee Break
          - **15:00-16:15** *From Standards to Buildable Biology* (David Ross / Tae Seok Moon)
              - **15:00 - 15:15** Doug Densmore, Chris Krenz, and Guzman Vigliecca, *Biodesign Metadata Exchange for Use in Biosecurity*
              - **15:15 - 15:30** Gonzalo Andrés Vidal Peña et al., *Standardized Synthetic Biology Data Curation Effort*
              - **15:30 - 15:45** Travis Uhrig and Chris Myers, *Adding SBML Modeling Support to SBOLCanvas*
              - **15:45 - 16:00** Jeanet Mante, *From Design to Build: Sequence Domestication, Robotic Assembly, and Integrated SBOL Data Capture*
              - **16:00 - 16:15** Sergey Rock Ingram and Lukas Buecherl, *Five Cellular Limits for Deployable Synthetic Biology and Design Automation*

          - **16:15-16:45** Closing Remarks

  - block: markdown
    id: venue
    content:
      title: Conference Venue
      text: |-
          ![Parking](cuparking.png) 
          <p>
            Visitors to campus may park in hourly pay-to-park lots located throughout campus.
            Campus pay-to-park lot locations are included on the CU Boulder
            <a href="https://www.colorado.edu/map/?id=336#!ce/2739?ct/20989,20990,20991,20992,20993,20994,26118,2739?mc/40.00563459437513,-105.2595376968384?z/16?lvl/0">
            campus interactive map</a>.
          </p>

  - block: people
    id: organizing
    content:
      title: Organizing Committee
      user_groups:
      - Bio Innovation Week 2026
  
  # - block: people
  #   id: program
  #   content:
  #     title: Program Committee
  #     user_groups:
  #     - Bio Innovation Week 2026 program
  
  - block: markdown
    id: program
    content:
      title: Program Committee
      text: |
          - [Lukas Bücherl](https://engineering.usu.edu/be/people/faculty/buecherl-lukas) Utah State University
          - [David J. Ross (Fed)](https://www.nist.gov/people/david-j-ross) NIST
          - [Aaron Adler](https://www.linkedin.com/in/adadler/) BBN
          - [Martín Gutiérrez](https://servicios.urjc.es/pdi/ver/martin.gutierrez) Universidad Rey Juan Carlos
          - [Caleb Bashor](https://profiles.rice.edu/faculty/caleb-bashor) Rice University
          - [Zhen Zhang](https://engineering.usu.edu/ece/people/faculty/zhang-zhen) Utah State University
          - [Harrison Steel](https://eng.ox.ac.uk/people/harrison-steel) University of Oxford
          - [Daisuke Kiga](https://kigalab.w.waseda.jp/) Waseda University
          - [Jake Beal](https://www.linkedin.com/in/jake-beal/) BBN
          - [Tae Seok Moon](https://www.jcvi.org/about/tae-seok-moon) J. Craig Venter Institute
          - [Eric Young](https://www.wpi.edu/people/faculty/emyoung) Worcester Polytechnic Institut (WPI)
          - [William Mo](https://geneticlogiclab.org/author/william-mo/) CU Boulder
          - [Carolus Vitalis](https://geneticlogiclab.org/author/carolus-vitalis/) CU Boulder
          - [Prashant Vaidyanathan](https://www.linkedin.com/in/prashant-vaidyanathan/) Oxford Biomedica
          - [Brian Munsky](https://www.engr.colostate.edu/~munsky/meet-the-team/) Colorado State University
          - [Jeanet Mante](https://geneticlogiclab.org/author/jet-mante/) Army Research Lab
          - [Nicholas Roehner](https://www.linkedin.com/in/nicholas-roehner-16819b151/) BBN
          - [Pete Carr](https://www.linkedin.com/in/peter-carr-5a60431b/) BBN
          - [Traci Haddock](https://www.linkedin.com/in/tracihaddock/) Asimov
          - [Christian Hochberger](https://www.rs.tu-darmstadt.de/ueber-uns/mitarbeiter/christian-hochberger) TU Darmstadt
          - [Joshua Chan](https://www.engr.colostate.edu/bce/people/joshua-chan/) Colorado State University

  
  - block: contact
    id: contact
    content:
      title: Contact Us
      text: |-
        Interested in participating, organizing, or sponsoring IWBDA or Bio Innovation Week? Reach out to us for more information on how you can get involved in IWBDA, IWBMA, the Nona Works Hackathon, or SBOL Workshops. We look forward to hearing from you!
      email: bio.design.automation.inc@gmail.com
      contact_links:
        - icon: clock
          icon_pack: fas
          name: Previous Years
          link: '/previous-years/'
        - icon: book
          icon_pack: fas
          name: Previous Special Issues
          link: '/special-issues/'
---
