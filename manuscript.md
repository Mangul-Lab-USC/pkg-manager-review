---
author-meta:
- Sharon Waymost
bibliography:
- content/manual-references.json
date-meta: '2020-07-09'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="Review of Package Managers for Bioinformatics Software Distribution" />

  <meta name="citation_title" content="Review of Package Managers for Bioinformatics Software Distribution" />

  <meta property="og:title" content="Review of Package Managers for Bioinformatics Software Distribution" />

  <meta property="twitter:title" content="Review of Package Managers for Bioinformatics Software Distribution" />

  <meta name="dc.date" content="2020-07-09" />

  <meta name="citation_publication_date" content="2020-07-09" />

  <meta name="dc.language" content="en-US" />

  <meta name="citation_language" content="en-US" />

  <meta name="dc.relation.ispartof" content="Manubot" />

  <meta name="dc.publisher" content="Manubot" />

  <meta name="citation_journal_title" content="Manubot" />

  <meta name="citation_technical_report_institution" content="Manubot" />

  <meta name="citation_author" content="Sharon Waymost" />

  <meta name="citation_author_institution" content="CS Dept, UCLA" />

  <meta name="citation_author_orcid" content="0000-0003-1176-5386" />

  <link rel="canonical" href="https://sbpw.github.io/pkg-manager-review/" />

  <meta property="og:url" content="https://sbpw.github.io/pkg-manager-review/" />

  <meta property="twitter:url" content="https://sbpw.github.io/pkg-manager-review/" />

  <meta name="citation_fulltext_html_url" content="https://sbpw.github.io/pkg-manager-review/" />

  <meta name="citation_pdf_url" content="https://sbpw.github.io/pkg-manager-review/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://sbpw.github.io/pkg-manager-review/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://sbpw.github.io/pkg-manager-review/v/5a6920b06155d01d8856355993485007cbb7dc74/" />

  <meta name="manubot_html_url_versioned" content="https://sbpw.github.io/pkg-manager-review/v/5a6920b06155d01d8856355993485007cbb7dc74/" />

  <meta name="manubot_pdf_url_versioned" content="https://sbpw.github.io/pkg-manager-review/v/5a6920b06155d01d8856355993485007cbb7dc74/manuscript.pdf" />

  <meta property="og:type" content="article" />

  <meta property="twitter:card" content="summary_large_image" />

  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />

  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />

  <meta name="theme-color" content="#ad1457" />

  <!-- end Manubot generated metadata -->'
keywords:
- package managers
- containerization
- distribution
- docker
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: Review of Package Managers for Bioinformatics Software Distribution
...






<small><em>
This manuscript
([permalink](https://sbpw.github.io/pkg-manager-review/v/5a6920b06155d01d8856355993485007cbb7dc74/))
was automatically generated
from [sbpw/pkg-manager-review@5a6920b](https://github.com/sbpw/pkg-manager-review/tree/5a6920b06155d01d8856355993485007cbb7dc74)
on July 9, 2020.
</em></small>

## Authors



+ **Sharon Waymost**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0003-1176-5386](https://orcid.org/0000-0003-1176-5386)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [sbpw](https://github.com/sbpw)<br>
  <small>
     CS Dept, UCLA
  </small>



## Abstract {.page_break_before}




## Introduction {.page_break_before}




## Discussion {.page_break_before}

### Existing problems with software distribution and installation
- root access limitations
- reproducibility of findings
- version conflicts
- dependency resolution

### Definitions and explanations of distribution system types
- package managers
-- definition
-- benefits for the developer
--- mature technology - higher degree of familiarity
--- allows dependency specification (including versions)
--limitations for the developer
--- can't always use to install missing dependencies for end-user
-- benefits for the end-user
--- package size is minimal (dependencies aren't duplicated)
--- installs missing dependencies
-- limitations for the end-user
--- not always accessible (unless admin user)
--- can't install multiple versions of same software
- containerization
-- definition
-- "Why containers?" Comic
-- benefits for the developer
--- include specific versions of dependencies
--- known running environment
---- fewer test variables
---- reproducibility of results
-- limitations for the developer
--- learn a new system instead of focusing on research
-- benefits for the end-user
--- no installation (except possible runtime)
--- no dependency issues
--- sandbox provides computer system security
-- limitations for the end-user
--- container size
--- duplication of dependencies
--- root access requirement to install runtime
--- configuration in cluster
- centralized repositories
-- definition
-- benefits
--- known download site
--- hosting is taken of
-- limitations
--- repo specific restrictions

## Glossary {.page_break_before}




## Acknowledgements {.page_break_before}




## Author Contributions {.page_break_before}




## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>


## Tables {.page_break_before}

| Distribution System Name | URL | Publication | Type | Licensing |
| :----------------------- | :-- | :---------- | :--- | :-------- |
| AppImage | appimage.org | something | blah | whatever |
