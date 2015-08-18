# dba-tools
The DBArt Tools repository

For now there is only one tool here:
- bin/dba-parse-general

## bin/dba-parse-general
This script was made to figure out quickly from the mysql general_log if schemas are still in use, who connects to them and from what server. This is important to know if you want to drop an "unused" schema and verify if it actually is unused.

### Usage
usage: dba-parse-general [-h] [--users [STATS_USERS]] [--schemas [STATS_SCHEMAS]] [--hosts [STATS_HOSTS]] [--verbose [STATS_VERBOSE]] --general-log [GENERAL_LOG_FILE [GENERAL_LOG_FILE ...]]
