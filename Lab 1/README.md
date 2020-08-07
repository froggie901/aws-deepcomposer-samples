# Using the AWS DeepComposer Music studio to create tracks 

The AWS DeepComposer music studio allows you to create music using trained models. To create your next masterpiece 
you can record a custom input track, use a sample input track, or import a .midi track. 

After choosing the **Source of input melody** you can start generating compositions. 

## Getting started 
Browser support for the AWS DeepComposer console varies. We *recommend* using Chrome for this lab. If you want to know
more about which features are supported by different browsers check out the [Browser support documenation](https://docs.aws.amazon.com/deepcomposer/latest/devguide/browser-support.html). 

>**Note** The exercises in this lab assume you've signed in to the AWS DeepComposer console. To use the AWS DeepComposer
>console and other AWS services, you need an AWS account. If you don't have an account, see [aws.amazon.com](https://aws.amazon.com/)
>and choose **Create and AWS account**. For detailed instructions, see [Create and Activate an AWS Account](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/)  

### Exploring the AWS DeepComposer music studio, make your first composition  

1. Open the [AWS DeepComposer console](https://console.aws.amazon.com/deepcomposer)

2. Open the navigation pane (&#9776;), choose **Music studio**

3. Choose &#9658; to play the default melody.
![music-studio-press-play](images/lab1-press-play.png)

4. Choose **Generative Adversarial Network** from the **Model Parameters** card under **Generative AI technique**

5. Choose **Generate composition** to create a new composition

6. Choose &#9658; to listen to your new AI generative musical composition

### Changing the source of your input melody
The AWS DeepComposer supports uploading custom input melodies and recording custom melodies.

#### Recording a custom input melody 
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

4. Choose **Generative Adversarial Network** from the **Model Parameters** card under **Generative AI technique**
>**NOTE** You can use either between either the **MuseGAN** or **U-Net** under **Generative algorithm** in the **Model parameters**
>card 

5. Choose **Generate Composition**

6. Choose &#9658; to listen to your new AI generative musical composition

#### Importing tracks in AWS DeepComposer
The AWS DeepComposer music studio allows you to import your own input track. You can upload input tracks that are MIDI formatted files, and the file size is less than 10 KB.  

>**NOTE**
>ou certify that you own all necessary rights to any content you upload/import and you acknowledge and agree that you
>will not use AWS DeepComposer to violate or infringe the intellectual property rights of others.

1. Open the [AWS DeepComposer console](https://console.aws.amazon.com/deepcomposer)

2. Open the navigation pane (&#9776;), choose **Music studio**

3. To open the **Input melody** section, choose the door arrow (&#9660;)

4. Change **Source of input melody** to **Imported track**

5. Choose **Choose file** to import your track

6. Choose **Generative Adversarial Network** from the **Model Parameters** card under **Generative AI technique**
>**NOTE** 
>You can use either between either the **MuseGAN** or **U-Net** under **Generative algorithm** in the **Model parameters** card 

7. Choose **Generate Composition**

8. Choose &#9658; to listen to your new AI generative musical composition


## Next steps 
Congratulations! You have learned how to use pre-trained models to generate new music. Try experimenting with different
Generative AI techniques or algorithms, and different input tracks.   
