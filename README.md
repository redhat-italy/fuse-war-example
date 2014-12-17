Example WAR application for Fabric/Fuse
====================

Create profile in fabric with parent feature-fabric-web.
Add reference to the war bundle and specify the maven type

Example io.fabric8.agent.properties

```properties
#Profile:sampleapp
attribute.parents = feature-fabric-web
bundle.mvn\:it.redhat.fuse/war-example/1.0.0/war = mvn:it.redhat.fuse/war-example/1.0.0/war
```