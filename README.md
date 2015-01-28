# 'Loop' for CodeRush #
Provides a TextCommand (Loop) which expands a template multiple times. This plugin was initially created in response to a customer suggestion and was
[blogged about by Mark Miller here](http://community.devexpress.com/blogs/markmiller/archive/2011/01/06/wpf-amp-silverlight-grids-faster-creation-using-coderush-templates-and-a-custom-plug-in.aspx)

### Usage ###
Use the following syntax in Templates and other places where TextCommands are appropriate

    «Loop(!TemplateName,Count,Offset)»

Reference iteration value from within a template using the **«?!LoopIterationValue»** StringProvider

 * **TemplateName**: Name of template to repeat.
 * **Count**: Number of iterations.
 * **Offset**: Numeric value to add to **«?!LoopIterationValue»** before returning it.
