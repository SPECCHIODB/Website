<template>
  <footer class="footer">
    <div class="container">
      <div class="columns">
        
        <!-- Links -->
        <div class="column is-3">
          <h2>
            <strong>Links</strong>
          </h2>
          <ul>
           <li>
              <a
                href="https://twitter.com/SPECCHIO_DB"
                target="_blank"
                rel="noopener noreferrer">
                Twitter
              </a>
            </li>
            <li>
              <a
                href="https://github.com/SPECCHIODB/SPECCHIO"
                target="_blank"
                rel="noopener noreferrer">
                Github
              </a>
            </li>
            <li>
              <a
                href="https://www.geo.uzh.ch/en/units/rsl"
                target="_blank"
                rel="noopener noreferrer">
                Remote Sensing Laboratories (RSL)
              </a>
            </li>
            <li>
              <a
                href="http://sc22.geo.uzh.ch:8080/SPECCHIO_Web_Interface"
                target="_blank"
                rel="noopener noreferrer">
                SPECCHIO Web Interface
              </a>
            </li>
            <li>
              <a
                href="https://www.researchgate.net/project/SPECCHIO-Spectral-Information-System"
                target="_blank"
                rel="noopener noreferrer">
                SPECCHIO on ResearchGate
              </a>
            </li>            
          </ul>
        </div>

        <!-- Feedback -->
        <div class="column is-3">
          <h2>
            <strong>Contact and Feedback</strong>
          </h2>
          <p>
            <a 
              href="https://www.geo.uzh.ch/geolean/en/units/rsl/staff/?content=andreashueni"
              target="_blank"
              rel="noopener noreferrer">
              A. Hueni
            </a>
          </p>
          <p>
            <email-address
              name="specchioadmin" 
              domain="geo.uzh" 
              tld="ch"/>
          </p>
        </div>
        
        <!-- Citation and Licence -->
        <div class="column is-3">
          <h2>
            <strong>Citation and Licence</strong>
          </h2>
          <ul>
           <li>
              <a
                href="/citations/"
                target="_blank"
                rel="noopener noreferrer">
                Citations
              </a>
            </li>
           <li>
              <a
                href="https://github.com/SPECCHIODB/Guides/raw/master/Data_License.pdf"
                target="_blank"
                rel="noopener noreferrer">
                Online Database Licence
              </a>
            </li>            
          </ul>
        </div>

        <!-- Other spectral databases -->
        <div class="column is-4">
          <h2>
            <strong>Other spectral databases</strong>
          </h2>
          <ul>
            <li>
              <a
                href="https://docs.dea.ga.gov.au/data/product/australian-national-spectral-database"
                target="_blank"
                rel="noopener noreferrer">
                Australian National Spectral Database (A SPECCHIO Instance)
              </a>
            </li>          
            <li>
              <a
                href="https://ecosis.org/"
                target="_blank"
                rel="noopener noreferrer">
                EcoSIS
              </a>
            </li>
            <li>
              <a
                href="https://www.genlib.info"
                target="_blank"
                rel="noopener noreferrer">
                GENLIB
              </a>
            </li>            
            <li>
              <a
                href="http://www-app2.gfz-potsdam.de/spectation/?file=main"
                target="_blank"
                rel="noopener noreferrer">
                SPECTATION
              </a>
            </li>
            <li>
              <a
                href="https://speclib.jpl.nasa.gov/"
                target="_blank"
                rel="noopener noreferrer">
                ECOSTRESS spectral library version 1.0 (formerly the ASTER library)
              </a>
            </li>            
            <li>
              <a
                href="https://speclab.cr.usgs.gov/spectral-lib.html"
                target="_blank"
                rel="noopener noreferrer">
                USGS Spectral Library
              </a>
            </li>
            <li>
              <a
                href="http://www.geo-informatie.nl/Projects/Santa_Barbara_Urban_Spectral_Library/urbanspec/roads/sb_road_data.htm"
                target="_blank"
                rel="noopener noreferrer">
                Santa Barbara urban spectral library
              </a>
            </li>
            <li>
              <a
                href="/spectra_proc/"
                target="_blank"
                rel="noopener noreferrer">
                SpectraProc system
              </a>
            </li>
          </ul>
        </div>
      </div>

    </div>
  </footer>
</template>

<script>
export default {
  data () {
    return {
       showEmail: false
    }
  },

  mounted() {
    setTimeout(() => {
      this.showEmail = true
    }, 1000)
  }
}
</script>
