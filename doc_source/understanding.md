# 1: Understanding the Amazon Lumberyard Interface<a name="understanding"></a>


****  

|  | 
| --- |
| This topic references tools and features that are [legacy](https://docs.aws.amazon.com/lumberyard/latest/userguide/ly-glos-chap.html#legacy)\. If you want to use legacy tools in Lumberyard Editor, disable the [CryEntity Removal gem](https://docs.aws.amazon.com/lumberyard/latest/userguide/gems-system-cryentity-removal-gem.html) using the [Project Configurator](https://docs.aws.amazon.com/lumberyard/latest/userguide/configurator-intro.html) or the [command line](https://docs.aws.amazon.com/lumberyard/latest/userguide/lmbr-exe.html)\. To learn more about legacy features, see the [Amazon Lumberyard Legacy Reference](https://docs.aws.amazon.com/lumberyard/latest/legacyreference/)\. | 

In this section, you learn the basics of Lumberyard's interface\. You also explore and play the completed level for this tutorial series, giving you a solid understanding of what you'll be building\.

This tutorial shows you how to do the following:
+ [Open Lumberyard's orientation level](#understanding-opening) – Open the orientation level, explore the welcome screen, and preview the completed level that you'll be building\.
+ [Identify the basic tools](understanding-identifying.md) – Become familiar with the primary areas of Lumberyard's interface\.
+ [Navigate in the viewport](understanding-navigating.md) – Learn how to move efficiently around the level\.
+ [Manipulate objects](understanding-manipulating.md) – [Select](understanding-manipulating-select.md), [Move](understanding-manipulating-moving.md), [Rotate](understanding-manipulating-rotating.md), and [Scale](understanding-manipulating-scaling.md) objects\.
+ [Configure auto backup](understanding-auto-backup.md) – Configure incremental backups so that you don't lose your work in the event of a crash or freeze\.

## Downloading and Installing Lumberyard<a name="understanding-prerequisites"></a>

Before you get started, download and install Lumberyard\. Use the installation [tutorial](https://s3.amazonaws.com/gamedev-tutorials/Tutorials/Getting_Started_01_Download-Install-Express_1.10.pdf) if you need instructions\. After you have set up Lumberyard, launch Lumberyard Editor and proceed to the next section\.

## Opening the Orientation Level<a name="understanding-opening"></a>

To familiarize you with Lumberyard's opening screen and basic controls, open the first tutorial level called **GSG\_01\_Orientation**\.

**To open the orientation level**

1. Launch Lumberyard Editor\.

   The **Welcome** screen appears by default each time you open Lumberyard\.

   On the welcome screen, you see the following:
   + **A** – **Current Project** – Displays the project that you are currently working on\. If you click the project name, the following options appear:
     + **Switch project** – Closes Lumberyard Editor and opens the **Project Configurator**, which you can use to switch to another project\.
     + **Setup Assistant** – Closes Lumberyard Editor and opens Lumberyard Setup Assistant, where you can customize your build options\.
   + **B** – **Welcome** messages – Displays the latest news about Lumberyard and its partners\.
   + **C** – **Documentation and Tutorials** – Opens the Lumberyard support page where you can find other tutorials and documentation about Lumberyard\.
   + **D** – **Welcome** screen options – Select check boxes to **Auto\-load last opened level on startup** or **Skip this dialog on startup**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/understanding-welcome.png)

1. Click **Open level**\.

   Navigate to `Levels/GettingStartedGuide`\. 

   Choose `GSG_01_Orientation` and then click **Open**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/understanding-open.png)

   The orientation level opens\. It looks similar to the following image\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/understanding-orientation.png)

1. \(Optional\) To explore the level and play the game, press **Ctrl\+G**\.

   Use standard PC game controls – W, A, S, D, space to jump, left click to shoot\.

   Try to complete all of the following:
   + Approach the entry door to trigger it to open\. The timer starts when you enter the maze\.
   + Shoot to kill enemy AI sentries\.
   + Find and collect the pickup item, a glowing orb\. This triggers the opening of the exit door\.
   + Shoot at and knock over the wall built from crates\.
   + Exit the maze\. The timer stops, and a "Mission Complete" screen appears\.
   + Explore the level\. Have fun\!

   Press **Esc** to quit\.

[Next: Identifying the Basic Tools](understanding-identifying.md)
