| Announcements |
|-|
| [[Ubuntu, Windows] Docker Compose v1 will be removed from images on July, 29](https://github.com/actions/runner-images/issues/9692) |
***
# Windows Server 2019
- OS Version: 10.0.17763 Build 6054
- Image Version: 20240717.1.0

## Windows features
- Windows Subsystem for Linux (WSLv1): Enabled

## Installed Software

### Language and Runtime
- Bash 5.2.26(1)-release
- Go 1.21.12
- Julia 1.10.4
- Kotlin 2.0.0
- LLVM 18.1.8
- Node 18.20.3
- Perl 5.32.1
- PHP 8.3.9
- Python 3.7.9
- Ruby 3.0.7p220

### Package Management
- Chocolatey 2.3.0
- Composer 2.7.7
- Helm 3.15.2
- Miniconda 24.5.0 (pre-installed on the image but not added to PATH)
- NPM 10.7.0
- NuGet 6.10.1.5
- pip 24.0 (python 3.7)
- Pipx 1.2.1
- RubyGems 3.2.33
- Vcpkg (build from commit 1318ab14a)
- Yarn 1.22.22

#### Environment variables
| Name                    | Value        |
| ----------------------- | ------------ |
| VCPKG_INSTALLATION_ROOT | C:\vcpkg     |
| CONDA                   | C:\Miniconda |

### Project Management
- Ant 1.10.14
- Gradle 8.8
- Maven 3.8.7
- sbt 1.10.1

### Tools
- 7zip 24.07
- aria2 1.37.0
- azcopy 10.25.1
- Bazel 7.2.1
- Bazelisk 1.19.0
- Bicep 0.28.1
- Cabal 3.12.1.0
- CMake 3.30.0
- CodeQL Action Bundle 2.18.0
- Docker 26.1.3
- Docker Compose v1 1.29.2
- Docker Compose v2 2.27.1
- Docker-wincred 0.8.2
- ghc 9.10.1
- Git 2.45.2.windows.1
- Git LFS 3.5.1
- Google Cloud CLI 484.0.0
- ImageMagick 7.1.1-35
- InnoSetup 6.3.3
- jq 1.7.1
- Kind 0.23.0
- Kubectl 1.30.3
- Mercurial 5.0
- gcc 8.1.0
- gdb 8.1
- GNU Binutils 2.30
- Newman 6.1.3
- NSIS 3.10
- OpenSSL 1.1.1w
- Packer 1.11.0
- Parcel 2.12.0
- Pulumi 3.124.0
- R 4.4.1
- Service Fabric SDK 9.1.1436.9590
- Stack 2.15.7
- Subversion (SVN) 1.14.2
- Swig 4.1.1
- VSWhere 3.1.7
- WinAppDriver 1.2.2009.02003
- WiX Toolset 3.14.1.8722
- yamllint 1.32.0
- zstd 1.5.6

### CLI Tools
- Alibaba Cloud CLI 3.0.213
- AWS CLI 2.17.13
- AWS SAM CLI 1.120.0
- AWS Session Manager CLI 1.2.650.0
- Azure CLI 2.62.0
- Azure DevOps CLI extension 1.0.1
- Cloud Foundry CLI 8.7.11
- GitHub CLI 2.53.0

### Rust Tools
- Cargo 1.79.0
- Rust 1.79.0
- Rustdoc 1.79.0
- Rustup 1.27.1

#### Packages
- bindgen 0.69.4
- cargo-audit 0.20.0
- cargo-outdated 0.15.0
- cbindgen 0.26.0
- Clippy 0.1.79
- Rustfmt 1.7.0

### Browsers and Drivers
- Google Chrome 126.0.6478.183
- Chrome Driver 126.0.6478.182
- Microsoft Edge 126.0.2592.102
- Microsoft Edge Driver 126.0.2592.102
- Mozilla Firefox 128.0
- Gecko Driver 0.34.0
- IE Driver 4.14.0.0
- Selenium server 4.22.0

#### Environment variables
| Name              | Value                              |
| ----------------- | ---------------------------------- |
| CHROMEWEBDRIVER   | C:\SeleniumWebDrivers\ChromeDriver |
| EDGEWEBDRIVER     | C:\SeleniumWebDrivers\EdgeDriver   |
| GECKOWEBDRIVER    | C:\SeleniumWebDrivers\GeckoDriver  |
| SELENIUM_JAR_PATH | C:\selenium\selenium-server.jar    |

### Java
| Version             | Environment Variable |
| ------------------- | -------------------- |
| 8.0.412+8 (default) | JAVA_HOME_8_X64      |
| 11.0.23+9           | JAVA_HOME_11_X64     |
| 17.0.11+9           | JAVA_HOME_17_X64     |
| 21.0.3+9.0          | JAVA_HOME_21_X64     |

### Shells
| Name          | Target                            |
| ------------- | --------------------------------- |
| gitbash.exe   | C:\Program Files\Git\bin\bash.exe |
| msys2bash.cmd | C:\msys64\usr\bin\bash.exe        |
| wslbash.exe   | C:\Windows\System32\bash.exe      |

### MSYS2
- Pacman 6.1.0

#### Notes
```
Location: C:\msys64

Note: MSYS2 is pre-installed on image but not added to PATH.
```

### BizTalk Server
- BizTalk Server Project Build Component 3.13.832.0

### Cached Tools

#### Go
- 1.20.14
- 1.21.12
- 1.22.5

#### Node.js
- 16.20.2
- 18.20.4
- 20.15.1

#### Python
- 3.7.9
- 3.8.10
- 3.9.13
- 3.10.11
- 3.11.9
- 3.12.4

#### PyPy
- 2.7.18 [PyPy 7.3.16]
- 3.6.12 [PyPy 7.3.3]
- 3.7.13 [PyPy 7.3.9]
- 3.8.16 [PyPy 7.3.11]
- 3.9.19 [PyPy 7.3.16]
- 3.10.14 [PyPy 7.3.16]

#### Ruby
- 3.0.7
- 3.1.6
- 3.2.4

### Databases

#### PostgreSQL
| Property             | Value                                                                                                                                |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| ServiceName          | postgresql-x64-14                                                                                                                    |
| Version              | 14.12                                                                                                                                |
| ServiceStatus        | Stopped                                                                                                                              |
| ServiceStartType     | Disabled                                                                                                                             |
| EnvironmentVariables | PGBIN=C:\Program Files\PostgreSQL\14\bin <br> PGDATA=C:\Program Files\PostgreSQL\14\data <br> PGROOT=C:\Program Files\PostgreSQL\14  |
| Path                 | C:\Program Files\PostgreSQL\14                                                                                                       |
| UserName             | postgres                                                                                                                             |
| Password             | root                                                                                                                                 |

#### MongoDB
| Version  | ServiceName | ServiceStatus | ServiceStartType |
| -------- | ----------- | ------------- | ---------------- |
| 5.0.28.0 | MongoDB     | Stopped       | Disabled         |

### Database tools
- Azure CosmosDb Emulator 2.14.18.0
- DacFx 162.3.566.1
- MySQL 5.7.44.0
- SQL OLEDB Driver 18.7.4.0
- SQLPS 1.0

### Web Servers
| Name   | Version | ConfigFile                            | ServiceName | ServiceStatus | ListenPort |
| ------ | ------- | ------------------------------------- | ----------- | ------------- | ---------- |
| Apache | 2.4.55  | C:\tools\Apache24\conf\httpd.conf     | Apache      | Stopped       | 80         |
| Nginx  | 1.27.0  | C:\tools\nginx-1.27.0\conf\nginx.conf | nginx       | Stopped       | 80         |

### Visual Studio Enterprise 2019
| Name                          | Version         | Path                                                           |
| ----------------------------- | --------------- | -------------------------------------------------------------- |
| Visual Studio Enterprise 2019 | 16.11.35026.282 | C:\Program Files (x86)\Microsoft Visual Studio\2019\Enterprise |

#### Workloads, components and extensions
| Package                                                                   | Version         |
| ------------------------------------------------------------------------- | --------------- |
| Component.Android.NDK.R16B                                                | 16.11.35026.282 |
| Component.Android.SDK25.Private                                           | 16.0.28625.61   |
| Component.Android.SDK30                                                   | 16.10.31205.252 |
| Component.Ant                                                             | 1.9.3.8         |
| Component.Dotfuscator                                                     | 16.10.31205.252 |
| Component.Linux.CMake                                                     | 16.2.29003.222  |
| Component.MDD.Android                                                     | 16.0.28517.75   |
| Component.MDD.Linux                                                       | 16.5.29515.121  |
| Component.MDD.Linux.GCC.arm                                               | 16.5.29515.121  |
| Component.Microsoft.VisualStudio.LiveShare                                | 1.0.4441        |
| Component.Microsoft.VisualStudio.RazorExtension                           | 16.10.31205.252 |
| Component.Microsoft.VisualStudio.Tools.Applications                       | 16.0.31110.1    |
| Component.Microsoft.VisualStudio.Web.AzureFunctions                       | 16.10.31205.252 |
| Component.Microsoft.Web.LibraryManager                                    | 16.10.31205.180 |
| Component.Microsoft.WebTools.BrowserLink.WebLivePreview                   | 0.7.22.39845    |
| Component.Microsoft.Windows.DriverKit                                     | 10.0.21381.0    |
| Component.OpenJDK                                                         | 16.11.31827.77  |
| Component.UnityEngine.x64                                                 | 16.10.31205.252 |
| Component.Unreal                                                          | 16.1.28810.153  |
| Component.Unreal.Android                                                  | 16.1.28810.153  |
| Component.VSInstallerProjects                                             | 1.0.2           |
| Component.WixToolset.VisualStudioExtension.Dev16                          | 1.0.0.22        |
| Component.WixToolset.VisualStudioExtension.Schemas3                       | 1.0.0.22        |
| Component.Xamarin                                                         | 16.10.31205.252 |
| Component.Xamarin.RemotedSimulator                                        | 16.11.32629.160 |
| Microsoft.Component.Azure.DataLake.Tools                                  | 16.10.31205.252 |
| Microsoft.Component.ClickOnce                                             | 16.11.31603.221 |
| Microsoft.Component.MSBuild                                               | 16.11.33214.272 |
| Microsoft.Component.NetFX.Native                                          | 16.5.29515.121  |
| Microsoft.Component.PythonTools                                           | 16.11.31314.313 |
| Microsoft.Component.PythonTools.Miniconda                                 | 16.11.31314.313 |
| Microsoft.Component.PythonTools.Web                                       | 16.10.31205.252 |
| Microsoft.Component.VC.Runtime.UCRTSDK                                    | 16.0.28625.61   |
| Microsoft.ComponentGroup.Blend                                            | 16.0.28315.86   |
| Microsoft.ComponentGroup.ClickOnce.Publish                                | 16.11.31603.221 |
| Microsoft.Net.Component.3.5.DeveloperTools                                | 16.0.28517.75   |
| Microsoft.Net.Component.4.5.1.TargetingPack                               | 16.11.31605.320 |
| Microsoft.Net.Component.4.5.2.TargetingPack                               | 16.0.28517.75   |
| Microsoft.Net.Component.4.5.TargetingPack                                 | 16.11.31605.320 |
| Microsoft.Net.Component.4.6.1.TargetingPack                               | 16.0.28517.75   |
| Microsoft.Net.Component.4.6.2.TargetingPack                               | 16.0.28517.75   |
| Microsoft.Net.Component.4.6.TargetingPack                                 | 16.0.28517.75   |
| Microsoft.Net.Component.4.7.1.TargetingPack                               | 16.10.31205.252 |
| Microsoft.Net.Component.4.7.2.SDK                                         | 16.4.29409.204  |
| Microsoft.Net.Component.4.7.2.TargetingPack                               | 16.10.31205.252 |
| Microsoft.Net.Component.4.7.TargetingPack                                 | 16.10.31205.252 |
| Microsoft.Net.Component.4.8.SDK                                           | 16.4.29313.120  |
| Microsoft.Net.Component.4.TargetingPack                                   | 16.11.31605.320 |
| Microsoft.Net.ComponentGroup.4.6.2.DeveloperTools                         | 16.3.29207.166  |
| Microsoft.Net.ComponentGroup.4.7.1.DeveloperTools                         | 16.3.29207.166  |
| Microsoft.Net.ComponentGroup.4.7.DeveloperTools                           | 16.3.29207.166  |
| Microsoft.Net.ComponentGroup.DevelopmentPrerequisites                     | 16.3.29207.166  |
| Microsoft.Net.ComponentGroup.TargetingPacks.Common                        | 16.0.28516.191  |
| Microsoft.NetCore.Component.DevelopmentTools                              | 16.11.33214.272 |
| Microsoft.NetCore.Component.Web                                           | 16.11.33214.272 |
| Microsoft.VisualStudio.Component.AppInsights.Tools                        | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.AspNet45                                 | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Azure.AuthoringTools                     | 16.11.31827.77  |
| Microsoft.VisualStudio.Component.Azure.ClientLibs                         | 16.11.34829.67  |
| Microsoft.VisualStudio.Component.Azure.Compute.Emulator                   | 16.11.31827.77  |
| Microsoft.VisualStudio.Component.Azure.Kubernetes.Tools                   | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Azure.Powershell                         | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.Azure.ResourceManager.Tools              | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.Azure.ServiceFabric.Tools                | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.Azure.Storage.Emulator                   | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.Azure.Waverton                           | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Azure.Waverton.BuildTools                | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.ClassDesigner                            | 16.0.28528.71   |
| Microsoft.VisualStudio.Component.CloudExplorer                            | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.CodeMap                                  | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.Common.Azure.Tools                       | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.CoreEditor                               | 16.1.28811.260  |
| Microsoft.VisualStudio.Component.Debugger.JustInTime                      | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.Debugger.Snapshot                        | 16.5.29813.82   |
| Microsoft.VisualStudio.Component.Debugger.TimeTravel                      | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.DiagnosticTools                          | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.DockerTools                              | 16.11.33214.272 |
| Microsoft.VisualStudio.Component.DotNetModelBuilder                       | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.DslTools                                 | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.EntityFramework                          | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.FSharp                                   | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.FSharp.Desktop                           | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.FSharp.WebTemplates                      | 16.3.29207.166  |
| Microsoft.VisualStudio.Component.GraphDocument                            | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.Graphics                                 | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Graphics.Tools                           | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.IISExpress                               | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.IntelliCode                              | 16.11.31603.221 |
| Microsoft.VisualStudio.Component.IntelliTrace.FrontEnd                    | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.JavaScript.Diagnostics                   | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.JavaScript.TypeScript                    | 16.11.31404.150 |
| Microsoft.VisualStudio.Component.LinqToSql                                | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.LiveUnitTesting                          | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.ManagedDesktop.Core                      | 16.4.29318.151  |
| Microsoft.VisualStudio.Component.ManagedDesktop.Prerequisites             | 16.11.33214.272 |
| Microsoft.VisualStudio.Component.Merq                                     | 16.2.29012.281  |
| Microsoft.VisualStudio.Component.MonoDebugger                             | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.MSODBC.SQL                               | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils                         | 16.0.28707.177  |
| Microsoft.VisualStudio.Component.Node.Tools                               | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.NuGet                                    | 16.1.28829.92   |
| Microsoft.VisualStudio.Component.NuGet.BuildTools                         | 16.1.28829.92   |
| Microsoft.VisualStudio.Component.PortableLibrary                          | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Roslyn.Compiler                          | 16.0.28714.129  |
| Microsoft.VisualStudio.Component.Roslyn.LanguageServices                  | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Sharepoint.Tools                         | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.SQL.ADAL                                 | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.SQL.CLR                                  | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.SQL.DataSources                          | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime                      | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.SQL.SSDT                                 | 16.3.29207.166  |
| Microsoft.VisualStudio.Component.TeamOffice                               | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.TestTools.CodedUITest                    | 16.0.28327.66   |
| Microsoft.VisualStudio.Component.TestTools.WebLoadTest                    | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.TextTemplating                           | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.TypeScript.4.3                           | 16.0.31506.151  |
| Microsoft.VisualStudio.Component.Unity                                    | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.UWP.VC.ARM64                             | 16.3.29207.166  |
| Microsoft.VisualStudio.Component.VC.14.25.x86.x64                         | 16.11.32428.96  |
| Microsoft.VisualStudio.Component.VC.140                                   | 16.11.33801.447 |
| Microsoft.VisualStudio.Component.VC.ASAN                                  | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.ATL                                   | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.ATL.ARM                               | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.ATL.ARM.Spectre                       | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.ATL.ARM64                             | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.ATL.ARM64.Spectre                     | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.ATL.Spectre                           | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.ATLMFC                                | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.ATLMFC.Spectre                        | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.CLI.Support                           | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.CMake.Project                         | 16.3.29103.31   |
| Microsoft.VisualStudio.Component.VC.CoreIde                               | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.DiagnosticTools                       | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.Llvm.Clang                            | 16.11.31603.221 |
| Microsoft.VisualStudio.Component.VC.Llvm.ClangToolset                     | 16.3.29207.166  |
| Microsoft.VisualStudio.Component.VC.MFC.ARM                               | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.MFC.ARM.Spectre                       | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.MFC.ARM64                             | 16.4.29313.120  |
| Microsoft.VisualStudio.Component.VC.MFC.ARM64.Spectre                     | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.Modules.x86.x64                       | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.Redist.14.Latest                      | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.Redist.MSM                            | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.Runtimes.ARM.Spectre                  | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.Runtimes.ARM64.Spectre                | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.Runtimes.x86.x64.Spectre              | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.TestAdapterForBoostTest               | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.VC.TestAdapterForGoogleTest              | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.VC.Tools.ARM                             | 16.11.32406.258 |
| Microsoft.VisualStudio.Component.VC.Tools.ARM64                           | 16.11.32406.258 |
| Microsoft.VisualStudio.Component.VC.Tools.ARM64EC                         | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.Tools.x86.x64                         | 16.11.32406.258 |
| Microsoft.VisualStudio.Component.VC.v141.ARM                              | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.v141.ARM.Spectre                      | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.v141.ARM64                            | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.v141.ARM64.Spectre                    | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VC.v141.ATL                              | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.ATL.ARM                          | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.ATL.ARM.Spectre                  | 16.5.29721.120  |
| Microsoft.VisualStudio.Component.VC.v141.ATL.ARM64                        | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.ATL.ARM64.Spectre                | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.ATL.Spectre                      | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.MFC                              | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.MFC.ARM.Spectre                  | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.MFC.ARM64.Spectre                | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.MFC.Spectre                      | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.VC.v141.x86.x64                          | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.VC.v141.x86.x64.Spectre                  | 16.5.29515.121  |
| Microsoft.VisualStudio.Component.VSSDK                                    | 16.0.28315.86   |
| Microsoft.VisualStudio.Component.Wcf.Tooling                              | 16.0.28625.61   |
| Microsoft.VisualStudio.Component.Web                                      | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.WebDeploy                                | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.Windows10SDK                             | 16.4.29409.204  |
| Microsoft.VisualStudio.Component.Windows10SDK.16299                       | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Windows10SDK.17134                       | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Windows10SDK.17763                       | 16.0.28517.75   |
| Microsoft.VisualStudio.Component.Windows10SDK.18362                       | 16.1.28829.92   |
| Microsoft.VisualStudio.Component.Windows10SDK.19041                       | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Windows10SDK.20348                       | 16.11.31603.221 |
| Microsoft.VisualStudio.Component.Windows11SDK.22000                       | 16.11.31727.170 |
| Microsoft.VisualStudio.Component.WinXP                                    | 16.10.31205.252 |
| Microsoft.VisualStudio.Component.Workflow                                 | 16.0.28315.86   |
| Microsoft.VisualStudio.ComponentGroup.ArchitectureTools.Native            | 16.0.28621.142  |
| Microsoft.VisualStudio.ComponentGroup.Azure.CloudServices                 | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.Azure.Prerequisites                 | 16.10.31303.231 |
| Microsoft.VisualStudio.ComponentGroup.Azure.ResourceManager.Tools         | 16.0.28528.71   |
| Microsoft.VisualStudio.ComponentGroup.AzureFunctions                      | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.MSIX.Packaging                      | 16.11.34827.16  |
| Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Core                  | 16.2.29012.281  |
| Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Llvm.Clang            | 16.11.31603.221 |
| Microsoft.VisualStudio.ComponentGroup.UWP.NetCoreAndStandard              | 16.11.33214.272 |
| Microsoft.VisualStudio.ComponentGroup.UWP.Support                         | 16.11.33214.272 |
| Microsoft.VisualStudio.ComponentGroup.UWP.VC                              | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.UWP.VC.v141                         | 16.1.28810.153  |
| Microsoft.VisualStudio.ComponentGroup.UWP.Xamarin                         | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.VisualStudioExtension.Prerequisites | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.Web                                 | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.Web.Client                          | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.Web.CloudTools                      | 16.10.31205.180 |
| Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions                  | 16.11.32413.511 |
| Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions.CMake            | 16.11.32413.511 |
| Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions.TemplateEngine   | 16.11.32413.511 |
| Microsoft.VisualStudio.Workload.Azure                                     | 16.11.35026.282 |
| Microsoft.VisualStudio.Workload.CoreEditor                                | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.Data                                      | 16.0.28720.110  |
| Microsoft.VisualStudio.Workload.DataScience                               | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.ManagedDesktop                            | 16.11.33214.272 |
| Microsoft.VisualStudio.Workload.ManagedGame                               | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.NativeCrossPlat                           | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.NativeDesktop                             | 16.11.31727.170 |
| Microsoft.VisualStudio.Workload.NativeGame                                | 16.11.31727.170 |
| Microsoft.VisualStudio.Workload.NativeMobile                              | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.NetCoreTools                              | 16.11.33214.272 |
| Microsoft.VisualStudio.Workload.NetCrossPlat                              | 16.11.33214.272 |
| Microsoft.VisualStudio.Workload.NetWeb                                    | 16.11.33214.272 |
| Microsoft.VisualStudio.Workload.Node                                      | 16.10.31205.180 |
| Microsoft.VisualStudio.Workload.Office                                    | 16.11.33214.272 |
| Microsoft.VisualStudio.Workload.Python                                    | 16.11.33328.57  |
| Microsoft.VisualStudio.Workload.Universal                                 | 16.11.33214.272 |
| Microsoft.VisualStudio.Workload.VisualStudioExtension                     | 16.10.31205.180 |
| ms-biztalk.BizTalk                                                        | 3.13.2.0        |
| ProBITools.MicrosoftAnalysisServicesModelingProjects                      | 2.9.18          |
| ProBITools.MicrosoftReportProjectsforVisualStudio                         | 2.6.11          |
| SSIS.SqlServerIntegrationServicesProjects                                 | 4.6             |
| VisualStudioClient.MicrosoftVisualStudio2017InstallerProjects             | 1.0.2           |
| Windows Driver Kit                                                        | 10.1.22000.1    |
| Windows Driver Kit Visual Studio Extension                                | 10.0.21381.0    |
| Windows Software Development Kit                                          | 10.1.22621.755  |
| WixToolset.WixToolsetVisualStudio2019Extension                            | 1.0.0.22        |

#### Microsoft Visual C++
| Name                                         | Architecture | Version     |
| -------------------------------------------- | ------------ | ----------- |
| Microsoft Visual C++ 2010 Redistributable    | x64          | 10.0.40219  |
| Microsoft Visual C++ 2010 Redistributable    | x86          | 10.0.40219  |
| Microsoft Visual C++ 2013 Additional Runtime | x64          | 12.0.40660  |
| Microsoft Visual C++ 2013 Minimum Runtime    | x64          | 12.0.40660  |
| Microsoft Visual C++ 2013 Additional Runtime | x86          | 12.0.21005  |
| Microsoft Visual C++ 2013 Minimum Runtime    | x86          | 12.0.21005  |
| Microsoft Visual C++ 2019 Debug Runtime      | x64          | 14.29.30153 |
| Microsoft Visual C++ 2019 Debug Runtime      | x86          | 14.29.30153 |
| Microsoft Visual C++ 2022 Additional Runtime | x64          | 14.40.33810 |
| Microsoft Visual C++ 2022 Minimum Runtime    | x64          | 14.40.33810 |
| Microsoft Visual C++ 2022 Additional Runtime | x86          | 14.40.33810 |
| Microsoft Visual C++ 2022 Minimum Runtime    | x86          | 14.40.33810 |

#### Installed Windows SDKs
- 10.0.14393.0
- 10.0.16299.0
- 10.0.17134.0
- 10.0.17763.0
- 10.0.18362.0
- 10.0.19041.0
- 10.0.20348.0
- 10.0.22000.0
- 10.0.22621.0

### .NET Core Tools
- .NET Core SDK: 6.0.132, 6.0.203, 6.0.321, 6.0.424, 7.0.120, 7.0.203, 7.0.317, 7.0.410, 8.0.107, 8.0.206, 8.0.303
- .NET Framework: 4.7.2, 4.8
- Microsoft.AspNetCore.App: 6.0.5, 6.0.26, 6.0.32, 7.0.5, 7.0.20, 8.0.6, 8.0.7
- Microsoft.NETCore.App: 6.0.5, 6.0.26, 6.0.32, 7.0.5, 7.0.20, 8.0.6, 8.0.7
- Microsoft.WindowsDesktop.App: 6.0.5, 6.0.26, 6.0.32, 7.0.5, 7.0.20, 8.0.6, 8.0.7
- nbgv 3.6.139+a9e8765620

### PowerShell Tools
- PowerShell 7.4.3

#### Powershell Modules
- Az: 11.3.1
- Azure: 2.1.0 (Default), 5.3.0
- AzureRM: 2.1.0 (Default), 6.13.1
- Azure (Cached): 3.8.0.zip, 4.2.1.zip, 5.1.1.zip
- AzureRM (Cached): 3.8.0.zip, 4.2.1.zip, 5.1.1.zip, 6.7.0.zip
- AWSPowershell: 4.1.618
- DockerMsftProvider: 1.0.0.8
- MarkdownPS: 1.10
- Microsoft.Graph: 2.20.0
- Pester: 3.4.0, 5.6.1
- PowerShellGet: 1.0.0.1, 2.2.5
- PSScriptAnalyzer: 1.22.0
- PSWindowsUpdate: 2.2.1.4
- SqlServer: 22.3.0
- VSSetup: 2.2.16
```
Azure PowerShell module 2.1.0 and AzureRM PowerShell module 2.1.0 are installed
and are available via 'Get-Module -ListAvailable'.
All other versions are saved but not installed.
```

### Android
| Package Name               | Version                                                                                                                                                                                                                                       |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Command Line Tools | 8.0                                                                                                                                                                                                                                           |
| Android Emulator           | 34.2.16                                                                                                                                                                                                                                       |
| Android SDK Build-tools    | 35.0.0<br>34.0.0<br>33.0.0 33.0.1 33.0.2 33.0.3<br>32.0.0<br>31.0.0<br>30.0.2                                                                                                                                                                 |
| Android SDK Platforms      | android-35 (rev 1)<br>android-34-ext8 (rev 1)<br>android-34-ext12 (rev 1)<br>android-34 (rev 3)<br>android-33-ext5 (rev 1)<br>android-33-ext4 (rev 1)<br>android-33 (rev 3)<br>android-32 (rev 1)<br>android-31 (rev 1)<br>android-30 (rev 3) |
| Android SDK Platform-Tools | 35.0.1                                                                                                                                                                                                                                        |
| Android Support Repository | 47.0.0                                                                                                                                                                                                                                        |
| CMake                      | 3.10.2<br>3.18.1<br>3.22.1                                                                                                                                                                                                                    |
| Google APIs                | addon-google_apis-google-21<br>addon-google_apis-google-22<br>addon-google_apis-google-23<br>addon-google_apis-google-24                                                                                                                      |
| Google Play services       | 49                                                                                                                                                                                                                                            |
| Google Repository          | 58                                                                                                                                                                                                                                            |
| NDK                        | 24.0.8215888<br>25.2.9519653<br>26.3.11579264                                                                                                                                                                                                 |

#### Environment variables
| Name                    | Value                                    |
| ----------------------- | ---------------------------------------- |
| ANDROID_HOME            | C:\Android\android-sdk                   |
| ANDROID_NDK             | C:\Android\android-sdk\ndk\25.2.9519653  |
| ANDROID_NDK_HOME        | C:\Android\android-sdk\ndk\25.2.9519653  |
| ANDROID_NDK_LATEST_HOME | C:\Android\android-sdk\ndk\26.3.11579264 |
| ANDROID_NDK_ROOT        | C:\Android\android-sdk\ndk\25.2.9519653  |
| ANDROID_SDK_ROOT        | C:\Android\android-sdk                   |

### Cached Docker images
| Repository:Tag                                                            | Digest                                                                   | Created    |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------- |
| mcr.microsoft.com/dotnet/framework/aspnet:4.8-windowsservercore-ltsc2019  | sha256:4d87502a9422420948af8264a1cecad215f032e4c2d4b1fb92cfee779ecfb480  | 2024-07-09 |
| mcr.microsoft.com/dotnet/framework/runtime:4.8-windowsservercore-ltsc2019 | sha256:8d7c40438ba7645768219770ab60b9b2cacc90a8a2cc2be0f880939cbc6091db  | 2024-07-09 |
| mcr.microsoft.com/dotnet/framework/sdk:4.8-windowsservercore-ltsc2019     | sha256:04e06ae8f595b48bdee73c3334e82f46ba61217e2fe29702350d7b90e9c4b787  | 2024-07-09 |
| mcr.microsoft.com/windows/nanoserver:1809                                 | sha256:736f8845da1c7bbc9510b419abddb870230485e74644a96e0001a21e1ca4c172  | 2024-07-03 |
| mcr.microsoft.com/windows/servercore:ltsc2019                             | sha256:41f42aa4ad39d85e4d30642b8111ca6454ca2275f188f012934b9afbaf63a647  | 2024-07-03 |

