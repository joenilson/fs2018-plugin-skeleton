# Table folder
All the database tables must to be described here in XML format, the code must to be something like:

```
<?xml version="1.0" encoding="UTF-8"?>
<table>
    <column>
        <name>name</name>
        <type>character varying(100)</type>
        <null>NO</null>
    </column>
    <column>
        <name>codproject</name>
        <type>character varying(8)</type>
        <null>NO</null>
    </column>
    <constraint>
        <name>projects_pkey</name>
        <type>PRIMARY KEY (codproject)</type>
    </constraint>
</table>
```