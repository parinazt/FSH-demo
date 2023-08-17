# FHIR IG repo
This is a repo containing the documents of developing a demo Implementation Guide (IG) with FHIR Shorthand (FSH).

o	An Implementation Guide (IG) in FHIR is a set of rules and guidelines for how to use FHIR in a specific context or use case. It can include a collection of FHIR resources, such as profiles, extensions, value sets, and examples that are specific to that context or use case.

o	FHIR profiles are one of the components that can be included in an Implementation Guide. A FHIR profile is a way to define how a specific resource or set of resources should be used in a particular context. It can include constraints on the allowed data elements, as well as extensions specific to that context.

o	So, an Implementation Guide is a collection of resources and guidelines for using FHIR in a specific context, and a FHIR profile is a part of that collection, it is a specific way of defining how a resource should be used in a particular context. An Implementation guide can include one or more profiles and many other resources to fully define how FHIR should be used in a specific context.

# How to play with FSH?

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

# Useful tutorial videos about FSH and IG

1) Chris Moesel - Advanced FHIR Shorthand and Tools | DevDays June 2021 Virtual: https://www.youtube.com/watch?v=Ohgx5TedLlI
2) Mark Kramer - Introduction to FHIR Shorthand | DevDays November 2020 Virtual: https://www.youtube.com/watch?v=RfmqpUA606U&t=286s
3) Mark Kramer - Learn to FSH: a friendly introduction to FHIR Shorthand | DevDays June 2022: https://www.youtube.com/watch?v=jegp6qEjgwM
4) Mark Kramer - Create an Implementation Guide with FHIR Shorthand | DevDays June 2021 Virtual: https://www.youtube.com/watch?v=0JSp-IOul20&t=1488s
5) M. Kramer & C. Moesel - Let's Build - Profiling with FHIR Shorthand | DevDays November 2020 Virtual: https://www.youtube.com/watch?v=7yzLzQjict0
6) Mark Kramer & Chris Moesel - FHIR Shorthand | DevDays 2020 Virtual June: https://www.youtube.com/watch?v=oK3-wYzJeIA
7) Chris Moesel & Mark Kramer - Let's Build! FHIR Shorthand | DevDays 2020 Virtual June: https://www.youtube.com/watch?v=iJGmHiAlQwo
8) Mark Kramer - Create an Implementation Guide with FHIR Shorthand | DevDays June 2021 Virtual: https://www.youtube.com/watch?v=OmcSuAMf20s
9) Mark Kramer & Chris Moesel - FHIR Shorthand | DevDays 2020 Virtual June: https://www.youtube.com/watch?v=kF03qOnX_xc
10) Introduction - FHIR Implementation Guide Creation Training: https://www.youtube.com/watch?v=ovbRwbd0uD8&t=5s

# Other useful videos about FHIR: 
1) FHIR for Developers - Getting Started: https://www.youtube.com/watch?v=m2O6HiA1Z7g&t=1429s
2) Intro to FHIR: https://www.youtube.com/watch?v=YbQcJj1GqH0 (very informative for beginners)

# Json <-> FSH converter
https://fshschool.org/FSHOnline/#/
