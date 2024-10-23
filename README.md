# The VIVO Ontology

The VIVO Ontology is used to represent scholarship.

## A note about licensing

The VIVO Ontology is in the public domain, and free to use. The VIVO Ontology file includes terms from other ontologies. These ontologies
may have their own licenses and may not be in the public domain. While the VIVO Project has made every effort to ascertain the
licenses of each of the terms it uses, this has not always been possible. Some of these terms may have licenses that prevent
their use in some settings.

## A note about development

The VIVO Ontology and related *VIVO ontologies* are under active development by the [VIVO Ontology Interest Group](https://wiki.lyrasis.org/display/VIVO/Ontology+Interest+Group) of the [VIVO Project](https://vivo.lyrasis.org).
The group holds regular meetings and is open to all. Please consider participating.

VIVO Ontologies is an open source community. All are welcome to open issues, participate in discussions, and generate pull reqeuests.

You can contribute using the fork, branch and pull model. Helpful descriptions of the process are available [on the VIVO wiki](https://wiki.lyrasis.org/display/VIVO/Contributing+code+with+a+fork%2C+branches%2C+and+pull+requests).

## Editing Policy
Manual structural changes can result in inconsistencies. Editing and saving the file with ontology editors or IDEs can lead to new serialisations, which creates verbose diffs. This makes reviewing the changes very difficult. Therefore we recommend the following approaches for editing:

* For **large modifications**: Use [Protégé](https://github.com/protegeproject/protege-distribution/releases) (Version 5.6.4) to ensure consistency. **Re-serialize the ontology** with `[robot](http://robot.obolibrary.org/)` before submitting a pull request. This helps to minimize differences and fosters the review.
* For **small modifications** (e.g. minor annotations, small additions, or typos): Direct manual editing using a text editor is permitted. In these cases, re-serialization is **not required**. Small changes are less likely to impact the structural consistency or to lead to verbose diffs.

**Updates:**  
Updates to approved tools and versions will be posted here.

## Releases
### Semantic Versioning
This ontology adheres to the principles of Semantic Versioning (SemVer) for managing its releases. Semantic Versioning provides a standardized approach for versioning ontologies, allowing users to quickly understand the scope of changes between versions.

### Versioning Scheme
- Major Release: Indicates substantial changes, such as alterations to the ontology's core structure or significant shifts in semantics.
- Minor Release: Introduces new concepts or properties in a manner consistent with existing ontology structures.
- Patch Release: Includes bug fixes or minor updates without modifying the ontology's core structure or semantics.

### Latest ontology file
The latest version of the ontology file can be found at:
https://raw.githubusercontent.com/vivo-ontologies/vivo-ontology/master/vivo.owl

### Release versions
Release versions be found at:
https://github.com/vivo-ontologies/vivo-ontology/releases
