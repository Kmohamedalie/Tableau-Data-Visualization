---
jupyter:
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
  language_info:
    codemirror_mode:
      name: ipython
      version: 3
    file_extension: .py
    mimetype: text/x-python
    name: python
    nbconvert_exporter: python
    pygments_lexer: ipython3
    version: 3.8.5
  nbformat: 4
  nbformat_minor: 5
---

::: {#8b0bc5fe .cell .markdown}
![image-2.png](vertopal_cc1574a18d014dc9a7a6226e3dc12e0e/image-2.png)
:::

::: {#1bf55402 .cell .markdown}
Tableau is a visual analytics platform transforming the way we use data
to solve problems---empowering people and organizations to make the most
of their data.
`<a href="https://www.tableau.com/why-tableau/what-is-tableau">`{=html}`<b>`{=html}Tableau`</b>`{=html}`</a>`{=html}
:::

::: {#b824c2da .cell .markdown}
**My Tableau page:** [Mohamed Alie
Kamara](https://public.tableau.com/app/profile/mohamed.alie.kamara6326)
:::

::: {#3f44b7db .cell .markdown}
```{=html}
<!--[![image.png](attachment:image.png)](https://www.youtube.com/watch?v=YfE9jBq002s)-->
```
:::

::: {#21e0f5fc .cell .markdown}
**Official video about Tableau**
:::

::: {#d1b8d91b .cell .code execution_count="1"}
``` python
from IPython.display import YouTubeVideo
YouTubeVideo('YfE9jBq002s', width=720, height=360)
```

::: {.output .execute_result execution_count="1"}
![](vertopal_cc1574a18d014dc9a7a6226e3dc12e0e/c8897bb3418a0057651eb7d61bce457a328a6564.jpg)
:::
:::

::: {#c21bf92d .cell .code}
``` python
```
:::

::: {#dadacc10 .cell .markdown}
## **Table of content:**
:::

::: {#0087656f .cell .markdown}
`<a href="#bar">`{=html}**1.Bar**`</a>`{=html}

`<a href="#pie">`{=html}**2.Pie**`</a>`{=html}

`<a href="#stacked">`{=html}**3.Stacked**`</a>`{=html}

`<a href="#line">`{=html}**4.Line**`</a>`{=html}

`<a href="#histogram">`{=html}**5.Histogram**`</a>`{=html}

`<a href="#scatter">`{=html}**6.Scatter**`</a>`{=html}

`<a href="#regression">`{=html}**7.Regression**`</a>`{=html}

`<a href="#bar_line">`{=html}**8.Bar and Line**`</a>`{=html}

`<a href="#dashboard">`{=html}**9.Dash Boarding with
Tableau**`</a>`{=html}
:::

::: {#9dbc45be .cell .markdown}
## `<p id="bar">`{=html}Bar`</p>`{=html}

A bar chart (aka bar graph, column chart) plots numeric values for
levels of a categorical feature as bars. Levels are plotted on one chart
axis, and values are plotted on the other axis. Each categorical value
claims one bar, and the length of each bar corresponds to the bar\'s
value.
:::

::: {#ac69848e .cell .markdown}
```{=html}
<div class='tableauPlaceholder' id='viz1692379834496' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;CarListingsbyBrand_16909653936930&#47;BarChart&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CarListingsbyBrand_16909653936930&#47;BarChart' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;CarListingsbyBrand_16909653936930&#47;BarChart&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /></object></div>
```
```{=html}
<script type='text/javascript'>                    var divElement = document.getElementById('viz1692379834496');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
```
`<br/>`{=html}

```{=html}
<div align="right">
source: <a href="https://public.tableau.com/views/CarListingsbyBrand_16909653936930/BarChart?:language=en-GB&:display_count=n&:origin=viz_share_link">Tableau Public</a>
</div>
```
:::

::: {#f75a626e .cell .code}
``` python
```
:::

::: {#8a116928 .cell .markdown}
## `<p id="pie">`{=html}Pie`</p>`{=html}

These graphs are divided into sections that represent parts of a whole.
They provide a simple way to organize data and compare the size of each
component to one other.
:::

::: {#6c2961bb .cell .markdown}
```{=html}
<div class='tableauPlaceholder' id='viz1692383866464' style='position: relative'><noscript><a href='#'><img alt='Cars by Engine Fuel Type ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pi&#47;PierChart&#47;Foglio1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='PierChart&#47;Foglio1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pi&#47;PierChart&#47;Foglio1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>
```
```{=html}
<script type='text/javascript'>                    var divElement = document.getElementById('viz1692383866464');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
```
```{=html}
<div align="right">
source: <a href="https://public.tableau.com/app/profile/mohamed.alie.kamara6326/viz/PierChart/Foglio1?publish=yes">Tableau Public</a>
</div>
```
:::

::: {#8600e46b .cell .markdown}
## `<p id="stacked">`{=html}Stacked Area`</p>`{=html}

These visuals show change in one or more quantities by plotting a series
of data points over time and are frequently used within predictive
analytics. Line graphs utilize lines to demonstrate these changes while
area charts connect data points with line segments, stacking variables
on top of one another and using color to distinguish between variables.
:::

::: {#b145b6ab .cell .markdown}
```{=html}
<div class='tableauPlaceholder' id='viz1692386944658' style='position: relative'><noscript><a href='#'><img alt='Popularity of Engine Fuel Types (1982-2016) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;Stackedareachart_16923869047700&#47;Foglio1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Stackedareachart_16923869047700&#47;Foglio1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;Stackedareachart_16923869047700&#47;Foglio1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>
```
```{=html}
<script type='text/javascript'>                    var divElement = document.getElementById('viz1692386944658');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
```
```{=html}
<div align="right">
source: <a href="https://public.tableau.com/views/Stackedareachart_16923869047700/Foglio1?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link">Tableau Public</a>
</div>
```
:::

::: {#8abd5059 .cell .code}
``` python
```
:::

::: {#8618c2c0 .cell .markdown}
## `<p id="line">`{=html}Line`</p>`{=html}

These visuals show change in one or more quantities by plotting a series
of data points over time and are frequently used within predictive
analytics. Line graphs utilize lines to demonstrate these changes while
area charts connect data points with line segments, stacking variables
on top of one another and using color to distinguish between variables.
:::

::: {#dd65937a .cell .markdown}
```{=html}
<div class='tableauPlaceholder' id='viz1692390345326' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;SP&#47;SPvsFTSEReturnsH22008_16923903130000&#47;Line&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SPvsFTSEReturnsH22008_16923903130000&#47;Line' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;SP&#47;SPvsFTSEReturnsH22008_16923903130000&#47;Line&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>
```
```{=html}
<script type='text/javascript'>                    var divElement = document.getElementById('viz1692390345326');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
```
`<br>`{=html}

```{=html}
<div align="right">
source: <a href="https://public.tableau.com/views/SPvsFTSEReturnsH22008_16923903130000/Line?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link">Tableau Public</a>
</div>
```
:::

::: {#6970d63a .cell .code}
``` python
```
:::

::: {#955cfea0 .cell .markdown}
## `<p id="histogram">`{=html}Histogram`</p>`{=html}

This graph plots a distribution of numbers using a bar chart (with no
spaces between the bars), representing the quantity of data that falls
within a particular range. This visual makes it easy for an end user to
identify outliers within a given dataset.
:::

::: {#0de4eb8d .cell .markdown}
```{=html}
<div class='tableauPlaceholder' id='viz1692437035951' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Di&#47;DistributionofRealEstatePrices_16924370092110&#47;Foglio2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DistributionofRealEstatePrices_16924370092110&#47;Foglio2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Di&#47;DistributionofRealEstatePrices_16924370092110&#47;Foglio2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>
```
```{=html}
<script type='text/javascript'>                    var divElement = document.getElementById('viz1692437035951');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
```
`<br>`{=html}

```{=html}
<div align="right">
source: <a href="https://public.tableau.com/app/profile/mohamed.alie.kamara6326/viz/DistributionofRealEstatePrices_16924370092110/Foglio2?publish=yes">Tableau Public</a>
</div>
```
:::

::: {#0b6e608a .cell .code}
``` python
```
:::

::: {#d36f1f61 .cell .markdown}
## `<p id="scatter">`{=html}Scatter`</p>`{=html}

These visuals are beneficial in reveling the relationship between two
variables, and they are commonly used within regression data analysis.
However, these can sometimes be confused with bubble charts, which are
used to visualize three variables via the x-axis, the y-axis, and the
size of the bubble.
:::

::: {#8a863c5a .cell .markdown}
```{=html}
<div class='tableauPlaceholder' id='viz1692439771857' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sc&#47;Scatterplot_16924397544000&#47;Foglio1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Scatterplot_16924397544000&#47;Foglio1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sc&#47;Scatterplot_16924397544000&#47;Foglio1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>
```
```{=html}
<script type='text/javascript'>                    var divElement = document.getElementById('viz1692439771857');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
```
`<br>`{=html}

```{=html}
<div align="right">
source: <a href="https://public.tableau.com/views/Scatterplot_16924397544000/Foglio1?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link">Tableau Public</a>
</div>
```
:::

::: {#8702a51e .cell .code}
``` python
```
:::

::: {#3a7e35a1 .cell .markdown}
## `<p id="regression">`{=html}Regression`</p>`{=html}

Plots can aid in the validation of the assumptions of normality,
linearity, and equality of variances. Plots are also useful for
detecting outliers, unusual observations, and influential cases. After
saving them as new variables, predicted values, residuals, and other
diagnostic information are available in the Data Editor for constructing
plots with the independent variables.
:::

::: {#a1cea084 .cell .markdown}
`<br>`{=html}

```{=html}
<div align="right">
source: <a href="">Tableau Public</a>
</div>
```
:::

::: {#3ab48afc .cell .code}
``` python
```
:::

::: {#b78d499b .cell .markdown}
## `<p id="bar_line">`{=html}Bar and Line`</p>`{=html}

Bar-Line charts show two metric values aggregated across a group
dimension. They are useful for showing quantity alongside changes in
trends over time.

The first Y-axis metric displays as a bar, and the second displays as a
line. The chart uses a dual-axis plot, where bars are plotted against
the left vertical axis and the line is plotted against the right
vertical axis.
:::

::: {#cf24c21c .cell .markdown}
`<br>`{=html}

```{=html}
<div align="right">
source: <a href="">Tableau Public</a>
</div>
```
:::

::: {#b8cd6e15 .cell .code}
``` python
```
:::

::: {#c710c330 .cell .markdown}
## `<p id="dashboard">`{=html}Dash Boarding in Tableau`</p>`{=html}
:::

::: {#7505e3e7 .cell .markdown}
`<br>`{=html}

```{=html}
<div align="right">
source: <a href="">Tableau Public</a>
</div>
```
:::

::: {#56199919 .cell .code}
``` python
```
:::
