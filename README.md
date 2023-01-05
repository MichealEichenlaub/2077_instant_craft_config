# 2077_instant_craft_config

<pre>
  -Updated contexts file for cyberpunk 2077. This updated config makes it so that item crafting
   and dissassembling items is instant.
  
  -To update this file, you can search for something you want to edit and change it in the file. 
  
   We wil go over an example for changing the speed of upgrading attributes. 
      
  -Open your "inputContexts.xml"  located in cyberpunk 2077 \ r6 \ config
  -Use ctrl+f to open the find menu
  -type "upgrade_attribute" and navigate to the section of the XML labeled "hold actions"
  
  -you should see      " hold action="upgrade_attribute"			timeout="0.4" "
  
  -the "timeout" variable controls the speed at which the action takes place. 
  
  -if we change this hold action to  " hold action="upgrade_attribute"			timeout="0.01" "
  
   we reduce the amount of time it takes for the action to be completed. This will make upgrading
   an attribute practically instant. This can be applied to any other action in this file such as
   crafting speed, vehicle horn, etc. 
</pre>
