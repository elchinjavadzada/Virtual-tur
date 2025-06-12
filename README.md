<!DOCTYPE html>
<html>
  <head>
    <script type="text/javascript" src="https://cdn.pannellum.org/2.5/pannellum.js"></script>
    <link rel="stylesheet" type="text/css" href="https://cdn.pannellum.org/2.5/pannellum.css"/>
    <style>html, body { margin: 0; height: 100%; }</style>
  </head>
  <body>
    <div id="panorama" style="width: 100%; height: 100%;"></div>
    <script>
      const urlParams = new URLSearchParams(window.location.search);
      const img = urlParams.get('img');
      pannellum.viewer('panorama', {
        type: 'equirectangular',
        panorama: img
      });
    </script>
  </body>
</html># Virtual-tur
