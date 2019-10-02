---
title:     Demo Back Data
permalink: /analytics/backdata/demo
layout:    none
---
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Demo Back Data :: Frogtek Analytics</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="{{site.baseurl}}/assets/css/tableros.css">
  </head>
  <body>
    <nav id="top" class="navbar sticky-top navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="http://frogtek.org/analytics">
        <img
          src="{{ site.baseurl }}/assets/img/logo_analytics.png"
          class="d-inline-block align-top" alt="Frogtek Analytics">
      </a>
      <div class="navbar-text flex-row ml-md-auto">
        <div>Demo Back Data</div>
      </div>
      <ul class="navbar-nav flex-row ml-md-auto d-none d-md-flex">
        <li class="navbar-item">
            <a class="nav-link" href="https://ayuda.analytics.frogtek.org/" target="_blank">Centro de ayuda</a>
        </li>
      </ul>
    </nav>
    <div class='tableauPlaceholder' style='width: 1000px; height: 2350px;'>
      <object class='tableauViz' width='1000' height='2350' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2F10az.online.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='&#47;t&#47;frogtekdashboards' />
        <param name='name' value='BackData-Chiles&#47;Marca' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='no' />
        <param name='showAppBanner' value='false' />
        <param name='filter' value='iframeSizedToWindow=true' />
      </object>
    </div>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <script type='text/javascript' src='https://10az.online.tableau.com/javascripts/api/viz_v1.js'></script>
    <script src="{{ site.baseurl }}/assets//js/kommunicate.js"></script>
    <script>
      initKommunicate("704ff923dd05ff76f955580e61e755f5", "Chat de soporte Frogtek Analytics", null ,null, "True");
      $(function() {
        $('#myTab a').on('click', function(e) {
          e.preventDefault();
          $(this).tab('show');
        });
      });
    </script>
  </body>
</html>