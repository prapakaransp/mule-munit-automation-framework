# mule-munit-automation-framework
The munit framework automates coding steps for unit testing and validate all the business scenarios based on the input and output files which includes positive scenarios and Error scenarios.

The below digram illustrates architecture of the unit test framework.
![image](https://user-images.githubusercontent.com/6832114/69595505-5bb84b80-0fc5-11ea-8bcc-fe94c1746905.png)


## project steps
i)Copy testmunitautomation-test-suite.xml to src/test/munit.

ii)Configure main flow(the actual flow for testing) with unit test framework.

iii)Place input scenarios(XMLs, Json, CSV) files inside /src/test/resources/examples/input folder depending on requirement.

iv)Place the json, XML, Error codes on output file inside /src/test/resources/examples/output folder. The name of the file should match equivalent input file. Error code will be placed .txt file.

v)Run the unit test flow.

## Additional maven dependencies
`<repository>
    <id>central</id>
    <name>artifactory.codecentric.de-releases</name>
    <url>https://artifactory.codecentric.de/artifactory/public</url>
</repository>

<dependency>
    <groupId>de.codecentric.mule.modules</groupId>
    <artifactId>assert-object-equals-module</artifactId>
    <version>1.1.0</version>
    <classifier>mule-plugin</classifier>
</dependency> `




## Contributing
Pull requests are welcome.
