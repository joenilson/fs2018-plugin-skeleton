# XMLView folder
To use the power of FacturaScripts screens generation you must to put the XML View of the controller here, the basic XMLView have this structure:

```
<?xml version="1.0" encoding="UTF-8"?>
<view>
    <columns>
        <column name="id" order="100">
            <widget type="text" fieldname="id" />
        </column>
        <column name="fieldone" order="110">
            <widget type="text" fieldname="databasefieldone" />
        </column>
        <column name="fieldtwo" order="120">
            <widget type="number" fieldname="databasefieldtwo" />
        </column>
        <column name="datecreation" title="creation-date" display="right" order="130">
            <widget type="date" fieldname="datecreation"/>
        </column>
    </columns>
</view>
```