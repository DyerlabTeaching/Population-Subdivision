# Population Subdivision

<!-- BEGIN module:header -->

![Looking down over green desert scrub and rocky ridges to the Sea of Cortez south of Loreto, Baja California, with a small rocky island and a distant larger one offshore.](https://dyerlabteaching.github.io/PopulationSubdivision/media/module_image.jpg)

<!-- END module:header -->

## Impetus

Few species are a single randomly mating population.  Most are broken into subpopulations by space, habitat, or timing, and the amount of gene flow among those pieces determines whether they drift apart or are held together.  This module introduces the classic models of connectivity among subdivided populations (the island–mainland, island, and stepping-stone models) and a general network model that covers them all, and uses simulation in R to predict how allele frequencies change under gene flow and where they come to rest.

## Module Learning Objectives

### Model Gene Flow Among Subdivided Populations

> Learners will describe how the island–mainland, island, stepping-stone, and general models connect populations, and write the recursion that predicts each population's allele frequency in the next generation.

- **Bloom's Levels:** Understand, Apply
- **Reinforces:** The geometric approach to equilibrium developed for recurrent mutation in [Drift and Mutation](https://dyerlabteaching.github.io/Drift-and-Mutation/narrative.html), and random mating as an assumption of [Hardy-Weinberg Equilibrium](https://dyerlabteaching.github.io/Hardy-Weinberg-Equilibrium/narrative.html).
- **Notes:** Emphasizes the difference between migration and gene flow, and that allele frequencies change through immigration, not emigration.

### Predict Allele Frequency Change Under Gene Flow

> Learners will simulate allele frequencies through time on an arbitrary connectivity network in R, determine the equilibrium and how long it takes to reach it, and explain which populations set that equilibrium.

- **Bloom's Levels:** Apply, Analyze
- **Reinforces:** Loops and `data.frame` objects for building simulations in R.
- **Notes:** With one-way gene flow, the equilibrium is set by the source populations, not by the average of all populations.

## Content

<!-- BEGIN module:resources -->

- The [slides](https://dyerlabteaching.github.io/PopulationSubdivision/slides.html) for this topic.
- A longer [narrative](https://dyerlabteaching.github.io/PopulationSubdivision/narrative.html) that goes into more depth.
- An [in-class](https://dyerlabteaching.github.io/PopulationSubdivision/in-class.html) activity.
- Wright S (1931) [Evolution in Mendelian populations](https://doi.org/10.1093/genetics/16.2.97). *Genetics* 16: 97–159, which introduced the island model.
- Kimura M & Weiss GH (1964) [The stepping stone model of population structure and the decrease of genetic correlation with distance](https://doi.org/10.1093/genetics/49.4.561). *Genetics* 49: 561–576.

<!-- END module:resources -->

## Assessment

- A [homework](https://dyerlabteaching.github.io/PopulationSubdivision/homework.html) assignment on the topic.

## Logistics

- A [Teaching Log](https://dyerlabteaching.github.io/PopulationSubdivision/log.html) record of delivery and notes.

## Contact Information

If you need to contact me, I am available at:
- Email: [rjdyer@vcu.edu](mailto://rjdyer@vcu.edu)
- Web: [rodneydyer.com](https://rodneydyer.com)
