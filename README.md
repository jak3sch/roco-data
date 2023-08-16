# Roco data repository

This repository stores data for backup and workflow purpose.

## Releases

Releases contains the data files. The version numbers consists from `season`.`week`.`iteration`.

Therefore, the files for each week are separated and can be viewed as backups. After the season, all weekly data will be deleted and only a file with season totals will be saved.

## Authentification

In order to keep the automatic workflow running, a gitlab access token must be provided. It must be stored in the gitlab repo as a pipeline variable.
