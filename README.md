# techdegree-project-05

[![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/organization/repository)

TeamTreehouse Front-End Developer TechDegree Project 5

## Table of contents

- [General info](#general-info)
- [UX Screen Recording](#ux-screen-recording)
- [Feature List](#feature-list)
- [Technologies Used](#technologies-used)

## General info

Project completed as part of the [Front End Web Development track](https://teamtreehouse.com/tracks/front-end-web-development) at TeamTreehouse.com.

## UX Screen Recording

![screen-recording](https://vimeo.com/580375989/5dca590bc7)

## Feature List

### Lightbox features

- [x] When gallery thumbnail image is clicked, larger image appears with overlay.
- [x] Background overlay hides the gallery and covers the entire window when displaying a larger image.
- [x] Images in lightbox include full text captions for each image.
- [x] Lightbox images can be navigated by clicking right and left arrows.
- [x] The lightbox can be closed to return to the gallery view.

### Search box features

- [x] Gallery photos update in real time as the user types into the search box, only photos that match the caption text appear in the gallery.
- [x] Case insensitivity has been added so searches will ignore letter case.
- [x] Entire caption is searchable, not just title or keywords.

### Additional features

- [x] Mobile-first responsive layout for both the gallery page and the lightbox.
- [x] Original JavaScript code to implement search box functionality instead of a plugin.
- [x] Javascsript includes HTML integrity checks to ensure search input, photos, and captions exist.
- [x] Javascsript displays "No photos found" message displayed if no matches.
- [x] Search field and photo thumbnail hover effects added to encourage interaction.
- [x] Search field includes `aria-label` to describe functionality.
- [x] Search field includes `type="search"` attribute allowing browsers to add enhancements such as a clear field icon.
- [x] Search field includes `spellcheck="false"` and `autocomplete="off"` attributes.
- [x] No HTML `<div>` tags used.
- [x] Tested in latest Chrome, Firefox, and Safari browsers.

## Technologies Used

This project includes:

- HTML
- CSS
- Responsive Layout
- Vanilla JavaScript for custom search feature
- [Fancyapps Fancybox UI](https://github.com/fancyapps/ui) Lightbox carousel
- PNG images optimized using ImageOptim and multiple passes
- Best practices for modern evergreen browsers
- Code validated by W3C to meet [HTML5](https://validator.w3.org/) and [CSS3](http://jigsaw.w3.org/css-validator/) standards
