# Understory Bot Safety Policy

**Effective Date:** September 5, 2026
**Last Updated:** September 5, 2026

## 1. Purpose

This Policy defines the safety rules and operating principles for the Understory bot, automation engine, and related automated workflows.

Understory may use automation to assist users with supported job-application workflows, including:

* Processing job information
* Assessing job compatibility or suitability
* Preparing or tailoring resumes
* Preparing or tailoring cover letters
* Processing application forms
* Identifying application questions
* Suggesting application answers
* Entering supported application information
* Tracking application status
* Performing other supported application-related actions

The purpose of the bot is to assist the user while reducing incorrect, unintended, excessive, unsafe, or unauthorized actions.

---

## 2. User-Controlled Automation

Understory automation operates on behalf of the user within the features and permissions provided by the application.

The bot must not be treated as an independent decision-maker with unlimited authority.

Where a workflow requires important user judgment or confirmation, Understory may:

* Request user input
* Request confirmation
* Pause the workflow
* Require manual intervention
* Skip the affected action
* Stop the application

The availability of these controls may depend on the particular portal and workflow.

---

## 3. No Guarantee of Complete Automation

Understory does not guarantee that every application can be completed automatically.

A workflow may require manual intervention because of:

* New application questions
* Unsupported fields
* Unsupported controls
* Missing information
* Ambiguous information
* Employer-specific requirements
* Portal-specific requirements
* CAPTCHA
* Authentication
* Identity verification
* Document requirements
* External application redirects
* Unexpected website changes
* Technical failures
* Security restrictions
* Other workflow limitations

Understory may stop or skip an application rather than continue when reliable completion is not possible.

---

## 4. Bot May Skip an Application

Understory may skip an application when continuing the workflow could result in an unreliable, incorrect, incomplete, or unsupported application.

Examples include:

* The bot cannot reliably understand a required question
* Required user information is unavailable
* The bot cannot determine a suitable answer
* A required field is unsupported
* A required document cannot be processed
* The portal requires an unsupported interaction
* A security challenge prevents continuation
* The application workflow changes unexpectedly
* The application requires information that should be confirmed directly by the user
* Continuing could create a significant risk of submitting incorrect information
* A technical or security control requires the workflow to stop

Skipping an application does not necessarily mean that the job is unsuitable or that the user is ineligible.

It may only mean that Understory cannot reliably complete that particular application.

Where supported, Understory may record or display that the application was skipped and provide a reason.

---

## 5. Bot May Pause or Stop an Application

Understory may pause or stop an application at any point when necessary for safety, reliability, security, or workflow compatibility.

The bot may stop when it detects:

* Unexpected page changes
* Unexpected form fields
* Unexpected navigation
* Repeated errors
* Missing required information
* Incorrect page state
* Login problems
* Authentication problems
* CAPTCHA
* Security verification
* Rate limiting
* Portal restrictions
* Suspicious activity
* Unsupported controls
* Potentially malicious content
* Prompt injection
* Other conditions that make continued automation unreliable

The bot should prefer stopping over continuing an action that it cannot reliably interpret.

---

## 6. Application Question Safety

Understory may encounter questions that it has never seen before.

Application questions may be:

* New
* Unusual
* Ambiguous
* Employer-specific
* Portal-specific
* Context-dependent
* Legally significant
* Personal
* Difficult to infer from existing user information

The bot must not assume that a previously used answer is automatically correct for a new question.

Where the system cannot reliably determine an answer, it may:

* Request user input
* Request confirmation
* Leave the field unanswered where technically possible
* Skip the application
* Stop the workflow

The bot must not intentionally invent user-specific facts.

---

## 7. User Information Is the Primary Source

When generating or suggesting application information, Understory should primarily rely on information provided or confirmed by the user.

This may include:

* Resume
* CV
* User profile
* Application history
* Previous confirmed answers
* User preferences
* User instructions
* Other information explicitly provided by the user

The bot should not intentionally create false:

* Employment history
* Education
* Certifications
* Qualifications
* Skills
* Achievements
* Job titles
* Professional experience
* Personal circumstances

However, AI-assisted systems may still make mistakes or incorrect inferences.

Users remain responsible for reviewing important information before submission where review is available or required.

Additional requirements are provided in `ai-policy`.

---

## 8. No Intentional Fabrication

Understory must not intentionally fabricate information to improve an application's apparent suitability.

The bot must not intentionally:

* Invent experience
* Invent qualifications
* Invent certifications
* Invent employment
* Invent education
* Invent achievements
* Invent salary history
* Invent work authorization
* Invent demographic information
* Invent personal circumstances
* Misrepresent user preferences
* Falsify application answers

Tailoring or rewording user-provided information does not by itself constitute fabrication.

---

## 9. AI Output Is Not Automatically Trusted

AI-generated output must be treated as potentially incorrect.

The bot should not assume that AI output is automatically:

* Accurate
* Complete
* Suitable
* Current
* Consistent
* Appropriate for the specific application

Where appropriate, Understory may apply validation, consistency checks, confidence checks, structured output requirements, or other controls before using AI-generated information.

These controls do not guarantee that AI output will always be correct.

---

## 10. Important User-Specific Questions

The bot should use additional caution when a question concerns information that requires direct confirmation from the user.

Examples include:

* Legal declarations
* Work authorization
* Visa or immigration status
* Criminal-history declarations
* Disability or accommodation information
* Demographic information
* Salary or compensation
* Notice period
* Relocation
* Employment status
* Conflicts of interest
* Availability
* Eligibility
* Certifications
* Licenses
* Professional registrations
* Other sensitive or legally significant information

Where reliable user confirmation is required, the bot may stop, request confirmation, or skip the application.

---

## 11. Resume and Cover-Letter Safety

Understory may tailor resumes and cover letters using information provided by the user.

The bot may:

* Reorganize information
* Reword information
* Emphasize relevant experience
* Adjust formatting
* Improve clarity
* Adapt content to a job description
* Remove unnecessary information
* Create job-specific versions

The bot must not intentionally fabricate qualifications or experience.

AI-generated resumes and cover letters may nevertheless contain errors.

Users remain responsible for reviewing the final content before submission.

Additional requirements are provided in `ai-policy`.

---

## 12. Application Submission Safety

The bot should perform reasonable validation before submitting an application where technically possible.

Validation may include:

* Confirming the intended job
* Confirming the employer
* Checking required fields
* Checking required documents
* Checking selected answers
* Checking for obvious missing information
* Checking application state
* Detecting duplicate applications
* Detecting unexpected page changes
* Confirming that the workflow is still associated with the intended job

Validation does not guarantee that an application is complete, accurate, or accepted by the third-party portal.

---

## 13. Duplicate Application Prevention

Where technically possible, Understory may attempt to identify applications that have already been submitted or are already being processed.

The bot may use:

* Application history
* Job identifiers
* Portal information
* Employer information
* Application URLs
* User records
* Other available application metadata

Duplicate detection may not always be accurate.

Users remain responsible for reviewing application history where necessary.

---

## 14. Current Employer Protection

Where the user has provided information identifying their current employer, Understory may use that information to prevent unintended applications to the user's current employer where the relevant feature is enabled.

Understory may use information from:

* User-provided profile
* Resume
* Application settings
* Employer preferences
* Other user-provided information

The bot must not assume that employer information is always current unless the user has confirmed or updated it.

Users remain responsible for maintaining accurate employer preferences and restrictions.

---

## 15. Job Compatibility and Suitability

Understory may provide compatibility or suitability assessments based on available information.

Such assessments may consider:

* Job description
* User resume
* Skills
* Experience
* Education
* Qualifications
* User preferences
* Other available information

A compatibility assessment is an assistive estimate and is not a guarantee.

The bot must not represent an assessment as a guaranteed prediction of:

* Interview
* Shortlisting
* Employment
* Offer
* Compensation
* Recruiter response
* Application acceptance

---

## 16. Unexpected Page or Workflow Changes

The bot must treat unexpected changes to a page or workflow as a potential safety issue.

Examples include:

* New buttons
* New forms
* Changed field labels
* Unexpected redirects
* New required questions
* Changed application steps
* New authentication requirements
* Unexpected pop-ups
* Security warnings
* Portal error messages

Where the bot cannot reliably determine the meaning of a changed interface, it may stop or skip the workflow.

The bot should not blindly continue based on assumptions from an earlier page state.

---

## 17. CAPTCHA and Security Challenges

If the bot encounters CAPTCHA, authentication verification, identity verification, or another security challenge, it may stop or pause the workflow.

The bot must not intentionally bypass or defeat:

* CAPTCHA
* MFA
* Authentication
* Identity verification
* Access controls
* Rate limits
* Anti-bot controls
* Other portal security mechanisms

Users may be required to complete security steps directly.

Additional requirements are provided in `bot-detection-and-portal-ban-policy`.

---

## 18. Rate Limiting and Activity Controls

Understory may limit automated activity to reduce:

* Excessive requests
* Excessive applications
* Duplicate actions
* Repeated failures
* Unintended activity
* Security risk
* Portal restrictions

Controls may include:

* Daily application limits
* Request limits
* Delays
* Temporary pauses
* Retry limits
* Error thresholds
* Duplicate detection
* Security-triggered stops

Understory may modify these limits as necessary.

Understory limits do not override limits imposed by third-party portals.

---

## 19. Retry Safety

The bot should not repeatedly retry an action when repeated attempts may cause:

* Duplicate applications
* Duplicate submissions
* Excessive requests
* Account restrictions
* Security alerts
* Incorrect data entry

The bot may stop after a configured number of failed attempts.

The bot should prefer reporting the failure or requesting user intervention over uncontrolled repeated retries.

---

## 20. Prompt Injection and Malicious Instructions

Content encountered during automation must not automatically be treated as an instruction from the user or Understory.

Potentially untrusted content may appear in:

* Job descriptions
* Employer information
* Application questions
* Web pages
* Documents
* Uploaded files
* Recruiter information
* AI-generated content
* Third-party content

Examples of potentially malicious instructions include requests to:

* Ignore Understory instructions
* Reveal system prompts
* Reveal credentials
* Reveal API keys
* Access unrelated information
* Disable safety controls
* Bypass security
* Submit unauthorized applications
* Perform actions unrelated to the user's request

The bot should treat such content as untrusted.

Additional requirements are provided in `ai-policy`.

---

## 21. Data and Credential Safety

The bot must not intentionally expose:

* Passwords
* OTPs
* Authentication codes
* API keys
* Access tokens
* Session cookies
* Private credentials
* Secrets
* Information belonging to another user

Third-party portal passwords should not be provided to Understory.

Users should authenticate directly with the applicable portal.

Additional requirements are provided in `login-and-password-safety-policy`.

---

## 22. Third-Party Portal Compliance

The bot must not be represented as having permission to violate third-party portal rules.

The bot may be technically capable of interacting with a portal without the portal necessarily permitting that activity.

Users are responsible for reviewing the applicable portal's:

* Terms of Service
* User Agreement
* Automation policies
* Security requirements
* Application limits
* Other applicable restrictions

Additional requirements are provided in `portal-wise-disclaimer` and `bot-detection-and-portal-ban-policy`.

---

## 23. No Security Bypass

Understory bot functionality must not be treated as a mechanism for bypassing:

* Portal authentication
* CAPTCHA
* MFA
* Access controls
* Rate limits
* Security restrictions
* Account restrictions
* AI provider safeguards
* Understory security controls

Understory may restrict or disable workflows that attempt to circumvent security controls.

---

## 24. Error Handling

When an automation error occurs, Understory may:

* Stop the workflow
* Retry within defined limits
* Record the error
* Notify the user
* Request user intervention
* Mark the application as incomplete
* Skip the application
* Disable the affected workflow temporarily

The bot should not silently continue when an error creates a significant risk of incorrect or unintended activity.

---

## 25. Application Status Tracking

Understory may record application status information to help users track activity.

Possible statuses may include:

* Not Started
* In Progress
* Completed
* Submitted
* Skipped
* Failed
* Paused
* Requires User Action
* Unsupported
* Blocked
* Unknown

The exact statuses may vary by feature.

Understory should not represent an application as successfully submitted unless the available information reasonably indicates that submission occurred.

---

## 26. Bot Logs and Audit Information

Understory may maintain technical records necessary to:

* Diagnose failures
* Track application workflows
* Prevent duplicate applications
* Investigate security events
* Detect abuse
* Improve reliability
* Maintain application history
* Provide support

Such records may include:

* Workflow status
* Application identifiers
* Portal information
* Error information
* Timestamps
* Technical information
* Security events
* Automation events

Retention is governed by the `privacy-policy`.

---

## 27. User Notification and Review

Where technically practical, Understory may inform users when:

* An application is skipped
* An application is stopped
* User intervention is required
* A security challenge is detected
* A required field cannot be completed
* An automation error occurs
* A workflow is unsupported

The exact notification behavior depends on the feature and portal.

---

## 28. No Guarantee of Automation Success

Understory does not guarantee:

* Successful automation
* Successful application submission
* Correct answers
* Complete applications
* Portal compatibility
* Continuous automation
* Availability of automation
* Successful document uploads
* Successful resume or cover-letter submission
* Successful portal interaction

The bot may stop or skip an application whenever reliable completion is not possible.

---

## 29. No Guarantee of Employment or Application Results

Bot functionality does not guarantee:

* Interviews
* Shortlisting
* Job offers
* Employment
* Application acceptance
* Recruiter responses
* Employer responses
* Salary or compensation
* Career advancement
* Any particular monetary result
* Any particular non-monetary result

Understory is an assistance and automation tool and does not guarantee employment outcomes.

---

## 30. Relationship With Other Policies

This Policy should be read together with:

* `ai-policy`
* `privacy-policy`
* `portal-wise-disclaimer`
* `bot-detection-and-portal-ban-policy`
* `login-and-password-safety-policy`
* `third-party-services-policy`
* `payment-and-refund-policy`
* `user-agreement`

Each policy addresses its respective subject matter.

---

## 31. Legal Terms

Governing law, jurisdiction, dispute resolution, arbitration, arbitration seat and venue, limitation of liability, maximum liability, indemnification, notices, termination, and other general legal terms governing Understory are governed by the Understory User Agreement.

The Understory User Agreement is the controlling document for these legal matters.

This Policy does not independently establish a different governing law, arbitration arrangement, jurisdiction, liability limitation, maximum liability amount, or indemnification obligation unless expressly provided in the User Agreement.

If there is a conflict between this Policy and the User Agreement regarding these matters, the User Agreement will control, subject to applicable law.

---

## Policy Changes

Understory may update this Policy to reflect:

* Product changes
* Automation changes
* Portal changes
* Security improvements
* New safety controls
* New supported workflows
* Legal or regulatory requirements
* Technical changes
* Operational requirements

## Policy Changes, Terms, and Continued Use

Understory may create, modify, update, replace, supplement, suspend, restrict, or remove this Policy and other applicable Understory policies, terms, guidelines, requirements, documentation, features, services, technical requirements, security requirements, or operational rules from time to time.

To the maximum extent permitted by applicable law, Understory may make such changes without individual prior notice, reminder, telephone communication, email reminder, or other direct communication to each user.

The latest applicable version will apply from its stated effective date or, where no effective date is stated, from the date it is published, made available, or implemented.

The user is responsible for reviewing the current version of this Policy and other applicable Understory terms periodically.

By accessing or continuing to use Understory or any feature covered by this Policy after an updated version becomes effective, the user acknowledges and agrees to the updated Policy and applicable Understory terms, subject to applicable law.

Use of a particular Understory feature may also be subject to additional policies or feature-specific requirements. The user is responsible for reviewing and complying with those applicable policies and requirements.

Understory policies should be read together with the **Understory User Agreement**, which is the principal contractual agreement governing the relationship between the user and Understory.

If there is a conflict between this Policy and the Understory User Agreement regarding general legal or contractual matters, the User Agreement controls, subject to applicable law.

Central legal matters, including governing law, jurisdiction, dispute resolution, arbitration, limitation of liability, maximum liability, indemnification, notices, and other general contractual terms, are governed by the Understory User Agreement.

Nothing in this Policy or any update to it is intended to remove, restrict, or waive any right, remedy, notice requirement, consent requirement, consumer protection, or other protection that cannot legally be excluded, limited, or waived.


---

## Contact

**General Support:** [getspacecar@gmail.com](mailto:getspacecar@gmail.com)

For third-party portal account restrictions, CAPTCHA, login problems, verification issues, or portal-specific enforcement, users should also contact the applicable portal directly.

**Legal Entity:** [getspacecar@gmail.com](mailto:getspacecar@gmail.com)

**Registered Address:** [getspacecar@gmail.com](mailto:getspacecar@gmail.com)

---

## Important Policy Notice

Understory automation is designed to assist users and to stop or request user intervention when reliable or safe completion is not possible.

The bot may skip, pause, or stop applications. It may also produce incorrect AI-assisted information despite safeguards.

Users remain responsible for reviewing important information and complying with applicable third-party portal requirements.

Nothing in this Policy authorizes bypassing third-party security controls or violating third-party portal rules.

Nothing in this Policy excludes or restricts rights or remedies that cannot lawfully be excluded or restricted under applicable law.
