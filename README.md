# sit-library-bom

This is the parent project for all projects of the S-IT Application Engineering & Consulting GmbH
that should be deployed to maven central.

Plugins can be disabled for inheriting projects by using the "inherited" tag in the pom.xml.

Example:
```
<plugin>
   <inherited>false</inherited>
   <groupId>packageGroupId<groupId>
   <artifactId>packageArtifactId<artifactId>
   <version>packageVersion</version>
 </plugin>
```