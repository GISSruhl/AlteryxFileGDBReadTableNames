# AlteryxFileGDBReadTableNames
Alteryx tool to read table names from file geodatabases to allow batch input of spatial data.


#### Miniconda
The miniconda build that is included is the [Virtual Environment](https://help.alteryx.com/developer/current/Python/use/VirtualEnvironment.htm?tocpath=SDKs%7CBuild%20Custom%20Tools%7CPython%20SDK%7C_____3) for the tool and allows it to be packaged without worrying about the end user's environment. **This should never be added to gitignore.**

#### Working Notes
This tool will use [GDAL](https://github.com/OSGeo/gdal) to open and read a file geodatabase then return a list of tables.
It also uses the [Alteryx Python SDK](https://help.alteryx.com/developer/current/Python/Overview.htm?tocpath=SDKs%7CBuild%20Custom%20Tools%7CPython%20SDK%7C_____0) to package the script and make it available in a native Alteryx tool.


#### Icon Credit
Icons made by <a href="https://www.flaticon.com/authors/vitaly-gorbachev" title="Vitaly Gorbachev">Vitaly Gorbachev</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>

Modified by Stephen Ruhl <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
