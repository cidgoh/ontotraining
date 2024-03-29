# Ontology Curation & Development Training Materials

A repository for ontology training materials developed by The Centre for Infectious Disease Genomics and One Health ([www.cidgoh.ca](https://cidgoh.ca/)). This readme contains (draft) curriculum for the CIDGOH online ontology curation and development training manuals. The intention is to develop guidance for new and existing curators that can be used within and outside of CIDGOH associated ontologies. Some contents are labelled as "AVAILABLE WITH PERMISSION" because the primary authors haven't confirmed the release of the unfinished/draft work on this repo at this time.

![Florian Thiery, CC BY 4.0](https://github.com/cidgoh/ontotraining/assets/48695054/5ec83823-9638-4875-b2c5-75e9045ba459)

### **Contributors:**
_Currently in no particular order._

- Rhiannon Cameron [0000-0002-9578-0788] @cmrn-rhi
- Emma Griffiths [0000-0002-1107-9135] @griffie
- Damion Dooley [0000-0002-8844-9165] @ddooley
- Dalia Alghamdi [] @dalalghamdi
- Anoosha Sehar [0000-0001-5275-8866] @Anoosha-Sehar
- Charlotte Barclay [0000-0001-8008-8249] @cbarbl01
- Soyean Kim [] @soyeangrey
- Aishwarya Sridhar [0000-0002-4880-8311] @ASridhar94
- Nithu Sara John [0000-0002-4823-6210] @nithujohn
- William Hsiao [0000-0002-1342-4043] @wwhsiao

## 0. Table of Contents (TOC)

- [1. Preface](#1-preface)
- [2. Introduction](#2-introduction)
  * [2.1 What is an ontology](#21-what-is-an-ontology)
  * [2.2 How ontologies can be used](#22-how-ontologies-can-be-used)
  * [2.3 OBO Foundry](#23-obo-foundry)
  * [2.4 CIDGOH Ontologies](#24-cidgoh-ontologies)
  * [2.5 Be FAIR](#25-be-fair)
- [3. Prerequisites](#3-prerequisites)
  * [3.1 Ontology folder structures](#31-ontology-folder-structures)
  * [3.2 GitHub](#32-github)
  * [3.3 Accessing OWL Files](#33-accessing-owl-files)
- [4. Getting Start - Finding Your Feet](#4-getting-start---finding-your-feet)
- [5. Ontology Building](#5-ontology-building)
- [6. Subject FAQs - Special Cases](#6-subject-faqs---special-cases)

## 1. Preface

A humble preface! We are creating original content AND drawing from/referencing other wonderful material already available. FAIR and how it is our goal to make this material as FAIR as possible.

## 2. Introduction

### 2.1 What is an ontology
- [**2.1.1 Data standards vs ontologies**](https://docs.google.com/document/d/e/2PACX-1vS7GsG2ShIJA25uac6PDQR3qKaU5_O_kOnI5H1SdOyQvcl2xRShFt3VOUPbMSfDw55lqsQPAZpsYO0M/pub) ✔️
- **2.1.2 Adolescent ontologies**

### 2.2 How ontologies can be used
_Consider giving this an "overview" blurb that introduces the examples._
- [**2.2.1 Genomic epidemiology examples**](https://docs.google.com/document/d/e/2PACX-1vSaNtX1yKdiradc0L3MbReqvLIeBlJazOeB-SNX9cVzm3cvfl3ZtxcCjyhpGy4obWT-cglpx0kg3Bnj/pub) ✔️
- **2.2.2 Harmonizing across food databases (FoodOn)**
- [**2.2.3 Natural Language Processing (NLP) examples**](https://medium.com/@soyeankim/genomic-epidemiology-ontology-and-nlp-creating-new-systems-for-infectious-disease-management-7d14eac6ac1d) ✔️
- **2.2.4 CINECA webservice for ontology mapping**

### 2.3 OBO Foundry
_Add sections on RO and OMO. The transition from BFO to COB._
- **2.3.1 BFO (Basic Formal Ontology)**
- **2.3.2 COB (Common Biology Ontology)**
- [**2.3.3 Ontology IRIs vs IDs**](https://docs.google.com/document/d/e/2PACX-1vSekJ3Sj1Km1l5prok-U1aeV3UcZhwIRibQe7u5EIVeR5kZEd4ewKbB-CRbsi6JvXHTU-ISxeNaLRm8/pub) ✔️

### 2.4 CIDGOH Ontologies
- **2.4.1 FoodOn**
- **2.4.2 GenEpiO**

### 2.5 Be FAIR
_Consider switching places with 2.4._
- **FAIR principles and their relationship with ontologies** - AVAILABLE WITH PERMISSION ✔️

## 3. Prerequisites

### 3.1 Ontology folder structures
- e.g. https://foodon.org/design/curation-workflow/

### 3.2 GitHub
- **3.2.1 Preparing your workspace with GitHub Desktop** - AVAILABLE WITH PERMISSION ✔️

### 3.3 Accessing OWL Files

## 4. Getting Start - Finding Your Feet
- **4.1 What information do you need?**
  - **4.1.1 Standardized vocabulary**
  - **4.1.2 Annotations**
    - **4.1.2.1 Minimal metadata schema**
    - **4.1.2.2 Naming Conventions**
    - [**4.1.2.3 Definitions**](https://docs.google.com/document/d/e/2PACX-1vSJaJpA3ebp8gSWfSMO5lCPQcmk1RSJuaxtzfwTGoZaMEuMuxZZZjLsvMBG5TS9Q_IPFVQqhL0Ei-C-/pub) ✔️
  - **4.1.3 Parents and subclasses**
  - **4.1.4 Classes vs Instances**
  - **4.1.5 Axioms**
    - **4.1.5.1 OBOF axioms**
    - **4.1.5.2 `is_a` vs `other` axioms**
    - **4.1.5.3 What we ue at CIDGOH**
  - **4.1.6 Guidance for diagramming models** [EXAMPLE](https://drive.google.com/file/d/15yJ7bIs3OGAIEgZ3Shp51BgJoCFcaZNh/view?usp=sharing)
  - **4.1.7 Importance of "processes" that connect individual classes**
- **4.2 Term Curation (step-by-step)**
   - **4.2.1 Curation workflow**
   - **4.2.2 Getting a template started**
   - **4.2.3 Do you need to create a new term?**
   - **4.2.4 Creating a new term**
   - **4.2.5 Importing an existing term**
   - **4.2.6 Making a new term / term edit request**
   - **4.2.7 Minting & Term Obsolescence**
   - **4.2.8 CIDGOH SOPs**
       - **Addressing & Responding to new term requests** - AVAILABLE WITH PERMISSION ✔️
       - **Reporting Protocol**
       - **ROBOT Protocols** - AVAILABLE WITH PERMISSION ✔️
 
## 5. Ontology Building
- **5.1 Import files**
- **5.2 What tool is appropriate for your needs?**
- **5.3 GitHub & version control
- **5.4 Protege** - AVAILABLE WITH PERMISSION ✔️
- **5.5 ROBOT**
- **5.6 SPARQL** - AVAILABLE WITH PERMISSION ✔️
   - **5.6.1 Basic querying**
   - **5.6.2 Teasing facts out of OWL**
   - **5.6.3 FoodOn Instant Formula**
- **5.7 OntoFox**
- **5.8 Ontology Development Kit**

## 6. Subject FAQs - Special Cases
- **Taxanomy Manual** - AVAILABLE WITH PERMISSION ✔️
- **CHEBI**
- **How to use relations in your ontology**
- **Illumina entities example (sequencer vs company)**
- **"Fuzzy" terms**
- **Ontology conundrums (ontology discussions that will keep you up at night - still need addressing by the greater community)**
