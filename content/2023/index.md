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

  - block: people
    id: keynote
    content:
      title: Keynote Speaker
      user_groups:
      - Speakers

  - block: markdown
    id: registration
    content:
      title: Registration
      text: |- 
        <link rel="stylesheet" type="text/css" href="https://www.brownpapertickets.com/widget_v671.css" /> <DIV ID="bpt_eventbody"><CENTER><BR><BR>Brown Paper Tickets Ticket Widget Loading...<BR><BR><A HREF="https://www.brownpapertickets.com/event/6126340">Click Here</A> to visit the Brown Paper Tickets event page.</CENTER><BR><BR></DIV> <script src="https://www.brownpapertickets.com/eventwidget.js?event=6126340&nodescription=1&notitle=1" type="text/javascript" language="javascript"></script> <script src="https://www.brownpapertickets.com/widget_v671.js?event=6126340" type="text/javascript" language="javascript"></script>
    design:
      columns: '2'

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
    id: agenda
    content:
      title: Agenda
      text: |- 
        # Bio-Design Week - September 11-14, 2023

          ## Monday, September 11 - 665 Commonwealth Avenue, 17th Floor

          - **08:00-09:00** Registration and breakfast
          - **09:00-09:10** Welcome and kick-off of Bio-Design Week
          - **09:10-10:30** Workshop: SBOL Data Model
          - **10:30-11:00** Coffee break
          - **11:00-12:30** Workshop: SBOL Visual
          - **12:30-13:30** Lunch
          - **13:30-15:00** Workshop: Programmatic genetic design automation using LOICA
          - **15:00-15:30** Coffee break
          - **15:30-17:00** Nona Works Team Building and Mixer

          ## Tuesday, September 12 - 665 Commonwealth Avenue, 17th Floor

          - **08:00-09:00** Registration and breakfast
          - **09:00-09:10** Welcome to IWBDA
          - **09:10-10:15** IWBDA Talks: Sequence Manipulation and Gene Expression
              - 09:10-09:30 **Energy Aware Technology Mapping.** Erik Kubaczka, Tobias Schwarz, Jérémie Marlhens, Maximilian Ge, Nicolai Engelmann, Christian Hochberger and Heinz Koeppl.
              - 09:30-09:50 **Local RNA Feedback: More Logic, Less Leakage.** Nicolai Engelmann, Maik Molderings and Heinz Koeppl.
              - 09:50-10:10 **Using learned representations of genetic circuits to evaluate sequence-level mutations.** Olivia Gallup and Harrison Steel.
              - 10:10-10:15 *Lightning Talk*
                  - **Multi-Site Mutagenic Protein Library Design with Controlled Annealing Temperature.** Yehuda Binik, Ayesha Chaudry, Akira Takada, Georgios Papamichail and Dimitris Papamichail.
          - **10:15-10:45** Coffee break
          - **10:45-11:45** Keynote: Dr. Nicole Wheeler
              - Dr. Nicole Wheeler is a Turing Fellow at the University of Birmingham and also serves as a technical consultant for the Nuclear Threat Initiative. Dr Wheeler’s work focuses on the development of computational screening tools for identifying DNA from emerging biological threats, establishing genomic pathogen surveillance in resource-limited settings, One Health surveillance of antimicrobial resistance, and the ethical development of artificial intelligence (AI) for health applications...
          - **11:45-13:00** Lunch
          - **13:00-14:00** IWBDA Talks: Biosecurity
              - 13:00-13:20 **Biological Malware Detector.** Muntaha Samad, Dan Wyschogrod and Jacob Beal.
              - 13:20-13:40 **DNA Editing Game (DEGA) Theory.** Nicholas Roehner.
              - 13:40-14:00 **Splicing-based Biocontainment Devices.** Allison Taggart, Miles Rogers and Jacob Beal.
          - **14:00-14:30** Coffee break
          - **14:30-16:00** Biosecurity Panel and Discussion Session
              - We are pleased to announce that IWBDA will host a biosecurity panel with panelists Dr. Nicole Wheeler and Dr. Peter Carr, moderated by Dr. Jacob Beal. This panel will explore the relationship between design tools and biosecurity.

              - **Dr. Peter Carr** is a Senior Scientist at the Massachusetts Institute of Technology’s Lincoln Laboratory, where he leads the Synthetic Biology research program. His research interests include genome engineering, rapid prototyping of both hardware and wetware, DNA synthesis and error correction, and biosecurity. He is the Director of Judging for the International Genetically Engineered Machine (iGEM) competition and a founding member of the Synthetic Biology Center at MIT. He received his bachelor’s degree in Biochemistry from Harvard, and his PhD in Biochemistry and Molecular Biophysics from Columbia University.

              - **Dr. Jacob Beal** is an Engineering Fellow at Raytheon BBN and is the lead developer for FAST-NA Scanner, a signature-based biosecurity screening tool used by multiple DNA synthesis companies. He also co-led the IGSC's Regulated Pathogen Database update, and is co-organizing international standards for testing biosecurity sequence screening systems.

          - **16:00-16:30** Discussion summary
          - **16:30-17:00** Break and travel time to dinner
          - **17:00-20:00** Dinner at Sunset Cantina

          ## Wednesday, September 13 - 201 Brookline Avenue, 4th Floor

          - **08:30-09:00** Breakfast
          - **09:00-10:05** IWBDA Talks: Modeling
              - 09:00-09:20 **A Collection of Biological Models for the Development of Infinite-State Stochastic Model Checking Tools.** Lukas Buecherl, Payton J. Thomas, Mohammad Ahmadi, Josh Jeppson, Andrew Gerber, Eric Reiss, Chris Winstead, Hao Zheng, Zhen Zhang and Chris J. Myers. 
              - 09:20-09:40 **A neural-mechanistic hybrid approach improving the predictive power of genome-scale metabolic models.** Bastien Mollet, Jean-Loup Faulon, Léon Faure and Wolfram Liebermeister. 
              - 09:40-10:00 **Knowledge-Based Pathway Extraction and Verification.** Gaoxiang Zhou and Natasa Miskov-Zivanov. 
              - 10:00-10:05 *Lightning Talk:* 
                  - **Model Checking of Interval Discrete-Time Markov Chain for Biochemical Pathways.** Krishnendu Ghosh. 

          - **10:05-10:35** Coffee break
          - **10:35-11:40** IWBDA Talks: Genetic Design
              - 10:35-10:55 **Guided Design of Genetic Circuits Exploiting Stochastic Model Verification.** Lukas Buecherl, Mohammad Ahmadi, Hao Zheng and Chris J. Myers. 
              - 10:55-11:15 **Design-Build-Test-Learn of Sponge RNAs for Synthetic Gene Circuits.** Scott Stacey, Harrison Steel and Antonis Papachristodoulou. 
              - 11:15-11:35 **Rule-based generation of synthetic genetic circuits.** Masayuki Yamamura, Ryoji Sekine, Kazuteru Miyazaki, Sota Okuda, Naoki Kodama and Daisuke Kiga.
              - 11:35-11:40 *Lightning Talk:*
                  - **Analysis of ASR inducible promoter in different conditions in *Escherichia coli*.** Maria Jose Mesa-Rodriguez, Domenica Cuneo-Campodonico, Martin Gutierrez and Alberto J. Donayre-Torres. 

          - **11:40-13:00** Lunch

          - **13:00-13:30** Invited Talk: Kernel and Simulator 
          - **13:30-14:30** Discussion session: Topic TBD
          - **14:30-15:00** Coffee break
          - **15:00-15:30** Discussion summary
          - **15:30-16:30** IWBDA Talks: Automating Evolution
              - 15:30-15:50 **Long-term evolution of bacteria for maximal growth rate.** Antoine Vigouroux and Johan Paulsson. 
              - 15:50-16:10 **Engineering Continuous Directed Evolution with Single Cell Optogenetic Selection and Microfluidics.** Jess James, Sebastian Towers, Idris Kempf, Jingyu Wang, Jakob Foerster and Harrison Steel. 
              - 16:10-16:30 **An Automated Platform for Accelerating Adaptive Laboratory Evolution.** Marco Corrao and Harrison Steel. 

          - **16:30-17:00** Late breaking lightning talks
          - **17:00-19:30** Networking Reception sponsored by Asimov

          ## Thursday, September 14 - 665 Commonwealth Ave, 17th Floor

          - **08:30-09:00** Breakfast
          - **09:00-09:45** Workshop: How to Write a Technical Note for ACS Synthetic Biology
          - **09:45-10:45** Nona Works: Presentations
          - **10:45-11:15** Coffee break
          - **11:15-12:20** IWBDA Talks: Machine Learning
              - 11:15-11:35 **SeqImprove: Machine Learning Assisted Curation of Genetic Circuit Sequence Information.** Zach Sents, Duncan Britt, William Mo and Chris J. Myers. 
              - 11:35-11:55 **Automated model curation using LLMs: Integration of ChatGPT with the DySE framework.** Emilee Holtzapple, Tanvi Verma and Natasa Miskov-Zivanov. 
              - 11:55-12:15 **Encoding Process Markers with Neural Networks to Simplify the Complexity of Engineering CAR T Cells.** Haomiao Luo, Anya Zivanov and Natasa Miskov-Zivanov. 
              - 12:15-12:30 *Lightning Talks:* 
                  - **How to build and train your ANN (In-Vivo) From zero to hero.** Tomás Fuentes Araya and Martín Gutiérrez. 
                  - **AI algorithms for classification and generation of spatial/temporal patterns in cell colonies.** Valeria Navarrete, Freddy Aguilar and Martín Gutiérrez. 
                  - **Using Machine Learning to Infer RNA Velocity Fields.** Taos Transue and Payton Thomas. 

          - **12:30-13:30** Lunch and Nona Works Voting
          - **13:30-14:30** Discussion Session: Topic TBD
          - **14:30-15:25** IWBDA Talks: Improving Workflows through Software
              - 14:30-14:50 **A Report on SynBio Data Management Practices.** Carolus Vitalis, Sai Samineni, Chris Myers and Pedro Fontanarrosa. 
              - 14:50-15:10 **Software for Synthetic Biology Workflows: How to Improve Your Productivity and Impact.** Chris J. Myers, Lukas Buecherl, Daniel Fang, Pedro Fontanarrosa, William Mo, Sai P. Samineni, Gonzalo Vidal, Carolus Vitalis, Guillermo Yanez-Feliu and Timothy J. Rudge. 
              - 15:10-15:25 *Lightning Talks:* 
                  - **DBTL Engineering cycle automation: Improving basic parts characterization in the Learn stage by Automation of the Test stage.** Yadira Boada, Anna Pushkareva, Harold Díaz-Iza, Andrés Arboleda-García, Jesús Picó and Alejandro Vignoni. 
                  - **PUDU: Simple Liquid Handling Robot Control for Synthetic Biology Workflows.** Gonzalo Andrés Vidal Peña, Carolus Vitalis, Matt Burridge, Lukas Buecherl, David Markham, Chris Myers and Timothy Rudge. 
                  - **A fully in-silico workflow for treating colon cancer with engineered cells: a study case.** Cristobal Hofmann, Francisco Salcedo and Martin Gutierrez. 

          - **15:25-15:45** Awards and Closing Remarks



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
      - IWBDA
      - NonaWorks23

---
