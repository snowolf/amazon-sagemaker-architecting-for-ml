# Architecting for ML - DeepComposer Module

## Your Mission

You are responding to a call for content from Amazon Studios to compose the soundtrack for a new movie on space exploration and colonization. They want the theme to reflect our Baroque music culture but at the same be reflective of advanced science that powers space travel. The studio wants new sounds and has heard about AWS DeepComposer that uses Machine Learning and Generative AI to create new music. They reach out to you to compose a test track for them that should be a minute long that should be harmonically elegant, contain Bach like chords, contain fresh embellishments and should impress them. If they like your track you will be hired to compose music for the movie.


## Machine Learning at the hands of every developer

Organizations across industries are relying on Machine Learning to help them solve for a variety of use cases including predictive analytics, forecasting, business optimization, robotics, industrial process automation, design efficiencies etc. At AWS our mission is to put Machine Learning at the hands of every developer and data scientist. To that end, we launched **AWS DeepLens** for object detection use cases at the edge, **AWS DeepRacer** to make it fun to learn Reinforcement Learning and now with **AWS DeepComposer**, we want to educate, enrich and provide an immersive platform to our customers on a new branch of Machine Learning called Generative Adversarial Networks (**GAN**) that can **generate new levels of creativity based on a set of inputs.** ****GAN is already popular in a variety of industries today with Autodesk using GAN to design highly efficient Airplane Wings for example. In collaboration with AWS DeepComposer product and engineering teams, we introduce an immersive and fun event format for our customers to experience GAN first-hand.


## Generative AI with AWS DeepComposer

Viewed by some as the most interesting machine learning idea in a decade, Generative AI allows computers to learn the underlying pattern of a given problem and use this knowledge to generate new content from input (such as image, music, and text). In contrast to more commonly used machine learning models that learn to differentiate, for example between images of cats and dogs (by identifying traits that set them apart), a Generative AI model based on cat images would learn the features that are common across cats, and use that knowledge to generate all-new images of what it believes are cats. This difference is significant because with the advancement in Generative AI algorithms, machines can automatically discover and learn the patterns in data and generate new data based on the data they were trained on.

Regardless of your experience with machine learning (ML) or music, you can use AWS DeepComposer to develop a working knowledge of generative AI. AWS DeepComposer includes learning capsules, sample code, and training data to help you understand and use generative AI models.

## The Challenge

You have to complete the following two steps to complete your challenge:

1. Use Generative Adversarial Network (GAN) to train a ML model using a dataset of Bach compositions so that the model learns to add accompaniments to a single track input melody. In other words, if the user provides a single piano track of a song such as "twinkle twinkle little star", the GAN model would add three other piano tracks to make the music sound more Bach-inspired. 

2. Use AWS DeepComposer to generate music that needs to be as similar to a Baroque or Bach style composition as you can get. You can select from one of the several samples already provided by DeepComposer. You then use a combination of Autoregressive CNN and GAN techniques to infuse creativity, accompaniments and unforeseen embellishments to the input piece resulting in diverse musical variation but you will have to stay close to Bach or Baroque. Once you complete a composition, you can upload it to SoundCloud (yes you will have to create an account for yourself) with the tag **#aug-arch-ml-workshop** (uncheck the chart buster challenge checkbox). Some tips and criteria to considering when creating your composition:

 * Originality – a unique composition
 * Rhythm – enhances melody/harmony
 * Accompaniment/chord progressions – supportive
 * Cleanliness of sound – polished composition
 * Emotional Resonance - how do you feel when you listen to this

## Get Started

* You can get started with this sample notebook - https://github.com/aws-samples/amazon-sagemaker-architecting-for-ml/blob/master/Starter-Code/Architecting-for-ML-GAN.ipynb
* We use the midi files from the DeepComposer samples here for our notebook - https://github.com/aws-samples/aws-deepcomposer-samples/tree/master/Lab%202/original_midi

**Hint:** Use the links provided in the resources below to learn about GAN and how to use DeepComposer

## Resources

* DeepComposer Demo Videos from Youtube - https://www.youtube.com/watch?v=XH2EbK9dQlg&t=9s
* DeepComposer Learning Capsule 1 Generative Adversarial Networks - https://console.aws.amazon.com/deepcomposer/home?region=us-east-1#learningCapsules/introToGANs
* DeepComposer Learning Capsule 2 Autoregressive CNN - https://console.aws.amazon.com/deepcomposer/home?region=us-east-1#learningCapsules/autoregressive
* Creating a new music genre model - https://aws.amazon.com/blogs/machine-learning/creating-a-music-genre-model-with-your-own-data-in-aws-deepcomposer/
* SoundCloud - https://soundcloud.com/tags/awsdeepcomposer
