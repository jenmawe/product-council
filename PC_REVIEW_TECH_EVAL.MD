# New Functionality Product Council Evaluation Processes

## Overview
This document outlines the processes for **product** evaluation of new funcitonality for inclusion in a FOLIO release.  The following activities are covered:
1. Before Development
1. Submission
1. Evaluation
1. Review
1. Feedback
1. Approval/Rejection

### Supporting documentation
* Details of the JIRA workflow are captured in a separate [document](PC_REVIEW_EVAL_JIRA.md). 
* Functionality evaluation by the Product Council is part of a larger process involving the other FOLIO Councils (PC/CC). A description of the full process is currently being developed by a cross council working group. Upon completion a link to this process will be added here. 

## Before Development
* Please review the Evaluation Process for new FOLIO Functionality and Evaluation FAQ before (or as early as possible during) development, to avoid any issues which would lead to delay or rejection of the module.
* The Product Council welcomes questions. In particular, if you anticipate that the functionality will introduce any cross-app changes or other innovations that might conflict with existing PCR criteria, or would imply significant changes to the hosting environment or required infrastructure, please do reach out to the Product Council ASAP.  

## Submission
1. The Submitter fills out a form in JIRA (using a template) and submits it to the PCR Board for review.  
    * See JIRA workflow for details.
    * An Evaluator will only respond to submissions from the official Submitters as defined in the 'Roles' section of this document.
1. The Product Council will update the JIRA within 1 week (See JIRA workflow for details) with the following information:
    * Confirm receipt of the submission
    * Who will be performing the role of Evaluator, as defined in the 'Roles' section of this document
    * Provide a rough estimate for the initial evaluation to be completed
      * Should be 3 weeks or less.
    * Request additional information
      * If there are missing points of contact, the Product Council will be contacted
      * Any questions about the module will be directed to the points of contact.
    * Request a demonstration of the module
      * In some cases the PC may request a demonstration of the module
      * In such instances the Evaluator will contact the Submitter with a request for a demonstration, and a mutually suitable time for the demonstration will be scheduled.

### Submission form
Information gathered includes:
* Functionality name
* Description of functionality
* Link to source - a tag/commit in a publicly accessible git (preferably GitHub) repository 
* List of related functionality (e.g. is this a Frontend/backend pair?  Business logic/storage pair?  ePC.)
* Points of contact (Subject Matter / Domain / Technical)
  * Each point of contact's role should be clearly identified.
  * A single, main point of contact must have an account in issues.folio.org JIRA.
* Free form section for notes, clarifications, background, links to supporting documentation.
* Link to self evaluation results
* Informational Section - provides info, instead of eliciting it.
  * A link/pointer to the most recent version of the Acceptance Criteria.
  * The PC has a maximum duration of 3 weeks to perform the initial review.
    * The evaluator may have between 2 and 3 weeks, depending when the PC meeting happens during that first week.  
    * This does not include activities that happen after feedback is given, ePC. 
  * The applicable deadline for submissions in the release timeline (not the date, but the name of the milestone/deadline e.g. "deadline for new modules")

## Evaluation
1. The Product Council reviews a JIRA board to see if there are any new submissions, and check on the status of evaluations in progress.
1. If there’s a new submission, the Product Council finds one or more people to perform the role of Evaluator. 
    * The review team will be formed in a way to allow for a fair review and avoid either perceived or actual conflicts of interest.  No members should have participated in the module's development, and at least one member should be independent of the submitter's organization.  The lead evaluator will be assigned in JIRA; if the submitting team has concerns about the chosen evaluator they should contact the PC chairs within one week of the assignment.
    * JIRA workflow: the ticket is transitioned from **SUBMITTED** to **UNDER EVALUATION**
    * In order to improve notifications when the Jira is updated, the primary reviewer should be the Assignee and other members of the review team should be issue watchers.
1. The module is evaluated.
    * If the Evaluator(s) have questions, they may reach out to the Point of Contact for clarification.
      * This may be an iterative process: the evaluator and submitter may choose to iterate on the submission, making adjustment to address the questions raised. 
      * Whenever changes are made, the submitter should update the commit hash in the Jira.
    * If answers aren't provided in a timely manner, the criteria in question may be failed.
1. Upon completion of the evaluation the JIRA will be updated to indicate this.
     * JIRA workflow: the ticket is transitioned from **UNDER EVALUATION** to **PC REVIEW**

## Review
1. The Product Council reviews the evaluation results.
    * The evaluators present the evaluation results, and optionally reccommends a PC decision.
    * Asks any questions they have for the evaluators.
    * Weigh in on any subjective criteria.
    * The Product Council may ask the Evaluator(s) to make changes to the evaluation.  
    * This review may happen either out of band, during the regularly scheduled Product Council meeting, or a separate meeting scheduled specifically for this purpose.
1. The Product Council decides, using its standard protocols, to accept, provisionally accept, or reject the module, or else to defer a decision pending other action.
    * An evaluation where all criteria are met will typically result in the acceptance of a module by the Product Council.
    * An evaluation where not all criteria are met will typically result in the rejection of a module by the Product Council. However:
        * If some of the failures are due to proposed architectural (or other cross-module) changes, the PC may request that Submitter first propose those changes via the RFC process to get sufficient community input. In that situation the PC may defer its decision pending the resolution of the RFC. (See [Before Development](#Before-Development).)
        * If PC and Submitter unanimously agree on module changes that would resolve any failures, the PC may decide to provisionally accept the module with an agreed-upon timeline for the changes to be completed.  When Submitter notifies PC that the changes are complete, the reviewer(s) may update the evaluation and PC may adjust its decision.
        * If the PC determines that some failed criteria would be resolved by non-controversial changes to the criteria themselves (or referenced requirements like the Officially Supported Technologies), PC may decide to accept the module and make the agreed-upon changes.
    * When the Product Council's decision is contrary to the evaluation, or after any provisional acceptance or deferral, the Product Council is required to provide written justification for their decision.
1. Upon completion of the review, the JIRA will be updated to indicate this.
    * JIRA workflow: the ticket is transitioned from **PC REVIEW** to **APROVED** or **REJECTED**

## Feedback & Acceptance/Rejection
1. Evaluation results are published (in markdown format) to the [tech-council GitHub repository](https://github.com/folio-org/tech-council) and linked to the JIRA ticket.
    * An [Evaluation Results Template](https://github.com/folio-org/tech-council/blob/master/MODULE_EVALUATION_TEMPLATE.MD) will be used for this.
1. Interested parties (e.g. release coordinator, contributor points of contact, Product Council members, ePC.) are notified, and provided a link to the results.
    * JIRA workflow: notification is in the form of transition from **PC REVIEW** to **APROVED** or **REJECTED**
    * If failed, the Point of Contact may ask for help understanding the failed criteria.
      * The comments section of the JIRA may be used for this purpose.  
      * If a meeting is required or desired, it's the responsibility of the Point of Contact to find a time that works and set the meeting up with the review team.  The regular Product Council meeting ***will not*** be used for this purpose.
1. If applicable, the module developers resolve all issues and request a re-review.  
    * * JIRA workflow: the ticket is transitioned from  **REJECTED** to **SUBMITTED**

## Process Feedback

1. PC asks the submitter if they have any feedback on the New Module Technical Evaluation process.
    * PC considers that feedback as part of the next process evaluation improvement round.

## Roles

1. Submitter

    * Creates the JIRA ticket on the PCR board.

1. Evaluator

    * Processes a PCR ticket through the JIRA workflow
    * Can be a member of the PC or a delegate appointed by the PC
    * Must not be a member of the development team seeking approval.

1. Point of Contact 

    * Communicates relevent module information through updates to the PCR Issue in jira, once it has been created by the submitter.
    * Includes developers, product owners and other team members.
