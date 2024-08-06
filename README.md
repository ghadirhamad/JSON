# JSON
## what is JSON?
JSON is a lightweight data-interchange format based on a subset of the JavaScript
## JSON application:
1)using along side with programming language
2)transfer data between server and website
3)simplify complex information
## JSON format
JSON program must be written inside curly brackets {}
JSON depends on key-value pairs, for example:
{ "key":"value"}
as you see key and value should be seperated by colon :
## checking format
https://jsonformatter.org/
## JSON datatype
1) String --> {"name":"Ghadir"}
2) Numbers --> {"age":24}
3) Boolean --> {"livesInMiddleEast":true}  -notice must be written in lower case wethier it is true or false and without qutation marks
4) NULL --> {"phoneNumber":null}
5) Object --> now we will create object call "person"
 {
   "person":{
   "name":"Ghadir",
   "age":24,
   "livesInMiddleEast":true,
   "phoneNumber":null
   }
}
6) Array
{
  "people":[
   {
   "name":"Ghadir",
   "age":24,
   "livesInMiddleEast":true,
   "phoneNumber":null
   },
   {
   "name":"Ahmed",
   "age":26,
   "livesInMiddleEast":false,
   "phoneNumber":123456789
   },
   {
   "name":"Sara",
   "age":20,
   "livesInMiddleEast":true,
   "phoneNumber":321456987
   }
   ]
}
## JSON schema
is a file using to validating json file 
## Create JSON schema
https://transform.tools/json-to-json-schema
## checking the consistency of JSON schema with JSON file
https://www.jsonschemavalidator.net/
![image](https://github.com/user-attachments/assets/b6476f76-2ced-4475-8e06-df5a781da65e)
## Project 
in library.json file we have a library that wants to store information about 3 books based on this data: (book name, author name, author's birth year, author's nationality), book publication year, book classification, book availability). Book One
The Lord of the Rings
Written by: John Tolkien

Birth Year: 1892

Nationality: British

Book Published in: 1954

Genre: Fantasy, Adventure

Availability: Yes

Book Two
And Then There Were None
Written by: Agatha Christie

Birth Year: 1890

Nationality: British

Book Published in: 1939

Genre: Literature, Mystery

Availability: No

Book Three
Heidi
Written by: Johanna Spyri

Birth Year: 1827

Nationality: Swiss

Book Published in: 1880

Genre: Literature, Children

Availability: Yes
