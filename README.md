# Softadels
A software development oriented version of Citadels

## Glossary
- **Stories**: each of the cards of the backlog. Each card has an estimation cost in story points that you need to pay for finishing it.
- **Story Points**: they precious time units you can spend to finish your stories.
- **Backlog**: Card pile
- **Board**: Player area
- **Finish a story**: pay its story points cost and add it to your board.
- **Sprint**: round.
- **Requirements**: Blue 
- **Testing**: Red
- **Development**: Green
- **Comms**: Yellow
- **Special**: Pink

## Characters
1. **IT Support**
    - The laptop of a character of your choice will stop working due to a maintenance update and can't contribute to the Sprint.
2. **Scrum Master**
    - A surprirse retrospective and workshop drains all the points of the character of your choice and are given to you.
3. **Product Owner**
    - Change of priorities!. Swap your stories with another player or change any number of stories with the backlog.
4. **Delivery Lead**
    - Claim the PSM I certificate at the end of the turn. 
    - Collect 1 story point per each Comms (yellow) story in your board.
5. **Business Analyst**
    - It's not a bug, it's a requirement: QA can't find bugs in your stories. 
    - Collect 1 story point per each Requirements (blue) story in your board.
6. **Developer**
    - Get one story point because you do shit. 
    - Collect 1 story point per each Development (green) story in your board.
7. **Architect**
    - Get 2 stories from the backlog. You can finish up to 3 stories in your turn.
8. **QA**
    - Severe bugs found during the implementation moves a finished Story back to the backlog paying it's estimation cost -1.
    - Collect 1 story point per each Testing (red) story in your board.
9. **UI/UX Designer**
    - You may beautify one or two of your stories adding one extra story point on each of the stories you are beautifying.

//TODO Devops Security 

## Cards
### Requirements
3x * Ticket

3x * * Epic

3x * * * Increment

2x * * * * * Roadmap

### Testing
3x * Test case

3x * * Device testing

3x * * * Performance testing

2x * * * * * Full regression

### Development
5x * Config change

4x * * Unit test

3x * * Refactor

3x * * * Pair programming 

3x * * * * Merge conflicts

2x * * * * * Functional test

### Comms
5x * * * Escalate

4x * * * * Change Process

3x * * * * * Sign new Contract


### Special
* * Fullstack ninja. This story is of the color of your choice.

2x * * * Software as a Service. QA can't find bugs in this story.

* * * * * MVP focus. Once per Sprint you may return to the backlog a story from your hand and receive 1 story point.

* * * * * Scope creep. Once per Sprint, you may spend 2 story points to draw 3 stories from the backlog.

* * * * * Advance planning session. If you choose to draw stories from the backlog in your turn, you draw 3 stories, keep one of your choice, and put the other 2 on the bottom of the backlog.

* * * * * Let me fix tha for you. When the QA finds bugs in a story, you may pay one story point to take the story into your hand. You may not do this if you are the QA.

2x * * * * * * Outsourcing. This story costs 6 story points to finish, but is worth 8 story points at the end of the game.

* * * * * * Extra Kanban board. If you choose to draw stories when you take an action, you keep both of the stories you have drawn.

* * * * * * It works in my local. The cost for the QA to find bugs in your stories is increased by one.

