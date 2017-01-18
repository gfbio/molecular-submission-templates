# Molecular Submission Templates

This repository contains csv templates to prepare submission of molecular data to the appropriat archives (ENA,PANGAEA) via the GFBio brokerage service.

## Status

Under active development! Frequent changes are expected at this stage, please always refer to the [latest release](https://github.com/gfbio/molecular-submission-templates/releases/latest). Documentation will be extended and improved ASAP.
In the meantime, do no hesitate to post questions, help requests or bug reports to the [issue tracker](https://github.com/gfbio/molecular-submission-templates/issues).

## Template Description

* There are currently three templates - samples, mixs, full (combination of the previous two). The **samples** template refers to general information about the samples (title, taxonomy, sequencing procedure), while the **mixs** template refers to metadata according to the MIxS community standard.

* The templates are comma separated (CSV) and all fields are quoted
* The first 10 fields of the **samples** template are mandatory
* All fields of the **mixs** template are required in order to comply to the MIxS standard. In some cases additional infromation might be required - you will be contacted by our curatorial team if that applies to you.
* Detailed explanation of each field can be found in the [wiki](https://github.com/gfbio/molecular-submission-templates/wiki).
* You can add extra fields at the end of both the **mixs** and the **full** template. We will provide a list of environmental paramteres that can be recorded there. You can also include any kind of measurements - if our software cannot recognize the headers, these will be ignored.

## Template Usage
* Once the latets version of the GFBio brokerage system for molecular data has been released (planned for beginning of February 2017), you will be able to upload one or more of the templates via the GFBio portal [molecular submission interface](www.gfbio.org/data/submit/molecular).
* For the moment we recommend to always use the [latest release](https://github.com/gfbio/molecular-submission-templates/releases/latest) of the **full** template and fill out as many of the fields as possible (only the first 10 are strictly mandatory).
