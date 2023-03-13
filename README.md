# EzApi2022

Fork of [EzApi](http://sqlsrvintegrationsrv.codeplex.com/releases/view/21238) adapted for SQL Server 2022 version. Stand-alone edition forked by KoureasS & GitHub

## Instructions
SQLServer2022EzApi is producing SQL Server Packages with the following charateristics:
1. Build --> 16
2. PackageFormatVersion --> 8
3. TargetSQLServerVersion --> 2022
4. MicrosoftNetFramework --> 4.7.2

*Based on Microsoft Intructions, SQLServerPackages should be deployed on SQLServer using aligned version of Management Studio.
**Management Studio deployment wizard may affect the Build and PackageFormatVersion in case of using a newer version of SSMS for deploying package with older TargetSQLServerVersion version.

## Updates
2023-03-09 Added EzExecutables.EzPackage.MaxConcurrentExecutables

## Changelog
Major changes from SQLServer2019EzApi --> SQLServer2022EzApi

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

Credits are for Microsoft =)

## License

The project inherits the Microsoft license: 

Copyright © Microsoft Corporation.  All Rights Reserved.

This code released under the terms of the 

Microsoft Public License (MS-PL, http://opensource.org/licenses/ms-pl.html.)
