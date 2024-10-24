## What is a Kubernetes ConfigMap used for?
   * We know that ConfigMap is an API object that is mainly used to store non-confidential data or configurations for other objects to use.
Most of the Kubernetes objects have a specification, but ConfigMap has data and binary data fields. Key value pairs are accepted by these fields as values.
The data field is used to store UTF-8 strings, while the binary data field is used to store binary data as base64-encoded strings.
   * A valid DNS subdomain name should be given to ConfigMap. The key value that is recorded in the data field and the key value in the binaryData field cannot both be the same.
