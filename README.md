vmc-timeline
============

Steps to build VMC Timeline:
1. Build a new Google Spreadsheet using a template and publish to the public web
https://docs.google.com/spreadsheet/pub?key=0Ag8Nu3d9BacYdEc0QTJXV2xzNE9vd3JabS1VVG9KU2c&output=html 

2. Go to http://timeline.knightlab.com/#make to generate embed code for TimelineJS object referencing the google spreadsheet
<iframe src='http://cdn.knightlab.com/libs/timeline/latest/embed/index.html?source=0Ag8Nu3d9BacYdEc0QTJXV2xzNE9vd3JabS1VVG9KU2c&font=BreeSerif-OpenSans&maptype=TERRAIN&lang=en&start_zoom_adjust=2&height=700' width='100%' height='700' frameborder='0'></iframe> 

3. Add an index.html page with the embed code where you want your TimelineJS to appear 

4. Open the index page on a browser locally or upload it to a website

Cheers
