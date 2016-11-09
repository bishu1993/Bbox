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

<table class="tables">
                            <thead>
                                <tr>
                                    <th>#</th>
                                    <th>Key</th>
                                    <th>Default Value</th>
                                    <th>Description</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>1</td>
                                    <td>title</td>
                                    <td>Null</td>
                                    <td>This is used to define Title Bar Value</td>
                                </tr>
                                <tr>
                                    <td>2</td>
                                    <td>content</td>
                                    <td>Null</td>
                                    <td>This is used to define Content Part of the Bbox.</td>
                                </tr>
                                <tr>
                                    <td>3</td>
                                    <td>maxWidth</td>
                                    <td>600</td>
                                    <td>This is used to define maximum width of Bbox.</td>
                                </tr>
                                <tr>
                                    <td>4</td>
                                    <td>minWidth</td>
                                    <td>280</td>
                                    <td>This is used to define minimum width of Bbox.</td>
                                </tr>
                                <tr>
                                    <td>5</td>
                                    <td>autoOpen</td>
                                    <td>false</td>
                                    <td>This is used to open the specified Bbox automatically when function initilize.</td>
                                </tr>
                                <tr>
                                    <td>6</td>
                                    <td>sticky</td>
                                    <td>false</td>
                                    <td>This is used to create a sticky Bbox.</td>
                                </tr>
                                <tr>
                                    <td>7</td>
                                    <td>className</td>
                                    <td>fade-and-drop</td>
                                    <td>This is used to define animation type.
                                        Some pri-defined animation are 
                                        <ul type="a" style="margin-left:35px;font-weight:bold;">
                                            <li>
                                                fade-and-drop
                                            </li>
                                            <li>
                                                zoom
                                            </li>
                                            <li>
                                                zoom-and-spin
                                            </li>
                                        </ul>
                                    </td>
                                </tr>
                                <tr>
                                    <td>8</td>
                                    <td>closeButton</td>
                                    <td>True</td>
                                    <td>This create a close button on the top-right corner of the Bbox</td>
                                </tr>
                                <tr>
                                    <td>9</td>
                                    <td>closeButtonIcon</td>
                                    <td>Null</td>
                                    <td>This key is used to define the path of the close button's icon.</td>
                                </tr>
                                <tr>
                                    <td>10</td>
                                    <td>closeIconInnerColor</td>
                                    <td>Null</td>
                                    <td>This is used to fill the inner cross Icon.</td>
                                </tr>
                                <tr>
                                    <td>11</td>
                                    <td>closeIconOuterColor</td>
                                    <td>Null</td>
                                    <td>This is used to fill the Outer part of the Icon.</td>
                                </tr>
                                <tr>
                                    <td>12</td>
                                    <td>hideOnOverlayClick</td>
                                    <td>false</td>
                                    <td>When this is true, it close the Bbox when someone click on the overlay.</td>
                                </tr>
                                <tr>
                                    <td>13</td>
                                    <td>overlay</td>
                                    <td>True</td>
                                    <td>It generate a overlay in the backside of the Bbox.</td>
                                </tr>
                                <tr>
                                    <td>14</td>
                                    <td>overlayColor</td>
                                    <td>#000000</td>
                                    <td>It is used to define the Background Color of the overlay.</td>

                                </tr>
                                <tr>
                                    <td>15</td>
                                    <td>overlayOpacity</td>
                                    <td>0.5</td>
                                    <td>This is used to define the trancparency label of the Overlay</td>
                                </tr>
                                <tr>
                                    <td>16</td>
                                    <td>bgColor</td>
                                    <td>#FFFFFF</td>
                                    <td>This is used to  define the background colorur of the Bbox Modal.</td>
                                </tr>
                                <tr>
                                    <td>17</td>
                                    <td>scroll</td>
                                    <td>false</td>
                                    <td>This is used to set the scroll option for the Bbox Modal.</td>
                                </tr>
                                <tr>
                                    <td>18</td>
                                    <td>url</td>
                                    <td>Null</td>
                                    <td>If the path will be given it iniciate a XMLHttpRequest to the given path and load content dinamically from the server side.</td>
                                </tr>
                                <tr>
                                    <td>19</td>
                                    <td>urlParms</td>
                                    <td>Null</td>
                                    <td>It is used to send parameter to the server side with XMLHttpRequest</td>
                                </tr>
                            </tbody>
                        </table>
