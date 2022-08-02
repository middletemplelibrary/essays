<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Women In The Law"
       author="Middle Temple Library"
       banner="https://www.middletemple.org.uk/sites/default/files/Uploads/archive/Robinson.png" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
 

<param ve-entity eid="Q5703674"> <!-- Helena Normanton -->
<param ve-entity eid="Q925942"> <!-- Middle Temple -->


# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       ="https://www.middletemple.org.uk/sites/default/files/styles/large/public/CC%20Temple%20Bar%2018C_0.jpg">

# Basic usage

## Image

_Helena Normanton_ (Dutch: Meisje met de parel) photograph of blah blah blah.[^1]
<param ve-image 
       label="Helena Normanton" 
       description="photograph" 
       license="public domain" 
       url="https://www.middletemple.org.uk/sites/default/files/Uploads/archive/normantonLSEWL.png">

## Map

Middle Temple is located in the wider Temple area of London, near the Royal Courts of Justice, and within the City of London.
<param ve-map center="Q925942" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Helena Normanton](https://en.wikipedia.org/wiki/Helena_Normanton)
