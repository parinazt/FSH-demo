# FHIR IG repo
This is a repo containing the documents of developing a demo Implementation Guide (IG) with FHIR Shorthand (FSH).

o	An Implementation Guide (IG) in FHIR is a set of rules and guidelines for how to use FHIR in a specific context or use case. It can include a collection of FHIR resources, such as profiles, extensions, value sets, and examples that are specific to that context or use case.

o	FHIR profiles are one of the components that can be included in an Implementation Guide. A FHIR profile is a way to define how a specific resource or set of resources should be used in a particular context. It can include constraints on the allowed data elements, as well as extensions specific to that context.

o	So, an Implementation Guide is a collection of resources and guidelines for using FHIR in a specific context, and a FHIR profile is a part of that collection, it is a specific way of defining how a resource should be used in a particular context. An Implementation guide can include one or more profiles and many other resources to fully define how FHIR should be used in a specific context.

# how to play with FSH?

- Install Visual Studio Code and the FSH language extension
- Install a Java runtime
- Install Ruby and Jekyll using these OS-specific instructions
- Install SUSHI using these directions
- Download the syllabus IG from https://github.com/FSHSchool/courses-fsh-seminar-exercise/archive/refs/heads/main.zip and unzip it, or git clone https://github.com/FSHSchool/courses-fsh-seminar-exercise.git
- Open a Terminal/Command Prompt window inside the IG folder, and run ./_updatePublisher.sh (Mac/Linux) or _updatePublisher.bat (Windows) from the command line.
This will automatically download the latest publisher.jar release from https://github.com/HL7/fhir-ig-publisher/releases and put it in the input-cache/ folder inside the IG folder.
The IG folder will be courses-fsh-seminar-exercise-main/input-cache/ if you used the .zip download, or courses-fsh-seminar-exercise/input-cache/ if you used git clone.
- Run ./_genonce.sh (Mac/Linux) or _genonce.bat (Windows)
Open output/index.html from inside your IG folder. You should see a mostly-empty IG home page that says “FSHSeminarExercise” on it.

Ref: https://fshschool.org/courses/fsh-seminar/setup.html 
