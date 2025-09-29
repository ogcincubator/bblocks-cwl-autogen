Technically should be minimum=1, but fractional for scheduling algorithms are allowed.
There is no way to distinguish between float/long simultaneously in JSON schema (multi-match oneOf).
Therefore, only validate that it is greater than zero.
