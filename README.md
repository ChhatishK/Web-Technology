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
