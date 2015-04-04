# Android Lollipop Views

This is an application that displays Android lollipop views.

------------------

These material widgets and animations were introduced in Android 5.0 (API level 21):

- RecyclerView (the new ListView)
- CardView (custom outline and shadow)
- Ripple animation (touch feedback)
- Palette (Incorporate dynamic color)
- Shared Element Activity Transition
- Floating Action Button

The app composes two screens. The first screen displays a list of contacts, in which, each item is described by the contact's avatar and name. Once a contact is selected from the list, a second screen appears with additional details about the contact, including his contact no. and a floating action button to place a phone call to this contact.

#### Contact List
<img src="http://i.imgur.com/VSbsd4Gl.png" height="400" width="300">


#### Contact Details

<img src="http://i.imgur.com/NpKJJgdl.png" height="400" width="300">


### Overview

The app does the following:

1. It uses a `RecyclerView` to display a list of contacts.
2. `CardView` is used to display each contact in the list.

#### Suggested extensions:

1. Add ripple effect to `CardView` to provide touch feedback.
2. Use `Palette` to add dynamic color to contact item's background. Use the same color as the accent color for the views in details screen.
3. Add shared element activity transition to provide a seamless experience by emphasizing continuity between activity transitions.
4. Add a floating action button, clicking on which should enable you to directly place a call to your contact.

### Libraries

- [Picasso](http://square.github.io/picasso/) - For image loading
