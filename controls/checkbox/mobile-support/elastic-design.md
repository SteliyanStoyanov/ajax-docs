---
title: Elastic Design
page_title: Elastic Design | RadCheckBox for ASP.NET AJAX Documentation
description: Elastic Design
slug: checkbox/mobile-support/elastic-design
tags: elastic,design
published: True
position: 1
---

# Elastic Design

This article explains the **elastic design capabilities RadCheckBox offers**. **Example 1** shows the basic approach to scale the control by only changing its default font size.

Generally, responsive design means that the page and its content are able to adapt to different screen resolutions without deteriorating the user experience. This often includes changing the font size and having [dimensions set in percent]({%slug checkbox/mobile-support/fluid-design%}).

>caption Figure 1: Comparison between appearance of a RadCheckBox with regular font size and with increased font size.

![checkbox-elastic-design](images/checkbox-elastic-design.png)

>caption Example 1: Shows how to increase the font size of a RadCheckBox in Figure 1.

````CSS
<style type="text/css">
	button.RadButton {
		font-size: 26px;
	}
</style>
````

````ASP.NET
<telerik:RadCheckBox runat="server" ID="RadCheckBox1" Text="Elastic Toggle Button">
	<ToggleStates>
		<telerik:ButtonToggleState Text="State 1"/>
		<telerik:ButtonToggleState Text="State 2" /> 
	</ToggleStates>
</telerik:RadCheckBox>
````

## See Also

 * [Mobile Support Overview]({%slug checkbox/mobile-support/overview%})

 * [Render Modes]({%slug checkbox/mobile-support/render-modes%})

 * [Fluid Design]({%slug checkbox/mobile-support/fluid-design%})

