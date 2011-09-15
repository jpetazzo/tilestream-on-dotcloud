TileStream on DotCloud
======================

To deploy tilestream on DotCloud::

  git clone git://github.com/jpetazzo/tilestream-on-dotcloud
  dotcloud push tilestream tilestream-on-dotcloud

Then go to the URL shown at the end of the push.

By default, it will download Haiti Terrain Grey tileset. 
If you want to automatically load other tilesets, edit
``dotcloud.yml`` and change the ``mbtiles`` list under
the ``environment`` section.

More about MBTiles: http://mapbox.com/mbtiles-spec/

More about TileStream: https://github.com/mapbox/tilestream
