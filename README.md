# docsync
Logging, notification and digest bot for syncing docs with code

Create a [Swagger](https://swagger.io/)-type syncronization workflow for maintaining a current and rigorous internal knowledgebase.

Documentation example: http://editor2.swagger.io/#!/

Non-API software companies may develop API-like modules (or, internal APIs) that require syncronized and up-to-date documentation for teams to be able to collaborate effectively.

Open API Initiative is an industry movement to standardize practices to be vendor-neutral. In a smaller environment, this tool would be a company movement to standardize practices to be team-neutral.

The tool will do the following:

1. Allow user to tag documents with code base ID
1. Log changes to code base as they occur
1. Compile an up-to-date log when development teams complete their sprint
1. Allow developer to add comments about larger architectural design changes
1. Compile a list of documents affected by code base

The following human tasks remain:

1. Tagging documents with appropriate code base IDs
1. **LABOR INTENSIVE:** Evaluating whether changes impact the functionality of other tools (and therefore requires document update)
1. **LABOR INTENSIVE:** Transforming the code changes into documentation
1. **LABOR INTENSIVE:** Sanity-checking the code changes to make sure it is functionally accurate
1. Publishing the changes in a clean, search-friendly environment
1. Creating and diagramming maps of compiled docs that refer to single-source modules
1. Feeding continued optimizations into the publishing tool

Also consider how to auto-generate templated API definition files as a fillable inventory form.
