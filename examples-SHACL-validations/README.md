# Demonstration of IDS Information Model Base Application Profiles

The following examples are adapted from an [original example file](Initial-Example-Resource.jsonld) to remove any constraint violations and present a proper demonstration.

- The [basicIDSValidations](../basicIDSValidations) folder contains the basic validations against the models defined in the IDS info model. There are two variants: one covers only local references (prefix: ids), and the other covers external references (prefixes: dcat, dct, time, etc.)
- [extendedValidations](../extendedValidations) contains the extended validations by including minCount 1 for some properties, covering the abovementioned variants.
