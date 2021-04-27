
# eclipse-tycho-issue-97
Repo to demonstrate Tycho regression since version 2.2.0 in issue #97 of eclipse/tycho.

Instructions:

cd parent
mvn install
cd ../project-tycho-2.1.0
mvn validate
cd ../project-tycho-2.3.0
mvn validate

Last command will abort with an NPE.

