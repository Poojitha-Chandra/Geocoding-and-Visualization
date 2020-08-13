# Geocoding-and-Visualization
Bonjour!

# Multi-Step Data Analysis

 Increasingly, data is found on Web, often you find it in the wild.We can pull the data from a Twitter API or a GeoJSON API but then there are some rules about it.You might have to an API key.Here I simulated Google places API to look places up and so we can visualize on the map.So,for this gathering process I've used `my tutor's API` and tend to put in the database.This is a,spider like restartable process.

 **where.data** file is just a flat file thata has a list of organizations.So this data is read in by the program **geoload.py**,is a lot like a thing that reads some JSON,hits a URL,reads some JSON,parses some JSON,and then writes the JSON in the database *geodata.sqlite* and *geodata.db*.

I've got all our data sitting in this database,so I wrote a little program called **geodump.py**,that goes through looping all the records in the database.

The summarized information can be visualized through a whole bunch of JavaScript and HTML files like **where.js** and **where.html**.

Finally, that's the end-to-end spider process visualization.

