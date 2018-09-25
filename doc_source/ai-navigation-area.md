# Defining the AI Navigation Area<a name="ai-navigation-area"></a>


****  

|  | 
| --- |
| This topic references tools and features that are [legacy](https://docs.aws.amazon.com/lumberyard/latest/userguide/ly-glos-chap.html#legacy)\. If you want to use legacy tools in Lumberyard Editor, disable the [CryEntity Removal gem](https://docs.aws.amazon.com/lumberyard/latest/userguide/gems-system-cryentity-removal-gem.html) using the [Project Configurator](https://docs.aws.amazon.com/lumberyard/latest/userguide/configurator-intro.html) or the [command line](https://docs.aws.amazon.com/lumberyard/latest/userguide/lmbr-exe.html)\. To learn more about legacy features, see the [Amazon Lumberyard Legacy Reference](https://docs.aws.amazon.com/lumberyard/latest/legacyreference/)\. | 

The AI navigation area is the traversable area for the AI characters\.

In this tutorial you use a legacy feature called **Rollup Bar** to define the AI navigation area\.

**To define the AI navigation area**

1. Open the **Rollup Bar** by clicking **Tools**, **RollupBar \(LEGACY\)**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/ai-navigation-area-menu.png)

1. Under **Objects**, click **AI**\.

   Under **Object Type**, click **NavigationArea**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/ai-navigation-area-object.png)

1. The **Navigation Area** tool is a point\-and\-click shape builder\. You'll create a box that is within the **AiTrigger** volume that you created earlier in this tutorial\.

   To create the box, click one corner inside the maze walls and then work your way around to the other corners\. On the fourth corner, double\-click to exit the tool and close the area that you defined\.
**Tip**  
If the tool restricts you from moving in certain directions, ensure that no directional restrictions are selected in your toolbar\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/ai-navigation-area-dimension.png)
**Tip**  
If you cannot see the outline of the navmesh as you click, you likely have helpers turned off\. Turn on helpers ![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/helper.png) in the top toolbar to view the navmesh outline\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/placing-character-controller-toggle.png)  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/ai-navigation-area-animated.gif)

1. Adjust the **Z** value of the AI navigation area to ensure that it fully intersects with the ground\.

   To do this, select the **Move** tool and then at the bottom of the Perspective Viewport, for the **Z** value, enter `4.9`\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/ai-navigation-area-height.png)

1. Press **Ctrl\+S** to save your level\.

[Next: Creating AI Spawn Points](ai-spawn-points.md)