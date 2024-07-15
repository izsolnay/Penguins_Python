<img src="Adelie.jpg" width="30%" height="30%">

<img src="Chinstrap.jpg" width="30%" height="30%">

<img src="Gentoo.jpg" width="30%" height="30%">


<img src="Adelie.jpg" width="200" height="500">

<img src="Chinstrap.jpg" width="200" height="500">

<img src="Gentoo.jpg" width="200" height="500">

| Adelie penguins                     | Chinstrap penguins                  | Gentoo penguins                     |
| ----------------------------------- | ----------------------------------- | ----------------------------------- |
| ![penguin](Adelie.jpg)              | ![penguin](Chinstrap.jpg)           | ![penguin](Gentoo.jpg)    



| Adelie penguins                     | Chinstrap penguins                  | Gentoo penguins                     |
| ----------------------------------- | ----------------------------------- | ----------------------------------- |
| <img src="Adelie.jpg" width="70%" height="70%"> | <img src="Chinstrap.jpg" width="70%" height="70%">| <img src="Gentoo.jpg" width="70%" height="70%">




```python

```


```python
from IPython.display import IFrame
IFrame(src='Biscoe_islands_map.html', width=600, height=600)
```





<iframe
    width="600"
    height="600"
    src="Biscoe_islands_map.html"
    frameborder="0"
    allowfullscreen

></iframe>





```python
from IPython.display import HTML
HTML('<iframe src='Biscoe_islands_map.html' width=700 height=350></iframe>')
```


      Cell In[5], line 2
        HTML('<iframe src='Biscoe_islands_map.html' width=700 height=350></iframe>')
             ^
    SyntaxError: invalid syntax. Perhaps you forgot a comma?




```python
from IPython.display import IFrame
IFrame(src='Biscoe_islands_map.html', width=600, height=600)
```


```python
from IPython.display import HTML
HTML('<iframe src=http://emperor.colorado.edu/master/make_emperor/emperor_output/index.html width=700 height=350></iframe>')
```

    /usr/local/lib/python3.11/site-packages/IPython/core/display.py:431: UserWarning: Consider using IPython.display.IFrame instead
      warnings.warn("Consider using IPython.display.IFrame instead")





<iframe src=http://emperor.colorado.edu/master/make_emperor/emperor_output/index.html width=700 height=350></iframe>




```python

```


```python
import folium

# Create a map centered on the GeoNames ID 6625672
m = folium.Map(location=[-64.77429, -64.05311], zoom_start=6)

# Add a marker at the GeoNames ID 6625672
folium.Marker(location=[-64.7742919,-64.0531107], popup='Palmer station').add_to(m)

folium.Marker(location=[-65.62781400486787, -65.84280382293767], popup='Biscoe').add_to(m)

folium.Marker(location=[-64.77274, -64.0745], popup='Torgersen').add_to(m)

folium.Marker(location=[-64.72504954782697, -64.2276111263013], popup='Dream').add_to(m)

# Save the map to an HTML file
m.save('map2.html')

```


```python
from IPython.display import IFrame

IFrame(src="map2.html", width=800, height=350)
```





<iframe
    width="800"
    height="350"
    src="map2.html"
    frameborder="0"
    allowfullscreen

></iframe>





```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
