Disables read queries for a connection to a Valkey Cluster replica node.

Read queries against a Valkey Cluster replica node are disabled by default,
but you can use the `READONLY` command to change this behavior on a per-
connection basis. The `READWRITE` command resets the readonly mode flag
of a connection back to readwrite.
