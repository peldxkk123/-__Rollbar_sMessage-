# -__Rollbar_sMessage-
; Write code that causes an error you want to catch, then call  ; _Rollbar_Send ; Parameters ....:  $__Rollbar_sErrorLevel      - [Required] Must be one of the following values: Debug, Info, Warning, Error, Critical. ;                   $__Rollbar_sMessage         - [Required] The message to be sent. This should contain any useful debugging info that will help you debug. ;                   $__Rollbar_sMessageSummary  - [Optional] A string that will be used as the title of the Item occurrences will be grouped into. Max length 255 characters. If omitted, Rollbar will determine this on the backend.
