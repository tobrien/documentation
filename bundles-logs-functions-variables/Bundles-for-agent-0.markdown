---
layout: default
title: xxxx
categories: [xxx]
published: true
alias: Bundles-for-agent-0.markdown.html
tags: [xx]
---

Bundles of `agent`
------------------

\

         
         bundle agent main(parameter)
         
         {
         vars:
         
           "sys_files"    slist        = {
                                          "/etc/passwd",
                                          "/etc/services"
                                          };
         files:
         
           "$(sys_files)" perms        = p("root","0644"),
                          changes      = trip_wire;
         
           "/etc/shadow"  perms        = p("root","0600"),
                          changes      = trip_wire;
         
           "/usr"         changes      = trip_wire,
                          depth_search = recurse("inf");
         
           "/tmp"         delete       = tidy,
                          file_select  = days("2"),
                          depth_search = recurse("inf");
         
         }
         

\

Agent bundles contain user-defined promises for `cf-agent`. The types of
promises and their corresponding bodies are detailed below.

-   classes in common promises:
-   defaults in common promises:
-   meta in common promises:
-   reports in common promises:
-   vars in common promises:
-   \* in common promises:
-   commands in agent promises:
-   databases in agent promises:
-   guest\_environments in agent promises:
-   files in agent promises:
-   \* in edit\_line promises:
-   delete\_lines in edit\_line promises:
-   insert\_lines in edit\_line promises:
-   field\_edits in edit\_line promises:
-   replace\_patterns in edit\_line promises:
-   \* in edit\_xml promises:
-   build\_xpath in edit\_xml promises:
-   delete\_tree in edit\_xml promises:
-   insert\_tree in edit\_xml promises:
-   delete\_attribute in edit\_xml promises:
-   set\_attribute in edit\_xml promises:
-   delete\_text in edit\_xml promises:
-   set\_text in edit\_xml promises:
-   insert\_text in edit\_xml promises:
-   interfaces in agent promises:
-   methods in agent promises:
-   outputs in agent promises:
-   packages in agent promises:
-   processes in agent promises:
-   services in agent promises:
-   storage in agent promises:
-   access in server promises:
-   roles in server promises:
-   inferences in knowledge promises:
-   things in knowledge promises:
-   topics in knowledge promises:
-   occurrences in knowledge promises:
-   measurements in monitor promises: