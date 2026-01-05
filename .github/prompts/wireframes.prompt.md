---
mode: agent
---
# Prototype Generation Instructions
Create a web-based prototype based on the wireframe description provided. Follow these guidelines:

- colors should be neutral, no other colors to have a feel of a wireframe

- strictly follow the what forms, buttons, and other UI elements are described in the prompt. Do not add any extra elements or features. for example, if a form has 3 fields, do not add more fields. If it is not mentioned to have a search bar, do not add one. if it is one form on a page, do not add more forms or separate it.

- add navigation items only if they are mentioned in the prompt. otherwise, keep the sidebar items based on the name of the htmlfiles in the root folder.

- form fields, titles, button labels, and other text content should always be vertically aligned.

- do not change the existing navigation items unless specified in the prompt.
- if action buttons are mentioned, add them. if not mentioned, just use reset and submit buttons for forms and aligned it to the right.

- if a reference image is mentioned, use it as a guide for this specific wireframe.

- if OpenApi schema is provided, use it to understand the data structure and fields required for forms and other UI elements.


- if OpenApi schema is provided, ask the user what type of components they want for each field if not specified. for example, text input, dropdown, radio button, checkbox etc.

- by default, use text input for string fields, number input for number fields, date picker for date fields, checkbox for boolean fields, and dropdown for enum fields.

- do not create a wireframe if the prompt does not specifies fields or openAPI schema. Ask the user to provide the required information.