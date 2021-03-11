# synapse-formation-templates

This project hopes to house `yaml` or `json` templates that will leverage [synapseformation](https://github.com/Sage-Bionetworks/synapseformation) to create the Synapse resources required for a particular Synapse project.

## Templates

- Inital template
    - [sfn_schema.json](templates/sfn_schema.json) - This is the schema file that describes all the components that a json configuration can have. A json template could be validated against this schema file by using existing tools like [jsonschema](https://github.com/Julian/jsonschema)
    - [example_template.json](templates/example_template.json) - This is an example template for a Synapse project that creates a `Project`, `Folders`, `Teams`, `ACL`, and etc...  This is what would be the input to `synapseformation` so that Synapse resources could be created.
