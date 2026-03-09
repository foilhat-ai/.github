# Foilhat.ai
## A Student-Developed project to make credible information more accessible

Greetings! I've made my code private so that I can control who can copy it and take credit. If you are here looking for access, send me an email at gronkyd@gmail.com with your name, email, and why you want access; and I'll get back to you within a day.

-Daniel Weiss

https://github.com/user-attachments/assets/2697702d-9e9d-46d8-9ddf-0f749746ef6c

## Foilhat's Mission:
- To make differentiating between reporting and conspiracy effortless
- To make gathering information and citing sources easier
- To show the positive impact AI can have on research and journalism
- To NOT use AI if there is a better method by which a task can be done

## How it works:
* 2 part system: backend API and frontend web extension
* Web extension scrapes raw text from sites visited and checks for sensitive information before sending to backend API
* Backend processes data and sends to NVIDIA/OPENAI API to process
* Backend receives a JSON containing disputed/supported claims and sends to web extension
* Eeb extension alters HTML and CSS of website to display disputed claims and counter-sources

## Public TODO:
1. Create a more secure account system
2. Citation creator subfeature
3. Refine the control panel UI
4. Create a more reliable method of determining the credibility of a source (credibility database?)
5. Locally host an LLM so that we don't rely on a third party service (I will handle this, this is literally what my dad does for work)
6. Figure out a more precise, sustainable monetization plan
7. Create a customer landing page
8. Buy the domain (foilhat.ai) and host the webapp on it
9. Obtain legal rights to code and write terms of service
10. Artwork + advertising
