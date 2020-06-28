# {{cookiecutter.project_slug}}

{{cookiecutter.project_short_description}}

[![Build Status](https://travis-ci.com/roycetech/{{cookiecutter.project_slug}}.svg?branch=master)](https://travis-ci.com/roycetech/{{cookiecutter.project_slug}})
[![Test Coverage](https://api.codeclimate.com/v1/badges/TODO/test_coverage)](https://codeclimate.com/github/roycetech/{{cookiecutter.project_slug}}/test_coverage)
[![Maintainability](https://api.codeclimate.com/v1/badges/TODO/maintainability)](https://codeclimate.com/github/roycetech/{{cookiecutter.project_slug}}/maintainability)


### To build

`mvn test`


### Release process

- Develop, develop, develop
- Commit any outstanding changes
- Verify build passes with `mvn test`
- Update versions to release version with `mvn versions:set -DnewVersion=1.0.2`
- Commit release version
- Run deployment with: `mvn clean deploy -P release`
- Update versions to next snapshot version: `mvn versions:set -DnewVersion=1.0.2-SNAPSHOT`
- Commit new snapshot version
- Develop, develop, develop and rinse and repeat


### References

[Working with Apache Maven]()https://central.sonatype.org/pages/apache-maven.html)
