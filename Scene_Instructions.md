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
