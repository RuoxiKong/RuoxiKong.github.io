---
title: The Architecture of Key Module 1
date: 2025-08-04
categories: [TOP_CATEGORY, SUB_CATEGORY]
tags: [TAG]     # TAG names should always be lowercase
categories: [Wordinow, Key Module]
tags: [Learning Engineering, Algorithm Design, Adaptive Learning, Corpus Linguistics, CAT, ZPD, Spaced Repetition, NLP, EdTech, Product Deep Dive]
author: <author_id>        
description: The Vocabulary, Reading, & Phrase Modules — An Algorithm-Driven Personalized Learning Loop
---
<div style="text-align: justify;">

<p>The Vocabulary, Reading, and Phrase modules I designed are central to the platform, with their innovative design deeply integrating advanced academic theories such as <strong>Corpus Linguistics, Computerized Adaptive Testing (CAT), Zone of Proximal Development (ZPD) Theory, Situated Learning Theory, Formative Assessment,</strong> and the <strong>Ebbinghaus Forgetting Curve</strong>, providing robust theoretical and technical support for precise personalized learning.</p>

<p align="center">
  <img src="{{ '/assets/module1.jpg' | relative_url }}" alt="Key Module 1" width="900">
</p>

<p align="center"><em>Key Module 1</em></p>

<h4>1. Localized Lexicon Construction: The First Step Towards Educational Equity</h4>
<p>I led and completed the construction of a specialized corpus and vocabulary leveling system specifically for Chinese English as a Foreign Language (EFL) learners. This corpus integrates vocabulary from over 50 versions of K12 English textbooks across China, high-frequency words from national college entrance exams, general reference corpora (BNC, COCA), and the CEFR framework. Building on this, I designed and developed a proprietary weighted-leveling algorithm that generates a vocabulary grading system highly matched to Chinese learners' cognitive pathways and examination requirements. The core objective of this initiative is to address the disparity between diverse local curricula across China and the unified national college entrance examination, ensuring that all students begin from an equitable starting point, with fair access to vocabulary resources highly aligned with core exam demands. This represents not only technological innovation but also a practical commitment to educational equity.</p>

<p>From a data-driven perspective, this foundational work is a non-negotiable prerequisite. Without a high-quality, culturally-contextualized dataset, any subsequent "adaptive" algorithm would be operating on flawed assumptions—garbage in, garbage out. From a user experience perspective, this ensures that the very first interaction a student has with the recommended content feels relevant and respectful of their learning context, building crucial initial trust and motivation.</p>


<h4>2. The Four-Step Adaptive Learning Loop: Precisely Matching the ZPD</h4>
<p>I designed the core learning experience not as a simple path, but as a dynamic, four-step loop, driven by my proprietary algorithms.</p>

<p><strong>a. Dynamic Assessment:</strong><br>
My first algorithm is built on the core principle of Computerized Adaptive Testing (CAT). It is capable of dynamically adjusting the difficulty of subsequent vocabulary items based on the learner's real-time response. This allows it to efficiently and accurately assess their current vocabulary size, rapidly pinpointing a student's true proficiency while avoiding redundant testing.</p>

<p><strong>b. Targeted Recommendation:</strong><br>
Following the assessment, my second algorithm does not simply match the student's grade level. Instead, based on their assessed proficiency and my localized lexicon system, it intelligently recommends core vocabulary items within their "Zone of Proximal Development (ZPD)". This challenges the traditional "grade level = proficiency" mindset and ensures maximum learning efficiency.</p>

<p><strong>c. Gamified Acquisition & Memorization:</strong><br>
Once the "highest-value" words are recommended, the crucial next step is the actual acquisition. Instead of rote drilling, I designed a series of engaging, interactive games. Each game is engineered to help students effectively memorize the vocabulary through varied repetition and interaction in a low-pressure, enjoyable environment. This is where the critical initial encoding of the memory takes place, building the foundation for deeper understanding.</p>

<p><strong>d. Contextualized Application & Comprehension Training:</strong><br>
After the initial memorization through games, the final step is to transform this fragile knowledge into robust, applicable understanding. This is where I leverage Large Language Models (LLM) to dynamically generate a short, original text using the newly learned words. This feature constitutes a highly dynamic graded reading system, with difficulty rigorously controlled by models like the Lexile Framework. More importantly, this is deep comprehension training. Each text is paired with questions I designed to target key skills like identifying the main idea and extracting information. This final step seamlessly upgrades memorization into authentic reading and comprehension practice.</p>

<p>From a data-driven perspective, this four-step loop is a closed, self-optimizing system. The data from step (d), comprehension performance, is not an endpoint; it is a critical feedback signal that can be used to refine the recommendation algorithm in step (b) and even inform the difficulty calibration of the assessment in step (a). From a user experience perspective, this structure is designed to create a seamless and logical flow. It respects the cognitive journey of the learner: from the low-anxiety of an adaptive test, to the clear value of a personalized recommendation, the enjoyable engagement of games, and finally, the profound satisfaction of seeing newly learned words come to life in a meaningful context.</p>

<h4>3. Formative Assessment & Spaced Repetition: Combating Forgetting, Reinforcing Memory</h4>
<p>In the learning loop design, I place a strong emphasis on Formative Assessment. Post-learning tests are used not only for Dynamic Knowledge Tracing, continuously updating the learner's personal knowledge graph, but also for accurately assessing their vocabulary size. If a student forgets a previously learned word during a test, the system automatically refreshes the word's status and reincorporates it into the learning plan. Furthermore, based on Ebbinghaus's Forgetting Curve theory, I designed a Spaced Repetition System (SRS) that delivers review content at optimal time points through gamified formats to combat forgetting, achieving long-term vocabulary retention and precise assessment. Phrase learning also follows this logic, primarily through gamified and contextualized learning, ensuring efficient memorization.</p>

<p>From a data-driven perspective, the SRS is the engine's long-term memory. It operates on a sophisticated scheduling algorithm that continuously re-evaluates the forgetting probability of every single item in a user's knowledge graph, making thousands of micro-decisions to optimize for retention. From a user experience perspective, the key design choice was to wrap this powerful, data-intensive process in a gamified, low-friction interface. The student doesn't see the complex algorithm; they experience a timely, enjoyable review session that feels helpful, not demanding. This focus on a seamless user experience is crucial for ensuring long-term adherence to the scientifically-backed review schedule.</p>
</div>
