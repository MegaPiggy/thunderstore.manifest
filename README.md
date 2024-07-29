# Thunderstore Manifest
This is a community maintained repository to host documentation for Thunderstore manifests.

Do note: you **cannot** copy and paste the example files. The `$schema` property uses a relative path and will break if it is moved outside of this repository. Please just copy the example below.

## How to use the schemas
First, you need an editor that supports JSON Schema v7. I personally recommend Visual Studio Code.  
Once you have an editor, simply create a new JSON file with the `$schema` property. It should point to a schema file hosted in this repository. For example, for r2modman-flavored manifest v1:

```json
{
  "$schema": "https://raw.githubusercontent.com/malicean/thunderstore.manifest/main/v1/r2modman/schema.json"
}
```

You should notice that your editor now has IntelliSense, as well as warnings for missing or malformed JSON properties. Enjoy!
