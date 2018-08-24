# Adding a Pickup Item<a name="scripting-pickup"></a>


****  

|  | 
| --- |
| This topic references tools and features that are [legacy](http://docs.aws.amazon.com/lumberyard/latest/userguide/ly-glos-chap.html#legacy)\. If you want to use legacy tools in Lumberyard Editor, disable the [CryEntity Removal gem](http://docs.aws.amazon.com/lumberyard/latest/userguide/gems-system-cryentity-removal-gem.html) using the [Project Configurator](http://docs.aws.amazon.com/lumberyard/latest/userguide/configurator-intro.html) or the [command line](http://docs.aws.amazon.com/lumberyard/latest/userguide/lmbr-exe.html)\. To learn more about legacy features, see the [Amazon Lumberyard Legacy Reference](http://docs.aws.amazon.com/lumberyard/latest/legacyreference/)\. | 

Now you add an item in the maze that the player must pick up before exiting the maze\. The pickup item is a prebuilt slice that you access through the **Asset Browser**\. After you place the pickup item slice, you customize the **Lua Script** component\.

**To place a pickup item**

1.  In the **Asset Browser**, navigate to `StarterGame\Slices\GSG`\. 

   Select `maze_pickupobjective.slice` and drag it into your viewport, into the far corner of the maze\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/scripting-pickup-slice.png)

1. The `maze_pickupobjective.slice` has a number of components and several entities\. You modify the properties on one of these components\.

   In the **Entity Outliner**, select the **Maze\_PickupObjective** slice\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/scripting-pickup-select.png)

1. In the **Entity Inspector**, in the bottommost **Lua Script** component, under **Recipients**, next to **Entity**, click the picker ![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/picker.png)\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/scripting-pickup-editlua.png)

1.  In the **Entity Outliner**, under **ExitDoor\_Parent**, select **Exitdoor\_Script**\.   
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/scripting-pickup-modifylua.png)

   You now have a pickup that, when retrieved, allows the player to exit the maze\.

1. Press **Ctrl\+S** to save your level\.

[Next: Adding a Timer](scripting-timer-add.md)