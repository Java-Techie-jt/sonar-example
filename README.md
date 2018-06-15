# sonar-example
What is sonar how to get start with it | Example

# Plugins:

<build>
		<plugins>
			<plugin>
				<groupId>org.sonarsource.scanner.maven</groupId>
				<artifactId>sonar-maven-plugin</artifactId>
				<version>3.4.0.905</version>
			</plugin>
			<plugin>
				<groupId>org.jacoco</groupId>
				<artifactId>jacoco-maven-plugin</artifactId>
				<version>0.8.1</version>
			</plugin>
		</plugins>
	</build>

# jacoco cmd:
clean org.jacoco:jacoco-maven-plugin:prepare-agent install

# sonar cmd:
mvn sonar:sonar 
