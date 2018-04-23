# How to get invisible / collapsed selected nodes' keys in virtual mode


<p>This example illustrates how to manually get invisible / collapsed selected nodes' keys when ASPxTreeList operates in  virtual mode.</p><p>It is then possible to get these keys on the server side for further processing.</p><br />
<p>Selected nodes have two states: visible and invisible (if a parent node is collapsed).</p><p>These states are saved as string arrays within the ASPxHiddenField.</p><p>Then, these arrays are synchronized on the client side in the EndCallback event.<br />
</p>


<h3>Description</h3>

<p><br />
</p>

<br/>

