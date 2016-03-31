---
layout: page
title: max_colH_correction
parent_title: mPDF Variables
permalink: /reference/mpdf-variables/max-colh-correction.html
---

<div id="bpmbook" class="bpmbook" style="direction:ltr;">
<div class="topic_user_field">
<div id="U0">
<p>(mPDF &gt;= 1.0)</p>
<p>max_colH_correction – Sets maximum ratio to allow when adjusting column heights</p>
<h2>Description</h2>

<div class="alert alert-info" role="alert"><b>max_colH_correction</b> ( <i>1.15</i> | float )</div>
<p>The maximum ratio to adjust column height when justifying - too large a value can give ugly results</p>

<div class="alert alert-info" role="alert"><b>Note:</b> The <span class="parameter">vAlign</span> parameter of &lt;<a href="{{ "/reference/html-control-tags/columnbreak.html" | prepend: site.baseurl }}">columnbreak</a>&gt; or <a href="{{ "/reference/mpdf-functions/setcolumns.html" | prepend: site.baseurl }}">SetColumns()</a> must be set to J or justify</div>
<h2>Values</h2>
<table class="bpmTopic"> <thead>
<tr>
<td>value</td>
<td>description</td>
</tr>
</thead> <tbody>
<tr>
<td>default

</td>
<td>1.15 

</td>
</tr>
<tr>
<td>range</td>
<td>Values above 1.0 

</td>
</tr>
</tbody> </table>
<p>Examples</p>

{% highlight php %}
Example #1
{% endhighlight %}

{% highlight php %}
<?php

<?php

$mpdf=new mPDF();

$mpdf->max_colH_correction = 1.3;

?>
{% endhighlight %}

<p>&nbsp;</p>
</div>
</div>
