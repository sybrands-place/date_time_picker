## 4.0.0 - 2026-11-13

* **Breaking:** Migrated from the deprecated `package:flutter/material.dart` to `package:material_ui`. The `decoration` parameter is now `material_ui`'s `InputDecoration`, so callers must import `package:material_ui/material_ui.dart`.
* Added `material_ui` dependency; raised constraints to Dart >=3.13.0 and Flutter >=3.47.0.

## 2.1.0 - 2021-07-08

* Fixed 12h display format.
* Fixed field cleaning.
* Added a new parameter (timePickerEntryModeInput) to set timepicker mode, dial or input.

## 2.0.0 - 2021-03-09

* Migrate to null safety.
* Update SDK constraints to >=2.12.0 <3.0.0 based on beta release guidelines.
* Updata intl version dependency.
* Add 2 optional params, initialDate and initialTime to set date picker and time picker to show date and time diferent of now, when initialValue is empty.
  
## 1.1.1 - 2020-12-29

* Removing flutter_localizations dependency.
  
## 1.1.0 - 2020-11-12

* Improved use of the local parameter to define DateTimePicker directly.

## 1.0.2 - 2020-09-21

* Fix issue #4 - fixed the time display when period is 12h. Now it can differ correctly when time is AM or PM and show this information.

## 1.0.1 - 2020-08-18

* Fix issue #2 - just reference in README.md.
* Fix issue #3 - filling the time field when press Ok button on time picker dialog without select a specific time, getting the current time showed.
* Fix problems when initialValue is empty.

## 1.0.0 - 2020-07-22

* Initial Open Source release.
