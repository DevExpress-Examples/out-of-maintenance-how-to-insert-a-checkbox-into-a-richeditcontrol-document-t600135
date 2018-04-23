# How to insert a CheckBox into a RichEditControl document


<p>This example demonstrates how to imitate a CheckBox control in a document by inserting Unicode characters and allow changing the CheckBox state on a mouse click.</p>
<p>Use the <a href="https://documentation.devexpress.com/#corelibraries/DevExpressXtraRichEditHitTestManagerMembersTopicAll">HitTestManager.HitTest</a> method to get the <a href="https://documentation.devexpress.com/#CoreLibraries/clsDevExpressXtraRichEditRichEditHitTestResulttopic">RichEditHitTestResult</a> object providing information about a specific document element which is located under the mouse cursor. Retrieve the layout element using the <a href="https://documentation.devexpress.com/#CoreLibraries/DevExpressXtraRichEditRichEditHitTestResult_LayoutElementtopic">RichEditHitTestResult.LayoutElement</a> property, check whether this element is a CheckBox character, and change its checked state by replacing the clicked character with another one.</p>

<br/>


