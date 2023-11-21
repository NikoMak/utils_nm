# Changelog

<!--
## v1.0.15 (YYYY-MM-DD)
### Features
- feat in ...

### Fix
- fix in ...
-->
## v1.0.14 (2023-09-22)
### Features
- add `inverse_non_unique_dict` and `warning_on_one_line` to `util_functions` module


## v1.0.13 (2023-09-07)
### Features
- add `transform_long_wide` in `data_functions` module


## v1.0.12 (YYYY-MM-DD)
### Fix
- fix in default argument evaluation for argparse in `util_functions.determine_default_value_for_argparse`


## v1.0.11 (2023-08-23)
### Features
- improve default argument evaluation for argparse in `util_functions.determine_default_value_for_argparse`


## v1.0.10 (2023-08-22)
### Fix
- fix in dtype casting in `data_functions` `stack_temporal_data` and `unstack_temporal_data`


## v1.0.9 (2023-08-14)
### Features
- implement dtype casting in `data_functions.stack_temporal_data`


## v1.0.8 (2023-08-14)
### Fix
- fix TypeError in function definition


## v1.0.7 (2023-08-12)
### Features
- add `data_functions` module and implement `stack_temporal_dataframe` and `unstack_temporal_dataframe`


## v1.0.6 (2023-04-04)
### Chore
- update dependency to pandas 2.*


## v1.0.5 (2023-03-23)
### Fix
- add logfile creation logic to `create_logger` from `util_functions`


## v1.0.4 (2023-03-22)
### Fix
- improve `determine_default_value_for_argparse` in `util_functions` for parsing in repl mode


## v1.0.3 (2023-03-22)
### Features
- improve `determine_default_value_for_argparse` in `util_functions` for parsing in repl mode


## v1.0.2 (2023-03-22)
### Chore
- improve logging formatting from `create_logger` in `util_functions`


## v1.0.1 (2023-03-17)
### Features
- add `convert_to_datetime` in `util_functions`


## v1.0.0 (2023-03-14)
### Features
- update code to use sqlalchemy 2.0


## v0.8.4 (2023-03-09)
### Refactors
- rename `isnone()` to `replace_none()`
- add deprecation warning to `clean_umlauts`


## v0.8.3 (2023-03-02)
### Features
- add `isnone` to `util_functions`
- add additional umlaut to `clean_umlauts` from `util_functions`


## v0.8.2 (2022-01-11)
### Features
- add support for oracle database


## v0.8.1 (2023-01-11)
### Chore
- update package dependencies


## v0.8.0 (2023-01-10)
### Features
- add `create_multiple_db_engines` to `db_functions`

### Refactor
- rename `create_db_engine` to `create_single_db_engine` from `db_functions`


## v0.7.7 (2023-01-07)
### Features
- add yaml implicit resolver and constructor helper for environment variables


## v0.7.6 (2022-12-14)
### Fix
- format logger from `util_functions`


## v0.7.5 (2022-12-13)
### Fix
- fix in `util_gui_classes` by commenting out example usage code, which made trouble when importing the module in repl.


## v0.7.4 (2022-11-18)
### Refactor
- refactor code


## v0.7.3 (2022-11-18)
### Features
- re-add usage of text_split for `util_gui_classes.GuiPromptYesNo`


## v0.7.2 (2022-11-18)
### Fix
- fix `util_gui_classes.GuiPromptYesNo` behaviour when using multiple times


## v0.7.1 (2022-11-17)
### Fix
- make `util_gui_classes.GuiPromptYesNo` topmost window


## v0.7.0 (2022-11-17)
### Features
- add `split_text` to `util_function`
- add new module `util_gui_classes` which includes `GuiPromptYesNo`, a class to prompt the user a gui based yes / no question with default value and countdown functionality 


## v0.6.6 (2022-11-02)
### Features
- add `print_yellow` and `input_yellow` to `util_functions` and make use of them in `input_prompt`


## v0.6.5 (2022-11-02)
### Fix
- fix while conditions in `util_functions.input_prompt`


## v0.6.4 (2022-11-02)
### Fix
- fix while loop for enumerated input in `util_functions.input_prompt`


## v0.6.3 (2022-11-01)
### Features
- extend capabilities of `util_functions.input_prompt` to accept multi user input


## v0.6.2 (2022-10-25)
### Features
- improved verbosity of `util_functions.input_prompt`


## v0.6.1 (2022-10-25)
### Features
- improved verbosity of `util_functions.input_prompt`


## v0.6.0 (2022-10-23)
### Fix
- fix project dependencies


## v0.5.5 (2022-10-19)
### Fix
- fix dependencies to `util_functions.input_prompt` due to new `message` argument


## v0.5.4 (2022-10-19)
### Features
- improve `util_functions.input_prompt` to accept additional optional `message` argument


## v0.5.3 (2022-10-14)
### Fix
- add call to `window.withdraw()` to hide the initialization of the gui box


## v0.5.2 (2022-10-14)
### Features
- improved `prompt_file_name` to work properly in repl mode


## v0.5.1 (2022-10-14)
### Features
- added util function: `prompt_file_name`


## v0.5.0 (2022-10-14)
### Features
- added util function: `determine_main_script_path`
- added util function: `runs_in_repl_mode`


## v0.4.3 (2022-09-30)
### Docu
- improve static typing for `util_classes.Email`


## v0.4.2 (2022-09-29)
### Fix
- improve `db_functions.loop_insert_df_to_table()` by ensuring the index of the dataframe is reset before loop


## v0.4.1 (2022-09-29)
### Forgot to apply changes, use v0.4.2

## v0.4.0 (2022-09-26)
### Features
- added db function: `loop_insert_df_to_table`


## v0.3.2 (2022-09-22)
### Fix
- fix documentation for `execute_raw_sql`


## v0.3.1 (2022-09-22)
### Features
- improve `execute_raw_sql` to accept string or sqlalchemy text clause


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
