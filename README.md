# windows-xp
A fun side project with a simulated Windows XP computer

I've been so bored that I really want something to build, but I had very few ideas. I remembered something I used to do all the time at after school care as a kid. 

In MSPaint, I would create fake desktops, fake browsers, the whole 9 yards to make them look as realistic as possible. Now that I have my master coding skills, I decided to take this project idea and revamp it into a browser web app that you can actually interact with. 

## Project Overview
This app will feature:
- A desktop interface resembling Windows XP
- A single window policy
  - For ease of implementation, v1 will only support one window at a time.
- Apps available as shortcuts on the desktop and in the start menu 
  - Internet browser with pre-set internet pages
    - Old school GeoCities
    - Old school Hotmail email
    - Old school Addicting Games
  - Minesweeper
  - Calculator
  - Notepad with save functionality
  - AIM with only one buddy and an already logged in account

For data persistence, I haven't yet decided if it will be persistent across refreshes/loading or if it will reset every time. 

## Architecture
### Front-end
- Desktop environment
  - Some sort of front-end framework
- Styling
  - Use a UI library or custom styling
- Real time communication
  - Use potentially websockets for communication with LLM

### Back-end
- Api Layer
  - REST APIs or potentially graphQL APIs for retrieving web pages,storing documents, chat memory
- Chat
  - Host LLM integrating into AIM app
- Data storage
  - Create structured data storage
 
## Implementation
1. System design and choosing tech
2. Boilerplate for technologies chosen for backend and frontend
3. Implement UI basic structure with links that don't necessarily work yet
4. Create REST API endpoints (maybe do before UI?) Do a wireframe of UI and then think of all the API endpoints that will be necessary?
5. ???
6. Integrate
7. Profit
