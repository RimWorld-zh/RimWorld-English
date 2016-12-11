# RimWorld-English

This is the standard lanugage data template for translating RimWorld!

### DefInjected

* Fields: 5737
* Generated from the Defs by [RimTrans](https://github.com/duduluu/RimTrans).

### Keyed

* Fields: 1729
* Written by Tynan Sylvester.

### Current Version

* 0.16.1382

----

## Format of injections

### Format

DefInjected\defType\fileName.xml

```xml
  <defName.fieldName>Translation</defName.fieldName>
```

* **Note**: The field name ignore case!

### Example

**Defs** files: Mods\Core\Defs\XxxxxxDefs\Example.xml

```xml
<?xml version="1.0" encoding="utf-8" ?>
<Defs>

  <XxxxxxDef>  <!-- defType -->
    <defName>YYYYYY<defName>  <!-- defName -->
    <label>ZZZZZZ</label>  <!-- field -->
    <description>ZZZZZZ is a example, its defType is "XxxxxxDef" and defName is "YYYYYY".</description>  <!-- field -->
    <....>
  </XxxxxxDef>

</Defs>
```

* Then, create a subdirectory in directory DefInjected, **using the def type as a name**.
* The name of subdirectories ignore Singular and Plural from Alptha 14.


**DefInjected** files: Mods\Core\Languages\English\DefInjected\\**XxxxxxDef**\\Example.xml

```xml
<?xml version="1.0" encoding="utf-8" ?>
<LanguageData>

  <YYYYYY.label>ZZZZZZ</YYYYYY.label>
  <YYYYYY.description>ZZZZZZ is a example, its defType is "XxxxxxDef" and defName is "YYYYYY".</YYYYYY.description>

</LanguageData>
```