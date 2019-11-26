# mule-munit-automation-framework
The munit framework automates coding steps for unit testing and validate all the business scenarios based on the input and output files which includes positive scenarios and Error scenarios.

The below digram illustrates architecture of the unit test framework.
![image](https://gecgithub01.walmart.com/storage/user/35039/files/f0fe9180-0a53-11ea-9adc-4b355885e927)


## project steps
i)Copy testmunitautomation-test-suite.xml to src/test/munit.

ii)Configure main flow(the actual flow for testing) with unit test framework.

iii)Place input scenarios(XMLs, Json, CSV) files inside /src/test/resources/examples/input folder depending on requirement.

iv)Place the json, XML, Error codes on output file inside /src/test/resources/examples/output folder. The name of the file should match equivalent input file. Error code will be placed .txt file.

v)Run the unit test flow.




## Contributing
Pull requests are welcome.
