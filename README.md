# UpdateMyManga

## Goal 
---
Create a system that will allow me to get reminded when it's time to change the source of a particular manga torrent in tachiyomi
---
## Problem 
As of July 24 2021, Tachiyomi does not have a system that allows the user to be reminded of whenever another source has the most updated chapters. There were times that I would be missing out on essential manga chapter to only realize that it's the fault of the source and not myself, the goal of this app/service is to change that.

# Expected Milestones

### Milestone 1 
- Get a general understanding of the basics that this project will entail (what do I need, api tokens, how to make an app??, SQL vs Firebase maybe???, Web scrapers instead of apis?) Design and UML / Sequence diagrams created.

### Milestone 2 
- Basic calling of the api in a postman setting on one particular well known manga source (MangaDex)

### Milestone 3 
- Backend of api functionality finished. Move api backend to an application, which will send manga name notifications to users phone.

### Milestone 4 
- Application is completed. The following HAS to be included in order for full functionality:
1. A history page (main page) that contains all past and current manga sources.  ie) [Manga name]: [Old source] -> [New source]. Each entry must have the date gorup to which it was updated. (Updated... Today, Yesterday, Last Week, Last Month, Older)
2. Notification system (previously mentioned) that must be clickable to open the application and show some sort of splash screen detailing more information
3. Ability to clear entire history and restart.
4. TBA - more will come as nesesary 

Milestone 5 - Setup a SQL database (if needed) that will store information regarding the manga sources. (This will assist in retaining memory for this project)

Milestone 6 - Link of SQL and application together completed. Test sample sources that are known to be deprecated. More sources added.

Milestone 7 - Atrempted integration of Tachiyomi and application. (Maybe Tachiyomi has multiple apis that will allow deletion of mangas from library and insertions to new ones?)

Final Milestone 8 - Completion of project. Polishing of code, and detailed documentation presented on GitHub (most of project should be on there anyway). Project emailed to taciyomi staff for possible integration for future update??

Possible Problems - API tokens (cost of maintenance and upkeep), Manga Title names (not the same usually; Japanese vs English name; order of the words in the name)

Results - What I expect for this project will be two fold: A more accurate understanding of the development process as well as a working system that can tell me if there is a more up-to-date manga from another source.

This is what I should recieve from a notification:
"Hey, <[Manga name]> needs to updated to <[New source]>!"
