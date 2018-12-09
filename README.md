#ISO20022 JSON XML

We are using one XML file published on the iso20022 website.

##ISO20022 XML File downloaded from

```
URL  : https://www.iso20022.org/full_catalogue.page
File : acmt.005.001.05.xsd 
Type : ATMDeviceReportV03
```

##Install Node JS on your machine
```
URL  : https://nodejs.org/en/download/
```

##Install XSD to JSON schema converter on your machine
```
URL  : https://www.npmjs.com/package/xsd2json
```

##Convert XSD to JSON schema demo(Using command line) 
```
£:~/Code/ISO20022-JSON/XSD|
⇒  xsd2json acmt.005.001.05.xsd > acmt.005.001.05.schema.json
£:~/Code/ISO20022-JSON/XSD|
⇒  ls -l
total 144
-rw-r--r--  1 suchakjani  staff  26997 9 Dec 08:33 acmt.005.001.05.schema.json
-rw-r--r--@ 1 suchakjani  staff  43248 9 Dec 07:56 acmt.005.001.05.xsd
```

##Convert XSD to sample XML (Use the URL to generate a sample XML online)
```
URL  : https://devutilsonline.com/xsd-xml/generate-xml-from-xsd
```

###Place the file in the XML folder
```
£:~/Code/ISO20022-JSON/XML|
⇒  ls  -la
total 48
drwxr-xr-x  3 suchakjani  staff     96 9 Dec 08:55 .
drwxr-xr-x  4 suchakjani  staff    128 9 Dec 08:55 ..
-rw-r--r--@ 1 suchakjani  staff  21686 9 Dec 08:55 acmt.005.001.05.sample.xml
```

##Install XML to JSON converter on your machine
```
URL  : https://www.npmjs.com/package/xml2json-cli
```

##Convert XML to JSON (Using command line)
```
£:~/Code/ISO20022-JSON/XML|
⇒  ls -l
total 48
-rw-r--r--@ 1 suchakjani  staff  21686 9 Dec 08:55 acmt.005.001.05.sample.xml
£:~/Code/ISO20022-JSON/XML|
⇒  xml2json acmt.005.001.05.sample.xml acmt.005.001.05.sample.json

   Complete writing to acmt.005.001.05.sample.json

£:~/Code/ISO20022-JSON/XML|
⇒  ls -l
total 72
-rw-r--r--  1 suchakjani  staff  10213 9 Dec 09:00 acmt.005.001.05.sample.json
-rw-r--r--@ 1 suchakjani  staff  21686 9 Dec 08:55 acmt.005.001.05.sample.xml
```


