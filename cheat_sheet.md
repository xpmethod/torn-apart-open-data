# ICE Awards Data Cheat Sheet

As the *Torn apart/Separados* team grappled with the complexities of the ICE awards data set, we developed an internal "cheat sheet" of notes on the columns of the data set. We share this sheet to assist other teams interested in working with ICE award data.

## Descriptive Data

The descriptive data corresponds to the unique identifiers for awards and related parent awards in the government contracting database.

**Column A: Unique identifiers for awards**
Each award is denoted by a unique identifier.

**Column B: Modification numbers documenting changes to initial award**
Modifications to original awards are denoted by a modification number. The latest (highest numbered) modification provides the most current total values for each award.

**Column C: Transaction number**
Transaction numbers indicate multiple transactions under the same award number. There aren't any awards fitting this description in the ICE award data set.

**Column D: Parent Award Agency ID**
If the award came through a parent award, this is the ID number of the agency that awarded it. Many of the awards in this data set came through parent awards, indicating that many contractors have their hands in a lot of different government pies.

**Column E: Parent Award Agency Name**
Name of the agency where the parent award came from. Some agencies have multiple agency IDs. For example, Federal Acquisition Service appears variously as 4730 and 4732. This is because they correspond to sub-codes in the Federal Procurement Data System based on type of acquisition.

**Column F: Parent award numbers for procurement related to Federal Supply Schedules**
Unique identifiers in Column A may share "parent award numbers" but are still unique awards granted by ICE via the Department of Homeland Security.

**Column G: Parent award modification number**
Indicates if the award is the result of a modification to a parent award.

## The Money Data

Government regulations require recording of all contract changes. Negative, very small, and zero amounts of money in the following columns reflect changes made to existing contracts. Negative amounts reflect de-obligation of government responsibility for an award. Very small or zero amounts reflect a very minimal change in the original contract.

**Column H: Federal action obligation**
Total government obligation, de-obligation (if negative), or financial liability for the award or award modification.

**Column I: Base amount and exercised options**
Total amount of all exercised contract line items and options upon effective date or modification date.

**Column J: Current total value of award**
Total amount of money obligated by the government on the contract to-date (for our data set, as of July 4, 2018), including base contract value and exercised options. This obligation is legally binding and reflects net value of an award, taking into account all award modifications to-date.

**Column K: Base and all options value**
Ultimate value of award or award modification.

**Column L: Potential total value of award**

Potential value of award if all options on the award were to be exercised. This column is interesting because it demonstrates the total amount the government *could* be obligated to pay, if it were to exercise all award options. In the case of ICE data, these potential values speaks to the preparedness to expand operations.

## Temporal Data

Temporal data describes a range of dates associated with the awards.

**Column M: Action Date**
Date binding agreement was reached on award or award modification.

**Column N: Period of performance start date**
Date on which award or modification is effective.

**Column O: Period of performance current end date**
Expected end date of award.

**Column P: Period of performance potential end date**
Potential end date if all options on contract are exercised.

**Column Q: Ordering period end date**
Date after which no more orders on awards can be placed. This refers to awards made as "indefinite delivery contracts" (IDCs) or "blanket purchase agreements" (BPAs), where the specific quantities of goods or services during a fixed award period are variable and are "called" by the government when needed.

## Agency Data

Agency data offers important insight on ICE operations and sub-offices supported by awards.

**Column R: Awarding agency code**
Code for agency granting award. All awards for ICE are granted by the Department of Homeland Security.

**Column S: Awarding agency name**
Name for agency granting award. All awards for ICE are granted by the Department of Homeland Security.

**Column T: Awarding subagency code**
Code for subagency within agency granting award. The subagency for awards granted by ICE is ICE itself.

**Column U: Awarding subagency name**
Name for subagency within agency granting award. The subagency for awards granted by ICE is ICE itself.

**Column V: Awarding office code**
Code for office within ICE granting the award.

**Column W: Awarding office name**
Name of office within ICE granting the award.

Categories:
* Detention Compliance and Removals: oversees detention compliance & deportation.
* Detention Management - Laguna: oversees detention management.
* Information Technology Division: oversees tech needs related to ICE at the systems level. Individual Mission Support offices make additional technology purchases in relation to their operations.
* Mission Support Dallas - management of critical functions for ICE (financial, acquisition, asset, and logistical management).
* Mission Support Orlando - management of critical functions for ICE (financial, acquisition, asset, and logistical management).
* Mission Support Washington - management of critical functions for ICE (financial, acquisition, asset, and logistical management).

**Column X: Funding Agency Code**
Code of agency providing the preponderance of funds for the award. For ICE awards, these are all Department of Homeland Security.

**Column Y: Funding Agency Name**
Name of agency providing the preponderance of funds for the award. For ICE awards, these are all Department of Homeland Security.

**Column Z: Funding Sub Agency Code**
Code of subagency providing the preponderance of funds for the award. For ICE awards, these are all ICE itself.

**Column AA: Funding Sub Agency Name**
Name of subagency providing the preponderance of funds for the award. For ICE awards, these are all ICE itself.

**Column AB: Funding Office Code**
Code for sub-office within ICE providing the preponderance of funds for the award.

**Column AC: Funding Office Name**
Name for sub-office within ICE providing the preponderance of funds for the award.

Categories:
* Acquisition Policy Oversight
* Chief Financial Officer (CFP) - Assurance Compliance
* CFO - Office of Asset Management
* CFO - Financial Management Burlington FO: Burlington, Massachusetts field office w/ jurisdiction over CT, ME, MA, NH, RI, VT
* CFO - Financial Management Dallas FO: Dallas, Texas field office, jurisdiction - North TX & OK
* CFO - Financial Management Headquarters
* CFO - Budget
* Chief Information Officer (CIO) - Immediate Office of the CIO
* CIO - Architecture Division: Manages technical/information architecture
* CIO - Business Resource Management
* CIO - Chief Info Security Officer
* CIO - Chief Technology Office
* CIO - Operations Division
* Detention Compliance and Removals
* Detention Management - Laguna
* Department of Homeland Security (DHS) Investigations Special Agent-in-Charge (SAC) Atlanta: SAC is a particular kind of field office responsible for the administration and management of all investigative and enforcement activities within the geographic boundaries of the office.
* DHS Investigations SAC Baltimore
* DHS Investigations SAC Boston
* DHS Investigations SAC Buffalo
* DHS Investigations SAC Chicago
* DHS Investigations SAC Dallas
* DHS Investigations SAC Denver
* DHS Investigations SAC Detroit
* DHS Investigations SAC El Paso
* DHS Investigations SAC Honolulu
* DHS Investigations SAC Houston
* DHS Investigations SAC Los Angeles
* DHS Investigations SAC Miami
* DHS Investigations SAC New Orleans
* DHS Investigations SAC New York
* DHS Investigations SAC Newark
* DHS Investigations SAC Philadelphia
* DHS Investigations SAC Phoenix
* DHS Investigations SAC San Antonio
* DHS Investigations SAC San Diego
* DHS Investigations SAC San Francisco
* DHS Investigations SAC San Juan
* DHS Investigations SAC Seattle
* DHS Investigations SAC St. Paul
* DHS Investigations SAC Tampa
* DHS Investigations SAC Washington, DC
* Enforcement and Removal (EnforcmntRemovl) Field Operations Division (FOD) New Orleans: An FOD is responsible for enforcement/removal in a jurisdiction. Here, AL, AK, LA, MS, TS.
* EnforcmntRemovl FOD Salt Lake City: jurisdiction - UT, ID, MT, NV
* EnforcmntRemovl FOD San Antonio: jurisdiction - Central South TX
* EnforcmntRemovl Operations (OPNS) FOD Atlanta - jurisdiction: GA, NC, SC
* EnforcmntRemovl OPNS FOD Baltimore: jurisdiction - MD
* EnforcmntRemovl OPNS FOD Boston: jurisdiction - CT, ME, MA, NH, RI, VT
* EnforcmntRemovl OPNS FOD Chicago: jurisdiction - IL, IN, WI, MO, KY, KS
* EnforcmntRemovl OPNS FOD Dallas: jurisdiction - North TX, OK
* EnforcmntRemovl OPNS FOD Denver: jurisdiction - CO, WY
* EnforcmntRemovl OPNS FOD Detroit: jurisdiction - MI, OH
* EnforcmntRemovl OPNS FOD El Paso: jurisdiction - West TX, NM
* EnforcmntRemovl OPNS FOD Houston: jurisdiction - Southeast TX
* EnforcmntRemovl OPNS FOD LA: jurisdiction - Los Angeles Metropolitan Area (counties of Los Angeles, Orange, Riverside, San Bernardino) and Central Coast (counties of Ventura, Santa Barbara and San Luis Obispo)
* EnforcmntRemovl OPNS FOD Miami: jurisdiction - FL, PR, U.S.V.I.
* EnforcmntRemovl OPNS FOD New York: jurisdiction - The five boroughs (counties of New York City) and Duchess, Nassau, Putnam, Suffolk, Sullivan, Orange, Rockland, Ulster, and Westchester counties
* EnforcmntRemovl OPNS FOD Newark: jurisdiction - NJ
* EnforcmntRemovl OPNS FOD Philadelphia: jurisdiction - DE, PA, WV
* EnforcmntRemovl OPNS FOD Phoenix: jurisdiction - AZ
* EnforcmntRemovl OPNS FOD San Diego: jurisdiction - San Diego & Imperial County
* EnforcmntRemovl OPNS FOD San Francisco: jurisdiction - Northern CA, HI, Guam, Saipan
* EnforcmntRemovl OPNS FOD Seattle: jurisdiction - AK, OR, WA
* EnforcmntRemovl OPNS FOD St. Paul: jurisdiction - IA, MN, NE, ND, SD
* EnforcmntRemovl OPNS FOD Washington, DC: jurisdiction - DC, VA
* EnforcmntRemovl OPNS Headquarters (HQ) Compliance: enforcement & removal compliance oversight at headquarters
* EnforcmntRemovl OPNS HQ Crim Alien: the “Criminal Alien” program oversight at headquarters
* EnforcmntRemovl OPNS HQ ENF MNGMT: enforcement management oversight at headquarters
* EnforcmntRemovl OPNS Service Processing Center (SPC) EL PASO: all SPC are detention centers  
* EnforcmntRemovl OPNS SPC Florence
* EnforcmntRemovl OPNS SPC Krome
* EnforcmntRemovl OPNS SPC Port Isabel
* EnforcmntRemovl OPNS Field Office Division (FOD) Buffalo
* EnforcmntRemovl OPNS FOD Pocbatavia
* EnforcmntRemovl OPNS HQ Mission Supply
* EnforcmntRemovl OPNS HQ Removal Management
* Equal Employment Opportunity
* Homeland Security Intelligence (INTEL) - HQ DIV 1
* Homeland Security INTEL - HQ DIV 2
* Homeland Security INTEL - HQ DIV 3
* Homeland Security INTEL - HQ DIV 4
* Homeland Security INTEL - HQ DIV 6
* Homeland Security INTEL - HQ DIV 5
* Homeland Security Investigations (HSI) - Headquarters (HQ) - Division (DIV) 1
* HSI - HQ - DIV 2
* HSI - HQ - DIV 3
* HSI - HQ - DIV 5
* HSI - HQ - DIV 6
* HSI - HQ - DIV 4
* Human Capital Office
* ICE Assistant (Asst) Secretary
* ICE Intelligence
* ICE Office of Congressional Relations
* ICE Student Exchange Visitor Program
* Information Technology Division
* Mission Support Orlando
* Mission Support Washington
* Office (OFC) of the Chief Financial Officer
* OFC of the Chief Information Officer
* Office of Training Tactical Programs
* Office of the Chief Financial Officer
* Officer of Facilities Administration
* Office of International Affairs
* Office of Policy and Planning
* Office of Professional Responsibility
* Office of Principal Legal Advisor
* Office of Public Affairs
* Office of Training and Development

## Recipient Data

Recipient data provides a wealth of information about which contractors are receiving ICE awards. Contractors include individuals, sole proprietors, companies, parent companies and subsidiaries, and non-profit institutions. This data includes contractor addresses and congressional districts, as well as addresses and congressional districts for the place of performance of business (which may be different from a contractor's business address).

**Column AD: Foreign Funding**
Indicates whether the award was given to an entity outside of the United States. This is unusual for ICE awards, but not entirely unheard of.

**Column AE: Foreign Funding Description**
Description of foreign funding.

**Column AF: SAM Exception**
All government contractors are required to have a unique Data Universal Numbering System (DUNS) code, unless they meet the criteria for an exception. This column indicates an exception, if relevant.

**Column AG: SAM Exception Description**
Describes the nature of the exception to the DUNS requirement.

**Column AH: DUNS code**
DUNS code of contractor.

**Column AI: Recipient Name**
Name of recipient.

**Column AJ: Recipient Doing Business As Name**
If the recipient is doing business under a different name, it will be indicated here. This is distinct from the case where a recipient is a subsidiary of a parent company, which is indicated in Column AL.

**Column AK: Cage Code**
Commercial and government entity code issued by the Department of Defense. Presence of a CAGE code indicates security clearance.

**Column AL: Recipient Parent Name**
If the recipient is the subsidiary of a parent company, the parent name listed here will be *different* from the recipient name. If the listed name is the same as the recipient name, there recipient is not a subsidiary.

**Column AM: Recipient Parent DUNS**
DUNS number of the parent.

**Column AN: Recipient Country Code**
Country abbreviation for the recipient address.

**Column AO: Recipient Country Name**
Country name for recipient address.

**Column AP: Recipient Address line 1**
Street address for recipient.

**Column AQ: Recipient Address line 2**
Additional street address information for recipient, if applicable.

**Column AR: Recipient City**
City for recipient address.

**Column AS: Recipient State Abbreviation**
State abbreviation for recipient address.

**Column AT: Recipient State Name**
State name for recipient address. We noticed some errors in data entry in this column. There are instances where the state name that  is listed is actually the state that corresponds with the place of performance of business. The state abbreviations in Column AS are correct for the recipient addresses and the errors are in this column.

**Column AU: Recipient Zip Code + 4**
Zip Code + 4 digits for recipient address.

**Column AV: Recipient Congressional District**
Congressional district for recipient. Number of the district is listed and corresponds to state abbreviation in Column AS (e.g. VA in Column AS and 10 in Column AV corresponds to Virginia's 10th Congressional District).

**Column AW: Recipient Phone**
Phone number of recipient.

**Column AX: Recipient Fax**
Fax number of recipient.

**Column AY: Recipient Primary Place of Performance Country Code**
Country code for the primary place where the business is performed. Primarily the US for this data set.

**Column AZ: Recipient Primary Place of Performance Country Name**
Country name for primary place of business.

**Column BA: Primary Place of Performance City Name**
City name for primary place of business.

**Column BB: Primary Place of Performance County Name**
County name for primary place of business.

**Column BC: Primary Place of Performance State Code**
State abbreviation for primary place of business.

**Column BD: Primary Place of Performance State Name**
State name for primary place of business.

**Column BE: Primary Place of Performance Zip Code + 4**
Zip code + 4 digits for primary place of business.

**Column BF: Primary Place of Performance Congressional District**
Congressional district of primary place of business.

## Award Detail Data

**Column BG: Award or IDV Flag**
Indicates whether this is an outright award or an indefinite delivery contract (IDV), which allows the government to request delivery of goods and services when necessary, within a fixed contract period.

**Column BH: Award Type Code**
Code for award type:
* A = Blanket Purchase Order (BPA) Call
* B = Purchase Order
* C = Delivery Order

**Column BI: Award Type**
Specifies award type:
* BPA Call - a call against existing blanket purchase agreement
* Purchase Order - agreement to buy certain goods/services under certain terms/provisions
* Delivery Order - contract that does not procure or supply a firm quantity of goods or services aside from minimum and maximum quantity

**Column BJ: IDV Type Code**
Code for type of indefinite delivery vehicle:
* E = blanket purchase agreement
* B = indefinite contract delivery

**Column BK: IDV Type**
Specifies IDV type:
* BPA = blanket purchase agreement
* IDC = indefinite delivery contract

**Column BL: Multiple or Single Award Code**
Code for whether multiple or single awards came from a single solicitation:
* M = one of multiple awards from a single solicitation
* S = single award from single solicitation]

**Column BM: Multiple or Single Award IDV**
Specifies multiple or single award.

**Column BN: Type of IDC Code**
Indicates type of indefinite delivery contract (IDC):
* A= Indefinite delivery / requirements
* B = Indefinite delivery / quantity

**Column BO: Type of IDC**
Specifies type of IDC.

**Column BP: Type of Contract Pricing Code**
Codes for pricing of contracted goods and services:
* J = Firm fixed price
* U = cost plus fixed fee
* Y = Time and materials
* 1 = order dependent
* Z = labor hours
* 2 = Combination
* 3 = other   
Additional codes available here: [https://www.fpds.gov/help/Type_of_Contract.htm](https://www.fpds.gov/help/Type_of_Contract.htm).

**Column BQ: Type of Contract Pricing**
Specifies type of Pricing.

**Column BR: Award Description**
A semi-controlled vocabulary of award descriptions.

**Column BS: Action Type Code**
Codes for contract options on particular award or award modification:
* C = funding only
* B = supplemental action
* M = Other Administrative Action
* G= Exercise and Option
* D = Change order
* K = Close out
Additional codes available here: [https://www.fpds.gov/help/Reason_for_Modification.htm](https://www.fpds.gov/help/Reason_for_Modification.htm).

**Column BT: Action Type**
Specifies action type on award or award modification.

**Column BU: Solicitation Identifier**
Identifier used to link solicitations across agencies.

**Column BV: Number of Actions**
Number of actions on award.

**Column BW: Product or Service Code**
Codes for particular kinds of services rendered.

**Column BX: Product or Service Names**
Controlled vocabulary of types of products or services.

**Column BY: Contract Bundling Code**
Codes whether contract is bundled - if consolidating procurements previously made under separate contracts.

**Column BZ: Contract Bundling**
Indicates contract bundling.

**Column CA: DOD Claimant Program Code**
Codes for a grouping of supplies.

**Column CB: DOD Claimant Description**
Designates a grouping of supplies.

**Column CC: NAICS Description Code**
Codes for goods and services through industry codes.

**Column CD: NAICS Descriptions**
Controlled vocabulary of goods and services using industry codes.

## Law Related Data

Law related data indicates the relationship between awards and various legalities governing government contracting.

**Column CE: Recovered  Materials & Sustainability Code**
Codes whether awards must use sustainable materials.

**Column CF: Recovered Materials and Sustainability**
Sustainability related contract clauses, if any.

**Column CG: Domestic or Foreign Entity Code**
Codes whether recipient is a domestic or foreign entity.

**Column CH: Domestic or Foreign Entity**
Indicates whether recipient is domestic or foreign.

**Column CI: DOD Acquisition Code**
Code for Department of Defense acquisitions.

**Column CJ: DOD Acquisition**
Indicates DOD acquisition.

**Column CK: Information Technology Commercial Item Category Code**
Codes whether the information technology service or good is commercially available.

**Column CL: Info Tech Commercial Item Category**
Indicates commercial availability of IT goods and services.

**Column CM: EPA Designated Product Code**
Codes whether there is an EPA designation on the award.

**Column CN: EPA Designated Product**
Indicates EPA designation.

**Column CO: Country of Product Service Origin Code**
Code for country of product or service origin.

**Column CP: Country of Product Service Origin**
Indicates country origin of product or service.

**Column CQ: Place of Manufacture Code**
Code for location where goods were manufactured.

**Column CR: Place of Manufacture**
Indicates place where goods were manufactured.

**Column CS: Subcontracting Plan Code**
Codes whether subcontracting plan is required.

**Column CT: Subcontract Plan**
Indicates whether subcontracting is required.

**Column CU: Extent Completed Code**
Code for whether the award required competition.

**Column CV: Extent Completed**
Indicates competition requirements. See guide: [https://www.fpds.gov/help/Extent_Competed.htm](https://www.fpds.gov/help/Extent_Competed.htm).

**Column CW: Solicitation Procedures Code**
Code designating solicitation procedures.

**Column CX: Solicitation Procedures**
Indicates details of solicitation procedures. See guide: [https://www.fpds.gov/help/Solicitation_Procedure.htm](https://www.fpds.gov/help/Solicitation_Procedure.htm).

**Column CY: Type of Set Aside Code**
Codes whether award was set aside for small businesses.

**Column CZ: Type of Set Aside**
Indicates type of small-business set aside. See guide: [https://www.fpds.gov/help/Type_of_Set_Aside.htm](https://www.fpds.gov/help/Type_of_Set_Aside.htm).

**Column DA: Evaluated Preference Code**
Codes for preferences related to award action.

**Column DB: Evaluated Preference**
Indicates preference given on award. See guide: [https://www.fpds.gov/help/Evaluated_Preference.htm](https://www.fpds.gov/help/Evaluated_Preference.htm).

**Column DC: Research Code**
Codes for research.

**Column DD: Research**
Indicates research related to award.

**Column DE: Fair Opportunity Code**
Code for whether all contractors on a multi-award contract had equal opportunity to respond to a request for proposals (RFP).

**Column DF: Fair Opportunity**
Indicates competition reporting.

**Column DG: Other than full and open competition code**
Codes for solicitation procedures other than open competition. [solicitation procedure reporting, see guide:

**Column DH: Other than full and open competition**
Indicates solicitation procedures aside from open competition. See guide: [https://www.fpds.gov/help/Reason_Not_Competed.htm](https://www.fpds.gov/help/Reason_Not_Competed.htm).

**Column DI: Number of Offers received**
Indicates number of responses to RFP.

**Column DJ: Commercial Items Acquisitions Procedures Code**
Codes for whether commercial item acquisition procedures were used.

**Column DK: Commercial Items Acquisitions Code**
[were commercial item procedures used]

**Column DL: Small Business Competitiveness Demonstration Program**
Indicates recipient participation in the Small Business Competitiveness Demonstration Program, which examines the ability of small businesses to compete for unrestricted government awards beyond the small business set-aside program.

**Column DM: Commercial Item Test Program Code**
Codes whether award is covered under government regulations to simplify commercial acquisitions.

**Column DN: Commercial Item Test Program**
Indicates award inclusion under simplified commercial acquisition protocols.

**Column DO: A76 Fair Act Action Code**
Codes compliance with the FAIR Act, which requires reporting of activities that are not "inherently governmental" but are performed by government employees.

**Column DP: A76 Fair Act Action**
Indicates relationship between award and FAIR Act.

**Column DQ: Federal Business Opportunities Code**
Code for awards subject to Federal Business Opportunity regulations.

**Column DR: Federal Business Opportunities**
Indicates monitoring via Federal Business Opportunity regulations.

**Column DS: Local Area Set Aside Code**
Codes for whether only businesses in a specific geographic area could compete for award.

**Column DT: Local Area Set Aside**
Indicates geographical set aside.

**Column DU: Price Evaluation Adjustment Preference Percent Difference**
Indicates whether there was pricing evaluation and adjustment on the award.

**Column DV: Clinger Cohen Act Planning Code**
Codes for relationship to Clinger-Cohen Act for tech management reform.

**Column DW: Clinger Cohen Act Planning**
Indicates whether award was subject to Clinger-Cohen Act.

**Column DX:  Materials Supplies Equipment Code**
Code for bids for materials, supplies, and equipment.

**Column DY: Materials Supplies Equipment**
Indicates materials, supplies, and equipment.

**Column DZ: Labor Standards Code**
Codes for labor regulations governing the award.

**Column EA: Labor Standards**
Indicates labor regulations to which award is subject.

**Column EB: Construction Wage Rate Requirements Code**
Code for labor wage requirements.

**Column EC: Construction Wage Rate Requirements**
Indicates wage requirements.

**Column ED: Interagency Contracting Authority Code**
Code for authority in cases of interagency contracting.

**Column EE: Interagency Contracting Authority**
Indicates authority for interagency awards.

**Column EF: Other Statutory Authority**
Indicates whether an alternative entity has authority to execute the award.

## Cost/Accounting Data

Cost/Accounting data offers details related to financial transactions on the award. Those that are not self-evident are defined below.

**Column EG: Program Acronym**
Acronym for contracting program.

**Column EH: Parent Award Type Code**
Code for type of parent award, if any.

**Column EI: Parent Award Type**
Indicates parent award type, if relevant.

**Column EJ: Parent Award Single or Multiple Code**
Code for whether there are single or multiple awards under parent award.

**Column EK: Parent Award Single or Multiple**
Indicates single or multiple awards under parent award.

**Column EL: Major Program**
Federal program determination as a "major program".

**Column EM: National Interest Action Code**
Code for the national interest for which the award was given.

**Column EN: National Interest Action**
Specifies national interest for award.

**Column EO: Cost or Pricing Data Code**

**Column EP: Cost or Pricing Data**

**Column EQ: Cost Accounting Code**

**Column ER: Cost Accounting**

**Column ES: Government Furnished Equipment/Property Code**

**Column ET: Government Furnished Equipment/Property**

**Column EU: Sea Transportation Code**

**Column EV: Sea Transportation**

**Column EW: Undefinitized Action Code**
Code for awards where specific terms have not been agreed on in advance.

**Column EX: Undefinitized Action**
Specifies awards for which terms have not been subject to prior agreement.

**Column EY: Consolidated Contract Code**
Code for awards that are the result of consolidation of existing contacts.

**Column EZ: Consolidated Contract**
Indicates consolidation of prior contracts.

**Column FA: Performance Based Service Acquisition Code**
Code for acquisitions based on services rendered.

**Column FB: Performance Based Service Acquisition**
Indicates acquisitions based on services rendered.

**Column FC: Multiyear Contract Code**

**Column FD: Multiyear Contract**

**Column FE: Contract Financing Code**

**Column FF: Contract Financing**

**Column FG: Purchase Card as Payment Method Code**

**Column FH: Purchase Card as Payment Method**

**Column FI: Contingency Humanitarian or Peacekeeping Operation Code**
Codes used to exceed purchasing regulations and thresholds in the case of humanitarian or peacekeeping related contingencies.

**Column FJ: Contingency Humanitarian or Peacekeeping Operation**
Indicates awards subject to humanitarian or peacekeeping related contingencies.

## Demographic Data of Awarded Contracts

Demographic data is opt-in information on race, ethnicity, gender, veteran status, and socio-economic status supplied by award recipients. Recipients can opt-in to the many categories listed below.

**Column FK: Alaskan Native Owned Corporation or Firm**

**Column FL: American Indian Owned Business**

**Column FM: Indian Tribe Federally Recognized**

**Column FN: Native Hawaiian Owned Business**

**Column FO: Tribally Owned Business**

**Column FP: Veteran Owned Business**

**Column FQ: Service Disabled Veteran Owned Business**

**Column FR: Women Owned Business**

**Column FS: Women Owned Small Business**

**Column FT: Economically Disadvantaged Women Owned Small Business**

**Column FU: Joint Venture Women Owned Small Business**

**Column FV: Joint Venture Economic Disadvantaged Women Owned Small Business**

**Column FW: Minority Owned Business**

**Column FX: Subcontinent Asian Indian American Owned Business**

**Column FY: Asian Pacific American Owned Business**

**Column FZ: Black American Owned Business**

**Column GA: Hispanic American Owned Business**

**Column GB: Native American Owned Business**

**Column GC: Other Minority Owned Business**

## Recipient Type Data

Recipient type data indicates the type of company, non-profit organization, or other institution (educational, religious, etc.) that has received the award. Those that are not self-evident are defined below.

**Column GD: Contracting Officers Determination of Business Size**
Determination of business size is handled by the Small Business Administration.

**Column GE: Contracting Officers Determination of Business Size Code**
Code relating to business size determination.

**Column GF: Emerging Small Business**
Any small business that is no greater than 50% of the standard numerical size assigned to a contracting opportunity.

**Column GG: Community Developed Corporation Owned Firm**
Recipient is a corporation developed by a local community for the economic development of the community.

**Column GH: Labor Surplus Area Firm**
Indicates recipient in a civil jurisdiction that has an employment rate of 20% or more over the average for all states within a two-uear period.

**Column GI: US Federal Government**

**Column GJ: Federally Funded Research and Development Corporation**

**Column GK: Federal Agency**

**Column GL: US State Government**

**Column GM: US Local Government**

**Column GN: City Local Government**

**Column GO: County Local Government**

**Column GP: Inter Municipal Local Government**

**Column GR: Municipality Based Local Government**

**Column GS: School District Local Government**

**Column GT: Township Local Government**

**Column GU: US Tribal Government**

**Column GV: Foreign Government**

**Column GW: Organizational Type**

**Column GX: Corporate Entity**

**Column GY: Corporate Entity, Tax Exempt**

**Column GZ: Partnership or Limited Liability Partnership**

**Column HA: Sole proprietorship**

**Column HB: Small agricultural cooperative**

**Column HC: International organization**

**Column HD: US Government Entity**

**Column HE: Community Development Corporation**
Non-profit, community-based organizations that focus on revitalizing their geographic areas.

**Column HF: Domestic Shelter**

**Column HG: Educational institution**

**Column HH: Foundation**

**Column HI: Hospital**

**Column HJ: Manufacturer of Goods**

**Column HK: Veterinary Hospital**

**Column HL: Hispanic Serving Institution**

**Column HM: Receives Contracts**

**Column HN: Receives Grants**

**Column HO: Receives Contracts and Grants**

**Column HP: Airport Authority**

**Column HQ: Council of Governments**

**Column HR: Housing Authority - Public Tribal**

**Column HS: Interstate Entity**

**Column HT: Planning Commission**

**Column HU: Port Authority**

**Column HV: Transit Authority**

**Column HW: Subchapter S-Corporation**

**Column HX: Limited Liability Corporation**

**Column HY: Foreign Owned**

**Column HZ: For-profit Organization**

**Column IA: Non-profit Organization**

**Column IB: Other Not-for-profit Organization**

**Column IC: The Ability One Program**
Source of employment for people with disabilities.

## Organization Data

Organization data offers insight on the recipients, from number of employees to annual revenue to institution type.

**Column ID: Number of Employees**

**Column IE: Annual Revenue**

**Column IF: Private University**

**Column IG: State Controlled Institution of Higher Learning**

**Column IH: 1862 Land Grant College**

**Column II: 1890 Land Grant College**

**Column IJ: 1994 Land Grant College**

**Column IK: Minority Institution**

**Column IL: Historically Black College or University**

**Column IM: Tribal College**

**Column IN: Alaskan Native Servicing Institution**

**Column IO: Native Hawaiian Servicing Institution**

**Column IP: School of Forestry**

**Column IQ: Veterinary College**

**Column IR: DOT Certified Disadvantaged**

**Column IS: Self-certified Small Disadvantaged Business**

**Column IT: Small Disadvantaged Business**

**Column IU: C8A Program Participant**
Capital development program.

**Column IV: Historically Underutilized Business Zone Hubzone Firm**

**Column IW: SBA Certified 8A Joint Venture**
Joint business agreement between two or more small businesses.

**Column IX: Last Modified Date**
Last modified date of award.

