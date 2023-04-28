# Hivemapper Ground Truth Dataset


### What is Hivemapper Ground Truth?
Ground Truth is a project to carefully and accurately build a highly precise dataset of street level objects -- speed limit signs, traffic lights, stop sings, and so forth. The positional accuracy of each object is equal to or better than 50 cm. 

### The purpose of Ground Truth

Hivemapper's Map AI automatically produces object detections - this is a speed limit sign of 25 mph located at these coordinates.  In order to assess the performance of Hivemapper's object detections we need a highly accurate and comprehensive reference dataset to compare against.  We built Ground Truth to serve as this reference dataset.

### How did we build Ground Truth

**1. Selected five object classes:**

* Stop Signs
* Traffic Lights
* Speed Limit Signs
* Turn Restriction Signs
* Highway Exit Signs


**2. Selected three different areas across the San Francisco Bay Area**

Ground Truth data was collected across 2-3 days in these three areas:

* Highway 101 from SF to SFO
* Urban area in San Francisco
* Suburban residential area south of San Francisco

![aor-sfbay](https://user-images.githubusercontent.com/3408732/235260289-866b59e1-7662-475c-922e-03665edceb27.jpg)


**3. Manual field surveys**

A team of two surveyors manually collected field data for these five object classes e.g. speed limit sign of 25 mph at 2359 Oakmont Dr, San Bruno, CA 94066 by driving up and down the roads across these different areas in (2) above.  The team of surveyors then cross-referenced their manually collected data with Hivemapper Dashcam imagery from those same areas to verify that all objects manually collected were comprehensive and accurately labeled.

Hivemapper built a high precision GNSS surveying kit as seen below to collect the positional coordinates of the objects -- speed limit signs, stop signs, etc. The GNSS surveying kit provides positional accuracy of 50cm or better.  The positional coordinates for the objects were captured by the team of surveyors placing the surveying kit directly next to the object (speed limit sign) and recording the GNSS coordinates provided.


![High Precision GNSS Surveying Kit](https://user-images.githubusercontent.com/3408732/235258976-2a946c0e-120b-4695-b656-95fe8a9b875f.jpg)


### Can I use this data for my project?

Yes, this is an open source dataset that Hivemapper is making available as a public good.  If you like to add or suggest a modification please do so by opening a GitHub Issue.
