This extension adds the ability to define and apply a default quota when a new user is created.

Alfresco's default quota is unlimited.  This extension sets the default to 2 GB, unless a value is provided at user creation time, which then overrides the default.

The default value is set in a context file and must be defined in bytes.

Currently tested with 3.1.1 - 3.3.2