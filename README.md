# Cash Change Breakdown Prototype

A browser exercise that subtracts a bill from cash received and divides the difference across a configured denomination list. The current implementation contains validation and message handling defects that need repair before dependable use.

## The question

How can a whole unit change amount be represented using a configured set of denominations?

## Tools and methods

HTML, CSS, JavaScript, Algorithmic thinking.

## Work in this repository

1. Implemented a descending denomination loop using integer division and remainders.
2. Displayed the note count for each configured denomination.
3. Added an interface for bill and cash values with validation branches.

## Evidence and scope

| Measure | Recorded value |
| --- | --- |
| Configured denominations | 2000, 500, 100, 20, 10, 5 and 1 |

## Repository guide

| File or folder | Purpose |
| --- | --- |
| [index.html](https://github.com/divyansh2703/cash-registor/blob/main/index.html) | Inputs and result table |
| [index.js](https://github.com/divyansh2703/cash-registor/blob/main/index.js) | Calculation and validation logic |
| [main.css](https://github.com/divyansh2703/cash-registor/blob/main/main.css) | Styling |

## Getting started

Open `index.html` in a browser to inspect the prototype. Before relying on the result, convert both inputs to valid numbers and correct the message handling function in `index.js`.

## Current limitations

1. The current cash versus bill comparison can compare input strings rather than numeric values.
2. The message function shadows the selected DOM element and needs correction.
3. The implementation uses whole denominations and does not handle fractional currency units. The configured list is an educational example.

## Next steps

1. Repair numeric validation and message handling before presenting the tool as functional.

## Authors and reuse

Divyansh Doshi.

Documentation reviewed against the public repository on 7 September 2026. Counts are taken from the named saved artifacts or directly inspected CSVs; this review did not rerun model training or validate a complete deployment. No source code licence was found in the reviewed project tree. Data and third party material may have separate terms.
