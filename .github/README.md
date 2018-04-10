# LightNovelSniffer
C# .Net 4.0 Web crawler to create PDF and Epub version of online light novels

## Web parser
Web parser use HtmlAgilityPack (https://www.nuget.org/packages/HtmlAgilityPack/1.4.9.5) to parse string to HtmlNodes.

## Epub
The library Ionic.Zip.dll is part of the DotNetZip library (https://www.nuget.org/packages/DotNetZip/) which have been cloned in this repo because of some needed modification

## PDF
PDF files are generated by the iTextSharp library (https://www.nuget.org/packages/iTextSharp/5.5.10)