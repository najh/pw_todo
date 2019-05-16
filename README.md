### API TODO

- ✅ API Client
- ✅ Auth with credentials file
- ✅ JSON - System.Runtime.Serialization.Json
- ✅ Hit reports list endpoint - /api/reports
- ✅ Hit reports since endpoint - /api/reports?since=...
- ✅ Deserialise Report List
- ✅ Deserialise Report
- ✅ Deserialise Area
- ✅ Deserialise Division
- ✅ Deserialise InspectionType
- ✅ Deserialise Inspector
- ✅ Rate limiting
- ✅ Deserialise Role
- ✅ Deserialise Survey
- ✅ Hit detailed report endpoint - /api/report/:id
- ✅ Deserialise FinalReflections
- ✅ Deserialise Answers
- ✅ Activity logging
- ✅ Rename installer to connector
- ✅ Separate out answers into a new table
- ✅ Sub answers point at parent ID
- ✅ Remove API responses from logs
- ✅ Mutex for single instance
- 🔳 Pagination
    - ✅ Pending live implementation
    - 🔲 Testing
- ✅ Debug task scheduler error code
  - ✅ Determine cause of Debug class Type Initializer error.

### Other TODO
- 🔳 Setup tool
  - ✅ Abstracted DB driver to test connection
  - ✅ Abstracted PW wrapper to test connection
  - ✅ Bundle UI + connection tests to provide "easy setup"
  - ✅ Automate scheduled task creation
  - ✅ Save down last ID to skip already queried reports.
  - ✅ Single EXE for ease of distribution
  - 🔲 Code signing
    - 🔲 Pending finalisation of code
- ✅ Documentation
  - ✅ Update docs for changes
  - ✅ Finish docs for DB storage
  - ✅ Document running as admin
  - ✅ State what will be removed or will remain after an uninstallation
  - ✅ Document connector setup as an alternative to the API itself
  - ✅ Document SQL storage details (table/columns/permissions/connection string)
  - ✅ Document pagination
  - 🔲 Document .NET/Windows file security, failing to load assemblies, error messages.
    - 🔲 Pending testing on client machine
- ✅ DB backends
  - ✅ Separate MSSQL into its own module.
