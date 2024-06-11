The following instructions should help you to familiarise yourself with the adjustments. Parameters that are not mentioned in each case can be left at their default values.  
# Directional Arrows
In order to display directional arrows, the following parameters must be selected in the
Inspector:
- The Start Rule needs to be set to „Street“
- In case of an intersection with traffic lights:
   1. Stop_Begin or Stop_End (depending on which end of the road the arrow
  should be) need to be set to „line only“
  2. Set Pfeil_Farbe to „white“
  3. Set Richtungspfeil to the direction you want the arrow to display (gerade,
  gerade-rechts, gerade-links, rechts, links)
  4. Set Center_Type to „White Stripe Centerline“ in order to create a full stop box
- In case of an intersection without traffic lights and holding lines:
  1. Stop_Begin or Stop_End (depending on which side of the road the arrow
  should be) need to be set to „none“
  2. Set Pfeil_Farbe to „white“
  3. Set Richtungspfeil to the direction you want the arrow to display
- In case of an intersection without traffic lights but with holding lines:
  1. Stop_Begin or Stop_End (depending on which side of the road the arrow
  should be) need to be set to the direction you want the arrow to display (gerade,
  gerade-rechts, gerade-links, rechts, links)
  2. Set Pfeil_Farbe to „white“
  3. Set Richtungspfeil to „none“
- In case of holding lines between a crosswalk and an intersection:
  1. Set Wartelinien_Begin_Crosswalk or Wartelinien_End_Crosswalk to „true“depending
  of the side of the road
  2. Set Crosswalk_Begin or Crosswalk_End to „continental“
- In order to display holding lines on bike lanes, the following parameters must be selected
in the Inspector:
   1. The Start Rule needs to be set to „Street“
   2. The parameter Stop_Begin_Velo or Stop_End_Velo depending on the side of the
   road needs to be set to „Wartelinien“
   3. If Stop_Begin or Stop_End for motorised traffic is set to „line only“ the created
   holding line is solid, otherwise it is triangular

# Bike Lanes
The necessary parameters to create different types of bike lanes are described here:
- The Start Rule needs to be set to „Street“
- Bike lanes on the side of the road:
  1. Right_Bike_Lane_Width and Left_Bike_Lane_Width can be set to the
   desired widths of the bike lanes
   2. Bike_Lane_Type needs to be set to „One-way“
   3. Set Bike_Lane_Color to the desired colour of the bike lane
   4. Set Bike_Paint_Line_Side to „Left“
   5. Set velosymbol to the desired symbol showing the correct directional arrows
- Pure, two-way bike paths:
   1. Either Right_Bike_Lane_Width or Left_Bike_Lane_Width needs to be set
   to the full segment width and the other one to 0
   2. Bike_Lane_Type needs to be set to „Two-way“
   3. Set Bike_Lane_Color to the desired colour of the bike lane
   4. Set velosymbol to the desired symbol showing the correct directional arrows

# Crosswalks
In order to display crosswalks, the following parameters are needed:
- Again, the Start Rule needs to be set to „Street“
- Depending on the desired position of the crosswalk (on the beginning or the end of the
street) either Crosswalk_Begin or Crosswalk_End needs to be set to „continental“
- Set _Begin_Crosswalk_To_Stop_Bar or _End_Crosswalk_To_Stop_Bar to the
desired distance of the crosswalk to a chosen stop bar
- Crosswalk_Color has to be „yellow“
- Set the Crosswalk_Width to the desired width of the crosswalk

# Street Markings
The configuration in order to display different street markings are the following:
- Again, the Start Rule needs to be set to „Street“
- Set Center_Type to the desired type: „White Stripe Centerline“ for a white dashed
centreline, „White Centerline“ for a white through centreline and a few others, whose
names are quite self-explanatory

# Tram lanes
To generate tram lanes, the following parameters are necessary:
- Again, the Start Rule needs to be set to „Street“
- Set Transit_Lane to „Light Rail Lane“
- Set Transit_Lane_Sides to „Both“
- When creating pure tram lanes without motorised traffic, Transit_Lane_Width can
be left on the default width of 3.15 m and the segment width needs to be 6.3 m
- When creating a tram lane where the road space is shared with motorised traffic or
bike lanes, Transit_Lane_Width can be left on the default width of 3.15 m but the
segment width needs to be adjusted respecting the widths of the additional lanes

# Bus lanes, 30 zones and speed limit 30
In order to generate bus lanes, 30 zones or speed limit 30, the following parameters are
essential:
- As always, the Start Rule needs to be set to „Street“
- Set Transit_Lane to „Bus Lane“, „Zone 30“ or „Tempo 30“
- Set Transit_Lane_Sides to „Both“
- When creating a transit lane where the road space is shared with bike lanes,
Transit_Lane_Width can be left on the default width of 3.15m but the segment
width needs to be adjusted respecting the width of the additional lanes

# Tram stops
The two different configurations for tram stops are described here:
- Tram stops on the sidewalk:
   1. The Start Rule needs to be set to „Sidewalk“
   2. Set Tramhaltestelle_Trottoir to the side of the road you’re on (left or right)
   3. Set Sidewalk_Bus_Stop to „Both“ and Sidewalk_Bus_Stop_Location to the
desired Location
   4. The white guiding lines can be controlled with the handles called Haltestelle_Rotation_links,
Haltestelle_Translate_X_links, Haltestelle_Translate_Y_links and Haltestelle_Translate_Z_links
for a smooth placement it is advisable to first set Haltestelle_Rotation_links,
then Haltestelle_Translate_X_links, Haltestelle_Translate_Z_links and at
the end if necessary Haltestelle_Translate_Y_links (and respectively for the
right side)
- Tram stops as an island on the road:
   1. The Start Rule needs to be set to „Street“
   2. When creating tram stops as islands with an additional lane for motorized
traffic with a width of 3.25 m on both outer sides the minimum Segment Width
is 16.1 m
   3. The Lane Width should be 3.25 m
   4. Set Center_Type to „Boulevard“
   5. Set Center_Width to 9.6 m, WalkWay_Width to 2 m and Boulevard_Inside_Width
to 5.6 m
   6. Boulevard_Configuration should be „Tram Lanes“
   7. Set Median_Bus_Stop to „Both“ and Median_Bus_Stop_Location to „Mid-
Block“
   8. Set Inselhaltestelle to „beidseitig"

# Pedestrian Protection Island
In order to generate a pedestrain protection island, the following parameters are essential:
- The Start Rule needs to be set to „Street“
- Set Fussgaengeruebergang to „true“
- Set Center_Type to „Median“
- Set the Center_Width and WalkWay_Width to 2 m
- If tram lanes are desired, set Transit_Lane to „Light Rail Lane“

# Traffic lights and signs
In order to display traffic lights and signs, the following instructions can be followed:
- As both traffic lights and signs are located on the sidewalk, the Start Rule needs to
be set to „Sidewalk“
- To display traffic lights, set Traffic_Lights to the desired streetside
- In order to display traffic signs choose from the wide selection of signs that come
with the parameter Street_Sign
- It is possible to control the position of the lights and signs with the handles
Street_Sign_Rotation, Street_Sign_Translate_X, Street_Sign_Translate_Z and
respectively for traffic lights

# Bike Racks
In order to display bike racks, the following instructions can be followed:
- The Start Rule needs to be set to „Street“
- Set Center_Type to „Median“
- Set Median_Bike_Rack_CH to the side of the Median the objects should be inserted
- It is possible to control the position of the bike racks with the handles SBike_Rack_Translate_X,
SBike_Rack_Translate_Y and SBike_Rack_Translate_Z
