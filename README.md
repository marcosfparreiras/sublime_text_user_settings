# About

This is an example of User Settings for Sublime Text (version 2 and 3). These settings will override the default ones.
These settings will allow you to:
- Ensure that all files that you save have a new line at the end;
- Translate tabs to spaces;
- Configure the default tab size to 2 (two) spaces;
- Trim every trailing white space;
- See line numbers;
- See rulers so you can follow good practices about lines length;
- Highlight the tabs related to files that were modified and not yet saved;
- Bold directories labels in the sidebar so you can see easily what is a directory and what is a file;
- Preview a file when you click on it in the sidebar.

# How to use it

In order to use this set of configuration, open your sublime text, click on the Preferences menu and then click on "Settings - User". Then, just paste the following content to it:
```
{
  // Set to true to ensure the last line of the file ends in a newline
  // character when saving
  "ensure_newline_at_eof_on_save": true,

  // Set to true to insert spaces when tab is pressed
  "translate_tabs_to_spaces": true,

  // The number of spaces a tab is considered equal to
  "tab_size": 2,

  // Set to true to removing trailing white space on save
  "trim_trailing_white_space_on_save": true,

  // Set to false to prevent line numbers being drawn in the gutter
  "line_numbers": true,

  // Columns in which to display vertical rulers
  "rulers": [ 80, 100, 120 ],

  // List any packages to ignore here. When removing entries from this list,
  // a restart may be required if the package contains plugins.
  "ignored_packages": [ "Vintage" ],

  // Makes tabs with modified files more visible
  "highlight_modified_tabs": true,

  // Show folders in the side bar in bold
  "bold_folder_labels": true,

  // Preview file contents when clicking on a file in the side bar. Double
  // clicking or editing the preview will open the file and assign it a tab.
  "preview_on_click": true
}
```
This code can be seen also in the Preferences.sublime-settings file of this project.

