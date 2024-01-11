# Frequently asked questions

This document is used to colect frequently asked questions while developing for OSH workstream.


- **While using Coverity, I get the following error *"reset-host-name renames emit data created on a single host only. Please use add-other-hosts to merge emit data from multiple hosts"*. How can this be fixed?"** 
You can try to set the  `COV_HOST`  environment variable so that the same hostname is used for both the capture commands. For example: [https://gitlab.cee.redhat.com/osh/csmock-plugin-coverity/-/commit/ba591c18743e09cee51d359aee744643d5f463a6](https://gitlab.cee.redhat.com/osh/csmock-plugin-coverity/-/commit/ba591c18743e09cee51d359aee744643d5f463a6)
