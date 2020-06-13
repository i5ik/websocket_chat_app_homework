# Development environment: Chrome (on windows), vim, Node.JS on Debian

## Stage 1 (necessary requirements)
**[[DONE]]**
  - DONE make chat view: list and form
  - DONE add function to select latest chat message and scroll into view if needed (use css :last) (runs on rerender this route)
  - DONE add onsubmit to form to send message
  - DONE add onmessage handler to redraw whole app
  - DONE and onhashchange handler to redraw whole app (for settings/chat routes)
  - DONE add everything to settings (light/dark, crtl+enter, etc)
  - DONE add form to settings page
  - DONE add onsubmit to that form to save to localstorage
  - DONE add function to load settings from localstorage (runs on rerender this route)
  - DONE add a default settings static object
  - DONE well commented self-documenting code
  - DONE add css to fulfill minimal requirements (my message right, others messages left, responsive, landscape/portrait, light/dark mode)
  - DONE add title blinking effect if tab is not active
  - DONE test in Firefox, and Safari
  - DONE add tests layer 1 (use typescript to check types)
- add readme with features (required and optional sections)
- add tests layer 2 (basic unit tests as per issue)

## Stage 2 (my own improvement)
**[[DONE]]**
  - DONE use no frameworks, only vanilla JS (per response to question)
  - DONE format code nicely
  - optional ideas 1: add ephemeral key to messages, being the number of seconds they exist from delivery, after which they are deleted [[do not implement]] 
  - optional ideas 2: add encrypted flag to messages, indicating the message has been e2-encrypted using a password (private key, participants must share out of channel) [[do not implement]]
  - optional ideas 3: add a room list route (a view that just lists names of members in the room), and a room count on the chat route (number of members) [[do not implement]]
  - optional ideas 4: add a door list (in other words, you cannot get in unless your member name is on the list) [[do not implement]]

## Stage 3 (selected optional requirements)
- Add emoji keyboard (use emoji-button https://emoji-button.js.org/)

## Submission 
- Double check app against all requirements
- Document instructions in README
- Submit
