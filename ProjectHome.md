### Attention: ###
# The project is now inactive #

### What is flex-mojos? ###

Flexmojos provides first-class support for Flex and AIR development within Apache Maven. It allows Maven to compile, optimize, and test Flex SWF, Flex SWC, Air SWF and Air SWC.

The main goal is to provide a full support to all mxmlc/compc options.

Those two projects are great, but I believe I can be a good alternative.
I made this choice of create a new project when I tried to compile the Adobe Open Source SDK and figure out that will not be possible with none of these.

Major features:
  * SWF, SWC, AIR and Flex versions;
  * RSL and caching framework support;
  * Modules support;
  * full cover to MXMLC and COMPC options;
  * flex 3;
  * use FLEX-OEM-COMPILER, means it faster, uses less memory, no need of references to local drive;
  * flex unit support;
  * asdoc support;
  * no setup needed, no environment variables, no changes at flex-configs.xml, no needs to point your pom to any absolute path.  Just maven life style.
  * compatible with several unit testing frameworks: FlexUnit, FUnit, asUnit and AdvancedFlex
  * library otimization
  * html-wrappers generation
  * code generation using GAS3


There are several releases of the project.  Please check maven repository for details.