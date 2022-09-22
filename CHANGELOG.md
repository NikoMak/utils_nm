# Changelog

<!--next-version-placeholder-->

<!--
## v0.3.0 (YYYY-MM-DD)
### Features
- feat in ...

### Fix
- fix in ...
-->


## v0.3.0 (2022-09-22)
### Features
- added `util_context_managers` module


## v0.2.1 (2022-09-22)
### Features
- added util function: `determine_default_value_for_argparse`

### Fix
- fix `db_functions.execute_raw_sql()` where the statement was not being committed
- fix `util_functions.input_promt()` from for the case where a default is provided without choices


## v0.2.0 (2022-09-20)
### Features
- added `active` column in orm model `JboSchedule`
- added orm base class method: `select_all`
- added orm base class method `select_filtered`


## v0.1.0 (2022-09-09)
### Features
- added util function: `chunker`
- added util function: `last_day_of_month`
- added util function: `date_as_integer`
- added util function: `display_formatted_time`
- added util function: `clean_umlauts`
- added util function: `calc_equidistant_weights`
- added `util_decorators` module


## v0.0.4 (2022-09-08)
### Fix
- rectify send_email method of Email class to stop the code in case of a debug server at localhost


## v0.0.3 (2022-09-08)
### Features
- add "check first" logic when creating orm tables


## v0.0.2 (2022-09-08)
### Fix
- fix create_table method to only create the table from which class it was called and not all tables in metadata


## v0.0.1 (2022-09-07)
- First release of `utils_nm`
