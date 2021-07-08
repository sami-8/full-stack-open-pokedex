## Exercise 11.1

### Linters, test frameworks and build tools for Java
Some popular Java linter and static analysis tools:
- CheckStyle for checking that the code style follows a standard or other set of rules
- SpotBugs for static analysis looking for possible bugs
- SonarLint. A linter for detecting common mistakes, bugs and vulnerabilities.
- PMD. Another code analyzer for detecting common programming flaws.

Each of these tools can be added to an IDE, like Eclipse, as a plugin.

Some popular Java test frameworks and libraries include:
- Junit for unit tests
- JBehave, designed for behaviour driven development
- Serenity, designed for behaviour driven development, can be integrated with JBehave
- Selenium for cross browser testing
- Mockito and EasyMock for creating mock objects

Java test coverage reports can be generated with JaCoCo.

Most popular Java build tools include Google's Gradle and Apache's Maven. Another well known but old build tool is Apache's Ant. There is also SBT, that is mainly used for Scala but also supports Java.

### Some alternatives for Jenkins and GitHub actions:
- GitLab offers a CI/CD service
- Travis. Has many databases and services preinstalled, automatic deployments, can test pull requests before merging, etc. Companies using it include Heroku and BitTorrent. Written in Ruby.
- TeamCity. Commercial product. Has a free version with some limitations. Java-based and developed by JetBrains.
- BuildBot. Describes itself as a framework rather than a ready-to-use application. Python-based.

