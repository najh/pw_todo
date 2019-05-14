### API TODO

- [x] API Client
- [x] Auth with credentials file
- [x] JSON - System.Runtime.Serialization.Json
- [x] Hit reports list endpoint - /api/reports
- [x] Hit reports since endpoint - /api/reports?since=...
- [x] Deserialise Report List
- [x] Deserialise Report
- [x] Deserialise Area
- [x] Deserialise Division
- [x] Deserialise InspectionType
- [x] Deserialise Inspector
- [x] Rate limiting
- [x] Deserialise Role
- [x] Deserialise Survey
- [x] Hit detailed report endpoint - /api/report/:id
- [x] Deserialise FinalReflections
- [x] Deserialise Answers
- [x] Activity logging
- [x] Rename installer to connector
- [x] Separate out answers into a new table
- [x] Sub answers point at parent ID
- [x] Remove API responses from logs
- [x] Mutex for single instance
- [ ] Pagination (pending live implementation)
- [ ] Debug task scheduler error code
  - [ ] Determine cause of Debug class Type Initializer error.

### Other TODO
- [ ] Setup tool
  - [x] Abstracted DB driver to test connection
  - [x] Abstracted PW wrapper to test connection
  - [x] Bundle UI + connection tests to provide "easy setup"
  - [x] Automate scheduled task creation
  - [x] Save down last ID to skip already queried reports.
  - [x] Single EXE for ease of distribution
  - [ ] Code signing
- [x] Documentation
  - [x] Update docs for changes
  - [x] Finish docs for DB storage
  - [x] Document running as admin
  - [x] State what will be removed or will remain after an uninstallation
  - [x] Document connector setup as an alternative to the API itself
  - [x] Document SQL storage details (table/columns/permissions/connection string)
  - [ ] Document .NET/Windows file security, failing to load assemblies, error messages.
- [ ] Client requirements
  - [x] Windows
  - [x] .NET 4.6
  - [ ] Perfect Ward Account
  - [ ] API key
  - [ ] Firewall access
  - [ ] DB access
- [x] DB backends
  - [x] Separate MSSQL into its own module.
