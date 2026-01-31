# Changelog



## [0.0.2] - 2026-01-31

🚀 Features
- **Database Management**: Added support for choosing which databases to display in the tree view.
- **Editor Experience**: Added configuration options for SQL editor tab closing behavior.

### ⚡ Optimizations
- **Performance**: Implemented parallel execution for SQL files to improve processing speed.

### 🐞 Bug Fixes
- Fixed the bug where tree nodes cannot be searched
- UI/UX:
  - Fixed real-time update issues where the right panel failed to refresh.
  - Fixed missing log displays during data export and SQL file execution.
  - Corrected display of table names during the export process.
- Database Support
  : Fixed a MySQL parsing error occurring when script strings contained backslashes (\\\).