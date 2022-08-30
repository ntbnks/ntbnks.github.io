# DND Initiative ntbnks.github.io
### Current version: 1.6.2

## Version 1.6.2:
- Refactored MobileAddAndEdit page.
- Fixed length for initiative and passive values in [MobileAddAndEdit].

## Version 1.6.1:
- Added [NotesTextField] into [FocusTraversalGroup] for desktop version.
- Updated Version tag. Added version tag for desktop version.
- Deleted irrelevant files for mobile version.
- Pressing "Enter" while on an active TField will take you to the next element in [FocusTraversalGroup].  
- Added background image for mobile.
- Fixed fInit not beign set to true after successful init.
- [MobileAddAndEdit] converted to [StatelessWidget].

## Version 1.6:
- Desktop version now uses **order for tab presses** ([FocusTraversalGroup]).
- Fixed bug with [MainPanelInitiative] widget, where controller kept grabbing incorrect values. MainPanelInitiative is now a StatelessWidget.
- Added **Notes** to [Actor] class.
- [AddAndEditPage] on mobile uses [Provider] for better performance.
- Minor UI changes.
