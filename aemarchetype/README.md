## Build and place the latest AEM archetype in this folder

mvn -B org.apache.maven.plugins:maven-archetype-plugin:3.2.1:generate -D archetypeGroupId="com.adobe.aem" -D archetypeArtifactId="aem-project-archetype" -D archetypeVersion=43 -D aemVersion=cloud -D frontendModule=react -D appTitle="First AEM Project" -D appId="firstaemproject" -D artifactId="firstaemproject" -D groupId="com.support.interview" -D includeDispatcherConfig=y
