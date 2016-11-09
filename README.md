# Bbox
Bbox Modal Box Plugin


###installation###
in a html file

<pre>
&lt;script type='text/javascript' src='path/Bbox.min.js'>&lt;/script>
&lt;link rel="stylesheet" href='path/Bbox.min.css'>
</pre>

###with nodejs###
<pre><code class="highlight language-javascript">//npm install -g Bbox
var Bbox = require('Bbox');</code></pre>
                    
###Basic Usage###
<pre><code class="highlight language-javascript">//Setting up a Bbox Module
Bbox("Your Selector").open({ //Options Goes Here });
</code></pre>

######or initialise the container with values######
<pre><code class="highlight language-javascript">Bbox("Your Selector").open({
    title:'My First Modal',
    className: 'zoom-and-spin',
    closeButton: true,
    hideOnOverlayClick: true,
    overlayOpacity: '.8',
    overlayColor: 'lightgreen',
    size: 'medium'
});
</code></pre>


### API and Options of Bbox ###

