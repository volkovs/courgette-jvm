CHANGES IN VERSION 2.3.2
========================

* Add support to use TestNG to run Cucumber features and scenarios in parallel. You can now extend your runner class with TestNGCourgette.


CHANGES IN VERSION 2.3.1
========================

* Add support for JDK 10.
* Update Courgette report to include data table row info.
* Update Courgette report to include feature and line info on the modal title.


CHANGES IN VERSION 2.2.1
========================

* Bug Fixes

    * Fixed issue which caused Cucumber reports to be incorrectly created due to missing plugins.
    * Added missing background steps to Courgette-JVM html report.


CHANGES IN VERSION 2.2.0
========================

* Add ability to override default courgette report target directory (PR from Andrejs)


CHANGES IN VERSION 2.1.0
========================

 * Bug Fix
    * Non reporting plugins are not added to runtime options.


CHANGES IN VERSION 2.0.0
========================

* Upgrade to Cucumber-JVM 2.4.0
* Change Courgette-JVM html report to support additional Cucumber-JVM 2+ statuses.


CHANGES IN VERSION 1.6.1
========================

* Add all custom step outputs (scenario.write) to Courgette html report.
* Fixed modal overflow in Courgette html report where text overflows the bounds of the modal.


CHANGES IN VERSION 1.6.0
========================

* Update Courgette-JVM html report. Report now includes all step definitions, embedded screenshots, thrown exceptions, pie chart and Courgette run information.
* Remove "cucumber.options" system property (if set by the client) before calling the CLI because cucumber options are already parsed by Courgette beforehand.


CHANGES IN VERSION 1.5.1
========================

* Add feature to provide non standard VM options for each VM thread.


CHANGES IN VERSION 1.5.0
========================

* Courgette options (threads, runLevel, rerunFailedScenarios, showTestOutput) can now be overridden at runtime.
* Remove unnecessary href from Courgette Html report.


CHANGES IN VERSION 1.4.3
========================

* Add default Cucumber runtime options (dryRun, strict, monochrome) to Courgette.


CHANGES IN VERSION 1.4.2
========================

* Propagate Cucumber exception to Courgette when Cucumber features fail to load.
* Fixed bug which causes the Gradle build to fail when there are no matching features using the provided tags.


CHANGES IN VERSION 1.4.1
========================

* Add functionality to override the cucumber options set the in Courgette runner.


CHANGES IN VERSION 1.4.0
========================

* Add new Courgette-JVM html report. (Reports are fully searchable and pagniated)


CHANGES IN VERSION 1.3.2
========================

* Fixed temp directory path for Unix (Ubuntu) systems.


CHANGES IN VERSION 1.3.1
========================

* Fixed JSON output bug.


CHANGES IN VERSION 1.3.0
========================

* Add support to run scenarios (in addition to running features) in parallel.
* Add new Courgettte option - runLevel


CHANGES IN VERSION 1.2.0
========================

* Add Courgette Feature runner.
* Removed Courgette CLI runner.
* Add showTestOuput runtime option.
* Add all system properties to Courgette Feature runner.


CHANGES IN VERSION 1.1.1
========================

* Update feature parser.


CHANGES IN VERSION 1.1.1
========================

* Add Cucumber-Java8 dependancy
* Courgette no longer extends from Cucumber - it now extends from ParentRunner.


CHANGES IN VERSION 1.0.0
========================

* Initial version release