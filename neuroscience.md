---
layout: page
permalink: /neuroscience/
title: "computational neuroscience"
---

# Computational Neuroscience
Computation neuroscience provides tools and methods for:
1. characterizing [what](https://github.com/sophiechenyang/sophiechenyang.github.io/blob/main/neuroscience.md#descriptive-model-of-cortical-receptive-fields) nervous systems do
1. determining [how](https://github.com/sophiechenyang/sophiechenyang.github.io/blob/main/neuroscience.md#mechanistic-model-of) they function
1. [why](#interpretive-model-of-receptive-fields) they operate in participular ways 
(P.Dayan and L. Abbott)

Receptive field comprises of specific properties of a sensory stimulus that elicts a very robust or strong response from the cell. Examples may include spot of light that turns on at a _particular location_ on the retina, or bar of light that turns on at a _particular orientation_ and _location_ on the retina. 

visual cortex cell of a cat's brain

![descriptive model of receptive field](https://i.imgur.com/ae7WEws.png)
 
#### Descriptive model of Receptive Fields 
When a person looks at an object, the inverted image is projected onto the back of the eye on the retina. The layer of tissues called the retinall ganglion cells convey information about the image to the lateral geniculate nucleus (LGN), which in turn passes the information to the primary visual cortex in the back of the brain. You can find the receptive fields in the retina by flashing a spot of light on different locations of the retina. 

##### Center-Surround Receptive Fields in the Retina

An on-center, off-surround cell becomes more active when only the center of this area is illuminated and less active when the only edges of this area (the surround) are illuminated. Conversely, cells with an off-center, on-surround receptive field respond with increased activities when light is turned off in the center region and on in the surrounding region.  

![center-surroound receptive fields in the retina](https://i.imgur.com/7pklArV.png)

In the visual cortext, we can find cells that respond best to different orientation and center-surround receptive fields 

![center-surroound receptive fields in the retina](https://i.imgur.com/qq685v8.png)

#### Mechanistic Model of Receptive Fields
The mechanistic model of receptive fields attempts to answer the question of how receptive fields are constructed using the neural circuitry of the visual cortex. In the Lateral Geniculate Nucleus (LGN), we find receptive fields that are center surround, similar to what is found in the retina. In the primary visual cortex (V1), we find receptive fields that are elongated at certain orientations. 

![receptive fields in lgn and v1](https://i.imgur.com/STLcX6b.png)

According to the model suggested by Hubel & Wiesel in the 1960s, V1 receptive fields are created from converging LGN signals. The center-surround LGN RFs are displaced along preferred orientation of the V1 cell. This model is considered quite controversial as it does not take into accounts the recurrent input to V1. 

![mechanistic model of rf](https://i.imgur.com/c0NiRRp.png)

#### Interpretive Model of Receptive Fields

The interpretive model of receptive fields attempts to understand why receptive fields in v1 are shaped this way. In other words, what are the computational advantages of such receptive fields? 

The elongated orientated bars do not span the entire retina, but only a small portion of it. Therefore, we can combine them to make a huge variety of images. Simillary, an image reconstruction I can be seen as a linear combination of a set of receptive fields where the multipliers are the strength of the response of a neuron (with a particular receptive field) to the visual stimulus.  Diifferent algorithms can be used to generate the ideal RFs that minimize the total squared pixelwise errors between I and I^ and are as independent as possible, including sparse coding ( Olshauren & Field, 1996), ICA ( Bell & Sejnowski, 1997) and predictive coding ( Rao & Balland, 1999). The RFs are chosen based on two selection criterias:

1. **Efficient representation** -  representing images using as few components as possible 
1. **Faithful representation** - accurate representation of important image features

The RFs found using efficient codiing algorithm on natural image patches match the RFs observed experimentally. This suggests that perhaps efficiency and faith representation were also the optimization criteria used during the evolution of the primary visual cortex. 

![rf efficient algorithm](https://i.imgur.com/HFLYEII.png)


## Resources
[Code repository of Neural Systems Modeling by Thomas J. Anastasio](https://github.com/vogdb/neural-systems-modeling-exercises)

