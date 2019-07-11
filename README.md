# Fashion product categorisation and attribute extraction from images

A keras implementation of the following paper:

**A Unified Model with Structured Output for Fashion Images Classification - Ferreira *et al* (2018)**

**Abstract**: A picture is worth a thousand words. Albeit a cliché, for the fashion industry, an image of a clothing piece allows one to perceive its category (e.g., dress), sub-category (e.g., day dress) and properties (e.g., white colour with floral patterns). The seasonal nature of the fashion industry creates a highly dynamic and creative domain with evermore data, making it unpractical to manually describe a large set of images (of products). In this paper, we explore the concept of visual recognition for fashion images through an end-to-end architecture embedding the hierarchical nature of the annotations directly into the model. Towards that goal, and inspired by the work of [7], we have modified and adapted the original architecture proposal. Namely, we have removed the message passing layer symmetry to cope with Farfetch category tree, added extra layers for hierarchy level specificity, and moved the message passing layer into an enriched latent space. We compare the proposed unified architecture against state-of-the-art models and demonstrate the performance advantage of our model for structured multi-level categorization on a dataset of about 350k fashion product images.


https://arxiv.org/abs/1806.09445


This project was developed for a Google Colab environment. It may require some modification for running in a locla jupyter environment.

## Key files:

`product_image_categorisation.ipynb` - main notebook containing code to download dataset, build and train model, and predict categories and attributes for previously unseen images

`move_images.ipynb` - Use this file to move and resize the images to avoid issues with Google Drive mounting which occur when thousands of files exist within one folder.

`tensorboard.ipynb` - use this notebook during model training to access TensorBoard in Colab.
