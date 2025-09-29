Validate that the 'default' value, if specified, is of same type as the CWL 'type'.
This avoids over-accepting anything that does not match the intended type.
However, validation limits itself to data literals and arrays.
Nested type and multi-type definitions will validate against 'Any'.
