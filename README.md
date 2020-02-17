# JSON_Siva

Since many years I'm using org.json and I noticied parsing is not much efficient also there are many different JSON libraries are available
like JSON, Jackson, JSON-Simple, etc,..

But I like org.json library and I thought to upgrade org.json library and then I started parsing improvements finally it's done and I felt
that I have to help my co-developer's with this library so made it.

These are some useful parsing improvements I implemented like

JSONObject.getJSONObject(key) this can provide you JSONObject whether it is in {"key", "value"} format or "{"key", "value"}" format
and if key is not available this library will provide empty JSONObject like {}.

like this I have made many improvements in this library.

Usages:

Maven Dependency
<dependency>
  <groupId>siva.nimmala.json</groupId>
  <artifactId>JSON_Siva</artifactId>
  <version>1.0.1</version>
</dependency>


Gradle Implementation
allprojects {
        repositories {
            jcenter()
            maven { url "https://jitpack.io" }
        }
   }
   
   
   dependencies {
        implementation 'com.github.nsiva7:JSON_Siva:Version'
   }
   
   Version:
   [![](https://jitpack.io/v/nsiva7/JSON_Siva.svg)](https://jitpack.io/#nsiva7/JSON_Siva)
   
   
That's all.
Happy Programming....🤗
Have a good day.
