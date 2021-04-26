# Introduction

🎉 Congrats 🎉 - If you got here that means we really like you and want you on our team! 

This challenge is a great example of the type of work that Pensight engineers do. We hope that you have fun tackling it.

# The Challenge

## Step 1 - Build

Build a simple single-page video call web application using the Twilio Video.js library.

### Lobby Screen

This is the first page that any user who opens the app should see.

The user should be presented with a form that asks them to input their name and the name of the room that they want to join. The user should be connected to the video call when the form is submitted.

### Room Screen

This is where all the action happens.

After the user has entered the requested information in the lobby, they should be connected to the relevant video call room. 

Display all the names of all call participant names and their video streams. The video of the participant who is speaking should be much bigger than the others.

Have buttons that allow the user to mute their own audio or video.

Have a button that allows the user to leave the room and return to the lobby.

## Step 2 - Extend

Add a feature or two that you find interesting. Some options:

* Screen sharing
* Local or remote participant audio level indicator
* Camera and microphone test in the lobby
* Video background filter
* A way to switch camera or microphone inputs
* A way for call participants to "raise a hand", i.e. indicate to others that they want to speak

## Step 3 - Document

Write a README.md file. Be sure to:
1. Provide basic intructions on how to start the app
2. Mention how much time you spent on the task
3. Describe what you would do if you had more time 
4. Explain the reasoning behind your technical and architectural choices
5. Describe what is needed to make your prototype into a production-ready app

## Step 4 - Submit

Put your code on a public GitHub repository and send us an email with the link and we'll get back to you ASAP. Maybe the next time we speak it will be via your app!

Please don't mention our company name anywhere in the repository - wouldn't want future candidates to find it.

Feel free to show it off to your friends or even share it with other potential employers.


# How we review


What we care about:
* **Quality over feature-completeness.** It is fine to leave things aside provided you call them out in your project's README.
* **Correctness.** Does the application do what was asked? Does it handle errors well? If there is anything missing, does the README explain why it is missing?
* **Code quality.** Is the code simple, easy to understand, and maintainable? Are there any code smells or other red flags?
* **UX/UI.** Is it intuitive and pleasant to use? Does it fail gracefully? We don't expect you to apply beautiful styling but having a responsive layout is important.
* **Technical choices.** Do choices of libraries, architecture etc. seem appropriate for the chosen application?



What we won't check in this challenge:
* **Testing**. Write tests only if you find them useful. It is hard to test this type of application and we don't expect you to solve this problem given the time constraints.
* **Security**. Call out potential vulnerabilities but don't worry about fixing them.
* **Commit history**. Feel free to squash all your commits if you want to.

# FAQ

If you'd like any further clarification on the task don't hesitate to email!


### What language, framework, libraries should I use?

**Language:** TypeScript or JavaScript.

**Framework:** any React-based framework, popular choices include [create-react-app](https://create-react-app.dev/) and [Next.js](https://nextjs.org/)

**Libraries:** whatever makes you more productive

### Can I use something other than React?

React is preferred but if you haven't used it and don't have much time to learn it, Angular, Vue or Svelte are fine too. 

### Do I need a Twilio account?

Yes. You'll need it to access the Twilio Video.js SDK. Sign up for a free account [here](https://www.twilio.com/try-twilio)

### Do I need a backend server?

You might find some examples online that use a backend server to fetch Twilio API access tokens.

You can instead fetch these tokens in your frontend. It's not secure but perfectly fine to do for this challenge.

