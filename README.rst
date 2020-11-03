WeatherScript
=============

For all your HK weather data

Setup using python
Usage
.. code:: python 
	from weatherScript.weatherScript import weatherInstance
	weather_obj = weatherInstance(config_file, debug_state, data_dir, debug_dir)
	# reads config file (.ini) for URL and locations (see sample ini)

Tasks
.. code:: python
	weather_obj.log_data() # Writes to data_dir or debug_dir based on state