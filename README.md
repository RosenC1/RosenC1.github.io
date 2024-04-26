Unraveling the Mysteries of Model Decisions with t-SNE
In our journey through the fascinating world of AI with the fastai course, we've encountered a treasure trove of tools for peeling back the layers of neural network decision-making. Today, I'd like to take you through a particularly revealing technique: t-SNE visualization.
![image](https://github.com/RosenC1/Jiacheng-s-CV-Assignment/assets/168141223/013d52aa-7cee-4ebf-bef5-c3df6a2bf75e)

This colorful scatter plot might look like abstract art, but it's actually a window into how a classification model perceives different categories of images. The technique reduces complex, high-dimensional data into a 2D space, clustering data points (in this case, images) such that similar items are grouped together.
![image](https://github.com/RosenC1/Jiacheng-s-CV-Assignment/assets/168141223/e5d55459-8a87-44aa-8011-06c0ac44fb1b)

From the plot, it's clear that our model has done an impressive job of clustering images into distinct categories, a testament to the power of convolutional neural networks and the efficacy of our training process. However, life (and data) is rarely perfect—some points stray from their clusters, highlighting potential outliers or unique instances that buck the trend.

Intriguingly, a few clusters overlap slightly. Are these shared boundaries a sign of common features, or perhaps an indication of where our model's confidence wavers?

Lessons Learned and Next Steps
This visualization isn't just a pat on the back for our model—it's a guide to further improvement. Here's what we're planning next:

Investigate Overlaps: Why do some categories blend into each other? We'll examine these images closely to understand the features causing confusion.
Fine-Tune the Model: Armed with insights, we'll refine our model. Perhaps we'll introduce more data, or maybe we'll adjust the architecture itself.
Outlier Analysis: Those wayward points may be errors, or they may be genuinely unusual images. They deserve a closer look to improve our dataset quality.
Through this explorative process, we're reminded that AI is as much about questions as answers. Each finding leads to new inquiries, propelling us forward on our AI odyssey.

Stay tuned for our next adventure, and in the meantime, happy learning!

