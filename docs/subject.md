---
layout: default
---


# Slot: subject


connects an association to the subject of the association. For example, in a gene-to-phenotype association, the gene is subject and phenotype is object.

URI: [biolink:subject](https://w3id.org/biolink/vocab/subject)

## Domain and Range

[Association](Association.md) ->  <sub>REQ</sub> [NamedThing](NamedThing.md)

## Parents

 *  is_a: [association slot](association_slot.md)

## Children

 *  [subject](anatomical_entity_to_anatomical_entity_association_subject.md)
 *  [subject](case_to_thing_association_subject.md)
 *  [subject](cell_line_to_disease_or_phenotypic_feature_association_subject.md)
 *  [subject](cell_line_to_thing_association_subject.md)
 *  [subject](chemical_to_chemical_derivation_association_subject.md)
 *  [subject](chemical_to_thing_association_subject.md)
 *  [subject](disease_or_phenotypic_feature_association_to_thing_association_subject.md)
 *  [subject](disease_to_thing_association_subject.md)
 *  [subject](environment_to_phenotypic_feature_association_subject.md)
 *  [subject](functional_association_subject.md)
 *  [subject](gene_regulatory_relationship_subject.md)
 *  [subject](gene_to_disease_association_subject.md)
 *  [subject](gene_to_expression_site_association_subject.md)
 *  [subject](gene_to_gene_association_subject.md)
 *  [subject](gene_to_phenotypic_feature_association_subject.md)
 *  [subject](gene_to_thing_association_subject.md)
 *  [subject](genomic_sequence_localization_subject.md)
 *  [subject](genotype_to_gene_association_subject.md)
 *  [subject](genotype_to_genotype_part_association_subject.md)
 *  [subject](genotype_to_phenotypic_feature_association_subject.md)
 *  [subject](genotype_to_thing_association_subject.md)
 *  [subject](genotype_to_variant_association_subject.md)
 *  [subject](material_sample_derivation_association_subject.md)
 *  [subject](material_sample_to_thing_association_subject.md)
 *  [subject](model_to_disease_mixin_subject.md)
 *  [subject](pairwise_interaction_association_subject.md)
 *  [subject](population_to_population_association_subject.md)
 *  [subject](sequence_feature_relationship_subject.md)
 *  [subject](sequence_variant_modulates_treatment_association_subject.md)
 *  [subject](variant_to_disease_association_subject.md)
 *  [subject](variant_to_phenotypic_feature_association_subject.md)
 *  [subject](variant_to_population_association_subject.md)
 *  [subject](variant_to_thing_association_subject.md)

## Used by

 * [AnatomicalEntityToAnatomicalEntityAssociation](AnatomicalEntityToAnatomicalEntityAssociation.md)
 * [AnatomicalEntityToAnatomicalEntityOntogenicAssociation](AnatomicalEntityToAnatomicalEntityOntogenicAssociation.md)
 * [AnatomicalEntityToAnatomicalEntityPartOfAssociation](AnatomicalEntityToAnatomicalEntityPartOfAssociation.md)
 * [Association](Association.md)
 * [CaseToPhenotypicFeatureAssociation](CaseToPhenotypicFeatureAssociation.md)
 * [CaseToThingAssociation](CaseToThingAssociation.md)
 * [CellLineToDiseaseOrPhenotypicFeatureAssociation](CellLineToDiseaseOrPhenotypicFeatureAssociation.md)
 * [CellLineToThingAssociation](CellLineToThingAssociation.md)
 * [ChemicalToChemicalAssociation](ChemicalToChemicalAssociation.md)
 * [ChemicalToChemicalDerivationAssociation](ChemicalToChemicalDerivationAssociation.md)
 * [ChemicalToDiseaseOrPhenotypicFeatureAssociation](ChemicalToDiseaseOrPhenotypicFeatureAssociation.md)
 * [ChemicalToGeneAssociation](ChemicalToGeneAssociation.md)
 * [ChemicalToPathwayAssociation](ChemicalToPathwayAssociation.md)
 * [ChemicalToThingAssociation](ChemicalToThingAssociation.md)
 * [DiseaseOrPhenotypicFeatureAssociationToThingAssociation](DiseaseOrPhenotypicFeatureAssociationToThingAssociation.md)
 * [DiseaseToPhenotypicFeatureAssociation](DiseaseToPhenotypicFeatureAssociation.md)
 * [DiseaseToThingAssociation](DiseaseToThingAssociation.md)
 * [EntityToPhenotypicFeatureAssociation](EntityToPhenotypicFeatureAssociation.md)
 * [EnvironmentToPhenotypicFeatureAssociation](EnvironmentToPhenotypicFeatureAssociation.md)
 * [ExonToTranscriptRelationship](ExonToTranscriptRelationship.md)
 * [FunctionalAssociation](FunctionalAssociation.md)
 * [GeneAsAModelOfDiseaseAssociation](GeneAsAModelOfDiseaseAssociation.md)
 * [GeneHasVariantThatContributesToDiseaseAssociation](GeneHasVariantThatContributesToDiseaseAssociation.md)
 * [GeneRegulatoryRelationship](GeneRegulatoryRelationship.md)
 * [GeneToDiseaseAssociation](GeneToDiseaseAssociation.md)
 * [GeneToExpressionSiteAssociation](GeneToExpressionSiteAssociation.md)
 * [GeneToGeneAssociation](GeneToGeneAssociation.md)
 * [GeneToGeneProductRelationship](GeneToGeneProductRelationship.md)
 * [GeneToGoTermAssociation](GeneToGoTermAssociation.md)
 * [GeneToPhenotypicFeatureAssociation](GeneToPhenotypicFeatureAssociation.md)
 * [GeneToThingAssociation](GeneToThingAssociation.md)
 * [GenomicSequenceLocalization](GenomicSequenceLocalization.md)
 * [GenotypeToGeneAssociation](GenotypeToGeneAssociation.md)
 * [GenotypeToGenotypePartAssociation](GenotypeToGenotypePartAssociation.md)
 * [GenotypeToPhenotypicFeatureAssociation](GenotypeToPhenotypicFeatureAssociation.md)
 * [GenotypeToThingAssociation](GenotypeToThingAssociation.md)
 * [GenotypeToVariantAssociation](GenotypeToVariantAssociation.md)
 * [MaterialSampleDerivationAssociation](MaterialSampleDerivationAssociation.md)
 * [MaterialSampleToDiseaseOrPhenotypicFeatureAssociation](MaterialSampleToDiseaseOrPhenotypicFeatureAssociation.md)
 * [MaterialSampleToThingAssociation](MaterialSampleToThingAssociation.md)
 * [ModelToDiseaseMixin](ModelToDiseaseMixin.md)
 * [PairwiseInteractionAssociation](PairwiseInteractionAssociation.md)
 * [PopulationToPopulationAssociation](PopulationToPopulationAssociation.md)
 * [SequenceFeatureRelationship](SequenceFeatureRelationship.md)
 * [SequenceVariantModulatesTreatmentAssociation](SequenceVariantModulatesTreatmentAssociation.md)
 * [ThingToDiseaseOrPhenotypicFeatureAssociation](ThingToDiseaseOrPhenotypicFeatureAssociation.md)
 * [TranscriptToGeneRelationship](TranscriptToGeneRelationship.md)
 * [VariantToDiseaseAssociation](VariantToDiseaseAssociation.md)
 * [VariantToPhenotypicFeatureAssociation](VariantToPhenotypicFeatureAssociation.md)
 * [VariantToPopulationAssociation](VariantToPopulationAssociation.md)
 * [VariantToThingAssociation](VariantToThingAssociation.md)