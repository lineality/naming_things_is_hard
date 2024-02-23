# naming_things_is_hard
Rules for Clearer Naming


1. Do not use the same exact name to refer to multiple things, including: do no not re-use an existing name.
2. Do not use multiple different names to refer to the same thing.
3. Do not use a misleading name, such that someone who sees the name will confidently misunderstand and believe that the name refers to something other than what it actually refers to.
4. Extreme shortness must not be a goal in and of itself. Making a name extremely short simply for the sake of aesthetics of ODC at the expense of everything else in the project is a catastrophic proliferation of liabilities.
5. The goal is for the name to clearly communicate and not miscommunicate
6. If you are referig to something unique, do not use general terms or general catagories as your specific unique name, unless there is an unavoidable exception. Where you are refering to a standardized non-unique variable (see below) still try to be clear.
#### (Rule of thumb, any reserved word in a normal programming language should NOT be a variable name.)
- Unique Names: Do not use ->
  - string (or any shorter abreviation of "string")
  - dictionary or dict
  - code
  - type
  - module
  - controller
  - text
  - variable
  - context
- Repeating Standardized Variables:
  - There will be standard-formula cases such as logging, exception handling, or other standardized procedures, or even standard 'dictionary' formats, where the same 'standard key' will be reused. (E.g. This may be re-used in every exeption-handler to standardize exception handling [e.g. error_message: X, error_code: y] as opposed to giving every error_message variable a completely new name which would arguably be less clear and less practical). Even here, try not to make the 'standard key' so vague and general that it causes confusion, or that it collides with other vague and general standard terms. Some terms such as 'response' may need to be re-used, but even there, unless there is a strong and compelling reason for the name to collide with other names do not force a collision without nessesity. Try to use a repeating name such as "error_message" or even "exception_block_error_message" instead of "text" or "messaage". An example of why this is useful, is when searching for and or refactoring these names or the code they are a part of, too many collisions are a problem. Having everything in your code simply named "text" makes finding and identifying even standardized sets of variables problematic.
7. Do not use a self-contradictory name. (e.g. "chain of one")
8. Avoid using single letters as variables, even though they are commonly used.

Stay positive and ignore the inevitable trolling, bullying and harrasement you will face for practicing and advocating for clear communication. 
