The Toolbar
===========
The SimpleDiagrams toolbar contains most of the tools you'll need to modify your diagrams. Click
a tool to activate it, or use it's shortcut key...

.. image:: /_static/images/tool-overview.jpg


.. |tool-zoom| image:: /_static/images/tool-zoom.png
   :align: middle

.. |tool-pencil| image:: /_static/images/tool-pencil.png
   :align: middle

.. |tool-marker| image:: /_static/images/tool-marker.png
   :align: middle

.. |tool-line| image:: /_static/images/tool-line.png
   :align: middle

.. |tool-text| image:: /_static/images/tool-text.png
   :align: middle

.. |tool-eyedropper| image:: /_static/images/tool-eyedropper.png
   :align: middle

.. |tool-move-to-front| image:: /_static/images/tool-move-to-front.png
   :align: middle

.. |tool-move-to-back| image:: /_static/images/tool-move-to-back.png
   :align: middle

.. |tool-align| image:: /_static/images/tool-align.png
   :align: middle

.. |tool-stroke-color| image:: /_static/images/tool-stroke-color.png
   :align: middle

.. |tool-fill-color| image:: /_static/images/tool-fill-color.png
   :align: middle

.. |tool-text-color| image:: /_static/images/tool-text-color.png
   :align: middle


.. |tool-align-expanded| image:: /_static/images/tool-align-expanded.png
.. |tool-line-expanded| image:: /_static/images/tool-line-expanded.png
.. |tool-eyedropper-full| image:: /_static/images/tool-eyedropper-full.png


Zoom Tool
------------
|tool-zoom|

**Shortcut key : V**

When you select the zoom tool, you can click to zoom in or shift-click to zoom out. Also, you can drag a marquee to zoom to a specific area.

You can completely skip this tool and just use the shortcut keys Command-shift-(plus key) to zoom and Command-shift-(minus key) to zoom in and out of your doc.


Pencil Tool
------------
|tool-pencil|

**Shortcut key : Z**

Pencil tool allows you to just draw silly lines. It's not as powerful as the line tool, in that you can't modify the curve of those lines afterwards.
You can, however, move and resize a drawing after you're finished.

Each time you click, draw and then release the mouse button, a new drawing shape is created that you can then resize or move.

(This actually isn't the best setup, and I'm working on making drawing more powerful and intuitive.)

Yes, you can't erase lines. Yes, I know that's stupid. Working on that too.


Marker Tool
------------
|tool-marker|

**Shortcut key: P**

The marker tool is just like the pencil too, except that is has kind of a marker-like look.


Line Tool
------------
|tool-line|

**Shortcut key : L**

The line tool is pretty much your go-to when creating diagrams. Use this to connect shapes or to draw lines whose curves you want do modify later.

There are three options to this tool, which you see when you click down on the button:

|tool-line-expanded|

The first option lets you draw straight lines, the second curved lines and the third kind of free-form squiggly lines.

Important Note: Hold down SHIFT while drawing a line so that you can drag-click drag-click and keep doing that in order to construct a complex line.

For more information on connectors, please read :doc:`making-diagrams`

Text Tool
------------
|tool-text|

**Shortcut key : T**

Select this tool and click on you diagram to place a text widget.


Eyedropper Tool
-----------------
|tool-eyedropper|

**Shortcut key : I**

Use the eyedropper tool to pick up a style from an existing object. When you click on a shape, eyedropper will remember that shape's stroke and fill styles.
When you do this, the eyedropper will change to a "full" image: |tool-eyedropper-full|

Then click on any other object to give it those styles.

Hold down the ALT key if you want to empty the eyedropper so you can pick up a new style. Aren't eyedroppers great? I don't know why it took me until v4 to get this working.



Move Forwards Button
---------------------
|tool-move-to-front|

**Shortcut key : Shift-command-[**

Move the selected shape to the front of the diagram.



Move Backwards Button
----------------------
|tool-move-to-back|

**Shortcut key : Shift-command-]**

Move the selected shape to the back of the diagram.

Align Objects
--------------
|tool-align|

**Shortcut key : (none)**

When you click this tool, you actually get a popout with a bunch of options for aligning *selected* shapes (don't forget to select the shapes you want to align before selecting the tool).

|tool-align-expanded|

Align moves the shapes into alignment, as pictured by the red line on each button.
Distribute spaces shapes out, using the side of the shape highlighted by the red line.



Stroke Color
-------------
|tool-stroke-color|

**Shortcut key : (none)**

The stroke color chip allows you to change the stroke color and texture of all selected objects (as long as that object has a stroke).

For more information on color see :doc:`working-with-color`



Fill Color
------------
|tool-fill-color|

**Shortcut key : (none)**

The fill color chip allows you to change the fill color and texture of all selected objects (as long as that object has a fill).

For more information on color see :doc:`working-with-color`



Text Color
------------
|tool-text-color|

**Shortcut key : (none)**

The text color chip allows you to change the font color all selected objects (as long as that object has a text).

For more information on color see :doc:`working-with-color`
