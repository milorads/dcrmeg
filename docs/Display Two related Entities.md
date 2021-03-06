## Display Two related Entities

**Create a new "D CRM EG Configuration"**

**Select an entity to display the grid on. Example Case**

![](Display Two related Entities_config1copy.png)

**Select and two entites to the list of entities to be displayed. Example Account and Contact**

![](Display Two related Entities_config2copy.png)

![](Display Two related Entities_config10copy.png)

**Drag Contact entity and drop it on the Account entity**

**If the drag entity (Contact) has many to one relationship with the dropped entity (Account), you will have the option to display related Contacts or all Contacts.**

![](Display Two related Entities_config12copy.png)

**Select fields for Account and Contact**

![](Display Two related Entities_configuration.PNG)

**Save and close the new configuration**


## Setting up the web resource

**Open any "Case" record. Find and click "Form Editor" menu item.**

![](Display Two related Entities_case1copy.PNG)

**In the form editor, add a new "One Column Tab" to the form.**

![](Display Two related Entities_case2copy.PNG)

**Open up the new tab's properties (DbClick or use properties tool-bar button). Uncheck "Show the label for this tab on the form" check box. Click OK button.**

![](Display Two related Entities_case3copy.PNG)

**Add a new web resource to the tab.**

![](Display Two related Entities_case4copy.PNG)

**For the web resource, enter "dcrmeg_dcrmeghtml". Enter a name for the web resource.**

![](Display Two related Entities_case5copy.PNG)

**Click on the "Formatting" tab of the new Add Web Resource window.**

![](Display Two related Entities_case7copy.PNG)

**Set the "Number of rows" to 20. Uncheck "Display border". Click OK.**

![](Display Two related Entities_case8copy.PNG)

**Save and publish the changes to the case form.**

**Refresh the case record. You should see a grid displaying selected fields from the "Account" entity. Clicking the "+" sign in each grid row will display related contacts.**

