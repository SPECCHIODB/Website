---
layout: Hero
title: Spectral Information System
description: >
  SPECCHIO is a spectral information system designed to hold reference spectra and
  spectral campaign data obtained by spectroradiometers. The inclusion of a rich
  metadata set in the data model ensures the longevity of spectral data and
  enables the sharing of spectral data between research groups. 
---

<!-- Features -->
<div class="columns features">

  <!-- Webapp -->
  <feature-card
    absolute
    :icon="['fas', 'database']"
    :to="$site.themeConfig.specchioWebinterface"
    class="column is-4">

#### SPECCHIO Web Interface
The Web Interface allows you searched the database directly for spectral data by
web browser without installing additional software.

  </feature-card>


  <!-- Download -->
  <feature-card
    :icon="['fas', 'download']"
    to="/downloads/"
    class="column is-4">

#### SPECCHIO Client / VM
Download the latest SPECCHIO Client Application. We have installers for MacOS,
Windows and Linux. We also provide a preconfigured VirtualBox VM with everything
installed you need.

  </feature-card>


  <!-- Guides -->
  <feature-card
    :icon="['fas', 'book']"
    to="/guides/"
    class="column is-4">

#### Guides
We provide guides with detailed installation instructions, technical background
information and tutorials for the SPECCHIO client application. Furthermore,
there are also guides on how to access SPECCHIO directly from Matlab and R.

  </feature-card>  
</div>



<!-- Teaser -->
<div class="intro column is-8 is-offset-2">

## Perfect for research!
Learn more by reading our leaflet: 
<download-link
    name="SPECCHIO Leaflet"
    link="https://github.com/SPECCHIODB/Guides/blob/master/SPECCHIO%20Leaflet.pdf"/>
Programmatic access from e.g. Matlab or R.
Check out the [tutorials](/programming-course/)
and our extensive [API documentation](https://specchio.ch/javadoc/).

![Architecture](./_img/Architecture.jpg)

</div>


<!-- Support Acknowledgements -->
<div class="intro column is-8 is-offset-2">

# Acknowledgements

SPECCHIO has received support by

img {
    object-fit: contain;
}
<img src="./_img/logo_SCNAT_EN_RGB.png" alt="ScNat" width="240" height="180"/>
<img src="./_img/MetEOC.png" alt="MetEOC" width="240" height="180"/>
<img src="./_img/EMPIR.png" alt="EMPIR" width="240" height="180"/>

</div>


::: slot twitter
<!-- Tweets -->
<client-only>
  <twitter-feed/>
</client-only>
:::
