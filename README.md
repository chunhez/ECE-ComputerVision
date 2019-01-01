# ECE-ComputerVision
This repository includes the term project for computer vision class.

The project considers the problem of food segmentation. In this project, an active contour algorithm is implemented to allow a user to semi-automatically segment food items in a photograph of multiple foods on a dinner plate. An active contour, also known as a "snake", is a semi-automated method for segmentation. It takes an initial contour and iteratively moves it based upon a set of criteria. The goal is to start with an initial contour close to a desired location, and then use the active contour algorithm to drive the contour to the final desired location.

In this project, five images are provided: bacon-eggs-toast.pnm (3 items), eggs-pancakes-milk.pnm (3 items), hushpuppies-biscuits.pnm (2 items), fish-lemon-rice-greens.pnm (4 items) and macaroni-kale.pnm (2 items). The image names indicate the number of food items in each image, which is also the number of segmented regions expected to be produced. This report also discussed the influence of different parameters and the way to improve performance.

The GUI is built in MS Visual Studio 2017.
