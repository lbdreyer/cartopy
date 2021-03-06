.. _cartopy_projections:

Cartopy projection list
=======================


PlateCarree
-----------

.. autoclass:: cartopy.crs.PlateCarree

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(6, 3))
    ax = plt.axes(projection=ccrs.PlateCarree())
    ax.coastlines(resolution='110m')
    ax.gridlines()



.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(6, 3))
    ax = plt.axes(projection=ccrs.PlateCarree(central_longitude=180))
    ax.coastlines(resolution='110m')
    ax.gridlines()


LambertConformal
----------------

.. autoclass:: cartopy.crs.LambertConformal

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(4.28969332205, 3))
    ax = plt.axes(projection=ccrs.LambertConformal())
    ax.coastlines(resolution='110m')
    ax.gridlines()


LambertCylindrical
------------------

.. autoclass:: cartopy.crs.LambertCylindrical

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(9.42477796077, 3))
    ax = plt.axes(projection=ccrs.LambertCylindrical())
    ax.coastlines(resolution='110m')
    ax.gridlines()


Mercator
--------

.. autoclass:: cartopy.crs.Mercator

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(3.50907018473, 3))
    ax = plt.axes(projection=ccrs.Mercator())
    ax.coastlines(resolution='110m')
    ax.gridlines()


Miller
------

.. autoclass:: cartopy.crs.Miller

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(4.09152901955, 3))
    ax = plt.axes(projection=ccrs.Miller())
    ax.coastlines(resolution='110m')
    ax.gridlines()


Mollweide
---------

.. autoclass:: cartopy.crs.Mollweide

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(6, 3))
    ax = plt.axes(projection=ccrs.Mollweide())
    ax.coastlines(resolution='110m')
    ax.gridlines()


Orthographic
------------

.. autoclass:: cartopy.crs.Orthographic

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(3, 3))
    ax = plt.axes(projection=ccrs.Orthographic())
    ax.coastlines(resolution='110m')
    ax.gridlines()


Robinson
--------

.. autoclass:: cartopy.crs.Robinson

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(5.91496652704, 3))
    ax = plt.axes(projection=ccrs.Robinson())
    ax.coastlines(resolution='110m')
    ax.gridlines()


Stereographic
-------------

.. autoclass:: cartopy.crs.Stereographic

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(3, 3))
    ax = plt.axes(projection=ccrs.Stereographic())
    ax.coastlines(resolution='110m')
    ax.gridlines()


TransverseMercator
------------------

.. autoclass:: cartopy.crs.TransverseMercator

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(6, 3))
    ax = plt.axes(projection=ccrs.TransverseMercator())
    ax.coastlines(resolution='110m')
    ax.gridlines()


UTM
---

.. autoclass:: cartopy.crs.UTM


InterruptedGoodeHomolosine
--------------------------

.. autoclass:: cartopy.crs.InterruptedGoodeHomolosine

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(6.92280629527, 3))
    ax = plt.axes(projection=ccrs.InterruptedGoodeHomolosine())
    ax.coastlines(resolution='110m')
    ax.gridlines()


RotatedPole
-----------

.. autoclass:: cartopy.crs.RotatedPole

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(6, 3))
    ax = plt.axes(projection=ccrs.RotatedPole(pole_longitude=177.5, pole_latitude=37.5))
    ax.coastlines(resolution='110m')
    ax.gridlines()


OSGB
----

.. autoclass:: cartopy.crs.OSGB

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(1.61538461538, 3))
    ax = plt.axes(projection=ccrs.OSGB())
    ax.coastlines(resolution='50m')
    ax.gridlines()


EuroPP
------

.. autoclass:: cartopy.crs.EuroPP

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(2.51842105263, 3))
    ax = plt.axes(projection=ccrs.EuroPP())
    ax.coastlines(resolution='50m')
    ax.gridlines()


Geostationary
-------------

.. autoclass:: cartopy.crs.Geostationary

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(2.99893683337, 3))
    ax = plt.axes(projection=ccrs.Geostationary())
    ax.coastlines(resolution='110m')
    ax.gridlines()


Gnomonic
--------

.. autoclass:: cartopy.crs.Gnomonic

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(3, 3))
    ax = plt.axes(projection=ccrs.Gnomonic())
    ax.coastlines(resolution='110m')
    ax.gridlines()


NorthPolarStereo
----------------

.. autoclass:: cartopy.crs.NorthPolarStereo

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(3, 3))
    ax = plt.axes(projection=ccrs.NorthPolarStereo())
    ax.coastlines(resolution='110m')
    ax.gridlines()


OSNI
----

.. autoclass:: cartopy.crs.OSNI

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(2.43233741378, 3))
    ax = plt.axes(projection=ccrs.OSNI())
    ax.coastlines(resolution='10m')
    ax.gridlines()


SouthPolarStereo
----------------

.. autoclass:: cartopy.crs.SouthPolarStereo

.. plot::

    import matplotlib.pyplot as plt
    import cartopy.crs as ccrs

    plt.figure(figsize=(3, 3))
    ax = plt.axes(projection=ccrs.SouthPolarStereo())
    ax.coastlines(resolution='110m')
    ax.gridlines()


