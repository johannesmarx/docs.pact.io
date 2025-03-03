---
title: Planned breaking changes in version 3.0
---

* Rename `pacticipant` to `application`
* Removal of deprecated relations without a pb
* Remove option to order by semantic version.
* Rename failed to failure
* Make nullable foreign keys not nullable
* Do not allow array JSON request bodies (Beth can't remember why this is a thing now)
* Drop support for case-insensitive resource names
* Drop support for modifying contracts?
* Disallow modification of verification results
* Drop support for proxy badge provider mode
* Remove redundant webhook creation endpoints
* Remove deprecated pact publication endpoints
* Make the providerVersionBranch not allowed to be blank in PactsForVerificationJSONQuerySchema
* Update all error responses to use problem+json
* Make PUT/PATCH consistent for all resources
* Do not allow blank values in matrix query - it makes it hard to tell if the user has intentionally submitted a blank value or if the client always sets a value
* Add pacticipant name to contract publish endpoint URL
* Remove deprecated JSON in pacticipants endpoint
* Paginate all collection endpoints by default
