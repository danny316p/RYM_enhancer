###Features
*	Changes ratings from 0.5-5 to 1-10
*	Fixes stars alternative text in a 1-10 scale
*	Gives an average rating for each artist and release category (album, single, video, etc.)
*	Gives ratings color (1-4 red; 4-7 yellow; 7-10 green)
*	Highlights owned records at chart pages
*	Gives the number of records you own at the bottom of chart pages.

All these features are optional and you can activate or deactivate using the user script commands menu.

###Background
This repository is based on the source code and documentation for the RYM enhancer script, as retrieved from: <http://userscripts.org/scripts/show/38361> . Somewhere along the way, <http://www.rateyourmusic.com> (generally abbreviated as RYM) changed their chart code in a few minor ways that broke the original script. This repository begins with my minor changes, which restore the script's original functionality by making the hard-coded expectations match the current version of the site. Shortly after, I contacted the original author for permission to upload my repository with his code to github and slap on a free/open license - which brings us here.

###Installation
The main script can be installed in Firefox through Greasemonkey or in Chrome through Tampermonkey.

###Goals for this project
1. Continued maintenance of the script to handle future changes to RYM.
2. Development of additional client-side features for RYM.

###Suggested new features for future development
1. Highlight records you own in user-created lists
2. Give the amount of records you own from a user-created list

###Contributing
You are highly encouraged to fork this project and submit pull requests. I'll do my best to address issues and pull requests in a timely manner.

###Licensing
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.

