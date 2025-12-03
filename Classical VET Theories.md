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




# Welcome
<!-- Features of VET - SVG title banner -->
<svg width="1200" height="350" viewBox="0 0 1200 350" xmlns="http://www.w3.org/2000/svg">

  <!-- Background gradient -->
  <defs>
    <linearGradient id="vetGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0A2647"/>
      <stop offset="50%" stop-color="#144272"/>
      <stop offset="100%" stop-color="#205295"/>
    </linearGradient>
  </defs>

  <!-- Rounded background -->
  <rect x="25" y="25" width="1150" height="300" rx="40" ry="40" fill="url(#vetGradient)"/>

  <!-- Top small label -->
  <text x="600" y="95"
        text-anchor="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="28"
        fill="#E0F4FF"
        letter-spacing="3">
    FEATURES OF
  </text>

  <!-- Main title -->
  <text x="600" y="175"
        text-anchor="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="44"
        font-weight="bold"
        fill="#FFFFFF">
    Vocational Education and Training
  </text>

  <!-- (VET) on next line -->
  <text x="600" y="230"
        text-anchor="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="40"
        font-weight="bold"
        fill="#FFD700">
    (VET)
  </text>

  <!-- Decorative bottom line -->
  <line x1="320" y1="265" x2="880" y2="265"
        stroke="#E0F4FF"
        stroke-width="3"
        stroke-linecap="round"
        stroke-dasharray="10 8"/>
</svg>

## Three Perspectives & a Multi-Perspective Conceptual Framework


Course: Educational and Vocational Training Theories (TVET Master)
Session: Features of VET – Epistemological/Pedagogical, System, Socioeconomic Perspectives
Duration for this block: ~20 minutes
Source: Cedefop (2017). The changing nature and role of vocational education and training in Europe, Vol. 1.

---

## Learning Goals for this 20-Minute Block

<style>
  .vet-slide-box {
    background: linear-gradient(135deg, #0A2647 0%, #144272 50%, #205295 100%);
    padding: 35px;
    border-radius: 18px;
    color: white;
    box-shadow: 0 8px 18px rgba(0,0,0,0.25);
    margin: 20px 0;
  }
  .vet-slide-box h2 {
    color: #E0F4FF;
    margin-top: 0;
  }
  .vet-white-card {
    background: #ffffff;
    color: #0A2647;
    padding: 20px;
    border-radius: 14px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.12);
    margin-top: 12px;
  }
  .vet-reflect-box {
    background: #E8F3FF;
    border-left: 6px solid #205295;
    padding: 18px;
    border-radius: 8px;
    margin-top: 18px;
    font-style: italic;
    color: #0A2647;
  }
  .vet-summary {
    cursor: pointer;
    font-weight: bold;
    color: #E0F4FF;
  }
</style>

<div class="vet-slide-box">

<h2>🎯 By the end of this input, you should be able to:</h2>

<details>
  <summary class="vet-summary">Click here to reveal the learning outcomes</summary>

  <div class="vet-white-card">

- Explain **why** VET cannot be adequately captured by a single definition.
- Distinguish between the **three main perspectives** on VET:
  - Epistemological and pedagogical(-didactical),
  - System and institutional (education system) perspective,
  - Socioeconomic and labour market perspective.
- Describe how these perspectives are combined in a **multi-perspective conceptual framework**.
- Relate these perspectives, in a first step, to the **German VET context** (as an example).

  </div>
</details>

<div class="vet-reflect-box">
💡 <strong>Reflection question (no need to answer in chat):</strong><br>
From your own experience, how is “VET” usually talked about more — as a type of knowledge, as a type of institution, or as a labour-market tool?
</div>

</div>


---

## Why Do We Need a Multi-Perspective View of VET?

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

- The three perspectives are **analytical tools**, not three separate systems.
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

## 1. VET from an Epistemological and Pedagogical Perspective

Key idea: VET has a particular **knowledge base** and **learning logic**.

Two ideal-typical views of knowledge are distinguished:

1. **Cognitive view of knowledge**
2. **Tacit knowing view of knowledge**

These views are linked to different traditions of VET and different teaching–learning arrangements.

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

## ✅ End of Quiz – Self-Reflection (Not Graded)


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

<div class="reflect-title">🧭 Self-Assessment: Confidence Check</div>

<div class="reflect-box">

On a scale from 1 (very low) to 5 (very high), how confident do you now feel about:

- Explaining the three perspectives on VET?
- Applying them to the German VET system?

(You can simply reflect for yourself or note a number in your notes; this is **not graded**.)

</div>

</div>



# Part 2 – Classical German VET Theories  
## Kerschensteiner, Spranger and Fischer  
**Teacher Input (15 minutes)**  

**Source strictly based on:** Kuhlee, Steib & Winch (2022)  
*Founding German vocational education: Kerschensteiner, Spranger and Fischer as key figures in the classical German VET theory*

---

## Learning Objectives

After this input, students will be able to:

- explain the **historical conditions** of classical German VET theory,
- describe the **core pedagogical ideas** of:
  - Kerschensteiner,
  - Spranger,
  - Fischer,
- understand the **central role of Beruf (occupation)**,
- explain the **foundations of the German dual system**.

---

# 1. Historical Background

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

# ✅ Knowledge Check – Quiz (With Automatic Feedback)

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

# ✅ Reflection & Confidence Check



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

On a scale from **1 (very low)** to **5 (very high)**:

- How confident are you in explaining:
  - Kerschensteiner’s work-based civic education?
  - Spranger’s concept of Bildung through Beruf?
  - Fischer’s theory of vocational choice?

- Which of the three theories do you find **most relevant** for modern TVET and why?

</div>

</div>



# Part 3 – The Bildung Theory  
## From von Humboldt to Klafki  
What is interesting is the paradigm shift from set educational goals to critical questioning of educational goals, e.g. by Klafki, to output orientation and the usability of education.

---

## Learning Objectives

After this part, students will be able to:

- explain the **core meaning of Bildung** as a German educational theory,
- distinguish between **classical, formal, material, and categorical Bildung**,
- understand **Klafki’s critical-constructive reinterpretation** of Bildung,
- explain the relationship between **Bildung, democracy, and emancipation**,
- connect Bildung theory to **modern educational theory and Didaktik**.

---

# 1. Bildung as a Central European Theory of Education

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

# 4. From Classical to Critical-Constructive Bildung



<style>
  .ribbon-container {
    padding: 35px;
    background: linear-gradient(135deg, #1A237E 0%, #3949AB 40%, #5C6BC0 100%);
    border-radius: 26px;
    box-shadow: 0 12px 26px rgba(0,0,0,0.30);
    margin: 30px 0;
    font-family: sans-serif;
    color: #E8EAF6;
  }

  .ribbon-title {
    font-size: 30px;
    font-weight: bold;
    margin-bottom: 20px;
    color: #C5CAE9;
    text-align: center;
    letter-spacing: 0.5px;
  }

  .ribbon-strip {
    background: #FFFFFF;
    color: #1A237E;
    padding: 18px 22px;
    border-radius: 14px;
    box-shadow: 0 6px 16px rgba(0,0,0,0.15);
    font-size: 17px;
    margin-bottom: 16px;
    border-left: 8px solid #9FA8DA;
  }

  .highlight-block {
    margin-top: 25px;
    background: #E8EAF6;
    padding: 24px;
    border-radius: 18px;
    color: #1A237E;
    box-shadow: 0 10px 24px rgba(0,0,0,0.18);
    font-size: 17px;
    line-height: 1.6;
    border-left: 10px solid #5C6BC0;
  }
</style>

<div class="ribbon-container">

<div class="ribbon-title">📚 Historical Stages of Bildung Theory</div>

<div class="ribbon-strip">
Historical stages of Bildung theory:
- Classical (Humboldt)  
- Liberal humanistic education  
- Scandinavian folk Bildung  
- Democratic Bildung  
- Critical-hermeneutic Bildung  
</div>

<div class="ribbon-strip">
The most influential modern formulation is:  
<strong>Klafki’s critical-constructive Bildung theory</strong>.
</div>

<div class="highlight-block">
It integrates:
- Critique  
- Democracy  
- Emancipation  
- Social responsibility  
</div>

</div>


---

# 5. Klafki’s Theory of Bildung

For Klafki, Bildung means the development of the capacity for:

- **self-determination**,  
- **participation**,  
- **solidarity**.

Education must enable learners to:

- Shape their own lives,
- Participate responsibly in society,
- Act ethically toward others.

Thus, Bildung is not:

- Adaptation to society,
but:

- **critical engagement with society**.

---

# 6. Material, Formal and Categorical Bildung

## Material Bildung
- Focus on **content and cultural substance**.
- Priority of canonical knowledge.
- Two subtypes:

  - scientific Bildung (orientation to scientific knowledge),
  - humanistic Bildung (orientation to cultural heritage).

  Material Bildung emphasizes content knowledge. It is in line with the American version of liberal education, mainly focusing the canon of topics. Important aspects of especially humanistic material Bildung can also be found in classical Bildung, although von Humboldt’s orientation is probably better described as formal Bildung.

## Formal Bildung


<style>
  .formal-wrap {
    background: linear-gradient(135deg, #2E7D32 0%, #43A047 40%, #66BB6A 100%);
    padding: 40px;
    border-radius: 28px;
    color: #E8F5E9;
    box-shadow: 0 12px 26px rgba(0,0,0,0.28);
    margin: 30px 0;
    font-family: sans-serif;
  }

  .formal-title {
    text-align: center;
    font-size: 30px;
    font-weight: bold;
    color: #F1F8E9;
    margin-bottom: 20px;
    letter-spacing: 0.4px;
  }

  .accent-card {
    background: #FFFFFF;
    color: #1B5E20;
    padding: 22px;
    border-radius: 18px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    margin-bottom: 18px;
    border-left: 8px solid #A5D6A7;
    font-size: 17px;
    line-height: 1.55;
  }

  .accent-sub {
    background: #E8F5E9;
    color: #2E7D32;
    padding: 20px;
    border-radius: 16px;
    box-shadow: 0 6px 16px rgba(0,0,0,0.12);
    font-size: 17px;
    line-height: 1.6;
    border-left: 10px solid #66BB6A;
  }
</style>

<div class="formal-wrap">

<div class="formal-title">🌿 Formal Bildung Perspective</div>

<div class="accent-card">
- Focus on **capacities and competences**.  
- Priority of learning methods and transferable skills.
</div>

<div class="accent-card">
**Two subtypes:**
- Functional Bildung (development of human powers, potentials),  
- Method-based Bildung (methods and strategies to “master life”).
</div>

<div class="accent-sub">
Formal Bildung emphasizes the development of the person. For example, 
the character-formation ideal is emphasized in the English tradition of liberal education,
which focuses on skills development.  
Both the Scandinavian “folk-Bildung” tradition and democratic education have many aspects 
that can be categorized as formal Bildung.
</div>

</div>

## Categorical Bildung (Klafki’s Synthesis)
- Unity of **content and competence**.
- Learning opens:

  - The **world to the learner**,
  - The **learner to the world**.
- Education must be:

  - Fundamental (elementary, basic structures),
  - Exemplary (selected as representative key content),
  - Structure-generating (helps to organise understanding).

  Categorical Bildung emphasizes both content and the skills development in the learner. We would claim that critical-hermeneutic Bildung is most compatible with categorical Bildung.

---

# 7. Relationships between material, formal, and categorical Bildung

 Therelationship between the three different types of Bildung is illustrated in Fig. 5.1. page 59
 Material, formal, and categorical Bildung can further be connected to the five Bildung-traditions (described above) in the following ways

---

# 8. Bildung and Didaktik

Didaktik is the **practical reflection of Bildung in teaching**.

Teaching must always answer:

- **Why** is this taught?
- **What** is taught?
- **How** is it taught?

Didaktik is therefore:

- not technical instruction,
- but **normative educational reflection** about aims, contents, and methods.

It is about:

- Transforming cultural knowledge into **educationally meaningful content**,
- For the sake of **Bildung**.

---

# 9. Klafki’s Didactical Analysis (1958): The Five Guiding Questions

Didactical analysis, originally suggested by **Klafki (1958)**, offers guidance to reflect  
whether an issue or topic is **relevant enough to be taught**.  
It consists of **five questions**:

---

### 1. Exemplary Meaning  
What wider or general sense or reality does this content **exemplify and open up to the learner**?  

What **basic phenomenon or fundamental principle, law, criterion, problem, method, technique, or attitude**  
can be grasped by dealing with this content as an *example*?

---

### 2. Present Significance  
What **significance** does the content in question, or the **experience, knowledge, ability, or skill**  
to be acquired through this topic, possess in the minds of the children in my class?  

What **significance should it have from a pedagogical point of view**?

---

### 3. Future Significance  
What constitutes the topic’s **significance for the children’s future**?

---

### 4. Structure of the Content  
How is the **content structured**?  

How can it be placed in a **specifically pedagogical perspective** by reference to  
Questions 1, 2, and 3?

---

### 5. Accessibility and Vividness  


<style>
  .glass-wrap {
    background: linear-gradient(135deg, #512DA8 0%, #303F9F 50%, #1976D2 100%);
    padding: 45px;
    border-radius: 30px;
    color: #EDE7F6;
    box-shadow: 0 14px 30px rgba(0,0,0,0.32);
    margin: 32px 0;
    font-family: sans-serif;
  }

  .glass-title {
    text-align: center;
    font-size: 30px;
    font-weight: bold;
    color: #F3E5F5;
    margin-bottom: 25px;
    letter-spacing: 0.5px;
  }

  .glass-card {
    backdrop-filter: blur(12px);
    background: rgba(255, 255, 255, 0.20);
    padding: 26px;
    border-radius: 20px;
    box-shadow: 0 10px 24px rgba(0,0,0,0.25);
    border: 1px solid rgba(255, 255, 255, 0.35);
    color: #EDE7F6;
    font-size: 18px;
    line-height: 1.6;
  }

  .glass-bullets {
    margin-top: 18px;
    padding-left: 20px;
  }
</style>

<div class="glass-wrap">

<div class="glass-title">🎨 What Makes Content Vivid?</div>

<div class="glass-card">

What are the **special cases, phenomena, situations, experiments, persons,  
elements of aesthetic experience**, and so forth, in terms of which the  
structure of the content in question can become:

<div class="glass-bullets">
- interesting,  
- stimulating,  
- approachable,  
- conceivable, or  
- vivid  
</div>

</div>

</div>


for children at the **developmental stage** of this class?

---

# 10. Bildung in Late-Modern Society

Late-modern societies face:

- technological risk,
- digitalisation,
- socio-scientific conflicts,
- global ecological crisis,
- spread of misinformation.

These require:

- critical judgement,
- value-based reflection,
- democratic participation.

Bildung therefore becomes:

- **critical-reflexive Bildung**,
- oriented toward **transformative learning** and **sustainable development**.

---



---

# ✅ Knowledge Check – Complex Quiz (with Feedback)

---

## Question 1 – Differentiating Material, Formal and Categorical Bildung

A curriculum designer argues:

> “We should identify a small number of exemplary topics that both  
> reveal the structure of the subject matter **and** allow learners to develop  
> general capacities for critical judgement and participation.”

Which type(s) of Bildung does this MOST clearly reflect?

* [[ ]] Purely material Bildung  
* [[ ]] Purely formal Bildung  
* [[X]] Categorical Bildung  
* [[X]] Critical-hermeneutic / Allgemeinbildung (in Klafki’s sense)  



---

## Question 2 – Applying the Five Questions of Didactical Analysis

A teacher plans a unit on “digital surveillance and data capitalism” in a technology course.  
She reflects on the following:

1. How this topic reveals fundamental dynamics of power, rationality, and technology in late-modern society.  
2. Why this topic matters for her learners now (their everyday digital practices).  
3. How it will matter for their future autonomy as citizens.  

Which Klafki questions are she mainly addressing, and how does this relate to Bildung?

- [[ ]] Only Question 4 (structure of content); it is mainly technical planning.  
- [[X]] Questions 1–3; she is aligning the topic with exemplary meaning, present and future significance as part of Allgemeinbildung.  
- [[ ]] Only Question 5; she is searching for vivid media.  
- [[ ]] None; this is unrelated to Bildung and Didaktik.  


---

## Question 3 – Bildung vs Competence / Outcome Orientation in TVET

Consider the following four statements about the relationship between **Bildung** and **competence-/outcome-based TVET**:

1. Bildung and competence approaches are identical, since both focus on measurable skills.  
2. Bildung transcends competence approaches, because it includes self-determination, participation and solidarity that are not fully measurable as discrete outcomes.  
3. Competence frameworks can be **re-interpreted** in a Bildung-oriented way if they are connected to exemplary content, critical reflection, and democratic citizenship.  
4. A strict output orientation (only measurable learning outcomes) risks narrowing education to adaptation rather than emancipation.

Which combination of statements best reflects a **Bildung-theoretical critique**?

* [[ ]] 1 and 2  
* [[X]] 2, 3 and 4  
* [[ ]] 1, 3 and 4  
* [[ ]] Only 2  



---

## Question 4 – Vision of Scientific Literacy and Critical-Reflexive Bildung

A science teacher designs a unit on climate change where students:

- analyse conflicting media representations and interests of different stakeholders,  
- understand the underlying science,  
- debate ethical and political options,  
- develop and present proposals for local climate action.

Which vision of scientific literacy AND which interpretation of Bildung does this correspond to most clearly?

- [[ ]]  Vision I (conceptual scientific literacy) and classical, content-oriented Bildung  
- [[ ]]  Vision II (contextual scientific literacy) and purely formal Bildung  
- [[X]] Vision III (critical scientific literacy) and critical-reflexive / critical-hermeneutic Bildung  
- [[ ]]  No connection to scientific literacy or Bildung  



---

# ✅ Final Reflection

> - Where do you personally see the **limits** of competence-/outcome-based approaches from a Bildung perspective?  
> - How could you design a **Bildung-oriented TVET module** that still satisfies formal curriculum requirements?

(These questions are intended for written reflection or seminar discussion.)

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




