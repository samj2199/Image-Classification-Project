# Image Classification Project: Journey and Insights :-

-It can be noticed that we have uploaded 3 ‘.ipynb’ files. Each file explains our exploration of image classification across three distinct attempts, each building on the lessons and outcomes of the previous. This journey took us from a custom made dataset to the complexities of CIFAR-10, testing different models along the way.

## *FIRST ATTEMPT :- The Custom Dataset Challenge

- We started with custom curated image dataset but soon hit roadblocks:
- Our dataset was too simple - just birds and squirrels. This simplicity didn't push our models enough and led us to dead-ends at every new trial.
- Acquiring 500 images each of birds and squirrels was definitely a task in itself.
- We messed up on balancing our classes due to duplication, which gave us a bad start with our initial results.
- Some images were just not good enough, leading to more noise than signal.

From this, we learned a very important lesson - good data is more than just quantity. It’s about variety, balance, and clarity all coming together.

## *SECOND ATTEMPT :- (Moving to CIFAR-10: A Leap Forward)

-Realizing the limitations of our custom dataset, we jumped to CIFAR-10 for our second attempt. Why? Because it's a well-rounded challenge with 60,000 images across 10 categories. Using the ResNet model, we wanted to see if our approach could scale with better data. Spoiler: It did. The diverse, high-quality dataset of CIFAR-10 was a game-changer, allowing us to refine our approach in a way our custom dataset never could.

## *THIRD ATTEMPT :- (Third Time's a Charm: VGG16)

-With CIFAR-10 as our new standard, we decided to switch gears model-wise. Enter VGG16. The question was simple: With the right dataset and methods in place, could a different model boost our results? Turns out, yes. VGG16 brought a fresh perspective to our CIFAR-10 images, showcasing the importance of matching model strengths to dataset characteristics.

## *ON NOT MEETING OUR SIX-MODEL GOAL :-

-We aimed high, hoping to test six different models. But reality checked in – time, resources, and the initial dataset hiccup limited our reach. While we're not thrilled about falling short, the strides we've made with GoogleNet, ResNet, and VGG16 have been incredibly revealing. Each step was a learning curve, and we're coming out wiser.
