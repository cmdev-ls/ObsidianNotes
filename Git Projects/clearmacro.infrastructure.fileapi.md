# Project Review: clearmacro.infrastructure.fileapi
**Project URL:** https://github.com/ClearMacro/clearmacro.infrastructure.fileapi

## To Do

- [ ] Add a basic README
- [x] Disable e2e tests for local runs
- [x] Document the dependancies somewhere

## Thoughts

### Initial Entry

- No README or guidance on how to start the project

### Testing
- 8 tests failed due to MongoDB issues...guessing setup related
- The test design is good, I like the distinction between unit tests and e2e tests
- It would be good to disable the e2e tests when running pytest locally, waiting 30 seconds on every test is pointless if it can't be run

### Dependancies
- Python/Poetry
- Build tools for building wheels