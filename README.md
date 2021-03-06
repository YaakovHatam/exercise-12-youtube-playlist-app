# Youtube playlist App (exercise #12)

## General
**Fork this project to start the exercise.**

This exercise is part of exercises repository found AT [Exercises master repo](https://github.com/YaakovHatam/exercises)

If you finish the exercise you can request to add your repo here [add a finished project](https://github.com/YaakovHatam/exercises/issues/new?assignees=YaakovHatam&labels=Add+a+project+to+hall+of+fame&template=add-a-finished-project.md&title=i+want+to+add+my+proejct+exercise-12-youtube-app+to+hall+of+fame)

Something is not clear? Please open issue here: [Open clarification issue](https://github.com/YaakovHatam/exercises/issues/new?assignees=YaakovHatam&labels=help+wanted&template=exercise-clarification.md&title=%5BCLARIFICATION%5D)

## Objective of the exercise
Build a media player, which plays songs from Youtube using the youtube embed (iframe).

## The knowledge required to solve the exercise
JavaScript, HTML5 APIs, CSS.

## Mockup
![Example of the page](https://github.com/YaakovHatam/exercise-12-youtube-playlist-app/blob/master/youtube-app.png?raw=true)

## Initial files
`songs.json` - Contains a list of songs that the user can add to his playlist

`youtube.css` - basic style

`youtube.js` - JavaScript API to load the YouTube player

`youtube.html` - first HTML skeleton

## Exercise instructions
An HTML page should be built that is divided into 3 parts, one side part will contain a list of songs that can be added to the user's playlist, a second side part will contain the list of songs that the user added to his playlist, the main part (which is also between the other two side parts) will contain the media player.

### Using HTML5 apis

**Fetch API**  - Use `Fetch` to get the playlist from the `songs.json` file and then display them in the area from which you can drag songs to the playlist

[MDN Fetch_API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)

---------------------

**Drag and drop API** - The user can drag songs from one side (the list of songs from which you can choose what to add to the playlist) to the other side (the list of songs that the user has added to his playlist)

[MDN HTML_Drag_and_Drop_API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API)

---------------------

**Web storage API** - Local storage, When the user moves an item to his playlist, the user's playlist in Local storage needs to be updated.
When the page is reloaded, the user's playlist must be loaded from the Local storage into the appropriate place.

[MDN Web_Storage_API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)

---------------------

**History API** - When a user clicks on a song from his playlist, the hash of the address bar should be put / replaced so that it contains the id of the song being clicked.

[MDN History_API](https://developer.mozilla.org/en-US/docs/Web/API/History_API)

---------------------

**Location API** - When a user clicks on a song from his playlist, the hash of the address bar should be put / replaced so that it contains the id of the song being clicked.

[MDN Location](https://developer.mozilla.org/en-US/docs/Web/API/Location)

---------------------

**Page visibility API** - When a user navigates outside the tab the player must be paused.

[MDN Page_Visibility_API](https://developer.mozilla.org/en-US/docs/Web/API/Page_Visibility_API)

---------------------

**HTMLElement API** - dataset, 

[MDN HTMLElement/dataset](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/dataset)

---------------------
