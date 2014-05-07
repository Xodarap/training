This area of HIPAA relates to the accepted coding for data exchanged in healthcare. The transactions this applies to are financial related (claims, eligibility, enrollment, etc). As the name implies, the intent is to make it administratively easier to exchange data by not having to keep track of an endless number of code sets. The common code sets range from X12 or NCPDP (pharmacy-related) and include DRG, ICD, CPT, NDC, SNOMED-CT, and LOINC amongst others.

Here's a quick overview of these code sets and their intended function.

This area of HIPAA relates to the accepted coding for data exchanged in healthcare. The transactions this applies to are financial related (claims, eligibility, enrollment, etc). As the name implies, the intent is to make it administratively easier to exchange data by not having to keep track of an endless number of code sets. The common code sets range from X12 or NCPDP (pharmacy-related) and include DRG, ICD, CPT, NDC, SNOMED-CT, and LOINC amongst others.

Here's a quick overview of these code sets and their intended function.

They are all linked to the appropriate browsers where possible so that you can get a better idea as to what they look like.

* SNOMED-CT or Systematized Nomenclature of Medicine - Clinical Terms: SNOMED-CT is a comprehensive vocabulary that covers almost every aspect of clinical care - ranging from anatomy to diagnoses to observations and procedures. SNOMED-CT requires a licenses but since the US is a participating country in [IHTSDO](http://www.ihtsdo.org/), it can be used freely after accepting a simple license agreement. There are no fees to use this in any commercial application.(see the download link for more info).
[Website](http://www.ihtsdo.org/snomed-ct/snomed-ct0/), [Browser](http://bioportal.bioontology.org/ontologies/SNOMEDCT?p=classes), [Download](http://www.nlm.nih.gov/research/umls/licensedcontent/downloads.html).
* LOINC or Logical Observation Identifiers Names and Codes. This is meant primarily for laboratory and clinical observations. It was developed by the [Regenstrief Institute](http://www.regenstrief.org/). Note that LOINC doesn't have codes for anatomy for one. But, as you can imagine, there is some overlap with SNOMED-CT. There was a recent agreement announced for the two creating bodies to [work together](http://www.regenstrief.org/news/new-regenstrief-and-ihtsdo-agreement-make-emrs-more-effective-improving-health-care/) to map and link SNOMED-CT and LOINC. The use of LOINC is also possible with the acceptance of a simple license agreement. There are no fees to use this in any commercial application. [Website](http://loinc.org/), [Browser](http://bioportal.bioontology.org/ontologies/LOINC?p=classes),[Download](http://loinc.org/downloads)
* ICD 9 and 10 - The International Classification of Diseases. It was developed and is managed by the [World Health Organization](http://who.org). It was initially developed for epidemiology but has since evolved significantly. The US was / is one of the last to switch over to the latest version, ICD-10. ICD-10 was complicated as it introduced a lot more detail (for example, it's codes allow one to distinguish between the right and left lobes of a lung and even more granularly) and an almost 10x increase in codes which is why its rollout in the US was delayed and is still problematic. The use of ICD 9 and 10 is also possible with the acceptance of a simple license agreement (see the download link for more info). There are no fees to use this in any commercial application [Website](http://www.who.int/classifications/icd/en/), [Browser](http://apps.who.int/classifications/icd10/browse/2010/en), Download](http://www.nlm.nih.gov/research/umls/licensedcontent/downloads.html).
* CPT - Common Procedure Terminology. It was developed and is maintained by the American Medical Association [AMA](http://www.ama-assn.org/ama). CPT coding is similar to ICD-9 and ICD-10 coding, except that it identifies the services rendered rather than the diagnosis on the claim. ICD code sets also contain procedure codes but these are only used in the inpatient setting. There is a necessary license agreement for any use and a fee for usage as well (see the download link for more info). [Website](http://www.ama-assn.org/ama/pub/physician-resources/solutions-managing-your-practice/coding-billing-insurance/cpt.page), [Download](https://commerce.ama-assn.org/store/catalog/productDetail.jsp?product_id=prod1270012)
* RxNORM - RxNorm provides normalized names for clinical drugs and links its names to many of the drug vocabularies commonly used in pharmacy management and drug interaction software, including those of First Databank, Micromedex, MediSpan, Gold Standard, and Multum. By providing links between these vocabularies, RxNorm can mediate messages between systems not using the same software and vocabulary. [Website](http://www.nlm.nih.gov/research/umls/rxnorm/), [Browser](http://mor.nlm.nih.gov/download/rxnav/)
* HL7 - Health Language 7. This is more of a messaging and interoperability oriented standard and organization. It is the most common standard set for exchanging data between clinical systems. There are multiple HL7 message standards. However, HL7 has had to evolve to include codesets to enable this exchange. [Website](http://hl7.org), Browser - none, Download - you must be a paid member to access and use it.
* Other codesets - There are others of course. Often there are specific codesets which are mandated for use in a particular context. For example, for immunizations, interoperability and Meaningful Use required the use of the CVX codeset which is put out by the CDC. These are all accessible at via the links below. [Website](https://phinvads.cdc.gov/vads/BrowseValueSets_browse.action), [Browser](https://phinvads.cdc.gov/vads/BrowseValueSets_browse.action)