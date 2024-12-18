<!--TITLE: Set List Index Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


List Commands &gt; Other &gt; Set List Index


# Set List Index Command


## What does this command do?
This command allows you to modify List Index.


## When would I want to use this command?
Use this command when you want to modify List Index.  You can even use variables to modify other variables.


<a id="param_list"></a>
## Command Parameters
- [Please Select the List Variable Name](#param_0)
- [Please Specify the Index of the List](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select the List Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the List Variable Name</dd>
<dt>Value</dt><dd>List Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command And also The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vList</strong> or <strong>{vList}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vList</strong> | Specify Variable Name **vList** |
| <strong>{vList}</strong> | Specify Variable Name **vList** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Index of the List


<dl>
<dt>What to input</dt><dd>Enter or Select the Index of the List</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>-1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd><strong>-1</strong> means index of the last row. If it is empty, it will be the value of Current Position, which can be used for Loop List command.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Get First List Item |
| <strong>-1</strong> | Get Last List Item |
| <strong>{vIndex}</strong> | Specify Value of Variable **vIndex** for Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: SetListIndexCommand
Parent Namespace: neobots.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/neobots/issues/new)
- [Ask a question on Gitter](https://gitter.im/neobots-rpa/Lobby)
