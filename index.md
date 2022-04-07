---
layout: lesson
root: .
bioschemas:
  "@context": "https://schema.org"
  "@id": "https://cloud-span.github.io/prenomics00-intro/"
  "@type": "LearningResource"
  "http://purl.org/dc/terms/conformsTo":
  - "@type": CreativeWork
    "@id": "https://bioschemas.org/profiles/TrainingMaterial/0.9-DRAFT-2020_12_08/"
  about:
  - "@id": "http://edamontology.org/topic_3372"
  - "@id": "http://edamontology.org/topic_0622"
  name: Cloud-SPAN Prenomics Course"
  abstract: "Prenomics prepares learners for the Cloud-SPAN Genomics course. It teaches the basics of command-line programming, including: (1) file directory structure, (2) use of command-line utilities to connect to and use cloud computing and storage resources and (3) basic shell commands for file navigation and basic script writing."
  author: ["Emma Rand", "James Chong", "Sarah Forrester", "Annabel Cansdale", "Jorge Buenabad-Chavez", "Evelyn Greeves"]
  description: "Prenomics prepares learners for the Cloud-SPAN Genomics course. It teaches the basics of command-line programming, including: (1) file directory structure, (2) use of command-line utilities to connect to and use cloud computing and storage resources and (3) basic shell commands for file navigation and basic script writing."
  educationalLevel: "Beginner"
  identifier: "10.5281/zenodo.6354056\t"
  url: "https://cloud-span.github.io/prenomics00-intro/"
  inLanguage: "en"
  keywords: "shell, command line tools, cloud computing, AWS, genomics"
  license: CC-BY 4.0


---
![A comic figure is looking over the shoulder of another and is shocked by a list of files with names like 'Untitled 138 copy.docx' and 'Untitled 243.doc'. Caption: 'Protip: Never look in someone else's documents folder'.](fig/xkcd-comic-file-names.png)

Welcome to the first lesson in Cloud-SPAN’s **Prenomics** module!

This module is designed to help you get the foundational skills and knowledge needed for our [Cloud Genomics](https://cloud-span.github.io/genomics01-intro/) module, where you will learn how to analyse ‘omics data using cloud-based High Performance Computing (HPC) resources.

In this lesson we will learn how the files and directories on your computer are structured, as well as logging onto the cloud and using the command line (also known as the shell) for the first time. 


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
