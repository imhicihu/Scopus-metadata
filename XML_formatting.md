* Be sure to define the document type appropriately using <!DOCTYPE ...>.
* Your XML file should UTF8-encoded.
* Your XML file must validate. Most *nix systems have access to the xmllint program for validation; there are also a number online XML validators, such as Validome; and many XML editing tools such as Liquid XML Editor, Oxygen XML and XMLspy can also validate XML files.
* Dates should be specified as YYYY-MM-DD.
* ~~To import a file, you can use <embed> to place a file directly within your XML document, or use <href> to link to one.~~
* full URLs as well as local files using <href>
* importing HTML galleys, use the <htmlgalley> element. Otherwise, use the <galley> element (ie., for PDF/Postscript, audio, video and other files).
* Some elements can support embedded HTML tags, such as the abstract element. If you do embed HTML within your document, remember to wrap the HTML within <![CDATA[]]> tags.
* 