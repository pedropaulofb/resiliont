# ResiliOnt: The Resilience Core Ontology 

<p align="center">
  <img src="https://raw.githubusercontent.com/pedropaulofb/resiliont/main/resources/logos/resiliont-logo-06.png" alt="Logo" style="width:500px">
</p>

This repository hosts ResiliOnt, a core ontology that aims to provide a clear and robust definition of resilience by leveraging the Unified Foundational Ontology (UFO) and OntoUML. By addressing the ambiguities and inconsistencies in existing definitions of resilience, ResiliOnt seeks to ensure interoperability and clarity across various domains and facilitate interdisciplinary research.

## Related Ontologies

ResiliOnt leverages concepts from the [Common Ontology of Value and Risk (COVER)](https://github.com/unibz-core/value-and-risk-ontology) and the Capabilities Ontology. These ontologies provide the baseline for understanding concepts used in ResiliOnt, such as the relationships between capabilities and concepts like vulnerabilities and threats.

- [**COVER**](https://www.academia.edu/download/82803282/the_common_ontology_of_value_and_risk_2018.pdf): Introduces key concepts such as Objects at Risk, Threat Events, and Vulnerabilities, which are integral to modeling resilience. For more details, please refer to:
  - Sales, Tiago Prince, Baião, Fernanda, and others. "The Common Ontology of Value and Risk." In *Conceptual Modeling*, Springer International Publishing, Cham, 2018, pp. 121-135.

- [**Capabilities Ontology**](https://nemo.inf.ufes.br/wp-content/papercite-data/pdf/a_system_core_ontology_for_capability_emergence_modeling_2023.pdf): Explores the nature of capabilities and their enabling and disabling relationships, contributing to a deeper understanding of how resilience can be achieved and observed. For more details, please refer to:
  - Calhau, Rodrigo F., Prince Sales, Tiago, and others. "A System Core Ontology for Capability Emergence Modeling." In *Enterprise Design, Operations, and Computing - 27th International Conference, EDOC 2023, Groningen, The Netherlands, October 30 - November 3, 2023, Proceedings*, Springer, 2023, pp. 3-20. DOI: 10.1007/978-3-031-46587-1_1.

## Contents

ResiliOnt is found in the `ontouml/` folder. The files there contained are:

- **vpp**: The editable Visual Paradigm project file containing the OntoUML ontology model and UML Object Diagrams with examples of possible instantiations.
- **json**: The OntoUML model serialized to JSON using [OntoUML-Schema](https://w3id.org/ontouml/schema).
- **images/**: Images of the OntoUML model and UML Object diagrams illustrating examples of the ontology's instantiation.
- **archive/**: Old versions of ResiliOnt.

## How to Cite

If you use this work in your research, please cite it as follows:

**APA Style Citation:**

Barcelos, P. P. F., Calhau, R. F., Oliveira, Í., Sales, T. P., Gailly, F., Poels, G., & Guizzardi, G. (2024). *Ontological foundations of resilience*. In *Proceedings of the 43rd International Conference on Conceptual Modeling: Conceptual Modeling, AI, and Beyond* (ER 2024). Pittsburgh, Pennsylvania, USA, October 28-31.

**BibTeX Citation:**

```bibtex
@inproceedings{barcelos2024ontological,
title={Ontological foundations of resilience},
author={Barcelos, Pedro Paulo F. and Calhau, Rodrigo F. and Oliveira, Ítalo and Sales, Tiago Prince and Gailly, Frederik and Poels, Geert and Guizzardi, Giancarlo},
booktitle={Proceedings of the 43rd International Conference on Conceptual Modeling: Conceptual Modeling, AI, and Beyond (ER 2024)},
year={2024},
address={Pittsburgh, Pennsylvania, USA},
month={October 28-31}
}
```

## How to Contribute

Contributions are welcomed! If you would like to contribute, you can create Pull Requests (PRs) or open issues in the repository.

## Authors

This work was developed by researchers from the [Business Informatics Group of Ghent University, Belgium](https://ugent-businessinformatics.github.io/) and the [Semantics, Cybersecurity & Services Group at the University of Twente, Netherlands](https://www.utwente.nl/en/eemcs/scs/).

<table>
  <tr>
    <td><strong>Pedro Paulo F. Barcelos</strong></td>
    <td>
      <a href="https://orcid.org/0000-0003-2736-7817"><img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID" width="20"/></a>
      <a href="https://github.com/pedropaulofb"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" width="20"/></a>
      <a href="https://www.linkedin.com/in/pedro-paulo-favato-barcelos/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" width="20"/></a>
    </td>
  </tr>
  <tr>
    <td><strong>Rodrigo F. Calhau</strong></td>
    <td>
      <a href="https://orcid.org/0009-0006-6051-2165"><img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID" width="20"/></a>
      <a href="https://github.com/rfcalhau"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" width="20"/></a>
      <a href="https://www.linkedin.com/in/rodrigo-f-calhau-a6663776/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" width="20"/></a>
    </td>
  </tr>
  <tr>
    <td><strong>Ítalo Oliveira</strong></td>
    <td>
      <a href="https://orcid.org/0000-0002-2384-3081"><img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID" width="20"/></a>
      <a href="https://github.com/italojsoliveira"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" width="20"/></a>
      <a href="https://www.linkedin.com/in/%C3%ADtalo-oliveira-800923162/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" width="20"/></a>
    </td>
  </tr>
  <tr>
    <td><strong>Tiago Prince Sales</strong></td>
    <td>
      <a href="https://orcid.org/0000-0002-5385-5761"><img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID" width="20"/></a>
      <a href="https://github.com/tgoprince"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" width="20"/></a>
      <a href="https://www.linkedin.com/in/tiago-sales/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" width="20"/></a>
    </td>
  </tr>
  <tr>
    <td><strong>Frederik Gailly</strong></td>
    <td>
      <a href="https://orcid.org/0000-0003-0481-9745"><img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID" width="20"/></a>
      <a href="https://github.com/fgailly"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" width="20"/></a>
      <a href="https://www.linkedin.com/in/fgailly/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" width="20"/></a>
    </td>
  </tr>
  <tr>
    <td><strong>Geert Poels</strong></td>
    <td>
      <a href="https://orcid.org/0000-0001-9247-6150"><img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID" width="20"/></a>
      <a href="https://github.com/geertpoels"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" width="20"/></a>
      <a href="https://www.linkedin.com/in/geert-p-039198287/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" width="20"/></a>
    </td>
  </tr>
  <tr>
    <td><strong>Giancarlo Guizzardi</strong></td>
    <td>
      <a href="https://orcid.org/0000-0002-3452-553X"><img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID" width="20"/></a>
      <a href="https://www.linkedin.com/in/giancarlo-guizzardi/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" width="20"/></a>
    </td>
  </tr>
</table>
