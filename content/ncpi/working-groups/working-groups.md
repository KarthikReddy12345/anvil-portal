---
draft: false
---


# Working Groups
The NCPI has established the following working groups to address various challenges to interoperability.

We have purposely constrained the problems we are addressing to that which is achievable in the near term and maximizes value to researchers.
 
Harmonization of metadata, or large scale data harmonization across projects, for example, are worthwhile and interesting topics that are likely to be future areas of focus for this group.  We will, however, stay focused initially on the "lowest hanging fruit" in terms of user functionality and interoperability improvements.


## Coordination Working Group

<hero small>The Coordination Working Group will coordinate discourse, collaboration, and meetings between the working groups of NCPI.</hero> 

The Coordination Working Group provides an interface between the chairs of the other NCPI working groups to promote use case driven interoperability between cloud platforms. 

**Co-Chairs**
- Valentina di Francesco (NHGRI)
- Ken Wiley (NHGRI)

## Community Governance Working Group

 <hero small>The Community Governance Working Group aims to establish a set of [principles](/ncpi/interoperating-principles) for promoting interoperability across multiple platforms to remove operational barriers to trans-platform data sharing.</hero>

**Co-Chairs**
- Stan Ahalt (ORG)
- Bob Grossman (ORG)
 

##FHIR Working Group

<hero small>The FHIR Working Group is exploring the potential of HL7 FHIR to support the exchange of clinical and phenotype data between the NCPI effort's particpating platforms.</hero>

**Co-Chairs**
- Robert Carrol (Vanderbilt)
- Allison Heath (CHOP)

Recently, there is increasing attention on the potential of HL7 FHIR, a standard developed primarily for clinical data interoperability. Electronic Health Record interoperability has been a serious challenge in the field for the length of its existence - fraught with challenges across the spectrum of technical and policy.
 
 Similar challenges face the research world in using FHIR: the standard has only been lightly implemented in clinical practice, though at times to great effect, and the tools researchers need to effectively use this complex data do not exist. However, the promise of interoperability of systems with large support in the community is one that’s hard to ignore in the context of clinical/phenotypic data interoperability for the NCPI efforts. 

### Initial Focus
An initial objective of the FHIR working group is to have a practical approach for learning and prototyping with FHIR to gain a shared understanding of the problems it solves.
 
 Our first project is a collaborative technical “hands-on” project to allow teams to gain hands-on experience with FHIR. This will allow us to better communicate and create a roadmap for clinical data interoperability between datasets hosted by participants in NCPI. 
 
 As knowledge is gained, we anticipate needing to reevaluate the objectives of this working group. 
 
 
##NIH CIT Researcher Auth Service Project
 
<hero small>In parallel with the NCPI effort, the NIH CIT is working to create one unified Researcher Auth Service (RAS) that will streamline access to multiple NIH data resources.  </hero>
 
Currently the NCPI participating platforms use different methods for authentication and managing approvals to controlled access data, and this is one of the major roadblocks to interoperability.
  
**Project Lead**
- Rebecca Rosen (NIMH)


## Outreach and Training Working Group

<hero small>The Outreach and Training Working Group will provide exposure and training for NCPI platforms in the biomedical research community. </hero>

**Co-Chairs**
- Ashok Krishnamurthy (RENCI)
- Anton Nekrutenk (PSU)

## NIH Systems Interoperation Working Group

<hero small>The NIH Systems Interoperation Working Group group will spearhead technical improvements to the NCPI participating platforms that enable improved interoperability.  We will demonstrate progress rooted in realistic researcher use cases every 6 months.</hero>

**Co-Chairs**
- Brian O’Connor (Broad)
- Jack DiGiovanna (Seven Bridges)


## Background

Right now it is very difficult to use GTEx, Kids First, TOPMed, and TCGA cloud-based datasets together (or in distinct combinations).  While data portals make it easy to find data in most cases, it is difficult to take search results from a given data portal to a preferred analysis workspace (cloud compute environment). 
 
 Currently, there is not a way that researchers can browse multiple data portals (Kids First, AnVIL, Catalyst, etc), collect their search results, and take them to a single compute environment of their choosing (Terra, Seven Bridges, Cavatica, DNAstack, Galaxy, etc).
   
  Some data portals can send search results to analysis workspaces (Kids First DRC to Cavatica for example) but this is limited to specific analysis workspace + portal combinations while other portals cannot interact with analysis workspaces at all.


Luckily, new and emerging standards (PFB, GA4GH DRS) can help to make the interface between data portals and analysis workspaces consistent, allowing many portals to send search results (e.g. lists of sample IDs and some metadata) to many different analysis workspace environments, ultimately giving researchers better access to data and increased flexibility in their analysis.


## Goals
The key goal of this activity is to establish a generic and universal handoff mechanism so Data Portal users can further analyze search results on any analysis platform that supports the format.  This would allow for Data Portals to develop and maintain a single “export mechanism” which would be available to any Analysis Platform that invested in supporting the standard format. Importantly, this gives their users much more freedom in how and where they compute.

 
 By improving the handoff of search results from portals to workspace environments through standardization, we will enable researchers to query on multiple portals and aggregate their search results to a common cloud workspace of their choosing in order to perform an analysis. 
 
 For example, this will let a researcher search for Kids First and TOPMed data on their respective portals and then take the results to the Terra environment where they can perform a joint analysis on these data. Right now, this simple scenario has limited or no support across portals and analysis workspaces, making this type of joint analysis impossible for most users.


## Deliverables

1. Build the necessary infrastructure to enable the research use cases.
1. Document the standards and conventions we use so that other systems can implement the same approaches.
1. Provide user-facing materials (blog post, tutorials, and/or documentation) so that other researchers can leverage what is built.




