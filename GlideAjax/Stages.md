# GlideAjax Stages

1. Method passed in sysparm_name gets invoked
2. Server-side scripts are ran
3. return styatement ends server-side script execution -=> `response.responseXML.documentElement.getAttribute('answer')
4. Response is packaged up as XML and sent to client

## JS callback

a callback is a function that is passed in as an argument which is then executed at a later time

## JSON VS XML

JSON -=> JavaScript Object Notation

XML -=> Extensible Markup Language

### Overview

addParam() -> getXML() -> getXMLAnswer()