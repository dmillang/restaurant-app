# Restaurant Reviews App
---
#### A Responsive Material Design Web App with map, a11y and offline availabililty

## Project Brief

_You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality._

## How to initiate this Web App

1. Fork and clone the starter repository. The code in this repository will serve as your baseline to begin development.

2. From inside the new directory, launch a local client server using Python from your terminal: `python -m SimpleHTTPServer 8000`

3. Visit the site in your browser at: `http://localhost:8000`

## Project Highlights (Rubric)

### Responsive Design

1. All content is responsive and displays on a range of display sizes.

2. Content makes use of available screen real estate and displays correctly at all screen sizes.

3. An image's associated title and text renders next to the image in all viewport sizes.

4. Images in the site are sized appropriate to the viewport and do not crowd or overlap other elements in the browser, regardless of viewport size.

5. On the main page, restaurants and images are displayed in all viewports. The detail page includes a map (using [Mapbox](https://www.mapbox.com/)), hours and reviews (stored in 'data/restaurants.json') in all viewports.

### Accessibility

1. All content-related images include appropriate alternate text that clearly describes the content of the image.

2. Focus is appropriately managed allowing users to noticeably tab through each of the important elements of the page. Modal or interstitial windows appropriately lock focus.

3. Elements on the page use the appropriate semantic elements. For those elements in which a semantic element is not available, appropriate ARIA roles are defined.

### Offline Availability

1. When available in the browser, the site uses a service worker to cache responses to requests for site assets. Visited pages are rendered when there is no network access.