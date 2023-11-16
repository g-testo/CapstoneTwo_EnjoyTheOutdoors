# Capstone 2: Enjoy the outdoors

Description:
- HTML, CSS and JS project
- It involves finding national parks using dropdowns
- There are three pages, home, search by location/type

## Pages

### Home

This is the landing page for our website and it includes navigation and highlights things people can to enjoy the great outdoors.

<p align="center" width="100%">
    <img width="70%" src="screenshots/home.png"> 
</p>

## Things to do

Placeholder Text...

<p align="center" width="100%">
    <img width="70%" src="screenshots/thingsToDo.png"> 
</p>

## Travel
Placeholder Text...

<p align="center" width="100%">
    <img width="70%" src="screenshots/travel.png"> 
</p>

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