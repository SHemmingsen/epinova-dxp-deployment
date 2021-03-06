# Release notes

## v1.9.10
- Added detailed description [how to setup content harmonization with YAML/Classic mode](documentation/ContentHarmonization.md) .

## v1.9.9
- Set ContentCopy params IncludeBlob and IncludeDb as default `true`.

## v1.9.8
- Fixed ContentCopy script bug.

## v1.9.0
- Implemented "Content copy" task.  

## v1.8.0
- #61: Implement "Deploy smooth to" task.

## v1.7.1
- #58: Added CurrentStatus in error/warning text when something goes wrong/timeout.

## v1.7.0
- #55: Add task "ExpectStatus".

## v1.6.1, v1.6.2
- #48: Fixed guid in AwaitStatus task and vss-extension.json.

## v1.6.0
- #48: Add task "AwaitStatus".

## v1.5.1
- Small documentation updates.

## v1.5
- #44: SmokeTestIfFailReset: Add function to retry URL checks for specified number of times. This will help when it takes time for the application to start up on the slot example.

## v1.4
- #26: DeployTo: Fix problem with using SourceApp = 'cms,commerce'.  
- #45: Show start and end DateTime when run DeployNuGetPackage, DeployTo, CompleteDeploy, ExportDb, ResetDeploy.

## v1.3
- #36: ExportDb: Added new task ExportDb.  

## v1.2
- #34: DeployTo: Add support for IncludeBlob and IncludeDb in the task.  

## v1.1.4
- #23, #30: DeployNugetPackage: Bugfix. Code does not get to the extra debug info.  
  
## v1.1.3
- #23, #30: DeployNugetPackage: Bugfix. Spec char error.  

## v1.1.2
- #23, #30: DeployNugetPackage: Added more debug info when no nupkg found.  

## v1.1.1
- #23: DeployNugetPackage: Added support for upload both cms and commerce at the same time. "cms,commerce".  

## v1.1.0
- #23: DeployNugetPackage: Added support for upload of specified SourceApp. You can now run DeployNugetPackage twice to upload cms and commerce package.  

## v1.0.9
- #26: Removed the space between "cms,commerce" (the actual value and not just the title) 

## v1.0.8
- #24: Removed the space between "cms,commerce"