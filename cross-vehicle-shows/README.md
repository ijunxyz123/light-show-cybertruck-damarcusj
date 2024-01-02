# Programming a show with cross-vehicle animations
With the tesla_xlights_cross_vehicle_folder, you can program synchronized light shows with cross-vehicle animations for up to 5 vehicles at once.

## Setup xLights
This guide assumes that you have already setup the global xLights settings and read the instructions for creating normal light shows.

1. Download and unzip [tesla_xlights_cross_vehicle_folder.zip](xlights/tesla_xlights_show_folder.zip?raw=true), which is the Tesla xLights bare project directory.
2. Change your xLights show directory to tesla_xlights_cross_vehicle_folder
    - You can select 'Change Temporarily' if you want xLights to continue opening the normal show directory when starting the program.

    <img src="/images/change_directory.png?raw=true" width="450" />

3. Create a new sequence with the usual settings. Select the 'All Cars' view.

    <img src="/images/view_all_cars.png?raw=true" width="450" />

## Layout
- In the preview, you will find five Cybertruck's in a row with five Model S' stacked above them. This accomodates all lights and closures for all vehicle types. It's recommended to resize or move the preview to fit all cars.

    <img src="/images/preview_moved.png?raw=true" width="1000" />

- Each Cybertruck / Model S combination has it's own number. When viewed from the front, the cars are numbered 1 to 5 from Left to Right.
- This show folder heavily relies on Groups to organize the almost 1000 light channels.
    - Make yourself familiar with the Groups before you start programming effects.
    - All Groups can be expanded by double clicking them in the timeline. Most can be expanded multiple times.
    - You can place effects directly on the groups.

## Programming tips
- Get started by only using a small set of groups and don't program the individual lights. Group recommendations for getting started:
    - _Front 1_ to _Front 5_, and _Rear 1_ to _Rear 5_ (located in _All Front Lights_ and _All Rear Lights_)
    - Groups _All Channel 4-6, All Signatures, All Inner Main Beam, All Outer Main Beam, All Front Turns_.
    - For Cybertruck: _Front Light Bar 1-5_, and _Rear Light Bar 1-5_, located in _All Front Lightbars_ and _All Rear Lightbars_
- You can use xLights' integrated effects, e.g. the Curtain effect, on the following channels:
    - Front Light Bar 1-5
    - Rear Light Bar 1-5
    - Front 1-5
    - Rear 1-5
    - Do not use integrated effects on any other channel, including _All Front Lightbars_, _All Front Lights_, etc. They will not play as previewed in xLights.
- To create cross-vehicle 'sweeping' effects on the Cybertruck light bar, or the normal lights, align the 'Curtain' effect to play successively on each car. Place 'On' effects as necessary.

    <img src="/images/sweep_example.gif?raw=true" width="1000" />

