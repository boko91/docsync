# docsync
Logging, notification and digest bot for syncing docs with code

Create a [Swagger](https://swagger.io/)-type syncronization workflow for maintaining a current and rigorous internal knowledgebase.

Non-API software companies may develop API-like modules (or, internal APIs) that require syncronized and up-to-date documentation for teams to be able to collaborate effectively.

The optimal tool will do the following:

1. Allow user to tag documents with code base ID
1. Log changes to code base as they occur
1. Compile an up-to-date log when development teams complete their sprint
1. Allow developer to add comments about larger architectural design changes
1. Compile a list of documents affected by code base

The human input into documentation remains the following:

1. Tagging documents with appropriate code base IDs
1. **Labor Intensive:** Evaluating whether changes impact the functionality of other tools (and therefore requires document update)
1. **Labor Intensive:** Translate and sanity-check the changes into the documentation
1. Publish the changes in a clean, search-friendly environment
1. Create and diagram maps of compiled docs that refer to single-source modules
1. Feed continued optimizations into the publishing tool

Also consider how to auto-generate reference API docs in the form of a fillable inventory of parts.
