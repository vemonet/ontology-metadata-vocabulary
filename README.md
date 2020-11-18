**Browse the Ontology Metadata Vocabulary (OMV) documentation website at https://vemonet.github.io/ontology-metadata-vocabulary 📖**

Documentation for the [Ontology Metadata Vocabulary (OMV)](https://www.oeg-upm.net/index.php/en/ontologies/86-omv-ontology/index.html) generated using [Ontospy](http://lambdamusic.github.io/Ontospy)

The OWL ontology file for OMV can be found here: https://www.oeg-upm.net/files/omv/OMV.owl

## Generate documentation

The documentation website can be [generated using a GitHub Action](https://github.com/vemonet/ontology-metadata-vocabulary/blob/main/.github/workflows/generate-docs.yml).

Generate multi page docs for classes and properties in `/docs/`:

1. Install [Ontospy](http://lambdamusic.github.io/Ontospy):

```bash
pip install ontospy[FULL]
```

2. Download OMV.owl file and generate HTML for the ontology:

```bash
wget -O OMV.owl https://www.oeg-upm.net/files/omv/OMV.owl
```

3. Generate multi page HTML documentation for the ontology:

```bash
ontospy gendocs -o docs --type 2 --nobrowser OMV.owl
```

You can also try out other type of documentation (graph, single page, etc):

```bash
ontospy gendocs -o docs --nobrowser OMV.owl
```

## OMV diagram

See more details about the OMV ontology on the author website: https://www.oeg-upm.net/index.php/en/downloads/75-omv/index.html

![OMV diagram](https://www.oeg-upm.net/images/stories/tecnologias/omv.png)
