
## Overvewiew
This repository provides samples for implementing Neoload automated testing in:
* Azure DevOps pipeline
* GitHub workflow

The samples leverage the Neoload CLI to run a Neoload test through Neoload Web.

The test infrastructure (Controller and Load Generators) needed to run the test can be either provided as predefined/existing Neoload Web resources (Neoload Cloud, static or dynamic) or hosted within the pipeline itself (*neoload-\*-resoruces.yml* samples)

## TL;DR ... How
The samples are "ready to use", just follow the vendor-specific guidelines to set up the pipeline.

The automated test execution requires 3 parameters:

* Neoload Web access *Token*
* Neoload Web resources *Zone Id* (required also in case of pipeline self-hosted test infrastructure)
* Neoload Web *Test Id* (the test has to be already created and configured in terms of the underlying Neoload project and Neoload scenario)


## Additional info
* [Neolaod CLI repo](https://github.com/Neotys-Labs/neoload-cli/)
* [Neolaod Web doc](https://documentation.tricentis.com/nlweb/latest/en/content/home.htm)
