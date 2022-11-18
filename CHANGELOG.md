# Changelog

<!--
## v0.7.3 (YYYY-MM-DD)
### Features
- feat in ...

### Fix
- fix in ...
-->
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
