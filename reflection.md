# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").
- The first thing i noticed was the difficutlty range, i expected hhard level to have a wider range but fewer attemps, but here normal has a wider range than hard.
- The feedback i received when i entered a number higher than the actual number tell me to go higher not lower, and opposite goes for lower number, which is logically wrong.
- The game says that I have a set of attempts but when i only have one attempt remaining, it says that I am out of attempts.

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)? Copilot
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result). changing the logic of the hard and normal levels definitions
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result). i did not find any.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed? when running the code on the browser and the hints and winning were smooth and with a logic reasoning.
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code. for the hint on high and low i used a number and try to see the kind of hint the game was giving and if it was correct.
- Did AI help you design or understand any tests? How? yes, it explained why the test was used, and why the approach was better.

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app. at first it wasn't changing until  i clicked on start a new game.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit? it can be tricky, and you need the refresh the page to observe updates.
- What change did you make that finally gave the game a stable secret number? did not fix that since it was mention 3 bugs..

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
