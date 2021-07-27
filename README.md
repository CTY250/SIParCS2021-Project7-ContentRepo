# SIParCS2021-Project7-ContentRepo
Content Related to Presentations and Poster for Project 7 of SIParCS 2021

Hello! This is a repository storage for Project 7 of the 2021 SIParCS program hosted by NCAR/UCAR.
Here, you may access supplementary material associated to this project's poster, as well as presentation copies for additional reference material.

The following are some general conclusions established with this project's conclusion (5/17/2021 - 7/30/2021):
- Pair Programming through IntelliJ's Code With Me feature provided greater code reassurance when implementing new features
- Code refactoring results in an organized structure for the Harvester
- Harvester service converted to spring boot web application to allow developers to control the harvesting process of ISO XML metadata
- Harvester service harvests data without human intervention and recognizes changes based on file rather than repositories
- Solr index updates are made after immediate detection of GitHub changes.
- Developers can view ISO metadata GitHub link under "debug mode" in Search

Some suggestions for future development:
- Deleting files and reflecting on the local host machine for the search app will need to be looked into
- Treating GitHub repositories instead of local disk repositories as the authoritative source when getting metadata updates
- Implementation of autocomplete for search results
- Login and two-factor authentication (2FA) feature for Harvester controls
- Allowing developers to see a preview of ISO metadata when hovering over the ISO metadata link / Preview page of ISO metadata instead of directly linking it to the actual page
