
<!--

author:   Masub Makhdoom
email:    masub.makhdoom@ovgu.de
date:     20/09/2025
version:  30.0.0
language: en
narrator: UK English Female

repository: https://github.com/LiaScript/docs

logo:     img/logo.png

comment:  This document shall provide an entire compendium and course on the
          development of Open-courSes with [LiaScript](https://LiaScript.github.io).
          As the language and the systems grows, also this document will be updated.
          Feel free to fork or copy it, translations are very welcome...

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
          https://felixhao28.github.io/JSCPP/dist/JSCPP.es5.min.js

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

link: https://raw.githubusercontent.com/OVGU-VET-TechEd/Integrating_AI_in_TVET_UNESCO/refs/heads/main/VorlageUN.css

link:     https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css

import:   https://raw.githubusercontent.com/liaTemplates/ABCjs/main/README.md

link:     https://fonts.googleapis.com/css2?family=Noto+Sans+Egyptian+Hieroglyphs
          https://fonts.googleapis.com/css2?family=Noto+Sans+Ogham

font:     Noto Sans Egyptian Hieroglyphs, Noto Sans Ogham
-->
## <svg xmlns="http://www.w3.org/2000/svg" width="1800" height="1000" viewBox="0 0 1800 1000">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#F7FAFF"/>
      <stop offset="100%" stop-color="#EAF2FF"/>
    </linearGradient>

    <style>
      .h1{font:700 52px Arial, Helvetica, sans-serif; fill:#0F172A}
      .h2{font:700 36px Arial, Helvetica, sans-serif; fill:#0F172A}
      .h3{font:600 30px Arial, Helvetica, sans-serif; fill:#0F172A}
      .p{font:500 28px Arial, Helvetica, sans-serif; fill:#0F172A}
      .muted{fill:#334155}
      .chipText{font:700 26px Arial, Helvetica, sans-serif; fill:#0F172A}
    </style>

    <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="10" stdDeviation="12" flood-color="#0B1220" flood-opacity="0.18"/>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1800" height="1000" fill="url(#bg)"/>

  <!-- Top accent bar -->
  <rect x="0" y="0" width="1800" height="18" fill="#173A66"/>

  <!-- Main card -->
  <rect x="110" y="110" width="1580" height="780" rx="28" fill="#FFFFFF" filter="url(#shadow)"/>
  <rect x="110" y="110" width="1580" height="780" rx="28" fill="none" stroke="#173A66" stroke-width="3"/>

  <!-- Title -->
  <text x="170" y="210" class="h2">Institute of Vocational, Industrial and Business Education (IBBP)</text>

  <!-- Degree -->
  <text x="170" y="275" class="h3">Academic degree “Master of Science”</text>

  <!-- Program line -->
  <text x="170" y="350" class="p">Didactics and Learning Theories in Vocational Education and Training</text>

  <!-- Presence seminar chip -->
  <rect x="170" y="395" width="360" height="56" rx="16" fill="#E6EEF9" stroke="#173A66" stroke-width="2"/>
  <text x="190" y="433" class="chipText">Presence Seminar (6 CP)</text>

  <!-- Module -->
  <text x="170" y="525" class="p">
    Module 2: Structures and Theories of Technical and Vocational Education and Training
  </text>

  <!-- Seminar -->
  <text x="170" y="635" class="h1">Seminar: Focus Seminar for Vocational Education</text>

  <!-- Subtitle -->
  <text x="170" y="710" class="h2">VET 6.0 for Ind 5.0</text>

  <!-- Footer line -->
  <line x1="170" y1="780" x2="1630" y2="780" stroke="#CBD5E1" stroke-width="3"/>

  <!-- Names -->
  <text x="170" y="845" class="p muted">Lutz Thelen, Mahwish Kanwal, Masub Makhdoom</text>

  <!-- Bottom accent -->
  <rect x="110" y="872" width="1580" height="18" fill="#173A66" opacity="0.12"/>
</svg>


---

# Objectives

  --{{0}}--

This degree program has a strong international orientation and prepares students for higher-level positions in education and further education, particularly in international contexts. It opens career opportunities in vocational education research, training development, and international development cooperation.

<div style="display:flex; gap:22px; align-items:stretch; margin-top:16px;">

  <div style="flex:0 0 36%; border-radius:18px; padding:22px; color:#fff;
              background: linear-gradient(135deg, #0ea5e9, #6366f1);
              box-shadow: 0 10px 26px rgba(0,0,0,.15);">
    <div style="font-size:18px; letter-spacing:.12em; opacity:.9; text-transform:uppercase;">
      Program Focus
    </div>
    <div style="margin-top:12px; font-size:34px; font-weight:800; line-height:1.15;">
      International Orientation
    </div>

    <div style="margin-top:18px; padding:14px 16px; border-radius:14px;
                background: rgba(255,255,255,.16); border: 1px solid rgba(255,255,255,.25);">
      <div style="font-size:16px; opacity:.95;">Key idea</div>
      <div style="font-size:20px; font-weight:700; margin-top:6px;">
        Theory + Practice + Collaboration
      </div>
    </div>
  </div>

  <div style="flex:1; border-radius:18px; padding:22px; background:#ffffff;
              box-shadow: 0 10px 26px rgba(0,0,0,.10);
              border: 2px solid rgba(99,102,241,.18);">

    <div style="display:grid; gap:14px;">

      <div style="border-left:8px solid #22c55e; padding:12px 14px; border-radius:14px; background:#f0fdf4;">
        The degree course has an international orientation.
      </div>

      <div style="border-left:8px solid #0ea5e9; padding:12px 14px; border-radius:14px; background:#eff6ff;">
        It prepares the students for higher (or senior) positions in the field of education and further education (e.g. in European vocational educa-tion institutions or economic educational institutions), especially in an international context.
      </div>

      <div style="border-left:8px solid #f97316; padding:12px 14px; border-radius:14px; background:#fff7ed;">
        Positions in the field of training aids, research on vocational education or in the international development cooperation can also be pursued.
      </div>

      <div style="border-left:8px solid #a855f7; padding:12px 14px; border-radius:14px; background:#faf5ff;">
        The master's degree assures that the students dispose of the neces-sary knowledge and ability for the transition into the professional practice and are capable of applying scientific methods and concepts.
      </div>

      <div style="border-left:8px solid #e11d48; padding:12px 14px; border-radius:14px; background:#fff1f2;">
        The integrated internship ensures that the students gain competences in the field of international collaboration.
      </div>

    </div>

  </div>
</div>


 

---

# Career Perspectives

This internationally oriented study program prepares you for tasks in middle and superior management positions in the field of vocational education and training, e.g.

* Management and coordination of initial and further training especially at companies; with an international orientation
* Management of TVET projects in the context of international development cooperation and in international organizations
* Teaching in further education programs at national and international vocational education institutions
* Consulting, e.g. in the learning and teaching aids sector
* Development cooperation in international TVET policy contexts
* National and international TVET research

   --{{0}}--
This internationally oriented study program prepares you for middle and senior management positions in vocational education and training. Graduates can work in the management and coordination of initial and further training, especially in internationally oriented companies. Career opportunities include managing TVET projects in international development cooperation and organizations, teaching in national and international vocational education institutions, consulting in the learning and teaching aids sector, contributing to international TVET policy development, and conducting national and international vocational education research.

---

# Fields of activity

* Company management and coordination activities in the field of vocational education and training, particularly in internationally active companies

* Management activities for vocational training projects in international development cooperation and in international organizations

* Consulting and development work, e.g. in the teaching materials industry

---

# Fields of activity

* Teaching activities as a teacher in continuing vocational education and training programmes at business educational institutions and in international vocational training institutions

* Development work in vocational education and training policy in an international context

* National and international vocational training research

---

# Competencies and Interests Required



---

  ### Potential students should have a general interest in:

🟦 **Education and training processes** 

🟩 **Different topics in technical and vocational education and training**  

🟧 **TVET research**  

🟪 **International development cooperation** 

🟥 **International tasks in educational policy-making and administration**

---

💡 **Key competence:**  

Against this background, **intercultural competence and openness** are important key competences.


---

# Objectives of the Seminar
 ### The Student 

🟦 Have a deepened scientific understanding of central subject areas and issues of vocational and business education  

🟩 Can critically assess relevant research results and current know-how and practice in vocational education and training  

🟧 Can systematically and scientifically work on relevant topics and issues of vocational and business education to contribute to theory development  

🟪 Have a pedagogically reflected understanding of key characteristics of and developments in vocational education and training  

🟥 Can describe, compare and assess national and international developments in vocational education and training  

🟨 Can describe and discuss traditional and current concepts and theories of vocational education and training and assess their significance for the development of vocational education and training



---

# Objectives of the Seminar

Students …

* Understand the central theories and structures of vocational education and training (VET) and its development from Industry 4.0 to 5.0.
* Develop their own project (classical, agile or a hybrid form) that implements innovative educational concepts for Industry 5.0
* Use tools such as Loopy to visualise system relationships and analyse feedback loops in education systems
* Apply systems thinking with LOOPY to understand the interactions between technology, education and society.

---

# Seminar content

* Industry 5.0
* World of work 2030 and 2040
* VET 6.0 for Ind 5.0, VET 2030
* Influence of AI for teaching, learning and working processes
* Development and status quo of vocational education and training
* Modernization of vocational education and training 
* Educational and vocational training theories
* Specialization of aspects of the development of vocational education and training in Germany and worldwide, e.g. questions of financing, target groups in VET, transitions in VET, VET policy, etc.
* Vocational and business education research


---
# Didactic principles of the seminar

* Matching theory with and from practice
* Linking examples with the abstraction
* Legitimation of content with practice ("What for and why do you need this?" must always be able to be answered)
* Case Work, e.g. (technology, QF-Competency level, didactic considerations, Curriculum Legitimation)
* Alternation of lecture, individual work, partner work, group work, plenary session, homework

# Digitally supported learning

* Functionally in this seminar by using videoconferencing, Moodle as a working platform and virtual communication
Click 👇 

* [LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/Mahwish-Lia/Structure-and-Theories-of-TVET/main/Seminar%201%20_Version%202.md#1)
* [LOOPY](https://idp-serv.uni-magdeburg.de/idp/profile/SAML2/Redirect/SSO?execution=e1s2)
* [MIRO](https://miro.com/de/)


---

# Elaboration for the seminar and service provision

<div style="display:flex; gap:22px; align-items:stretch; margin-top:18px;">

  <!-- Left panel -->
  <div style="flex:0 0 38%; border-radius:18px; padding:22px; color:#ffffff;
              background: linear-gradient(135deg, #22c55e, #0ea5e9);
              box-shadow: 0 12px 28px rgba(0,0,0,.16);">

    

  </div>

  <!-- Right panel -->
  <div style="flex:1; border-radius:18px; padding:22px; background:#ffffff;
              box-shadow: 0 10px 26px rgba(0,0,0,.10);
              border: 2px solid rgba(14,165,233,.18);">

    <div style="display:grid; gap:18px;">

      <div>
        <h3 style="margin:0 0 10px 0; color:#0f172a;">Final Assessment</h3>

        <div style="display:grid; gap:10px;">
          <div style="border-left:8px solid #22c55e; padding:12px 14px; border-radius:14px; background:#f0fdf4;">
            Taking on a project task and working it out
          </div>

          <div style="border-left:8px solid #0ea5e9; padding:12px 14px; border-radius:14px; background:#eff6ff;">
            Active participation in project teams
          </div>

          <div style="border-left:8px solid #f97316; padding:12px 14px; border-radius:14px; background:#fff7ed;">
            Design thinking loops for case analysis
          </div>
        </div>
      </div>

      <div>
        <h3 style="margin:18px 0 10px 0; color:#0f172a;">Evaluation criteria</h3>

        <div style="display:grid; gap:10px;">
          <div style="border-left:8px solid #a855f7; padding:12px 14px; border-radius:14px; background:#faf5ff;">
            Professionally correct
          </div>

          <div style="border-left:8px solid #22c55e; padding:12px 14px; border-radius:14px; background:#f0fdf4;">
            Professional terminology
          </div>

          <div style="border-left:8px solid #0ea5e9; padding:12px 14px; border-radius:14px; background:#eff6ff;">
            Form and references
          </div>

          <div style="border-left:8px solid #f97316; padding:12px 14px; border-radius:14px; background:#fff7ed;">
            Independent performance
          </div>

          <div style="border-left:8px solid #e11d48; padding:12px 14px; border-radius:14px; background:#fff1f2;">
            Stringent thoughts
          </div>

          <div style="border-left:8px solid #14b8a6; padding:12px 14px; border-radius:14px; background:#f0fdfa;">
            Citation according to APA-standard
          </div>

          <div style="border-left:8px solid #6366f1; padding:12px 14px; border-radius:14px; background:#eef2ff;">
            
          </div>
        </div>
      </div>

    </div>

  </div>
</div>

---

# Criteria for final seminar works

* New, complex task and problem
* Autonomous management of processes in a strategy-oriented field of occupational activity
* Requirement structure is characterised by frequent and unpredictable changes
* Comprehensive, detailed, specialist and up-to-date knowledge in a technical specialism
* Specialised conceptual skills for solving strategic problems in a specific field
* Define objectives for new application or research-oriented tasks while reflecting on potential social, economic and cultural implications, and autonomously access knowledge required for this purpose.

* [APA-citation](https://apastyle.apa.org/?utm_source=apa.org&utm_medium=referral&utm_content=/&utm_term=header)

---

# Seminar Focus

<div style="display:flex; gap:22px; align-items:stretch; margin-top:18px;">

  <!-- Highlight panel -->
  <div style="flex:0 0 40%; border-radius:18px; padding:24px; color:#ffffff;
              background: linear-gradient(135deg, #6366f1, #0ea5e9);
              box-shadow: 0 14px 30px rgba(0,0,0,.18);">

   

  </div>

  <!-- Content panel -->
  <div style="flex:1; border-radius:18px; padding:24px; background:#ffffff;
              box-shadow: 0 10px 26px rgba(0,0,0,.10);
              border: 2px solid rgba(99,102,241,.18);">

    <div style="display:grid; gap:16px; font-size:20px; line-height:1.55; color:#0f172a;">

      <div style="border-left:8px solid #22c55e; padding:14px 16px; border-radius:14px; background:#f0fdf4;">
        The focus is on developing future-oriented vocational education and training (VET 6.0) in response to the challenges posed by Industry 4.0 and 5.0.
      </div>

      <div style="border-left:8px solid #f97316; padding:14px 16px; border-radius:14px; background:#fff7ed;">
        The event combines theoretical principles with practical application and promotes students' ability to analyse complex systems and develop innovative educational concepts.
      </div>

    </div>

  </div>
</div>




---

# Dates and topics



| Date       | Topic |
|------------|-------|
| 2026-01-10 | Welcoming, Introduction & Briefing (6h) |
| 2026-01-11 | Analyzing Current VET Limitations & Envisioning VET 6.0 (6h) |
| 2026-01-17 | Idea Generation & Prototyping (6h) |
| 2026-01-18 | Prototyping & Development (6h) |
| 2026-01-24 | Final Presentation (4h) |


# Options for VET 6.0
 ## Case 1:
>Requirements for vocational training VET 6.0 for Ind 5.0

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture_focus.png?raw=true)



# Options for VET 6.0
 ## Case 2: 
>Vision Statement: By 2040, VET has dissolved the boundaries between learning, working, and living

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture_focus2.png?raw=true)


# Starting Point
The event begins with a source analysis or expert interview on Industry 4.0 and 5.0. This analysis serves as a basis for deriving the requirements for vocational education and training (VET 6.0). The results are discussed in the seminar and used for further project work.

# Sustainability as a benchmark
![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture_focus3.png?raw=true)



# Types of project management

* Conventional PM
* Agile PM
* Mixed types
* Learning projects (Frey, Kersten Reich)

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture_focus4.png?raw=true)

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture_focus5.png?raw=true)

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture_focus6.png?raw=true)

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture_focus7.png?raw=true)

# Project Phase

* Development of a project (classical, agile or hybrid) for the implementation of VET 6.0
* Formation of project teams with tasks and roles
* Setup of a DMS in Moodle
* Use of tools such as Loopy and Miro to visualise system relationships



# Requirements for the selecting and presentation of the learning situation VET 6.0

* Professional relevance according to action field analysis
* Competence expansion according to Qualification Framework
* Subject or learning medium
* Necessary equipment and teacher qualifications
* Required organisational structure for vocational training

# Examples of status quo action fields for VET 4.0

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture8.png?raw=true)

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture9.png?raw=true)

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture10.png?raw=true)

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Picture_focus11.png?raw=true)



---

# Conclusion

* Presentation of projects and discussion of results
* Reflection on the suitability of the chosen project methods and their transferability to real educational contexts in the future

# Contact Details
  ### Dr. Yuliya Nepomyashcha

  ### profLutz Thelen

Otto von Guericke University Magdeburg
Faculty of Human Sciences
Department of Vocational Education and Human Resources Development 

**yuliya.nepomyashcha@ovgu.de**

**lutz.thelen@ovgu.de**

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Prof.Lutz.png?raw=true)

![](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Dr.yuliya.png?raw=true)





