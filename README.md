# CETEIcean Starter

Simple template for publishing TEI with CETEicean 

* Add your TEI file to the foler `data`
* Change the code in `index.html` to load your file instead of the example file:
  ```javascript
  CETEIcean.getHTML5("data/YOUR_TEI_FILE.xml", function(data) {})
  ```
* Open `index.html` in a browser that allows fetching local files (e.g. Firefox), or serve through a simple server locally or publish it on the web.