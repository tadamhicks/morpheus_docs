Workflows
---------

Add Workflow
^^^^^^^^^^^^

To Add Workflows:

#. Select the Provisioning link in the navigation bar.
#. Select Automation from the sub-navigation menu.
#. Click the Workflows tab to show the Workflows tab panel.
#. Click the `Add Workflow` button.
#. From the New Workflow Wizard input a name for the workflow.
#. Optionally input a description.
#. Expand the execution phases to add tasks to, and type the name of a created task and click the task when it appears to add.
#. If multiple tasks are added to the same execution phase, their execution order can be changed by selecting the grip icon and dragging the task to the desired execution order.
#. For multi-tenant environments, select Public or Private visibility for the Workflow.
#. Click the Save Changes button to save.

Workflow Execution Phases
^^^^^^^^^^^^^^^^^^^^^^^^^

For VM’s, Pre-Provision and Provision execute after the VM is running. Pre-Provision can be used for a template so it is added before a script set at the Provision phase executes. Pre-Provision for scripts is mainly for Docker as you can execute on the host before the container is up. Post-Provision will execute after the entire provisioning process is complete.


Edit Workflow
^^^^^^^^^^^^^

To Edit Workflows:

#. Select the Provisioning link in the navigation bar.
#. Select Automation from the sub-navigation menu.
#. Click the Workflows tab to show the workflows tab panel.
#. Click the Edit icon on the row of the workflow you wish to edit.
#. Modify information as needed.
#. Click the Save Changes button to save.

Delete Workflow
^^^^^^^^^^^^^^^

To Delete Workflows:

#. Select the Provisioning link in the navigation bar.
#. Select Automation from the sub-navigation menu.
#. Click the Workflows tab to show the workflows tab panel.
#. Click the Delete icon on the row of the workflow you wish to delete.