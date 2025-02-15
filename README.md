# Gender, Sex, and Sexual Orientation

The Gender, Sex, and Sexual Orientation (GSSO) ontology is an ontology which includes a vast amount of information related to gender identity, gender expression, romantic identity, sexual identity, sexual orientation, sexual behavior, sexual abuse, and various related topics. Its emphasis is on a multidisciplinary and intersectional approach to these topics.

## Usage

### API Access

The API for the GSSO can be accessed as part of the NCBO BioPortal's API. For more information, consult the NCBO BioPortal API documentation [here](http://data.bioontology.org/documentation).

#### Getting Instances for a Class

In order to get instances for a given class, the BioPortal concept ID should be created from the class ID, for example:

```
http://purl.bioontology.org/ontology/GSSO/000047
```

Becomes:

```
http%3A%2F%2Fpurl.bioontology.org%2Fontology%2FGSSO%2F000047
```

The full URL for access is thus:

```
http://data.bioontology.org/ontologies/GSSO/classes/http%3A%2F%2Fpurl.bioontology.org%2Fontology%2FGSSO%2F000047/instances
```

Note that this method will only grab instances from the current class, not from subclasses; i.e. the following:

```
http://data.bioontology.org/ontologies/GSSO/classes/http%3A%2F%2Fpurl.bioontology.org%2Fontology%2FGSSO%2F000140/instances
```

Will pull LGBTQ slang, but not transgender slang.

#### Getting GSSO from Homosaurus

TBD

#### Getting GSSO from LCSH

TBD

#### Getting GSSO from LCC

Getting the entry for "RC571" is implemented as follows:

```
http://data.bioontology.org/search?q=RC571&ontologies=GSSO&also_search_properties=true
```

#### Getting GSSO from Dewey Decimal System

TBD

## Versioning

Note that versions with "rdf_xml" in the title are in RDF/XML format, while those without utilize Manchester OWL syntax.

Further, note that PURLs utilize the "1.0.1" syntax as to be backwards compatible with any of the 1.0.1 releases. The 1.0.0 release is not forward or backward compatible at the present time. It is recommended that users utilize 2.0.0.

* 1.0.0 (24 June 2019)
* 1.0.1a (11 September 2019)
* 1.0.1b (12 September 2019)
* 1.0.1c (13 September 2019)
* 1.0.1d (13 September 2019)
* 1.0.1e (13 September 2019)
* 2.0.0 (18 June 2020)

## Contributing

Please feel free to contribute! If there is a term or terms that include unsatisfactory information, broken links, derogatory terminology that is not appropriately marked, please contact us!

A very basic search/browse interface of version 1.0.0 is located [here](http://homepages.uc.edu/~kronkcj/gsso/) for the time being.

An alpha version of 1.0.1 is also available on the NCBO BioPortal [here](http://bioportal.bioontology.org/ontologies/GSSO).

The beta version 2.0.0. is available at the same URL.

## Authors

* Clair Kronk (clair.kronk@gmail.com)

## License

This project is currently bound by the Apache 2.0 License. All mapped ontologies within GSSO are within Creative Commons, but may require separate requirements. Please check with their respective creators before utilizing.

## Publications

* Kronk C, Dexheimer J. "Development of the Gender, Sex, and Sexual Orientation Ontology: Evaluation and Workflow." _Journal of the American Medical Informatics Association_. 2020. DOI: [10.1093/jamia/ocaa061](https://doi.org/10.1093/jamia/ocaa061). PMID: [32548638](https://pubmed.ncbi.nlm.nih.gov/32548638/).
* Kronk C, Tran G, Wu D. "Creating a Queer Ontology: Introduction of the Gender, Sex, and Sexual Orientation (GSSO) Ontology." _MEDINFO 2019: Health and Wellbeing e-Networks for All_. 2019:264. DOI: [10.3233/SHTI190213](https://doi.org/10.3233/SHTI190213). PMID: [31437915](https://www.ncbi.nlm.nih.gov/pubmed/31437915).

## Acknowledgments

* Judith W. Dexheimer
* Giao Q. Tran
* Danny T. Y. Wu