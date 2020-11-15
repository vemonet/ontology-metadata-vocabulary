Documentation for the [Ontology Metadata Vocabulary (OMV)](https://www.oeg-upm.net/index.php/en/ontologies/86-omv-ontology/index.html) generated using [Ontospy](http://lambdamusic.github.io/Ontospy)

> See more details about the OMV ontology on the author website: https://www.oeg-upm.net/index.php/en/downloads/75-omv/index.html

![OMV diagram](https://www.oeg-upm.net/images/stories/tecnologias/omv.png)

## Generate documentation

Generate multi page docs for classes and properties in `/docs/`

```bash
wget -O OMV.owl https://www.oeg-upm.net/files/omv/OMV.owl
ontospy gendocs -o docs --type 2 --nobrowser OMV.owl
```