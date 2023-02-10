[license]: http://www.apache.org/licenses/LICENSE-2.0 "Apache License 2.0"
[site]: https://qameta.io/?source=Report_GitHub
[blog]: https://qameta.io/blog
[gitter]: https://gitter.im/allure-framework/allure-core
[gitter-ru]: https://gitter.im/allure-framework/allure-ru
[tg-ru]: https://t.me/allure_ru
[twitter]: https://twitter.com/QametaSoftware "Qameta Software"
[twitter-team]: https://twitter.com/QametaSoftware/lists/team/members "Team"
[build]: https://github.com/allure-framework/allure2/actions/workflows/build.yaml
[build-badge]: https://github.com/allure-framework/allure2/actions/workflows/build.yaml/badge.svg
[maven]: https://repo.maven.apache.org/maven2/io/qameta/allure/allure-commandline/ "Maven Central"
[maven-badge]: https://img.shields.io/maven-central/v/io.qameta.allure/allure-commandline.svg?style=flat
[release]: https://github.com/allure-framework/allure2/releases/latest "Latest release"
[release-badge]: https://img.shields.io/github/release/allure-framework/allure2.svg?style=flat
[CONTRIBUTING.md]: .github/CONTRIBUTING.md
[CODE_OF_CONDUCT.md]: CODE_OF_CONDUCT.md
[docs]: https://docs.qameta.io/allure-report/
[discussions]: https://github.com/allure-framework/allure2/discussions

<h3 align="center">🚀🚀🚀 Welcome to Allure Report 🚀🚀🚀</h3>
<p align="center"><a href="https://qameta.io/allure-report/" target="_blank"><img src="https://github.com/apostolst/readme-file/blob/112b6e61f8763cb93f9623c56972058020f9f264/report_icons/LogoReport.png" height="300"/></p>
 <h3 align="center">
   🫶🏻We did it, with care for everyone QA Engineer🫶🏻
</h3> 
<p align="center">
  <a href="https://docs.qameta.io/allure-report/">Documentation</a> |
  <a href="https://github.com/allure-framework/allure2/releases">Changelog</a> |
  <a href="https://github.com/allure-framework/allure2/releases">Roadmap</a>
 </p>


## What is Allure Report?
Allure Report is a flexible open-source multi-language test report tool that shows you a detailed representation of what has been tested and allows you to extract the most from the everyday execution of automated tests. 
<p align="center">
  <a href="https://qameta.io/allure-report/">
    <img alt="What is Allure Report" src="https://github.com/apostolst/readme-file/blob/a08ba3a07059f4b625ab97e933f45a6418ae87b4/report_icons/How%20Allure%20Report%20works.png" height="75%" />
  </a>
</p>
From the point of view of a tester or developer, Allure Report shortens the defect lifecycle. It has fully customizable categories that automatically sort tests according to error messages and stack traces. There is also a plethora of tools that provide useful information from test runs. For instance, the @Step annotation provides a human-readable description for actions within a test, which means that test execution can be examined without reading code. Allure Report also allows creating logs as well as displaying fixtures and attachments.

From the point of view of a manager, Allure Report allows tracking important "big-picture" data, like feature coverage, where the defects are clustered, what the execution timeline looks like, etc.

Allure Report can be set up and run with minimal infrastructure if all you need is to just dig through some test results locally. On the other hand, Report can also be used in a CI setting, where additional features become available (like test retries and test history).

All of this is possible because of the immense work that has been put into integrating Allure Report with over 100 tools. Over these years, we've been building a truly polyglot tool that can work with testing frameworks for Java, Python, JavaScript, .Net, Cucumber, Go, and PHP, and can be run on any CI system (Jenkins, Bamboo, TeamCity, and many, many others).

## 🏃🏼Let's Begin!!!🏃🏼

You can use one of the following ways to get Allure:

- Grab it from releases (see the [Assets](https://github.com/allure-framework/allure2/releases) section).
- On Mac OS, use Homebrew:
    
    ```
    brew install allure
    
    ```
    
- On Windows, Allure is available from the [Scoop](http://scoop.sh/) command-line installer. To install Allure, download and install Scoop, and then execute the following command in the Powershell:
    
    ```
    scoop install allure
    
    ```
    
- Or you could just install everything manually.
    1. Download the latest version as a zip archive from [GitHub releases](https://github.com/allure-framework/allure2/releases).
    2. Unpack the archive to the allure command-line directory.
    3. Navigate to the **bin** directory.
    4. Use **allure.bat** for Windows or **allure** for Unix platforms.
    5. Add **allure** to system PATH.
    
    Allure CLI requires Java Runtime Environment to be installed.
    
## 🔨 Setting up Allure Report 🔨
To start your work, you'll need to ensure that your configuration file has the proper dependencies for the tools you'll be using along with Allure. The configuration settings for each tool are different, so it's best to [look up examples on the documentation page](https://docs.qameta.io/allure-report/).

When that’s done, the report can already be generated, but it would be empty. For any information to appear, you’d first need to annotate the tests. Once you've got the report files from a test framework, you can run the following command:

```jsx
allure serve /path/to/the/data/
```

This will generate the report, serve it, and open it in the default browser.

<h2 align="center">✨Integrations✨</h2>
<p align="center">
 <a href="https://github.com/allure-framework/allure-php-commons2"><img src="https://github.com/apostolst/readme-file/blob/ac317373af3ae2d5d157c670c1d7cd57799fcdef/report_icons/frameworks%20:%20languages/colored/php.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-codeception"><img src="https://github.com/apostolst/readme-file/blob/ac317373af3ae2d5d157c670c1d7cd57799fcdef/report_icons/frameworks%20:%20languages/colored/codeception.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-phpunit"><img src="https://github.com/apostolst/readme-file/blob/ac317373af3ae2d5d157c670c1d7cd57799fcdef/report_icons/frameworks%20:%20languages/colored/phpunit.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-python"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/python.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-js"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/js.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-ruby"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/ruby.png" height="70"/>
  </p>
<p align="center">
 <a href="https://github.com/allure-framework/allure-java"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/java.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-kotlin"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/kotlin.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-mocha"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/mocha.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-nose"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/nose.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-jasmine"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/jasmine.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-karma"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/karma.png" height="70"/>
  </p>
<p align="center">
 <a href="https://github.com/allure-framework/allure-cucumber"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/cucumber.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-ruby-commons"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/ruby.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-rspec"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/rspec.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-pytest"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/pytest.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-scalatest"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/scalatest.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-nunit2"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/nunit.png" height="70"/>
  </p>
<p align="center">
 <a href="https://github.com/allure-framework/allure-mstest"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/mstest.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-specs"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/specs2.png" height="70"/>
 <a href="https://github.com/ozontech/allure-go"><img src="https://github.com/apostolst/readme-file/blob/main/report_icons/frameworks%20:%20languages/colored/go.png" height="70"/>
  </p>
    
## 🏡Join Allure community🏡
<a href="https://github.com/allure-framework/allure-php-commons2"><img src="https://github.com/apostolst/readme-file/blob/e83e37ba773331d944a8d011b1eed5df51a461e0/report_icons/soc/youtube.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-php-commons2"><img src="https://github.com/apostolst/readme-file/blob/e83e37ba773331d944a8d011b1eed5df51a461e0/report_icons/soc/twitter.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-php-commons2"><img src="https://github.com/apostolst/readme-file/blob/e83e37ba773331d944a8d011b1eed5df51a461e0/report_icons/soc/tg.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-php-commons2"><img src="https://github.com/apostolst/readme-file/blob/e83e37ba773331d944a8d011b1eed5df51a461e0/report_icons/soc/linkedin.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-php-commons2"><img src="https://github.com/apostolst/readme-file/blob/e83e37ba773331d944a8d011b1eed5df51a461e0/report_icons/soc/github.png" height="70"/>
 <a href="https://github.com/allure-framework/allure-php-commons2"><img src="https://github.com/apostolst/readme-file/blob/e83e37ba773331d944a8d011b1eed5df51a461e0/report_icons/soc/facebook.png" height="70"/>
  </p>
    
## Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct][CODE_OF_CONDUCT.md]. By participating in this project you agree to abide by its terms.

## Contributors

This project exists thanks to all the people who contributed. [[Contribute]](.github/CONTRIBUTING.md).

<a href="https://github.com/allure-framework/allure2/graphs/contributors"><img src="https://opencollective.com/allure-report/contributors.svg?avatarHeight=24&width=890&showBtn=false" /></a>

## License
The Allure Framework is released under version 2.0 of the [Apache License][license].
[![build-badge][]][build] [![release-badge][]][release] [![maven-badge][]][maven] [![Backers on Open Collective](https://opencollective.com/allure-report/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/allure-report/sponsors/badge.svg)](#sponsors)
