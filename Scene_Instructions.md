# Directional Arrows
In order to display directional arrows, the following parameters must be selected in the
Inspector:
- The Start Rule needs to be set to „Street“
- In case of an intersection with traffic lights:
   – Stop_Begin or Stop_End (depending on which end of the road the arrow
  should be) need to be set to „line only“
  – Set Pfeil_Farbe to „white“
  – Set Richtungspfeil to the direction you want the arrow to display (gerade,
  gerade-rechts, gerade-links, rechts, links)
  – Set Center_Type to „White Stripe Centerline“ in order to create a full stop box
- In case of an intersection without traffic lights and holding lines:
  – Stop_Begin or Stop_End (depending on which side of the road the arrow
  should be) need to be set to „none“
  – Set Pfeil_Farbe to „white“
  – Set Richtungspfeil to the direction you want the arrow to display
- In case of an intersection without traffic lights but with holding lines:
  – Stop_Begin or Stop_End (depending on which side of the road the arrow
  should be) need to be set to the direction you want the arrow to display (gerade,
  gerade-rechts, gerade-links, rechts, links)
  – Set Pfeil_Farbe to „white“
  – Set Richtungspfeil to „none“
- In case of holding lines between a crosswalk and an intersection:
  – Set Wartelinien_Begin_Crosswalk or Wartelinien_End_Crosswalk to „true“depending
  of the side of the road
  – Set Crosswalk_Begin or Crosswalk_End to „continental“
