# Blue CoLab Jeopardy

Blue CoLab's version of \@mvbattista's Jeopardy. See the original repo [here](https://github.com/mvbattista/jeopardy). Please see the linked repo for a full list of contributors. 

## Authors
- Keathson @KeathsonLam

## Tech Stack
This project is powered by [bootstrap](https://getbootstrap.com/) and [jquery](https://jquery.com/).

To update them download latest versions of their website and replace version in repo. Make sure to update the name of directory in index.html.

## Directory structure
- index.html - Root HTML file, contains the Jeopardy board, models, etc.
- blue_CoLab_board.json - Contains the Jeopardy answers and questions
- assets/ - Contains Jeopardy specific assets
  - css/jeopardy.css - Jeopardy specific css
  - images - all images used by Jeopardy
  - js/jeopardy.js - Jeopardy specific JS
  - sounds - all sound used by Jeopardy
- bootstrap-* - Static copy of latest bootstrap assets
- jquery-* - Static copy of latest jquery assets



## Deployment
- Just merge or push to the main branch, GitHub will take care of the rest

## Suggested Extensions
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)


## Change Log

### [4.0.0] - 2026-03-13
#### Added
- Upgraded frontend libraries:
  - Bootstrap to 5.3.8
  - jQuery to 4.0.0
- Complete rework of directory structure

#### Changed
- Applied post-upgrade compatibility patches and small fixes.

### [3.1.0] - 2026-02-02
#### Added
- Deployment instructions in the README.

### [3.0.0] - 2025-04-25
#### Changed
- Repository maintenance and documentation cleanup:
  - Fixed repository link
  - Updated README content and formatting
  - Added cSpell configuration
  - Corrected grammar and factual issues

#### Content
- Jeopardy question set cleanup and updates.

### [2.2.0] - 2024-05-10
#### Changed
- Board content refresh and question wording updates.
- Typography and layout tuning for board/category readability.

### [2.1.0] - 2024-05-09
#### Fixed
- Removed scroll bar artifacts from the game layout.
- Fixed black border visual issue.

### [2.0.0] - 2024-01-26
#### Added
- Double Jeopardy mode.

### [1.1.0] - 2024-02-27
#### Changed
- Board now loads by default.
- Repository cleanup (removed leftover folder/submodule artifacts).

### [1.0.0] - 2024-01-06
#### Added
- Initial project structure and first playable Jeopardy board.

