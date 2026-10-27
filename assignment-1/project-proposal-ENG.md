# Assignment 1: Needfinding — Project "Wellbeing for Pensioners"

Course: **HCI Fundamentals (A.Y. 2026/2027)**
Instructors: **Luigi De Russis, Alberto Monge Roffarello** — Politecnico di Torino

---

## 1. Intro

### a. Team Members

* **Tommaso Mancuso**
* **Zarina Saden**
* **Taha Shahid**
* **Melissa Massarenti**

### b. Domain of Interest and Why/How You Chose It

* **Assigned general theme:** *Wellbeing for Pensioners* (Wellbeing in older age).
* **Problem Domain definition:** We narrowed our investigation down to the **transition and reorganization of post-work daily life**, focusing in particular on:
  1. The autonomous management of free time and the establishment of new daily routines;
  2. Actively maintaining physical and psychological wellbeing (gentle movement, self-care, nutrition, sleep);
  3. The structure of social relationships, neighborhood ties, and intergenerational dialogue;
  4. The role of local urban resources and the actual relationship (navigating barriers and opportunities) with digital technology.
* **Motivation and selection process:** Leaving the workforce marks a radical turning point: predetermined schedules, professional roles, and social interactions established over decades suddenly disappear. Many current digital services stem from flawed assumptions, treating retirees exclusively as frail individuals, chronically ill, or passive users. Our objective was to explore on the field — through observation and qualitative interviews in their real-life contexts — how people actually experience this phase. We aim to design a digital product that is not confined to the medical or assistive sphere, but rather acts as a social and motor enabler, enhancing autonomy, a sense of purpose, and the daily dignity of the retiree.

---

## 2. Methodology

### a. Participants

In full compliance with the course guidelines, we selected a diverse group of **5 real participants**, including direct users (*immediate users*) and extreme profiles (*extreme users*):

1. **Participant 1 (P1 - Male, 60+ years old):** *Immediate User / Reluctant Digital User*

   * **Profile:** Retired for about 8 years, former manual laborer with strenuous duties. Lives alone, manages household tasks independently, and cares daily for his brother admitted to the Spinal Unit.
   * **Why appropriate:** He represents the pragmatic, "do-it-yourself" user, living on a modest pension (€600) and showing a marked distrust toward digital devices: following the theft of his smartphone, he deliberately chose not to replace it, experiencing this disconnection as a relief (permanent *digital detox*).
   * **Recruitment:** Direct contact in an urban setting in Turin.
2. **Participant 2 (P2 - Female, 72 years old, "Anna"):** *Lead User / Active Cultural & Community User*

   * **Profile:** Retired for 10 years, former public administrator for the Metropolitan City of Turin with 42 years of service. A widow since 2021 (after years of caregiving for her husband who had severe mobility impairments), property owner, mother of 3, and grandmother.
   * **Why appropriate:** Shows a high level of education (classical high school, university studies) and strong proficiency with healthcare and administrative apps (Salute Piemonte, regional portals, email, scanner). She leads an active life (daily physical therapy exercises, swimming, theater, furniture restoration, knitting), but experiences severe insomnia linked to the solitary burden of decision-making regarding property management, along with minor memory slips for which she relies constantly on smartphone reminders.
   * **Recruitment:** Approached in context at a public park during her routine afternoon walk with her dog and friends.
3. **Participant 3 (P3 - Male, 67 years old):** *Extreme User (Ultra-Active & Intergenerational Bridge)*

   * **Profile:** Retired for 8 years after 45 years of work (former armed security guard working shift work for railways and public entities). Trains intensely at the gym 5 times a week, supports his family by taking grandchildren to school, assists his older dependent sister, and continues to work on weekends doing security at nightlife venues.
   * **Why an extreme user:** Positioned at the opposite extreme of the sedentary retiree stereotype. He uses night shifts to stay in contact with young adults aged 20–25, building educational and mediation relationships with them to avoid feeling "left behind." He displays exceptional physical vitality, sleeps very few hours without feeling fatigued, and is driven by a deep sense of personal redemption and self-sufficiency.
   * **Recruitment:** Direct encounter at a neighborhood café regularly visited after his gym workouts.
4. **Participant 4 (P4 - Female, 80 years old):** *Extreme User (High Independence with Sensory Limitations)*

   * **Profile:** 80 years old, long-time retiree, divorced for decades, lives alone in a 50 sq.m. studio apartment in San Salvario. Affected by severe visual impairment that prevents conventional reading and driving (she does not own a car or a driving license).
   * **Why an extreme user:** Despite her age and sensory impairments, she maintains complete domestic autonomy and relentless mobility on foot ("I am a camel") and on public transit. She developed creative mutual-aid neighborhood practices (cooking mashed potatoes in trays that she hangs on the doors of families with young children) and is an atypical, creative user of technology: she chats regularly with ChatGPT adopting a humorous, surreal persona (styled after "Cochi e Renato"), but encounters severe roadblocks when dealing with complex ticketing and booking interfaces.
   * **Recruitment:** Approached in context outdoors near Valentino Park / San Salvario.
5. **Participant 5 (P5 - Female, retiree):** *Immediate User (Leisure-Oriented, Low-Pace & Tech-Frustrated)*

   * **Profile:** Long-time retiree following an administrative career characterized by routine and monotony. Lives alone in a central/semi-central residential area, sold her car for economic and practical reasons, cherishes unhurried mornings, takes Pilates classes online from home to avoid traveling to a gym, reads printed newspapers and physical books, buys groceries from farmers at the local market, and firmly defends her right to "do nothing."
   * **Why appropriate:** Represents an emblematic figure of the non-hyperactive retiree: self-identified as slow-paced or lazy, she rejects the pressure of an over-scheduled calendar and experiences strong friction with smartphones and modern web interfaces (prefers traditional paper street maps over Google Maps, resents apps displacing websites, and finds generic help pages asking "was this page useful?" irritating and unhelpful).
   * **Recruitment:** Approached in context in an urban neighborhood setting / pastry café.

### b. Where Were the Interviews Conducted?

All interviews were conducted **in person within the everyday life contexts of the participants** (*in situ*):

* **P1:** Public urban space in Turin (transitional context during daily errands).
* **P2:** Bench in a city park, during an informal gathering with friends and her dog.
* **P3:** Table at a neighborhood café, his usual decompression spot post-workout and meetup location with former colleagues and acquaintances.
* **P4:** Green area / tree-lined avenue near Valentino / San Salvario, during one of her regular walking sessions.
* **P5:** Outdoor café table at a neighborhood pastry shop, during a morning break for coffee and newspaper reading.

### c. What Did You Observe and Ask?

* **Observation and Contextual Inquiry:** We observed body language, posture, movement patterns, and spontaneous interactions with the environment: the familiarity and warmth between P3, the café staff, and local youth; the care with which P2 brought her knitting kit and checked smartphone notifications; P4's careful navigation of sidewalk curbs and bus stops, compensating for low vision through sharp hearing and keen observation of people; the relaxed detachment of P5, who kept printed newspapers with her, handled her smartphone with suspicion, and defended her analog habits.
* **Interview Guide (Semi-Structured Protocol):** We designed and conducted a lean 4-phase guide grounded in HCI principles using open-ended, unbiased, and non-leading questions, avoiding premature assumptions of vulnerability and focusing on concrete past experiences:
  1. *Phase 1: Background & Context* (typical day, comparison between past work schedules and current daily life, relationship with home and neighborhood).
  2. *Phase 2: Going Deep: Social Connections & Self-Care* (organization of social ties, meal management, physical activity, rest, reminders, and deadlines).
  3. *Phase 3: Clarifications, Failures & Tools* (handling unexpected practical issues, sharing positive news, recent experiences using smartphones/apps, along with encountered barriers or workarounds).
  4. *Phase 4: Reflections & Closing* (most rewarding and most challenging aspects of life in retirement, open aspirations).

### d. Team Member Roles for Each Interview

Each interview was conducted on-site by team members fulfilling designated roles (lead interviewer and note-takers/observers):

* **Interview 1 (P1):** Tommaso Mancuso (*Lead Interviewer*), Zarina & Taha Shahid (*Note-taker & Audio Recording*).
* **Interview 2 (P2):** Tommaso Mancuso (*Lead Interviewer*), Zarina & Taha Shahid (*Note-taker & Artifacts Tracking*).
* **Interview 3 (P3):** Tommaso Mancuso (*Lead Interviewer*), Zarina & Taha Shahid (*Note-taker & Contextual Observation*).
* **Interview 4 (P4):** Tommaso Mancuso (*Lead Interviewer*), Zarina & Taha Shahid (*Note-taker & Contextual Observation*).
* **Interview 5 (P5):** Tommaso Mancuso (*Lead Interviewer*), Taha Shahid (*Note-taker & Contextual Observation*).

### e. Materials Used

* Printed informed consent forms (*Consent Form*) completed and signed by each participant prior to starting.
* Digital voice recorders on smartphones to capture complete audio tracks.
* Paper notepads for rapid note-taking, recording non-verbal cues, and capturing key quotes.
* Camera to document environments, relevant artifacts, and contextual settings.

---

## 3. Results

### a. Pictures and Relevant Artifacts

* **Photo 1 (Context P2):** Bag containing a knitting kit (handcrafted wool sweaters for grandchildren) and the smartphone reminder calendar for clinical appointments.
* **Photo 2 (Context P3):** Gym duffel bag and café table where he engages in daily conversations with peers and young workers.
* **Photo 3 (Context P4):** Piedmont Museum Card (*Abbonamento Musei*) and smartphone used for short-episode cultural audio tracks and conversational AI exchanges.
* **Photo 4 (Context P5):** Printed daily newspaper, physical city fold-out street map, and smartphone screen showing browser lookups and home fitness video sessions.
* **Photo 5 (Urban Mobility Context):** Neighborhood bus/tram transit stop and local bike lanes.

### b. Themes from the Thematic Analysis with Key Quotes

The inductive coding across the five transcripts revealed 4 overarching shared themes:

#### Theme 1: Reclaimed Freedom vs. Mental Overload / Defense of Slow Living

All participants celebrate leaving the workforce as an essential liberation: eliminating early morning alarm clocks and imposed schedules represents the peak of wellbeing. However, two polarities emerge: those who struggle with the solitary weight of practical decision-making (P2), and those who firmly assert the right to rest, leisure, and "doing nothing" without feeling obligated to fill up an agenda (P5).

* *P1:* "Since I retired I am very happy that I let go of work, which was too heavy... I have more freedom."
* *P3:* "Retirement truly gave me the breakthrough to take back what I couldn't have before... not having to wake up early in the morning at four to work exhausting shifts."
* *P2:* "The very demanding aspects are making decisions because I am alone, I can no longer discuss things with my husband... should I install solar panels? Should I replace the window frames? These are the kinds of thoughts that keep me awake at night."
* *P4:* "I became an independent woman... the greatest satisfaction is being independent as long as my health and mind hold up."
* *P5:* "Not having to set an alarm clock in the morning was pure liberation... since retiring I spend much more time doing nothing; I'm not one of those hyper-busy people who constantly have to do something."

#### Theme 2: Gentle Movement as a Pillar of Physical and Mental Health (Rejecting Forced Rigidity)

Regular physical activity (weight training, pain-relief gymnastics, brisk walks, Pilates) is perceived as the primary barrier against bodily decline and chronic joint pain. However, there is a clear preference for flexible, non-competitive, low-friction forms of exercise: from intense gym workouts (P3) to therapeutic routines (P2), continuous daily walking (P4), and online home sessions carried out without rigid schedules (P5).

* *P3:* "Exercising to the limit allows me to start the day differently, less monotonously; it completely clears my mind... I work out five times a week."
* *P2:* "I go to the gym every morning for pain-relief mobility exercises... I had back and sciatica issues so severe I couldn't get out of bed in the morning; once I started going to the gym, it went away."
* *P4:* "I am a camel in the sense that I walk a lot, an awful lot... I would love to do South American dancing where body discipline and music come together."
* *P5:* "I do online Pilates at home out of sheer laziness, so I don't even have to travel to a gym... I keep moving this way, because otherwise if you don't move, you end up rusty."

#### Theme 3: Selective Proximity Socializing, Intergenerational Exchange, and Rejection of Segregated Spaces

Participants do not seek generic entertainment or segregated senior facilities. The collective desire centers on authentic, self-paced socialization rooted in neighborhood mutual aid (P4), spontaneous yet quality street encounters (P1), enriching and reciprocal exchanges with youth (P3), and the freedom to close the front door and enjoy solitude whenever desired (P5).

* *P1:* "If there are worthwhile people, I gladly spend time with them; if I see it's not a good fit, I get up and leave... casual encounters on the street, nothing major."
* *P3:* "I enjoy being around people, I talk with young guys aged 20–25... my perspective today is to compare notes with youth so I don't get left behind."
* *P4:* "When I make a big batch of mashed potatoes, I put it into aluminum trays and hang them on the doors of neighbors with children... little by little they got used to leaving me fruit in return. Without being an overbearing grandmother."
* *P5:* "I enjoy chatting with people, but I also love being by myself: closing the door, saying 'the outside world stays out,' and being free from the obligation to socialize constantly."

#### Theme 4: The Digital Paradox: Practical Utility vs. Frustration, Intrusiveness, and App Saturation

All interviewees acknowledge the utility of digital technology when it directly addresses tangible tasks (health records, alerts, micro-conversations with AI). Nevertheless, significant saturation is evident: convoluted user interfaces, complex e-commerce checkouts, and the mandatory requirement to install dedicated apps for mundane services cause frustration, triggering drop-off (P4), a nostalgic return to paper maps and directories (P5), or total abandonment of smartphones (P1).

* *P1:* "Ever since my phone was stolen, I haven't used one... it saved my situation, so I'm no longer glued to the Internet and I don't care about any of it."
* *P2:* "Fortunately there's the phone with its alerts reminding me of things... I use Salute Piemonte for test results, but I am starting to forget appointments and words."
* *P4:* "Online reservations for concerts or guided tours freeze me up: I try on my own, then I call or give up, telling myself it wasn't meant to be. With AI, on the other hand, I chat like Cochi e Renato!"
* *P5:* "Everything goes through applications now: how on earth did we manage before apps? On websites you can't find a single thing, and Google Maps does whatever it wants instead of what I want: the old city street directory was far faster and clearer."

---

## 4. User Needs

### a. Brainstormed User Needs

*(Formulated as human and emotional necessities expressed with action verbs, rather than technical solutions or feature specifications):*

1. Retirees need a way to **maintain an engaging and active daily structure** without the rigidity of employment constraints.
2. Retirees need a way to **access tailored daily gentle physical activities** to prevent postural discomfort and preserve physical independence.
3. Retirees need a way to **find motivation and encouragement to move and leave the house** even on days marked by lethargy, fatigue, or loneliness.
4. Retirees need a way to **regularly interact with people across different generations** to stay up to date, feel useful, and remain connected to contemporary society.
5. Retirees need a way to **receive reassuring guidance on complex practical, logistical, and economic decisions** when living alone.
6. Retirees need a way to **build authentic, reciprocal neighborhood relationships** founded on small everyday acts of utility and mutual kindness.
7. Retirees need a way to **consume cultural and educational stimuli through short, accessible formats that minimize visual and cognitive fatigue**.
8. Retirees need a way to **join local activities, events, and tours without getting stuck in convoluted digital booking workflows**.
9. Retirees need a way to **navigate the city and access proximity services using clear, predictable routes** without being overwhelmed by opaque map algorithms.
10. Retirees need a way to **decompress from everyday mental tension and practical worries** to encourage restorative sleep.
11. Retirees need a way to **manage healthcare reminders and personal schedules reliably and unobtrusively**, eliminating the fear of missing deadlines.
12. Retirees need a way to **experience their free time at an unhurried, comfortable pace**, preserving quiet individual downtime without the pressure of forced hyper-socialization.

### b. 3–4 Deep User Needs

* **Deep Need 1: Retirees need a way to find regular, shared gentle physical activity opportunities within their neighborhood to relieve mental stress and preserve physical autonomy without performance pressure.**

  * *Thematic connection:* Rooted in **Theme 2** (*Physical activity as wellbeing*) and **Theme 1** (*Sovereignty over time*). P2, P3, P4, and P5 demonstrate that movement (walking, gym routines, joint mobility, Pilates) is the foundation supporting mental clarity and mitigating fear of functional decline, yet requires flexible, nearby options free of scheduling and logistical friction.
* **Deep Need 2: Retirees need a way to engage in spontaneous, equal-footing intergenerational interactions and neighborhood ties to preserve a sense of purpose, social usefulness, and connection to the present.**

  * *Thematic connection:* Rooted in **Theme 3** (*Proximity socializing and rejection of segregated spaces*). P3 actively seeks out conversations with young adults at nightlife venues to avoid feeling obsolete; P4 builds neighborhood bridges with young parents by sharing homemade meals; P1 and P5 prioritize genuine, casual everyday interactions. The need explicitly rejects isolated, age-segregated environments while preserving personal privacy boundaries.
* **Deep Need 3: Retirees need a way to discover and participate in neighborhood cultural, practical, and leisure activities through straightforward channels that eliminate the cognitive friction of complex online booking systems and app proliferation.**

  * *Thematic connection:* Rooted in **Theme 4** (*The digital paradox and access barriers*). Complex multi-step forms, account requirements, confusing digital maps, and convoluted e-ticketing lead to frustration and immediate drop-off (P4 missing out on guided visits, P5 rejecting apps in favor of physical street guides, P1 abandoning smartphones altogether). The need demands transparent, reassuring, and low-barrier local access.

---

## 5. Solutions

### a. Brainstormed Solutions (5 ideas per Deep Need)

#### For Deep Need 1 (Tailored physical activity and motor wellbeing):

1. *Drop-in Neighborhood Walking Groups:* Circular, low-barrier guided urban routes with regular gathering points in public parks and adaptable pacing, without mandatory attendance.
2. *Voice-Guided Gentle Mobility Coach:* Short audio routines for morning warm-ups, pain-relief stretching, and breathing exercises playable at home on the sofa or on a park bench.
3. *Active Safe Urban Route Map:* Interactive and printable local directory highlighting level pavements, shaded seating, public water fountains, and pedestrian zones free of car traffic and loud noise.
4. *Drop-in Open-Air Group Dance Sessions:* Weekly casual gatherings in pedestrian squares focused on rhythm-based individual dance (e.g., gentle Latin/folk music) without requiring a partner.
5. *Pace Pals (Walk with Me):* Proximity pairing system connecting neighbors to walk together during routine errands at scheduled, mutually agreeable times.

#### For Deep Need 2 (Intergenerational social exchange and community life):

1. *Neighborhood Skill Exchange Bank:* Asynchronous sharing platform where retirees offer hands-on crafts, traditional cooking, knitting, or plant care, while university students assist with heavy errands and technical troubleshooting.
2. *Neighborhood Story Cafés:* Informal breakfasts or evening drinks hosted at local cafés bringing together off-campus university students and long-time residents to share local stories.
3. *Shared Dish Bulletin Board:* Micro-community network to share extra portions of home-cooked dishes, produce, or book recommendations among neighbors.
4. *Shared Micro-Excursions:* Single-day group outings to regional landmarks and historic sites (e.g., Sacra di San Michele) utilizing shared shuttle transport between youth and older residents.
5. *Bite-Sized Listening Circles:* 20-to-30-minute group sessions listening to cultural podcasts followed by casual open discussion over tea or coffee.

#### For Deep Need 3 (Immediate access to local services and events):

1. *One-Step Conversational Voice Booking:* Natural-language voice/phone assistant allowing users to reserve seats and guided tours simply by speaking, with no complex forms or credentials.
2. *Local Tap-to-Join NFC Token/Badge:* Physical contactless card that users tap against totems at local libraries or cafés to register instantly for upcoming activities.
3. *Friendly Booking Desks at Newsstands and Cafés:* Assisted in-person booking spots within trusted everyday shops to receive printed confirmations and paper route maps.
4. *Weekly 90-Second Audio Digest:* Short on-demand voice bulletin summarizing the top three walk-accessible neighborhood events, free of invasive push notifications.
5. *Direct SMS Confirmation Flow:* Streamlined notification process delivering event dates, times, and addresses straight to basic SMS, eliminating accounts or PDF ticket downloads.

### b. Selected Solution Description (Top Solution)

Our selected solution is **"Step-by-Step": a civic neighborhood platform that enables micro-walks, gentle mobility sessions, and intergenerational skill exchanges (crafts, cooking, short cultural podcasts) between retirees and local youth, powered by an ultra-simplified conversational voice interface that allows users to discover and sign up for activities simply by speaking, removing complex forms and digital checkout flows.**

* **Connection to needs:** It simultaneously addresses **Deep Need 1** (encouraging daily outdoor walking and gentle physical activity in parks while respecting individual pacing), **Deep Need 2** (creating authentic opportunities to meet university students and young residents without patronizing dynamics or forced socializing), and **Deep Need 3** (removing digital barriers through voice-first interactions and direct confirmation via SMS/audio).

### c. How and Why Did You Select It?

* **Applied method:** We utilized the **Four-Category Method**, sorting the 15 brainstormed ideas into four quadrants:
  * *The Rational Choice:* The voice assistant for administrative and healthcare scheduling.
  * *The Most Likely to Delight:* Outdoor gentle Latin dance sessions in pedestrian squares.
  * *The Long Shot:* Citywide physical NFC totems deployed across local cafés and newsstands.
  * *The Darling:* **Step-by-Step: the voice-enabled intergenerational network for walks, practical exchanges, and neighborhood culture.**
* **Rationale (Why):** This solution aligns closely with the empirical insights gathered across all five interviews: it fulfills the drive for physical movement and vitality (P2, P3, P4, P5), responds to the desire to engage with youth as peers rather than dependents (P3, P4), respects the need for unhurried routines and personal boundaries (P5), and overcomes the friction of overly complex interfaces that led P1 to disengage from technology, caused P4 distress during online checkouts, and triggered P5's resentment toward mobile apps.

---

## 6. Project Name and Value Proposition

### a. How Did the Team Land on the Name?

The team explored several evocative working titles (*Controvento*, *Vicìno*, *Àncura*, *Girotondo*), ultimately reaching unanimous agreement on:

# **Step-by-Step**

* **Origin of the name:** The name draws on three complementary layers of meaning:
  1. *Physical step:* It evokes the simple, healthy everyday habit of walking together through neighborhood streets and parks;
  2. *Relational step:* It highlights the gradual, natural pace required to build trust between different generations;
  3. *Interaction step:* It reflects the interface experience, designed to guide users step by step with clarity, patience, and ease.

### b. One-Line Value Proposition

> **"The neighborhood that moves together: meetups, steps, and cross-generational exchange, all by voice."**
