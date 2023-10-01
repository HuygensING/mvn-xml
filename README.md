# mvn-xml

# XML for Huygens ING MVN editions

This repository contains XML files for the Huygens Institute's editions in the MVN series (Middeleeuwse Verzamelhandschriften uit de Nederlanden, = Medieval Miscellanies from the Low Countries).

The XML files are contained in directories by manuscript:
- vds: Handschrift Vanden Stock, Hs. Brussel, KBR, II 116, edited by Daniël Ermens, available at [https://vds.mvn.huygens.knaw.nl/](https://vds.mvn.huygens.knaw.nl/)https://vds.mvn.huygens.knaw.nl/
- serrure: Handschrift-Serrure, Hs. Brussel, KBR, II 144, edited by Erika Langbroek and Annelies Roeleveld, available at https://serrure.mvn.huygens.knaw.nl/[https://serrure.mvn.huygens.knaw.nl/](https://serrure.mvn.huygens.knaw.nl/)
- bs: Het Blauwe Schuit-handschrift, Hs. Den Haag, Koninklijke Bibliotheek, 75 H 57, edited by Herman Brinkman, available at https://bs.mvn.huygens.knaw.nl/[https://bs.mvn.huygens.knaw.nl/](https://bs.mvn.huygens.knaw.nl/)
- hbsr: De Heber-Serrurecodex, Gent, Universiteitsbibliotheek, Hs. 1374, edited by Renée Gabriël en Mike Kestemont, available at https://hbsr.mvn.huygens.knaw.nl/[https://hbsr.mvn.huygens.knaw.nl/](https://hbsr.mvn.huygens.knaw.nl/)

The repository also contains the XML documentation (docu folder), the source for the XML schema (schema folder) and the framework that we use for editing the XML files in oXygen (framework folder).

I need to bring the documentation (readable version: https://github.com/HuygensING/mvn-xml/blob/main/docu/Richtlijnen%20MVN%20digitaal.pdf) as well as some aspects of the framework up to date. 

To use the framework, copy the mvn folder from the framework folder into your oXygen framework folder. The framework is a modified TEI framework. What it does is:

- it associates an XML file in the TEI namespace with a top-level element MVN with the MVN schema
- it provides a CSS display for MVN files in the oXygen author wiew
- there is a template for a new MVN document
- there are a few XSLT stylesheets for generating HTML and for a few utility functions

Contact me if you have questions (peter.boot@huygens.knaw.nl)


   
