Accessibility statement
=======================

This is the accessibility statement for the MOOC learning environment (<https://courses.mooc.fi/>). The statement was last updated on 17 June 2025.

The website is governed by the Act on the Provision of Digital Services (306/2019). The Act stipulates that public online services must be accessible, which means that everyone must have equal opportunities to use them.

Service accessibility
---------------------

The MOOC learning environment complies largely with the relevant requirements. However, the website is not yet fully compliant with the [Act on the Provision of Digital Services (306/2019)](https://www.finlex.fi/fi/laki/alkup/2019/20190306) (in Finnish).

After an external provider tested the service for accessibility in May 2025, we have fixed some of the accessibility deficiencies. Those remaining are listed below.

Currently inaccessible content and features (WCAG success criteria in brackets)
-------------------------------------------------------------------------------

### General

-   Checkboxes: The contrast ratio of selected checkboxes is insufficient (WCAG 1.4.1, 1.4.11).

-   Content language: The programmatic language is not always consistent with the actual language (WCAG 3.1.2).

-   Support for narrow screens: Not all content adjusts to a 320 px-wide browser window without requiring horizontal scrolling (WCAG 1.4.10).

-   Page titles: Page titles are not always unique or descriptive of content on the active page (WCAG 2.4.2).

-   Page-to-page navigation: Screen readers do not consistently provide feedback when the user navigates to a new page (WCAG 1.3.1).

### Website features

-   The feature 'Improve material' cannot be used with a keyboard or assistive technologies (WCAG 2.1.1).

-   Footnotes cannot be opened or used with a keyboard or screen reader (WCAG 1.3.1, 2.1.1). Footnotes overlay other content and cannot be closed without moving the pointer (WCAG 1.4.13).

-   Peer and self-assessment cannot be completed with only a keyboard or screen reader (WCAG 2.1.1). The selected value cannot be programmatically determined (WCAG 1.3.1). The comment field label has not been programmatically associated with the field (WCAG 1.3.1, 4.1.2). The progress bar for peer assessment does not scale appropriately for narrow screens (WCAG 1.4.10).

-   Error messages in the login form are not announced by screen readers (WCAG 4.1.3). Link contrast ratio is insufficient (WCAG 1.4.3).

-   For the feedback feature, the contrast ratio of the keyboard focus indicator is insufficient (WCAG 1.4.11). Focus does not move logically when the feedback dialogue opens (WCAG 2.4.3). The dialogue does not adapt to narrow screens (WCAG 1.4.10).

-   The congratulation and certificate creation feature has some accessibility issues: the accessible name of the link does not match its visually presented text (WCAG 2.5.3), the heading structure is not entirely logical (WCAG 1.3.1), and the text contrast ratio is insufficient in some areas (WCAG 1.4.3). The certificate lacks alternative text matching its content (WCAG 1.1.1, 1.4.5).

-   Screen readers receive no notification when the chatbot dialogue opens or new messages arrive (WCAG 1.3.1, 4.1.3). The user's messages are not programmatically determinable from the bot's messages (WCAG 1.3.1). The contrast ratio of some text and user interface elements is insufficient (WCAG 1.4.3, 1.4.11).

-   The accessible name of the user menu in the header does not consistently convey its status, nor is the status programmatically determined (WCAG 1.3.1) (WCAG 1.3.1, 4.1.2). The menu contains nested buttons and links (WCAG 1.3.1). The contrast ratio of the menu text falls slightly short of the required minimum (WCAG 1.4.3).

-   The registration form contains deficiencies in the contrast ratio of text fields (WCAG 1.4.11), the labelling of element groups (WCAG 1.3.1) and the marking of compulsory fields (WCAG 3.3.2).

-   The status of the language menu is not programmatically determined (WCAG 1.3.1, 4.1.2).

-   The accessible text of links in the course list does not match their visible text, and not all information is available to users of assistive technologies (WCAG 2.5.3).

-   Although changing the language from the course menu changes the on-screen language immediately, the programmatic language is not updated accordingly (WCAG 3.1.2).

-   In the search dialogue, assistive technologies do not receive updates about dynamically displayed search results (WCAG 1.3.1). The alternative text 'Search for pages' for the search button in the header may be misleading to screen reader users (WCAG 1.1.1).

-   The radio button group for the report feature is not programmatically determined (WCAG 1.3.1). The description field does not always include a visible label or an accessible name that can be programmatically read (WCAG 3.3.2, 4.1.2).

### Content blocks

-   Page audio: The site's listening feature is not compatible with screen readers (WCAG 4.1.2). After launching, the audio player does not receive keyboard focus (WCAG 2.4.3).

-   Flip card content cannot be accessed with assistive technologies or keyboard controls (WCAG 1.3.1, 2.1.1). The card user interface text has low contrast ratio (WCAG 1.4.3). Content does not adapt appropriately to narrow screens (WCAG 1.4.10).

-   Glossary tips cannot be accessed with a keyboard or screen reader (WCAG 1.3.1, 2.1.1). The tips obscure other content and cannot be closed without moving the cursor (WCAG 1.4.13).

-   Expandable sections do not operate as expected when using a keyboard (WCAG 2.1.1). Buttons used to open content lack accessible names (WCAG 4.1.2).

-   Buttons and file upload blocks contain nested links and buttons, which may be confusing for users of assistive technologies. File links are preceded by an empty invisible link, resulting in screen readers typically reading the full file name (WCAG 1.3.1).

-   Terminology blocks are missing semantically correct headings (WCAG 1.3.1).

-   Progress indicators for chapters and courses are not fully accessible for users of assistive technologies and those with colour vision limitations (WCAG 1.3.1, 1.4.1).

-   The programmatic heading structure of course content tables does not fully align with their visual hierarchy (WCAG 1.3.1).

-   The heading hierarchy of the 'Authors' section does not align with its visual hierarchy (WCAG 1.3.1).

-   The contrast ratio between chapter main images and the overlaid text is not always sufficient (WCAG 1.4.3).

-   Errors in the programmatic structure of image elements may hinder the ability of assistive technologies to interpret accompanying text (WCAG 1.3.1).

### Assignment types

-   Accessibility deficiencies common to assignment types:

    -   If heading text is less than 24px in size, white on purple colour contrast does not meet the required minimum ratio of 4.5:1 (WCAG 1.4.3).

    -   Longer headings overlap other content on narrow screens (WCAG 1.4.10).

    -   For some assignment types, the correct order of heading levels is not maintained (WCAG 1.3.1). This hampers content comprehension for screen reader users.

    -   Decorative icons (Tries, Points) are not ignored by all screen readers, including Voiceover with Safari on macOS (WCAG 1.1.1).

    -   Some assignment types include an untitled iframe element surrounding content (WCAG 4.1.2). On mobile devices, the TalkBack screen reader moves focus to these elements during forward and backward navigation.

    -   Selecting the 'Submit' button in various assignment types does not trigger screen reader feedback (WCAG 4.1.3).

-   'Select N exercise': The status of buttons (selected/not selected) is not programmatically determined (WCAG 1.3.1). Perceiving the status is difficult for users with colour vision limitations (WCAG 1.4.1).

-   Multiple-choice questions: Perceiving the button status is difficult for users with colour vision limitations (WCAG 1.4.1). Questions and buttons are not programmatically grouped. Labels for drop-down menus are not programmatically linked (WCAG 1.3.1).

-   For essay assignments, the label is not programmatically linked to the text field (WCAG 1.3.1). The text field is poorly distinguishable from its background (WCAG 1.4.11). Exceeding the permitted character count does not trigger notifications for screen reader users (WCAG 4.1.3).

-   The text fields for supplementary assignments lack descriptive labels associating them with the surrounding sentence for assistive technology users (WCAG 1.3.1).

-   For assignments involving text highlighting, the contrast ratio between the selected text and its surroundings is insufficient (WCAG 1.4.1, 1.4.11)

-   For assignments involving a scale, radio buttons lack a visible focus indicator (WCAG 2.4.7). In addition, the radio buttons are poorly distinguishable from their background (WCAG 1.4.11). Labels for text fields are not programmatically linked to their corresponding fields (WCAG 1.3.1).

-   Timeline assignments fail to scale appropriately on very narrow screens (WCAG 1.4.10). The assignments' drop-down menus lack sufficient contrast (WCAG 1.4.11). All deselect buttons share the same name, which may make it difficult for assistive technology users to identify the correct option (WCAG 1.3.1).

-   Assignments using drop-down menus to select suitable words for a sentence indicate correct and incorrect answers with icons that have insufficient contrast against the background (WCAG 1.4.11).

-   For closed questions, the contrast ratio between text fields and their background is insufficient (WCAG 1.4.11). When an incorrect answer is given, the accessible name of the field changes, making it difficult for users of assistive technologies to modify their response (WCAG 1.3.1, 2.5.3).

-   In matrix assignments, the accessible names of text fields for numeric input do not accurately reflect their matrix positions (WCAG 1.3.1). Separating lines in matrix tables are too faint (WCAG 1.4.11). Fields lack visible focus indicators (WCAG 2.4.7). Matrix input fields lack visible instructions (WCAG 3.3.2).

Our commitment to enhancing accessibility
-----------------------------------------

We are working to enhance the accessibility of this online service. Our goal is to address critical accessibility issues by the end of 2025 and resolve remaining issues in 2026.

Feedback and contact details
----------------------------

You may send accessibility feedback by email to <mooc@helsinki.fi>. Use 'Accessibility feedback' as the subject line of your message and include a description of the relevant page and issue. Please note that it may take up to 14 days to receive a response. The accessibility of the courses.mooc.fi website and the processing of feedback are the responsibility of the MOOC Centre.

Enforcement procedure
---------------------

If you are dissatisfied with a response or do not receive one within two weeks, [you may submit a complaint to the supervisory authority](https://www.saavutettavuusvaatimukset.fi/en/user-rights/submit-complaint-web-accessibility-or-request-clarification). The authority's website has detailed instructions on how to submit a complaint and how the issue will be handled.

Contact information of the supervisory authority
------------------------------------------------

Finnish Transport and Communications Agency Traficom

Digital Accessibility Supervision Unit

[www.webaccessibility.fi](https://www.webaccessibility.fi)

<saavutettavuus@traficom.fi>

+358 29 534 5000 (switchboard)
