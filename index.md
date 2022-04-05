---
layout: lesson
root: .
bioschemas:
  "@context": "https://schema.org",
  "@id": "https://cloud-span.github.io/prenomics00-intro/",
  "@type": "TrainingMaterial",
  about: [
    {
      "@id": "http://edamontology.org/topic_3372",
      "@type": "Thing"
    },
    {
      "@id": "http://edamontology.org/topic_0622",
      "@type": "Thing"
    }
  ],
  abstract: "Prenomics prepares learners for the Cloud-SPAN Genomics course. It teaches the basics of command-line programming, including: (1) file directory structure, (2) use of command-line utilities to connect to and use cloud computing and storage resources and (3) basic shell commands for file navigation and basic script writing.",
  audience: [
    {
      "@id": "Graduates",
      "@type": "Audience"
    },
    {
      "@id": "PhD students",
      "@type": "Audience"
    },
    {
      "@id": "Post-doctorates",
      "@type": "Audience"
    }
  ],
  author: [
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "dct:conformsTo": "https://bioschemas.org/profiles/Person/0.2-DRAFT-2019_07_19",
      "description": [
        "ORCID: 0000-0002-1358-8275"
      ],
      "name": "Emma Rand"
    },
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "dct:conformsTo": "https://bioschemas.org/profiles/Person/0.2-DRAFT-2019_07_19",
      "description": [
        "ORCID: 0000-0001-9447-7421"
      ],
      "name": "James Chong"
    },
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "dct:conformsTo": "https://bioschemas.org/profiles/Person/0.2-DRAFT-2019_07_19",
      "description": [
        "ORCID: 0000-0001-8332-7196"
      ],
      "name": "Sarah Forrester"
    },
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "dct:conformsTo": "https://bioschemas.org/profiles/Person/0.2-DRAFT-2019_07_19",
      "description": [
        "ORCID: 0000-0001-9548-3110 "
      ],
      "name": "Annabel Cansdale"
    },
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "dct:conformsTo": "https://bioschemas.org/profiles/Person/0.2-DRAFT-2019_07_19",
      "description": [],
      "name": "Jorge Buenabad-Chavez"
    },
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "dct:conformsTo": "https://bioschemas.org/profiles/Person/0.2-DRAFT-2019_07_19",
      "description": [
        "ORCID: 0000-0003-4800-3422"
      ],
      "name": "Evelyn Greeves"
    },
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "dct:conformsTo": "https://bioschemas.org/profiles/Person/0.2-DRAFT-2019_07_19",
      "description": [
        "ORCID: 0000-0002-4914-5150"
      ],
      "name": "Emma Barnes"
    },
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "dct:conformsTo": "https://bioschemas.org/profiles/Person/0.2-DRAFT-2019_07_19",
      "description": [
        "ORCID: 0000-0002-8876-7606"
      ],
      "name": "Neil Chue-Hong"
    },
    {
      "@context": "https://schema.org",
      "@type": "Organization",
      "dct:conformsTo": "https://bioschemas.org/profiles/Organization/0.2-DRAFT-2019_07_19",
      "description": "University of York",
      "name": "University of York"
    },
    {
      "@context": "https://schema.org",
      "@type": "Organization",
      "dct:conformsTo": "https://bioschemas.org/profiles/Organization/0.2-DRAFT-2019_07_19",
      "description": "Software Sustainability Institute",
      "name": "Software Sustainability Institute"
    }
  ],
  dct:conformsTo: "https://bioschemas.org/profiles/TrainingMaterial/0.8-DRAFT-2020_10_06",
  description: "Prenomics prepares learners for the Cloud-SPAN Genomics course. It teaches the basics of command-line programming, including: (1) file directory structure, (2) use of command-line utilities to connect to and use cloud computing and storage resources and (3) basic shell commands for file navigation and basic script writing.",
  "educationalLevel": "Beginner",
  "identifier": [
    "10.5281/zenodo.6354056\t"
  ],
  inLanguage: [
    "en"
  ],
  keywords: "shell, command line tools, cloud computing, AWS, genomics, ",
  "learningResourceType": [
    "training course"
  ],
  license: [
    {
      "@id": "https://creativecommons.org/licenses/by/4.0/",
      "@type": "CreativeWork"
    }
  ],
  mentions: [
    {
      "@id": "https://gitforwindows.org/",
      "@type": "Thing"
    },
    {
      "@id": "https://cloud-span.github.io/00genomics/",
      "@type": "Thing"
    },
    {
      "@id": "https://datacarpentry.org/genomics-workshop/",
      "@type": "Thing"
    },
    {
      "@id": "10.1038/nature18959",
      "@type": "Thing"
    }
  ],
  name: "Cloud-SPAN Prenomics Course",
  teaches: [
    {
      "@id": "http://edamontology.org/topic_3372",
      "@type": "DefinedTerm"
    },
    {
      "@id": "http://edamontology.org/topic_3071",
      "@type": "DefinedTerm"
    },
    {
      "@id": "http://edamontology.org/topic_0622",
      "@type": "DefinedTerm"
    }
  ],
  timeRequired: {
    "@id": "PT12H",
    "@type": "Duration"
  },
  url: "https://cloud-span.github.io/prenomics00-intro/",
  isPartOf: [
    {
      "@type": "CreativeWork",
      "url": "https://cloud-span.york.ac.uk/",
      "name": "Cloud-SPAN Training Courses"
    }
  ]
---
![A comic figure is looking over the shoulder of another and is shocked by a list of files with names like 'Untitled 138 copy.docx' and 'Untitled 243.doc'. Caption: 'Protip: Never look in someone else's documents folder'.](fig/xkcd-comic-file-names.png)

Welcome to the first lesson in Cloud-SPAN’s **Prenomics** module!

This module is designed to help you get the foundational skills and knowledge needed for our [Cloud Genomics](https://cloud-span.github.io/genomics01-intro/) module, where you will learn how to analyse ‘omics data using cloud-based High Performance Computing (HPC) resources.

In this lesson we will learn how the files and directories on your computer are structured, as well as logging onto the cloud and using the command line (also known as the shell) for the very first time. 


> ## Getting Started
>
> This lesson assumes **no prior experience** with the tools covered in the module. It is designed for absolute beginners.
>
> If you have a little command line experience already, you may not need to complete this module before our [Cloud Genomics](https://cloud-span.github.io/genomics01-intro/) module. Try [our quiz](https://shiny.york.ac.uk/er13/prenomics-quiz/#section-some-general-questions) to help you judge whether you would benefit from Prenomics.
>
> This lesson uses an Amazon Machine Instance (AMI). If you are attending a tutor-led workshop your AMI will be created for you and will be sent the log in information you will need for this lesson. If you are self-studying Prenomics, you will need to set up your own instance using our [Create Your Own AWS Instance](https://cloud-span.github.io/create-aws-instance-0-overview/) module.
> 
> Before starting Prenomics, you should read the [Setup page](https://cloud-span.github.io/prenomics01-file-directories/setup.html). 
{: .prereq}
