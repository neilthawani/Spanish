##### Regex for appending pipe to beginning of line
*Find What:* `^([A-Z.])`
*Replace With:* `| $1`

##### Regex for appending pipe to end of line
*Find What:* `([A-Z.])$`
*Replace With:* `$1 |`