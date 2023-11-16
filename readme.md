# Capstone 2: Enjoy the outdoors

Description:
- HTML, CSS and JS project
- It involves finding national parks using dropdowns
- There are three pages, home, search by location/type

## Pages

### Home

This is the landing page for our website and it includes navigation and highlights things people can to enjoy the great outdoors.

<img src="screenshots/home.png" align="center" width="300" />

## Things to do

Placeholder Text...

<img src="screenshots/thingsToDo.png" align="center" width="300" />

## Travel
Placeholder Text...

<img src="screenshots/travel.png" align="center" width="300" />

## Interesting Code Snippet

What makes this code interesting is:
- Very efficient and very maintainable
- It's also scalable


```
    const locations = [
        { name: "Rocky Mountain", type: "mountain", difficulty: "hard" },
        { name: "Yosemite", type: "park", size: "large" },
        { name: "Everest", type: "mountain", difficulty: "extreme" },
        { name: "Zion", type: "park", size: "medium" }
    ];

    const filteredMountains = filterLocations(locations, { type: "mountain" });
    console.log(filteredMountains);

    const difficultMountains = filterLocations(locations, { type: "mountain", difficulty: "hard" });
    console.log(difficultMountains);
```