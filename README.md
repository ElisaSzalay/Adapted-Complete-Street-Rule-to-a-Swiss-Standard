# Adapted-Complete-Street-Rule-to-a-Swiss-Style
This repository shows the code developed within the Bachelor Thesis named "Procedural modelling of urban mobility transitions: Case Study of an E-Bike City in Zurich" carried out by Elisa Szalay at ETH Zurich. The second part of the thesis carried out by Fabien Forestier showing the application of the code can be viewed in the Repository named "E-Bike_City_Case_Study_Zurich".

# General Introduction to the thesis 
Urban mobility plays a crucial role in the sustainable transformation of cities and requires profound organisational changes in today’s urban transport systems. The E-Bike City project at ETH Zurich addresses precisely this issue and proposes modifications that will contribute to the decarbonisation of urban mobility. As transparent and comprehensible communication is essential for the political and social acceptance of such far-reaching changes, well-founded modelling and visualisation are indispensable. This bachelor thesis explores the innovative approach of using procedural modelling for this purpose. The program ArcGIS CityEngine was used to implement this modelling. The procedural modelling in CityEngine is achieved using Computer Generated Architecture, short CGA. David Wasserman developed a set of rules called “Complete Street Rule” which are able to generate street scenes when incorporating in CityEngine. However, these rules are only able to generate an American street scene and cannot adequately represent Swiss situations. As this thesis bases on a case study in Zurich, Switzerland, it was necessary to adapt and supplement these rules in order to generate a realistic street scene.

# Explanation of the Complete Street Rule
The Complete Street Rule in CityEngine is designed to swiftly generate complex, multimodal streets based on transportation planning guidelines like NACTO, AASHTO, and MUTCD standards. Its purpose is to create diverse 3D street configurations to aid urban multimodal planning and facilitate before-and-after comparisons of street treatments. Besides being a visualization tool, it offers dynamic performance metrics and reports, reacting to street configuration changes. These metrics establish a link between design and visualization, facilitating the exploration of various design scenarios. It's particularly adept at representing transportation planning treatments for complete streets and common highway configurations. Integrated with ArcGIS CityEngine, it can export 3D street models to various formats, including those compatible with game engines like Unity & Unreal, enhancing public outreach efforts. 

For further information of the Complete Street Rule, see https://github.com/d-wasserman/Complete_Street_Rule

# Adaption to a Swiss Standard
In order to adapt the Complete Street Rule correctly to a Swiss Standard, various guidelines of the VSS and VBZ were consulted. As the thesis is about creating an E-Bike City that prioritises public transport and bikes over motorised traffic, the adaptation largely involved the creation of tram and bike infrastructure. Another large part involved drawing and adapting road markings. Further information on the exact adjustments can be found in the report accompanying the thesis.

# Instructions
Instructions on how to integrate the rules into an existing project or how to create a new project from scratch can be found here. 

# Citation of the thesis
Forestier, F. and E. Szalay (2024), Procedural modelling of urban mobility transitions: Case study of an E-Bike City in Zurich, Bachelor Thesis, IVT, ETH Zürich, Zurich

