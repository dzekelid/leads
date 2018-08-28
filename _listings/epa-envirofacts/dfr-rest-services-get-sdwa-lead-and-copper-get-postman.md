{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility Report (DFR) Detailed Facility Report SDWA Lead and Copper Service",
    "_postman_id": "7d2c5454-f82f-4c90-a83e-b8f0ff7650c5",
    "description": "This procedure obtains data for the SDWA, Lead and Copper Rule section of the DFR.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "cd644646-107f-4d55-8de6-3b98cd9df036",
      "name": "this-procedure-obtains-data-for-air-compliance-in-the-environmental-conditions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_air_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Air Compliance in the Environmental Conditions Section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "78cc6080-a810-44c5-8f6f-7c095b7456de"
        }
      ]
    },
    {
      "id": "73385ab6-7bf1-4e5a-aca1-803dc478bf98",
      "name": "this-procedure-obtains-data-for-air-quality-in-the-environmental-conditions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_air_quality?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Air Quality in the Environmental Conditions Section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b59f2990-1bf6-4657-b263-cf8a2ac8e1c5"
        }
      ]
    },
    {
      "id": "763a4459-e6be-46b9-a384-80331ee38fc0",
      "name": "this-procedure-obtains-data-for-the-compliance-monitoring-history-5-years-in-the-enforcement-and-com",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_compliance_history?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Compliance Monitoring History (5 years) in the Enforcement and Compliance Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d3e70423-29ca-4dc3-8773-e4650b1dc260"
        }
      ]
    },
    {
      "id": "6fcea0c0-5569-4202-9221-1936a5ab186c",
      "name": "this-procedure-obtains-data-for-compliance-summary-data-in-the-enforcement-and-compliance-section-of",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_compliance_summary?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Compliance Summary Data in the Enforcement and Compliance Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "53ce76ca-8a09-4bf3-b304-b4fd04e39f8e"
        }
      ]
    },
    {
      "id": "27787aa0-7f02-4007-848a-505ba6c3dacc",
      "name": "this-procedure-obtains-data-for-the-cwa-facilitylevel-status-section-located-in-the-three-year-compl",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_3yr_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Facility-Level Status section located in the Three Year Compliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows:\n> \"In Viol\" = Facility is in violation\n> \"No Viol\" = No violation found\n> \"Unk\" = Unknown status\n> \"SNC/Cat 1\" = SNC/Category I violation found"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6396d8db-fa51-4dae-8fc2-570bd089d752"
        }
      ]
    },
    {
      "id": "c28c0410-0d53-4e78-a606-41a0a34da545",
      "name": "this-procedure-obtains-data-for-the-cwa-compliance-schedule-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_cs_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Compliance Schedule Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "ebf3da11-1390-4d54-8e98-af5ff9475918"
        }
      ]
    },
    {
      "id": "c78a860d-8a45-445f-93c8-7cf1ba276f0d",
      "name": "this-procedure-obtains-data-for-the-cwa-pollutant-discharge-section-located-in-the-three-year-compli",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_eff_alr?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Pollutant Discharge section located in the Three Year Compliance Status by Quarter portion of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "e95b3338-c6bb-458e-9a71-20b6076cf547"
        }
      ]
    },
    {
      "id": "a571d334-261e-44bf-9fcd-06a02b8e4c30",
      "name": "this-procedure-obtains-data-for-the-cwa-effluent-compliance-section-on-the-dfr---",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_eff_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Effluent Compliance section on the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "780f2c51-fd97-4afc-8f09-534eeb44c8b1"
        }
      ]
    },
    {
      "id": "d22636d5-ed64-4668-a431-fa2f96a8dbe8",
      "name": "this-procedure-obtains-data-for-the-cwa-permit-schedule-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_ps_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Permit Schedule Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "813142a6-e402-4470-8b0a-3a052a6af54a"
        }
      ]
    },
    {
      "id": "646b9da7-8756-40e6-90ed-c22eabc77166",
      "name": "this-procedure-obtains-data-for-the-cwa-sncrnc-history-section-located-in-the-three-year-ompliance-s",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_rnc_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA SNC/RNC History section located in the Three Year ompliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows.\n> S = SNC/Category I - an enforcement action has been issued, and the facility is not meeting its compliance schedule\n> E = SNC/Category I - effluent violations of monthly average limits (Technical Review Criteria and chronic)\n> X = SNC/Category I - effluent violations of non-monthly average limits (Technical Review Criteria and chronic)\n> T = SNC/Category I - compliance schedule reporting violation\n> D = SNC/Category I - reporting violation - nonreceipt of DMR\n> N = RNC/Category II - reportable non-compliance\n> P = Resolved Pending - an enforcement action has been issued, and facility compliance with the action is pending final completion\n> R = Resolved - the facility has returned to compliance with its permit conditions, either with or without issuance of an enforcement action\n> C = Not considered in RNC/SNC based on manual review of data by state or EPA region. This manual override status is also indicated by a superscripted \"m\".\n> Blank = Not considered in RNC/SNC\n> N/A = EPA's data system is not able to determine the facility-level compliance status based upon the information available. This information may be available from a state database."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "e7204c3b-5028-4566-8691-978b79161dd7"
        }
      ]
    },
    {
      "id": "2f0170b1-52ae-48e1-bdcb-eb1844b69b03",
      "name": "this-procedure-obtains-data-for-the-cwa-single-event-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_se_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Single Event Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "24412234-0ef3-49ea-ac22-51bb0f9b0175"
        }
      ]
    },
    {
      "id": "c57a48fa-d272-4437-9b95-e1065c2258ce",
      "name": "returns-a-complex-object-with-demographics-from-the-2010-census-and-2010-american-community-survey-b",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_demographics?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns a complex object with Demographics from the 2010 Census and 2010 American Community Survey based on a 3 mile radius around the facility spatial coordinates."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "74e004c9-3a99-46a6-be00-62497d1108ed"
        }
      ]
    },
    {
      "id": "12dfbf95-9b7f-48ea-8313-90eddb3bb80e",
      "name": "this-procedure-is-the-overall-service-for-the-detailed-facility-report--it-returns-all-of-the-data-d",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_dfr?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure is the overall service for the Detailed Facility Report. It returns all of the data displayed in the DFR web report by invoking individual procedures that each return a targeted portion of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "356b9f4b-7307-4f50-9c7b-c373ca9b5563"
        }
      ]
    },
    {
      "id": "14a7e9ec-aca0-44b9-926e-adfcaf1298ab",
      "name": "this-procedure-obtains-data-for-the-enforcement-and-compliance-summary-in-the-facility-summary-secti",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_enforcement_summary?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Enforcement and Compliance Summary in the Facility Summary section of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "68478116-e265-4fb4-bfdc-8838e706d03c"
        }
      ]
    },
    {
      "id": "4fa7aebb-8a46-4d98-aae0-eb9608cd671a",
      "name": "this-procedure-obtains-data-for-the-formal-enforcement-actions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_formal_actions?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Formal Enforcement Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "653c27be-eed7-4606-a150-c916d790544a"
        }
      ]
    },
    {
      "id": "9088e84e-9fb7-4573-962b-1d74372f7ec3",
      "name": "this-procedure-obtains-data-for-the-integrated-compliance-information-system-formal-enforcement-acti",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_icis_formal_actions?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Integrated Compliance Information System, Formal Enforcement Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b7249a87-bfcf-4e4d-a7dd-aebdbe02b698"
        }
      ]
    },
    {
      "id": "5c0aba02-9d9e-47f9-b1ec-4deb2acb0035",
      "name": "this-procedure-obtains-data-for-enforcement-and-compliance-summary-section-of-the-detailed-facility-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_inspections?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Enforcement and Compliance Summary Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "5aba8853-3d1a-4694-b30b-04910392690e"
        }
      ]
    },
    {
      "id": "8577c848-4870-494c-8795-ce94567d670d",
      "name": "returns-an-object-with-the-facilitys-latitude-and-longitude-coordinates-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_map?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns an object with the facility's latitude and longitude coordinates."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "dadfe20b-bb81-4d62-a53c-b5af20ab6d02"
        }
      ]
    },
    {
      "id": "2f1f614c-b4f9-450b-a57d-12b954932fc7",
      "name": "this-procedure-obtains-data-for-the-facility-naics-codes-section-in-facilitysystem-characteristics-o",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_naics?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Facility NAICS Codes section in Facility/System Characteristics of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "eef2ed30-5424-4e7d-8d08-ae9363432125"
        }
      ]
    },
    {
      "id": "b03301c0-fdc5-47eb-ba49-d0b1d432f51f",
      "name": "this-procedure-obtains-data-for-the-permits-by-statute-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_nnnPermits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Permits by Statute section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "227036e5-4f22-4a62-b041-6721c3ef23d0"
        }
      ]
    },
    {
      "id": "7b206494-36e6-4838-a3b6-bd2fa45203df",
      "name": "this-procedure-obtains-data-for-the-noticesinformal-actions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_notices?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Notices/Informal Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f419bd24-a4c8-4338-8b6d-4378b669bb17"
        }
      ]
    },
    {
      "id": "4a93343a-d8f6-4a08-a5ae-f72d7ccfd458",
      "name": "this-procedure-obtains-data-for-the-following-sections-of-the-detailed-facility-report--facility-inf",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_permits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the following sections of the Detailed Facility Report.\n> Facility Information (FRS) in the Facility Summary.\n> Regulatory Interests in the Facility Summary.\n> Also Reports in the Facility Summary.\n> Facility/System Characteristics in Facility/System Characteristics.\n> Facility Contact Information in Facility/System Characteristics.\n> Facility SIC Codes in Facility/System Characteristics section.\n> Facility NAICS Codes in Facility/System Characteristics section."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "948710c6-e9aa-4a30-8fc0-ab9682d75562"
        }
      ]
    },
    {
      "id": "c3c51bc5-1529-4908-94b4-79652a9562b6",
      "name": "this-procedure-obtains-data-for-the-rcra-compliance-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_rcra_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the RCRA Compliance section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "9cb907ca-e215-4405-8238-480727b15bb7"
        }
      ]
    },
    {
      "id": "895889fa-f10c-4763-970b-8e7974e094aa",
      "name": "this-procedure-obtains-data-for-the-sdwa-lead-and-copper-rule-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_lead_and_copper?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA, Lead and Copper Rule section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "5d87b329-3714-4396-82dc-08bd7852745b"
        }
      ]
    }
  ]
}