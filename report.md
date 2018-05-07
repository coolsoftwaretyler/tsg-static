# THC Staffing Group WCAG Updates
## Potential Problems - Outstanding
- The issues in this section haven't yet been resolved, and may not need to be. They weren't on the list of "known issues", but we can get closer to AA standards if we consider making these changes.

### Success Criteria 2.4.1 Bypass Blocks (A)
- *Check 28:* Document may be missing a "skip to content" link.
  - This is subjective. I don't think you need a "skip to content" link because most of the pages have content ale way at the top. If you want to go the extra mile, we can add one, though.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form*

### Success Criteria 2.4.2 Page Titled (A)
- *Check 54:* title might not describe the document.
    - This warning is talking about the page titles, which are:

      - THC Staffing Group | The Revolution is Hiring
      - THC Staffing Group | About
      - THC Staffing Group | For Employers
      - THC Staffing Group | For Candidates
      - Events
      - Employer Form
      - Non-Discrimination Policy
      - Submit Resume for Review

    - This is up to you. I think the title is sufficient, and generally tells people what to expect: that TSG is a staffing agency, hiring people in a new industry. But you could, if you want, create a more verbose title. It wouldn't be as good for Search Engine Optimization, though.
    - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form*

### Success Criteria 3.3.3 Error Suggestion (AA)
- *Check 268:* Form submission error messages may not provide assistance.
- *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form*


### Success Criteria 3.3.4 Error Prevention (Legal, Financial, Data) (AA)
- *Check 269:* Form submission data may not be presented to the user before final acceptance of an irreversable transaction.
  - It depends if you consider submitting these contact forms as "irreversible" - my opinion is that it is not a financially or legally binding form, and there is no harm in omitting this. It might take a few extra hours for me to add this functionality if you want it.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form*
- *Check 272:* Form may delete information without allowing for recovery.
- *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form*

## Potential Problems - Resolved

### Success Criteria 1.1.1 Non-text Content (A)
- *Check 8:* Img may require a long description
  - Since the image is a link, the alt text describes the type of image, and where it leads to.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 16:* Alt text is not empty and may be decorative
  - These images are not strictly decorative - alt text was added to describe where the link leads.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*  
- *Check 178:* Alt text does not convey the same information as the image
  - These images are decorative, and empty alt tags were added as per WCAG practices.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 1.3.1 Info and Relationships (A)
- *Check 241:* Tabular information may be missing table markup.
  - This is not a table, but rather the opening `<body>` tag left over from the WordPress conversion.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 248:* Visual lists may not be properly marked.
  - Again, this is not a table, but the opening `<body>` tag left over from WordPress.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 270:* Unicode right-to-left marks or left-to-right marks may be required.
  - This would be required if the website featured any type of language that reads in a different direction than English. This web site does not.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 271:* dir attribute may be required to identify changes in text direction.
  - Same as Check 270.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 211:* input element label, type of "text", is not positioned close to control.
  - The `<honeypot>` label and control are left empty and hidden to prevent spam submissions. This is not a user-facing element, and does not need to meet this criteria.
  - On the Employer Form page, there are more of these instances, but each label is placed correctly and very close to the control elements.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 96:* textarea label is not positioned close to control.
    - There is no label here, no need to position it to control. The control is properly titled.
    - *Home, About, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 1.3.3 Sensory Characteristics (A)
- *Check 250:* Text may refer to items by shape, size, or relative position alone.
  - It does not.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 1.4.1 Use of Color (A)

- *Check 14:* Image may be using color alone.
  - These images do not use color alone, they either have text, as the TSG logo does, have descriptive alt tags, or are decorative images of people being quoted, and are therefore tagged with empty alt attributes.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 251:* Image may contain text with poor contrast.
  - Same response to check 14.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 55:* input possibly using color alone.
  - These inputs use text, are appropriately titled, and navigable.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 86:* script may use color alone.
  - These scripts do not use color alone: they are mostly sliders, which change images or paragraphs, or they provide font utilities.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 1.4.5 Images of Text (AA)

- *Check 11:* Image may contain text that is not in Alt text.
  - The logos contain only text found in alt text, and the headshots do not need to meet this requirement.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 2.1.1 Keyboard (A)

- *Check 89:* script user interface may not be accessible.
  - These scripts do not provide or require a user interface, and therefore do not need to be utilized by a keyboard.
    - One exception is the main slider on the Home Page, to which `tabindex = "0"` was added for accessibility.
    - The Submit Resume for Review and Employer Forms have appropriate tab indices.
    - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 2.3.1 Three Flashes or Below Threshold (A)

- *Check 87:* script may cause screen flicker.
  - On the home page, this script only causes one flicker - on the initial loading of the images. This is below the threshold.
  - On the about page, there is no flicker.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 2.4.1 Bypass Blocks (A)

- *Check 262:* Groups of links with a related purpose are not marked.
  - This check is, again, misreading the opening `<body>` tag as a "group of links".
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 2.4.4 Link Purpose (In Context) (A)

- *Check 19:* Link text may not be meaningful.
  - I believe the text to be descriptive and meaningful for all of these links.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
- *Check 197:* Anchor text may not identify the link destination.
  - I believe the text to be descriptive and meaningful for all of these links.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 2.4.6 Headings and Labels (AA)

- *Check 43:* h2 may be used for formatting.
- *Check 44:* h3 may be used for formatting.
- *Check 45:* h4 may be used for formatting.
- *Check 46:* h5 may be used for formatting.
  - This check was caught in the initial audit and was resolved. All of the headings follow each other chronologically, and styling is done through id tags and classes, not the heading attributes.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*


### Success Criteria 3.1.2 Language Parts (AA)

- *Check 110:* Words or phrases that are not in the document's primary language may not be identified.
  - There are no words or phrases not in the primary language. The auditing software caught the opening `<body>` tag again.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 3.2.3 Consistent Navigation (AA)

- *Check 276:* Repeated components may not appear in the same relative order each time they appear.
  - This is another subjective criterion, and I believe that the site layout is consistent enough to pass this. It is true that not every single page is identical, which may not pass at the strictest standards, but the format is predictable enough to make it easy to use with accessibility software.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

- *Check 265:* Tab order may not follow logical order.
  - It does. I've changed all `tabindex` attributes to `tabindex = "0"`
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 3.2.4 Consistent Identification (AA)

- *Check 131:* Long quotations may not be marked using the blockquote element.
  - The auditing software caught the `<body>` tag again. Long quotes are, in fact, marked as blockquotes in the slider.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

### Success Criteria 3.3.1 Error Identification (A)

- *Check 267:* Form submission error messages may not identify empty required fields.
  - This check caught the `<honeypot>` field again - which is intentionally left blank and unidentified to prevent spam. It won't interfere with accessibility software because it's marked with a label that describes its purpose.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

- *Check 246:* All required form fields may not be indicated as required.
  - I've changed the placeholder text for the contact form to include "(Required)" - the software can't read it appropriately and throws this error.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

- *Check 189:* label may not describe its associated control.
  - The three listed labels are, in fact, descriptive of the control.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*

- *Check 218:* input element, type of "text", label may not describe the purpose or function of the control.
  - This check caught the `<honeypot>` field again - which is intentionally left blank and unidentified to prevent spam. It won't interfere with accessibility software because it's marked with a label that describes its purpose.
  - On the About Page, this check caught the entire contact form. However, each field is marked with a placeholder text and title which describes the purpose of each field.
  - *Home, About, Employers, Candidates, Events, Submit Resume for Review, Employer Form, Non-Discrimination Policy*
