# Definition of done 

## Functionality
1. The Street View button or icon is enabled and, when activated, correctly loads the immersive Google Street View for the university campus streets and paths that have coverage by said service.

2. Both the 2D map view and the Street View allow the user to navigate using touch gestures (on mobile devices) or cursor dragging (on desktop), as well as zoom to change the view.

3. The system uses the device's GPS (with a minimum accuracy of 5 meters) to detect and mark the user's current location on the map, represented by a pin.

4. The user can select a Point of Interest from a filtered list or by clicking/tapping directly on its icon on the map to set it as a destination.

5. The user's location (the pin) is updated on the map with a minimum frequency of every 2 seconds while the user physically moves around the campus, reflecting their movement in real-time.

6. The system clearly displays an estimated walking time in minutes, calculated based on the shortest pedestrian route and an average walking speed of 5 km/h.

7. The designated Points of Interest (minimum of 20: classrooms, libraries, cafeterias, etc.) are displayed on the map using differentiated icons and a clearly visible legend.

8. Upon selecting a Point of Interest on the map, a tooltip or modal window is displayed, showing its name, hours of operation, and a brief description or image.

9. The system automatically calculates and draws the shortest pedestrian route (in meters) from the user's current location to the selected destination, representing it with a solid  line.

## Design y user experience
1. The map interface is 100% responsive and correctly adapts to the viewports of smartphones, tablets, and desktops, maintaining full functionality and the legibility of all elements on all of them.

2. Map navigation (dragging, zooming, changing views) is intuitive for an average user without the need for prior instructions.

3. The map's user interface (buttons, color palette, typography) consistently follows the university website's style guide, visually integrating with the rest of the page's components.

## Performance
1. The base map (2D view with Points of interest) loads completely and becomes interactive in less than 3 seconds, simulating a 4G LTE internet connection (5 Mbps download).

2. The transition between the 2D map view and the Street View is completed in less than 3 second, without noticeable freezes or blank screens for the user.

3. The geolocation function obtains an initial reading of the user's position with a minimum accuracy of 10 meters within 5 seconds of permission being granted.