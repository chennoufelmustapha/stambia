<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.file.server" id="_KPD3gKyCEe2cfIbYAwURBw" md:ref="platform:/plugin/com.indy.environment/technology/file/standard.file.md#UUID_TECH_FILE_MD?fileId=UUID_TECH_FILE_MD$type=md$name=File?">
  <node defType="com.stambia.file.directory" id="_KUyFAKyCEe2cfIbYAwURBw" name="demo">
    <attribute defType="com.stambia.file.directory.path" id="_KVGOEKyCEe2cfIbYAwURBw" value="C:\Stambia 19\stambiaRuntime\samples\files"/>
    <node defType="com.stambia.file.file" id="_KVZwEKyCEe2cfIbYAwURBw" name="REF_US_STATES">
      <attribute defType="com.stambia.file.file.type" id="_KWGToayCEe2cfIbYAwURBw" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_KWLMIKyCEe2cfIbYAwURBw"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_KWLMIayCEe2cfIbYAwURBw" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_KWLMIqyCEe2cfIbYAwURBw" value="2C"/>
      <attribute defType="com.stambia.file.file.stringDelimiter" id="_KWLMI6yCEe2cfIbYAwURBw"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_KWLMJKyCEe2cfIbYAwURBw" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_KWQrsKyCEe2cfIbYAwURBw" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_KWQrsayCEe2cfIbYAwURBw" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_KWQrsqyCEe2cfIbYAwURBw" value="1"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_RPBTQKyCEe2cfIbYAwURBw" value="REF_US_STATES.csv"/>
      <node defType="com.stambia.file.field" id="_TVLugKyCEe2cfIbYAwURBw" name="STATE_UPPER_CASE" position="1">
        <attribute defType="com.stambia.file.field.size" id="_TVLugayCEe2cfIbYAwURBw" value="64"/>
        <attribute defType="com.stambia.file.field.type" id="_TVLugqyCEe2cfIbYAwURBw" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_TVLug6yCEe2cfIbYAwURBw" value="STATE_UPPER_CASE"/>
      </node>
      <node defType="com.stambia.file.field" id="_TVLuiKyCEe2cfIbYAwURBw" name="STATE_CODE" position="3">
        <attribute defType="com.stambia.file.field.size" id="_TVLuiayCEe2cfIbYAwURBw" value="52"/>
        <attribute defType="com.stambia.file.field.type" id="_TVLuiqyCEe2cfIbYAwURBw" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_TVLui6yCEe2cfIbYAwURBw" value="STATE_CODE"/>
      </node>
      <node defType="com.stambia.file.field" id="_TVLuhKyCEe2cfIbYAwURBw" name="STATE" position="2">
        <attribute defType="com.stambia.file.field.size" id="_TVLuhayCEe2cfIbYAwURBw" value="64"/>
        <attribute defType="com.stambia.file.field.type" id="_TVLuhqyCEe2cfIbYAwURBw" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_TVLuh6yCEe2cfIbYAwURBw" value="STATE"/>
      </node>
    </node>
  </node>
</md:node>