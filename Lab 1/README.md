# Using the AWS DeepComposer Music studio to create tracks 
The AWS DeepComposer Music studio allows you to create and edit music. To create your next masterpiece, 
you can record a custom input track, use a sample input track, or import a .midi track. The music studio supports two
generative AI techniques, generative adversarial networks (GANs) or an autoregressive convolutional neural network (AR-CNN).

To get started, choose a **Source of input melody** and then you are ready to start creating music. 

**Note** 
>The exercises in this lab assume you've signed in to the AWS DeepComposer console. To use the AWS DeepComposer
>console and other AWS services, you need an AWS account. If you don't have an account, see [aws.amazon.com](https://aws.amazon.com/)
>and choose **Create and AWS account**. For detailed instructions, see [Create and Activate an AWS Account](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/)

## Getting started 
Browser support for the AWS DeepComposer console varies. We *recommend* using Chrome for this lab. If you want to know
more about which features are supported by different browsers check out the [Browser support documenation](https://docs.aws.amazon.com/deepcomposer/latest/devguide/browser-support.html). 
  
### Exploring the AWS DeepComposer music studio, making your first composition  

1. Open the [AWS DeepComposer console](https://console.aws.amazon.com/deepcomposer)

2. Open the navigation pane (&#9776;), choose **Music studio**

3. Choose &#9658; to play the default melody.
![music-studio-press-play](images/lab1-press-play.png)

4. Choose **Generative Adversarial Network** from the **Model Parameters** card under **Generative AI technique**. You
can try experimenting with the different **Generative algorithms** and **Models**.

**NOTE**
> The available **Models** will change based on the **Generative algorithm** you select.  

5. Choose **Generate composition**

6. Choose &#9658; to listen to your new AI generative musical composition

### Changing the source of your input melody
With AWS DeepComposer you can import an input melody and record a custom melody.

#### To record a custom input melody 
Before recording a custom melody you can enable several settings to help make recording easier. 
To change your settings, choose the settings icon (&#x2699;)
 - **Metronome** will enable/disable a metronome being played while you are recording your melody. One the slider is enabled, you can adjust the metronome on the Music studio console.  
 - **Hot Keys** will allow you to use your computers keyboard when you are recording your melody 
 - **Countdown** enables a 5 second countdown before recording your melody 

1. Choose &#x25cf; to start recording a *custom melody*
    - If you need inspiration, you can try recording '*Mary had a little lamb*'
    ![custom-input](images/lab1-custom-music.png)

2. When finished, choose &#9632;

3. To trim an unwanted section of the input melody, choose one of the handles on the sides of the track, and drag it to remove the unwanted section.

4. Choose **Generative Adversarial Network** from the **Model Parameters** card under **Generative AI technique**. You
can try experimenting with the different **Generative algorithms** and **Models**.

**NOTE** 
>The available **Models** will change based on the **Generative algorithm** you select. 

5. Choose **Generate Composition**

6. Choose &#9658; to listen to your new AI generative musical composition

#### To import a track into Music studio 
The AWS DeepComposer music studio allows you to import your own input track. You can upload input tracks that are MIDI
formatted files, and less than 10 KB in size.  

>**NOTE**
>You certify that you own all necessary rights to any content you upload/import and you acknowledge and agree that you
>will not use AWS DeepComposer to violate or infringe the intellectual property rights of others.

1. Open the [AWS DeepComposer console](https://console.aws.amazon.com/deepcomposer)

2. Open the navigation pane (&#9776;), choose **Music studio**

3. To open the **Input melody** section, choose the down arrow (&#9660;)

4. Change **Source of input melody** to **Imported track**

5. Choose **Choose file** to import your track

6. Choose **Generative Adversarial Network** from the **Model Parameters** card under **Generative AI technique**. You
can try experimenting with the different **Generative algorithms** and **Models**.

**NOTE** 
> The available **Models** will change based on the **Generative algorithm** you select. 

7. Choose **Generate Composition**

8. Choose &#9658; to listen to your new AI generative musical composition

## Next steps 
Congratulations! You have learned how to use pre-trained models to generate new music. Try experimenting with different
Generative AI techniques or algorithms, and different input tracks.   
