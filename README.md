# Settings

* Java development settings

## How to use

1. Clone the repository and import settings to your Eclipse.

	```
	src/main/resources/
		spt/
			settings/
				checkstyle/			# Checkstyle settings
					checkstyle.xml
				eclipse/			# Eclipse settings
					platform/
					project/
	```

1. Otherwise, add the dependency in your POM ( [Maven Central](https://repo1.maven.org/maven2/com/github/spt-oss/settings/) ).

	```xml
	<plugin>
		<groupId>org.apache.maven.plugins</groupId>
		<artifactId>maven-checkstyle-plugin</artifactId>
		<configuration>
			<configLocation>spt/settings/checkstyle/checkstyle.xml</configLocation>
		</configuration>
		<dependencies>
			<dependency>
				<groupId>com.github.spt-oss</groupId>
				<artifactId>settings</artifactId>
				<version>X.X.X</version>
			</dependency>
		</dependencies>
	</plugin>
	```

## License

This software is released under the Apache License 2.0.
