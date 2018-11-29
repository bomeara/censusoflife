## Census of Life

This is my proposal for NSF's [Idea Machine](https://www.nsf.gov/news/special_reports/nsf2026ideamachine/index.jsp). I work in related areas, and have a background in insect systematics, but this is not my expertise: if this inspires you to write a grant, etc. and you want to use ideas from this, go for it! It's a big problem that needs smart people working on it. 

-- [Brian O'Meara](http://www.brianomeara.info)

## What is the compelling question or challenge? 

The goal is a census of life in the United States: population size and location of all species. This will require collaboration across engineering, computer science, biology, remote sensing, and more.

## What do we know now about this Big Idea and what are the key research questions we need to address? 

Systematists have labored for decades to try to discover every species; ecologists have worked as long to understand population dynamics of selected species; resource managers in fisheries and forestry work to maintain populations of their focal groups. However, we have extremely little data on populations as a whole. [Lister and Garcia (2018)](http://www.pnas.org/content/115/44/E10397) recently showed that insect populations in Puerto Rico rainforests dropped as much as 60-fold since 1976. This came as a shock, even to experts working in this long term ecological research site. In scale, it was as if we only noticed this year that since the 1970’s, every American vanished except residents of Houston, Phoenix, and Philadelphia. The only other study of population decline of insects in general showed a decline 76 to 82% ([Hallmann et al. 2017](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0185809)), only possible through the decision of German insect enthusiasts to use exactly the same trap design for a quarter century. There is remarkably little information for other groups (birds, through the Christmas Bird Count, may be an exception). How has fungus biomass declined in the Pacific Northwest? Lizard and snake biomass in the Appalachians? Beetle biomass in New England? We have no idea: these could have crashed or spiked, new species could have appeared, and there is no baseline comparison to use. Through the work of systematists and other naturalists, we can pull information from repositories like GBIF to learn where species are, but this still does not tell us how many individuals remain. It can also be hard to discover changes until they directly impact humans: we see directly harmful invasive species, but species that may do slower damage through indirect effects (destruction of leaf litter by invasive earthworms, restructuring spider communities by changing physical structure by invasive plants) could go undetected. 

The trouble, of course, is adopting approaches that can scale to the question. Finding what species exist is difficult; finding regions where they live, more so; but figuring out how many individuals there are, whether by count or by mass, can feel insurmountable. Below are the main research questions; later sections show how they can be achieved.

Key research questions:

* What is the current population (measured as biomass and/or population size or density) of major groups (insects, non-insect arthropods, fungi, woody angiosperms, birds, amphibians, squamates, archaea, eubacteria, etc.) across the United States?
* What is the current population (measured as biomass and/or population size or density) of particular species across the United States?

However, and this is an important outcome of the project, to answer these questions one must also address these secondary questions:

* How can we automate species detection (machine learning, remote sensing, eDNA detection, and more)?
* How can we interpolate to estimate density at a given unsampled point?
 
The key research questions are seductively simple, enabling interaction across fields to address the secondary questions.

## Why does it matter? What scientific discoveries, innovations, and desired societal outcomes might result from investment in this area? 

The idea that a census is essential for understanding the country has been embedded in the Constitution from the beginning. Data from this was originally intended just for deciding on representation, but having an accurate census of the population has been of tremendous importance in learning about migrations of people, how policies have affected where people can live, the need for roads, and more. As we understand more about connections between the natural world and human welfare, it is clear a census needs to deal with all life. Are pollinator numbers crashing, have bat and other insectivore numbers rebounded, are sturgeon expanding into this river again are all questions that have direct relevance to people. A census is also a discrete, understandable idea that the public and other stakeholders can support. This will also create vivid examples for teaching. “Based on predictions from similar areas from the Census of Life, this field behind the school likely has 15 snakes and a hundred bird nests. How many do you think we can see?” “Within ten miles of our university there are over two thousand individual trees from seventeen species, ranging from pines to pawpaws.”

The discrete goal will also help foster synthesis across fields. There are already elements to build on: 14 million citizen science observations plus machine learning approaches let iNaturalist users get nearly instantaneous, automatic identification of species they photograph on their smartphones. Remote sensing approaches are also being used to count animals in low complexity environments (penguins on snow and ice, right whales in the ocean). Environmental DNA approaches are being used to detect the presence of salamanders from wisps of DNA washing downstream. Metagenomic techniques identify a wide diversity of microorganisms in the soil. GBIF aggregates locality information from museums and herbaria. Species distribution models help predict where a species will live based on existing records and climate information. Computers with microphones can listen to bat calls and sort them to species. But these are all separate fields and research programs. The idea of a Census of Life generates a crystallizing goal that all can understand. This will encourage collaboration: a national camera trap network linking to machine learning powered by iNaturalist data, combining eDNA with automatic sequencing to record aquatic species through time, developing ways to use soil microbiomes to better predict populations of other species. This quest will generate spinoff products.

As with the US Census, GBIF, Genbank, and other aggregations of data, once this is all gathered in one place it becomes a resource to use in myriad questions relating to conservation, the effects of global change, measuring the efficacy of interventions intended to help biodiversity, environmental services, and more. It also prevents surprises such as finding that 98% of insect biomass disappeared before anyone noticed.

## If we invest in this area, what would success look like?

The [Census of Marine Life](http://www.coml.org/), launched nearly two decades ago and with a more modest goal, is a reasonable floor for success. It generated over 3100 scientific papers, extensive datasets, and considerable scientific outreach, though the proposed project is more extensive in scope. On the key questions, success is an analog of Bioclim layers, but rather than rainfall or minimum temperature in geographic cells it is population size or biomass of large categories of organisms (insects, trees) as well as individual species. These cells will include uncertainty of the estimates, and each layer will have metadata on how the information was generated. Given the thousands of species having a layer for each species is unrealistic, but layers for indicator or ecological keystone species could be targeted in initial rounds and more species added as methods are developed to better scale.

For the secondary questions, success comes from freely available products that lead to assessment of population sizes. These could be ways of scaling up or linking available technology (automatic species identification from photos paired with a trail cam network; drones that automatically take soil samples back to have their metagenomes sequenced; machine learning approaches that count trees and sort them into putative species): feasible today or in the near future, but difficult to organize without a central motivating goal that a census provides. 

Another spin off success would be moving these technologies and other info into other domains. The same technology that identifies a canid in a camera trap could be used to identify potential insect pest species on imported produce; the same algorithms used to count cacti in the desert could be used to identify homes at risk for wildfire. 

## Why is this the right time to invest in this area?

It has become terrifyingly apparent from recent studies how little we know about actual populations. Disparate fields of science are working on approaches that could address this (machine learning for images and sounds; revolutions in environmental DNA sequencing, remote sensing through drones and satellites). They are all rapidly developing and already have demonstrable utility, but they have not yet ossified into a single standard way to do things. It is thus the perfect time to promote synergy between them. This requires a single, understandable target that appeals to everyone, and a Census of Life is such a target.  

This is a key moment for understanding biodiversity. The world is changing rapidly, and while we know many of the causes, we are doing an incompetent job monitoring the effects. Each scientist in this area pursues their own research interest: state of the cod fishery, response of hemlocks to invasive insects, and so forth, but a top down goal could unite them all.

The tools are just coming available now: eDNA, genomics, remote sensing, AI. The expertise is dying now (taxonomists). This is the only time to do it. 
 
