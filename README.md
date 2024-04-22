# Code-Standards

Hardware:
* All variables names should be in camelCase.
* All function names should be in camelCase.

Frontend:
* API functions should be kept in the /api folder.
* assets like gifs/images/svgs should be kept in /assets folder.
* constants should be kept in /constants folder.
* all React components should be kept at /features folder (not including App.jsx and main.jsx).
* all React components should have an .jsx extension.
* In /features folder, each feature should have its own folder (for ex: Dashboard Page => /Dashboard).
* In /features folder, all components except the page should be kept in /components folder.
* /network folder should have netork related functions.
* /endpoints folder in /networks folder should have url endpoints of backend.
* /stores folder should keep zustand state management codes.
*  Common layouts for a feature should be placed into layouts folder under the corresponded feature`s folder

Cloud Backend
* All variables names should be in camelCase.
* All function names should be in camelCase.
* All lambda handlers used by Rest-api  should be wrapped with addCorsResHeaders middleware
* Cloud infrastructre related code should be placed under the lib folder.
* All test related code should be kept in test folder.
