# Changelog
All notable changes to this project will be documented in this file.

## Sprint 3
### Added
- Permissions groups for Django.
  - Groups: TA, Instructor, Administrator, Supervisor

### Changed
- 

### Removed
-

## Sprint 2
### Added
- Command line web ui
- Created Django models for Course, Section and User


### Changed
- Converted command parser(Sprint 1) into views.py for Django
- Storage Manager saves to Django database instead of Json
- Classes modified to use Django database
  - CourseManager
  - StorageManager
  - SectionManager
  - UserManager

### Removed
- Json storage functionality
