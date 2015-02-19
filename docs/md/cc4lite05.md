






##
##
### Spatial scale: precipitation

Now repeat the previous comparisons for precipitation.
Only the latter two plots using floating range bars are shown.
Due to the heteroskadasticity in the precipitation variable, the patterns of change in mean and variability between scales are similar.

#### Mean precipitation: 2-km resolution

<iframe srcdoc=' &lt;!doctype HTML&gt;
&lt;meta charset = &#039;utf-8&#039;&gt;
&lt;html&gt;
  &lt;head&gt;
    
    &lt;script src=&#039;//code.jquery.com/jquery-1.9.1.min.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/highcharts.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/highcharts-more.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/modules/exporting.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    
    &lt;style&gt;
    .rChart {
      display: block;
      margin-left: auto; 
      margin-right: auto;
      width: 800px;
      height: 400px;
    }  
    &lt;/style&gt;
    
  &lt;/head&gt;
  &lt;body &gt;
    
    &lt;div id = &#039;chart1be04617637c&#039; class = &#039;rChart highcharts&#039;&gt;&lt;/div&gt;    
    &lt;script type=&#039;text/javascript&#039;&gt;
    (function($){
        $(function () {
            var chart = new Highcharts.Chart({
 &quot;dom&quot;: &quot;chart1be04617637c&quot;,
&quot;width&quot;:            800,
&quot;height&quot;:            400,
&quot;credits&quot;: {
 &quot;href&quot;: null,
&quot;text&quot;: null 
},
&quot;exporting&quot;: {
 &quot;enabled&quot;: false 
},
&quot;title&quot;: {
 &quot;text&quot;: &quot;Average Monthly Precipitation for Fairbanks, Alaska&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;#000000&quot; 
} 
},
&quot;yAxis&quot;: [
 {
 &quot;title&quot;: {
 &quot;text&quot;: &quot;Precipitation (mm)&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
} 
} 
],
&quot;subtitle&quot;: {
 &quot;text&quot;: &quot;Historical CRU 3.1 and 5-Model Projected Average, Mid-Range Emissions (RCP 6.0)&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
},
&quot;legend&quot;: {
 &quot;verticalAlign&quot;: &quot;top&quot;,
&quot;y&quot;:             50,
&quot;borderWidth&quot;:              1,
&quot;borderColor&quot;: &quot;gray&quot;,
&quot;borderRadius&quot;:              5,
&quot;itemMarginBottom&quot;:             -5,
&quot;itemMarginBottom&quot;:             -5,
&quot;itemStyle&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
},
&quot;xAxis&quot;: [
 {
 &quot;categories&quot;: [ &quot;Jan&quot;, &quot;Feb&quot;, &quot;Mar&quot;, &quot;Apr&quot;, &quot;May&quot;, &quot;Jun&quot;, &quot;Jul&quot;, &quot;Aug&quot;, &quot;Sep&quot;, &quot;Oct&quot;, &quot;Nov&quot;, &quot;Dec&quot; ],
&quot;title&quot;: {
 &quot;text&quot;: &quot;Due to variability among climate models and among years in a natural climate system, these graphs are useful for examining trends over time, rather than for precisely&lt;br&gt;predicting monthly or yearly values. For more information on derivation, reliability, and variability among these projections, please visit www.snap.uaf.edu.&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot;,
&quot;fontWeight&quot;: &quot;normal&quot;,
&quot;fontSize&quot;: &quot;8px&quot; 
} 
} 
} 
],
&quot;series&quot;: [
 {
 &quot;data&quot;: [
 [
              0,
            46 
],
[
              2,
            29 
],
[
              0,
            29 
],
[
              0,
            17 
],
[
              2,
            46 
],
[
             11,
            71 
],
[
             18,
           109 
],
[
             15,
           132 
],
[
              3,
            63 
],
[
              3,
            56 
],
[
              3,
            40 
],
[
              0,
            44 
] 
],
&quot;name&quot;: &quot;1960-1989&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
              5,
            37 
],
[
              3,
            36 
],
[
              4,
            28 
],
[
              1,
            22 
],
[
              3,
            43 
],
[
             12,
            87 
],
[
             18,
           128 
],
[
             15,
           102 
],
[
              3,
            84 
],
[
              9,
            56 
],
[
              6,
            44 
],
[
              6,
            49 
] 
],
&quot;name&quot;: &quot;2010-2019&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
              3,
            57 
],
[
              4,
            43 
],
[
              4,
            30 
],
[
              2,
            18 
],
[
              5,
            49 
],
[
             15,
            82 
],
[
             26,
           100 
],
[
             22,
           123 
],
[
             11,
            56 
],
[
             11,
            60 
],
[
              7,
            54 
],
[
              6,
            51 
] 
],
&quot;name&quot;: &quot;2040-2049&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
              6,
            52 
],
[
              3,
            31 
],
[
              2,
            26 
],
[
              2,
            18 
],
[
              7,
            70 
],
[
             12,
           110 
],
[
             18,
           146 
],
[
             10,
           112 
],
[
              8,
            83 
],
[
              9,
            71 
],
[
              9,
            43 
],
[
              8,
            51 
] 
],
&quot;name&quot;: &quot;2060-2069&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
              3,
            41 
],
[
              3,
            46 
],
[
              4,
            21 
],
[
              2,
            24 
],
[
              8,
            52 
],
[
              6,
           113 
],
[
             25,
           117 
],
[
             18,
           134 
],
[
             12,
            70 
],
[
             12,
            74 
],
[
              9,
            52 
],
[
              7,
            49 
] 
],
&quot;name&quot;: &quot;2090-2099&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
} 
],
&quot;chart&quot;: {
 &quot;width&quot;:            800,
&quot;height&quot;:            500,
&quot;renderTo&quot;: &quot;chart1be04617637c&quot; 
},
&quot;id&quot;: &quot;chart1be04617637c&quot; 
});
        });
    })(jQuery);
&lt;/script&gt;
    
    &lt;script&gt;&lt;/script&gt;    
  &lt;/body&gt;
&lt;/html&gt; ' scrolling='no' frameBorder='0' seamless class='rChart  highcharts  ' id='iframe-chart1be04617637c'> </iframe>
 <style>iframe.rChart{ width: 100%; height: 400px;}</style>

#### Mean precipitation: 10-minute resolution

<iframe srcdoc=' &lt;!doctype HTML&gt;
&lt;meta charset = &#039;utf-8&#039;&gt;
&lt;html&gt;
  &lt;head&gt;
    
    &lt;script src=&#039;//code.jquery.com/jquery-1.9.1.min.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/highcharts.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/highcharts-more.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/modules/exporting.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    
    &lt;style&gt;
    .rChart {
      display: block;
      margin-left: auto; 
      margin-right: auto;
      width: 800px;
      height: 400px;
    }  
    &lt;/style&gt;
    
  &lt;/head&gt;
  &lt;body &gt;
    
    &lt;div id = &#039;chart1be044eb25ab&#039; class = &#039;rChart highcharts&#039;&gt;&lt;/div&gt;    
    &lt;script type=&#039;text/javascript&#039;&gt;
    (function($){
        $(function () {
            var chart = new Highcharts.Chart({
 &quot;dom&quot;: &quot;chart1be044eb25ab&quot;,
&quot;width&quot;:            800,
&quot;height&quot;:            400,
&quot;credits&quot;: {
 &quot;href&quot;: null,
&quot;text&quot;: null 
},
&quot;exporting&quot;: {
 &quot;enabled&quot;: false 
},
&quot;title&quot;: {
 &quot;text&quot;: &quot;Average Monthly Precipitation for Fairbanks, Alaska&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;#000000&quot; 
} 
},
&quot;yAxis&quot;: [
 {
 &quot;title&quot;: {
 &quot;text&quot;: &quot;Precipitation (mm)&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
} 
} 
],
&quot;subtitle&quot;: {
 &quot;text&quot;: &quot;Historical CRU 3.1 and 5-Model Projected Average, Mid-Range Emissions (RCP 6.0)&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
},
&quot;legend&quot;: {
 &quot;verticalAlign&quot;: &quot;top&quot;,
&quot;y&quot;:             50,
&quot;borderWidth&quot;:              1,
&quot;borderColor&quot;: &quot;gray&quot;,
&quot;borderRadius&quot;:              5,
&quot;itemMarginBottom&quot;:             -5,
&quot;itemMarginBottom&quot;:             -5,
&quot;itemStyle&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
},
&quot;xAxis&quot;: [
 {
 &quot;categories&quot;: [ &quot;Jan&quot;, &quot;Feb&quot;, &quot;Mar&quot;, &quot;Apr&quot;, &quot;May&quot;, &quot;Jun&quot;, &quot;Jul&quot;, &quot;Aug&quot;, &quot;Sep&quot;, &quot;Oct&quot;, &quot;Nov&quot;, &quot;Dec&quot; ],
&quot;title&quot;: {
 &quot;text&quot;: &quot;Due to variability among climate models and among years in a natural climate system, these graphs are useful for examining trends over time, rather than for precisely&lt;br&gt;predicting monthly or yearly values. For more information on derivation, reliability, and variability among these projections, please visit www.snap.uaf.edu.&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot;,
&quot;fontWeight&quot;: &quot;normal&quot;,
&quot;fontSize&quot;: &quot;8px&quot; 
} 
} 
} 
],
&quot;series&quot;: [
 {
 &quot;data&quot;: [
 [
             10,
            62 
],
[
              8,
            58 
],
[
              5,
            52 
],
[
              6,
            78 
],
[
              3,
            73 
],
[
             21,
           126 
],
[
             15,
           119 
],
[
             28,
           128 
],
[
             31,
            96 
],
[
             14,
            98 
],
[
             20,
            74 
],
[
              8,
            62 
] 
],
&quot;name&quot;: &quot;1960-1989&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
              6,
            76 
],
[
              8,
            64 
],
[
             11,
            50 
],
[
             11,
            62 
],
[
              9,
            80 
],
[
             10,
           165 
],
[
             15,
           158 
],
[
             25,
           190 
],
[
             27,
           121 
],
[
             14,
           100 
],
[
             17,
            98 
],
[
             15,
            66 
] 
],
&quot;name&quot;: &quot;2010-2019&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
              6,
            77 
],
[
             13,
            53 
],
[
              8,
            50 
],
[
             16,
            71 
],
[
             11,
           101 
],
[
             18,
           135 
],
[
             17,
           130 
],
[
             29,
           163 
],
[
             34,
           124 
],
[
             16,
           123 
],
[
              9,
            82 
],
[
             10,
            76 
] 
],
&quot;name&quot;: &quot;2040-2049&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
              7,
            67 
],
[
             13,
            68 
],
[
             10,
            48 
],
[
              6,
            64 
],
[
             13,
           112 
],
[
             21,
           136 
],
[
             13,
           137 
],
[
             15,
           168 
],
[
             16,
           134 
],
[
             26,
            95 
],
[
             24,
            86 
],
[
             20,
            78 
] 
],
&quot;name&quot;: &quot;2060-2069&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
             11,
            88 
],
[
              8,
            84 
],
[
             10,
            57 
],
[
              7,
            71 
],
[
             10,
           114 
],
[
             27,
           176 
],
[
             28,
           148 
],
[
             42,
           210 
],
[
             30,
           147 
],
[
             22,
           103 
],
[
             14,
           132 
],
[
             22,
            93 
] 
],
&quot;name&quot;: &quot;2090-2099&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
} 
],
&quot;chart&quot;: {
 &quot;width&quot;:            800,
&quot;height&quot;:            500,
&quot;renderTo&quot;: &quot;chart1be044eb25ab&quot; 
},
&quot;id&quot;: &quot;chart1be044eb25ab&quot; 
});
        });
    })(jQuery);
&lt;/script&gt;
    
    &lt;script&gt;&lt;/script&gt;    
  &lt;/body&gt;
&lt;/html&gt; ' scrolling='no' frameBorder='0' seamless class='rChart  highcharts  ' id='iframe-chart1be044eb25ab'> </iframe>
 <style>iframe.rChart{ width: 100%; height: 400px;}</style>

Apparently, Fairbanks is not where the rain and snow are falling.
A comparison of scales reveals that total monthly precipitation averaged across a 10-minute grid cell is substantially greater than that based on the 2-km PRISM climatology.

A quick comparison with a very wet community, Juneau, Alaska, will reveal the exact opposite.
Precipitation is very high there at 2-km resolution, but relatively washed out (no pun intended) at 10-minute resolution.

#### Precipitation range: 2-km resolution

<iframe srcdoc=' &lt;!doctype HTML&gt;
&lt;meta charset = &#039;utf-8&#039;&gt;
&lt;html&gt;
  &lt;head&gt;
    
    &lt;script src=&#039;//code.jquery.com/jquery-1.9.1.min.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/highcharts.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/highcharts-more.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/modules/exporting.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    
    &lt;style&gt;
    .rChart {
      display: block;
      margin-left: auto; 
      margin-right: auto;
      width: 800px;
      height: 400px;
    }  
    &lt;/style&gt;
    
  &lt;/head&gt;
  &lt;body &gt;
    
    &lt;div id = &#039;chart1be0615148a0&#039; class = &#039;rChart highcharts&#039;&gt;&lt;/div&gt;    
    &lt;script type=&#039;text/javascript&#039;&gt;
    (function($){
        $(function () {
            var chart = new Highcharts.Chart({
 &quot;dom&quot;: &quot;chart1be0615148a0&quot;,
&quot;width&quot;:            800,
&quot;height&quot;:            400,
&quot;credits&quot;: {
 &quot;href&quot;: null,
&quot;text&quot;: null 
},
&quot;exporting&quot;: {
 &quot;enabled&quot;: false 
},
&quot;title&quot;: {
 &quot;text&quot;: &quot;Average Monthly Precipitation for Juneau, Alaska&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;#000000&quot; 
} 
},
&quot;yAxis&quot;: [
 {
 &quot;title&quot;: {
 &quot;text&quot;: &quot;Precipitation (mm)&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
} 
} 
],
&quot;subtitle&quot;: {
 &quot;text&quot;: &quot;Historical CRU 3.1 and 5-Model Projected Average, Mid-Range Emissions (RCP 6.0)&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
},
&quot;legend&quot;: {
 &quot;verticalAlign&quot;: &quot;top&quot;,
&quot;y&quot;:             50,
&quot;borderWidth&quot;:              1,
&quot;borderColor&quot;: &quot;gray&quot;,
&quot;borderRadius&quot;:              5,
&quot;itemMarginBottom&quot;:             -5,
&quot;itemMarginBottom&quot;:             -5,
&quot;itemStyle&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
},
&quot;xAxis&quot;: [
 {
 &quot;categories&quot;: [ &quot;Jan&quot;, &quot;Feb&quot;, &quot;Mar&quot;, &quot;Apr&quot;, &quot;May&quot;, &quot;Jun&quot;, &quot;Jul&quot;, &quot;Aug&quot;, &quot;Sep&quot;, &quot;Oct&quot;, &quot;Nov&quot;, &quot;Dec&quot; ],
&quot;title&quot;: {
 &quot;text&quot;: &quot;Due to variability among climate models and among years in a natural climate system, these graphs are useful for examining trends over time, rather than for precisely&lt;br&gt;predicting monthly or yearly values. For more information on derivation, reliability, and variability among these projections, please visit www.snap.uaf.edu.&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot;,
&quot;fontWeight&quot;: &quot;normal&quot;,
&quot;fontSize&quot;: &quot;8px&quot; 
} 
} 
} 
],
&quot;series&quot;: [
 {
 &quot;data&quot;: [
 [
          111.5,
         280.5 
],
[
           73.6,
         238.4 
],
[
           92.4,
         225.6 
],
[
           85.9,
         192.1 
],
[
           95.3,
         174.7 
],
[
           70.7,
         141.3 
],
[
           95.6,
         206.4 
],
[
          106.8,
         279.2 
],
[
          185.3,
         392.7 
],
[
          229.8,
         462.2 
],
[
          142.7,
         355.3 
],
[
          113.9,
         296.1 
] 
],
&quot;name&quot;: &quot;1960-1989&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
            103,
           289 
],
[
           74.1,
         245.9 
],
[
             84,
           210 
],
[
           74.6,
         199.4 
],
[
           63.9,
         180.1 
],
[
           57.8,
         178.2 
],
[
           76.8,
         201.2 
],
[
          110.4,
         245.6 
],
[
          193.9,
         352.1 
],
[
          231.7,
         470.3 
],
[
          146.8,
         347.2 
],
[
          122.2,
         281.8 
] 
],
&quot;name&quot;: &quot;2010-2019&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
          116.4,
         279.6 
],
[
           99.5,
         256.5 
],
[
           90.5,
         215.5 
],
[
           97.6,
         214.4 
],
[
           74.3,
         199.7 
],
[
             49,
           147 
],
[
           94.6,
         219.4 
],
[
            119,
           291 
],
[
          231.1,
         428.9 
],
[
          234.4,
         523.6 
],
[
          149.3,
         320.7 
],
[
          127.4,
         298.6 
] 
],
&quot;name&quot;: &quot;2040-2049&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
          129.1,
         292.9 
],
[
           93.8,
         222.2 
],
[
           96.4,
         233.6 
],
[
          110.9,
         223.1 
],
[
           76.5,
         187.5 
],
[
           75.5,
         168.5 
],
[
           88.9,
         219.1 
],
[
           92.3,
         285.7 
],
[
            191,
           367 
],
[
          261.9,
         476.1 
],
[
            169,
           389 
],
[
          118.8,
         301.2 
] 
],
&quot;name&quot;: &quot;2060-2069&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
          121.8,
         278.2 
],
[
            103,
           241 
],
[
          112.8,
         233.2 
],
[
           84.6,
         231.4 
],
[
           86.8,
         215.2 
],
[
           50.5,
         179.5 
],
[
           92.2,
         211.8 
],
[
          110.7,
         337.3 
],
[
          219.4,
         434.6 
],
[
          295.1,
         550.9 
],
[
          164.2,
         361.8 
],
[
          141.4,
         302.6 
] 
],
&quot;name&quot;: &quot;2090-2099&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
} 
],
&quot;chart&quot;: {
 &quot;width&quot;:            800,
&quot;height&quot;:            500,
&quot;renderTo&quot;: &quot;chart1be0615148a0&quot; 
},
&quot;id&quot;: &quot;chart1be0615148a0&quot; 
});
        });
    })(jQuery);
&lt;/script&gt;
    
    &lt;script&gt;&lt;/script&gt;    
  &lt;/body&gt;
&lt;/html&gt; ' scrolling='no' frameBorder='0' seamless class='rChart  highcharts  ' id='iframe-chart1be0615148a0'> </iframe>
 <style>iframe.rChart{ width: 100%; height: 400px;}</style>

#### Precipitation range: 10-minute resolution

<iframe srcdoc=' &lt;!doctype HTML&gt;
&lt;meta charset = &#039;utf-8&#039;&gt;
&lt;html&gt;
  &lt;head&gt;
    
    &lt;script src=&#039;//code.jquery.com/jquery-1.9.1.min.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/highcharts.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/highcharts-more.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    &lt;script src=&#039;//code.highcharts.com/modules/exporting.js&#039; type=&#039;text/javascript&#039;&gt;&lt;/script&gt;
    
    &lt;style&gt;
    .rChart {
      display: block;
      margin-left: auto; 
      margin-right: auto;
      width: 800px;
      height: 400px;
    }  
    &lt;/style&gt;
    
  &lt;/head&gt;
  &lt;body &gt;
    
    &lt;div id = &#039;chart1be07a236ed6&#039; class = &#039;rChart highcharts&#039;&gt;&lt;/div&gt;    
    &lt;script type=&#039;text/javascript&#039;&gt;
    (function($){
        $(function () {
            var chart = new Highcharts.Chart({
 &quot;dom&quot;: &quot;chart1be07a236ed6&quot;,
&quot;width&quot;:            800,
&quot;height&quot;:            400,
&quot;credits&quot;: {
 &quot;href&quot;: null,
&quot;text&quot;: null 
},
&quot;exporting&quot;: {
 &quot;enabled&quot;: false 
},
&quot;title&quot;: {
 &quot;text&quot;: &quot;Average Monthly Precipitation for Juneau, Alaska&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;#000000&quot; 
} 
},
&quot;yAxis&quot;: [
 {
 &quot;title&quot;: {
 &quot;text&quot;: &quot;Precipitation (mm)&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
} 
} 
],
&quot;subtitle&quot;: {
 &quot;text&quot;: &quot;Historical CRU 3.1 and 5-Model Projected Average, Mid-Range Emissions (RCP 6.0)&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
},
&quot;legend&quot;: {
 &quot;verticalAlign&quot;: &quot;top&quot;,
&quot;y&quot;:             50,
&quot;borderWidth&quot;:              1,
&quot;borderColor&quot;: &quot;gray&quot;,
&quot;borderRadius&quot;:              5,
&quot;itemMarginBottom&quot;:             -5,
&quot;itemMarginBottom&quot;:             -5,
&quot;itemStyle&quot;: {
 &quot;color&quot;: &quot;gray&quot; 
} 
},
&quot;xAxis&quot;: [
 {
 &quot;categories&quot;: [ &quot;Jan&quot;, &quot;Feb&quot;, &quot;Mar&quot;, &quot;Apr&quot;, &quot;May&quot;, &quot;Jun&quot;, &quot;Jul&quot;, &quot;Aug&quot;, &quot;Sep&quot;, &quot;Oct&quot;, &quot;Nov&quot;, &quot;Dec&quot; ],
&quot;title&quot;: {
 &quot;text&quot;: &quot;Due to variability among climate models and among years in a natural climate system, these graphs are useful for examining trends over time, rather than for precisely&lt;br&gt;predicting monthly or yearly values. For more information on derivation, reliability, and variability among these projections, please visit www.snap.uaf.edu.&quot;,
&quot;style&quot;: {
 &quot;color&quot;: &quot;gray&quot;,
&quot;fontWeight&quot;: &quot;normal&quot;,
&quot;fontSize&quot;: &quot;8px&quot; 
} 
} 
} 
],
&quot;series&quot;: [
 {
 &quot;data&quot;: [
 [
           22.3,
          51.7 
],
[
           15.7,
          42.3 
],
[
           14.3,
          41.7 
],
[
           19.7,
          52.3 
],
[
           23.2,
          78.8 
],
[
           39.3,
          96.7 
],
[
           49.4,
         122.6 
],
[
           38.5,
          97.5 
],
[
           37.9,
          84.1 
],
[
           35.8,
          84.2 
],
[
           32.9,
          69.1 
],
[
           30.3,
          63.7 
] 
],
&quot;name&quot;: &quot;1960-1989&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
           25.9,
          54.1 
],
[
           20.2,
          41.8 
],
[
           19.9,
          46.1 
],
[
           26.7,
          53.3 
],
[
           33.2,
          84.8 
],
[
           44.8,
         109.2 
],
[
           62.2,
         137.8 
],
[
           27.2,
         106.8 
],
[
           40.5,
          89.5 
],
[
           39.5,
          86.5 
],
[
           39.9,
          76.1 
],
[
           33.2,
          62.8 
] 
],
&quot;name&quot;: &quot;2010-2019&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
           29.2,
          56.8 
],
[
           20.9,
          45.1 
],
[
           21.9,
          44.1 
],
[
           24.6,
          57.4 
],
[
           31.2,
          86.8 
],
[
           46.4,
         117.6 
],
[
           42.1,
         119.9 
],
[
           35.3,
          96.7 
],
[
           35.5,
          86.5 
],
[
           45.9,
          90.1 
],
[
           36.1,
          75.9 
],
[
             45,
            67 
] 
],
&quot;name&quot;: &quot;2040-2049&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
           30.8,
          59.2 
],
[
           20.2,
          49.8 
],
[
           20.4,
          43.6 
],
[
           28.2,
          53.8 
],
[
           35.8,
          84.2 
],
[
           50.3,
         107.7 
],
[
           51.9,
         124.1 
],
[
           37.2,
         102.8 
],
[
           35.1,
          96.9 
],
[
             45,
            93 
],
[
           40.9,
          81.1 
],
[
           40.8,
          67.2 
] 
],
&quot;name&quot;: &quot;2060-2069&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
},
{
 &quot;data&quot;: [
 [
           30.3,
          59.7 
],
[
           24.2,
          49.8 
],
[
             22,
            46 
],
[
           24.9,
          65.1 
],
[
           39.2,
          94.8 
],
[
           46.6,
         109.4 
],
[
             46,
           136 
],
[
           40.2,
         101.8 
],
[
           38.6,
          81.4 
],
[
           47.7,
          94.3 
],
[
           46.5,
          85.5 
],
[
           40.7,
          77.3 
] 
],
&quot;name&quot;: &quot;2090-2099&quot;,
&quot;type&quot;: &quot;columnrange&quot; 
} 
],
&quot;chart&quot;: {
 &quot;width&quot;:            800,
&quot;height&quot;:            500,
&quot;renderTo&quot;: &quot;chart1be07a236ed6&quot; 
},
&quot;id&quot;: &quot;chart1be07a236ed6&quot; 
});
        });
    })(jQuery);
&lt;/script&gt;
    
    &lt;script&gt;&lt;/script&gt;    
  &lt;/body&gt;
&lt;/html&gt; ' scrolling='no' frameBorder='0' seamless class='rChart  highcharts  ' id='iframe-chart1be07a236ed6'> </iframe>
 <style>iframe.rChart{ width: 100%; height: 400px;}</style>

<style>iframe.rChart{ width: 100%; height: 500px;}</style>

In summary, there are series issues of bias and pronounced heteroskadisticty between the 2-km and 10-minute resolution versions of these data.
With the exception of a quick comparison with Juneau, the magnitude of changes seen across scales are evidenced just by looking at Fairbanks.
There are thousands of communities in the Community Charts application, many of which will likely exhibit similar patterns as well as even more pronounced ones.
Furthermore, the comparison with Juneau reveals an important difference showing that even what has been uncovered here cannot be safely extrapolated to all communities.

If it is made clear that these differences across spatial scale exist and that, at the coarser scale, the climate signal no longer represents what would reasonably be considered community-level data,
then it is not bad to offer both resolutions for graphing.
However, it is not as though both resolutions would be offered.
Of course, for those communities to be added which necessitated consideration of 10-minute resolution "community" data in the first place, both resolutions cannot be offered.
Due to a combination of a push for adding communities to the application for which no high-resolution climate model outputs exist and a lack of due diligence in assessing the scientific merits of this,
communities are slated for inclusion in the application despite the known issues.

With what is shown here, a caveat next to a graph about this issue is simply not good enough.
Under the current circumstances, the 10-minute resolution data have no defensible place in the Community Charts application.
In fact, it can be argued that if use of the 10-minute resolution data is truly justifiable, that it is sufficiently spatially unbiased, and representative of community-level data,
then the most appropriate path forward is to dispense with the 2-km data which has a more limited geographic range, ensuring consistency of comparable data across communities.

The application could actually contain communities worldwide if using the 10-minute data. Why stop with the Northwest Territories?
This is too easy a claim to make, however.
It leaves aside many issues beyond the scope of this document regarding weaknesses in the 10-minute resolution downscaled CRU data and climate model outputs,
such as boundary issues during interpolation and downscaling which affect the usability of coarse coastal data for coastal communities.
If anything, the 10-minute resolution downscaled data should receive its own discrete treatment in any application and should not be mixed with 2-km outputs.