# Postman to OpCon Web Services
These scripts are designed to convert Postman API collections into Web Services template files.  The resulting files can then be imported into an OpCon Web Services job.

# Prerequisites
* OpCon 18.3+
* OpCon Web Services connector/subtype 20.1
* <a href='https://www.postman.com/'>Postman</a> (latest)
* Powershell 7+

# Instructions
Run the "ConvertPostman.ps1" file in the same directory as the module file.  You will also need to supply a parameter for where the Postman export is located.*

<b>Parameters</b>:
* PostmanFile -  path to the exported json file from Postman

```
powershell -ExecutionPolicy Bypass -File ".\ConvertPostman.ps1" -postmanFile "C:\postman_collection.json"
```

*To export a collection from Postman, click the 3 dots by the collection "view more actions" and choose "export".  Choose collection version 2.1 and then "export", remember where you save the resulting .json file.

# Disclaimer
No Support and No Warranty are provided by SMA Technologies for this project and related material. The use of this project's files is on your own risk.

SMA Technologies assumes no liability for damage caused by the usage of any of the files offered here via this Github repository.

# License
Copyright 2019 SMA Technologies

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Contributing
We love contributions, please read our [Contribution Guide](CONTRIBUTING.md) to get started!

# Code of Conduct
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code-of-conduct.md)
SMA Technologies has adopted the [Contributor Covenant](CODE_OF_CONDUCT.md) as its Code of Conduct, and we expect project participants to adhere to it. Please read the [full text](CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.
