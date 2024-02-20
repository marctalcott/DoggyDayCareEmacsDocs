# DoggyDayCareEmacsDocs
Doggy Day Care EventModel created in Emacs as an example of building an software documenation using open-source plain text tools.

## What is this?
This is an example of how to build documentation in Emacs.

## Browse the Project:
   The root of the project os the MOC (map of content) file here:
   
[src/DoggyDaycare-MOC.org](src/DoggyDaycare-MOC.org)


Click the links to move to the Slices. From the slices you can click a link at the bottomve of each to get back to the MOC.

## Purpose:
Find a way to generate awesome documentation that meets the following requirements.
- Completely open source (no licensing costs).
- Completely plain-text source files.
  - No vendor lock-in.
  - Can be stored in source-control with our projects.
- Can be edited by any team member.
- Tools are freely available to everyone.

## Why?
I design software solutions.
I need to generate software diagrams and document infomration flows.
I need to avoid touching a mouse due to RSI.
I want plain-text files so we can store our docs in source-control.
I want simple, readable documents.
I want images and text together in the same docs.
I want completely open-source tools so that I don't have to worry about licensing costs.

## Tools:
- Emacs OrgMode
- PlantUML

## Alternates:
- Markdown: I tried Markdown as an alternate to Emacs OrgMode. Markdown itself works well but once I started learning more about Emacs and OrgMode I decided to invest some time in learning it and found that it provides an environment that gets me away from dependence on a mouse which was peronsally important due to the pain it causes my hands to use a mouse.
- Mermaid: I love the simplicity of Mermaid drawings, but I wasn't able to hack the layouts to force it to display in a way that mimics EventModeling (www.eventmodeling.org) flow properly.
- Draw.io: 
    - Not an option for me because it requires too much time on a mouse.
    - Also it is not plain text so it can't be stored in Source Control.
    - Not open source.
    - Vendor lock-in of file format.
- LucidChart:
   - Same problems as Draw.IO, 
   - Not free for teams.


