# Test plan

  

## General

 **Before commit**
 - Did you rebase the code?
 -  Is the code commented?
 -  Have you reviewed the logs of the execution?
 
**Tests**

- Are all tests passing?
- Are all lines perfoming the intended function? 

**Styling**
- Do the code stick to the styling guide?

  

## OpenScanHub

**Are you changing the database model?**

- Are fixtures and migrations up-to-date?
- Were initial data added?


## cspodman/csmock

  

**Are you adding a new plugin?**

- Do cspodman and csmock share the same argument name?
- Do cspodman and csmock share the same description name?
- Should the argument enable the plugin by itself?

  

**Are you adding a new argument to a plugin?**

- Do cspodman and csmock share the same argument name?
- Do cspodman and csmock share the same description name?
- Should the argument enable the plugin by itself?

**Are we downloading something from the Internet?**

- Are we performing integrity checks on the downloaded files?
- Does it come from a known place?

**Tests**

- Was this tested with multiple RPMs?
