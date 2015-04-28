Easy to use calculator for converting units from/to the metric/imperial systems.

Originally developped by Cyril Andreattta

Improved by Justin MASSIOT

<br />

# How to use it #

  1. Enter a numeric value including its unit [in, mil, mm, um], e.g. 3.1415 mm
  1. Check the "copy to clipboard" checkbox if you want to directly paste the result somewhere.
  1. Press enter or click the small 'Convert' button.

<img src='http://altium-designer-addons.googlecode.com/svn/trunk/mil-mm-conv/mil-mm-conv.png' align='middle'>

<br />

<h1>Cool features</h1>

<ul><li>Converted values will be shown in all 4 units (inch support added by version 2.0).<br>
</li><li>Spaces between number and unit are ignored.<br>
</li><li>'.' and ',' are accepted as decimal separator.<br>
</li><li>If unit is missing, last unit is used. This makes it easy to calculate multiple values.<br>
And more with version 2.0:<br>
</li><li>The 'inch' unit is supported.<br>
</li><li>The result can be automatically copied to the Windows clipboard, in order to paste it wherever you want.<br>
</li><li>The input value is shown with a foreground color, and the copied value with a background color.<br>
</li><li>The converter is fully customizable for your own needs, see <a href='mil_mm_conv#Customizing_the_converter.md'>the dedicated section</a>.</li></ul>

<br />

<h1>Download it</h1>

<b><a href='https://drive.google.com/file/d/0B71DP3351mA0Vzd2WExhTjlseUk/edit?usp=sharing'>Download the converter script</a></b>

<br />

<h1>Customizing the converter</h1>

Inside the file mil-mm-conv.pas you will find a series of constants that you can modify to fit your needs:<br>
<ul><li>floatformat: defines the format of the decimal results; default is '0.####' (round to the fourth decimal, no trailing zeros but with a leading zero before the separator), leave this empty if you do not want to round the results<br>
</li><li>copybydefault: choose to copy the result to clipboard by default at startup; default is 'true' = copy by default<br>
</li><li>copymetric: choose the result to copy to clipboard after a conversion from imperial to metric; could be 'mm' or 'um', default is 'mm'<br>
</li><li>copyimperial: choose the result to copy to clipboard after a conversion from metric to imperial; could be 'mil' or 'in', default is 'mil'<br>
</li><li>copywithunit: choose to copy the raw value, or the value followed by the unit; default is 'false' = no unit<br>
</li><li>inputcolor: define the font color of the value which is the input<br>
</li><li>copycolor: define the background color of the result which has been copied to the clipboard; default is clSkyBlue, other proposals are clActiveCaption, clHighlight</li></ul>

<pre><code>const<br>
    floatformat = '0.####'; // configuration: define the format of the decimal results; default is '0.####' (round to the fourth decimal, no trailing zeros but with a leading zero before the separator), leave this empty if you do not ant to round the results<br>
    copybydefault = true; // configuration: choose to copy the result to clipboard by default at startup; default is 'true' = copy by default<br>
    copymetric = 'mm'; // configuration: choose the result to copy to clipboard after a conversion from imperial to metric; could be 'mm' or 'um', default is 'mm'<br>
    copyimperial = 'mil'; // configuration: choose the result to copy to clipboard after a conversion from metric to imperial; could be 'mil' or 'in', default is 'mil'<br>
    copywithunit = true; // configuration: choose to copy the raw value, or the value followed by the unit; default is 'false' = no unit<br>
    inputcolor = clBlue; // configuration: define the font color of the value which is the input<br>
    copycolor = clSkyBlue; // configuration: define the background color of the result which has been copied to the clipboard; default is clSkyBlue, other proposals are clActiveCaption, clHighlight<br>
</code></pre>