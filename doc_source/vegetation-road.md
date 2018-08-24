# Drawing a Road<a name="vegetation-road"></a>

You use Lumberyard's **Road** tool in the **Rollup Bar** to create a worn\-looking footpath that leads to the maze entrance and away from the maze exit\.

You first draw out the meandering line of the road and adjust it to give some variation in the road's height\. You then use the **Material Editor** to assign to the road a dirt texture\. To make the surrounding landscape slope up to the height variations of the road, you use a height aligning tool\. For the final touch, you use the terrain texture layers that you set up previously to add some dirt and rocks to the path's borders\.

**To create a path using the road tool**

1. If the **Rollup Bar** is not already open, open it from the main menu by choosing **Tools**, **RollupBar \(LEGACY\)**\.

1. On the **Objects** tab, click **Misc**, and then click **Road** to open the road tool\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-road-rollupbar.png)

1. The **Road** tool is a simple spline\-based tool that draws a decal texture along the terrain\.

   Click just outside the entrance to the maze to start your road\. Move your mouse pointer a small distance away and click again\. Repeat\.

   Notice how the shape of the path changes depending on where you place subsequent points\. Experiment with the different ways of changing the shape of the path\. If you need to expose more of your landscape while creating the path, you can use the typical navigational controls to change your view without breaking the path\.

   To stop or end the path, double\-click on the last spline point\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-road-splines.png)

1. The road's default texture displays **Replace Me**\. To replace the texture, first make sure that the road is still selected\.

   Open the **Material Editor** by pressing **M**\.

   In the left pane, navigate to `StarterGame\Materials\Natural\Road`\.

   Select `am_road_dust_rocks.mtl`\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-road-material.png)

1. Click the **Assign Item to Selected Objects** icon in the **Material Editor**'s toolbar\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-road-assign.png)

   Close the **Material Editor**\. In the viewport, you see that the road's **Replace Me** texture has been replaced with the dirt and rocks texture that you just assigned\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-road-dirt.png)

1. Using the same steps, create another road leading away from the maze's exit\. Replace the default texture with the dirt and rocks texture\.

You can edit your path by moving any of the points\. You create some up and down variations in the road you've drawn, and then align the height of the terrain to gradually slope up or down to that point on the path\.

**To edit the road and align height**

1. In the viewport, make sure that one of your roads is selected\.

   In the road tool, under **Spline Parameters**, click **Edit**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-road-edit.png)

   The spline points appear as movable points along the path\. Use the **Move** tool to adjust the points\. Make some points lower than the terrain and other points higher\.
**Tip**  
If you click **Edit** and the movable points are not displayed, turn on your helpers\. To do so, click the question mark icon at the upper right corner of your viewport\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-road-helper.png)

1. To make the height of the terrain slope up or down to the points on your road that do not sit at the same level, click **Align Height Map**\. You may have to scroll down in the road tool, as this command is located near the bottom of the tool, under **Road Parameters**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-road-height.png)

1. Use the **Layer Painter** tools to paint some dirt and rocks textures onto the borders of the path\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-paint-terrain.png)

   The path should look similar to the following image\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/vegetation-road-final.png)

[Next: Placing Trees](vegetation-trees.md)