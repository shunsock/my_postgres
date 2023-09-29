| MySQL Command | Description | PostgreSQL Command | Description |
|---------------|-------------|--------------------|-------------|
| `?` or `\?` | Synonym for `help`. | `\?` | Displays help on backslash commands. |
| `clear` or `\c` | Clear the current input statement. | `\r` | Resets the query buffer. |
| `connect` or `\r` | Reconnect to the server. Optional arguments are db and host. | None | None |
| `delimiter` or `\d` | Set statement delimiter. | None | None |
| `edit` or `\e` | Edit command with `$EDITOR`. | `\e` | Edit the current query buffer with an external editor. |
| `ego` or `\G` | Send command to MySQL server, display result vertically. | `\x` | Toggles expanded output mode. |
| `exit` or `\q` | Exit MySQL. Same as quit. | `\q` | Quit psql. |
| `go` or `\g` | Send command to MySQL server. | `\g` | Sends the current query input buffer to the server. |
| `help` or `\h` | Display help. | `\h` | Provides help with SQL commands. |
| `nopager` or `\n` | Disable pager, print to stdout. | None | None |
| `notee` or `\t` | Don't write into outfile. | None | None |
| `pager` or `\P` | Set PAGER [to_pager]. Print the query results via PAGER. | None | None |
| `print` or `\p` | Print current command. | `\p` | Shows the content of the current query buffer. |
| `prompt` or `\R` | Change your MySQL prompt. | `\set PROMPT1` | Sets the string that will be used as prompt. |
| `quit` or `\q` | Quit MySQL. | `\q` | Quit psql. |
| `rehash` or `\#` | Rebuild completion hash. | None | None |
| `source` or `\.` | Execute an SQL script file. Takes a file name as an argument. | `\i` | Executes the SQL commands from a file. |
| `status` or `\s` | Get status information from the server. | `\conninfo` | Displays information about the current connection. |
| `system` or `\!` | Execute a system shell command. | `\!` | Executes a shell command. |
| `tee` or `\T` | Set outfile [to_outfile]. Append everything into given outfile. | None | None |
| `use` or `\u` | Use another database. Takes database name as an argument. | `\c` | Connects to a new database. |
| `charset` or `\C` | Switch to another charset. | None | None |
| `warnings` or `\W` | Show warnings after every statement. | None | None |
| `nowarning` or `\w` | Don't show warnings after every statement. | None | None |
| `resetconnection` or `\x` | Clean session context. | None | None |
| `query_attributes` | Sets string parameters for the next query. | None | None |
| `ssl_session_data_print` | Serializes the current SSL session data. | None | None |
