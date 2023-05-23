Taskwarrior-TUI Customization
This document describes the changes made to the Taskwarrior-TUI application to create a cleaner, less cluttered interface. The primary motivation behind these changes was to create a custom dashboard using tmux and tmuxinator, where the original user interface of Taskwarrior-TUI was found to be too cluttered.
Changes Made

    Removed the Tab Bar: The original Taskwarrior-TUI application had a tab bar at the top of the screen that allowed switching between different views (Tasks, Projects, Calendar). This was removed to simplify the interface and focus on the task list.

    Removed the Filter Bar: The filter bar at the bottom of the screen was also removed. This bar was used to filter the tasks shown in the task list. Removing this bar further simplifies the interface.

    Added Report Name Display: Instead of the tab bar, the name of the current report is now displayed at the top of the screen. This provides useful context without adding unnecessary clutter.

How to Use the Customized Version

The usage of the customized version remains largely the same as the original. However, since the tab bar has been removed, switching between views (Tasks, Projects, Calendar) must be done through other means (e.g., command line arguments).

For example, to start the application with a specific report, you can use the -r command line argument followed by the report name:

taskwarrior-tui -r report

In this command, report should be replaced with the name of the report you want to view.
