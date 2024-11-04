# Codeql Workshop Preparation Instructions

In preparation for our CodeQL workshop we ask that you perform a few setup steps so that you may get the full hands on workshop value. Attendance presentation style is acceptable if it is not possible to perform these steps.

The most important steps to perform ahead of time will to be to do any downloads/cloning/VSCode installation/VSCode CodeQL extension installation and the remaining steps are optional to perform ahead of time as we can go over those in the session,

1. Clone the workshop repo onto your local environment:
https://github.com/advanced-security/codeql-workshops-staging/tree/master

3. Navigate into the following directory
codeql-workshops-staging/java/codeql-dataflow-sql-injection

4. Download the latest CodeQL binary (containing CLI and libraries) for whichever platform you are on, into the directory, and unpack that

Binaries found here:
https://github.com/github/codeql-cli-binaries

For this workshop, use <insert-recent-CLI-version-here>

5. Create a CodeQL database in that directory using the following command:
codeql database create -l java database --command='./build.sh'

6. Setup the VSCode editor. The prerequisite of this is that you have VSCode installed and have installed the CodeQL extension in it. This is the editor that we will be using to write queries.

Instructions on how to do that found here: https://codeql.github.com/docs/codeql-for-visual-studio-code/setting-up-codeql-in-visual-studio-code/

7. Open the workspace directory in the editor. Then we will need to add the downloaded CodeQL CLI to the VSCode editor. Find the CodeQL extension settings, then paste the full path to the CodeQL CLI into the Code QL > Cli: Executable Path field.

8. Add the CodeQL database to the editor, to do this there is a widget on the left side of editor that looks like QL and after selecting that, there is a databases panel. There are options to select from archive or folder. Select the "from folder" option and add the "database" folders you unpacked earlier.


9. Install the CodeQL (libraries)/pack dependencies: 
open the VSCode Command Palette (View-> Command Palette). Select "CodeQL: Install Pack Dependencies" then click the checkbox that comes up and hit enter. This should fetch a CodeQL library pack from the GitHub Container Registry called "java-all".

10. Open a sample query. Add a new file "example.ql" to the directory with this content:

```
/**
 * @name introduction workshop
 * @description Sample SQL Injection problem
 * @id java/introworkshop
 * @problem.severity warning
 */

import java

select 1
```

You can then right click in the query file and select CodeQL: Run Query. At this point there should be no red highlighting and the query should execute. 

If there are any hiccups in the setup we can go over those in the session however!

Thanks!
