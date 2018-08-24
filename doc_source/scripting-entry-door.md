# Adding the Entry Door<a name="scripting-entry-door"></a>


****  

|  | 
| --- |
| This topic references tools and features that are [legacy](http://docs.aws.amazon.com/lumberyard/latest/userguide/ly-glos-chap.html#legacy)\. If you want to use legacy tools in Lumberyard Editor, disable the [CryEntity Removal gem](http://docs.aws.amazon.com/lumberyard/latest/userguide/gems-system-cryentity-removal-gem.html) using the [Project Configurator](http://docs.aws.amazon.com/lumberyard/latest/userguide/configurator-intro.html) or the [command line](http://docs.aws.amazon.com/lumberyard/latest/userguide/lmbr-exe.html)\. To learn more about legacy features, see the [Amazon Lumberyard Legacy Reference](http://docs.aws.amazon.com/lumberyard/latest/legacyreference/)\. | 

In this tutorial, you'll create an entry door and add components that make it act solid and open upon approach\.

To set up your entry door, you do the following:

1. [Place the door entity](scripting-entry-door-entity.md)\.

1. [Add the physics and collider components to the door](scripting-entry-door-components.md)\.

1. [Create a trigger volume](scripting-entry-door-trigger.md)\.

1. [Add scripts to the entry door entity to do the following](scripting-entry-door-scripts.md):
   + Trigger an event upon exit and another event upon entry\.
   + Change the position of an object and link it as the entry event\.
   + Change the position of an object and link it as the exit event\.

1. [Define the door as the target object for the Lua scripts](scripting-entry-door-connect.md)\.

1. [Add realism by connecting sounds to the door's opening and closing events](scripting-entry-door-sounds.md)\.

Next: [Placing the Door Entity](scripting-entry-door-entity.md)