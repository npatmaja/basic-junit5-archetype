# Basic JUnit 5 Archtype
A maven archtype to bootstrap maven project using JUnit5 (Jupiter) and several others accompanying testing libraries.

Included libraries
- JUnit 5
- Google Truth
- Mockito
- Lombok

## Usage
Clone the archetype and install to the local maven repository.
```shell
git clone git@github.com:npatmaja/basic-junit5-archetype.git
cd basic-junit5-archetype
clean install
```
Generate the project using `basic-junit5-archetype`
```shell
mvn archetype:generate -DarchetypeCatalog=local \
	-DgroupId=com.your.group.id \
	-DartifactId=artifact-id \
	-Dpackage=com.your.group.id.package \
	-DarchetypeArtifactId=basic-junit5-archetype \
	-DarchetypeGroupId=com.nauvalatmaja.maven.archetypes \
	-DinteractiveMode=false
```
