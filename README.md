# MBD Process Management

* Aras Innovator manages the data and deliverables of "V-shaped process" in model-based development.

* モデルベース開発における「V字プロセス」のデータや成果物をAras Innovatorにより管理します。

## History

Release | Notes
--------|--------
[v1.0](https://github.com/mcor-aras/mbd-process/releases/tag/v1.0) | Initial Release

#### Supported Aras Versions

Project | Aras
--------|------
[v1.0](https://github.com/mcor-aras/mbd-process/releases/tag/v1.0) | 11.0 SP9

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch.**

### Pre-requisites

1. Aras Innovator installed
2. Visual Collaboration installed
3. Aras Package Import tool
4. MBD-Process import package


### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Copy the Client folder below the Client folder of the Aras Innovator installation folder.
3. Open up the Aras Package Import tool.
4. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
5. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
6. Enter the path to your local `..\mbd-process\Import\imports.mf` file in the Manifest File field.
7. Select **com.aras.innovator.core**, **jp.co.mcor.mbd-process** in the Available for Import field.
8. Select Type = **Merge** and Mode = **Thorough Mode**.
9. Click **Import** in the top left corner.
10. Close the Aras Package Import tool.

#### _Optional:_
Japanese language settings may be applied using the contents of the Language directory and the LanguagePackManagementUtility.

## Usage

Review the [ReadMe(MBDProcessManagement).pdf](./Documentation/ReadMe-MBDProcessManagement.pdf) for additional information on using the project. {[English translation](./Documentation/ReadMe-MBDProcessManagement-English.pdf)}

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Created by MCOR Co.,Ltd
