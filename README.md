# maven-pom-transformer
A maven plugin to transform parts of your pom in the build to reduce duplication.

This is currently an intentionally empty repo to remind me of the idea.
This came about from a fellow coder asking if I knew of a way to exclude a dependency from everything it appears in without cluttering the dependencies section. From when he was sure he did not need the dependency and it was breaking tests. We fixed that problem by analyzing the pom and re-ordering and adjusting dependencies, but the general principle is a sound one. Especialy for large common libraries.
