# cypress-ci-preinstalled

Preinstalled docker image with Cypress 3.0.2.

To run this in your CI the following should be set as environment Variables:

CYPRESS_BINARY_VERSION=""
CYPRESS_INSTALL_BINARY="0"
CYPRESS_RUN_BINARY="/root/.cypress/Cypress/3.0.2/Cypress"

This will skip installing Cypress and use the preinstalled version when running
