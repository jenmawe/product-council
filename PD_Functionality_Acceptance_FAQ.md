# Product Coucil Evaluation of New Functionality Frequently Asked Questions

## Product Council considers new functionality to be
- New FOLIO App
- New functionality that may be front end and/or back end changes that impact the data model and other cross-app functionality

## Examples of new functionality recently reviewed by the PC
- LIsts App: originally this app was not part of FOLIO, but was proposed to fill a gap in functionality. The Lists App went through the full review process with the PC, and the modules that composed it were reviewed by the Technical Council. BELA (Bulk Edit and Lists App) continues as a subgroup under the Application Interaction SIG, and continues List App development.
- New Serials App that was part of the Quesnelia flower release. Before that release, the Product Owners worked with the Acquisitions to share development progress and garner feedback, then presented this new App’s features and how it interacted with other Apps.
- New backend modules and front end UI work, the mod-marc-migrations (This backend module supports more seamless updates of bib and authority records to reflect mapping rules change) and mod-record-specifications (aka Mr Specs) (This backend module supports tenant level MARC validation rules configuration. A library will be able to define MARC validation rules MARC bib and MARC authority records with this module. An error will either warn a cataloger or prevent the quickMARC from being saved). These were presented to the PC for review for the Ramsons flower release.

## Examples of new functionality recently NOT reviewed by the PC
- Changes to property field names (both back and front end). For example, In Marc Source Record Storage, the inventoryHRID was renamed to externalHolderIDsInstanceHRID. This change was to accommodate other types of external identifiers for MARC holdings records and MARC authorities. This change can be seen in the API and in 3rd party systems such as LDP. This was a back end change to existing code.
- Updates to current functionality. For example, advanced search which was introduced in the Poppy flower release. This is new functionality built on existing code.
- New functionality to existing Apps. For example, the bindery functionality adds new features to the Receiving and Inventory App. This is new functionality built on existing code.
- New edge module for the API for ERM functionality. No UI features or functionality in FOLIO were impacted by the module, so the PC decided that the Technical Council modules review of edge-erm was sufficient.

# General Guidelines
Use your best judgement as to whether to seek review from the Product Council. In general, if you are seeking TC review, then also seek PC review. If you feel the functionality impacts current apps and functionality and has downstream impacts to front and/or back functionality, then submit a PCR. We also encourage you to reach out to the PC with questions.
