#RunResults
A desktop C#/.NET organizer of athletic competitions

Express my gratitude to my mentor Andrii Dashkovets

Purpose of application:
This application represents a simple organizer allowing runners to track their progress and generate categorized results for competitions.

Directories structure:
Debug – contains working version of application with local database (requires SQL server localDb v.11, .NET4.5);
Project Documents – requirements and development notes;
RunResults – source code;
ScreenShots – application UI and workflow.

Key features:
- Asynchronous data loading on startup;
- Timing of selected races, creating scancodes for runners;
- Persistence of runners data (CRUD);
- PDF/CSV export/import with support for sorting/filtering data;
- “Hamburger” navigation menu.

Target device/platform:
Tablet/windows7, 8.1 with .NET4.5

Tools:
VisualStudio2013, SQL server localDb v.11

Application frameworks/components:
SQL database, Entity framework 6, Windows forms, Metro framework (a little bit edited)

Used patterns:
MVP (using custom user controls), generic repository
