## Burnett PhD dissertation published May 2002

**Project description:** In 1998 I met Finish researcher Petri Pellikka at a Remote Sensing conference in Copenhagen. 18 months later, I started a Academy of Finland researcher position at the University of Turku. And approximately 30 months after that I defended my PhD dissertation.

This webpage is a copy of the text in the print version of my dissertation Summary.

I have marked in red any text which has been added added of edited to the published original.

<br><br><br>

<p style="text-align: center;">TURUN YLIOPISTON JULKAISUJA<br>
ANNALES UNIVERSITIS TURKUENSIS
<hr>

<p style="text-align: center;">SARJA – SER. A11 OSA – TOM. 151<br>
BIOLOGICA – GEOGRAPHICA - GEOLOGICA</p>

<br><br><br>

<p style="text-align: center;">VISUALISATION AND ANALYSIS OF LANDSCAPE
IN INFORMATION SPACE</p>
<br><br>

<p style="text-align: center;">by
Charles Burnett</p>

<p style="text-align: center;">ACADEMIC DISSERTATION</p>

<p style="text-align: center;">To be presented,  with permission of the Faculty of Matematics and Natural Sciences<br> of the University of Turku, for public criticism in the Tauno Nurmela Auditoirum<br> on April 20th, 2002, at 12 o'clock noon.</p>

<p style="text-align: center;">TURUN YLIOPISTO
<p style="text-align: center;">Turku 2002

<hr>
<br>
Department of Geography<br>
University of Turku<br>
FIN-20014 Turku<br
Finland<br>
Email: charles.burnett@utu.fi<br>
eMail: gi_science@hotmail.com<br>
Austria eMail: charles.burnett@sbg.ac.at<br>
Canada eMail: cburnett@uvic.ca
<br><br>

Supervisors:<br><br>

Professor Risto Kalliola<br>
University of Turku<br>
FIN-20014 Turku<br>
Finland<br><br>

Professor Petri Pellikka<br>
University of Helsinki<br>
FIN-00014 Helsinki<br>
Finland<br><br>

Reviewers:

Professor Wolter Arnberg<br>
Stockholm University<br>
Department of Physical Geography and Quaternary Geology<br>
S-106 91 Stockholm<br>
Sweden<br><br>

Dr. Olli Jaakkola<br>
Finnish Geodetic Institute<br>
Geodeetinrinne 2, P.O.Box 15<br>
FIN-02431 Masala<br>
Finland <br><br>

<br><br>
ISBN 951-29-2083-2<br>
ISSN 0082-6979<br>
Painosalama Oy Turku,Finland 2002
 <hr>
<br>

This thesis is a compilation of the following articles, which are referred to by their Roman numerals in the Summary text:

<table>
  <tr>
    <td>I</td>
    <td>Burnett, C. & R. Kalliola (2000). Maps and the information age. Fennia 178:1, pp. 81-96.</td>
  </tr>
  <tr>
    <td>II</td>
    <td>Vuorela, N., Burnett, C. & R. Kalliola (2002). Cartographic traditions and the future of digital maps: a Finnish perspective. Fennia 180: vol.  I (Special issue on the Geography of Finland, eds. Pauliina Raento & John Westerholm, with CD, pages pending)</td>
  </tr>
  <tr>
    <td>III</td>
    <td>Burnett, C., Leckie, D., Jay, C., Busler, J. & J. Aitken (1999). The effect of severe topography on image resolution: implications for flight planning, post-processing and applications, in Proceedings of the 4th International Airborne remote Sensing Conference / 21st Canadian Symposium on Remote Sensing, June 21-25, Ottawa, vol. II, pp. 793-800.</td>
  </tr>
    <tr>
    <td>IV</td>
    <td>Kalliola, R., Burnett, C. & I. Suojanen (2001). Change in near-natural boreal forest landscapes: Viena Karelia in the central border region of Finland and Russia. The Finnish Environment 485, Finnish Environment Institute (pages pending).</td>
  </tr>
    <tr>
    <td>V</td>
    <td>Burnett, C.,  Fall, A., Tomppo, E. & R. Kalliola (2002). Boreal forest fragmentation monitoring and modelling (submitted to Conservation Ecology).</td>
  </tr>
    <tr>
    <td>VI</td>
    <td>Burnett, C. & T. Blaschke (2002). Juxtaposing hierarchical patch dynamics and multiscale segmentation for landscape monitoring (submitted to Ecological Modelling).</td>
  </tr>
</table>

<br>
Copyright of the published articles:<br>
© Geographical Society of Finland<br>
© Finnish Environment Institute<br>
© ERIM International Inc.
<br><br>
The dissertation contains a large number of colour images. However, it was necessary to print the dissertation in greyscale.
<br><br>
You can access the colour images by visiting the web address below:
<br><br>
http://www.utu.fi/ml/maantiede/maisema/Publications/Burnett/Burnett_phd.html
<br><br>
Correction:
<br>
The colour images have been embedded in this web version.
<br><br>

_____________________________________________________________________
<br>

# Contents

**1. INTRODUCTION_____________________________________________________________________ 1**<br><br>
2. A THEORETICAL AND METHODOLOGICAL BACKGROUND____________________________ 4<br>
2.1. SOCIETY AND GEOGRAPHIC INFORMATION _____________________________________4<br>
2.2. BIOGEOGRAPHY AND LANDSCAPE ECOLOGY ____________________________________ 7<br>
2.3. COMPLEXITY AND SCALE IN ECOSYSTEMS________________________________________ 8<br>
2.4. EARTH OBSERVATION DATA ANALYSIS: PIXELS PROBLEMS? _____________________ 10<br>
2.5. BEYOND CLASSIC PIXEL-BASED EARTH OBSERVATION __________________________ 10<br>
&nbsp;&nbsp;&nbsp;2.5.1. L-resolution advances: better algorithms, more ancillary data _________________ 12<br>
&nbsp;&nbsp;&nbsp;2.5.2. H-resolution advances: beyond the pixel as a surrogate________________________ 12<br>
2.6. MODELLING ______________________________________________________________________ 14<br><br>
3. METHODS____________________________________________________________________________ 14<br>
3.1. A CRITICAL ASSESSMENT OF GI ARTIFACTS AND SOCIETY ______________________ 14<br>
3.2. ASSESSING REMOTELY-SENSED DATA QUALITY_______________________________ 15<br>
3.3. L-RESOLUTION CASE STUDY AND METHOD __________________________________ 15<br>
&nbsp;&nbsp;&nbsp;3.3.1. Land-use monitoring _______________________________________________ 15<br>
&nbsp;&nbsp;&nbsp;3.3.2. k-nn forest parameter estimation______________________________________16<br>
&nbsp;&nbsp;&nbsp;3.3.3. Forest fragmentation modelling______________________________________ 16<br>
3.4. H-RESOLUTION CASE STUDY AND METHOD __________________________________ 16<br>
&nbsp;&nbsp;&nbsp;3.4.1. Data Processing: crown delineation, patch segmentation __________________ 17<br>
&nbsp;&nbsp;&nbsp;3.4.4. Creating functional unit maps: image object modelling ____________________ 17<br><br>
4. MAIN RESULTS AND DISCUSSION_________________________________________18<br>
4.1. ARTIFACTS CHANGE AS PART OF BROADER SOCIETAL TRENDS___________________18<br>
4.2. SPATIAL DATA QUALITY IS A CRITICAL ISSUE FOR GI ARTIFACTS _________________ 20<br>
4.3. DISPARITIES BETWEEN LANDSCAPE ECOLOGY AND GI ARTIFACTS_______________ 21<br>
4.4. OPTIMAL METHODOLOGY VARIES WITH STUDY QUESTION_______________________ 23<br>
&nbsp;&nbsp;&nbsp;4.4.1. L-resolution: extending functionality beyond the pixel_____________________ 23<br>
&nbsp;&nbsp;&nbsp;4.4.2. H-resolution: mapping functional patches with hierarchical patch dynamics___ 24<br><br>
5. CONCLUSIONS ___________________________________________________________25<br><br>
REFERENCES______________________________________________________________ 26

<br><br><br><br>
<p style="text-align: center;"><em>Nature is a temple in which living pillars<br>
Sometimes emit confused words;<br>
Man crosses it through forests of symbols<br>
That observe him with familiar glances.</em><br>
<br>excerpt from “Correspondences” by Charles Baudelaire (1821-1867)</p>
<br><br>
# 1. Introduction

This dissertation is an exploration of history and future of geographic information (GI)
representations. Raper (2000) defines representation as “the projection of the entities,
relationships and processes of the conceptualized world onto symbolic ‘facsimile’ objects with their associations and transformations (p 4).” The sonnet above can be interpreted as a poetic sketch of humankind’s search for ways to represent the world: Nature is impossibly complex, and humans are not equipped with the sensory or mental apparatus to absorb anything but a distorted and very filtered subset. We endeavour to overcome this deficiency by cleverly abstracting Nature’s multitudinosity by way of symbols. Through symbolic representation, humans attempt to make Nature familiar and thus organize an unmanageable flow of information. Through ingenuity new symbol systems arrise to describe spatialized phenomenon and process. These developments are at the core of Geographic Information Science (GISc). Two tenents of the representation process underpin this thesis: throughout human history our ability to project reality into symbolic form has continually evolved; and, as abstractions or filters of a high fidelity reality, the resulting representations are imperfect.

Representation systems evolve, drawing power from the sociotechnical synergy of human need and technological agency (Graham 1998); living artifacts that change over time. As artifacts, they are both effected by societal progress (or digress) and affect society. Geo-representations, projections referenced to the earth, are one one set of communication artifacts. Raper (2000, p 4) divides geo-representations into simple two-dimensional projections and multi-dimensional geo-representations abstracting three- and/or four-dimensions. Geo-representations encompase a panoply of forms, from 8000 year old painted wall maps, to experimental real-time 3D virtual worlds [I].

Geo-representations are imperfect reflections of reality. Nonetheless, they are powerful
systems that allow civilians and experts to visualize and analyze human and natural patterns and processes. In this thesis, these human and natural patterns and processes are encapsulated in the term landscape:

...landscape denotes the external world mediated through subjective human
experience in a way that neither region nor area immediately suggest.
Landscape is not mearly the world we see, it is a construction, a composition
of that world. (Cosgrove 1984, p 13).

In the process of projecting landscape information into geo-representations, humans aggregate sets or layers of spatial information. For these high dimension collections I propose the term “information space” because it suggests a stage of conceptualization and assembly preceding any distillation of a visualisation. From an aggregate ***landscape information space***, layers are combined and contrasted, new layers created and sub-sets distilled to create visualisations.

The impetus for this dissertation is the assertion that the demands placed on mapping artifacts are increasing, and that this is driving the development of systems that increase both the utility of landscape information spaces, and improve on the traditional cartographer>map>user communication model described by Robinson (1952). The cumulative impacts of human use on the environment is such that the maintainability of some ecosystems is now in question. Species and landscape diversity is in flux, and very few areas on the globe are not heavily impacted by human resource use, either locally or as an effect of adjacency. Mean global temperature and sea level is projected to rise under all synopses investigated by the International Panel on Climate Change (IPCC 2001).

These trends may or may not be cause for alarm, depending upon a host of unknowns: critical thresholds in nature; the resilience of ecosystems; and on the resourcefulness of human ingenuity. Regardless, humans are impacting the environment and sustainability questions call for more information to be gathered on antropocentric, natural and interdigitated systems. Lavers and Haines-Young (1993) suggest that through the wider use of spatial information systems, we may gain deeper insight into the spatial structure and dynamics of systems. Our society needs more and increasingly accurate information on spatially distributed phenomena. We need better tools for scientific analysis and visualisation and better artifacts for geographic information (GI) communication: we need better geo-representations.

GISc is a rapidly evolving collage of disciplines, methodologies, practices and technologies (Raper 2001, p.4), including geography, cartography, mathematics, computer science, and more recently, cognitive scientists, psychologists, anthropologists and archaeologists (Goodchild et al. 1999). The six constituent articles found in this dissertation may be positioned most closely within the over-lapping fields of geography, computer science and ecology (Figure 1). This thesis contributes to our understanding of the challenges inherent to spatial information tool development and the application of new theoretical and methodological tools to landscape analysis.

In this dissertation, I pursue the following goals: 1) to provide a broad examination of georepresentation (mapping) artifacts and society; and then by focusing on Landscape Ecological investigations, 2) to examine mapping and modelling issues at regional scales; and 3) to examine data combination and mapping methodology at a local analysis scale. The structure of the thesis flows from the universal to the specific, and from the theoretical to the applied. The following themes are explored: [I] the binary evolution of technological advances and societal demand for GI, [II] the tradition of GI tool development in Finland, [III] scale-related data quality issues with remotely sensed data, (IV & V) the application of traditional and new spatial tools for monitoring and modelling of forested landscapes, and [VI] a methodological basis for landscape analysis based on ecosystem theory.

Paper [I] presents an exploration of the evolution of geographic information tools, focusing on the effects of digital data processing. The history of cartography is described as an evolutionary narrative wherein societal development is reflected in mapping artifacts. Geographic information, ‘maps’ are products of the intertwined developments in societal need and technological agency. In this paper, it is argued that the traditional passive model of maps is being replaced by a dynamic one. The potential of these new tools to assist in the sustainable management of resources, for instance, has not been fully realised and a range of challenges for geographers is listed.

In paper [II] the history of Finnish geographic information tools, from maps to digital databases, is reviewed. The study shows that the building of geographic databases for landscape analysis, as pioneered by J. G. Granö (1929, 1997), is a long tradition. The need to understand landscape pattern and process relationships is thus not a new societal demand, although the sophistication of the tools has increased and the range of scientific and management applications has widened.

Paper [III] explores data quality issues concerning the use of gridded sample data in landscape analysis. The study demonstrates the challenges in using remotely sensed data, since the scale of the measurement units (picture units, pixels) does not necessarily correspond with the pattern (and thus process) that is of interest in the landscape. This ‘scale’ problem is shown to be especially acute over areas of marked topographic variation. The paper concludes with an assessment of the impacts this will have on analysis algorithms and suggests some remedies.

Paper [IV] introduces a regional biogeography problem which requires GI analysis to encompass its complexity. In it a qualitative and quantitative assessment of the differences between the forested landscapes of a northern border region between Finland and Russian Karelia is examined. Space-borne Earth observation (EO) data and field documentation are used to give a landscape level description of the forests in this unique border belt. This in-depth survey concludes with a suggestion that, ecologically, Karelian forests will evolve in three distinct directions, based on their management history. The paper also provides useful politcal, historical and economic background information for the GI methodology paper which follows.

Figure 1. A schematic locating the six constituent articles of this dissertation in
relation to the fields of Geography, Computer Science and Ecology.

Paper [V] applies a methodology for monitoring and modelling land-use change to forested landscapes of a northern border region between Finland and Russian Karelia. The analysis includes a database building stage, a forest mapping stage and a land-use modelling stage.

In the database building, medium resolution remotely sensed imagery is collected and georeferenced over a 15 year time span. Using simple change images, visual interpretation enabled the delineation of forest change areas in each era. Using a statistical method developed for the
Finnish Multisource Forest Inventory, a forest classification was created for the study area. In the final stage of the analysis, a spatio-temporal model was built to simulate the change in the forest fragmentation in the next 250 years, given the estimated cutting and fire levels. Finally, paper [VI] provides a theoretical framework for the monitoring of landscapes at the local or habitat level. It is suggested that the monitoring of ecosystems, which exhibit such characteristics as emergence, hierarchy and non-linearity, may best be addressed by moving
away from a pixel-based appraoch to an object-based approach. However, since we desire to not just replace arbitrarily imaged pixels with arbitrarily segmented landscape objects, a methodology called multiscale segmentation is proposed that cleaves to hierarchy and patch
dynamics theory. Two demonstrations of multiscale segmentation analysis and mapping of landscapes are described.

# 2. A theoretical and methodological background

## 2.1. Society and Geographic Information

Maps may be examined as “iconic or representational models and as conceptual models in a framework provided by the human being’s struggle to communicate to his fellows something of the nature of the real world” (Board 1979, p 671). The conception of geo-representations in this dissertation is as maps, “vehicles for the flow of information” (Board 1979, p 673) and as frameworks for information integration and analysis. This definition is adopted deliberately to allow a broad exploration of cartographic information models. In this way, maps, or better georepresentation artifacts, include both 1) general cartographic systems and 2) systems for scientific visualisation. These quite different uses of maps are grouped in this dissertation because the line dividing them is blurring, as shall be discussed later.

The traditional cartographic vehicles or models have been the 2 and 2½ dimensional (2½-D) “abstraction in symbolic form of the territory itself” (George 1979, p. 48). These cartographic models have been examined by Board (1979, p 675) with reference to scale and complexity (Figure 2). 2½-D describes a perspective in which the surface of a three-dimensional solid is represented but locations within the solid are not accessable (MacEachren 1995). The surveying and mapping of phenomena in a 2 dimensional x/y space or plane, but with the third dimension of height communicated only through symbols such as point heights or contours, thus adding only 0.5 and not a full third dimension. Full 3-D geo-representations are possible
only with a combination of volume data, which requires such as stereo aerial photography or scanning LIDAR (LIght Detection And Ranging) data, and computer-based visualisation tools.

The traditional 2½-D cartographic model is still the dominant spatial communication system used in society today. It is portable, lending itself to printed media and computer terminal. It is adaptable to an ever expanding range of applications, and easily understood. New representational models, however, have recently been introduced that communicate four dimensions of information, showing the full dimensionality of spatial volume (x, y, z) and time. 3-D city models are an example. What has prompted this change is firstly an increased need for more dimensionality, and secondly, a dramatic leap in our our ability to store, visualize and analyse additional dimensions of data. Both new demands for multidimensional geo-represntations and our increasing technological agency are explored in the first part of this thesis.

The Figure 2 schematic is a useful tool to organize the plethora of historical geo-representation artifacts. However, one must be cautious because the term ‘gradient’ and the arrows in each corner give the impression that those artifacts near the top left corner are somehow ‘more real’ than the artifacts in the bottom right. This is misleading, and the fact is that all artifacts are
abstractions of reality. Let me put it like this: to suggest that a detailed map of a factory floor is more ‘real’ than a satellite image of a continent is a fallacy. The plan and the satellite image both show a great deal of information, and the fundamental difference is the scale: both maps are equally products of human conception. By implying that ‘large scales’ equates more closely
to ‘reality’ is potentially dangerous. Take for example natural processes operating at global scales such as El Niño. “Model” scale (see Figure 2) information is obviously not what is required in order to examine such phenomena. It has been a truism in GI artifact development, and especially in the GI marketing literature, that more detail is by default better, and this is not necessarily true. This scale issue is central to this dissertation and shall be discussed in more depth later in sections examining GI data quality and methodology.

Figure 2. The gradient between Reality and Abstraction indicating examples of types of maps at their appropriate level of abstraction (Board 1979, p705).

In order to expand on the idea of collections of geo-representations collectively forming landscape information spaces, I offer the following diagramatic exposition. We have already explored how scale and complexity can be used to dissect the x and y plane into a range of mapping systems (Figure 2). In order to add volume (z) and the temporal dimensions to our diagram, we can collapse x and y into one vector. This is possible if we acknowledge that the x and y scale of a map are normally identical. We can then compare ‘cases’ of dimensionality. For example, historic maps with no height information can be compared as lines defined in terms of their different acquisition dates and scales (Figure 3a), while a single map with labelled height data (Figure 3b) is represented in the information space as a plane with height of 0.5. A series of topographic maps produced at regular time intervals would be represented as a series of 0.5 height quadrilaterals, while a digital elevation model (DEM) derived from stereo-aireal photography or similarly dense z dimension survey would be depicted as a quadrilateral with height of 1.0, symbolizing full 3-D (Figure 3c).

Figure 3. (a) 2-D quaternary deposit maps 1:20000 and 1:10000 scales, (b) 2-D map, with contours interpreted from a field survey of spot heights.

Figure 3(c) 3-D model underlying an aerial photograph. Model extracted from stereo aerial photographs.

The number of ways in which GI can be grouped into landscape information spaces is limitless, but only two more are described here. In paper [I] new GI artifacts are discussed which incorporate real-time location technology with images and 3-D models. Such georepresentations artifact could be described by a dimensionality diagram such as Figure 4a, in which 4-D map images are created continuously. The second diagram (Figure 4b) describes the dimensionality diagram for a GI artifact that incorporates the ability to make prognoses of future conditions in the mapped environment. Modelling functionality is explored in paper [IV].

Figure 4. New 4-D systems, (left) a real-time up-dated map and (right) modelling
future landscapes.

### 2.2. Biogeography and Landscape Ecology

Biogeography is the study of the geographical distribution of organisms, past and present. There are three main processes which are normally explored in biogeography: dispersal, evolution and extinction. All biogeographic patterns derive from these three processes, and each is equally important. The tradition of biogeographical research is long and the range of natural system components assessed has varied. For instance, Humbolt described the latitudinal zonality and high-altitude zonality of the plant and animal world in relation to climate. In 1899, Dokuchaev (1899) described a theory of natural zones, in which he called for the study, not of individual bodies and natural phenomena, but of certain integral territorial aggregates of them (Kalesnik 1962). In Russia, Berg (1947) detailed landscape zones. J. G. Granö introduced a prototypical system for the analysis of landscape as areal units concieved of in some way as complexes (Granö 1929, 1997). In Canada, integrated biogeographical concepts are used in an ecological land classification (Wiken and Ironside 1977) methodology that calls for the total integration of landform, lithology, relief, climate, soils and vegetation. As noted above, the processes of extinction and evolution are the key, and thus the emphasis of biogeographic research is normally on processes and patterns on a regional or broader spatial scale.

This dissertation examines methodology for exploring regional level forest fragmentation (IV, V) which is known to be related to extinction (Linden 2000), however the work also focuses on the spatial scales of individuals and mosaics of communities [VI]. Landscape ecology
emphasizes the interaction between spatial pattern and ecological process - that is, the causes and consequences of spatial heterogeneity across a range of scales. Landscape ecology might be defined best by its focus on spatial heterogeneity and pattern: how to characterize it, where it comes from, why it matters, and how it changes through time (Urban 1987). Two important aspects of landscape ecology distinguish it from other subdisciplines within ecology. First, landscape ecology explicitly addresses the importance of spatial configuration for ecological
processes. Not only is landscape ecology concerned with how much there is of a particular component but also with how it is arranged. Second, landscape ecology often focuses upon spatial extents that are larger than those traditionally studied in ecology, but smaller than biogeography. Landscape ecological studies are practiced on a scale large enough to include heterogeneity in ecosystems, usually larger than square kilometers (Golley 1995). Wiens (1992) noted that most landscape ecology studies were conducted at spatial scapes ranging from a few hectares to many square kilometers. The variety of scientific investigation undertaken within the rubric of Landscape Ecology can be seen in the following statements: landscape ecology is a study of complicated systems but needs to be referenced to an organism to be better understood (Turner et al. 1995), and the development of landscape ecology is a direct response to human activity within ecosystems (Kent et al. 1997).

### 2.3. Complexity and scale in ecosystems

Central to my thesis is the idea that there is a disparity between the sophistication of GI artifacts that have been developed for the study of landscape and the complexity of ecosystems at the landscape level. In order to explore this disparity, we need to briefly examine issues of complexity in ecosystems. Ecosystem science provides us with a variety of first principles with which we can encompass this compexity. I focus on three: self-organization and emergence, hierarchy and quasi-equilibria.

#### Self-organization and Emergence

The theory of self-organization suggests that dissapative self-organization results in the spontaneous creation of macroscopically ordered spatio-temporal and functional structures (Müller 1997). These structures create local heterogeneity which may be defined as the uneven, non-random distribution of ecological units (Kolasa and Rollo 1991). These macroscopic structures ‘emerge’ from the action of local rules which subsequently constrain the local interactions. If the phrase “the whole is more than the sum of the parts” is correct, then emergence constitutes the ‘more’ (Müller 1997). Table 1 provides a list of some of the properties of self-organized systems and corresponding phenomena in ecosystems (Müller 1997).

Two principles from the table above are given further consideration in the following sections.

*Hierarchy*

The complexity of an ecological system can be observed using a hierarchical approach in which every system is composed of a set of nested subsystems (Allen and Starr 1982, O’Niell et al. 1986, Allen and Hoekstra 1992, Holling 1992, Wu and Loucks 1995, Wu 1999). Hierarchy is defined as a partially ordered set in which the subsystems are interacting through asymetric relationships (Müller 1997). The holon is the basic unit of a hierarchy, defined as a self-regulating system as well as an autonomous subsystem. Holons exist as volumes of spacetime that are semantically separate from other spacespace because of relatively strong gradients in the flux of energy and matter (see for example Figure 3 in [VI]). There, a schematic representation of three levels of holons in a forest ecosystem are discretized; tree, community and forest. These hierarchical ideas have been melded with the patch-dynamic views of Forman and Godron (1986) as suggested by Wu (1999). For all hierarchical systems, the higher levels define the environmental limits of ecosystem processes while the lower levels represent the biotic potential of the system (O’Neill et al. 1989). Thus, as was true of selforganization, microscopic processes are coordinated by the macroscopic level, which is nothing else than the result of the interactions between the microscopic holons. This hierarchical perspective has been suggested not only as a framework for understanding natural complexity, but for building analysis systems. O’Neill (1988), for instance, recommends the use of three hierarchical levels as a minimum in system analytical studies.

*Quasi-equilibria*

The principle of quasi-equilibria addresses the non-static nature of Nature. Hierarchy theory claims that within the conditions of steady states, holons of higher levels are operating on large spatial extents with slow time constants while holons of lower levels are assigned with small extents and high frequency changes (Müller 1997). Thus there exists a temporal dimension to hierarchy. The over-all system thus exhibits meta-stability or resilience, while the components may resonate at a variety of higher energy levels (Bormann and Likens 1979). The issue of quasi-equilibria is discussed further in [V p. 5].

### 2.4. Earth observation data analysis: pixels problems?

To explore the utility of mapping artifacts and the complexity of natural systems, we also need to examine the sophistication of landscape ecological GI artifacts. As articulated in paper [V], GI artifacts utilize three types of data; survey, sample and ancillary. Survey data is some regularized sampling of the landscape, normally at a coarse scale, and includes earth observation (EO) or remotely sensed data. Sample data, often called field or ground truth, is the detailed environment data that assists in the interpretation of the survey data. Ancillary data is a catch-all group for data sets derived from the first two categories or data that supports them, such as meta-data (text lists describing acquisition dates, sensor callibration, field measurment procedures, etc.). Modern landscape ecology artifacts make use of all of these groups, to various degrees, but with a heavy emphasis on EO data.

Remote Sensing has become an essential data source for landscape ecological studies. No other survey technique can operationally provide a regularized survey of landscape with which to assess landscape level patterns and change. However, remotely sensed data, like all georepresentations, are imperfect capturings of natural pattern, which itself is only a partial reflection of physical and anthropogenic processes. In the following section I examine what has come to be known as the traditional method of satellite EO-based landscape analysis and mapping, the so-called picture element (pixel)-based “raster model of geographical phenomena (Fisher 1997)”. I explore pixels because they are problematic from a scale and process point of view, and to lay a critical foundation upon which the newer methods of EO data use can be discussed.

The traditional image analysis method is a classification of pixels based on the assumption that pixels in the same land cover class share are proximal in the spectral feature space delimited by the number of channels in an image. Put a different way, one assumes that the patterns in the image relate to broad classes of land cover which are spectrally relatively separable. Cracknell (1998) explores the the question “What’s in a pixel?” and makes the point that a pixel (the ‘footprint’ or ground instantaneous field of view, GIFOV) of a sensor is often larger than we would like it to be, a penalty imposed by the technology for the fact that the sensor gives an overview of a very large area.

The multiplicity of scales of landscape processes is also problematic. A large number of ways exist in which a study area can be divided into non-overlapping areal units for the purpose of spatial analysis (Marceau 1999) and some areal units will be better suited to the capturing of information on some objects than others. Thus a scale of measurement appropriate to exploring the pattern of one landscape process may not be suitable for a range of other processes. This phenomenon was described by Marceau et al. (1990), who found that 90% of the variability in the classification results was explained by the window size employed in the classification. Furthermore, the best classification accuracy for each land cover class was achieved with different window sizes (Marceau et al. 1990).

### 2.5. Beyond classic pixel-based Earth Observation

In the above section I have tried to show some of the problems of the pixel-based approach to landscape analysis. Potential solutions to the traditional uni-scale EO approach come from the use of multiple scales of data and the use of more sample and ancillary data sets. The broad range of methodological developments can be separated into two broad groups based on the nomenclature suggested by Strahler et al. (1986) in which L-resolution approaches deal with issues of landscape at the regional level, and are characteristically explored with GI data that is coarser in resolution than the elements in the scene (Figure  ). The corrolary holds for the Hresolution analysis wherein organism to community scale issues are explored and the GI data is finer in resolution than the elements of interest in the scene. The object of interest does not determine which methodological path is taken, rather it is the relationship between object and analysis resolution which is the determinant. Cases where the resolution is neither >> or << than the object, e.g. Figure 6, individual tree surveyed at digital camera (DC) resolution, are problematic. H-resolution image analysis methods may fail in these cases (Paper [III] pp. 2).

In this dissertation, both L-resolution and H-resolution methodologies were examined. Having two scales of landscape inquiry has allowed for an examination of the challenges inherent to a broader range of GI methodology development. This L- and H-resolution methodological division concurs with that of Luoto (2000) who notes that environmental changes and processes can be divided into two spatial scales: (1) the structure of individual habitats, and (2) the structure and composition of the landscape at a regional scale. These divisions are artificial, of course, and Jörgensen et al. (1992) suggest that “...a fundamental precept of new ecosystem
ecology must be that complex systems are not reducible, that from cell to biosphere the essence of systemness is interconnection.” The division is useful, since practical immaturity in GI tool development and theoretical immaturity prohibit wholistic studies at this time. Nevertheless, it is important to note that this binary division should more appropriately named a sliding scale division, since the dividing line beteen L- and H- resolution is context sensitive; depending on the data resolution, a landscape object (holon, patch) may be mapped in either mode.

Figure 5. Schematic showing relationship between object size and survey resolution creates two rough sets, L- and H-resolution. Each object, individual tree (a), stand (b) and forest community (c) can be examined in manner, depending on the EO resolution to object relationship. [AVHRR = NOAA Advanced Very High Resolution Radiometer, MSS & TM = Landsat Multspectral Scanner and Thematic Mapper, SPOT = ESA Satellite Pour le Observation Terrestial, DC = digital camera, IKONOS = 1m satellite, AP & AP2 = aireal photos at 2 scales]

2.5.1. L-resolution advances: better algorithms, more ancillary data

Several methods and algorithms have been developed to improve on the traditional pixel-based extraction of information from digital satellite imagery. Methods described in recent literature include sub-pixel analysis (Napelka & Hyde 1972, Foody & Cox 1994, Ichoku & Karnielli 1996) and related techniques attempts to ‘unmix’ the spectral composition of each pixel using linear mixing models (Gong et al 1991, Asner et al 1997, DeFries et al 1999). Several types of fuzzy classifiers (Bastin 1997) have been developed, including c-means clustering (Bezdek et al. 1984), possibilistic c-means clustering (Krihnapuram & Keller 1996) and fuzzy supervised classification Wang (1990). These fuzzy classifiers produce images showing the degree of membership of pixels to training categories and thus offer some additional data on pixel-level error. Foody (2000) critically notes that untrained classes will only display membership to trained classes, which can introduce a significant bias to classification accuracy. Neural network classifiers, borrowing concepts from artificial intelligence research, have also produced better results than conventional methods (Civco 1993; Paola & Schowengerdt 1995; Blackard & Dean 1999, Foschi & Smith 1997; Skidmore et al. 1997). Contextual techniques,
or segmentation, have been explored by Lobo (1997) and Stuckens et al. (2000). All of these classification algorithms incorporate context and have resulted in improved classification accuracy.

Other approaches incorporate ancillary data to a larger extent, for example for stratification (Fuller et al. 1994) and in post-classification correction or filtering routines (Harris & Ventura 1995). Another is the nonparametric k-nearest-neighbour (k-nn) method developed by Finnish Forest Research Institute for the Finnish Multi-Source National Forest Inventory (FMS-NFI).
This method utilises satellite images, digital map data and field measurements, and has been operational since 1990. A key aspect of the method is a heavy reliance on ancillary data. For instance, digital map data is used to mask out urban areas and to separate mire forests from mineral soil forests and the use of hundreds of field plots per remotely-sensed image. The
method incorporates spectral information from thousands of field plots per satellite scene to build the spectral feature space. The method preserves the covariance structure of the variables (Tomppo 1991). The k-nn method is designed for large area estimation and non-spatial inventory reporting, but it has shown fair results on the plot level. The k-nn method is used in [V] and its detailed mathematical formulation is available there.

2.5.2. H-resolution advances: beyond the pixel as a surrogate

When the object size is very large and when technological advances in sensor design, processing techniques and data storage provide fine resolution data, H-resolution methodologies are required. A number of higher resolution airborne (casi, digital camera,
Hymap) and space-borne (SPOT, IKONOS, QuickBird) sensor data sets are now available to researchers and land managers. Since the number of scene objects in a higher resolution image increases dramatically, inter-object spectral separability often declines. In this area, new GI methodology and processing algorithms are developing rapidly. A suite of techniques have
been developed to assist in the identification of scene objects (i.e. groups of pixels). I will briefly mention three groups: individual tree crown mapping, image segmentation and objectbased image modelling.

*Individual tree crown mapping*

The goal of individual tree crown mapping is to separate crowns from each other and from the background vegetation, to delineate precisely their crown boundaries, identify their species. Techniques for single tree isolation include spatial statistics, thresholding, local maxima filtering, valley following, edge detection and template matching (Hill and Leckie 1999, McGraw et al. 1998). The algorithms used in this study were local maxima filtering ([III, pp. 5] and [VI, pp. 14]) and valley following [VI, pp. 14]. Local maxima filtering (Gougeon and Moore 1988) utilizes moving windows that pass over an image and identify pixels of local
peak radiance. Window sizes of 3, 5 and 7 are commonly used on airborne imagery. Local maxima filtering works best on forest patches with uniform tree shapes and ages (i.e. plantations), and has more difficulty with complex canopies (Daley et al. 1998, Burnett et al. 1998). Valley following (Gougeon, F.A. 1995) takes the contrary approach, by defining the tree crown perimeter by delineating the shadowed surrounding pixels.

*Segmentation*

Segmentation operations, on the other hand, divide the image into contiguous clumps of pixels called “segments” or “regions” (Stuckens et al. 2000). This division is based on spectral similarity or dissimilarity measures. All pixels of a segment or region are then assumed to belong to the same information class. Segmentation algorithms are based on either region growing/merging (Kettig and Landgrebe, 1976), boundary detection (Marr and Hildreth, 1980), or a combination of both (Tilton, 1996). Segmentation algorithms based on statistical models have been proposed (e.g., the PICO regression model) (Acton, 1996), Markov Field models (e.g., Bauman and Shapiro 1994) spatial-autocorrelation (semi-variograms) (St.Onge and Cavayas 1997).

The segmentation algorithms used in this dissertation [VI, pp. 13] is an algorithm developed at the Finnish Forest Research  nstitute (METLA) using a modified implementation of the method presented by Narendra & Goldberg (1980). With it, spectrally similar adjacent segments (using three image channels) and segments smaller than a user-defined minimum size were merged with their neighbouring segment (Pekkarinen 2001). The similarity of the segments was measured by means of t-ratio (Hagner, 1990).

*Object-based image modelling*

The tree crown delineation and image segmentation algorithms described above require a broader analysis framework within to work because at some point relationships between objects have to be defined. Normally this requires a human expert. An object-based multiscale segmentation methodology is introduced in [VI, pp. 14]. Multiscale segmentation refers to the exercising of a multi-scale image dataset, including both airborne and satellite data, but also to the analysis of scales of information inherent in single images. The latter is possible because the multiscale segmentation methodology is a move away from pixel-based analysis, to an
object-based analysis, where multiple scales of objects (Hay et al. 1997) can be explored within a single dataset. In this way, high resolution images contain a hierarchy of image objects that relate, hypothetically, to the (naturally) hierarchically organized landscapes below. The key to object-based image analysis is that segmentation algorithms can output results in as vector format. Once imported into the GI database, segments can be associated with attribute data, including information of the sub-objects (and maybe sub-segments) existing within its area.

### 2.6. Modelling

The term ‘modelling’ is used in two contexts in this thesis, static and dynamic. The development of models to complement empirical studies is critical for (i) extending our understanding of the natural processes driving landscape dynamics; (ii) predicting the consequences of management actions; and (iii) developing theory in landscape ecology (Baker 1989; Fall & Fall 2000). Traditional GIS-based systems are static in nature and do not lend themselves very well to dynamic, inter-process modelling. Object-based image modelling [VI, pp. 14] is an example of static modelling. Static models are designed to operate independently. When effective decisions require the assessment of several components of the ecosystem simultaneously - in terms of their relationship to each other as well as how they affect management decisions, dynamic modelling is required [V, pp. 6]. Resolving conflicts,
identifying knowledge gaps, and making sustainable decisions all require analyses that encompass large spatial scales and processes acting over long time frames. In addition to difficulties arising from these characteristics, empirical experiments in landscape ecology are often hampered by the impracticality of experimental manipulation and a lack of suitable replicates. Dynamic modelling is a young science, with recent advances made in climate prediction and ocean current modelling (Baker 1989).

# 3. Methods

## 3.1. A critical assessment of GI artifacts and Society

The methodology for the general analysis of historical and current development in georepresntations ([I] and [II]) is the survey. The emphasis of both surveys is on trends within the binary evolution of society and technology. This attention to technology and society is found in the civic surveys of Scottish botanist and urban planner Patrick Geddes (1854-1932), who saw urban change as an “evolutionary sequence of technological development in an increasingly complex society (Robson 2001, p 192).” We divided the evolutionary stages of the surveys into the past, present and future and these time frames were given the titles of Pre-Digital Age,
Digital Age and Information Age [I]. Emphasis was put on defining trends that are active in the present, while acknowledging the historical lineage of sociotechnical developments as reflected in past mapping artifacts. The future part of the survey comprised prognoses and critical recommendations. The main sociotechnical trends examined were developments in (1) digital cartography and GI science, (2) digital remote sensing, (3) locational technology and (4) the internet. Prognoses for future GI artifact evolution, as explored in the Information Age section, describes how a convergence in these four trends is resulting in the emergence of new GI
artifacts.

Focusing a second survey on GI artifact development in Finland [II], the analysis was separated into historical traditions and then a combined examination of present trends and probable future scenarios. This latter analysis was subdivided into sections detailing digital data sources and processing methods; data combination challenges; interactive models of map communication; and cartographic reliability. The survey [II] parallels the three era time structure of the earlier survey by (1) emphasizing the need to understand and honour the cartographic tradition in order to develop sound new spatial analysis artifacts, (2) describing active research and development trends for new GI data and processing, and (3) projecting into the future with recommendations and cautious optimism.

## 3.2. Assessing remotely-sensed data quality

The importance of data quality assessment was explored [III] in a critical investigation of the relationship between the at-sensor recorded data and the resampled data delivered to users. The case study examined one line of imaging spectrometer data recorded over a forested landscape adjacent to Cameron Lake, British Columbia, Canada. Flying at a constant elevation over complex topography induces variation in the ground resolution of the acquired pixels. Level flight is conducted for the safety of the aircraft and to reduce variance in the along track resolution of the recorded pixels. Casi imagery (Anger at al. 1994) was flown over the study
sites between September 25-27, 1996. Data was acquired at a nominal 70 cm resolution in eight spectral bands (438 nm, 489 nm, 550 nm, 601 nm, 656 nm, 715nm, 795 nm, 861 nm; with generally a +/- 25 nm bandwidth). Imagery was geometrically corrected to 0.7 m
resolution with the aid of GPS, aircraft attitude data and digital elevation models. Nearest neighbour resampling had been specified for the data, thus the resampled data contained information on the within-image pixel size variance. A simple statistical analysis of
this variance was performed by collecting samples in transects at three positions in the image. Following the identification of sizable variance, the effects of this error on analysis steps was estimated using modelled data. The algorithm chosen for the analysis was the local maximum (LM) filtering technique for the identification of individual tree crowns (see Section 2.5.2.).

## 3.3. L-resolution case study and method

The Viena Karelia (Vienansalo) study area [30°07’47”E, 64°54’44”N] is an approximately 790.000 ha region of forested land in the Russian Republic of Karelia (see Fig. 1 in paper IV). Due to close proximity of the Finnish/Karelian border, the area contains large patches of remnant near-natural boreal forests (Linden et al. 2000). In order to assess the present and future fragmentation of these valauble forests, a three part analysis was undertaken. The spatial data sets used in the study comprise medium-resolution Landsat and SPOT data covering a 15 years time span beginning in 1986, a topographic map and a variety of derived GIS vector
layers (roads, lakes, urban, etc.). See Table 1 in paper [IV, pp. 3] for a listing of the principle datasets used in the Vienansalo study

### 3.3.1. Land-use monitoring

Visual interpretation ([VI, pp. 3] and [VI, pp. 6]) of the multi-date Landsat MSS and TM imagery was conducted in using image processing software, and a vector database created with layers for urban areas, roads, gravel pits, mine, mine lake, and three ‘eras’ of cut blocks: pre-1986, 1986-1994, and 1994-1998. In order to assist in the delineation and the separation of the
cut-blocks into the different eras, change images were created where the red (TM band 3) and near infrared (TM band 4) channels of different images (dates) were combined into RGB composites. For instance, with a combination of red channel (1994 band 4), green channel (1986 band 4), and blue channel (1986 band 4), new cutblocks appear bright as red patches on a greyscale background (see also description of ‘false date compositing’ [V, Appendix 1]). Once the GIS database was assembed and checked, road development and clear-cut spatial distribution monitoring was undertaken. For instance, based on the forest cut block era layers, mean (areal) rates of clear cutting for the years between 1986 and 1997 were calculated.

### 3.3.2. k-nn forest parameter estimation

A classification of the forest types was created based on forest species composition and basal area estimates. These estimates were made using the nonparametric k-nearest-neighbour (k-nn) algorithm (Section 2.5.1.). The k-nn estimation made use of a field database collected during four field visits in 1996-1999. In each type A plot, four sub-plots of 10m diameter were examined with relascope and a tree-by-tree survey, for DBH, species and height. Full descriptions of the over and under-story were made. Inputs to the k-nn processing were the rectified 1994 Landsat TM image, GPS coordinates for each field plot, and plot estimates for tree species composition, tree heights and basal area from the field database [V, pp. 8]. The outputs from the k-nn estimation algorithm were six raster layers covering the entire study area showing the relative proportions of pine, spruce, deciduous, mean height, basal area standing live trees and basal area of standing dead trees[V, pp. 9]. These k-nn estimate layers were converted into mire and forest type classes based on a clumping method. Non-forest layers (urban, roads, mine, and water) was also produced. A leave-one-out validation was made for the forest estimates and the results were favourable. The resulting raster data layers were exported for use in the SELES cell-based landscape simulation tool. The knn estimates were also use to parameterize some of the SELES models. For instance, logging was not allowed in areas that consisted of pure deciduous stands or in forested mires.

### 3.3.3. Forest fragmentation modelling

The effects of future management activities on the total amount and distribution of near-natural forests (‘old forests’) in the area was explored using a spatio-temporal simulation tool designed at Simon Fraser University, Canada. The Spatially Explicit Landscape Event Simulator (SELES) (Fall & Fall 2001). SELES provides a structured framework to guide development and simulation of spatial landscape models [V, Appendix 3]. Five future scenarios were explored; Status Quo, Maximum Fibre, Conservation, Fire Only and Status Quo plus Fire [V, Appendix 4]. Area statistics [V, pp. 12] and patch metrics were collected for each of the ten Monte Carlo runs made for each of the scenarios. Each scenario was run for 250 years. Fragmentation metrics derived from Fragstats (McGarigal & Marks 1995) that were calculated included number of patches, mean patch size, and size of the largest patch [V, pp. 13]. In the Status Quo and Conservation scenarios, for each patch the mean nearest-neighbour distance (mNN) and the minimum spanning tree (MST) were calculated [V, pp. 15]. These metrics are designed to further describe the spatial pattern landscape fragmentation.

## 3.4. H-resolution case study and method

The case study examined in H-resolution mode [VI] was Ruissalo Island, Finland. Ruissalo [22°09’07”E, 60°25’50”N] is a 9 km2 island situated in the archipelago of southwestern Finland, near the city of Turku. Due to natural characteristics and long term human
management, Ruissalo Island is home to one of the richest species communities in Finland. The Ruissalo forest patches differ in species, density, age and purity; ranging from dense immature birch (Betula pendula) plantations to mature stands of lime (Tilia cordata), Scots pine (Pinus sylvestris) and oak (Quercus robur). The island is managed as a recreation area with a large proportion designated as nature reserve. A thorough description of the land use history and biogeographic character of the island is given in Vuorela (2000). Species richness is affected, both positively and negatively, by the fragmentation of forest habitat through its
effect on the dispersal of individuals between active clusters and other areas of the suitable habitat. In order to assess the suitability of a given landscape structure for the maintenance and expansion of, for example, bird populations, land managers need tools with which to create maps with units (‘patches’) that correlate with an organisms awareness of forest structure. A multi-temporal, multi-spectral and multi-scale dataset was assembled, including base EO datasets of 1 m digital camera data and 2 m airborne AISA spectrometer data (Schulz et al. 1999). Field data was collected in the summers of 2000 and 2001. During these campaigns, individual tree crown mapping was carried out. For each of ten 20 m2 plots, all trees over 20cm DBH had the following data collected: GPS coordinates, species, crown dimension, diameter at breast height (DBH) and tree height. The ten field plots comprise 5 forest types typical to the island. The following methodological steps were adopted for the multiscale segmentation methodology: GI database building, segmentation, object relationship model building, visualisation and quality assessment. This methodology is founded on a view of Nature that exhibits self-organization, hierarchy and quasi-equilibria [VI, pp. 9].

### 3.4.1. Data Processing: crown delineation, patch segmentation

Individual dominant tree crown detection algorithms were applied to the 1 m digital camera data. Dominant tree crowns were delineated by local maximum (LM) filtering (Gougeon 1997, Wulder et al. 2000). Crowns were also delineated via a segmentation algorithm developed at the Finnish Forest research Institute. Additionally, using multispectral imagery at a lower scale
of resolution (airborne AISA at 2m GIFOV), the delineated objects (LMs and crowns) were separated spectrally using spectral signatures (Burnett & Pekkarinen (unpublished data)). LMs and crowns became, in effect, level –2 scene patches, with LMs being patches at the theoretical lower limit in size: one pixel.

In a second segmentation step, the digital camera data was again segmented. However, this time the scale of this segmentation was programmed to elicit homogeneous groups of crowns. The resulting set of image objects was designated the landscape level –1 patches. These segments and their attributes (and sub-unit attributes) were stored in the GIS database. Thus, for example, the perimeter length, area, mean spectral value, number of individual tree crowns, the species mix, the amount of bare rock outcrops and the mean dominant crown size was recorded for each level –1 sub-patch. Attributes for each segment were populated through a semi-automated process of data layer mining (see [VI, pp. 13] for more detail).

### 3.4.4. Creating functional unit maps: image object modelling Level –1 patch vectors were aggregated to form focal (level 0) patches based on a hypothetical model of nesting/foraging habitat. This aggregation was done in a semi-automated fashion,
with both rules-based aggregation and aggregation by a user using a GIS tool developed for the study (VI: Fig. 6). In the visualisation step, a level +1 or landscape level map of candidate habitat was created. It is important to stress that the output map was only one candidate georepresentation (see [VI, pp. 14] for more detail). The object-relationship model is explicitly
stated in the GIS environment and thus is flexible, or modifiable, for a different species or management question.

# 4. Main Results and Discussion

## 4.1. Artifacts change as part of broader societal trends

Human need is not static nor is technological agency. This is clearly documented in [I] and [II], where eras of mapping artifacts can be explored both in terms of what human needs were being addressed at a point in time (ie. the socio-historic context) and in terms of the technology of the day (ie. the techno-historic context). The sociotechnical synergy underlying all human development drives changes in communication systems into the Information Age [I]: GISc is both influencing and influenced by the digital transition’ currently being experienced by developed societies (Pickles 1999b).

I attempted to describe through diagrams in section 2.1 the change in space-time dimensionality that has accompanied recent evolution in geo-representations. Those 3-D explorations of 4-D space-time might serve as good examples of the classic “slice through
time” (Massey 1999, pp. 264) conceptualization of spatiality. Massey would, presumably, criticise such diagrams as flawed, or at least crippled, understandings of space in science. Massey (1999, 268) argues that a “representation necessarily fixes, and therefore deadens and detracts from, the flow of life,” quoting Harvey:

<p style="text-align: center;">Any system of representation, in fact, is a spatialization of sorts, which<br>
automatically freezes the flow of experience and in so doing distorts<br>
what it strives to represent... (Harvey 1989, 206)</p>

I agree, and doubly so for these figures, for they are representations of representations, or maps of maps. These diagrams allow for a very limited comparison of spatial artifacts with respect to time: they are meant to emphasize the idea of information spaces as human perceptions and conceptions of shared reality, but they do not go far enough. They do little to convey the range
of change or the factors underlying the change that occurs in reality, or realities if you like. They are diagrams for comparing maps and not diagrams for comparing spatial sociotechnical artifacts. To produce diagrams that better demonstrate “real temporality” (Massey 1999: 264), we would need to add some indicator that the context of the information space is changing. We might start by replacing the axis of ‘time’ with ‘context’. However, perhaps the two points I wished to convey have been made: there is much more to spatial artifacts than meets the eye, and spatial artifacts are evolving to embrace the increasing complexity experienced by humans.

Space-time dimensionality mapping is not the only, nor clearly the best, method for dissecting landscape information spaces. Since I am interested in demonstrating how GI artifacts are evolving, it is also instructive to examine the amount of ancillary data that exists behind the GI output, and to examine how much of this information is accessable to the map user. For example, a printed map commonly presents only a fraction of the information stored in the Geographic Information System database from which the map is derived. Electronic mapping systems, in theory, add more depth (dimension) to the information space. The traditional communication model of maps is being subverted, and both the data and the graphic conventions of map making are increasingly accessible to non-cartographers and nonscientists. Figure 6 presents schematics to explore this experience point of view.

This phenonema of increased access to cartographic data and tools to non-proffesional cartographers is a revolution. It is a boon to scientists who need to explore the relationships of spatial information. Examples of this type of analysis and visualisation are provided in [V] and [VI]. Increased access is also a boon to lay people, because maps are powerful communication tools. The corollary, is that the public has come to accept neatly printed maps at face value [I]. Unlimited access to data and tools has already led to poor quality cartographic products entering the market.

There are many other issues that must be assessed in order to examine evolutionary changes in geo-representation artifacts. These include the inclusion, or exclusion, of context information (Ahlqvist 2000, Vuorela 2000), error assessment (Goodchild & Gopal 1989, Gahegan & Ehlers 1999), decomposability, methodological transparency, data model formalization (Frank 2001), open standards, flexibility for adding new datasets and new methods [II]; and practical issues such as system speed and efficiency, ease of use, and whether the system will work in snowstorm! This list emphasizes the sociotechnical synergy of artifact development.

<p style="text-align: center;">Figure 6. The line between data and user is blurring. Evolution in<br> GI artifacts is adding data interaction functionality to systems with which advanced users can<br>
create customized maps. Cartographic tools are now increasingly accessable by<br>
lay people and scientists, for instance for scientific visualisation.</p>

Some issues are more societal, such as the debate between open source versus proprietory software development models. Another example is the challenge of addressing changes in societal context when comparing artifacts created at different stages of societal development. Others issues are clearly more technical, such as comparing data storage requirements. To over-emphasize either when criticizing or building artifacts is unwise.

The evolutionary surveys in mapping artifacts presented in [I] and [II] provides a final lesson in that it points out that echnological advances are not necessarily the product of universities. This is very much the case with GI artifact evolution in the Information Age. Undoubtably, university researchers play an important role. However, the roles of individuals, citizen groups, non-profic organizations, industry and government are central to the development of improved GI standards and services. Modern mapping systems can be both tools for societal stability and service continuity, and tools for social change.

These are interesting times for geographers and cartographers. The traditional map communication model which has evolved within society for thousands of years is undergoing a radical re-invention [I]. The four sociotechnical trends that characterized the evolution of geographic information analysis and communication in the Digital Age (digitization, EO data, positioning systems, and tele-connectivity), have resulted in refinements of the traditional map communication model and are spawning new models for analysing and disseminating GI information. These latter representations are made possible by the ‘digital transition’ currently being experienced by digital technologies as decribed by Pickles (1999b).

## 4.2. Spatial data quality is a critical issue for GI artifacts

Data quality issues are central to any criticism of geo-representation artifacts. The quotation from Harvey at the beginning of Section 4.1 cuts to the core of the issue: the capturing of spatial data distorts what it strives to represent (Harvey 1989: 206). Distortions arrise because we are generalizing a highly dimensional reality. By fixing this reality into a communicable form, we are by necessity degrading or distorting the signal. Distortion can be divided based on what dimensions are being distorted. If the distortion is related to capturing the first 4 dimensions of reality (Cartesian dimensions plus time) into a series of 2D representations, we are focusing on mechanical or technical degrading. Since reality is more than just a 4D space, other distortions must be assessed and these we may think of as aspects of conceptual degrading.

Cracknell (1998) provides a critical examination of technical degrading related to the collection of EO data. He examined the distortion of reality associated with the recording into two dimensional arrays of pixels of a four dimensional reality. EO-based images are measurements of up-welling radiance by instruments in motion. Cracknell (1998) explores the data quality aspects of pixel geometry, mixed pixels, sensor point spread functions and image resampling. Pixel shape is a distortion of the reality of the measurement process, because platform velocity is never constant and sensor optics cannot physically produce a square pixel. Topographic variation complicates this further [III], and in a topographically complex landscape the values of collected by the sensor can be quite different from the nominal resolution of the imagery provided by the data vendor. The devolution and convolution of pixels over parts of an image swath will likely affect texture algorithms, signature generation for classification, calculation of species proportions within a stand, stem counts, and closure and gap estimates [III, pp. 5]. The hypothetical local maximum tree crown delineating experiment in [III] demonstrated that topography and resampling can have an significant effect on analysis results (pp. 5).

Other spatial concerns include mixed pixels, which occur because the response of the sensor to a source of radiation with a given intensity will vary according to the location of the source within the field of view, i.e. there are no square lens optics. There will also be a response to sources just outside the geometrical IFOV as well (Cracknell 1998, Townsend et al. 2000). Thus a pixel centred above a water body but adjacent to an immature forest will have its water pixel signal modified in the infrared (IR) wavelengths by the intense IR reflectance of the forest. Fortunately, mixing is not uniform, and Fisher (1997) notes that commonly sensors are centre-biased such that the reflectance towards the centre of the field of view has the most influence on the recorded value. Unfortunately, these biases, as described by the optics, detector (i.e. point spread function) and electronics characteristics, are rarely communicated to users of the GI data. The process of registering the EO data to geographic coordinates, using a mathematical transformations, further introduces a filter between the pattern on the ground and the digital data available for analysis.

Spectral differences within EO data may be induced by atmospheric distortions, bidirectional (BR) effects, topography (ie. shadowing), vingetting, and within image mosaics through relative changes in solar and sensor positions relative to the imaged surface (Burnett et al. 2001). The term anisotropy is used to describe part of the bidirectional phenomenon wherein objects do not reflect radiation evenly in all directions. Trees, for instance, reflect much more intensely in the back-scatter direction, and correction of BR effects requires careful study of the scene objects and the sensor-scene model (Burnett 1999). Corrections for spectral distortion have been explored for video camera data (Pellikka 1998), digital camera mosaics (Pellikka et al. 1999), Landsat Thematic Mapper (TM) change detection (Tokola et al. 1999) and TM mosaicing (Toivonen et al. 2002).

Conceptual degrading of the signal can also take a variety of forms. An example is contextual differences arrising from the comparion of data collected for different purposes. Vuorela et al. (2002) has demonstrated the difficulties in doing change analysis with diverse data sets that include painted 17th century maps, aerial photographs and digital EO data. The fact that the 17th Century maps were designed for one purpose and the satellite data for another is as important an issue as the technical challenges of registering them for overlay analysis. Kalliola and Syrjänen (1991) provide another example in a comparison between the information available from satellite images and the information available through traditional vegetation maps created in the field. They concluded that the information available through manual interpretation of Landsat TM imagery, especially enhanced  images, was useful for identifying major plant physiognomic categories. However, beyond that, their analysis revealed a gulf between the classification system developed for field mapping and coarse information available from the satellite data. Reconciling these two ways of generalizing reality will require both higher resolution sensors and a re-conceptualization of the vegetation classification system. Jaakkola (1994) explores conceptual error as part of a feasability assessment for the automatic generalization and data quality assessment for the Finnish CORINE land cover program using Landsat imagery. This mismatching issue has been termed <em>conceptual error</em> by Jong (1990).

EO data is distorted in more ways than than is generally acknowledged and thus we must approach landscape analysis using geo-representations based on EO data cautiously. Additionally, users should demand as much transparency in pre-processing as possible. In [III, pp. 7] it is suggested, for instance, that additional image layers could be added by data providers giving view geometry, pixel acquisition dimensions and other meta data. For data providers, this type of transparency is difficult because a competitive market favours data that appears better than others. A growing number of data products are being produced by non-governmental agencies and companies. Market effects on GI data quality are complex. In some cases, the quality of data has decreased, for instance when companies have rushed the development of products or not fully disclosed data idiosyncrasies for fear of the data seeming poor. On the other hand, data quality is improving as the market provides new capital investment and incentive for research and development.

## 4.3. Disparities Between Landscape Ecology and GI Artifacts

There is a disparity between the sophistication of GI artifacts that have been developed for the study of landscape and the complexity of ecosystems at the landscape level. The complexity of ecosystems can be understood in terms of self-organization and emergence, hierarchy and quasi-equilibria (Section 2.3). As an example, we can examine the natural processes active in a boreal forest system. Biological and physics heuristics provide a framework within which energy flows. The result is an emergent complex of functional units as suggested in Figure 7. The following patch levels can be envisioned: needle, branch, tree, clump, stand, forest, landscape, biome. These functional units can be neatly understood as nested inter-connectedness, as a hierarchy [VI, Figure 3].

The natural complexity summarised in Section 2.3 high-lights the importance of boundary dynamics in landscape ecology and in cartography: gradients demarcate the spatial, functional, an temporal differences between structures or energentic and materialistic units in ecological systems (Müller 1997). Boundary types range from the sharp, clearly defined boundaries (ecotones) between more highly modified plant communities and anthropogenically created land-use types at on extreme, to more gradual and diffuse boundaries (ecoclines) between natural and semi-natural plant communities at the other (Kent et al. 1997). It is critical to identify appropriate focal scales and functional units to guide accurate placement of boundaries. Researchers are now beginning to address questions concerning the role of boundary dynamics in fragmented landscapes, specifically the importance of forest edges in influencing the flows of energy, matter and species both within and between landscape elements (Kupfer 1995). Critical delineation of boundries is central to the hierarchical patch structure developed in [VI].

Figure 7.  Differential energy/matter flux in open systems produces gradients that are expressed as emergent organization that from an anthropocentric point of view might be grouped into the following holons: (a) individual trees, (b) stands, (c) forests, and (d) landscape.

Gridded sample data suffers from a range of problems, including variations in acquisition resolution [III]. Some of these problems can be grouped as data quality issues and addressed, though never dispelled, through data processing steps (Section 4.2). However, issues related to complexity necessitate a re-thinking and re-designing of GI artifacts. Two issues are paramount: ecosystems are dynamic and ecosystems operate through a range of scales. In the following sections I discuss how new GI methods, including spatio-temporal modelling and multi-scale analysis, can be used to address ecological complexity.

## 4.4. Optimal methodology varies with study question

### 4.4.1. L-resolution: extending functionality beyond the pixel

The demands placed on geo-representation artifacts are increasing. (1) From a societal point of view, the cumulative impacts of human use on the boreal environment is such that the maintainability of some ecosystems is now in question (Hansson 1992). The old forest areas of the Vienansalo border region are a typical example of threatened boreal biodiversity, being of high cultural, economic and conservation value. The contrast between the large areas of near-natural Vienansalo forests alongside the managed forest mosaic of Finland is strikingly apparent in satellite images (IV, Linden et al. 1999, Yaroshenko et al. 2001).  Several other characteristics make Vienansalo typical of other threatened regions: a) spatial and ecological knowledge of the area is sparse or inaccessable, b) the local economy if very depressed, c) the area is biodiversity rich relative to neighboring areas, d) political action is stalled, and e) juristictional conflicts (between Karelia, Russia and Finland) hinder conservation efforts. The Vienansalo border forests are examples of fragile and dynamic ecosystems (Turner, Gardner & O’Niell 1995) and clearly make a good candidate study area for developing GI artifacts. (2) From a technological point of view, the amount of data being compiled about ecosystems and human imapct is growing at an exponential rate. New geo-representation artifacts must be developed which abstract but not over-simplify local and regional landscape components; are relatively inexpensive; and which address the dynamic nature of the conservation problem, by incorporating knowledge of anthropogenic and natural processes.

The monitoring and modelling methodology developed in [V, pp. 6] integrates three methods: multi-temporal monitoring, forest parameter estimation and spatio-temporal modelling. Landscape monitoring is the most conventional, and advanced change detection methods are being energetically explored (Heikkonen et al., 1999, Petit & Lambin 2001, Remmel & Perera 2001). The use of the k-nn estimation addresses the pixel problem described in Section 2.4. The resulting forest classification showed its utility as a base layer to input into a SELES modelling suite, providing estimates of forest parameters in both the proposed conservation areas and beyond, and this information was used to assess the economies related to the expected timber production in the protected areas as well as the nature types in them. From the forest classification we were able to note the differences in landscape composition in the Reserve, proposed Park and intervening land: useful information for conservation planning [V, pp. 16].

Finally, dynamic cell-based modelling appears to be an effective tool for exploring alternatives for the management of near-natural boreal forest areas. Not only do the rough landscape statistics show identifiable trends in landscape responses to human impact on forest structure, but spatially explicit modelling is also able to provide predictions in map-form, which is particularly useful as a concrete and intuitive means of communication [V, pp. 16]. The methodology is especially appealing since the satellite imagery required is relatively inexpensive and some of the tools are free (e.g. SELES). Manual interpretation of enhanced satellite images [IV] can be problematic in regions with complex existing land cover. For the Vienansalo area, this type of mapping was justifiable because the change patterns were so spectrally and geometrically distinct from the old forest matrix. In fifty to seventy years, when the models predict a reversal in this landscape pattern [V], more sophisticated change detection tools will be required. One option would be to incorporate some of the segmentation tools used in [VI] and develop an object-based change detection system.

4.4.2. H-resolution: mapping functional patches with hierarchical patch dynamics

Landscapes are complex systems, which by their very nature necessitate a multiscale or hierarchical approach in their analysis, monitoring, modelling and management (Hay et al. 2001). Defining patches that comprise a landscape is not a trivial task, being a contextual problem. Patches must be defined relative to a focal question or organism. From an ecological perspective patches represent relatively discrete areas (spatial domain) or periods (temporal domain) of relatively homogeneous environmental conditions. Their boundries are distinguished from their surroundings by discontinuities in environmental character states of magnitures that are precieved by, or relevant to, the organism or ecological phenomenon under consideration (Blaschke and Hay 2001). Zones of relatively high flux or gradient [VI, pp. 7] express themselves in EO imagery as pattern, and can best be explored by image processing algorithms that abandon pixel-based classification in favour of segmentation and object-relationship modelling.
The merits of a multiscale and segmentation-based methodology [VI, pp. 2] include the recognition that 1) environmental impacts by human activity is driving the need for analysis tools that operate at a range of landscape levels (ie. can be tuned to different focal organisms or species groups), 2) new GI data sources are providing data that is dimensionally dense, potentially allowing for a greater amount of information extraction if traditional pixel-based approaches are replaced or modified to take into account a greater amount of ecosystem theory, and 3) the methodology is theoretically more transparent than its forebears, because of the explicitly defined and retained object relationship model, and more flexible, allowing new datsets to be added and different research and management questions to be addressed by the same database.

# 5. Conclusions

Two data dense geo-representation systems were assembled during the course of this thesis. These multi-temporal, multi-spectra and multi-scale databases, together with their associated tools and methods for visualizing and analysis, form new GI artifacts what I have called information spaces. By exercising the 4D Vienansalo information space, using montiroing (visualisation) and modelling (analysis) tools, we can extract the fragmentation snapshots in [IV] and animated maps [V] of old forest areas. Both the snapshots and animations express the outcome of spatial processes in such a way that scenarios can be easily appreciated and criticized by experts and  non-experts alike. The multi-scale Ruisallo information space provides an example of a novel geo-representation interface which cleaves more closely to the complexity of Nature. These visualisation and analysis tools, and databases, are prototypes of information spaces that will in the near future combine vastly more density in data, visualization and analysis tools with which to address next generation Natural and human needs.

This study provided a critical exploration of the recent evolution of geo-representations, with particular emphasis on systems developed to address landscape ecology questions. The main conclusions of the research are as follows:

1. Mapping artifacts are symbol-based spatial communication systems, manifestations of a synergy between societal need and technology agency.<br><br>
2. Data quality issues are central to the criticism of mapping artifacts. <br><br>
3. Mapping artifacts evolve, codifying and empowering human understanding of nature.<br><br>
4. Mapping artifacts incorporating temporality and modelling are increasingly important tools for the analysis of landscape ecological processes and for the visualisation of alternative land-use scenarios for conservation.<br><br>
5. Ecological complexity can be accessed through hierarchical, object-orientated analysis. The multiscale segmentation approach allows for the exploration of landscape at organism-specific spatial and temporal scales.

# References

Acton, S.T. (1996). On unsupervised segmentation of remotely sensed imagery using nonlinear regressing. *International Journal of Remote Sensing* 17, 1407–1415.

Allen, T. F. H. & T.W. Hoekstra (1991). Role of heterogeneity in scaling of ecological systems under analysis. In: J. Kolasa & S.T.A. Pickett (eds.) *Ecological Studies 86: Ecological Heterogeneity*, 47-68. Springer-Verlag.<br>

Allen, T. F. H. & T.B. Starr (1982). Hierarchy: Perspectives for Ecological Complexity. University of Chicago Press, Chicago.

Anger, C., S. Mah & S. Babey (1994). Technological Enhancements to the Compact Airborne Spectrographic Imager (casi). *Proceedings, 1st International Airborne Conference and Exhibition*, Strasbourg, France, 11-15 September 1994, Vol. II, 205-213.

Asner, G.P., C.A. Wessman & J.L. Privette (1997). Unmixing the directional reflectances of AVHRR sub-pixel landcovers. *IEEE Transactions on Geoscience and Remote Sensing* 35, 868-878.

Baatz, M. & A. Schäpe (2000). Multiresolution Segmentation – an optimization approach for high quality multi-scale image segmentation. In: J. Strobl, T. Blaschke, & G. Griesebner (eds.) *Angewandte Geographische Informationsverarbeitung XII*, 12-23. Wichmann-Verlag, Heidelberg.

Baker, W.L. (1989). A review of models of landscape change. *Landscape Ecology* 2, 111-133.

Bastin, L. (1997). Comparison of fuzzy c-means classification, linear mixture modeling and MLC probabilities as tools for unmixing coarse pixels. *International Journal of Remote Sensing* 17, 3629–3648.

Bauman, C. & M. Shapiro (1994).  A multi scale random field model for Bayesian image segmentation. IEEE Image Processing 3, 162–177.
Berg, L.S. (1947). Geograficheskie Zony Sovetskogo Soyuza (Geographical Zones of the Soviet Union). Vol. 1-2. Moscow: Geografgiz.
Blackard, J.A. & D.J. Dean (1999). Comparative accuracies of artificial neural networks and discriminant analysis in predicting forest cover types from cartographic variables. *Computers and Electronics in Agriculture* 24, 131–151.

Blaschke, T. & G.J. Hay (2001). Object-orientated image analysis and scale-space: theory and methods for modelling and evaluating multiscale landscape structure.

Blaschke, T., S. Lang, E. Lorup, J. Strobl & P. Zeil (2000). Object-oriented image processing in an integrated GIS/remote sensing environment and perspectives for environmental applications. In: Cremers, A., Greve, K.(eds.): *Environmental Information for Planning, Politics and the Public*, Metropolis-Verlag, Marburg, Volume II. p. 555-570.

Board, C. 1979. Maps as models. In: R.J. Chorley & P. Haggett (eds.). *Models in Geography*, 671-725. Methuen and Co., London.

Bormann, F.H. & G.E. Likens (1979). *Pattern and Process in a Forested Ecosystem*. Springer-Verlag, New York Inc. 253 p.

Burnett, C.N. (1999). An exploration of conifer canopy anisotropy: 3D modelling versus airborne imaging spectrometer and multispectral scanner imagery. Unpublished MSc thesis. University of Victoria, Canada, 97p.

Burnett, C. & A. Pekkarinen (unpublished data). Results of a spectral separatation experiment using ITC and crown segments on Ruissalo Island.

Burnett, C.N., M. Wulder, N.M.A. Daley, K.O. Niemann, K. & D.G. Goodenough (1998). Directional variability in 1 m casi imagery: an analysis using semi-variance range and slope shape. *Proceedings, International Geoscience and Remote Sensing Symposium*, Seattle, 6-10 July 1998, 3242-3244.

Burnett C., N. Vuorela & T. Toivonen (2001). Different connotations of time in landscape research. In: Ü. Mander, A. Prinsmann, & H. Palang (eds.) *Proceedings, IALE Europe*, Stockholm/Tartu June 30-July 6 2001, 101-106. Publicationes Instituti Geographici Universitatis Tartuensis, Tartu.

Caldwell, M.M., P.A. Matson, C. Wessman, C. & J. Gamon (1993). Prospects for scaling. In: *Scaling Physiological Processes: Leaf to Globe*, 223-230. Academic Press.

Cracknell, A. P. (1998). Synergy in remote sensing – what’s in a pixel? *International Journal of Remote Sensing* 19, 2025-2047.

Cosgrove, D. (1984). *Social formation and symbolic landscape*. Croom Helm, London.

Daley, N.M.A, C.N. Burnett, M. Wulder, K.O. Niemann, K.O. & D.G. Goodenough (1998). Comparison of fixed and variable sized windows for the estimation of tree crown position. *Proceedings, International Geoscience and Remote Sensing Symposium*, Seattle, 6-10 July 1998.

DeFries, R.S., J.R.G. Townsend, & S.O. Los (1997). Scaling land cover heterogeneity for global atmosphere-biosphere models. In: *Scale in Remote Sensing and GIS*, 231-246. Lewis Publishers.

DeFries, R.S., J.R.G. Townsend & M. Hansen (1999). Continuous fields of vegetation characteristics at the global scale. *Journal of Geophysical Research* 104, 16911-16923.

Dokuchaev, V.V. (1899). *On the theory of natural zones*. Sochineniya (collected works). Vol. 6. Moscow-Leningrad: Academy of Sciences of the USSR, 1951.

Fall, A. & J. Fall (2001).  A domain-specific language for models of landscape dynamics. *Journal of Ecological Modelling* 141, 1-18.

Fisher, P. (1997). The pixel: a snare and a delusion. *International Journal of Remote Sensing* 18, 679-685.
Forman, R.T.T. & M. Godron (1986). Landscape Ecology. Wiley, New York.

Frank, A.U. (2001). Tiers of ontology and consistency constraints in geographic information systems. *International Journal of GIS* 15, 667-678.

Friedl, M.A., F.W. Davis, J. Michaelsen & M.A. Moritz (1995). Scaling and uncertainty in the relationship between the NDVI and land surface biophysical variables: An analysis using a scene simulation model and data from FIFE. *Remote Sensing of Environment* 54, 233-246.

Gahegan, M. & M. Ehlers (1999). A framework for the modelling of uncertainty between remote sensing and Geographic Information Systems. In: Ehlers & Schiewe (eds.) *Geoinformatik* 99, 17-26. Materialien Umweltwissenschaften Vechta, Vechta.

George, F.H. (1979). The use of models in science. In: R.J. Chorley, & P. Haggett (eds.) *Models in Geography*, 43-56. Methuen and Co., London.

Gong, P., J.R. Miller, J. Freemantle & B. Chen (1991). Spectral decomposition of Landsat Thematic Mapper data for urban land cover mapping. *Proceedings, 14th Canadian Symposium on Remote Sensing*, Calgary, Alberta, 458-461. Canadian Remote Sensing Society, Ottawa.

Goodchild, M. & S. Gopal, eds. (1989). *The accuracy of spatial databases.* Taylor & Francis, London.

Goodchild, M.F., Egenhofer, M.J., Kemp, K.K., Mark, D.M., Sheppard, E. (1999). Introduction to the Varenius project. *International journal of geographical information science*, 13, 731-745.

Gougeon, F.A. & T. Moore (1988). Classification individuelle des arbres à partir d’images à haute résolution spatiale. *Proceedings, Télédétection et gestion des ressources Vol. VI , 6e congrès de l’association québecoise de télédétection*, Sherbrooke, Québec, 4-6 May 1988.

Gougeon, F.A. (1995). A crown-following approach to the automatic delineation of individual tree crowns in high spatial resolution aerial images. *Canadian Journal of Remote Sensing* 21, 274-284.

Gougeon, F.A. (1997). Recognizing the forest from the trees: individual tree crown delineation, classification and regrouping for inventory purposes. *Proceedings, 3rd Int. Airborne Rem. Sens. Conf. and Exh.*, Vol. II. Copenhagen, Denmark, July 7-10, 807-814.

Graham, S. (1998). The end of geography or the explosion of place? Conceptualizing space, place, and information technology. *Progress in Human Geography* 22, 165-185.

Granö, J.G. (1929). *Reine Geographie*. Eine methodologische Studie, beleuchtet mit Beispielen aus Finnland und Estland. 202 pp. Acta Geographica 2.

Granö, J.G. (1997). *Pure Geography*. 191 p. The John Hopkins University Press, Baltimore & London.

Hagner, O. (1990). Computer aided forest stand delineation and inventory based on satellite remote sensing. *In: The usability of remote sensing for forest inventory and planning* (Proceedings of the SNS/IUFRO workshop Umeå, Sweden, 26 - 28 February 1990). Swedish University of Agricultural Sciences, Remote sensing laboratory, Umeå.

Hansson L. (1992). Landscape Ecology of Boreal Forests. *Trends in Ecology and Evolution* 7, 299-302.

Harvey, D. (1989). *The condition of postmodernity*. Blackell, Oxford.

Hay, G.J., K.O. Niemann & D.G. Goodenough (1997). Spatial thresholds, image-objects and upscaling: a multi-scale evaluation. *Remote Sensing of Environment* 62, 1-19.

Hay, G.J., P. Dube, A. Bouchard & D.J. Marceau (2002). A scale-space primer for exploring and quantifying complex landscapes. *Ecological Modelling* (accepted).

Heikkonen, J., J. Varjo & A. Vehtari (1999). Forest Change Detection via Landsat TM Difference Features. *Proceedings, Scandinavian Conference on Image Analysis* 11, 157-164.

Hill, D.A. & D.G. Leckie, eds. (1999). *Proceedings of the International Forum on Automated Interpretation of High Spatial Resolution Digital Imagery for Forestry*, Victoria, British Columbia, Canada, February 10-12, 1998. Natural Resources Canada, Canadian Forest Service, Victoria, B.C., Canada.

Holling, C.S. (1992). Cross-scale morphology, geometry, and dynamics of ecosystems. *Ecological Monographs* 62, 447-502.

Ichoku, C. & A. Karnielli (1996). A review of mixture modeling techniques for sub-pixel land cover estimation. *Remote Sensing Reviews* 13, 161-186.

Jong, S. (1990). Intergration of remotely sensed and GIS data to determine SPOT classification accuracy. *Proceedings, EGIS’90*, Amsterdam, Netherlands, 517-525.

Jörgensen, S.E., B.C. Patten, & M. Straskraba (1992). Ecosystems emerging: towards an ecology of complex systems in a complex future. *Ecological Modelling* 62, 1-27.

Kalliola, R. & K. Syrjänen (1991). To what extent are vegetation types visible in satellite imagery? *Annales Botanici Fennici* 28, 45-57.

Kalesnik, S.V. (1962). Landscape science. In: C.D. Harris (ed.) Soviet geography, accomplishments and tasks 201-204. *Am. Geog. Soc. Occasional Publ*. No.1, American Geographical Society, New York.

Kent, M., W. J. Gill and R. P. Armitage (1997). Landscape and plant community boundaries in biogeography. *Progress in physical geography* 21, 315-353.

Kettig, R.L., & D.A. Landgrebe (1976). Classification multispectral image data by extraction and classification of homogeneous objects. *IEEE Transactions on Geoscience Electronics* 14, 19–26.

Kupfer, J. A. (1995). Landscape ecology and biogeography. *Progress in Physical Geography* 19, 18-34.

Linden, H., P.I. Danilov, A.N. Gromtshev, P. Helle, E.V. Ivanter, & J. Kurhinen (2000). Large-scale forest corridors to connect the taiga fauna to Fennoscandia. *Wildlife Biology* 6, 179-188.

Lindholm, T., R. Heikkilä & M. Heikkilä, eds. (1997). Ecosystems, fauna and flora of the Finnish-Russian Nature Reserve Friendship. *The Finnish Environment* 124, 1-364.

Lobo, A. (1997). Image segmentation and discriminant analysis for the identification of land cover units in ecology. *IEEE Transactions on Geoscience and Remote Sensing* 35, 1136–1145.

Luontoliitto (1997). Green Belt from a Finnish perspective: Position of Finnish environmental organizations. <http://www.luontoliitto.fi/forest/greenbelt/finnishperspective.html>.

Luoto, M. (2000). *Spatial analysis of landscape ecological characteristics of five agricultural areas in Finland by GIS*. Fennia 178, 15-54.

MacEachren, A. M. (1995). *How maps work: representation, visualisation and design*. Guilford Press, New York, 513 p.

Marr, D., & E. C. Hildreth (1980). Theory of edge detec-sensed images. *Proceedings, The Royal Society*, 187-217. London, England.

Marceau, D., P.J. Howarth, J.M.M. Dubois, D.J. Gratton (1990). Evaluation of the gray-level co-occurrence matrix (GLCM) method for land-cover classification using SPOT imagery. *IEEE Transactions of Geoscience and Remote Sensing* 28, 513-519.

Marceau, D. (1999). The scale issue in the social and natural sciences. *Canadian Journal of Remote Sensing* 25, 347-356.

Massey, D. (1999). Space-time, ‘science’ and the relationship between physical geography and human geography. *Trans. Inst. British Geographers* 24, 261-276.

McGraw, J.B., T.A. Warner, T. Key & W. Lamar (1998). Advances in high resolution remote sensing for forest ecological studies. *Trends in Ecology and Evolution* 13, 300-301.

Narendra, P. & M. Goldberg (1980). Image segmentation with directed trees. *IEEE Transactions on Pattern Analysis and Machine Intelligency*. Pami-2, 185-191.

O'Neill, R.V. (1988). Hierarchy theory and global change. *In: Rosswall, T. Woodmansee, R.G., Risser, P.G. (eds.) Scales and Global Change*, 29-46. Wiley, Chichester.

O'Neill, R.V., D.L. DeAngelis, J.B. Waide & T.F.H. Allen (1986). A Hierarchical Concept of Ecosystems, *Monographs in Population Biology* No. 23. Princeton University Press. Princeton, NJ. 253p.

O'Neill, R.V., A.R. Johnson & A.W. King (1989). A hierarchical framework for the analysis of scale. *Landscape Ecology* 3, 193-206.

Paola, J. D. & R.A. Schowengerdt (1995). A detailed comparison of back propagation neural network and maximum-likelihood classifiers for urban land use classification. *IEEE Transactions on Geoscience and Remote Sensing* 33, 981-996.

Pekkarinen, A. Image segment-based spectral features in the estimation of timber volume. Submitted to *Remote Sensing of Environment*.

Pelllikka, P. (1998). Development of correction chain for multispectral airborne video camera data for natural resource assessment. *Fennia* 176, 1-110.

Pellikka, P., D.J. King & S.G. Leblanc (1999). Quantification and removal of bidirectional effects in airborne color infrared imagery using a multi-look approach. *Proceedings, 17th Biennial Workshop on Color Aerial Photography and Videography in Resource Management*, Reno, USA, 5-7 May 1999, 13-24.

Petit, C.C. & E.F. Lambin (2001). Integration of multi-source remote sensing data for land cover change detection. *International Journal of Geographical Information Science* 15, 785-803.

Pickles, J. (1999b). Cartography, digital transitions and questions of history. *Proceedings of the International Cartographic Association Annual Conference*, Ottawa, Canada, August 1999. CD.

Raper, J. (2000). *Multidimensional Geographic Infromation Science*, Taylor & Francis, London. 300p.

Remmel, T. K. & A.H. Perera (2001). Fire mapping in a northern boreal forest: assessing AVHRR/NDVI methods of change detection. *Forest Ecology and Management* 152, 119-129.

Robinson, A.H. (1952). *The Look of Maps*. University of Wisconsin Press, Madison.

Robson, B.T. (1981). Geography and social science: the role of Patrick Geddes. *In: I. Stoddart & D. Ross (eds.) Geography, ideology and social concern*. Basil Blackwell Publishers, London. 250p.

Schulz, M., R. Kalliola & P. Pellikka, P. (1999). Use of imaging spectrometer data to determine seasonal patterns and changes in wooded parkland landscape in SW Finland. *Proceedings, 4th International Airborne Remote Sensing Conference and Exhibition*, Ottawa, Canada, 21-24 June 1999, Vol. II, 641-647.

Souriau, M. (1994). Scaling and physical thresholds: the case of continental topography. *International Journal of Remote Sensing* 15, 2403-2408.

St. Onge, B.A. & F. Cavayas (1997). Automated forest structure mapping from high resolution imagery based on directional semivariogram estimates. *Remote Sensing of Environment* 61, 82-95.

Strahler, A.H., C.E. Woodcock & J. Smith (1986). On the nature of models in remote sensing. *Remote Sensing of Environment* 20, 121-139.

Stuckens, J., P.R. Coppin & M.E. Bauer 2000. Integrating contextual information with per-pixel classification for improved land cover classification. *Remote Sensing of Environment* 71, 282–296.

Tilton, J. C. (1996). Hybrid image segmentation for earth remote sensing data analysis. *Proceedings, International Geoscience and Remote Sensing Symposium*, Lincoln, Nebraska, 703–705.

Tokola, T., S. Lofman & A. Erkkilä (1999). Relative Calibration of Multitemporal Landsat Data for Forest Cover Change Detection. *Remote Sensing of Environment* 68, 1-.

Tomppo, E. (1991). Satellite image-based national forest inventory of Finland. *International Archives of Photogrammetry and Remote Sensing* 28, 419-424.

Townsend, J.R.G., C. Huang, S.N.V. Kalluri, R.S. DeFries, & S. Liang (2000). Beware of per-pixel characterization of land cover. *International Journal of Remote Sensing* 21, 839-843.

Turner, M.G., G.J. Arthaud, R.T. Engstrom, S.J. Hejl, J. Liu, S. Loeb & K. McKelvey (1995). Usefulness of spatially explicit population models in land management. *Ecological Applications* 5, 12-16.

Turner, M.G., R.H. Gardner, R.V. O'Neill. (1995). Ecological dynamics at broad scales, ecosystems and landscapes. *Science & Biodiversity Policy, Supplement to Bioscience*, American Institute of Biological Sciences, Washington D.C.

Vuorela, N. (1997). Historialliset kartat maisemaekologisessa tutkimuksessa: esimerkkinä Ruissalo, S-W Finland, *Terra* 109, 67-75.

Vuorela, N., P. Alho & R. Kalliola. Systematic assessment of maps as source information in landscape change research. *Landscape Research*, submitted.

Wiens, J. A. (1992). What is landscape ecology, really? *Landscape Ecology* 7, 149-150.

Wu, J. (1999). Hierarchy and scaling: extrapolating information along a scaling ladder. *Canadian Journal of Remote Sensing* 25, 367-380.

Wu, J. & O.L. Loucks (1995). From the balance-of-nature to hierarchical patch dynamics: a theoretical framework shift in ecology. *Quarterly Review of Biology* 70, 439-466.

Wulder, M., K.O. Niemann, & D.G. Goodenough (2000). Local maximum filtering for extraction of tree locations and basal area from high spatial resolution imagery. *Remote Sensing of Environment* 73, 103-114.

Yaroshenko, A.Y., P.V. Potapov & S.A. Turubanova (2001). *The last intact forest landscapes of northern European Russia*. Greenpeace, Moscow, Russia. 75p.
