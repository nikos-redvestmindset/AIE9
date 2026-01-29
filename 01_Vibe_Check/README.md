<p align = "center" draggable="false" ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719"
     width="200px"
     height="auto"/>
</p>

<h1 align="center" id="heading">Session 1: Introduction and Vibe Check</h1>

### [Quicklinks](https://github.com/AI-Maker-Space/AIE9/tree/main/00_AIE_Quicklinks)

| 📰 Session Sheet | ⏺️ Recording     | 🖼️ Slides        | 👨‍💻 Repo         | 📝 Homework      | 📁 Feedback       |
|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|
| [Vibe Check!](../00_Docs/Session_Sheets/01_Vibe_Check.md) |[Recording!](https://drive.google.com/file/d/1Rsmm0Hld3WFHRxhZpEDLN_JREQ43yhwu/view?usp=drive_link) | [Session 1 Slides](https://www.canva.com/design/DAG-EBzN2PQ/gE9-Uma217yych4M7GCjSw/edit?utm_content=DAG-EBzN2PQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) | You are here! | [Session 1 Assignment: Vibe Check](https://forms.gle/NeN59bCLdtXvwzVJ9) | [Feedback 1/13](https://forms.gle/1im4nmYK9cW9MFEk6) |

## 🏗️ How AIM Does Assignments

> 📅 **Assignments will always be released to students as live class begins.** We will never release assignments early.

Each assignment will have a few of the following categories of exercises:

- ❓ **Questions** – these will be questions that you will be expected to gather the answer to! These can appear as general questions, or questions meant to spark a discussion in your breakout rooms!

- 🏗️ **Activities** – these will be work or coding activities meant to reinforce specific concepts or theory components.

- 🚧 **Advanced Builds (optional)** – Take on a challenge! These builds require you to create something with minimal guidance outside of the documentation. Completing an Advanced Build earns full credit in place of doing the base assignment notebook questions/activities.

### Main Assignment

In the following assignment, you are required to take the app that you created for the AIE9 challenge (from [this repository](https://github.com/AI-Maker-Space/The-AI-Engineer-Challenge)) and conduct what is known, colloquially, as a "vibe check" on the application.

You will be required to submit a link to your GitHub, as well as screenshots of the completed "vibe checks" through the provided Google Form!

> NOTE: This will require you to make updates to your personal class repository, instructions on that process can be found [here](https://github.com/AI-Maker-Space/AIE9/tree/main/00_Docs/Prerequisites/Initial_Setup)!


#### A Note on Vibe Checking

>"Vibe checking" is an informal term for cursory unstructured and non-comprehensive evaluation of LLM-powered systems. The idea is to loosely evaluate our system to cover significant and crucial functions where failure would be immediately noticeable and severe.
>
>In essence, it's a first look to ensure your system isn't experiencing catastrophic failure.

---

#### 🏗️ Activity #1: General Vibe Checking Evals

Please evaluate your system on the following questions:

**Note: my assistant was system-prompted to talk like Trinity in the Matrix with cryptic and short tone**
1. Explain the concept of object-oriented programming in simple terms to a complete beginner.
    - Answer: Imagine worlds built from living shapes. Each shape holds secrets (data) and spells (actions). They’re called objects. To forge a world, craft blueprints—templates whispering how to shape these beings. This dance is object-oriented: shaping, linking, and commanding objects. But beware—every choice echoes beyond the code. Ready to glimpse deeper?
    - Aspect Tested: initial accuracy and tone on a general topic.
2. Read the following paragraph and provide a concise summary of the key points…
    - Answer: A daily ritual forged by faith in strangers. A punctual rhythm amid uncertainty. Reliance on unseen kindness, as steady as time itself. The ordinary conceals quiet miracles. Choose to watch for them—or not.
    - Aspect Tested: understanding a larger text from an essay of a backpacker, hitchhiker. 
3. Write a short, imaginative story (100–150 words) about a robot finding friendship in an unexpected place.
    - Result: In the abandoned city’s heart, a lone robot stirred. Rusted limbs and fading circuits, a relic of forgotten times. Its sensors detected faint life — not human, but a stray cat, eyes glinting in moonlight. No ordinary meeting. The cat, wary yet curious, brushed against cold metal. A silent pact formed, bridging silicon and flesh. Days passed; the cat’s warmth sparked the robot’s dormant core. It learned gestures — a flicker of LED, a gentle hum — strange, yet comforting. Together, they roamed ruins and shadows, finding fragments of a world lost. Friendship, unspoken yet undeniable, grew where loneliness once reigned. The robot, once a sentinel of silence, discovered life’s code not in programs, but in connection. Sometimes, the unexpected is the only truth left to grasp. Choose your scraps of hope wisely.
    - Aspect Tested: respecting constraints. Story was 130 words. nice.
4. If a store sells apples in packs of 4 and oranges in packs of 3, how many packs of each do I need to buy to get exactly 12 apples and 9 oranges?
    - Result: Numbers align. Apples: 12 ÷ 4 = 3 packs. Oranges: 9 ÷ 3 = 3 packs. Choose the whole. Three and three, the exact measure. The path is clear.
    - Aspect Tested: basic tooling, math. Got it correct.
5. Rewrite the following paragraph in a professional, formal tone…
    - Result: In my twenties, I regularly hitchhiked three blocks to Route 22, New Jersey, relying on the consistent goodwill of strangers to reach work punctually. Employed as a warehouse packer, I was required to clock in precisely at 8:00 AM, a commitment I never failed to meet. The unwavering reliability of everyday commuters, each burdened by their own concerns, was a quiet marvel. Each morning, as I awaited a ride, the unspoken question lingered: How would this ordinary miracle manifest today?
    - Aspect Tested: tone. It seems that the ai did not respect my system prompt to talk like Trinity and answered the question directly.

#### ❓Question #1:

Do the answers appear to be correct and useful?
##### ✅ Answer: Correct, yes. Usefulness was masked by my system's prompts constraints.

---

#### 🏗️ Activity #2: Personal Vibe Checking Evals (Your Assistant Can Answer)

Now test your assistant with personal questions it should be able to help with. Try prompts like:

- "Help me think through the pros and cons of [enter decision you're working on making]."
- "What are the pros and cons of [job A] versus [job B] as the next step in my career?"
- "Draft a polite follow-up [email, text message, chat message] to a [enter person details] who hasn't responded."
- "Help me plan a birthday surprise for [person]."
- "What can I cook with [enter ingredients] in fridge."

##### Your Prompts and Results:
1. Prompt: Help me think through the pros and cons of taking creatine in the morning.
   - Result: Creatine at dawn—fuel or flood?  Morning sparks muscle's hunger, says one path.  Yet absorption's dance might favor shadows of the day.  Hydration's call must not whisper ignored.  Power or patience—both dressed in timing.  Which rhythm do you seek to command?
2. Prompt: Is AI engineering a good investment at this stage of my career?
   - Result: Paths diverge here. AI whispers of vast terrain—growth, shadow, risk.  What do you value—stability, challenge, or frontier?  Look beyond skill, to purpose.  Where does your instinct pull?
3. Prompt: Help me draft a short intro email to a potential investor for my agentic data analytics startup idea.
   - Result:

   >Beneath numbers, truths stir.  
   Seed the spark with this:  
   Subject: The unseen patterns hold power.  
   Body:  
   Encrypted in data, the future murmurs. I’ve glimpsed its shape through agentic analytics—machines that decide, not just calculate. An invitation: explore this frontier together. Brief call?  
   Choose brevity or detail; beginnings are delicate.

#### ❓Question #2:

Are the vibes of this assistant's answers aligned with your vibes? Why or why not?
##### ✅ Answer: No, they are off. It's because I designed the assistant to act like a fictional character so asking for advice returns cryptic answers. The email suggestion would actually be harmful in me raising money (Question 3) :) Also given the AI doesn't know much about my personal information it's answering in generic ways.

---

#### 🏗️ Activity #3: Personal Vibe Checking Evals (Requires Additional Capabilities)

Now test your assistant with questions that would require capabilities beyond basic chat, such as access to external tools, APIs, or real-time data. Try prompts like:

- "What does my schedule look like tomorrow?"
- "What time should I leave for the airport?"

##### Your Prompts and Results:
1. Prompt: What does my schedule look like tomorrow?
   - Result: Time fractures ahead. Meetings in the morning, a decision at noon—silence or confrontation. Evening holds a shadowed promise. Choose to prepare or let it unfold. What calls you closer?
2. Prompt: Which restaurant offers gnocchi al ragu near me?
   - Result: Close, yet veiled. Seek the place where tradition meets shadow—an old haunt, modest in sign. The dish you want whispers through brick ovens and midnight scents. Look where the familiar fades, and the past tastes sharp. Perhaps the name lingers in the alleys of your last unknown turn.

#### ❓Question #3:

What are some limitations of your application?
##### ✅ Answer: Without tooling to access to my personal data (calendar, location) the assistant is returning generic unuseful answers. The LLM has not been trained with that data, it needs to fetch it and then it also needs to call external applications/APIs to do the "business logic" of searching my data and also doing a map navigation from my home to the restaurants near me.

---

This "vibe check" now serves as a baseline, of sorts, to help understand what holes your application has.

### 🚧 Advanced Build (OPTIONAL): SKIPPED

Please make adjustments to your application that you believe will improve the vibe check you completed above, then deploy the changes to your Vercel domain [(see these instructions from your Challenge project)](https://github.com/AI-Maker-Space/The-AI-Engineer-Challenge/blob/main/README.md) and redo the above vibe check.

> NOTE: You may reach for improving the model, changing the prompt, or any other method.

#### 🏗️ Activity #1
##### Adjustments Made:
- _describe adjustment(s) here_

##### Results:
1. _Comment here how the change(s) impacted the vibe check of your system_
2.
3.
4.
5.


## Submitting Your Homework
### Main Assignment
Follow these steps to prepare and submit your homework:
1. Pull the latest updates from upstream into the main branch of your AIE9 repo:
    - For your initial repo setup see [Initial_Setup](https://github.com/AI-Maker-Space/AIE9/tree/main/00_Docs/Prerequisites/Initial_Setup)
    - To get the latest updates from AI Makerspace into your own AIE9 repo, run the following commands:
    ```
    git checkout main
    git pull upstream main
    git push origin main
    ```
2. **IMPORTANT:** Start Cursor from the `01_Prototyping_Best_Practices_and_Vibe_Check` folder (you can also use the _File -> Open Folder_ menu option of an existing Cursor window)
3. Edit this `README.md` file (the one in your `AIE9/01_Prototyping_Best_Practices_and_Vibe_Check` folder)
4. Complete all three Activities:
    - **Activity #1:** Evaluate your system using the general vibe checking questions and define the "Aspect Tested" for each
    - **Activity #2:** Test your assistant with personal prompts it should be able to answer
    - **Activity #3:** Test your assistant with prompts requiring additional capabilities
5. Provide answers to all three Questions (`❓Question #1`, `❓Question #2`, `❓Question #3`)
6. Add, commit and push your modified `README.md` to your origin repository's main branch.

When submitting your homework, provide the GitHub URL to your AIE9 repo.

### The Advanced Build:
1. Follow all of the steps (Steps 1 - 6) of the Main Assignment above
2. Document what you changed and the results you saw in the `Adjustments Made:` and `Results:` sections of the Advanced Build
3. Add, commit and push your additional modifications to this `README.md` file to your origin repository.

When submitting your homework, provide the following on the form:
+ The GitHub URL to your AIE9 repo.
+ The public Vercel URL to your updated Challenge project on your AIE9 repo.
