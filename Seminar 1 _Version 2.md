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






<style>
/* ============================================
   GLOBAL ENHANCED STYLING FOR LIASCRIPT
   ============================================ */

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.7;
}

h1 {
    background: linear-gradient(135deg, #1A237E 0%, #3949AB 50%, #5C6BC0 100%);
    color: white !important;
    padding: 30px 40px;
    border-radius: 20px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.3);
    margin: 30px 0;
    font-size: 2.5em;
    text-align: center;
    border-left: 8px solid #FFD700;
}

h2 {
    background: linear-gradient(135deg, #0A2647 0%, #205295 100%);
    color: white !important;
    padding: 20px 30px;
    border-radius: 15px;
    box-shadow: 0 6px 20px rgba(0,0,0,0.25);
    margin: 25px 0 15px 0;
    font-size: 1.8em;
    border-left: 6px solid #4FC3F7;
}

h3 {
    color: #0A2647;
    border-bottom: 3px solid #4FC3F7;
    padding-bottom: 10px;
    margin-top: 25px;
    font-size: 1.4em;
}

blockquote {
    background: linear-gradient(135deg, #E3F2FD 0%, #BBDEFB 100%);
    border-left: 6px solid #2196F3;
    padding: 20px 25px;
    margin: 20px 0;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    font-style: italic;
    color: #0D47A1;
}

ul, ol {
    line-height: 1.9;
    padding-left: 30px;
}

li {
    margin: 10px 0;
    padding-left: 5px;
}

strong {
    color: #0A2647;
    font-weight: 700;
}

a {
    color: #2196F3;
    text-decoration: none;
    border-bottom: 2px solid transparent;
    transition: all 0.3s ease;
}

a:hover {
    color: #0D47A1;
    border-bottom: 2px solid #2196F3;
}

code {
    background: #F5F5F5;
    padding: 3px 8px;
    border-radius: 5px;
    color: #D32F2F;
    font-family: 'Courier New', monospace;
}

pre {
    background: #263238;
    color: #AEDD94;
    padding: 20px;
    border-radius: 10px;
    overflow-x: auto;
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}

details {
    background: #FAFAFA;
    padding: 15px 20px;
    border-radius: 10px;
    margin: 15px 0;
    border-left: 5px solid #4CAF50;
    box-shadow: 0 3px 10px rgba(0,0,0,0.1);
}

summary {
    cursor: pointer;
    font-weight: 600;
    color: #1B5E20;
    padding: 10px;
    transition: all 0.3s ease;
}

summary:hover {
    color: #2E7D32;
    background: #E8F5E9;
    border-radius: 8px;
}

hr {
    border: none;
    height: 3px;
    background: linear-gradient(to right, #2196F3, #4CAF50, #FF9800);
    margin: 40px 0;
    border-radius: 3px;
}

table {
    border-collapse: collapse;
    width: 100%;
    margin: 25px 0;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    border-radius: 10px;
    overflow: hidden;
}

th {
    background: linear-gradient(135deg, #1976D2, #2196F3);
    color: white;
    padding: 15px;
    text-align: left;
    font-weight: 600;
}

td {
    padding: 12px 15px;
    border-bottom: 1px solid #E0E0E0;
}

tr:nth-child(even) {
    background: #F5F5F5;
}

tr:hover {
    background: #E3F2FD;
    transition: all 0.3s ease;
}

</style>



<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 50px; border-radius: 25px; text-align: center; box-shadow: 0 15px 35px rgba(0,0,0,0.3); margin: 30px 0;">
    <h1 style="color: white; font-size: 3em; margin: 0; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); background: none; padding: 0; box-shadow: none; border: none;">
        🎓 Module 2: VET Structures & Theories
    </h1>
    <p style="color: #FFE5B4; font-size: 1.3em; margin-top: 15px;">
        Seminar 1: Structures and Theories of TVET
    </p>
    <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 15px; margin-top: 25px;">
        <p style="color: white; margin: 0;">
            📚 Facilitator: Mr. Lutz Thelen<br>
            👥 Teaching Team: Mahwish Kanwal & Masub Makhdoom
        </p>
    </div>
</div>

# Welcome to Module 2

     --{{0}}--
Welcome to Module 2 Seminar 1, Today is the first session of the seminar , In this comprehensive session, we will explore vocational education and training in three blocks , 1) defining features of V E T, 2) classical German V E T theories, and 3) Educational theory transition from von Humboldt to Klafki.


Seminar 1: Structures and theories of Technical and Vocational
Education and Training (4 CPs)

Seminar 1 : 07-December-2025

Facilitator: Mr. Lutz Thelen

Teaching Assistants : Mahwish Kanwal and Masub Makhdoom


## Defining Features of Vocational Education and Training

     --{{0}}--
In Block 1, we examine V E T through three analytical perspectives: epistemological and pedagogical, system and institutional, and socioeconomic and labor market perspectives.



Three Perspectives:  Epistemological/Pedagogical perspective , Education System, Socioeconomic/Labor Market Perspectives


Duration for this block: ~30 minutes


Source: Cedefop (2017). The changing nature and role of vocational education and training in Europe, Vol. 1.

---

---

## Why Do We Need a Multi-Perspective View of VET?

     --{{0}}--
V E T is highly diverse and appears in different forms across countries and levels, A single definition cannot capture this complexity, which is why we need multiple analytical perspectives


- VET is described as **the least unitary of all education sectors**.  
- It appears in **different institutional forms**, at **different levels**, and in **formal, non-formal and informal settings**.
- Standard short definitions (for example, “preparation for occupations”) are **too broad** to capture:

  - How VET is organised,
  - Which types of knowledge it prioritises,
  - What functions it fulfils in the labour market and society.

Therefore, Cedefop proposes to analyse VET through **three partly overlapping perspectives**:

1. **Epistemological and pedagogical(-didactical) perspective**  
2. **System and institutional perspective (education system perspective)**  
3. **Socioeconomic and labour market perspective**

>These perspectives help us **structure the complexity** of VET and compare national conceptions over time.

---

## Overview: Three Perspectives on VET



<style>
  .color-slide {
    background: linear-gradient(135deg, #0A2647, #144272, #205295);
    padding: 35px;
    border-radius: 18px;
    color: #FFFFFF;
    box-shadow: 0 8px 18px rgba(0,0,0,0.25);
    margin: 20px 0;
  }
  .content-box {
    background: #FFFFFF;
    color: #0A2647;
    padding: 22px;
    border-radius: 14px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.12);
    margin-top: 15px;
  }
  .highlight {
    color: #FFD700;
    font-weight: bold;
  }
  .section-title {
    color: #E0F4FF;
    font-size: 26px;
    font-weight: bold;
    margin-bottom: 10px;
  }
</style>

<div class="color-slide">

<div class="section-title">🔍 Understanding the Three Perspectives of VET</div>

<details>
<summary style="cursor:pointer; font-size:20px; color:#E0F4FF;"><strong>Click to reveal content</strong></summary>

<div class="content-box">

     --{{0}}--
- German Vocational and training , especially the dual system, can be interpreted as a case where all three perspectives are strongly interlinked, The three perspectives are analytical tools, not three separate systems


- They address different questions:

  1. **Epistemological/pedagogical**:

     - *What kind of knowledge is central in VET?* 

     - *How is learning organised?*

  2. **System and institutional**:

     - *How is VET positioned and structured within the education system?*  

     - *Which providers, levels and governance arrangements exist?*

  3. **Socioeconomic/labour market**: 

     - *What functions does VET fulfil for the economy and society?*  

     - *How does it relate to work organisation and occupational structures?*

- **German VET**, especially the dual system, can be interpreted as a case where all three perspectives are **strongly interlinked**.

</div>
</details>

</div>


---

##  1. VET from an Epistemological and Pedagogical Perspective

Key idea: VET has a particular **knowledge base** and **learning logic**.

Two ideal-typical views of knowledge are distinguished:

1. **Cognitive view of knowledge**
2. **Tacit knowing view of knowledge**

These views are linked to different traditions of VET and different teaching–learning arrangements.

     --{{0}}--
!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Epistemological%20and%20Pedagogical%20Perspective%20.mp4?raw=true)
---

## Cognitive View of Knowledge

**Characteristics:**

- Knowledge is seen as:

  - **explicit**,
  - **abstract**,
  - **standardised**,
  - **impersonal**.
- Main form: **“know-that”** (information, rules, theories).
- Knowledge is primarily produced by **scientific disciplines**.
- Learning is often:
  - **teacher-centred**,
  - structured through **lectures and classroom teaching**,
  - assessed by **written tests and exams**.

**Implications for VET:**

- Stronger emphasis on **technical/theoretical content**.
- Often associated with **school-based** or **college-based** forms of VET.
- In German VET: this view is especially visible in the **vocational school (Berufsschule)** component of dual training.

---

## Tacit Knowing View of Knowledge


<style>
  .color-slide {
    background: linear-gradient(135deg, #0A2647, #144272, #205295);
    padding: 35px;
    border-radius: 18px;
    color: #FFFFFF;
    box-shadow: 0 8px 18px rgba(0,0,0,0.25);
    margin: 20px 0;
  }
  .content-box {
    background: #FFFFFF;
    color: #0A2647;
    padding: 22px;
    border-radius: 14px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.12);
    margin-top: 15px;
  }
  .section-title {
    color: #E0F4FF;
    font-size: 26px;
    font-weight: bold;
    margin-bottom: 10px;
  }
</style>

<div class="color-slide">

<div class="section-title">✨ Characteristics & Implications for VET</div>

<details>
<summary style="cursor:pointer; font-size:20px; color:#E0F4FF;"><strong>Click to reveal content</strong></summary>

<div class="content-box">

**Characteristics:**

- Knowledge is seen as:

  - **practical** (“know-how”),
  - **experience-based**,
  - **implicit** and **situational**,
  - strongly **personal** and **context-bound**.
- Learning means **“learning by doing”** in real or simulated work situations.
- Knowledge is developed through **participation in communities of practice** and socialisation into an occupation.

**Implications for VET:**

- Central role of **work-based learning**.
- Teaching focuses on **creating learning environments** rather than only transmitting information.
- Closely connected to the **master–apprentice tradition** and, in modern form, to **dual systems**.

In the German dual system, the tacit knowing view is particularly strong in the **company-based training** part of apprenticeship.

</div>
</details>

</div>


---

## Historical Roots of These Knowledge Traditions

Two historical lines contribute to modern VET:

1. **Craft tradition (master–apprentice)** 

   - Origin: **medieval craft guilds**.  
   - Young people work and learn under the supervision of a master.  
   - Transmission of **practical skills**, **professional norms**, and **occupational identity**.

2. **Technical-scientific tradition**  

   - Origin: **military and engineering academies** (17th–18th century).  
   - Separation of **engineering knowledge** from shop-floor work.  
   - Focus on **applied scientific knowledge** and formal instruction.

Modern VET – including German VET – often represents a **combination of both**: 

- practical, workplace-based learning **and** 

- systematic, school-based acquisition of theoretical knowledge.

---

## 2. VET from a System and Institutional Perspective

     --{{0}}--
!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Education%20System%20Perspective%20.mp4?raw=true)

<style>
  .color-slide {
    background: linear-gradient(135deg, #0A2647, #144272, #205295);
    padding: 35px;
    border-radius: 18px;
    color: #FFFFFF;
    border-radius: 18px;
    box-shadow: 0 8px 18px rgba(0,0,0,0.25);
    margin: 20px 0;
  }
  .content-box {
    background: #FFFFFF;
    color: #0A2647;
    padding: 24px;
    border-radius: 14px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.12);
    margin-top: 18px;
    font-size: 17px;
    line-height: 1.55;
  }
  .section-title {
    color: #E0F4FF;
    font-size: 26px;
    font-weight: bold;
  }
</style>

<div class="color-slide">

<div class="section-title">🏛️ System & Institutional Perspective</div>

<div class="content-box">

Here the focus shifts from knowledge to **institutions and structures**.

**Key questions:**

- At which **levels of education** is VET located?
- Which **types of providers** are involved (schools, companies, colleges, training centres)?
- How is VET **governed and financed**?
- What is the **legal status** of learners (pupils, students, apprentices, workers)?

**VET can be viewed as:**

- a **sector** of the education system,
- a **system** of programmes and providers,
- an **organisational field** with multiple actors (state, social partners, providers, learners),
- and even a specific **educational culture**.

</div>

</div>


---

## Changes in the Statistical Definition of VET (ISCED)

International classification (ISCED) illustrates shifts in how VET is viewed:

- **1977**:

  - No explicit definition of VET.
  - VET only indirectly visible by combining **level of education** and **field of education**.

- **1997**:

  - VET defined as education mainly preparing for **employment in specific occupations or trades**.
  - Introduction of **programme orientation** (general / pre-vocational / vocational) and **destination** (labour market / access to higher education).

- **2011**:

  - VET defined as programmes designed for **occupation-specific knowledge, skills and competences**, often with **work-based components**.
  - Addition of **type of qualification** (full/partial); intention to distinguish **academic vs. professional** at higher levels.

Consequences:

- VET is **no longer confined to the “middle level”**.  
- There are VET programmes at **lower secondary, upper secondary, post-secondary and tertiary levels**.
- For analysis, it is important to ask:

  - Is VET in a given country **mainly associated with lower/middle levels**,  
  - or does it include **substantial higher-level/professional programmes**?

---

## Institutional Features with High Diagnostic Value

  

<style>
  .pro-slide {
    background: linear-gradient(135deg, #0A2647 0%, #144272 40%, #205295 100%);
    padding: 40px;
    border-radius: 22px;
    color: #FFFFFF;
    box-shadow: 0 10px 22px rgba(0,0,0,0.28);
    margin: 25px 0;
  }
  .pro-title {
    font-size: 30px;
    font-weight: bold;
    color: #E0F4FF;
    margin-bottom: 15px;
  }
  .pro-box {
    background: #FFFFFF;
    color: #0A2647;
    padding: 26px;
    border-radius: 16px;
    box-shadow: 0 6px 16px rgba(0,0,0,0.15);
    font-size: 17px;
    line-height: 1.58;
  }
  .pro-divider {
    height: 3px;
    background: linear-gradient(to right, #144272, #205295, #0A2647);
    margin: 18px 0;
    border-radius: 2px;
  }
  .pro-subtitle {
    font-size: 20px;
    font-weight: bold;
    color: #144272;
    margin-bottom: 8px;
  }
</style>



<div class="pro-title">🏛️ System & Institutional Features of VET</div>



From a system and institutional perspective, important features include:

<div class="pro-divider"></div>

  ### ⭐ Dominant levels of VET
- **Dominant level(s)** of VET (lower, upper, post-secondary, tertiary).

<div class="pro-divider"></div>

   ### 👥 Age structure
- **Age structure** of participants (adolescents vs. adults → link to lifelong learning).

<div class="pro-divider"></div>

   ### 📜 Legal status of learners
- **Legal status** of learners:
  - pupils/students,
  - employees,
  - apprentices with a special status.

<div class="pro-divider"></div>

     ### 🏫 Types of providers
- **Types of providers**:
  - general and vocational schools,
  - companies (work-based training),
  - specialised VET colleges,
  - further education providers.

<div class="pro-divider"></div>

   ### 🏢 Governance and funding
- **Governance and funding**:
  - State-dominated,
  - shared responsibility between state and social partners,
  - strong role of employers and labour market institutions.

<div class="pro-divider"></div>

In Germany, for example, the dual IVET system is placed mainly at **upper secondary level**, with **shared governance** (state + social partners) and a **company-based training component** financed largely by enterprises.





---

## 3. VET from a Socioeconomic and Labour Market Perspective

    --{{0}}--
!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/VET%20form%20socioeconomic%20perspective.mp4?raw=true)


This perspective focuses on the **functions of VET** in the labour market and society.

VET contributes to:

- **social stratification** and career pathways,
- the **supply of skills** for companies and sectors,
- the **matching** between education and employment,
- the **reproduction and transformation of occupational practices**,
- individuals’ **entry into and progression within** working life.

VET can be analysed using different models of labour markets and work organisation. One important distinction is between **organisational space** and **occupational space**.

---

## Organisational Space vs. Occupational Space

### Dominance of Organisational Space

- Firms organise work **idiosyncratically**, according to internal needs.
- Many workers **do not have formal vocational qualifications**.
- Skills are often acquired through **short in-house training** and **on-the-job learning**.
- IVET at upper secondary level is often **weak or remedial**.
- Wage differences between unskilled, skilled and professional workers can be **large**.
- Examples (ideal-typical, not pure): **France, United Kingdom, United States, Japan**.

### Dominance of Occupational Space



<style>
  .lm-slide {
    background: linear-gradient(135deg, #0A2647 0%, #144272 40%, #205295 100%);
    padding: 40px;
    border-radius: 22px;
    color: #FFFFFF;
    box-shadow: 0 10px 22px rgba(0,0,0,0.28);
    margin: 25px 0;
  }
  .lm-title {
    font-size: 30px;
    font-weight: bold;
    color: #E0F4FF;
    margin-bottom: 15px;
  }
  .lm-box {
    background: #FFFFFF;
    color: #0A2647;
    padding: 26px;
    border-radius: 16px;
    box-shadow: 0 6px 16px rgba(0,0,0,0.15);
    font-size: 17px;
    line-height: 1.58;
  }
  .lm-divider {
    height: 3px;
    background: linear-gradient(to right, #144272, #205295, #0A2647);
    margin: 18px 0;
    border-radius: 2px;
  }
</style>

<div class="lm-slide">

<div class="lm-title">🛠️ Occupational / Labour-Market Characteristics</div>

<div class="lm-box">

- Work organisation relies on **standardised vocational qualifications**.
- Most workers in manufacturing and many services have a **recognised VET qualification**.
- IVET at upper secondary level is **strong and central**.
- Workers can **move between firms** without losing the value of their qualification.
- Wage differentials between vocationally skilled workers and tertiary graduates are often **smaller**.
- Examples (ideal-typical): **Germany, Austria, Switzerland, Denmark, Netherlands**.

<div class="lm-divider"></div>

Germany is commonly described as a country with a **dominant occupational space**,  
where VET grants **membership in an occupation** and is closely linked to collective wage-setting  
and occupational career paths.

</div>

</div>


---

## Functional Roles of VET in the Labour Market

According to the labour market perspective, VET fulfils multiple functions, such as:

- **Cultural reproduction and transformation** of occupational practices  
- **Economic efficiency**: providing skills that meet workplace requirements  
- **Societal continuity**: supporting social cohesion and norms  
- **Individual readiness for work**: enabling smooth transitions into employment  
- **Support for lifelong development**: enabling progression and adaptation across the life course

In countries with strong occupational systems (such as Germany), VET is also seen as an important **pillar of the innovation system**, because skilled workers contribute not only to fulfilling existing tasks, but also to **shaping and improving work processes**.

---

## Towards a Multi-Perspective Conceptual Framework of VET

The three perspectives are combined into a **multi-perspective conceptual framework**:

- **Epistemological/pedagogical**:

  - What kinds of knowledge and learning processes are central?
  - How is the balance between **cognitive** and **tacit/practical** knowledge?

- **System and institutional**:

  - How is VET positioned within the education system?
  - Which levels, providers, governance arrangements and learner statuses dominate?

- **Socioeconomic and labour market**:

  - How does VET relate to work organisation, occupational structures and labour markets?
  - What are the main **functions** VET fulfils for the economy and society?

The framework does **not** prescribe one “ideal” VET model.  
Instead, it offers a **tool to characterise and compare** national conceptions of VET and to trace **changes over time**.

     --{{0}}--
!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/THE%20MULTI-PERSPECTIVE%20CONCEPTUAL%20FRAMEWORK%20.mp4?raw=true)
---

## Summary & Transition

**Key points from this 20-minute input:**

- VET is **too diverse** to be captured by one short definition; it requires a **multi-perspective analysis**.
- From an **epistemological and pedagogical** perspective, VET oscillates between:

  - A **cognitive** knowledge tradition, and
  - A **tacit, practice-based** knowledge tradition.
- From a **system and institutional** perspective, VET is shaped by:
  - Its **levels**, **providers**, **governance**, and **learner status**.
- From a **socioeconomic and labour market** perspective, VET:

  - Contributes to **stratification, matching, innovation, and social integration**, and can be analysed using the distinction between **organisational** and **occupational space**.
- The **German dual system** can be read as an example where these dimensions are **strongly linked** through occupationally based qualifications and shared governance.

> Reflection for the next part of the seminar. 
> *If you apply these three perspectives to German VET as you know it, what stands out most strongly – the epistemological, the system, or the labour market dimension?*

---

# ✅ Knowledge Check – Quiz (Features of VET)

     --{{0}}--
Now let's test your understanding of the three perspectives on V E T with this knowledge check quiz.




<style>
  .quiz-slide {
    background: linear-gradient(135deg, #0A2647 0%, #144272 35%, #205295 100%);
    padding: 40px;
    border-radius: 22px;
    color: #FFFFFF;
    box-shadow: 0 10px 22px rgba(0,0,0,0.28);
    margin: 25px 0;
  }
  .quiz-title {
    font-size: 30px;
    font-weight: bold;
    color: #E0F4FF;
    margin-bottom: 18px;
  }
  .quiz-box {
   background: #FFFFFF;
    color: #0A2647;
    padding: 26px;
    border-radius: 16px;
    box-shadow: 0 6px 16px rgba(0,0,0,0.15);
    font-size: 17px;
    line-height: 1.55;
  }
</style>

<div class="quiz-slide">

<div class="quiz-title">📝 Introduction to the Quiz</div>

<div class="quiz-box">

This short quiz helps you consolidate your understanding of:

- The three analytical perspectives on VET,
- Their key characteristics,
- And their relevance for the German VET context.

</div>

</div>


---

## Question 1 – Single Choice

Which statement best describes **why a multi-perspective framework is needed** to analyse VET?

- [[ ]] Because VET has a clear and uniform definition across all countries.  
- [[X]] Because VET is highly heterogeneous and cannot be captured by a single definition.  
- [[ ]] Because VET is only relevant for upper secondary education.  
- [[ ]] Because VET is identical to general education except for practical training.  



---

## Question 2 – Single Choice (Epistemological Perspective)

Which type of knowledge is **central to the tacit knowing view** in VET?

- [[ ]] Abstract scientific theories  
- [[ ]] Standardised textbook knowledge  
- [[X]] Experience-based, practical, situational knowledge  
- [[ ]] Memorised facts and rules only  



---

## Question 3 – Single Choice (Cognitive vs. Tacit Knowing)

Which option correctly matches the **knowledge view** to its characteristic?

- [[X]] Cognitive → explicit, abstract, discipline-based; Tacit → implicit, experience-based, situational  
- [[ ]] Cognitive → implicit, situational; Tacit → explicit, abstract, discipline-based  
- [[ ]] Cognitive and tacit both → purely theoretical knowledge  
- [[ ]] There is no difference between cognitive and tacit views in VET  



---

## Question 4 – Multiple Choice (System & Institutional Perspective)

Which of the following are **key dimensions of the system and institutional perspective on VET**?  
(More than one answer is correct.)

[[X]] Level(s) of education where VET is located  
[[X]] Types of providers (schools, companies, colleges, training centres)  
[[X]] Governance and funding arrangements  
[[ ]] Individual learning motivation only  
[[ ]] Personality traits of learners  



---

## Question 5 – Single Choice (ISCED Development)

According to the more recent ISCED definition (2011), VET:

- [[ ]] exists only at upper secondary level.  
- [[ ]] is defined exclusively as terminal education.  
- [[X]] includes occupation-specific qualifications and may include work-based components.  
- [[ ]] excludes post-secondary and tertiary education.  



---

## Question 6 – Multiple Choice (Labour Market Perspective)

Which functions of VET are explicitly highlighted in the **socioeconomic and labour market perspective**?  
(More than one answer is correct.)

- [[X]] Economic efficiency (meeting occupational requirements)  
- [[X]] Cultural reproduction and transformation of occupational practices  
- [[X]] Preparation for working life and individual progression  
- [[ ]] Elimination of all labour market inequality  
- [[ ]] Replacement of higher education  



---

## Question 7 – Single Choice (Organisational vs. Occupational Space)

In a system dominated by **occupational space**, initial VET (IVET) mainly prepares learners for:

- [[ ]] Short-term firm-specific tasks  
- [[X]] Membership in an occupation or (para-)profession  
- [[ ]] Immediate unskilled employment  
- [[ ]] Management and research roles only  



---

## Question 8 – True or False (Organisational Space)

> "In countries dominated by organisational space, upper-secondary IVET usually has high prestige and strong labour market value."

- [[ ]] True  
- [[X]] False  



---

## Question 9 – Single Choice (German VET)

Germany is commonly characterised in this framework as a country with:

- [[ ]] Dominance of organisational space  
- [[X]] Dominance of occupational space  
- [[ ]] Absence of work-based learning  
- [[ ]] Exclusively school-based VET  



---

## Question 10 – Single Choice (Multi-Perspective Framework)

What is the **main purpose** of the multi-perspective conceptual framework of VET?

- [[ ]] To rank countries according to VET quality  
- [[X]] To prescribe one ideal VET model  
- [[ ]] To analytically compare national conceptions of VET and their changes over time  
- [[ ]] To replace all legal definitions of VET  



---

## ✅ Self-Reflection


<style>
  .reflect-slide {
    background: linear-gradient(135deg, #0A2647 0%, #144272 35%, #205295 100%);
    padding: 40px;
    border-radius: 22px;
    color: #FFFFFF;
    box-shadow: 0 10px 22px rgba(0,0,0,0.28);
    margin: 25px 0;
  }
  .reflect-title {
    font-size: 30px;
    font-weight: bold;
    color: #E0F4FF;
    margin-bottom: 18px;
  }
  .reflect-box {
    background: #FFFFFF;
    color: #0A2647;
    padding: 26px;
    border-radius: 16px;
    box-shadow: 0 6px 16px rgba(0,0,0,0.15);
    font-size: 17px;
    line-height: 1.55;
    margin-top: 10px;
  }
</style>

<div class="reflect-slide">

<div class="reflect-title">🧭 How can you apply these perespectives to VET system in your own country ? </div>

<div class="reflect-box">


</div>

</div>


# Block 2 – Classical German VET Theories  

     --{{0}}--
Now we will explore three pioneering thinkers who shaped German vocational education: Georg Kerschensteiner, Eduard Spranger, and Aloys Fischer.


Duration for this block: ~30 minutes

**Literature source:** Kuhlee, Steib & Winch (2022)  
*Founding German vocational education: Kerschensteiner, Spranger and Fischer as key figures in the classical German VET theory*

---

## Why learn these theories ?

After this input, you will be able to :

- explain the **historical conditions** of classical German VET theory,
- describe the **core pedagogical ideas** of:
  - Kerschensteiner,
  - Spranger,
  - Fischer,
- understand the **central role of Beruf (occupation)**,
- explain the **foundations of the German dual system**.

---

# 1. Historical Background

     --{{0}}--
To understand classical German V E T theory, we need to examine the early 20th century context when these ideas emerged.


- Neo-humanist education theory (Humboldt):

  - strict separation of **Bildung** and **vocational training**,
  - vocational education regarded as **non-educational**.
- Industrialisation:

  - growth of working class,
  - youth leaving school at 14,
  - social unrest, political radicalisation.
- Vocational education needed a **new philosophical legitimacy**.

This led to the emergence of **classical German vocational education theory**.

---

# 2. Georg Kerschensteiner – Work, Civic Education and Beruf

  ## Core Pedagogical Problem

- Working-class youth had:

  - new civil rights,
  - but lacked **civic maturity**.
- General continuation schools failed because they were:

  - abstract,
  - detached from real work.

    --{{0}}--

!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Georg%20Kerschensteiner%20%E2%80%93%20The%20Architect%20of%20Dual%20Learning%20.mp4?raw=true)
---

## ✅ Core Ideas – Kerschensteiner (with Original Quotation)

> “Education for professional efficiency is the basis of all civic education,  
> because in the education for zeal and enthusiasm for work, those civic virtues develop  
> which we must regard as the basis of all higher moral education:  
> conscientiousness, diligence, perseverance, self-conquest and dedication to an active life  
> [in the service of society].”  
> *(Kerschensteiner, 1901, p. 16)*

### Theoretical Meaning

- **Work is not only economic activity** → it is **moral and civic education**.
- **Civic virtues emerge through productive work itself.**
- Occupation (**Beruf**) becomes the **didactical centre** of schooling.

---

## Institutional Impact of Kerschensteiner

- Transformation of:

  - Fortbildungsschule → **Berufsschule**
- Principle of:

  - **unity of theory and practice**
- Philosophical foundation of:

  - the **dual system**

---

# 3. Eduard Spranger – Vocational Education as Bildung

  ## Theoretical Problem

- Neo-humanism claimed:

  - *Beruf = narrow utility*,
  - *Bildung = higher education*.
- Spranger rejected this **duality of value**.

    --{{0}}--

!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Eduard%20Spranger%20%E2%80%93%20Bildung%20Through%20Vocation%20.mp4?raw=true)
---

## ✅ Core Ideas – Spranger (with Original Quotations)

> “It is the task of our time to understand the word ‘Berufsbildung’ again in its entire content.  
> According to the older view it could almost seem as if Beruf and Bildung were mutually exclusive…  
> But Bildung always carries a generality within itself.  
> Whoever is educated for his profession is at the same time educated for freedom.”  
> *(Spranger, 1923, p. 167)*

---

### Spranger’s Three-Step Theory (Original Formulation)

> “The developmental rhythm of education thus leads  
> from Grundbildung via Berufsbildung to higher Allgemeinbildung.  
> The path to higher general education leads through the Beruf – and only through the Beruf.”  
> *(Spranger, 1923, pp. 162–163)*

---

## Theoretical Meaning – Spranger



<style>
  .bildung-slide {
    background: linear-gradient(135deg, #0A2647 0%, #144272 40%, #205295 100%);
    padding: 40px;
    border-radius: 22px;
    color: #FFFFFF;
    box-shadow: 0 10px 22px rgba(0,0,0,0.28);
    margin: 25px 0;
  }
  .bildung-title {
    font-size: 30px;
    font-weight: bold;
    color: #E0F4FF;
    margin-bottom: 15px;
  }
  .bildung-box {
    background: #FFFFFF;
    color: #0A2647;
    padding: 26px;
    border-radius: 16px;
    box-shadow: 0 6px 16px rgba(0,0,0,0.15);
    font-size: 17px;
    line-height: 1.58;
  }
  .bildung-divider {
    height: 3px;
    background: linear-gradient(to right, #144272, #205295, #0A2647);
    margin: 18px 0;
    border-radius: 2px;
  }
</style>

<div class="bildung-slide">

<div class="bildung-title">🎓 VET, Bildung & Personal Maturity</div>

<div class="bildung-box">

- VET is **not inferior** to general education.
- VET is a **path to personal freedom and Bildung**.
- Goal of VET:
  - not only competence,
  - but **professional and personal maturity (Mündigkeit)**.
- The **Beruf becomes the bridge** between:
  - work,
  - culture,
  - personality.

</div>

</div>


---

# 4. Aloys Fischer – Self-Knowledge and Vocational Choice



    --{{0}}--
!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Aloys%20Fischer%20%E2%80%93%20The%20Pioneer%20of%20Career%20Guidance.mp4?raw=true)


  ## Historical Problem

- Traditional inheritance of occupations collapsed.
- Young people had to **choose their occupation** without:

  - family experience,
  - social transparency of modern industry.

---

## ✅ Core Ideas – Fischer (with Original Quotations)

> “The inheritance of occupations was replaced by the choice of occupation.”  
> *(Spranger, 1923, cited in Fischer-context)*

---

> “Vocational guidance and preparation for choosing an occupation are the responsibility  
> of all education sectors, including general and vocational education.”  
> *(Fischer, 1925; 1967/1932)*

---

## Theoretical Meaning – Fischer



<style>
  .choice-slide {
    background: linear-gradient(135deg, #4A148C 0%, #6A1B9A 40%, #AD1457 100%);
    padding: 40px;
    border-radius: 22px;
    color: #FBEAFF;
    box-shadow: 0 10px 22px rgba(0,0,0,0.30);
    margin: 25px 0;
  }
  .choice-title {
    font-size: 30px;
    font-weight: bold;
    color: #FFECFF;
    margin-bottom: 15px;
  }
  .choice-box {
    background: #FFFFFF;
    color: #4A148C;
    padding: 26px;
    border-radius: 16px;
    box-shadow: 0 6px 16px rgba(0,0,0,0.18);
    font-size: 17px;
    line-height: 1.58;
  }
  .choice-divider {
    height: 3px;
    background: linear-gradient(to right, #6A1B9A, #AD1457, #4A148C);
    margin: 18px 0;
    border-radius: 2px;
  }
</style>

<div class="choice-slide">

<div class="choice-title">🌟 Vocational Choice & Guidance</div>

<div class="choice-box">

- Vocational choice requires:
  - **self-knowledge**,
  - **systematic guidance**.
- Career choice becomes:
  - a **pedagogical task**,
  - not merely a market decision.
- Foundation of:
  - public **career guidance (Berufsberatung)**,
  - probationary phases in apprenticeships.

</div>

</div>


---

# 5. Shared Core of Classical German VET Theory

## ✅ Synthesising Core Idea (Original Formulation)

> “Classical vocational education theory put the holistic concept of ‘Beruf’  
> into the didactical centre of vocational education in Germany and constituted vocational education  
> not only as qualification, but also as education supporting the personal development of young people.”

---

## Common Assumptions of All Three Thinkers



<style>
  .beruf-slide {
    background: linear-gradient(140deg, #004D40 0%, #00695C 40%, #00897B 100%);
    padding: 42px;
    border-radius: 24px;
    color: #E0FFFA;
    box-shadow: 0 12px 26px rgba(0,0,0,0.30);
    margin: 28px 0;
    font-family: sans-serif;
  }
  .beruf-title {
    font-size: 30px;
    font-weight: bold;
    color: #FFF9C4;
    margin-bottom: 18px;
    letter-spacing: 0.5px;
  }
  .beruf-box {
    background: #FFFFFF;
    color: #004D40;
    padding: 28px;
    border-radius: 18px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.18);
    font-size: 17px;
    line-height: 1.6;
    border-left: 8px solid #80CBC4;
  }
  .beruf-divider {
    height: 3px;
    background: linear-gradient(to right, #80CBC4, #00897B, #004D40);
    margin: 20px 0;
    border-radius: 2px;
  }
</style>

<div class="beruf-slide">

<div class="beruf-title">🏅 The *Beruf* Principle in VET</div>

<div class="beruf-box">

- **Beruf is the core category** of VET.
- VET is:
  - Qualification **and** education.

<div class="beruf-divider"></div>

**Education integrates:**
- Work  
- Personality  
- Citizenship  

<div class="beruf-divider"></div>

**VET serves:**
- Individual development,  
- Social integration,  
- Economic stability.

</div>

</div>


---

# 6. Lasting Importance for Today’s German VET System



<style>
  .dual-slide {
    background: linear-gradient(135deg, #0D47A1 0%, #1565C0 40%, #00ACC1 100%);
    padding: 42px;
    border-radius: 24px;
    color: #E3F2FD;
    box-shadow: 0 12px 26px rgba(0,0,0,0.30);
    margin: 28px 0;
    font-family: sans-serif;
  }
  .dual-title {
    font-size: 30px;
    font-weight: bold;
    color: #E1F5FE;
    margin-bottom: 18px;
    letter-spacing: 0.5px;
  }
  .dual-box {
    background: #FFFFFF;
    color: #0D47A1;
    padding: 28px;
    border-radius: 18px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.18);
    font-size: 17px;
    line-height: 1.6;
    border-left: 8px solid #81D4FA;
  }
  .dual-divider {
    height: 3px;
    background: linear-gradient(to right, #00ACC1, #1565C0, #0D47A1);
    margin: 20px 0;
    border-radius: 2px;
  }
</style>

<div class="dual-slide">

<div class="dual-title">🏫⚙️ Dual Principle & Ongoing VET Debates</div>

<div class="dual-box">

- Dual principle:  
  - school + company training.

- Status of:  
  - VET as **equivalent to general education**.

<div class="dual-divider"></div>

**Centrality of:**
- Beruf  
- Career guidance  
- Maturity (Mündigkeit)

<div class="dual-divider"></div>

**Ongoing relevance in debates about:**
- Academic drift  
- Lifelong learning  
- Digital transformation  

</div>

</div>


---

# ✅ Knowledge Check – Quiz 

     --{{0}}--
Let's check your understanding of classical German V E T theories with this quiz.


## Question 1  
What social problem mainly triggered classical German VET theory?

- [[ ]] University expansion  
- [[X]] Industrialisation and working-class instability  
- [[ ]] Military reform  
- [[ ]] Teacher shortages  



---

## Question 2  
What is Kerschensteiner’s central educational principle?

- [[ ]] Theory replaces practice  
- [[X]] Civic virtues develop through productive work  
- [[ ]] Work has no educational value  
- [[ ]] Civic education is purely political theory  


---

## Question 3  
What does Spranger’s Three-Step Theory describe?

- [[ ]] School → University → Industry  
- [[X]] Grundbildung → Berufsbildung → Allgemeinbildung  
- [[ ]] Skill → Competence → Qualification  
- [[ ]] Childhood → Youth → Adulthood  



---

## Question 4  
What was Fischer mainly concerned with?

- [[ ]] Teacher professionalisation  
- [[X]] Industrial productivity  
- [[ ]] Self-knowledge and vocational choice  
- [[ ]] Military preparation  



---

## Question 5  
What concept forms the didactical centre of German VET?

- [[ ]] School  
- [[X]] Firm  
- [[ ]] Beruf  
- [[ ]] Examination  



---

## Question 6  
What is the shared educational goal of classical German VET theory?

- [[ ]] Fast job placement   
- [[ ]] Pure economic efficiency  
- [[ ]] Academic elite formation 
- [[X]] Professional, personal and civic maturity  



---

# ✅ Reflection Question



<style>
  .theory-reflect {
    background: linear-gradient(135deg, #BF360C 0%, #D84315 35%, #FF7043 100%);
    padding: 42px;
    border-radius: 26px;
    color: #FDECE4;
    box-shadow: 0 12px 26px rgba(0,0,0,0.35);
    margin: 28px 0;
    font-family: sans-serif;
  }
  .theory-title {
    font-size: 30px;
    font-weight: bold;
    color: #FFF3E0;
    margin-bottom: 18px;
    letter-spacing: 0.4px;
  }
  .theory-box {
    background: #FFFFFF;
    color: #BF360C;
    padding: 28px;
    border-radius: 18px;
    box-shadow: 0 10px 24px rgba(0,0,0,0.18);
    font-size: 17px;
    line-height: 1.6;
    border-left: 8px solid #FFAB91;
  }
  .theory-highlight {
    font-weight: bold;
    color: #D84315;
  }
</style>

<div class="theory-reflect">

<div class="theory-title">🧭 Self-Assessment: Understanding the Classic Theories of VET</div>

<div class="theory-box">


- Which of the three theories do you find **most relevant** for modern TVET and why?

</div>

</div>



# Block 3 – The Bildung Theory-From von Humboldt to Klafki  

     --{{0}}--
Now we will explore most important concept , Bildung theory, a central concept in German education, tracing its evolution from Wilhelm von Humboldt to Wolfgang Klafki, What is interesting here is to understand the paradigm shift from set educational goals to critical questioning of educational goals, for example by Klafki, to output orientation and the usability of education.

---


# 1. Bildung as a Central European Theory of Education


    --{{0}}--
!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Bildung%20as%20a%20Central%20European%20Theory%20of%20Education.mp4?raw=true)

Bildung is the **core educational theory** of:

   ## 🌸 Bildung Tradition Overview (New Multi-Panel Style)

<style>
  .panel-container {
    display: grid;
    gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    margin: 25px 0;
    font-family: sans-serif;
  }

  .panel {
    padding: 22px;
    border-radius: 18px;
    color: #ffffff;
    box-shadow: 0 6px 18px rgba(0,0,0,0.18);
  }

  .p1 { background: linear-gradient(135deg, #6A1B9A, #8E24AA); }
  .p2 { background: linear-gradient(135deg, #1565C0, #1E88E5); }
  .p3 { background: linear-gradient(135deg, #00897B, #26A69A); }

  .full-panel {
    background: linear-gradient(135deg, #D84315, #F4511E);
    padding: 26px;
    border-radius: 20px;
    color: #ffffff;
    box-shadow: 0 8px 22px rgba(0,0,0,0.22);
    margin-top: 20px;
    line-height: 1.6;
  }

  .panel-title {
    font-size: 22px;
    font-weight: bold;
    margin-bottom: 8px;
  }
</style>

<div class="panel-container">

  <div class="panel p1">
    <div class="panel-title">🌍 Regions</div>
    - German-speaking countries  
    - Scandinavia  
    - selected Latin American traditions  
  </div>

  <div class="panel p2">
    <div class="panel-title">📜 Historical Timeline</div>
    It is a **200+ year tradition**, dating back to:  
    - Wilhelm von Humboldt  
  </div>

  <div class="panel p3">
    <div class="panel-title">🎓 What is Bildung?</div>
    - not just “education”,  
    - but a **theory of the aims and meaning of education itself**,  
    - rooted in:  
      - the Enlightenment (reason, autonomy)  
      - Romanticism (personality, humanity)  
  </div>

</div>

<div class="full-panel">
It defines **what education is for**,  
not only *how* teaching is organised.
</div>


---

# 2. Core Meaning of Bildung

     --{{0}}--
Bildung refers to personal self-formation through self-activity, self-reflection, and responsibility, It is not mere knowledge accumulation, but the development of judgment, autonomy, and moral orientation




<style>
  .split-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 22px;
    margin: 25px 0;
    font-family: sans-serif;
  }

  .panelA, .panelB {
    padding: 24px;
    border-radius: 18px;
    color: #ffffff;
    box-shadow: 0 8px 20px rgba(0,0,0,0.22);
  }

  .panelA {
    background: linear-gradient(135deg, #00695C, #00897B);
  }

  .panelB {
    background: linear-gradient(135deg, #283593, #3949AB);
  }

  .bottom-panel {
    margin-top: 25px;
    background: linear-gradient(135deg, #AD1457, #C2185B);
    padding: 26px;
    border-radius: 20px;
    color: #ffffff;
    box-shadow: 0 10px 26px rgba(0,0,0,0.28);
    line-height: 1.6;
    font-size: 17px;
  }

  .title {
    font-size: 22px;
    font-weight: bold;
    margin-bottom: 10px;
  }
</style>

<div class="split-container">

  <div class="panelA">
    <div class="title">🌱 Two Dimensions of Bildung</div>
    Bildung always includes **two inseparable dimensions**:
    <br><br>
    1. The **process of personal self-formation**,  
    2. The **result of this formation**.
  </div>

  <div class="panelB">
    <div class="title">🌿 Bildung as Active Development</div>
    Bildung:
    - Cannot simply be transmitted,  
    - Must be **actively developed by the individual**.
    <br><br>
    Education may **support** Bildung,  
    but Bildung remains a process of:
    - Self-activity,  
    - Self-reflection,  
    - Responsibility.  
  </div>

</div>

<div class="bottom-panel">
Thus, Bildung is not the accumulation of knowledge,  
but the development of:
- Judgement,  
- Autonomy,  
- Moral orientation.
</div>


---

# 3. Bildung as Self–World Relation



<style>
  .pastel-container {
    background: linear-gradient(135deg, #F8BBD0 0%, #FFE0B2 50%, #FFF9C4 100%);
    padding: 40px;
    border-radius: 28px;
    box-shadow: 0 12px 28px rgba(0,0,0,0.25);
    margin: 28px 0;
    font-family: sans-serif;
  }

  .pastel-title {
    font-size: 30px;
    font-weight: bold;
    color: #4E342E;
    margin-bottom: 20px;
    text-align: center;
  }

  .card-grid {
    display: grid;
    gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  }

  .pastel-card {
    background: #FFFFFF;
    padding: 22px;
    border-radius: 20px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    font-size: 17px;
    color: #5D4037;
    line-height: 1.55;
    border-left: 6px solid #F48FB1;
  }

  .bottom-card {
    margin-top: 25px;
    background: #FFFFFF;
    padding: 24px;
    border-radius: 22px;
    color: #4E342E;
    box-shadow: 0 10px 26px rgba(0,0,0,0.20);
    font-size: 17px;
    line-height: 1.6;
    border-left: 8px solid #FFCC80;
  }
</style>

<div class="pastel-container">

<div class="pastel-title">🌼 Bildung: Reflexive Transformation</div>

<div class="card-grid">

  <div class="pastel-card">
    Bildung describes a **reflexive transformation of the relationship between self and world**.
  </div>

  <div class="pastel-card">
    It includes:
    - Meaning-making  
    - Value orientation  
    - Character formation  
    - Lifelong development  
  </div>

  <div class="pastel-card">
    Bildung is both:
    - **individual**, and  
    - **social**.  
  </div>

</div>

<div class="bottom-card">
It links:
- Personal freedom  
- Social responsibility  
- Ethical action  
</div>

</div>


---
# 5.  Classical Bildung or Classical Concept of Education

Classical Bildung (concept of education) is based on von Humboldt’s way of under
standing "Bildung" as a process of individualization,where the human being develops personality in all their human capacity.

# 6.  Wolfgang Klafki's - Modern Concept of Education

     --{{0}}--
!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Minute%20Script_%20Klafki's%20Concepts%20of%20Bildung.mp4?raw=true)

One of Klafki's particular achievements is the development of a concept of education that was constituted by combining the material and formal educational theories that prevailed until the middle of the 20th century with the theory of categorical education. 

---

# 6. Material Educational Theories

 Material educational theories define education on the basis ofspecific content: "they ask which 
aspects of our diverse reality are so valuable and important that pupils should learn or 
experience them" (Jank/Meyer, 1991, p. 78). 


Examples of material educational theories are 
**objectivism and classical theory**

# 7.Formal Educational Theories

 Formal educational theories define education from the perspective of the subject, i.e. the 
student and their presumed subjective and objective needs, the development and promotion 
of their potential, and not from the perspective of content and its objective meaning. "They ask 
what is important for the student now or in the future" (ibid., cf. also Blankertz 1975, p. 39 f.). 


Examples include 
**the theory of functional education and the theory of methodical education**


# 8. Klafki's Theory of categorical education


    --{{0}}--
!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Klafki%20-Theory%20of%20categorical%20%20education.mp4?raw=true)

Klafki develops his theory of categorical education with the aim of 
dialectically intertwining the object-related (= material) and subject-related (= formal) perspectives. 


Acccrding to Jank/Meyer (1991, p.144) 
"Categorical education is Klafki's attempt to avoid the one-sidedness of predominantly object-related (material) and predominantly subject-related (formal) didactics by 
dialectically intertwining both approaches at the didactic-content level".



# 9. Principles of categorical education: the Elementary, Fundamental and Exemplary

     --{{0}}--
Klafki emphasises that not everything that can be taught and learned is always educational, rather, 
the relationship between the specific nature of educational content and the general principles it 
represents must be precisely defined


Klafki coined three terms for this purpose:

 
1) The elementary –  general principle behind the specific case or example.


 2) The fundamental – experiences that pupils can acquire when engaging with educational 
content: "Teaching content is (...) only truly educational if it is elementary in terms of the 
subject matter (...) and fundamental in terms of the students (conveying basic experiences and 
fundamental insights)" (Jank/Meyer, 1991, p. 146);


3) The exemplary: fruitful examples from which fundamentals and elementary principles can be 
gained.




# 10. Klafki’s Didactical Analysis : The Five Guiding Questions



    --{{0}}--
!?[](https://github.com/Mahwish-Lia/Structure-and-Theories-of-TVET/blob/main/Klafki's%20Didactic%20Analysis.mp4?raw=true)

 The principles of categorical education clearly outline the self-image of educational theory and 
didactics: when dealing with educational content, both material and formal education are acquired. 
However, not all educational content is equally suitable for this purpose.



Klafki expresses this as 
follows: 


Educational content can only meet this requirement if it represents many cultural contents 
as a single content. This refers to a special characteristic: its educational content. "Every specific 
educational content has an educational content." (Klafki 1975, p. 134)

---

### 1. Present Significance  
What significance does the content in question already have in the 
intellectual lives of the children in my class, and what significance 
should it have – from an educational point of view?

---

### 2. Future Significance  
What is the significance of the topic for the children's future?

---

### 3.  Factual structure
What is the structure of the content?

---

### 4. Examplary Meaning 
What general facts or issues does the content in question address?

---

### 5. Accessibility  
What are the specific cases, phenomena, situations, attempts in 
which the structure of the respective content (...) can become 
interesting, questionable, accessible, comprehensible, vivid?

# 11. Klafki's Critical-constructive didactics

 Klafki understands his changed position:
 


 1) as critical in the context of a position based on the Frankfurt School and oriented towards the 
objectives of "self-determination, co-determination and solidarity" (Klafki, 1996, p. 90)


 2) as constructive in the sense of a concrete further development and change in teaching practice.

 Other important concepts of critical-constructive didactics are as follows: 
* The exemplary principle (Klafki, 1996, p. 141 ff.)
* The principle of science orientation (p. 162 ff.)
* The internal differentiation of teaching (p. 173 ff.) 
* The performance principle (p. 209 ff.).

---

# ✅ Knowledge Check 

---

## Question 1 – Understanding Klafki's Categorical Education

Wolfgang Klafki developed the concept of **categorical education** as a synthesis of two earlier educational approaches. 

What does Klafki's categorical education aim to achieve?

[[ ]] It prioritizes only the acquisition of factual content and subject matter knowledge.
[[ ]] It focuses exclusively on developing general cognitive abilities and formal capacities.
[[X]] It dialectically combines both material (content-focused) and formal (process-focused) education approaches.
[[ ]] It replaces both material and formal education with a completely new pedagogical framework.
***
<div style="background:#D4EDDA; padding:15px; border-left:5px solid #28A745; border-radius:5px;">

**✅ Correct Answer: It dialectically combines both material (content-focused) and formal (process-focused) education approaches.**

**Explanation:**  
Klafki's categorical education represents a **synthesis** that overcomes the one-sidedness of material education (which emphasizes content and canonical knowledge) and formal education (which emphasizes capacities and transferable skills). By dialectically intertwining both perspectives, categorical education ensures that learners acquire both:
- **Objective understanding** (structure of subject matter - the material side)
- **Subjective development** (personal capacities and ways of thinking - the formal side)

This integration is at the heart of Klafki's educational philosophy: educational content should reveal fundamental structures (elementary) while simultaneously developing fundamental capacities in the learner (fundamental).
</div>
***

---

## Question 2 – The Three Principles: Elementary, Fundamental, and Exemplary

Klafki introduced three key terms to define what makes educational content truly "educational": **the elementary**, **the fundamental**, and **the exemplary**.

Match each principle with its correct description:

- **The Elementary**: [[ general principle | basic experiences | fruitful examples ]]
- **The Fundamental**: [[ general principle | basic experiences | fruitful examples ]]
- **The Exemplary**: [[ general principle | basic experiences | fruitful examples ]]
***
<div style="background:#D4EDDA; padding:15px; border-left:5px solid #28A745; border-radius:5px;">

**✅ Correct Answers:**
- **The Elementary**: general principle
- **The Fundamental**: basic experiences
- **The Exemplary**: fruitful examples

**Explanation:**  
These three principles work together to define educational content:

1. **The Elementary**: Refers to the general principles or underlying structures behind specific content. It represents the fundamental structure of the subject matter itself (object side).

2. **The Fundamental**: Refers to the experiences and insights that students gain when engaging with content. It focuses on what is fundamental for the learner's development (subject side).

3. **The Exemplary**: Refers to carefully selected examples through which both elementary principles and fundamental experiences can be gained. Not all examples are equally "exemplary" - they must be chosen to reveal general structures while being meaningful for learners.

Klafki emphasizes: "Teaching content is only truly educational if it is elementary in terms of the subject matter and fundamental in terms of the students."
</div>
***

---

## Question 3 – Klafki's Five Guiding Questions for Didactical Analysis

Klafki developed five guiding questions to help teachers analyze and select educational content. These questions ensure that content has true **educational value** (Bildungsgehalt).

Which of the following are among Klafki's five guiding questions? (Select all that apply)

[[ ]] What textbooks are available for this topic?
[[X]] What is the present significance of this content for the learners?
[[X]] What is the future significance of this topic?
[[X]] What is the factual structure of the content?
[[ ]] How much time should be allocated to teach this content?
[[X]] What exemplary meaning does this content have (what general issues does it address)?
[[X]] How can the content be made accessible, comprehensible, and engaging?
[[ ]] What standardized test questions can assess this content?
***
<div style="background:#D4EDDA; padding:15px; border-left:5px solid #28A745; border-radius:5px;">

**✅ Correct Answers:**
- What is the present significance of this content for the learners?
- What is the future significance of this topic?
- What is the factual structure of the content?
- What exemplary meaning does this content have?
- How can the content be made accessible, comprehensible, and engaging?

**Explanation:**  
Klafki's five guiding questions for didactical analysis are:

1. **Present Significance**: What significance does the content already have in the intellectual lives of the children, and what significance should it have from an educational point of view?

2. **Future Significance**: What is the significance of the topic for the children's future?

3. **Factual Structure**: What is the structure of the content?

4. **Exemplary Meaning**: What general facts or issues does the content in question address?

5. **Accessibility**: What are the specific cases, phenomena, situations in which the structure of the content can become interesting, questionable, accessible, comprehensible, and vivid?

These questions guide teachers in selecting content that is both structurally significant (elementary) and meaningful for learners (fundamental), ensuring genuine Bildung rather than mere knowledge transmission.
</div>
***

---

## Question 4 – Applying Klafki's Five Questions to a Teaching Scenario

A vocational teacher is planning a unit on **"sustainability in manufacturing processes"** for apprentices in industrial mechanics. She considers the following:

- **A**: Students already encounter waste and energy use in their daily workshop activities (present significance).
- **B**: Understanding sustainability will be crucial for their careers as industries transition to green technologies (future significance).
- **C**: The topic reveals fundamental principles about resource efficiency, circular economy, and systems thinking (exemplary meaning and factual structure).
- **D**: She plans to use concrete examples from their own workshop and local companies to make concepts tangible (accessibility).

Which of Klafki's five guiding questions has the teacher primarily addressed through considerations A, B, C, and D?

- Statement A addresses: [[ Present Significance | Future Significance | Factual Structure | Exemplary Meaning | Accessibility ]]
- Statement B addresses: [[ Present Significance | Future Significance | Factual Structure | Exemplary Meaning | Accessibility ]]
- Statement C addresses: [[ Present Significance | Future Significance | Factual Structure | Exemplary Meaning | Accessibility ]]
- Statement D addresses: [[ Present Significance | Future Significance | Factual Structure | Exemplary Meaning | Accessibility ]]
***
<div style="background:#D4EDDA; padding:15px; border-left:5px solid #28A745; border-radius:5px;">

**✅ Correct Answers:**
- Statement A addresses: **Present Significance**
- Statement B addresses: **Future Significance**
- Statement C addresses: **Exemplary Meaning and Factual Structure**
- Statement D addresses: **Accessibility**

**Explanation:**  
This scenario demonstrates how Klafki's questions guide practical teaching planning:

- **Present Significance (A)**: The teacher recognizes that sustainability is already relevant to students' current workshop experiences, not just an abstract future concern.

- **Future Significance (B)**: She identifies how this content will matter for their professional futures as the industry evolves.

- **Factual Structure & Exemplary Meaning (C)**: She identifies the underlying principles (systems thinking, circular economy) that give this topic its educational depth - it's not just about "being green" but understanding fundamental economic and ecological relationships.

- **Accessibility (D)**: She selects concrete, local examples that make abstract concepts comprehensible and engaging.

By systematically addressing these questions, the teacher ensures the content has genuine **Bildungsgehalt** (educational content) rather than being merely informational or skills-focused.
</div>
***

---

## Question 5 – Critical-Constructive Didactics: Goals and Orientation

Klafki's later work evolved into **critical-constructive didactics**, which integrates critical theory with practical pedagogical development.

What are the three main objectives of education according to Klafki's critical-constructive approach?

[[ ]] Efficiency, productivity, and economic competitiveness
[[ ]] Knowledge accumulation, skill mastery, and certification
[[X]] Self-determination, co-determination, and solidarity
[[ ]] Tradition preservation, cultural heritage, and national identity
***
<div style="background:#D4EDDA; padding:15px; border-left:5px solid #28A745; border-radius:5px;">

**✅ Correct Answer: Self-determination, co-determination, and solidarity**

**Explanation:**  
Klafki's critical-constructive didactics is oriented toward three interconnected democratic and emancipatory objectives:

1. **Self-determination (Selbstbestimmung)**: The ability to make autonomous decisions about one's own life, relationships, beliefs, and vocational/political orientations.

2. **Co-determination (Mitbestimmung)**: The ability and willingness to participate in decision-making about shared concerns in society, workplace, politics, and culture.

3. **Solidarity (Solidarität)**: The commitment to support others in developing their capacities for self-determination and co-determination, especially those who are disadvantaged or marginalized.

These objectives reflect Klafki's alignment with the **Frankfurt School** of critical theory and distinguish his approach from:
- Purely functional/economic orientations to education
- Traditional authority-centered pedagogy
- Narrowly individualistic competence frameworks

Education should prepare learners not just for employment, but for active, reflective, and responsible participation in democratic society.
</div>
***

---

## Question 6 – Distinguishing Material, Formal, and Categorical Bildung in Practice

A curriculum committee is debating three different approaches to designing a **computer programming course** for VET students:

**Proposal A**: Focus on teaching specific programming languages (Java, Python) and their syntax, data structures, and standard algorithms. Assessment is based on coding proficiency in these languages.

**Proposal B**: Focus on developing general problem-solving abilities, logical thinking, and algorithmic reasoning. The specific programming language is less important; what matters is that students learn "how to think like a programmer."

**Proposal C**: Select exemplary programming problems that both reveal fundamental concepts of computer science (algorithms, abstraction, data modeling) AND develop students' abilities to analyze, design, and critically evaluate software solutions. Students engage with both the structure of the discipline and their own cognitive development.

How would these proposals be classified according to Klafki's framework?

- Proposal A represents: [[ Material Bildung | Formal Bildung | Categorical Bildung ]]
- Proposal B represents: [[ Material Bildung | Formal Bildung | Categorical Bildung ]]
- Proposal C represents: [[ Material Bildung | Formal Bildung | Categorical Bildung ]]
***
<div style="background:#D4EDDA; padding:15px; border-left:5px solid #28A745; border-radius:5px;">

**✅ Correct Answers:**
- Proposal A represents: **Material Bildung**
- Proposal B represents: **Formal Bildung**
- Proposal C represents: **Categorical Bildung**

**Explanation:**  

**Proposal A (Material Bildung)**: 
This approach prioritizes **content and canonical knowledge** - specific programming languages, their syntax, and standard algorithms. It focuses on "what to know" (the object side) and assumes that mastering this content is educational in itself. This reflects **material-scientific Bildung**.

**Proposal B (Formal Bildung)**: 
This approach prioritizes **capacities and transferable skills** - problem-solving, logical thinking, general reasoning abilities. The specific content is secondary; what matters is developing mental powers that can be applied to any situation. This reflects **formal-functional Bildung**.

**Proposal C (Categorical Bildung)**: 
This approach synthesizes both perspectives by:
- Selecting **exemplary** content (not all possible programming topics, but carefully chosen problems)
- Ensuring content is **elementary** (reveals fundamental computer science principles)
- Ensuring it is **fundamental** (develops students' thinking and analytical capacities)
- Creating a dialectical relationship where students understand both the structure of the discipline AND develop their own capabilities

Klafki's categorical education argues that neither material nor formal approaches alone are sufficient - genuine Bildung emerges from their integration through carefully selected exemplary content.
</div>
***

---

# ✅ Final Reflection




# End

<svg width="1200" height="350" viewBox="0 0 1200 350" xmlns="http://www.w3.org/2000/svg">

  <!-- Background gradient -->
  <defs>
    <linearGradient id="endGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0A2647"/>
      <stop offset="40%" stop-color="#144272"/>
      <stop offset="100%" stop-color="#205295"/>
    </linearGradient>

    <!-- Soft glow for quote box -->
    <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="6" stdDeviation="10" flood-color="#000000" flood-opacity="0.35"/>
    </filter>
  </defs>

  <!-- Rounded background -->
  <rect x="25" y="25" width="1150" height="300" rx="40" ry="40" fill="url(#endGradient)"/>

  <!-- Top label -->
  <text x="600" y="85"
        text-anchor="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="26"
        fill="#E0F4FF"
        letter-spacing="4">
    END OF TOPIC
  </text>

  <!-- Main title -->
  <text x="600" y="150"
        text-anchor="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="46"
        font-weight="bold"
        fill="#FFFFFF">
    Thank you for your attention!
  </text>

  <!-- Subtitle -->
  <text x="600" y="190"
        text-anchor="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="24"
        fill="#CFE8FF">
    VET, Bildung and the Three Perspectives
  </text>

  <!-- Quote / CoT box -->
  <g filter="url(#shadow)">
    <rect x="260" y="210" width="680" height="90" rx="18" ry="18" fill="#FFFFFF" fill-opacity="0.10" stroke="#E0F4FF" stroke-opacity="0.7"/>
  </g>

  <!-- Quote icon -->
  <text x="290" y="250"
        font-family="Georgia, 'Times New Roman', serif"
        font-size="40"
        fill="#FFD700">
    “
  </text>

  <!-- CoT text (short conclusion thought) -->
  <text x="330" y="242"
        font-family="Arial, Helvetica, sans-serif"
        font-size="20"
        fill="#F5FBFF">
    Bildung & VET aim at more than skills:
  </text>

  <text x="330" y="270"
        font-family="Arial, Helvetica, sans-serif"
        font-size="20"
        fill="#F5FBFF">
    they foster judgement, autonomy and social responsibility.
  </text>

</svg>