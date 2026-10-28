\# Study Tracker



A lightweight, browser-based study timer and progress dashboard for a 120-day study challenge. The app combines focused study/break sessions with a visual progress tracker, motivational ticker, and goal gallery.



\## Features



\- \*\*Study and break timer\*\* with a 50-minute study session and 10-minute break session.

\- \*\*120-day progress tracker\*\* with a visual completion bar.

\- \*\*Persistent day count\*\* using browser storage so progress survives page refreshes.

\- \*\*One-click day logging\*\* through the `Log Completed Day` button.

\- \*\*Study/break mode styling\*\* that changes the dashboard colors and status indicator.

\- \*\*Motivational scrolling ticker\*\* to keep the current goals visible.

\- \*\*Vision gallery\*\* for career, travel, and personal study goals.

\- \*\*Responsive single-page layout\*\* built with plain HTML, CSS, and JavaScript.



\## Tech Stack



\- HTML5

\- CSS3

\- Vanilla JavaScript

\- Browser `localStorage`



No framework, package manager, build step, or backend is required.



\## Project Structure



```text

study-tracker/

├── index.html      # Application markup, styles, and timer logic

├── gate.jfif       # Career/GATE goal image

├── mountain.jfif   # Mountain and travel goal image

└── lake.webp       # Travel goal image

```



\## Getting Started



\### Run locally



1\. Clone the repository:



   ```bash

   git clone https://github.com/ranish234/study-tracker.git

   cd study-tracker

   ```



2\. Open `index.html` in a modern web browser.



   Alternatively, serve the directory with a local static server:



   ```bash

   python -m http.server 8000

   ```



   Then open \[http://localhost:8000](http://localhost:8000).



\### Use the tracker



1\. Start the page to begin a study session.

2\. Let the timer alternate between study and break modes.

3\. Select \*\*Log Completed Day\*\* when a study day is complete.

4\. Refreshing the page preserves the stored day count in the same browser.



\## Configuration



The main timer and challenge settings are defined near the bottom of `index.html`:



```js

const STUDY\\\_TIME = 50;

const BREAK\\\_TIME = 10;

const TOTAL\\\_TARGET\\\_DAYS = 120;

```



Change these values to customize the study duration, break duration, or target number of days.



\## Customizing the Goals



The goal cards are defined in the `.vision-gallery` section of `index.html`. Replace the image files or update the image paths and captions to match your own goals.



For portability, use repository-relative paths such as:



```html

<img src="gate.jfif" alt="Career goals" class="vision-image">

```



Avoid local machine paths such as `C:\\\\Users\\\\...`, because they will not work for other users or when deployed through GitHub Pages.



\## Deployment



This is a static website and can be deployed using any static hosting provider. GitHub Pages is a natural option:



1\. Open the repository's \*\*Settings\*\* tab.

2\. Select \*\*Pages\*\*.

3\. Configure deployment from the `main` branch and the repository root.

4\. Open the generated Pages URL after deployment completes.



Before deploying, make sure all image references in `index.html` use relative repository paths.



\## Browser Storage



The completed-day counter is stored locally in the browser. It is device- and browser-specific; it is not synchronized between browsers and there is no server-side account or backup.



To reset the stored progress, open the browser developer console and run:



```js

localStorage.clear();

```



> This clears local storage for the current site, including any other values saved by the page.



\## License



No license has been specified for this repository. Add a license file if you want to define how others may use, modify, and redistribute the project.





A lightweight, browser-based study timer and progress dashboard for a 120-day study challenge. The app combines focused study/break sessions with a visual progress tracker, motivational ticker, and goal gallery.



\## Features



\- \*\*Study and break timer\*\* with a 50-minute study session and 10-minute break session.

\- \*\*120-day progress tracker\*\* with a visual completion bar.

\- \*\*Persistent day count\*\* using browser storage so progress survives page refreshes.

\- \*\*One-click day logging\*\* through the `Log Completed Day` button.

\- \*\*Study/break mode styling\*\* that changes the dashboard colors and status indicator.

\- \*\*Motivational scrolling ticker\*\* to keep the current goals visible.

\- \*\*Vision gallery\*\* for career, travel, and personal study goals.

\- \*\*Responsive single-page layout\*\* built with plain HTML, CSS, and JavaScript.



\## Tech Stack



\- HTML5

\- CSS3

\- Vanilla JavaScript

\- Browser `localStorage`



No framework, package manager, build step, or backend is required.



\## Project Structure



```text

study-tracker/

├── index.html      # Application markup, styles, and timer logic

├── gate.jfif       # Career/GATE goal image

├── mountain.jfif   # Mountain and travel goal image

└── lake.webp       # Travel goal image

```



\## Getting Started



\### Run locally



1\. Clone the repository:



   ```bash

   git clone https://github.com/ranish234/study-tracker.git

   cd study-tracker

   ```



2\. Open `index.html` in a modern web browser.



   Alternatively, serve the directory with a local static server:



   ```bash

   python -m http.server 8000

   ```



   Then open \[http://localhost:8000](http://localhost:8000).



\### Use the tracker



1\. Start the page to begin a study session.

2\. Let the timer alternate between study and break modes.

3\. Select \*\*Log Completed Day\*\* when a study day is complete.

4\. Refreshing the page preserves the stored day count in the same browser.



\## Configuration



The main timer and challenge settings are defined near the bottom of `index.html`:



```js

const STUDY\\\_TIME = 50;

const BREAK\\\_TIME = 10;

const TOTAL\\\_TARGET\\\_DAYS = 120;

```



Change these values to customize the study duration, break duration, or target number of days.



\## Customizing the Goals



The goal cards are defined in the `.vision-gallery` section of `index.html`. Replace the image files or update the image paths and captions to match your own goals.



For portability, use repository-relative paths such as:



```html

<img src="gate.jfif" alt="Career goals" class="vision-image">

```



Avoid local machine paths such as `C:\\\\Users\\\\...`, because they will not work for other users or when deployed through GitHub Pages.



\## Deployment



This is a static website and can be deployed using any static hosting provider. GitHub Pages is a natural option:



1\. Open the repository's \*\*Settings\*\* tab.

2\. Select \*\*Pages\*\*.

3\. Configure deployment from the `main` branch and the repository root.

4\. Open the generated Pages URL after deployment completes.



Before deploying, make sure all image references in `index.html` use relative repository paths.



\## Browser Storage



The completed-day counter is stored locally in the browser. It is device- and browser-specific; it is not synchronized between browsers and there is no server-side account or backup.



To reset the stored progress, open the browser developer console and run:



```js

localStorage.clear();

```



> This clears local storage for the current site, including any other values saved by the page.



\## License



No license has been specified for this repository. Add a license file if you want to define how others may use, modify, and redistribute the project.



