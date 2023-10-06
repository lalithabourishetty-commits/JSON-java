# Library Comparison

There are many Java JSON libraries available which supports, to and pro data transfer.
which support this process like org.JSON,GSON etc...

The purpose of these libraries is same.How to choose among these? Let's go further

Below are few resources which explain about the differences between these libraries

*
*[Java Json libraries features Comparison](https://itsallbinary.com/jackson-vs-gson-vs-json-b-vs-json-p-vs-org-json-vs-jsonpath-java-json-libraries-features-comparison/#jsonparse)
**

*
*[Which JSONObject to use](https://stackoverflow.com/questions/29042622/which-one-to-use-jsonobject-from-org-json-vs-jsonobject-from-javax-json)
**

org.JSON vs Javax.json
=============================== 
org.json provides org.json.JSONObject while javax.json-api provides javax.json.JsonObject. Though they are used for
similar purpose they do have certain differences.
Below table shows the differences between these two,

|                             | **org.json**                                                                                                                                                                                                                     | **javax.json**                                         |
|:----------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------|
| Package                     | org.json                                                                                                                                                                                                                         | javax.json                                             |
| JSON Processing API Version | The API for org.json is well defined, although not "formal". Android currently uses the same namespace and API from this project, albeit an older iteration of it.                                                               | Java API for JSON Processing (Version 1.1)             |
| Parsing                     | org.json fully conforms on the JSON spec for input and output. The JSON Spec specifically states that parsing of JSON may be more lax and still be conforming, while output must meet exact specifications, which org.json does. | Provides a streaming and object model JSON parser      |
| Writing                     | Supports writing JSON objects and arrays                                                                                                                                                                                         | Supports writing JSON objects and arrays               |
| Size                        | Lightweight                                                                                                                                                                                                                      | Standard (part of Java EE and Java SE)                 |
| Dependencies                | Standalone library, no external dependencies                                                                                                                                                                                     | Part of Java EE and Java SE, no external dependencies  |
| Streaming                   | org.json support streaming by using the JSONTokener class directly, although it may not be as flexible as javax.json streaming. Unless you are implying event based streaming like an XML streaming parser may provide...        | Supports streaming JSON processing                     |
| Conformance                 | May not fully conform to the JSON standard                                                                                                                                                                                       | Fully conforms to the JSON standard                    |
| Performance                 | Generally considered slower                                                                                                                                                                                                      | Generally considered faster                            |
| Popularity                  | Widely used, especially in older Java projects                                                                                                                                                                                   | Gaining popularity, recommended for new projects       |
| license                     | Released as public domain                                                                                                                                                                                                        | Released with Eclipse and GPL+ GNU Classpath Exception |



