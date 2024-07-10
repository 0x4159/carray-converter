# C Array Converter

This utility takes 8-bit comma separated values enclosed in curly braces, and formats it based on the selected options. Conversion is done in the browser, so none of your data is transmitted to an external server.

## Options
| Option | Description |
| - | - |
| Optput as | Toggle between hexadecimal (default) or decimal output |
| Skip hex prefix | Applies when output is hexidecimal. Skipping the 0x makes it easier to copy output to an external hex editor |
| Skip adding comma | Skipping commas between elements makes it easier to copy output to an external hex editor |
| Skip adding newlines | Skip adding newline after character limit or element limit. Overrides following two options |
| Enable char count line break | Sets a max number of characters in a line before a line break is inserted |
| Enable element count line break | Sets a max number of elements in a line fore a line break is inserted |
| Indentation | Set the indentation for each line with elements. Select from the list of options or input a custom string |

## Notes
- Only the the data in the first set of curly braces is converted
- Text before and after the curly braces are preserved (whitespace trimmed)
