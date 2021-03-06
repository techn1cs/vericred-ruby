# VericredClient::PlanSearchResult

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**adult_dental** | **BOOLEAN** | Does the plan provide dental coverage for adults? | [optional] 
**age29_rider** | **BOOLEAN** | True if the plan allows dependents up to age 29 | [optional] 
**ambulance** | **String** | Benefits string for ambulance coverage | [optional] 
**benefits_summary_url** | **String** | Link to the summary of benefits and coverage (SBC) document. | [optional] 
**buy_link** | **String** | Link to a location to purchase the plan. | [optional] 
**carrier_name** | **String** | Name of the insurance carrier | [optional] 
**child_dental** | **BOOLEAN** | Does the plan provide dental coverage for children? | [optional] 
**child_eyewear** | **String** | Child eyewear benefits summary | [optional] 
**child_eye_exam** | **String** | Child eye exam benefits summary | [optional] 
**customer_service_phone_number** | **String** | Phone number to contact the insurance carrier | [optional] 
**durable_medical_equipment** | **String** | Benefits summary for durable medical equipment | [optional] 
**diagnostic_test** | **String** | Diagnostic tests benefit summary | [optional] 
**display_name** | **String** | Alternate name for the Plan | [optional] 
**dp_rider** | **BOOLEAN** | True if plan does not cover domestic partners | [optional] 
**drug_formulary_url** | **String** | Link to the summary of drug benefits for the plan | [optional] 
**effective_date** | **String** | Effective date of coverage. | [optional] 
**expiration_date** | **String** | Expiration date of coverage. | [optional] 
**emergency_room** | **String** | Description of costs when visiting the ER | [optional] 
**family_drug_deductible** | **String** | Deductible for drugs when a family is on the plan. | [optional] 
**family_drug_moop** | **String** | Maximum out-of-pocket for drugs when a family is on the plan | [optional] 
**family_medical_deductible** | **String** | Deductible when a family is on the plan | [optional] 
**family_medical_moop** | **String** | Maximum out-of-pocket when a family is on the plan | [optional] 
**fp_rider** | **BOOLEAN** | True if plan does not cover family planning | [optional] 
**generic_drugs** | **String** | Cost for generic drugs | [optional] 
**habilitation_services** | **String** | Habilitation services benefits summary | [optional] 
**hios_issuer_id** | **String** |  | [optional] 
**home_health_care** | **String** | Home health care benefits summary | [optional] 
**hospice_service** | **String** | Hospice service benefits summary | [optional] 
**hsa_eligible** | **BOOLEAN** | Is the plan HSA eligible? | [optional] 
**id** | **String** | Government-issued HIOS plan ID | [optional] 
**imaging** | **String** | Benefits summary for imaging coverage | [optional] 
**in_network_ids** | **Array&lt;Integer&gt;** | List of NPI numbers for Providers passed in who accept this Plan | [optional] 
**individual_drug_deductible** | **String** | Deductible for drugs when an individual is on the plan | [optional] 
**individual_drug_moop** | **String** | Maximum out-of-pocket for drugs when an individual is on the plan | [optional] 
**individual_medical_deductible** | **String** | Deductible when an individual is on the plan | [optional] 
**individual_medical_moop** | **String** | Maximum out-of-pocket when an individual is on the plan | [optional] 
**inpatient_birth** | **String** | Inpatient birth benefits summary | [optional] 
**inpatient_facility** | **String** | Cost under the plan for an inpatient facility | [optional] 
**inpatient_mental_health** | **String** | Inpatient mental helath benefits summary | [optional] 
**inpatient_physician** | **String** | Cost under the plan for an inpatient physician | [optional] 
**inpatient_substance** | **String** | Inpatient substance abuse benefits summary | [optional] 
**level** | **String** | Plan metal grouping (e.g. platinum, gold, silver, etc) | [optional] 
**logo_url** | **String** | Link to a copy of the insurance carrier&#39;s logo | [optional] 
**name** | **String** | Marketing name of the plan | [optional] 
**non_preferred_brand_drugs** | **String** | Cost under the plan for non-preferred brand drugs | [optional] 
**on_market** | **BOOLEAN** | Is the plan on-market? | [optional] 
**off_market** | **BOOLEAN** | Is the plan off-market? | [optional] 
**out_of_network_coverage** | **BOOLEAN** | Does this plan provide any out of network coverage? | [optional] 
**out_of_network_ids** | **Array&lt;Integer&gt;** | List of NPI numbers for Providers passed in who do not accept this Plan | [optional] 
**outpatient_facility** | **String** | Benefits summary for outpatient facility coverage | [optional] 
**outpatient_mental_health** | **String** | Benefits summary for outpatient mental health coverage | [optional] 
**outpatient_physician** | **String** | Benefits summary for outpatient physician coverage | [optional] 
**outpatient_substance** | **String** | Outpatient substance abuse benefits summary | [optional] 
**plan_market** | **String** | Market in which the plan is offered (on_marketplace, shop, etc) | [optional] 
**plan_type** | **String** | Category of the plan (e.g. EPO, HMO, PPO, POS, Indemnity) | [optional] 
**preferred_brand_drugs** | **String** | Cost under the plan for perferred brand drugs | [optional] 
**prenatal_postnatal_care** | **String** | Inpatient substance abuse benefits summary | [optional] 
**preventative_care** | **String** | Benefits summary for preventative care | [optional] 
**premium_subsidized** | **Float** | Cumulative premium amount after subsidy | [optional] 
**premium** | **Float** | Cumulative premium amount | [optional] 
**premium_source** | **String** | Source of the base pricing data | [optional] 
**primary_care_physician** | **String** | Cost under the plan to visit a Primary Care Physician | [optional] 
**rehabilitation_services** | **String** | Benefits summary for rehabilitation services | [optional] 
**service_area_id** | **String** | Foreign key for service area | [optional] 
**skilled_nursing** | **String** | Benefits summary for skilled nursing services | [optional] 
**specialist** | **String** | Cost under the plan to visit a specialist | [optional] 
**specialty_drugs** | **String** | Cost under the plan for specialty drugs | [optional] 
**urgent_care** | **String** | Benefits summary for urgent care | [optional] 
**match_percentage** | **Integer** | Percentage of doctors who matched this Plan | [optional] 
**perfect_match_percentage** | **Integer** | Percentage of employees with 100% match | [optional] 
**employee_premium** | **Float** | Cumulative premium amount for employees | [optional] 
**dependent_premium** | **Float** | Cumulative premium amount for dependents | [optional] 


