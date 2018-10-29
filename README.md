# IRIS Artefacts


### Add useragent-generic-java dependency into maven projects 
#### pom.xml changes

	<repositories>
		<repository>
			<id>jfiricel</id>
			<name>iris-repo</name>
			<url>https://github.com/jfiricel/iris-repo/raw/master/</url>
		</repository>
	</repositories>


	<dependencies>
		<dependency>
			<groupId>com.temenos.interaction</groupId>
			<artifactId>useragent-generic-java</artifactId>
			<version>0.15.34</version>
			<scope>compile</scope>
		</dependency>
	</dependencies>
