eGauge Monitor for SmartThigs

This is a small app based on the code from Ronald Gouldner.

This app will create two tiles, one for Solar Energy generation and one for energy used from or put back on the grid.
If solar energy is being generated the Solar tile turns green and displays the watts bing generated.  If no solar power
is being generated, the tile turns black.  The Grid tile displays positive ot negative watts values.  If the value is
negative, it means the solar system is generating surplus and putting it back on the grid.  In that case the tile is
green.  If the Grid value is positive, it means we are using power from the grid and the tile turns red. 

To intall create a new device type and copy the code from eGauge.groovy, save, and publish.  After that, create a 
new application and select the new eGage device.