---
aliases:
  - msl
  - mslink
  - mslink.mobi
  - Multi Screen Link
---
# mslink.mobi
aka Multi Screen Link (see [[design]])

App for controlling multiple monitors.
This can be used to control what is displayed on old phones screens (with app or by access browser page).

- A web page will show in frame other page that is set in admin panel.
- User can fast and easy change url that is displayed in frame of each phone/screen

### URL structure

- `/u/UUID` for user login and dashboard (uses [[app msl|msl app]]), auth by directus mechanism.
- `/u/UUID/s/UUID?token=absde` for screen clients (uses [[app msl_screen|msl_screen app]]), auth by token.

See [[Structure.canvas|Structure]] for general view of the services structure.