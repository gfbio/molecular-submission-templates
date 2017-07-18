# Molecular Submission Templates

This repository contains csv templates to prepare submission of molecular data to the appropriat archives (ENA,PANGAEA) via the GFBio brokerage service.

## Status
**In production use.**

Please post questions, help requests or bug reports to the [issue tracker](https://github.com/gfbio/molecular-submission-templates/issues).

## Template Description

* You can find three templates in the repository - samples, mixs, full (combination of the previous two). 
* Currently **only the [full template](https://raw.githubusercontent.com/gfbio/molecular-submission-templates/excel-compatible/full_template.csv) is supported** by the GFBio molecular brokerage service.
* Detailed description of the template fields is available [here](https://github.com/gfbio/molecular-submission-templates/wiki/Template-Description).

## Template Usage
* You can upload the [*full template*](https://raw.githubusercontent.com/gfbio/molecular-submission-templates/excel-compatible/full_template.csv) via the GFBio [molecular submission interface](www.gfbio.org/data/submit/molecular) to start a molecular submission.
* We accept either comma (,), tab (\t), or semicolon (;) as field separators, but only choose one and make sure you do not use that character within the content of the fields (e.g. if you spearate the fields wiht a comma, do not use commas in the sample description).
* Only the first 10 are strictly mandatory for starting the submission. Our curation team will contact you in case problems occur.
* You can add extra fields at the end of the template.
