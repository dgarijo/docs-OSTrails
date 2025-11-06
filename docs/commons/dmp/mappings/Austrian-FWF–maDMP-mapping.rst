Austrian FWF – maDMP mapping 
===============================================



.. list-table:: Mapping Table FWF Template
   :header-rows: 1

   * - Template Section
     - FWF DMP template questions
     - Corresponding maDMP fields in DCS
     - Corresponding maDMP fields in OSTrails AP
   * - 0 Data Officier
     - Who is responsible for the data management and the DMP of the project (name/email address)?
     - dmp/contact/*, dmp/contributor/*
     -    
   * - I Data Characteristics
     - What kinds of data/source code will be generated or reused (type, format, volume)?
     - dataset/type, distribution/format, distribution/byte_size  
     - 
   * - 
     - How will the research datasets be generated and which methods will be used?
     - 
     - dataset/methodology
   * - 
     - How will you structure the data and handle versioning?
     - host/support_versioning
     - 
   * - 
     - Who is the target audience?
     - 
     - 
   * - II Documentation and Metadata
     - What metadata standards (if any) will be in use and why? (see Digital Curation Centre)
     - dataset/metadata/*
     - 
   * - 
     - What information is needed for the data to be findable, accessible, interoperable and re-usable (FAIR) in the future?
     - dataset/dataset_id, distribution/data_access, distribu-tion/access_url, dataset/metadata/*, distribution/license/*
     - 
   * - 
     - Is the data machine-readable?
     - 
     - 
   * - 
     - How are you planning to document this information?
     - 
     - 
   * - 
     - What quality assurance processes will you adopt?
     - dataset/data_quality_assurance
     - 
   * - 
     - How will the consistency and quality of data collection be controlled and documented? (This may include processes such as repeat samples or measurements, standardised data capture, peer review of data or representation with controlled vocabularies.)
     - 
     - dataset/methodology
   * - 
     - How and when will the data be shared and made accessible?
     - distribution/*, distribution/host, license/start_date
     - 
   * - 
     - What repository will you be using?
     - host/url
     - 
   * - III        Data Availability and Storage
     - What persistent identifier will be used?
     - dataset/dataset_id, host/pid_system
     - 
   * - 
     - What data are to be preserved for the long-term, and what data will not be stored?
     - dataset/preservation_statement
     - 
   * - 
     - How and where will the data be stored and backed up during the research?
     - host/url,	host/storage_type,	host/availability, host/backup_type, host/backup_frequency
     - 
   * - 
     - How and where will the data be stored after the project ends?
     - distribution/access_url, distribution/host/*
     - 
   * - 
     - For how long will the data be stored?
     - distribution/available_until
     - 
   * - 
     -  Are there any costs that need to be covered for storage?
     - dmp/cost/*
     - 
   * - 
     - At what point during or after the project will the data be stored?
     - license/start_date
     - 

   * - 
     - Are there any technical barriers to making the research data fully or partially accessible?
     - distribution/data_access, dataset/technical_resource
     - 
   * - II Legal andEthical Aspects
     - Are there any legal barriers to making the research data fully or partially accessible?
     - 
     -
   * - 
     - Who owns the data?
     - license/license_ref
     - 
   * - 
     - What licence for reuse are you planning to attach to the data?
     - license/license_ref
     - 
   * - 
     - Are there any restrictions on the re-use of the data? If so, why?
     - license/license_ref
     - 
   * - 
     - Are there any ethical barriers to making the research data fully or partially accessible?
     - dmp/ethical_issues_exist, dmp/ethical_issues_description dmp/ethical_issues_report
     - 
   * - 
     - If applicable, how are you planning to deal with sensitive data during and after the project?
     - dataset/security_and_privacy/*
     - 