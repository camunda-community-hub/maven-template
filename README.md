[![Community badge: Incubating](https://img.shields.io/badge/Lifecycle-Incubating-blue)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#incubating-)
[![Community extension badge](https://img.shields.io/badge/Community%20Extension-An%20open%20source%20community%20maintained%20project-FF4700)](https://github.com/camunda-community-hub/community)

# maven-template

Empty maven project with defaults that incorporates Camunda Community Hub best practices.

## Usage

Use this as a template for new Camunda Community Hub projects.

Adding [Contributing to this project](https://gist.github.com/jwulf/2c7f772570bfc8654b0a0a783a3f165e)
to the repo.

(This is not part of the template as the text might change. Please copy the latest version.)

## Features

- IDE integration
  - https://editorconfig.org/
- GitHub Integration
  - Dependabot enabled for Maven dependencies (Dependabot not yet available for Camunda Community
    Hub)
  - Backport action (https://github.com/zeebe-io/backport-action)
- Maven POM
  - Release to Maven, Nexus and GitHub
  - Google Code Formatter
  - JUnit 5
  - AssertJ
  - Surefire Plugin
  - JaCoCo Plugin (test coverage)
  - flaky test extractor

## Versions

Different versions are represented in different branches

- `main` - Java 11

