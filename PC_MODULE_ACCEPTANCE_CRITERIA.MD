# Overview

The FOLIO project and its governance councils propose a process for evaluation of new functionality for inclusion into officially sanctioned FOLIO LSP releases.  Each Council reviews potential new functionality using complementary processes. Under the current “flower release” system, the Product Council will review and assess any proposed new apps that will require the addition of new modules. Adjustments in already established apps that are added to existing modules do not need to be reviewed by the PC at this time. The Product Council generally will work at the app level, the Technical Council considers evaluation at the Module level, and the Community Council determines the appropriate level of documentation and financial commitment to fulfill, maintain, update, and support the functionality. Functionality that passes the Product Council review will then be communicated to the Technical Council where resulting modules will receive a technical review before inclusion in an officially sanctioned release. These steps can happen simultaneously in order to expedite inclusion of desired functionality. If modules are of a technical or backend nature, the Product Council may decline a functionality review, and refer the module developers directly to the Technical Council for review. Once approved, contributors will be directed to the Community Council to explain investment and commitment which may include, at the Community Council’s option, a requirement to sign a MOU and contribute the code to the Open Library Foundation. The Councils recommend contributors review the functional, technical, and license requirements in advance of submission. The Product Council in particular welcomes and encourages discussions of new apps as they are being designed in addition to a final review when the underlying module(s) are ready to be added to a flower release, to ensure a smooth, fast, and transparent process. Regardless, the PC always welcomes discussions around new or existing functionality. If contributors are unsure, we encourage questions to be brought to the PC for discussion and next steps.
What requires review by the Product Council?

It can be difficult to answer this question. In general, if a grouping of new features requires changes to the front of end and the back-end of FOLIO and results in new modules, the Product Council would like to know about it. You can see examples of previous functionality reviewed and approved by the PC on the Decision Log wiki page. If a contributor is unsure whether engagement with the PC is warranted, please reach out and we can have a conversation. Similarly, the PC will endeavor to check in with the Product Owners group regularly to get a sense of new functionality coming and note where conversations would be helpful.

Plug-ins are an exception and do not require this review.

Apps, modules, and other definitions can be found in the FOLIO Terminology document.

Features may be defined as Epics or groups of UXPROD issues in Jira.
Motivation

The purpose of these evaluations is to ensure that substantial new functionality included in official FOLIO LSP releases meets three standards:

    Functional values and criteria defined by the Product Council
    Technical criteria defined by the Technical Council
    Financial and contributor criteria, defined by the Community Council. 

These criteria help ensure the longevity and usefulness of the FOLIO product to all stakeholders. The Product Council review will be focused on the type of functionality that would be provided to FOLIO. This includes: uniqueness, fit with existing FOLIO functionality, and support of Roadmap objectives. To state it very simply, the Product Council deals with the “what” and the “why” of new contributions, and the Technical Council deals with the “how,” ensuring that any new modules conform to specific technical characterizations.

Last, the Community ensures longevity and support for new contributions by vetting the contributor’s ability and willingness to continue to engage and maintain any new modules on a long-term basis. New functionality needs to meet all standards to be included in the standard FOLIO release.

All that said, the Product Council views itself in a supportive role for the inclusion of new functionality and wants to check in with product owners regarding new functionality, to understand how it fits into FOLIO as a whole, and consider ways to best integrate new functionality into the software and socialize it within the large FOLIO community. We recognize all new development is desired by at least one institution, and part of the goal of the review is to see how we can make it work even better for the broader community. 

# The Product Council values and criteria are as follows:

- App Description
	- Explain the App’s functionality, including any ways this app supports the FOLIO Roadmap.
	- Understand the reason for the app. Understand whether the functionality in the app supports the Roadmap, such as by filling a need identified through community priorities or a “desired state” that in an area is not actively being developed. Understand whether the app provides the FOLIO LSP with needed functionality to fill a market need.
	- TIMING: Before development begins
- App Delivery Description
	- Explain how the app will be built, including anticipated modules, integrations with existing functionality, and how delivery of the feature will occur.
	- Understand, at a high level, the technical underpinnings of the app. Understand the process for feature development.
	- TIMING: Before development begins
- Uniqueness
	- Explain whether the app introduces new functionality lacking in FOLIO or if it duplicates existing functionality. If the functionality duplicates existing functionality in FOLIO, explain why the duplication is beneficial (e.g., existing functionality doesn't work for select institutions, additional connectivity required). Consideration of whether alternatives exist and what unique aspects the app will bring to FOLIO. 
	- TIMING: Before development begins
- Dependencies
	- Explain how the app will interact with existing features in the FOLIO LSP. Share specific dependencies and plans to address adjustments that may need to be made with existing apps or modules.
	- Understand how functional dependencies are accounted for and thought out. New functionality that has an impact on existing apps or modules should demonstrate that the product owners in those areas have been consulted to make sure solutions for managing that connection make sense. May recommend conversation with App Interaction or other groups as appropriate.
	- TIMING: Before development begins
- Testing
	- Explain local testing process for the app and how work could be translated to BugFest (once approved, new functionality will be tested within FOLIO BugFest, or comparable testing mechanism, as part of the release process.
	- Provide understanding of reliability and interoperability of app with the rest of FOLIO. Provide support for FOLIO testing processes.
	- TIMING: Before development begins
- End-user Documentation
	- Share end-user documentation that is available for the app that can be provided to the product documentation. This may include information about the data model and a data dictionary. Explain how documentation will be provided for the new module and plans for managing its upkeep going forward. Technical document is covered by the TC review.
	- Apps will need to be well-documented using the same style as at docs.folio.org. Proposers will need to work with the Documentation Working group, which maintains https://docs.folio.org upon approval, and when it is released, to ensure general documentation covers the new functionality. Technical documentation is a requirement of the Technical Council review, which happens are part of the TC review.
	- TIMING: After development begins
	
# Technical and Community Council reviews

The Technical Council’s criteria are available here.

The Community Council will review the long-term viability of the contributing team and the code to see whether the FOLIO project can accept it into an official FOLIO LSP release. Definitions for support and the process to share the code with the Open Library Foundation may be detailed in a Memorandum of Understanding. 


## MOU and Next Steps

The PC will facilitate communication between the module contributors and the Community Council, who will, at their option, supply an MOU detailing their commitment. The FOLIO SMLLC will supply MOU and store the final results. The Community Council will manage the renewal of the MOUs as appropriate.


# Process Description

## What this process does:

- Provide a mechanism for interested community members to share and get feedback on ideas for new functionality and understand how to develop new apps that can be included in the official FOLIO LSP releases.
- Put potential contributors in touch with the SIG and other POs early in the process to ensure smooth development.
- Provide a framework and mechanism for the Product Council to respond to new contributions and to review and approve significant features for inclusion in an upcoming FOLIO LSP release.
- Provide a technical review process using objective criteria put in place by the Technical Council.
- Provide the Community Council with a mechanism to ensure long-term investment and stability of new apps and features, through the use of the memorandum of understanding.


## What this process does not cover:

    Any retroactive assessment of existing modules.
    Review of new code to be placed within existing modules. The Councils are always interested to learn about new functionality under development, especially as it relates to the roadmap or other planning, but changes to existing modules should follow existing processes and do not require a special review process. Product Owners with responsibilities for existing modules and areas of functionality should work through the respective SIG(s) as enhancements and updates are made.
    A review of code which will not be distributed as part of the FOLIO LSP under the FOLIO project and where the intellectual property rights will not be turned over to the OLF. As an open-source project, the FOLIO code is available for anyone to use, enhance, or modify outside of this process.
    A blueprint for long-term vision for FOLIO. This process has been designed to support the inclusion of new functionality and features under the current release framework.

https://folio-org.atlassian.net/secure/RapidBoard.jspa?rapidView=236
Submissions and Tracking

# Recommended steps for engagement with PC:

    Read through the module acceptance documentation as to the process. Please reach out to the Product Council with questions or help with this process.

# What the PC may recommend to help the development:

    Suggest follow-up conversations and put the contributors in touch with the appropriate SIGs. 
    Help recruit subject matter experts to create a new SIG or working group that can support development work
    Recommend a follow-up meeting with PC closer to the release date to see work in action.  