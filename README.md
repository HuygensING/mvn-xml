# mvn-xml

# XML for Huygens ING MVN editions

This repository will contain the XML files for the Huygens ING editions in the MVN series (Middeleeuwse Verzamelhandschriften uit de Nederlanden). 

For now it contains the XML documentation (docu folder), the source for the XML schema (schema folder) and the framework that we use for editing the XML files in oXygen (framework folder).

I need to bring the documentation (readable version: https://github.com/HuygensING/mvn-xml/blob/main/docu/Richtlijnen%20MVN%20digitaal.pdf) as well as some aspects of the framework up to date. 

To use the framework, copy the mvn folder from the framework folder into your oXygen framework folder. The framework is a modified TEI framework. What it does is:

- it associates an XML file in the TEI namespace with a top-level element MVN with the MVN schema
- it provides a CSS display for MVN files in the oXygen author wiew
- there is a template for a new MVN document
- there are a few XSLT stylesheets for generating HTML and for a few utility functions

Contact me if you have questions (peter.boot@huygens.knaw.nl)


   
