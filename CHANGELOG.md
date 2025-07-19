# Change Log: Oort Cloud Reverie

**The following file is included to communicate the changes released with each update**

- **Project's Repository: https://github.com/AjayChambers/oort-cloud-reverie**
- **This project is maintained by Ajay Chambers**

<br>

**PLEASE NOTE:** For the sake of brevity, when I list changes, I will refer to the themes using their acronyms rather than their names. The acronyms are for each theme can be seen below.

1. **DBGG**: Deep Blue Galactic Glow  @(`deep-blue-galactic-glow-color-theme.json`)
2. **DIGS**: Dark Inner Galactic Space @(`dark-inner-galactic-space-color-theme.json`)

----------------------------------------------------------------

<br>

### [1.1.0] - 2025-07-04

1. Released the early beta version of the theme. Many of the color selection properties have been colored, but much more work needs to be done before a regular version will be released.

----------------------------------------------------------------

### [1.2.0] - 2025-07-17
Changes apply to both DIGS and DBGG. 

1. Set `"semanticHighlighting"` to `false`
1. A colors so they contrast with each better.
1. Adjusted the tokenColors array's TextMate selectors to better highlighting for C++
1. Added custom coloring for CMake. The CMake grammar isn't consistent, and has other issues. I did the best I could with the grammar available.

----------------------------------------------------------------

### [1.3.0] - 2025-07-18    
This update primarily focuses on changes for DBGG. There was only one change that affected DIGS.

- #### Changes to DIGS & DBGG
    1. Added TM token object to target accessor type punctuation/operators. Examples include, but are not limited to:
        ```
          "punctuation.separator.scope-resolution",
          "punctuation.separator.dot-access",
          "punctuation.separator.pointer-access",
          "storage.type.function.arrow"
        ```

- #### Changes to DBGG only:
    1. Git decoration colors. The color scheme wasn't changed, they were just made brighter or softer depending on how each color contrasted with the theme in its current state.
    2. The biggest change was the adjusting of the 'activityBar', 'sideBar', 'panel' & 'terminal', active & inactive 'tab', 'tabsBackground', and 'breadcrumbs'. Like most other changes in this update, the hue itself was not changed, rather the colors where made darker or lighter so that the editors parts flowed more gently with each other
    3. Icon color was made brighter. 
    4. Changed `ActivityBar.activeForeground` hue to be closer to a cyan than a blue.

----------------------------------------------------------------