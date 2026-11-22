# GOOGLE GEMINI PROMPT TEMPLATE: STAGE 1 INCANTATION
**Stage:** Chamber Stage 1: Muggle Studies (Order of Merlin, Third Class)  
**Primary AI Engine:** Google Gemini (Web interface: `gemini.google.com`)  
**Purpose:** Rapid pedagogical ideation and structured generation of a complete, unplugged tabletop classroom game.

---

## 1. The Master Prompt Template (Copy-and-Paste Incantation)
This prompt is dynamically constructed by the **Stage 1 Muggle Studies Terminal** (`stage1_muggle_studies.html`). Participants can customize the bracketed fields in the web interface or copy this raw template directly into Google Gemini:

```markdown
Act as an expert instructional game designer and master curriculum developer.

I need you to design a high-engagement, unplugged tabletop classroom game that requires ZERO digital devices for students to play.

### PARAMETERS:
- Target Grade Band: [INSERT GRADE BAND: e.g., Middle School (6th–8th Grade)]
- Content Subject: [INSERT SUBJECT: e.g., Science / STEM]
- Topic / Standard: [INSERT SPECIFIC TOPIC: e.g., Photosynthesis & Cellular Respiration]
- Core Game Vector: [INSERT VECTOR: e.g., Dice Race with Card Obstacles (2 D6 Movement Table)]
- Physical Materials Available: 2 six-sided dice (D6), blank index cards, sticky notes, markers.

### REQUIRED GAME SPECIFICATIONS:
1. GAME TITLE & NARRATIVE HOOK: 
   A compelling, age-appropriate title and a 2-sentence classroom storyline that hooks students into the challenge.
2. PLAYER STRUCTURE: 
   Designed for small collaborative groups of 3 to 6 students with clear turn-taking protocols.
3. THE 12 CHALLENGE CARDS: 
   Provide exactly 12 specific challenge/question prompts that my team will handwrite onto 12 index cards:
   - Cards 1–4: Foundational recall / definition challenges (1 point / 1 space).
   - Cards 5–8: Application / problem-solving challenges (2 points / 2 spaces).
   - Cards 9–12: "Wildcard" scenario challenges (high risk/reward, team debate, or bonus rolls).
   Include the correct answer/criteria for each card right below it.
4. DICE & MOVEMENT MECHANICS:
   A clear, intuitive roll table for the 2 D6 dice that dictates turns, movement, or resource gathering (e.g., sum totals, odd/even rules, doubles bonuses).
5. STICKY NOTE MECHANICS:
   Explain how sticky notes are utilized as player tokens, status counters, or a mini tabletop track.
6. WIN CONDITION:
   A decisive, achievable win condition reached within 8 to 12 minutes of active classroom play.

Format the output with clean markdown headings and bullet points so my team can immediately divide up and handwrite our 12 cards and rules.
```

---

## 2. Anatomical Breakdown of the Prompt Architecture
Why this prompt produces exceptional, immediate results in professional development:

1. **Role Framing (*"Act as an expert instructional game designer..."*):** Sets the persona to prioritize pedagogy, student engagement, and rule clarity rather than generic trivia.
2. **Hard Material Constraints (*"ZERO digital devices... 2 D6 dice, index cards, sticky notes"*):** Prevents Gemini from suggesting digital apps, tablets, or complex store-bought board game components.
3. **Explicit Output Quantity (*"Provide exactly 12 specific challenge/question prompts"*):** Guarantees that the team receives the exact number of cards needed to distribute evenly across 4–6 table participants (e.g., 2–3 cards per wizard) without manual trimming.
4. **Cognitive Tiering (Cards 1–4, 5–8, 9–12):** Scaffolds the content along Bloom's Taxonomy:
   * *Tier 1 (Cards 1–4):* Low-floor recall to build early confidence.
   * *Tier 2 (Cards 5–8):* Moderate application and conceptual reasoning.
   * *Tier 3 (Cards 9–12):* High-ceiling scenarios, dynamic debate, and strategic risk.
5. **Time-Bound Win State (*"within 8 to 12 minutes"*):** Ensures games are tight, actionable, and fit comfortably into standard classroom station rotations.

---

## 3. The Three Game Vectors (Mechanic Profiles)

| Vector Option | Best For | Core Mechanic | Classroom Feel |
| :--- | :--- | :--- | :--- |
| **Vector A: Dice Race with Card Obstacles** | Math, Science, Fact Retention | Players roll 2 D6 to advance tokens on a sticky-note track; landing on challenge spaces triggers card draws. | High energy, fast-paced, linear board game experience. |
| **Vector B: Card-Matching & Resource Battle** | Biology, History Timelines, Vocabulary | Dice rolls determine resource gathering (mana, fuel, atoms); players spend resources to match or resolve challenge cards. | Strategic, collaborative, puzzle-oriented gameplay. |
| **Vector C: Turn-Based Knowledge Duel** | ELA Debates, Social Studies Dilemmas, High School Ethics | Two teams duel along a tug-of-war sticky track by successfully answering and defending card prompts. | Deliberative, argumentative, high-stakes peer engagement. |

---

## 4. Subject-Specific Calibration Examples

### Example A: Middle School Science (Ecosystems)
* **Topic:** *Energy Transfer in Food Webs & Trophic Levels*
* **Vector:** *Card-Matching & Resource Battle*
* **Gemini Card Sample:**
  * *Card 2 (Recall):* "Define a primary consumer and name one in a grassland ecosystem." (Answer: Herbivore that eats producers; e.g., rabbit or grasshopper).
  * *Card 7 (Application):* "If a disease wipes out 80% of frogs in a pond, predict the immediate impact on mosquito and hawk populations." (Answer: Mosquitoes surge; hawks seek alternative prey).
  * *Card 11 (Wildcard):* "Drought Strikes! Roll 2 D6. If the sum is 7 or higher, your ecosystem survives. If lower, lose 2 energy tokens."

### Example B: High School US History (Constitutional Law)
* **Topic:** *The Bill of Rights & Landmark Supreme Court Cases*
* **Vector:** *Turn-Based Knowledge Duel*
* **Gemini Card Sample:**
  * *Card 3 (Recall):* "Which amendment protects against unreasonable searches and seizures?" (Answer: 4th Amendment).
  * *Card 6 (Application):* "A school principal searches a student’s backpack based on a rumor. Does this violate the 4th Amendment under *New Jersey v. T.L.O.*? Explain." (Answer: No, schools require only 'reasonable suspicion').
  * *Card 12 (Wildcard):* "Executive Order Challenge! Debate whether national security overrides free speech in wartime. Opposing table votes on winner."

---

## 5. Facilitator Coaching Tips During Gemini Generation
* **If Gemini outputs generic questions:** Instruct teachers to add one sentence to the prompt: *"Make the questions specifically aligned to standard [State/NGSS/Common Core code]."*
* **If a table finishes in 2 minutes:** Remind them that Stage 1 requires a **physical tabletop prototype**! Gemini generates the blueprint; the educators must physically write the 12 cards, test the dice roll, and crack the terminal cipher.
