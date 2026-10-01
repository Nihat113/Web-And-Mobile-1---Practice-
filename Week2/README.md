# Week 2 Seminar Starter Project

Open `index.html` in your editor and browser.

Your task is to repair and complete the page by:

1. replacing generic `div` and `span` elements where a semantic element better communicates the content purpose;
2. creating a logical heading hierarchy;
3. completing the student-experience questionnaire with suitable form controls and attributes;
4. connecting every control to a visible label;
5. grouping related controls with `fieldset` and `legend`;
6. testing fragment links, keyboard navigation, native validation, submission, and reset behavior; and
7. explaining your important semantic and form-control decisions.

Do not add CSS or JavaScript. Do not replace every `div` or `span` automatically—retain a generic element when its role is genuinely generic and you can justify the decision.

## Finish-early extension

Before the questionnaire, add a headed **Workshop availability** section containing a table.

Use these columns and records:

| Workshop | Day | Time | Seats available |
| --- | --- | --- | --- |
| Semantic structure | Monday | 14:00 | 12 |
| Form controls | Wednesday | 11:00 | 8 |
| Accessibility review | Friday | 15:00 | 10 |

Your table must include:

- a descriptive `caption`;
- `thead` and `tbody`;
- `th scope="col"` for each column header;
- `th scope="row"` for each workshop name; and
- `td` for the remaining values.

Do not use `rowspan` or `colspan`. Do not use the table to arrange any part of the questionnaire. Check that the caption explains what the table contains and that each data cell can be interpreted through its row and column headers.
