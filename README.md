# cdmi_quality_assessment
Validity and reliability analysis of 2016-2017 clinical digital maturity index responses

NOTEBOOKS:
01_cdmi_internal_consistency -> analysis of internal consistency metrics
02_cdmi_factor_analysis -> exploratory factor analysis
03_cdmi_emram_external_validity -> validity against external EMRAM scores
04_cdmi_test_retest_icc -> section level analysis comparing delta across both years and explanatory factors for changes over time
05_cdmi_test_retest_icc_all_responses -> question level analysis comparing delta across both years

DATA:
/acute - contains CDMI responses for Acute Trusts only
-> 0000_question_key.xlsx -> questions are keyed and matched between 2016 and 2017
-> xxxx_acute_questions -> question level data
-> xxxx_acute_themes -> theme level data
-> /acute/section - individual section sheets for section analysis and internal consistency analysis
-> /acute/sem - questions by key, used for response delta, and for factor analysis.
-> /acute/external - contains external comparative measures for analysis

/geo_graph - contains long/lat data for all Trusts

/raw_data - original CDMI data

gelocated.csv - geolocation data for import
