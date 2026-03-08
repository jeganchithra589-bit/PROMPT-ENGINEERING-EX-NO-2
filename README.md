# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## OUTPUT
zero-short prompt:
* prompt:
   The Taj Mahal is an ivory-white marble mausoleum in Agra, India.
* output in chatGPT Tool:
    About the Taj Mahal

Construction started in 1632 and was completed around 1653.
  - It is a white marble mausoleum (tomb).
  - Around 20,000 workers and artisans were involved in building it.
  - The chief architect is widely believed to be Ustad Ahmad Lahori.
  - It is now recognized as a UNESCO World Heritage Site and one of the New7Wonders of the World.
  - 
* output in Gemini Tool:
  
   It certainly is! Often cited as the "jewel of Muslim art in India," it’s one of the most universally admired masterpieces of the world's heritage.
 Commissioned in 1632 by the Mughal emperor Shah Jahan to house the tomb of his favorite wife, Mumtaz Mahal, it’s more than just a building—it's a massive complex that showcases the   height of Mughal architecture.

 Quick Facts for the Curious
_________________________________________________________________________________________________________________________________________________
 Feature                                 Detail
 
 Architectural Style                     Mughal (a blend of Persian, Islamic, and Indian)
 Material                                White marble inlaid with semi-precious stones
 UNESCO Status                           Designated in 1983
 Symbolism                               Widely regarded as the ultimate monument to love
_________________________________________________________________________________________________________________________________________________

* output in Perplexity Tool:
  
   Yes, that's correct. The Taj Mahal is indeed an iconic ivory-white marble mausoleum located in Agra, India.
Location Details:
It sits on the south bank of the Yamuna River in Agra, Uttar Pradesh, serving as the centerpiece of a 17-hectare complex that includes a mosque, guest house, and formal gardens.

Historical Background:
Commissioned in 1632 by Mughal Emperor Shah Jahan, it was built to house the tomb of his favorite wife, Mumtaz Mahal, who died during childbirth; construction took about 22 years with over 20,000 workers.

Architectural Highlights:
The structure features a massive central dome, four minarets, intricate inlay work with semi-precious stones, and symmetrical Indo-Islamic design elements made from white marble and red sandstone
   
_________________________________________________________________________________________________________________________________________________
Few-short prompt:

* prompt:
   The Taj Mahal is an ivory-white marble mausoleum in Agra, India, commissioned in 1632 by Mughal emperor Shah Jahan to house the tomb of his beloved wife, Mumtaz Mahal.
*output in ChapGPT Tool:

Construction started in 1632 and was completed around 1653.
   It is a white marble mausoleum (tomb).
Around 20,000 workers and artisans were involved in building it.
The chief architect is widely believed to be Ustad Ahmad Lahori.
It is now recognized as a UNESCO World Heritage Site and one of the New7Wonders of the World.

   The Taj Mahal is made of ivory-white marble that changes color depending on sunlight.
- Morning: Pink shade
- Daytime: Bright white
- Night / Moonlight: Golden or bluish glow
- The monument has:
- A large central dome
- Four tall minarets
- Symmetrical buildings on both sides
- A long reflecting pool in the garden shows a mirror image of the monument.

The Taj Mahal represents several meanings:
   Love: Built as a symbol of eternal love between Shah Jahan and Mumtaz Mahal.
Paradise: The gardens represent the Islamic concept of heaven.
Power and beauty: It also shows the wealth and artistic achievements of the Mughal Empire.

*output in Gemini Tool:

  The construction was a massive logistical undertaking that began around 1632 and finished roughly in 1653.
- The Labor Force:
  Over 20,000 artisans were brought in from across India, Persia, and the Ottoman Empire.
- The Materials: 
  While the core is brick and rubble, the exterior is faced with Makrana marble from Rajasthan. Over 1,000 elephants were used to transport these heavy slabs.
- The Technique:
  Instead of bamboo, builders used a massive brick scaffolding system. Legend says Shah Jahan told locals they could keep any bricks they hauled away, and the structure was dismantled almost overnight.
- The Inlay: 
  They used a technique called pietra dura, where thousands of tiny semi-precious stones (like lapis lazuli and jade) were carved and fitted into the marble to create floral patterns.

*output in Perplexity Tool:

 -  Yes, that's accurate—the Taj Mahal is an ivory-white marble mausoleum in Agra, India, commissioned in 1632 by Mughal emperor Shah Jahan for his beloved wife, Mumtaz Mahal (often spelled Mumtaz Mahal, completing "Mumtaz Mahal"). 
- Completion and Purpose
The full name is Mumtaz Mahal, meaning "Chosen One of the Palace," and she died in 1631 during childbirth, prompting Shah Jahan to build this as her tomb.
- Key Facts
Construction spanned roughly 22 years (1632–1653), involving over 20,000 artisans, and it also houses Shah Jahan's tomb. It's a UNESCO World Heritage Site famed for its symmetrical Mughal architecture blending Persian, Islamic, and Indian styles
_________________________________________________________________________________________________________________________________________________
Chain-of-thought:

*prompt:
  I need this in Step-by-Step Construction Process
   Choosing the Location
   Preparing the Foundation
   Building the Main Structure
   Constructing the Dome and Minarets
   Decorative Work
   
*output in ChatGPT Tool:
 ---- Step-by-Step Construction Process
Step 1: Choosing the Location
The site near the Yamuna River was selected for its beauty and stable ground.
The river also helped in transporting building materials.

Step 2: Preparing the Foundation
Deep wells were dug and filled with stones and materials to create a strong foundation.
A large raised platform was built to support the main structure.

Step 3: Building the Main Structure
The central mausoleum was constructed using white marble from Makrana (Rajasthan).
Large blocks of marble were transported using elephants and carts.

Step 4: Constructing the Dome and Minarets
A large central dome was built above the tomb.
Four minarets (tall towers) were built at the corners of the platform.

Step 5: Decorative Work
Skilled artists added calligraphy, carvings, and inlay designs using precious stones.
These stones included jade, crystal, turquoise, and lapis lazuli.

Step 6: Gardens and Surroundings
A beautiful Mughal garden (Charbagh) was created in front of the monument.
Pathways, fountains, and reflecting pools were added.

*output in Gemini Tool:
   To understand the Taj Mahal's journey from a concept to a world wonder, it is best to look at it as a chronological and structural sequence.

Here is the step-by-step breakdown of how it was conceived, built, and finished.

Step 1: The Vision and Site Selection (1631–1632)
The Catalyst: Following the death of Mumtaz Mahal in 1631, Shah Jahan transitioned from grief to a vision of a "Paradise on Earth" to house her remains.

The Location: A site was chosen on the banks of the Yamuna River in Agra. This was strategic for both the scenic beauty and the water supply needed for the elaborate gardens.

The Architects: A board of architects was led by Ustad Ahmad Lahauri, who blended Persian, Islamic, and Indian styles.

Step 2: Preparing the Foundation (1632–1633)
Soil Stabilization: Because the site was on a riverbank, builders dug deep wells and filled them with rocks and mortar to create a massive, stable foundation.

The Plinth: A large square platform (plinth) was constructed, elevating the mausoleum so it would be visible against the sky with no other buildings behind it.

Step 3: Raising the Structure (1633–1643)
The Core: The main structure was built using red sandstone and brick, which was then faced with white Makrana marble.

The Dome: A "double dome" technique was used. The inner dome provides the ceiling for the tomb, while the outer "onion" dome provides the massive exterior height.

The Scaffolding: Unlike modern wooden scaffolding, they built a massive brick scaffold. Legend says it was so large that Shah Jahan told the locals they could keep the bricks, and they dismantled it in a single day.

Step 4: The Artistic Finishing (1643–1647)
Pietra Dura (Stone Inlay): Artisans used tiny, precious stones (like lapis lazuli and jade) to create intricate floral patterns. These were carved into the marble so precisely that the joints are nearly invisible.

Calligraphy: Inscriptions from the Quran were created using black marble inlay. As the writing goes higher up the walls, the letters get slightly larger so that they appear uniform to a person standing on the ground.

*output in Perplexity Tool:
     The Taj Mahal's construction unfolded over 22 years (1632–1653), involving over 20,000 workers under chief architect Ustad Ahmad Lahauri.
     
Phase 1: Foundation and Platform (1632–1635)
Site preparation began with deep excavation (up to 35 feet) to reach stable soil, followed by a multi-layered foundation of compacted earth, wooden planks, stone masonry, and marble blocks to support the 35,000-ton structure. A raised marble platform was built to elevate the mausoleum above the gardens, with infrastructure like worker housing and material transport via 1,000 elephants established.
​
Phase 2: Main Mausoleum (1635–1643)
Walls used double-shell construction for strength and lightness, connected by tie stones; the central dome (double-shell design) took four years with massive scaffolding. Four minarets were built simultaneously, leaning slightly outward for optical verticality from below.
​
Phase 3: Decoration and Gardens (1643–1648)
Pietra dura inlay with 28 semi-precious stones (lapis lazuli, agate) and Quranic calligraphy were added panel by panel; formal Charbagh gardens, fountains, and water systems were planted and tested.

Phase 4: Completion (1648–1653)
Subsidiary structures like the mosque, guest house, and grand gateway were finished, with final landscaping, cleaning, and details ensuring symmetry across 18,038 marble blocks.
​

## RESULT
                 Zero-short       Few-short       Chain-of -thought
                 ChatGPT          Gemini          Perplexity
           
* Accuracy         4                5               4

* Coherence        5                4               3 

* Simplicity       3                4               3

* Speed            4                5               5

* User experience  5                5               4

Considering the above prompts and outputs, ChatGPT provides the best summary in terms of accuracy,Coherance, Simplicity, Speed, User experience.
