# hal-fixture-sin

Fixture needed by tests in HAL team repositories.

For the automated tests of the antithesis project, this repo must:

- be public
- have its default branch be "main"
- contain a CODEOWNERS file at the root, whose contents contains valid role assignments for antithesis
- contain an antithesis-test dir with:
   -   docker-compose.yaml that contains valid instructions for an antithesis-test run
   -   README.md with valid markdown
   -   testnet.yaml with a valid multidocument yaml to configure the tests
