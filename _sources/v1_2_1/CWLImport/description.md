The schema validation of the CWL will not itself perform the '$import' to resolve and validate its contents.
Therefore, the complete schema will not be validated entirely, and could still be partially malformed.
To ensure proper and exhaustive validation of a CWL definition with this schema, all '$import' directives
should be resolved and extended beforehand.
