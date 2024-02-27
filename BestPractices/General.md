# General Best Practices

add short description to scripts when available

use condition statentment if condition field is available dependintg on scripting location

comment your code

follow a convention

wrap code in functions to prevent pollluting the global namespace

do not use hardcoded values

use descriptive variables and function names

verify a value exists before using it

let the database do the work

## Server-Side

Use GlideAggregate over GlideRecord when dealing with aggregates like counts

Log Records before deleting

Use GlideRecordSecure where appropriate

Use Script Includes over global Business Rules

## Client-Side

make as few calls as possible

Do not make synchronous calls

Use GlideAjax when passing data between server-sdie & client-side

Debug using console.log

Avoid direct DOM manipulation

Use UI Policies over Client Scripts when available