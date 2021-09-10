# To Do

## Outstanding
### Operational
- [ ] Re-index the FileAPI
	- [x] Dev
	- [ ] Missing Blobs?
	- [x] Prod
	- [x] Delete missing blobs

- [x] De-dupe in FileAPI
	- [ ] Remove existing dupes?

- [ ] Shutdown old prod-fileapi services

- [ ] Migrate legacy SQL DB to Postgres

- [ ] All prod services moved to subscription 2

- [ ] Sort out docker hub info

- [ ] Refresh Cosmo DB passwords


### Workflows
- [ ] Error notifications
- [ ] Data loader failures
- [ ] Rework argo workflows, standardise them
- [ ] Rename argo configuration
- [ ] Run workflows automatically
- [ ] Argo/Kubes permissions
- [ ] JIT Signal Generation
- [ ] Tooling to update crons/test




### Development
- [ ] Improve missing check, time constraint
- [ ] Customer API feature complete
- [ ] Add healthchecks to all API's
- [ ] UI/Process for managing Reference DB
- [ ] Update signal base to use common log logic

### Other
- [ ] Free resource?
- [ ] Standardise Github repos
- [ ] Get Tokens for Customer API

## Done
- [x] Reference API in Prod
- [x] Reference DB in Prod
- [x] Customer API in Prod
- [x] Make FileAPI transactions atomic
- [x] Add loaders to workflow
	- [x] Migrate loaders to Reference API
