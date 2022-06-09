## uJar Bootcamp

uJar is a collection of small and useful templates of Java apps, which are not big enough to make own projects.

## Code conventions

The code follows [Google Code Conventions](https://google.github.io/styleguide/javaguide.html) without exceptions. Code
quality is measured by:

- [Sonarqube](https://sonarqube.ujar.org/dashboard?id=ujar-org%3Alorem-ipsum-words-processor)
- [PMD](https://pmd.github.io/)
- [CheckStyle](https://checkstyle.sourceforge.io/)
- [SpotBugs](https://spotbugs.github.io/)

### Tests

This project has standard JUnit tests. To run them execute this command:

```
mvn test
```

It is mandatory to keep test code coverage not below **80** percents and cover all business logic and edge cases.
