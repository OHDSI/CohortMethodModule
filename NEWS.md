CohortMethodModule 0.3.0
========================
- Using renv project profiles to manage core packages required for module execution vs. those that are needed for development purposes.

CohortMethodModule 0.2.1
========================

- Upgrading CohortMethod to unreleased version (with faster covariate balance computation).

CohortMethodModule 0.2.0
========================

- Updated module to use HADES wide lock file and updated to use renv v1.0.2
- Added functions and tests for creating the results data model for use by Strategus upload functionality
- Added additional GitHub Action tests to unit test the module functionality on HADES supported R version (v4.2.3) and the latest release of R

CohortMethodModule 0.1.0
========================

- Updating CohortMethod reference. This exposes the diagnostics thresholds.


CohortMethodModule 0.0.6
========================

- Updating CohortMethod and other references for renv.lock file. This will fix the type of cm_target_comparator_outcome.outcome_of_interest (should be integer).


CohortMethodModule 0.0.5
========================

- Updating CohortMethod and other references for renv.lock file.


CohortMethodModule 0.0.4
========================

- Updating CohortMethod to fix missing columns in cm_covariate table, and fixing error when requesting balance without covariate filtering.

CohortMethodModule 0.0.3
========================

- Update to use DatabaseConnector v5.0.4 and CohortGenerator v0.6.0

CohortMethodModule 0.0.2
========================

Bugfixes:

- Updating CohortMethod to fix several minor issues in the export.


CohortMethodModule 0.0.1
========================

Initial version.