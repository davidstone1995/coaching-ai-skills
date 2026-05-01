---
name: icf-qualifier
description: Analyzes a coaching session transcript against the ICF 2025 Updated Core Competencies (ACC level) and produces a formatted qualification report. Modeled on the RaeNotes analysis format. Produces a DOCX report showing competency evidence, what was good, what was acceptable, what to improve, and a Pass/Fail submission recommendation. Upload the session transcript (and audio file if available) to run the analysis.
---

# ICF Qualifier: ACC Session Analysis Tool

**Requires:** coaching-foundation
**Produces:** DOCX qualification report (via docx skill)

---

## What This Skill Does

Analyzes a complete coaching session transcript against all 8 ICF 2025 Updated Core Competencies at the ACC level. Produces a report that:

- Identifies specific evidence (with timestamps and direct quotes) for each sub-competency
- Flags contra-evidence and missed opportunities
- Rates each competency: Demonstrated / Partial / Not Observable
- Provides targeted narrative feedback: what was good, what was acceptable, what to improve
- Delivers an overall Pass / Conditional Pass / Fail recommendation with reasoning

This is not a PCC-markers evaluation. It uses the 2025 ACC "Minimum Skills Requirements" framework -- the same document Stephanie Frost (ACC Mentor) uses for evaluation.

---

## What You Need to Provide

**Required:**
- Session transcript -- timestamped format preferred (PocketAI, JamieAI, Otter, or similar). Speaker-labeled format (Coach / Client) is ideal.
- Session date
- Client first name (or pseudonym)
- Session number in the coaching engagement

**Helpful:**
- Audio file (if uploaded, note verbal habit patterns: filler vocalizations, pacing, silence)
- Session length (total minutes)
- Any context about the client situation not visible in the transcript

---

## Analysis Methodology

### Step 1: Read the Full Transcript

Read the entire transcript before scoring anything. Build a picture of:
- Session length and arc (beginning, middle, close)
- Whether the coach established agreements at the start
- How the coach handled the middle section (surface vs. depth)
- Whether the coach directed or invited
- How the session was closed

### Step 2: Identify Evidence Per Sub-Competency

Go through all 8 competencies and their sub-items. For each sub-item:

**Demonstrated (☑):** Clear behavioral evidence in the transcript. Must cite:
- Timestamp (e.g., 04:36)
- Direct quote from the transcript (verbatim, italicized)
- Count of instances

**Contra-Evidence / Missed Opportunity (⚠):** Something in the transcript that works against this competency, OR a clear moment where this sub-competency was needed and was absent.
- Timestamp
- Quote or description of what happened
- Brief note on what should have happened instead

**Not Observable (☐):** No evidence in either direction. Some sub-competencies are not expected to appear in every session (e.g., 1.07 referrals, 2.08 seeking outside help). Note these but do not penalize.

### Step 3: Rate Each Competency Overall

After assessing all sub-items within a competency, assign an overall competency rating:

| Rating | Meaning |
|---|---|
| **Strong** | Multiple sub-items demonstrated with clear, specific behavioral evidence across beginning, middle, and close |
| **Adequate** | Core sub-items demonstrated; some gaps but not disqualifying |
| **Weak** | Few sub-items demonstrated, or only at one part of the session (e.g., only at open/close), or with notable contra-evidence |
| **Not Demonstrated** | Little to no observable evidence; would be flagged by an ICF evaluator |

### Step 4: Generate Narrative Feedback (Per Competency)

For each of the 8 competencies, write three short sections:

**What Was Good:** Specific, named behavior from the session. Not "you showed presence" -- "at 13:17, you named a shift in the client's countenance before they named it themselves. That is observable presence." One to three sentences.

**What Was Acceptable:** What functioned but didn't stand out. What met the minimum threshold without being distinctive. Be honest here -- this is where ICF evaluators may be neutral.

**What to Improve:** Specific, actionable feedback. Reference the transcript moment where the improvement opportunity was. Tie to the competency number and sub-item. One to three concrete suggestions.

### Step 5: Assess Depth of Middle Section

This is the most common failure point at ACC level (per Stephanie Frost, ACC Mentor). Specifically evaluate:

- Did the client stay surface-level (listing, planning, strategy) for more than 10-12 minutes without the coach pivoting?
- Did the coach use the obstacle question: "What's really getting in your way?"
- Did the coach use the perspective/feeling question: "How do you feel about this right now?"
- Did the coach use the insight question: "What's your biggest insight so far?"
- Did the coach distinguish between coaching and co-creating/consulting?

If the middle section was surface-level strategy planning without a pivot to obstacle, feeling, or insight: flag this explicitly. It is the most common reason ACC submissions fail.

### Step 6: Check for Disqualifying Patterns

These will result in a Fail recommendation regardless of other competency scores:

- **Advice-giving:** Coach told the client what to do, what the issue was, or what the answer is
- **Consulting:** Coach co-created strategy, offered solutions, or framed the problem for the client
- **Coach-inserted language:** Metaphors, analogies, or frameworks introduced by the coach that weren't drawn from the client's own words
- **No depth work:** Entire session stayed at surface level (topics, lists, action items) without touching belief, feeling, obstacle, or identity
- **No agreement established:** Session began without a clear focus, success measure, or outcome named by the client
- **No close:** Session ended without reflection, learning, or a named next step from the client

### Step 7: Overall Pass / Conditional Pass / Fail

**Pass:** All 8 competencies show at least Adequate rating; no disqualifying patterns; session has clear beginning (agreements), middle (depth work), and close (reflection + action).

**Conditional Pass:** Mostly adequate, with 1-2 weak areas that are correctable with targeted practice. Recommend specific rework before submission.

**Fail:** One or more disqualifying patterns present; OR 2+ competencies rated Not Demonstrated; OR middle section showed no depth work at all.

---

## The 8 Competencies and All Sub-Items

Reference for analysis. Use these exact IDs and text in the report.

### C1: Demonstrates Ethical Practice
1.01 Demonstrates personal integrity and honesty in interactions with clients, sponsors and relevant stakeholders
1.02 Is sensitive to clients' identity, environment, experiences, values and beliefs
1.03 Uses language appropriate and respectful to clients, sponsors and relevant stakeholders
1.04 Abides by the ICF Code of Ethics and upholds the Core Values
1.05 Maintains confidentiality with client information per stakeholder agreements and pertinent laws
1.06 Maintains the distinctions between coaching, consulting, psychotherapy and other support professions
1.07 Refers clients to other support professionals, as appropriate

### C2: Embodies a Coaching Mindset
2.01 Acknowledges that clients are responsible for their own choices
2.02 Engages in ongoing learning and development as a coach, including remaining aware of current coaching best practices and use of technology
2.03 Develops an ongoing reflective practice to enhance one's coaching
2.04 Remains aware of and open to the influence of biases, context and culture on self and others
2.05 Uses awareness of self and one's intuition to benefit clients
2.06 Develops and maintains the ability to regulate one's emotions
2.07 Mentally and emotionally prepares for sessions
2.08 Seeks help from outside sources when necessary
2.09 Nurtures openness and curiosity in oneself, the client, and the coaching process
2.10 Remains aware of the influence of one's own thoughts and behaviors on the client and others

### C3: Establishes and Maintains Agreements
3.01 Describes one's coaching philosophy and clearly defines what coaching is and is not for potential clients and stakeholders
3.02 Reaches agreement about what is and is not appropriate in the relationship, what is and is not being offered, and the responsibilities of the client and relevant stakeholders
3.03 Reaches agreement about the guidelines and specific parameters of the coaching relationship such as logistics, fees, scheduling, duration, termination, confidentiality and inclusion of others
3.04 Partners with the client and relevant stakeholders to establish an overall coaching plan and goals
3.05 Partners with the client to determine client-coach compatibility
3.06 Partners with the client to identify or reconfirm what they want to accomplish in the session
3.07 Partners with the client to define what the client believes they need to address or resolve to achieve what they want to accomplish in the session
3.08 Partners with the client to define or reconfirm measures of success for what the client wants to accomplish in the coaching engagement or individual session
3.09 Partners with the client to manage the time and focus of the session
3.10 Continues coaching in the direction of the client's desired outcome unless the client indicates otherwise
3.11 Partners with the client to end the coaching relationship in a way that respects the client and the coaching experience
3.12 Revisits the coaching agreement when necessary to ensure the coaching approach is meeting the client's needs

### C4: Cultivates Trust and Safety
4.01 Seeks to understand the client within their context which may include their identity, environment, experiences, values and beliefs
4.02 Demonstrates respect for the client's identity, perceptions, style and language and adapts one's coaching to the client
4.03 Acknowledges and respects the client's unique talents, insights and work in the coaching process
4.04 Shows support, empathy and concern for the client
4.05 Acknowledges and supports the client's expression of feelings, perceptions, concerns, beliefs and suggestions
4.06 Demonstrates openness and transparency as a way to display vulnerability and build trust with the client

### C5: Maintains Presence
5.01 Remains focused, observant, empathetic and responsive to the client
5.02 Demonstrates curiosity during the coaching process
5.03 Remains aware of what is emerging for self and client in the present moment
5.04 Manages one's emotions to stay present with the client
5.05 Demonstrates confidence in working with strong client emotions during the coaching process
5.06 Is comfortable working in a space of not knowing
5.07 Creates or allows space for silence, pause or reflection

### C6: Active Listening
6.01 Considers the client's context, identity, environment, experiences, values and beliefs to enhance understanding of what the client is communicating
6.02 Reflects or summarizes what the client communicated to ensure clarity and understanding
6.03 Recognizes and inquires when there is more to what the client is communicating
6.04 Notices, acknowledges and explores the client's emotions, energy shifts, non-verbal cues or other behaviors
6.05 Integrates the client's words, tone of voice and body language to determine the full meaning of what is being communicated
6.06 Notices trends in the client's behaviors and emotions across sessions to discern themes and patterns

### C7: Evokes Awareness
7.01 Considers client experience when deciding what might be most useful
7.02 Challenges the client as a way to evoke awareness or insight
7.03 Asks questions about the client, such as their way of thinking, values, needs, wants and beliefs
7.04 Asks questions that help the client explore beyond current thinking
7.05 Invites the client to share more about their experience in the moment
7.06 Notices what is working to enhance client progress
7.07 Adjusts the coaching approach in response to the client's needs
7.08 Helps the client identify factors that influence current and future patterns of behavior, thinking or emotion
7.09 Invites the client to generate ideas about how they can move forward and what they are willing or able to do
7.10 Supports the client in reframing perspectives
7.11 Shares observations, insights and feelings, without attachment, that have the potential to create new learning for the client

### C8: Facilitates Client Growth
8.01 Works with the client to integrate new awareness, insight or learning into their worldview and behaviors
8.02 Partners with the client to design goals, actions and accountability measures that integrate and expand new learning
8.03 Acknowledges and supports client autonomy in the design of goals, actions and methods of accountability
8.04 Supports the client in identifying potential results or learning from identified action steps
8.05 Invites the client to consider how to move forward, including resources, support and potential barriers
8.06 Partners with the client to summarize learning and insight within or between sessions
8.07 Partners with the client to integrate learning and sustain progress throughout the coaching engagement
8.08 Acknowledges the client's progress and successes
8.09 Partners with the client to close the session

---

## Report Output Format

Produce a DOCX file using the docx skill. Read the docx SKILL.md before building.

### Report Structure

**Page 1: Header Block**
- Title: "ICF ACC Qualification Report"
- Session: "[Client first name or pseudonym] Coaching Session"
- Subtitle: "Assessed with ICF Updated Core Competencies (2025) -- ACC Level"
- Overall Result: PASS / CONDITIONAL PASS / FAIL (large, colored)
- Date | Coach: David Stone | Session: #[number] | Length: [X] minutes

**Executive Summary (Page 1 or 2)**
3-4 sentences. What was the overall arc of the session? Where was it strongest? Where did it need more depth? One-line recommendation. Written in plain English, not bullet points.

**Session Arc Assessment (short section)**
Quick assessment of the three required parts:
- Beginning (agreements established): Yes / Partial / No
- Middle (depth work achieved): Yes / Partial / No
- Close (reflection + next step named by client): Yes / Partial / No

**Competency Breakdown (one section per competency, C1-C8)**
For each competency:

1. Competency header with overall rating and evidence count (matching RaeNotes style)
2. Three-column table: Sub-competency | Evidence (timestamp + quote) | Contra-evidence / Missed opportunity
   - Checkboxes: ☑ = demonstrated, ☐ = not observed, ⚠ = contra-evidence present
3. Narrative boxes (three distinct labeled sections):
   - **What Was Good:** Specific behavioral observation from the transcript
   - **What Was Acceptable:** What met the bar without distinction
   - **What to Improve:** Specific, actionable, tied to a transcript moment and sub-competency ID

**Overall Submission Recommendation (final section)**
- Pass / Conditional Pass / Fail -- stated clearly at the top
- Reasoning: 3-5 bullet points explaining the decision
- If Conditional Pass or Fail: specific list of what needs to change before resubmission
- Next session guidance: what to focus on in practice before recording again

---

## Output Quality Check

Before delivering the report:

- Every demonstrated sub-competency has a timestamp and verbatim quote
- Every "What to Improve" point references a specific transcript moment and sub-competency ID
- The middle section depth assessment is honest -- if the session stayed surface-level, say so clearly
- No PCC markers used. ACC Minimum Skills only.
- No generic praise ("You did a great job!") -- specific behavioral observations only
- The Pass/Fail recommendation is defensible based on the evidence shown in the report
- Report is produced as a DOCX file using the docx skill
- File saved to coaching-ai-skills folder
- No em dashes
- No banned phrases from coaching-foundation

---

## How to Run This Skill

1. Upload the transcript file (PocketAI, JamieAI, .txt, .docx, or .pdf)
2. Provide session metadata: client name/pseudonym, date, session number, length
3. Optionally upload the audio file -- note any verbal pattern observations in the report (filler vocalizations, pacing, silence usage)
4. Claude reads the full transcript, runs the analysis, and produces the DOCX report
5. Report is saved to /Users/davidstone/Claude Work/coaching-ai-skills/

The analysis takes time. Read the full transcript before scoring anything.
