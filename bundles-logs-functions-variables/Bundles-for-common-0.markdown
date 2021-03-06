---
layout: default
title: 
categories: [Bundles-for-common]
published: true
alias: Bundles-for-common.html
tags: [Bundles-for-common]
---

Bundles of `common`
-------------------

\

Common bundles may only contain the promise types that are common to all
bodies. Their main function is to define cross-component global
definitions.

Common bundles are observed by every agent, whereas the agent specific
bundle types are ignored by components other than the intended
recipient.

\

~~~~ {.smallexample}
     
     bundle common globals
     {
     vars:
     
       "global_var" string = "value";
     
     classes:
     
       "global_class" expression = "value";
     }
     
~~~~

-   [classes in common promises](#classes-in-common-promises):
-   [defaults in common promises](#defaults-in-common-promises):
-   [meta in common promises](#meta-in-common-promises):
-   [reports in common promises](#reports-in-common-promises):
-   [vars in common promises](#vars-in-common-promises):
-   [\* in common promises](#Miscellaneous-in-common-promises):
-   [commands in agent promises](#commands-in-agent-promises):
-   [databases in agent promises](#databases-in-agent-promises):
-   [guest\_environments in agent
    promises](#guest_005fenvironments-in-agent-promises):
-   [files in agent promises](#files-in-agent-promises):
-   [\* in edit\_line
    promises](#Miscellaneous-in-edit_005fline-promises):
-   [delete\_lines in edit\_line
    promises](#delete_005flines-in-edit_005fline-promises):
-   [insert\_lines in edit\_line
    promises](#insert_005flines-in-edit_005fline-promises):
-   [field\_edits in edit\_line
    promises](#field_005fedits-in-edit_005fline-promises):
-   [replace\_patterns in edit\_line
    promises](#replace_005fpatterns-in-edit_005fline-promises):
-   [\* in edit\_xml promises](#Miscellaneous-in-edit_005fxml-promises):
-   [build\_xpath in edit\_xml
    promises](#build_005fxpath-in-edit_005fxml-promises):
-   [delete\_tree in edit\_xml
    promises](#delete_005ftree-in-edit_005fxml-promises):
-   [insert\_tree in edit\_xml
    promises](#insert_005ftree-in-edit_005fxml-promises):
-   [delete\_attribute in edit\_xml
    promises](#delete_005fattribute-in-edit_005fxml-promises):
-   [set\_attribute in edit\_xml
    promises](#set_005fattribute-in-edit_005fxml-promises):
-   [delete\_text in edit\_xml
    promises](#delete_005ftext-in-edit_005fxml-promises):
-   [set\_text in edit\_xml
    promises](#set_005ftext-in-edit_005fxml-promises):
-   [insert\_text in edit\_xml
    promises](#insert_005ftext-in-edit_005fxml-promises):
-   [interfaces in agent promises](#interfaces-in-agent-promises):
-   [methods in agent promises](#methods-in-agent-promises):
-   [outputs in agent promises](#outputs-in-agent-promises):
-   [packages in agent promises](#packages-in-agent-promises):
-   [processes in agent promises](#processes-in-agent-promises):
-   [services in agent promises](#services-in-agent-promises):
-   [storage in agent promises](#storage-in-agent-promises):
-   [access in server promises](#access-in-server-promises):
-   [roles in server promises](#roles-in-server-promises):
-   [inferences in knowledge
    promises](#inferences-in-knowledge-promises):
-   [things in knowledge promises](#things-in-knowledge-promises):
-   [topics in knowledge promises](#topics-in-knowledge-promises):
-   [occurrences in knowledge
    promises](#occurrences-in-knowledge-promises):
-   [measurements in monitor
    promises](#measurements-in-monitor-promises):
