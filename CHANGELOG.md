# Change Log: Oort Cloud Reverie

**All notable changes to the "oort-cloud-reverie" extension will be documented in this file.**

## Notes from Author
**The following notes help readers to better understand this file and project.**
- The changes below are not always made to each. For each change it will be stated what theme (or themes) the change was made to. For the sake of brevity, I will document the changes to each theme using the themes acronyms, which have been included below: 
    - **DBGG**: Deep Blue Galactic Glow  @(`deep-blue-galactic-glow-color-theme.json`)
    - **DIGS**: Dark Inner Galactic Space @(`dark-inner-galactic-space-color-theme.json`)
- The first few updates are going to have more changes than what will be practical to put into the change log. For a more verbose and detailed source that journals this projects changes & progress @see https://github.com/AjayChambers/oort-cloud-reverie   


<br>

## [1.1.0] 
Released the early beta version of the theme. Many of the color selection properties have been colored, but much more work needs to be done before a regular version will be released.

### [1.2.0] Changes apply to both DIGS and DBGG.
Custom colored specific parts of the C++ grammar. Syntax targets include:
- Set `"semanticHighlighting"` to `false`
- A colors so they contrast with each better.
- Adjusted the tokenColors array's TextMate selectors to better highlighting for C++
- Added custom coloring for CMake. CMake grammars tend to be inconsistent, and even incorrect in what is properties are labeled. IDK why CMake grammars are like that, but I did the best I could with what I had. 