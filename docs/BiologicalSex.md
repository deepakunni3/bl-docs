---
layout: default
---


# Class: biological sex




URI: [biolink:BiologicalSex](https://w3id.org/biolink/vocab/BiologicalSex)

![img](images/BiologicalSex.png)

## Parents

 *  is_a: [Attribute](Attribute.md) - A property or characteristic of an entity. For example, an apple may have properties such as color, shape, age, crispiness. An environmental sample may have attributes such as depth, lat, long, material.

## Children

 * [GenotypicSex](GenotypicSex.md) - An attribute corresponding to the genotypic sex of the individual, based upon genotypic composition of sex chromosomes.
 * [PhenotypicSex](PhenotypicSex.md) - An attribute corresponding to the phenotypic sex of the individual, based upon the reproductive organs present.

## Referenced by class

 *  **[Association](Association.md)** *[sex qualifier](sex_qualifier.md)*  <sub>OPT</sub>  **[BiologicalSex](BiologicalSex.md)**

## Attributes


### Inherited from attribute:

 * [has attribute type](has_attribute_type.md)  <sub>OPT</sub>
    * Description: connects an attribute to a class that describes it
    * range: [OntologyClass](OntologyClass.md)
    * inherited from: [Attribute](Attribute.md)
    * in subsets: (samples)
 * [has quantitative value](has_quantitative_value.md)  <sub>0..*</sub>
    * Description: connects an attribute to a value
    * range: [QuantityValue](QuantityValue.md)
    * inherited from: [Attribute](Attribute.md)
    * in subsets: (samples)
 * [has qualitative value](has_qualitative_value.md)  <sub>OPT</sub>
    * Description: connects an attribute to a value
    * range: [NamedThing](NamedThing.md)
    * inherited from: [Attribute](Attribute.md)
    * in subsets: (samples)

### Inherited from named thing:

 * [id](id.md)  <sub>REQ</sub>
    * Description: A unique identifier for a thing. Must be either a CURIE shorthand for a URI or a complete URI
    * range: [IdentifierType](IdentifierType.md)
    * inherited from: [NamedThing](NamedThing.md)
    * in subsets: (translator_minimal)
 * [name](name.md)  <sub>REQ</sub>
    * Description: A human-readable name for a thing
    * range: [LabelType](LabelType.md)
    * inherited from: [NamedThing](NamedThing.md)
    * in subsets: (translator_minimal)
 * [category](category.md)  <sub>1..*</sub>
    * Description: Name of the high level ontology class in which this entity is categorized. Corresponds to the label for the biolink entity type class. In a neo4j database this MAY correspond to the neo4j label tag
    * range: [IriType](IriType.md)
    * inherited from: [NamedThing](NamedThing.md)
    * in subsets: (translator_minimal)
