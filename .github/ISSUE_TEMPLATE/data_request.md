---
name: Data Request
about: Suggest a data set for ingestion in the platform
title: '[Data]:'
labels: MSFC
assignees: freitagb, wildintellect

---
title: Data Request Form
form: 
    name: Data Request Form
    fields:
        - name: name
            label: Dataset Name
            description: What is the name of the data requested?
            placeholder:
            type: text
            validate:
                required: true
        - name: description
            label: Dataset Description     
            description: Please provide a short description of the data.
            placeholder:
            type: text
            validate:
                required: true
        - name: requestor
            label: Requestor Name/Affiliation
            description: What is your name and research affiliation?
            placeholder:
            type: text
            validate:
                required: true
        - name: method
            label: Platform/Instrument/Method
            description: What sensor and/or platform is used to collect the data?
            placeholder:
            type: text
            validate:
                required: true
        - name: doi
            label: URL or DOI to Dataset Description
            description:
            placeholder:
            type: text
            validate:
                required: true
        - name: url
            label: URL to Download or Access Data
            description:
            placeholder:
            type: text
            validate:
                required: true
        - name: license
            label: Data License
            description: Is the data openly available? Please list the license if you know it.
            placeholder: eg. CC-BY
            type: text
            validate:
                required: false
        - name: use
            label: Intended Science Use Case
            description: Please describe how you intend to use the data, or the expected relevance to MAAP users.
            placeholder:
            type: textarea
            validate:
                required: true
        - name: size
            label: Approximate Size of Data
            description: please estimate how many GB/TB/PB the data is.
            placeholder:
            type: text
            validate:
                required: false
        -name: additional info
            label: Additional Information
            description: Any additional info you think is relevant, possibly including spatial or temporal subset if applicable.
            placeholder:
            type: textarea
            validate:
                required: false
