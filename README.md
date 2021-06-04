# custom-actions-examples
This is a repository of custom action steps that work with Testim.io

Initially it includes custom action steps (JavaScript) that we have created for customers. The code can be copied from here and added to a custom step in a Testim test. Instructions on how to use each example are included in the linked file with the JavaScript code needed. Typically it will involve copying the file and code into a custom step, making a change or two to the properties panel, checking your variables, and perhaps pointing to the correct element. 

[Generate Faked Data](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/Generate-Faked-Data.js) (faker.js) - Uses the faker.js library to create fake test data. 

[Link Checker](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/link-checker.js) (CLI) - Finds links at the given URL and validates that they are working. 

[Network Performance Checker](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/network-performance-checker.js) - Validate that all network requests are completed under maxResponseTime milliseconds. 

[Network Performance Summary](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/network-performance-summary.js) - Creates a summary of network requests with min/max/avg duration and request size. 

[Network Validate Request](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/network-validate.js) - Validate that a network request returns the proper status and/or is not slower than maxDuration (ms).

[Popup Killer](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/popup-killer.js) - When you don't know when a popup modal will kill your test, use this to handle it.

[Redact data](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/Redact-data.js) - This custom step creates an overlay element to prevent screenshot capture of private data.

[Select Item/Option by Text/Value](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/select-by-text.js) - Select an item by value or text (select/option, ul/li. table/tr)

[Set Text](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/set-text-encrypted.js) (Encrypted) - Takes encrypted data, decrypts it and sets the text of a target field and optionally redacts it.

[Validate Select Items/Options](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/validate-select-items.js) - Validate that expected items are in a list/select.

[Validate Select Items/Options Order](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/select-order-validate.js) - Validates that the items in a list are sorted properly.

[Validate Element Computed Style(s)](https://github.com/testimio/custom-actions-examples/blob/main/testim-created/validate-computed-style.js) - Validate a superset/subset of style for an element
