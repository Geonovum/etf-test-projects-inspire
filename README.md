# ETF test projects for INSPIRE
ETF test projects for use in SoapUI to test services to INSPIRE Technical Guidance requirements.

The ETF (ESDIN Test Framework) allows for testing geospatial webservices (like WMS, WFS, Atom) to the requirements of the INSPIRE Technical Guidances for View and Download Services.

The ETF uses SoapUI [SoapUI](http://www.soapui.org/) for test execution. SoapUI has a GUI and a command line interface. In addition, in the European Location Framework project [(ELF project website)](http://www.elfproject.eu/) a web application to run these tests is being developed.

This repository contains the code of the test projects.

## SoapUI workspace
To open the workspace with all test projects click on _File_ -> _Switch Workspace_ in the GUI and select the file _Test_projects_for_INSPIRE-soapui-workspace.xml_.

## Execute tests in SoapUI
The tests import additional libraries that are required to run the tests in SoapUI. Download the required libraries from https://services.interactive-instruments.de/etfdev-af/etf-public-dev/de/interactive-instruments/etf/. If you are asked for a login use: etf-public-dev / etf-public-dev. Afterwards copy the content of the zip to the bin/ext sub folder of your SoapUI installation directory.

## Issues and feedback
Bugs, feedback or other issues about the testprojects? Please use the [issues system](https://github.com/Geonovum/etf-test-projects-inspire/issues).
