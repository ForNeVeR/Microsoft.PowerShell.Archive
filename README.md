# Archive-Module
[The Archive module](https://technet.microsoft.com/en-us/library/dn818910.aspx) contains cmdlets that let you create and extract ZIP archives.

## [Compress-Archive](https://technet.microsoft.com/library/dn841358.aspx) examples
1. Create an archive from an entire folder including subdirectories: `Compress-Archive -Path C:\Reference -DestinationPath C:\Archives\Draft.zip`
2. Update an existing archive file: `Compress-Archive -Path C:\Reference\* -DestinationPath C:\Archives\Draft.zip -Update`

## [Expand-Archive](https://technet.microsoft.com/library/dn841359.aspx) examples
1. Extract the contents of an archive in the current folder: `Expand-Archive -Path SampleArchive.zip`
2. Use -Force parameter to overwrite existing files by those in the archive: `Expand-Archive -Path .\SampleArchive.zip -DestinationPath .\ExistingDir -Force`

=============

|Master   |Development |
|:------:|:-------:|:-------:|
[![Build status](https://ci.appveyor.com/api/projects/status/2c5glo1kuveayorx/branch/master?svg=true)](https://ci.appveyor.com/project/PowerShell/archive-module/branch/master)|[![Build status](https://ci.appveyor.com/api/projects/status/2c5glo1kuveayorx/branch/develop?svg=true)](https://ci.appveyor.com/project/PowerShell/archive-module/branch/develop)|