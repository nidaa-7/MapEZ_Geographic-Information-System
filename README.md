# MapEZ_Geographic-Information-System

## MapEZ's Target Audience and Purpose: 
- ### Who: MapEZ’s target audience are people who require additional accessibility features on maps in order to help them plan for travel.
- ### Focus: English-speaking travellers looking to travel to new places whether it’s locally or internationally.
![Screenshot 2024-02-23 155949](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/495bdd43-1e1a-49aa-9533-1d7705628635)

## Graphical Features:
- ### Multulingualism:
  - #### A major goal of our team is to make MapEZ compatible with multiple languages; allow software to be used by travellers outside of Canada.
  - #### Travellers can match text with local street signs, or show the map to a local.
![Screenshot 2024-02-23 160515](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/b8bf9864-11a1-4273-a2ee-9ab703a9e054)

- ### Night Mode:
  ![Screenshot 2024-02-23 160816](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/3280085a-17b8-4369-8f0c-023df30a6490)

- ### Points of Interest:
  - #### We’ve grouped the points of interest in a few categories, to each a nice, colorful icon.
    ![Screenshot 2024-02-23 161037](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/4383a262-14bf-4e33-8168-89467dbc2d77)
    ![Screenshot 2024-02-23 161117](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/ac284299-2d9a-44e6-a458-cd67eb014f38)
  - #### Clicking on an icon enlarges it, and displays its category and name.
    ![video1133915169 mp42024-02-2316-32-00-ezgif com-video-to-gif-converter](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/35e18124-8c57-4f2c-9a71-06c6c4d952dc)
  - #### Users can select a category from the drop down menu. All the points of interest that belong to that category will show up on the map.
    ![video1133915169 mp42024-02-2316-23-40-ezgif com-video-to-gif-converter](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/ac9c57a4-d25e-4918-ad16-d5038acf26e7)

## Path Finding:
- ### Clicking on two intersection will display the shortest legal path between them.
  ![video1133915169 mp42024-02-2316-39-17-ezgif com-video-to-gif-converter](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/cfad4092-1e09-4ebc-8413-6b7ecef16777)
- ### Searching for intersections manually will also display the shortest legal path between them.
  ![video1133915169 mp42024-02-2316-44-30-ezgif com-video-to-gif-converter](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/644075b5-2a8d-4b4f-a4c8-98d45732be17)

## Algorithms:
- ### Breadth First Search vs Dijkstra:
  - #### Breadth First Search:
    - Fast: returns a path between two intersections quickly.
    - Inefficient: doesn't return the best legal path between two intersections.
  - #### Dijkstra's Algorithm:
    - Efficient: finds the best legal path between two intersections.
      
 ![Screenshot 2024-02-23 165417](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/0e361882-7b04-4d00-82f7-aac055ef7d11)

- ### Dijkstra vs A*:
  - #### Dijkstra's Algorithm:
    - Slow: not as responsive as we woulf like it to be.
  - #### A* Algorithm:
    - Fast: responsive, averaging 19.27ms for the more complex paths.
      
![Screenshot 2024-02-23 165658](https://github.com/nidaa-7/MapEZ_Geographic-Information-System/assets/136858218/19b35a1f-d657-4e53-a4d6-e0c459f9dd84)


