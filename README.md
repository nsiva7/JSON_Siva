# JSON_Siva

Since many years I'm using org.json and I noticied parsing is not much efficient also there are many different JSON libraries are available<br/>
like JSON, Jackson, JSON-Simple, etc,..

But I like org.json library and I thought to upgrade org.json library and then I started parsing improvements finally it's done and I felt
that I can help my co-developer's with this library so made it.

These are some useful parsing improvements I implemented like

JSONObject.getJSONObject(key) this can provide you JSONObject whether it is in {"key", "value"} format or "{"key", "value"}" format
and if key is not available this library will provide empty JSONObject like {}.
Like this I have made many improvements in this library.

Usages:

Maven Dependency
&lt;dependency&gt;
  &lt;groupId&gt;siva.nimmala.json&lt;/groupId&gt;
  &lt;artifactId&gt;JSON_Siva&lt;/artifactId&gt;
  &lt;version&gt;1.0.1&lt;/version&gt;
&lt;/dependency&gt;


Gradle Implementation
allprojects {
        repositories {
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
