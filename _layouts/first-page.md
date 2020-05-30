<head>
  <link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="{{ '/assets/libs/fontawesome-5.9.0/css/all.min.css' | relative_url }}" media="screen" type="text/css">
  <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}" media="screen" type="text/css">
</head>


<html style="min-height:100vh;">
  <body style="min-height:100vh;margin:0;padding: 0;background-image: url('assets/images/ciel.jpg');background-size: 100% 100%;background-attachment:fixed;">
    <div style="width:100%; height:100%;">
          {% include first-page.html %}
    </div>      
    <script type="text/javascript" src="{{ '/assets/libs/jquery-3.4.1.min.js' | relative_url }}"></script>
    <script type="text/javascript" src="{{ '/assets/libs/jquery-migrate-3.0.1.min.js' | relative_url }}"></script>
    <script type="text/javascript" src="{{ '/assets/js/panthera-jekyll.js?v=' | append: site.github.build_revision | relative_url }}"></script>
  
  </body>
</html>