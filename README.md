# Febreze ScentStories
 This repository tracks a simple attempt at reverse engineering the Febreze ScentStories, specifically its Symphony board from 2004 (2004-05-25). I am curious about reverse engineering the device, partly to miniaturize it further so that more people can look at how others have engineered scent technologies through history.

 ## Historical background
The Febreze ScentStories was a 2004 scent technology marketed as a home fragrance product. Media likened the device to a "CD player for smells," which provided "music for the nose." The device is loaded with a disc that contains five scent pockets (each with a heat-sensitive fragrance gel), and each odor exudes for roughly 30 minutes. Under the disc are a thermoelectric element (Peltier element) and thermistor to heat the scent pocket directly above, increasing the vaporized odorants in the pocket. The device had a fan blow air over the pocket to distribute the odor into the room. Users could adjust the odor intensity by raising or lowering the heat and could skip a scent pocket.

Country singer Shania Twain promoted the product ([interview with Twain including a TV commercial for the device](https://www.youtube.com/watch?v=z-RFbigZrQ8)). Six scent discs were originally released: (1) _Shades of vanilla_, (2) _Relaxing in the hammock_, (3) _Strolling through the garden_, (4) _Exploring a mountain trail_, (5) _Wandering barefoot on the shore_, and (6) _Celebrate the holidays_.


 ## What needs to be done
 * Reproduce the PCB layout with correct footprints.
 * Identify the FEGO153S mystery microcontroller being used.
 * The disk motor control is a bit mysterious at the moment. 
 * Document the three heating temperatures.
 * Produce an approximate 3D model for new scent discs.