# Kentucky's Legends

### Webpage Link: https://dtabeyrathne.github.io/ky-legends/

## 1. Data Sources

Since I am interested in making a map of local legends, myths, and cryptids, I will need to create my own database as a GIS-ready one is not currently available. I want to map all known legends in Kentucky, but as that is a rather large workload, I have decided to map only the more popular ones that many people may know about. Here are the a selection of sources I have found that detail a list of legendary figures and cryptids that are said to have been sighted in Kentucky:

1. https://mythicalencyclopedia.com/mythical-creatures-of-kentucky/
    - Pope Lick Monster
    - The Kentucky Goblins (Kelly-Hopkinsville)
    - The Black Shuck
    - The Wampus Cat
    - The Beast of Land Between the Lakes
    - The Tailypo
    - The Herrington Lake Monster
    - Green River Mermaids
    - The Hillbilly Beast
    - Ghost Horses of Mammoth Cave
    - Black Mountain Lion
    - Tommyknockers of the Mines
    - The Witch of Cedar Grove
    - Specters of the Cumberland

2. https://folkbestiary.com/kentucky/
    - Kelly-Hopkinsville Goblins
    - Pope Lick Monster
    - Hellhound of Pike County
    - Bearilla
    - Panther of Pine Mountain

3. https://fox56news.com/news/kentucky/what-mythical-creatures-are-rumored-to-inhabit-kentucky/
    - The Herrington Lake Monster
    - The Pope Lick Monster
    - Kelly Little Green Men (Goblins)
    - Bigfoot

4. https://hangar1publishing.com/blogs/cryptids/kentucky-cryptids
    - Bigfoot
    - The Pope Lick Monster
    - The Mothman
    - Bearilla
    - Sheepsquatch
    - The Kelly Green Men (Hopkinsville Goblins)
    - The Giraffe-Possum
    - The Herrington Lake Monster
    - The Boonesborough Octopus

5. https://www.kentucky.com/news/state/kentucky/article266816586.html
    - The Pope Lick Monster
    - The Mothman
    - The Sheepsquatch
    - Bearilla
    - Little Green Men of Kelly (Goblins)
    - Beast Between the Lakes
    - Giraffe-Possums
    - Milton Lizard
    - The Herrington Lake Monster
    - The Boonesborough Octopus
    - Demon Leaper

6. https://ancestralfindings.com/american-folklore-kentucky/
    - Sleepy Hollow Road
    - Cop Ghost of Narrows Road
    - Goatman of Fisherville (Pope Lick Monster)
    - Twin Train Tunnels of Lambs Ferry Road
    - Witch Child of Pilot's Knob

7. https://www.onlyinyourstate.com/experiences/kentucky/urban-legends-ky
    - Hogan's Fountain Statue of Pan

8. https://www.ranker.com/list/kentucky-creepy-stories-legends/jacob-shelton
    - The Hanging Man of Allendale Train Tunnel

For the format of the data, I compiled all of the legends into first and Excel sheet and then transferred everything over to geojson.io, where I began building a GeoJSON for the project. All data was updated in the Excel sheet as well so I could keep track of it. To represent this data visually in the map, I went with color-coded simple markers as I did not have time to create any illustrations or take a look into AI-created SVGs. The resulting markers were color-coded according to legend type, of which my dataset had two: cryptid (green marker) and specter (blue marker).

## 2. Topic and Geographic Phenomena to Explore

For this final project, I want to map a set of popular cryptids and legends in Kentucky. Since my undergraduate years, I have always wanted to create a comprehensive map of local legends, myths, cryptids, and legendary figures for the whole world. Although that scope is impossible for the time that I have for this final project, I want to give it a start at Kentucky first then perhaps expand in the future. In terms of geography, the map will represent Kentucky, with relevant major geographical features (rivers, lakes, tree cover) also being shown. Below are my title and subtitle:

**Title:** The Legends and Myths of Kentucky <br>
**Subtitle:** What Lurks in The Bluegrass State?

Here are my responses for the other provided questions (kept prom proposal):
1. **What?** I am mapping the most popular or well-known legends, myths, and cryptids of Kentucky. This map will feature the general places where the legends and myths have been placed and cryptids have been sighted. I've always wanted to do a map like this to explore the importance of narratives between the fictional and real in individuals' conceptions and engagament with the world around them. Stories of all kinds are an important part of our lives and I want to explore the spatiality of one of those types of stories: legends, myths, and cryptids.
2. **Where?** The current proposed map will only feature Kentucky, though eventually I want to expand it to include the world.
3. **When?** There is no time period of focus for this map, as legends, myths, and cryptids tend to span a wide range of time depending on conception and alleged sightings.
4. **Who?** After some deliberation, this map will be geared towards those who already have an interest in legends, myths, and cryptids and those who want to learn more about them--as the creation and alleged sightings of these legends, myths, and cryptids span a range of ages, I am not sure if this map would benefit being aimed towards a particular age range, though I do intend for this map to be aimed towards those who are are largely past their childhoods (unless there is some interest before that age, as I had when I was a younger tween).

Realizing this map in the browser will be a bit tricky, as I want to include functionality for users to add their own legends, myths, and cryptids that they know of. Here are my responses to the provided questions (kept from proposal):

5. **Anticipated Methods of Thematic Representation:** Icons or color-coded point markers
6. **Anticipated User Interface:**
    - General "Map Info" button where the user can learn about the map and credits are displayed
    - A side panel that will be open upon the webpage loading that states the web page name and has shortcut buttons to take the user to the map, images/descriptions, and footer credits; this side panel can be closed by clicking an "x" button in the top right corner and can be brought back into view by clicking the three parallel horizontal lines at the top left (as depicted in the wireframe mockup)
    - Pan & zoom the map intuitively
    - Click on a marker to open an informative popup
    - Popups will have an image and some general information
    - User will be able to click a button to add their own marker (this interface will provide a set of pre color-coded markers for the user's utility)
    - Images of each legend, myth, and cryptid displays on the map will be shown in the description area and will be clickable
    - Clicking on an image swap the image to a short description of the legend, myth, cryptid depicted
    - I also want to add functionality where the user can add their own image and description to the page
    - Potentially a geolocation function for users who want to see what legends, myths, and cryptids are near their location (this will not function without the user explicitly clicking a "Find Me" button)

## 3. Map Objectives and User Needs (kept from proposal as the objectives remain the same)

1. This map needs to be made because it is (in its full form) intended to be a comprehensive look at the stories that color out lives, specifically the legends, myths, and cryptids that many be familiar with growing up or among their neighborhoods, towns, and cities. These are the stories that transcend time and renew fresh interest the more they are discussed and passed down. I am the one mapping this because I have always had a passion in mapping narratives and stories, and, being interested in legends, myths, and cryptids since I was little, I feel I can bring illustrative and descriptive passion into designing this map in a way that displays the legends, myths, and cryptids as legitimate stories and interesting tales (regardless of if they are fact or fiction).

2. I expect the users of this map to be those already interested in stories surrounding legends, myths, and cryptids. I also anticipate that they will be interested in adding stories that they have encountered in their lives (which is what I intend for this product). For functionality here, I draw inspiration from the SCP Project's community writing interface--I want the users who view my map to also be able to contribute meaningfully to its dataset. To this end, the base functionality the user will need to do so are these: add markers, add images, and add descriptions. The full stack of functionality that I anticipate is detailed in the above section.

## 4. Full Technology Stack

**Information Processing Tools**
1. Microsoft Excel: for the initial compilation of popular legends, myths, and cryptids in Kentucky
2. geojson.io: for the processing of the Excel data into a GeoJSON for ease of use (manual)

**Format of Data Storage**
All map data will be stored as a GeoJSON. Images will be stored in their own folder and will be referenced by the GeoJSON for the purpose of adding them to pop-ups.

**JS (and CSS) Libraries**
1. Leaflet (JS and CSS): for drawing the basemap and adding markers and popups
2. Bootleg (JS and CSS): for design and style functionality 
3. W3 (CSS): for designing full-size modals for the images in the image gallery

## 5. First Digital Version of Mockup - Log and Notes

- Created index.html wireframe and added basic stylsheets
- Made CSS into a separate stylesheet and linked it to index.html so I don't have to scroll forver (names myStyle.css)
- Copied over basic CSS stylings from previous labs--will change specific stylings later
- Created HTML section and added header, map, and footer
- Footer has all credits and links to my GitHub and UKY GIS--used Bootstrap docs to help format three-column layout and used W3 Schools docs to help format footer
- Added necessary JS scripts
- Added map in JS and configured options--basic basemap, center position, zoom, and control options set
- Added sidebar functionality with references to different parts of the page (will be configured later due to time constraints) (has a lot of issues)
- Added image grid with four test images
- Added test description and subheading text for general description and for the image grid
- Added geolocation functionality (has some issues)
- Added text overlay to test image 1 to show title and description
- Added a sampling of the legends data to the map (also added legends.geojson file to the repository)
- Added rudimentary popups for the data sampling (only featuring names and "null" placeholder for description for now)
- Added some comments to indicate areas for adding additional functionality

**Update: March 5th, 2026**
- Added Boyd's eval commits which fixed the sidebar and scrolling issue
- Modified scrolling to only scroll for the image gallery with an overall scroll for the page
- Modified the sidebar openbtn (CSS: padding) to be closer to the top and got rid of the background
- Switched dark basemap with an ESRI shaded relief basemap
- Compiled more datapoints into Excel sheet and transferred some to a geojson.io file

**For Next Time:**
- Finish compiling datapoints and their descriptions
- Add GeoJSON file to repo & connect to map
- Acquire images to fill the image gallery
- Look into Claude AI's icon generation

**Known Issues to Fix**
1. The sidebar (in the hidden, permanent vertical form) is on top of the page--I want it to be part of the page located on the left. I think I have to do a grid layout for this but haven't figured out how yet.
2. The sidebar is not displaying properly--currently, all the sidebar's content is peeking out when it should be hidden. Also, when opening, the sidebar doesn't shift the page 250px to the right as inteneded.
    - What I want to do is create a permanent vertical bar on the right side that is 50px wide and is blank except for the hamburger icon button. When clicking on the button, it should open the full sidebar (250px width) while shifting the page 250px to the right.
3. When the hamburger button is clicked, it doesn't disappear from the expanded sidebar. Did not work on fixing this today, but will get to it later, although I'm not quite sure how to fix this...
4. The page scroll seems to be broken--the scroll works only for a little bit and then doesn't scroll past the first three images despite there being another image beyond when the scroll stops.
5. The text in the footer is not perfectly centered vertically--unsure what to do to fix this...
6. The "Find Me" button works, but doesn't change text to "Locating..." when the geolocation function is running prior to approximating the user's location. Unsure how to fix this

**Known Issues to Fix as of March 5th**
1. Sidebar openbtn is displaying orange outline upon hover--get rid of this
2. Sidebar openbtn doesn't disappear when sidebar is open

**Functionalities and Other Things I Didn't Get to Adding Yet**
1. Ability for users to add their own marker
2. Ability for users to upload their own image and add a title/description overlay
3. All of actual data (still working on compilation) and their popups
4. Color coding for the full dataset (still working on categorization and if this is needed)

## 6. FInal Map & Webpage - Log and Notes

- Copied over all relevant files from Module 6 proposal folder over to a new repository (ky-legends)
- Compiled all data and images into a GeoJSON (initially, the images were not included in the GeoJSON)
- Changed the basemap to Stamen Terrain from Stadia Maps in order to show more terrain data and have a brighter overall basemap
- Added all data to the map and configured the markers so that the data would be color-coded according to type (cryptid types were displayed with green markers and specter types with blue)
- Added all images to the image gallery and updated the image overlay to display legend name and a very brief, ~2 sentence description
- Added background color to image gallery
- Reconfigured sidebar again as it broke--it works fine now after many experiments (to be honest, I'm not even sure how I fixed it)
- Configured the buttons (Map Credits and Image Info) to show all sources for data and images
- Fixed the geolocation button
- Added W3 CSS library to build modals for the image gallery
- Opened a GitHub Pages deployment to create a new page
- Deployed page had broken the basemap so I signed up with Stadia Maps to get a key for my domain--this fixed the basemap
- Configured the "About the Map" section and added some information about what the map generally shows and notes on the functionalities of the webpage
- Added backgroud color to About section
- Fixed GeoJSON for legends as it had some mistakes--also added filepath reference to each image
- Added images to pop-ups using the above (image ref in GeoJSON)
- As the About section got longer, the image gallery got exponentially shorter until it only became a sliver on the page--this also broke the page's scrolling
- Tried a fox of getting rid of the scroll for just the image gallery, but that broke the footer and made it stick to the middle of the page instead of the bottom
- After many hours of hating my life, I finally figured a fix to the above (both the image gallery shrinkage and the footer escape) by changing the min-height of the #scroll-content (very satisfying once it worked!)
- Added link to README to the "Map Credits" section
- Made final edits to font-style of the buttons
- Doubled-checked all functionality before pushing final commit (yayyyyyy!!!!!!)

**Known Issues to Fix**
1. None so far! I believe I've fixed all issues thus far, but if any come your way, please leave me a comment or a message about it so I can recitify it!

**Functionalities and Other Things I Didn't Get Add**
1. Due to time constraints (and not being to figure out a good way to integrate the code into my current project), I was not able to add the user-creation functionalities for neither the map (creating and placing markers) nor the image gallery (uploading images and providing a description)--this is definitely something I want to keep in mind for the future though!
2. Also due to time constraints, I didn't get to experiment with the AI-generated SVGs to replace the colored markers. This is a very cool idea so I will be eager to explore it in the future.

## Enjoy exploring Kentucky's unique legends using this map and webpage!
