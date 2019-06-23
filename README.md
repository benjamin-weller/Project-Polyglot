# Project Polyglot

**Context switching sucks, so don't!**

Programming entirely in pseudocode. All done through VS code snippets.

Supports ~50 common patterns in Python, JavaScript, and Java.

| Key                             | Meaning  |
| ------------------------------- | -------- |
| Supported with a common API     | &#9989;  |
| Looking for improvement         | &#10024; |
| Not currently possible/feasible | &#9940;  |
| Not implemented                 | &#10060; |

## Features

| Feature                                | Python   | JavaScript | Java     |
| -------------------------------------- | -------- | ---------- | -------- |
| print                                  | &#9989;  | &#9989;    | &#9989;  |
| if_else                                | &#9989;  | &#9989;    | &#9989;  |
| if_elseif_else                         | &#9989;  | &#9989;    | &#9989;  |
| while_loop                             | &#9989;  | &#9989;    | &#9989;  |
| for_loop                               | &#9989;  | &#9989;    | &#9989;  |
| break                                  | &#9989;  | &#9989;    | &#9989;  |
| return                                 | &#9989;  | &#9989;    | &#9989;  |
| system_exit                            | &#9989;  | &#9989;    | &#9989;  |
| ternary/conditional                    | &#9989;  | &#9989;    | &#9989;  |
| try_catch_finally                      | &#9989;  | &#9989;    | &#9989;  |
| try_catch                              | &#9989;  | &#9989;    | &#9989;  |
| lambda                                 | &#9989;  | &#9989;    | &#9989;  |
| user_input                             | &#9989;  | &#9989;    | &#9989;  |
| string_interpolation                   | &#10024; | &#9989;    | &#9989;  |
| main_entry                             | &#9989;  | &#9940;    | &#9989;  |
| regex_match                            | &#9989;  | &#9989;    | &#10024; |
| block_comment                          | &#9989;  | &#9989;    | &#9989;  |
| switch                                 | &#9940;  | &#9989;    | &#9989;  |
| reserved_words                         | &#9989;  | &#10024;   | &#10024; |
| array_slice                            | &#10024; | &#9989;    | &#9989;  |
| do_while                               | &#9940;  | &#9989;    | &#9989;  |
| variable_declaration                   | &#10024; | &#9989;    | &#9989;  |
| constant                               | &#9940;  | &#9989;    | &#9989;  |
| large_number                           | &#9989;  | &#9989;    | &#9989;  |
| small_number                           | &#9989;  | &#9989;    | &#9989;  |
| regex_replace                          | &#9989;  | &#9989;    | &#10024; |
| bitwise_or                             | &#9989;  | &#9989;    | &#9989;  |
| bitwise_and                            | &#9989;  | &#9989;    | &#9989;  |
| bitwise_xor                            | &#9989;  | &#9989;    | &#9989;  |
| bitwise_negation                       | &#9989;  | &#9989;    | &#9989;  |
| bit_shift_left                         | &#9989;  | &#9989;    | &#9989;  |
| bit_shift_right                        | &#9989;  | &#9989;    | &#9989;  |
| return_long_standing_variable_function | &#9989;  | &#9989;    | &#9989;  |
| return_long_standing_variable_method   | &#9989;  | &#9989;    | &#9989;  |
| read_file                              | &#9989;  | &#9989;    | &#9989;  |
| get_command_output                     | &#9989;  | &#9989;    | &#10024; |
| run_command                            | &#9989;  | &#9989;    | &#10024; |
| method                                 | &#9989;  | &#9989;    | &#9989;  |
| function                               | &#9989;  | &#9989;    | &#10024; |
| static_method                          | &#9989;  | &#9989;    | &#9989;  |
| map                                    | &#9989;  | &#9989;    | &#10024; |
| cast                                   | &#9989;  | &#9989;    | &#10024; |
| filter                                 | &#9989;  | &#9989;    | &#10024; |
| reduce                                 | &#9989;  | &#9989;    | &#10024; |
| base_class                             | &#9989;  | &#10060;   | &#10060; |
| inheritance_class                      | &#9989;  | &#10060;   | &#10060; |

regex replace doesn't work for python

check out the file reading thing for javascript

Proposed snippets:

Selenium 

Dedicated logging

Catch excess function parameters?

## Help, how do I...?

### Make intellisense still appear when I'm in a snippet

"editor.suggest.snippetsPreventQuickSuggestions": false,

### Make snippets appear first on the list of intellisense

"editor.snippetSuggestions": "top",

## Make a pull request for something you use!