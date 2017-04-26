# lead-testing

This repo contains information related to DIY heavy metal testing in Troy, NY.  Heavy metal testing of soil and water generally requires expensive equipment and expertise beyond what is available to most who might be at risk for heavy metal poisoning.  This project aims to prepare a high-quality, low-cost DIY lab procedure that can be made accessible to Troy residents.

## policy, training and other info

* [NYS lead guide](https://www.health.ny.gov/regulations/nycrr/title_10/part_67/)

## mapping

It may be desirable to map any contaminated spots in the community.

* [Here GPS Location](https://f-droid.org/repository/browse/?fdfilter=here+gps+location&fdid=com.borneq.heregpslocation) - an app for logging your GPS coordinates when you take a sample
* [Leaflet](http://leafletjs.com/) mapping library
* [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON) standard
* [WhereAreTheEyes](https://f-droid.org/repository/browse/?fdfilter=where+are&fdid=org.daylightingsociety.wherearetheeyes) - this could probably be forked and set up with a new backend to meet our needs

## procedures

Papers and protocols describing how to do heavy metal testing on the cheap.

* [Mielke paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1651267/pdf/amjph00647-0022.pdf)
* [some other suggestions](https://www.researchgate.net/post/What_is_the_procedure_for_measuring_soil_heavy_metals_using_atomic_absorption_spectroscope_AAS)
* [strawberry pesticide detection](https://publiclab.org/notes/silverhammer/02-06-2014/detecting-pesticides-in-organic-and-conventional-raspberries-using-open-source-instrumentation)

## theory

* [absorbance vs concentration](https://terpconnect.umd.edu/~toh/models/BeersLawCurveFit.html) - important to think about during calibration.
* [Beer's Law](https://publiclab.org/notes/straylight/05-13-2013/using-the-spectroscope-for-analysis-of-concentration-beer-s-law)

## equipment

### absorbance spectroscopy
* [Lumini TWO](http://myspectral.tictail.com/product/lumini-two) - a fairly cheap handheld unit
* [open-Spectrometer](https://hackaday.io/project/1342-open-spectrometer) - this one seems decent
* [OtterVIS](https://hackaday.io/project/10738-ottervis-lgl-spectrophotometer) - **this one might be the best**
* [DAV 5](https://hackaday.io/project/11412-dav-5-uvvis-spectrometer) - another interesting one
* [Plab spectrometer version 2.5 vs Spex FluoroMax](https://publiclab.org/notes/silverhammer/02-06-2014/detecting-pesticides-in-organic-and-conventional-raspberries-using-open-source-instrumentation)
* [Public Lab Spectrophotommetry Kit 3.0](https://publiclab.org/wiki/desktop-spectrometry-kit-3-0)

### XRF
* [hackaday.io thread](https://hackaday.io/project/5885-handheld-xrf)
* [thread describing a DIY XRF](http://physicsopenlab.org/2016/02/24/diy-xrf-spectrometry/)

## software
* [Spectral Workbench](https://spectralworkbench.org/login?back_to=/spectrums/fork/105146)
