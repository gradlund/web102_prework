# WEB102 Prework - *Sea Capital*

Submitted by: **Grace Radlund**

**Sea Capital** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X] The Our Games section includes a search box and button that allows the user to display games that contain the given input.
* [X] The header section includes a navigation bar that allows the user to eaily navigate to different sections.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src="walkthrough.gif" title='Video Walkthrough' width='500px' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ezgif.com  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app.

- CSS for the header class was resulting in a horizontal scrollbar. Decreased the margins, which eliminated this issue.
- Search game was not returning games if capitalization was not correct. Fixed this by making the game name and description, as well as the search text, lowercase when seeing if the text was included in the game name and/or description.
- Initialy used backers instead of pledged when checking to see if games had met there goal. This was resolved through troubleshooting - then the correct game cards were displayed.

## License

    Copyright 2023 Grace Radlund

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
