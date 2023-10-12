# Web-Technology


#Workshop of web Technology in NIET.


unvisited link - It is underlined and blue in color.
Active link - It is underlined and red in color.
visited Link - It is underlined and purple in color.

The target attribute specify, where to document should open. values :- self, _blank, parent and top.
self - Opens the document in same window or tab as it was clicked.(Default)
_blank - Opens the document in new window.
parent - Opens the document in the parent frame or window.
Top - Opens the document in full body of the window.

syntax :- 
        <a href="url" target="blank"> Click here to see the results </a>
        <a href="url" target="top"> Click here to see the results </a>
        <a href="url" target="blank"> Click here to see the results </a>
        <a href="url" target="blank"> Click here to see the results </a>


XML (Extensive Markup Language) 

- We can create our own tag.
- It uses to define element within a document
- It is used to design to store and transport the data.
- It is designed to carry data not to display data.
- XML platforma% language independent
- It seperate HTML document from XML.
- XML siimplify data sharing process and platform change.

- Syntax -
- <friendmap>
     <friends>
             <friend1>Bipin</friend1>
             <friend2>Satyam</friend2>
     </friends>
</friendmap>

Disadvantages -->
- Does not support array.
- High Transportation cost.

- DTD (Document Timing Defination)

- It is used to describe XML lang precisely.
- It is used to define structure of document.
- It contains list of legel element.
- It is also used to performance and validation.
- It does not support data types.
- It is not extensible.

  
- Syntax (DTD) -->

- Internal

- <!DOCTYPE
        [Declaration 1
         Declaration 2]>

  <!DOCTYPE 
     roof-element
     [element-declaration]>


  Internal DTD -->
   <?XML version="1.0" encoding "UTF-8">
   <!DOCTYPE Address [
          <! Element Address [
                  Name;Company;phone]>
  <!Element Name(#PCDATA)
  <!Element Company(#PCDATA)
  <!Element phone(#PCDATA)
  ]>

  XML (Root Element)
  <Address
     <name>Aryan</name>
     <address>PrayagRaj</address>

  --External DTD
  <!DOCTYPE Address
     SYSTEM "Address dtd">
  
     <phone>123456788</phone>
  </Address>

how to merge two xml file -->

- add prefix to the first file to connect with second file.

if same data occurs in both the file then it can be merged.


XSD (XML Schema Definition) -->
- It is xml schema definition which is commonly used to descrive and validate structure and content of xml data.
- It is nethod of expressing consparent about xml document.
- It  is very much similar type of xml document.
- Entension --> (.xs)
- It is extensible.
- It supports namespace.
- 
- 
Two types of XSD -->
-- Simple XSD
-- Complex XSD

- Syntax -->
- add.xsd -->
  - <xs:schema xmlns:xs="----">
 
  - Simple XSD -->
  - <xs:element name
  -  = "phone" type xs:"int" />

- Complex XSD -->
- A complex type element is an XML element that contains other elements and/or attributes.

XML with stylesheet -->
- Syntax -->
- <?xml:stylesheet type="text/css" href="xml1.css"?>

- A DOM Document is an object which contain all the info of an html document.
- It is collection of nodes, PC doc info organized in hierarical format.
- DOM is defined standard to access and manipulate the document.
- Prammmers can easily modify, delete and can create new element also, This is also used to far implement of DOM API.


Advantage:-
- It support both read and write operations and API is very easily and simple to use.
- It is prefered when random access to widely  seperated parts of  document is required.


Disadvantage :-
- It required a lot of memory to convert whole html document.
- It is comparatively slower than other parts of a document.

XSLT - (eXtensible StyleSheet Language Transformation) --> 
- It basically convert xml document to other document.
- It is used to remove/add the attributes and elements and rearrange the elements.

Sample.xsl --> 
- <?xml version="1.0" encoding="UTF-8"?>
- <xsl:stylesheet version="1.0" type="text/xsl" href="sample.xsl" ?>
- <college>
        - <name>Aryan</name>
        - <roll_no>9004</roll_no>
</college>

<?xml version=""1.0 encoding="UTF-8" ?>
<xsl:stylesheet version="1.0" type="text/xsl" href="sample.xsl">
<xsl:template match="/">
<html>
        <body>
                <table>
                        <tr>
                                <th>Name</th>
                                <th>Roll_no</th>
                        </tr>
                        <xsl:foreach sheet="college"/class>
                        <tr>
                                <td><xsl:value of select="Name"/></td>
                                <td><xsl:value of select="Roll_no"/></td>
                        </tr>
                        </xsl:foreach />
                                
                </table>
        </body>
</html>




</xsl:template>
</xsl:stylesheet>


Class selector with element -->
p.big ex--> <p class="big"></p>
