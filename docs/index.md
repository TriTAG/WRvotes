---
title: Welcome!
layout: default
use-leaflet: true
---

<section class="flex justify-center">
  <article class="standout-box blue large">
    <div class="big-text blue-text header" id="map-box" data-aos="fade-left">
      October 22, 2018 is municipal election day in Waterloo Region.
    </div>
    <div class="content" data-aos="fade-up">
     <p>Type your address to find information about candidates & events relevant to your ward. Get informed, then vote!</p>
     <div id="map-searchbar"></div>
     <div id="map"></div>
     <p><strong>Note:</strong> The map loads more slowly than the rest of the page, so be patient, or use the <a href="/wards/">ward listing</a>.</p>
    </div>
  </article>
</section>

<script src="{{ site.baseurl }}/assets/js/leaflet.js"></script>
<script src="{{ site.baseurl }}/assets/js/leaflet-search.min.js"></script>
<!-- This has too many dependencies to load locally. -->
<script src="https://unpkg.com/leaflet-pip@1.1.0/leaflet-pip.js"></script>
<script src="{{ site.baseurl }}/assets/js/jquery-3.3.1.min.js"></script>
<script src="{{ site.baseurl }}/assets/js/show-map.js"></script>
