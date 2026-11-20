#  The CleanNeighbourhood
It is a simple webpage that enables us to keep our environment clean and eradicate pollution.

## Social problem
Littering, illegal dumping and uncollected waste can affect public spaces and the environment. This project gives residents a simple way to record a waste concern, add an area, and view reports on a community board.

## Pages
- Home page: introduces the problem and the project.
- Report an issue: form for recording a local waste concern.
- Community board: shows reports saved in the current browser.
- About page: explains the project and its technology.

## Technologies
- HTML: website structure and forms.
- CSS: olive green, gold and dark blue styling, including responsive layout.
- JavaScript: page rendering, hash routing, form handling, demo accounts and API requests.
- Open-Meteo Geocoding API: looks up a place name and returns coordinates.
- localStorage: stores demo accounts and reports in the browser.

## Run in Visual Studio Code
1. Extract the ZIP file.
2. Open the `CleanNeighbourhood` folder in VS Code.
3. Open `index.html` with the Live Server extension.
4. Create a demo account.
5. Open **Report an issue**, enter an area such as Nakuru, and press **Find location**.
6. Submit the report and view it on the **Community board**.

An internet connection is needed for location lookup and Google Fonts.

## Important limitations
This is a front-end learning prototype. Data is stored only in the browser where the site is opened. The community board is not shared between devices and reports are not sent to county authorities. Browser-only passwords are not secure. A real public service needs a backend, secure authentication, a database, moderation and an official process for receiving and acting on reports. Do not use this demo for emergencies.
