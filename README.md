# STRIDE_German_Regulation_LV_Smart_Grid
In this repository we provide the documents created in the STRIDE based threatanalysis of the german regulations describung the low voltage smart grid in germany.

# Threatmodel
In order to use the threatmodel you need to utilize OWASPs [Threatdragon](https://www.threatdragon.com), there you can load the `Smart_Grid_Threat_Model.json` and view the entire threat model.
An alternative are the images in the `images` directory. Note, however, that the images do not include the threats and mitigations that are included in the dataflows and components of the entire threatmodel.

# Structure Overview
```text
├── components
│   ├── components_with_regulations.csv
│   ├── components_with_regulations.md
│   ├── components_with_threat_mitigation_notes.csv
│   ├── components_with_threat_mitigation_notes.md
│   └── components.md
├── dataflows
│   ├── dataflow_protocol_mitigation.csv
│   ├── dataflow_protocol_mitigation.md
│   ├── dataflow_protocol_threats.csv
│   ├── dataflow_protocol_threats.md
│   ├── dataflows_threat_level.md
│   └── dataflows.md
├── images
│   ├── Dataflow_Diagram_Drawing_Small.png
│   ├── Dataflow_Diagram_Drawing_Small.svg
│   ├── Dataflowdiagram_Mitigation_Status.png
│   ├── Dataflowdiagram_Mitigation_Status.svg
│   ├── Dataflowdiagram.png
│   └── Dataflowdiagram.svg
├── LICENSE
├── mitigation_standards
│   ├── general_mitigation_standards.csv
│   ├── general_mitigation_standards.md
│   └── network_segmentations.md
├── README.md
├── Smart_Grid_Threat_Model.json
└── threats
    ├── threat_types_mitigation.png
    ├── threat_types_mitigation.svg
    └── threats.md
```
