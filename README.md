# SQL-Migration

SQL Server migration scripts and the server-level objects you script out when moving to a new server, consolidated from separate repositories. Each folder is one former repo, with its full commit history preserved.

## Migration
| Folder | What it covers |
|---|---|
| [MIgration-checklist](MIgration-checklist) | End-to-end checklist and scripts: AG and non-AG migration with selective RECOVERY/NORECOVERY, DB owner to `sa`, compatibility level, and more |
| [Migration-using-PowerShell-JPomf](Migration-using-PowerShell-JPomf) | PowerShell migration of AG and non-AG databases, recovery choice, adding databases to an AG |
| [DBATOOLS](DBATOOLS) | dbatools notes and commands: `Copy-*`/migrate commands, small-DB migration, replication, firewall rules |
| [PS-check-missing-logins-jobs-and-databases-between-old-and-new-servers](PS-check-missing-logins-jobs-and-databases-between-old-and-new-servers) | PowerShell check for logins, jobs and databases missing on the new server |
| [SSAS-migration](SSAS-migration) | SSAS migration notes |

## Server objects and configuration
| Folder | What it covers |
|---|---|
| [server-level-configuration-scripting](server-level-configuration-scripting) | Script out server-level configuration |
| [Linked-Server](Linked-Server) | Create linked servers, including an automated stored procedure |
| [list-all-linked-servers](list-all-linked-servers) | List all linked servers |
| [Create-SQL-Server-Alias-2022-](Create-SQL-Server-Alias-2022-) | Create SQL Server client aliases |
| [Scriptout-database-mail-setting](Scriptout-database-mail-setting) | Script out Database Mail profiles and accounts |
