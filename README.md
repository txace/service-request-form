# service-request-form
Service Request Form

# Parmfile Setup

##SQL Related Fields
Required Fields

o_user username
o_pass password                                                              
o_ds server_name                                                                     
o_db database                                                                
ICD10_Table [t_ICD-10_ICD-10_with_GEM_AXIS]                                     
ICD9_Table [t_ICD-10_ICD-9_with_GEM_AXI

##Center Related
CLLIST - Saved list name, if blank or omitted then the script will read through DB2

center_name
center_npi
center_phone
center_fax
center_contact
contact_phone

##Fundsource Eligibility Medicaid

Declared as an array, to use the paramter version include a dash and number after c_el_fs
c_el_fs-1 13
c_el_fs-2 210

##MCO Related
MCO fundsource
mco_fs-1 210

###MCO Names and matching fax numbers                                                                                
mco_name-1 M-UNITED                                                             
mco_name-2 M-SUPIOR                                                             
mco_name-3 M-FRSTCR                                                             
mco_name-4 M-CIGNA                                                              
mco_name-5 M-AMGRP                                                              
mco_name-6 M-AETNA                                                              
                                                                                
mco_fax_number-1 877-450-6011                                                   
mco_fax_number-2 866-469-0725                                                   
mco_fax_number-3 866-354-8758                                                   
mco_fax_number-4 877-809-0787                                                   
mco_fax_number-5 866-877-5229                                                   
mco_fax_number-6 855-841-8355
