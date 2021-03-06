
The `init` method for `CounterService` takes the `Properties` object as an argument. This means we can add properties to the service that are passed to the `init` method; see [Creating the Service Class](00_Creating_the_Service_Class.md). You can add properties declaratively as shown below. (You likely want to name your properties something other than someproperty.)

```xml
<service enabled="true">
   <name>CounterService</name>
   <class-name>CounterService</class-name>
   <properties> 
      <someproperty>10</someproperty>
   </properties>
</service>
```

If you want to parse a more complex XML, you can use the interface `com.hazelcast.spi.ServiceConfigurationParser`. It gives you access to the XML DOM tree.

