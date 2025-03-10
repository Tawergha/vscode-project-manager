## [12.5.0] - 2022-02-08
### Added
- New setting to support symlinks on `baseFolder` setting (issue [#583](https://github.com/alefragnani/vscode-project-manager/issues/583))
- Support new MacOS File Menu API (issue [#555](https://github.com/alefragnani/vscode-project-manager/issues/555))
- Support new `createStatusBarItem` API (issue [#521](https://github.com/alefragnani/vscode-project-manager/issues/521))

### Changed
- Remove `watchFile` interval (issue [#575](https://github.com/alefragnani/vscode-project-manager/issues/575))

### Internal
- Duckly becomes a Sponsor

## [12.4.0] - 2021-09-08
### Added
- `View as` option to Favorites View (issue [#534](https://github.com/alefragnani/vscode-project-manager/issues/534))
- `Sort by` option to Favorites View (issue [#484](https://github.com/alefragnani/vscode-project-manager/issues/484))
- Setting to display the parent folder on duplicate (same-name) projects (issue [#306](https://github.com/alefragnani/vscode-project-manager/issues/306))

### Changed
- Side Bar tooltips now in Markdown (issue [#540](https://github.com/alefragnani/vscode-project-manager/issues/540))
- Side Bar following `sortList` setting (issue [#366](https://github.com/alefragnani/vscode-project-manager/issues/366))

### Fixed
- Typos in README (Thanks to @kant [PR #532](https://github.com/alefragnani/vscode-project-manager/pull/532))

## [12.3.0] - 2021-07-11
### Added
- Organize your projects with **Tags** (issue [#50](https://github.com/alefragnani/vscode-project-manager/issues/50))
- Documentation about how to use the extension on Remote Development (issue [#477](https://github.com/alefragnani/vscode-project-manager/issues/477))
- Use specific icons for each kind of remote project (issue [#483](https://github.com/alefragnani/vscode-project-manager/issues/483))

## [12.2.0] - 2021-06-10
### Added
- Support **Virtual Workspaces** (issue [#500](https://github.com/alefragnani/vscode-project-manager/issues/500))
- Support **Workspace Trust** (issue [#499](https://github.com/alefragnani/vscode-project-manager/issues/499))
- Support `.code-workspace` projects ocated on remotes (issue [#486](https://github.com/alefragnani/vscode-project-manager/issues/486))

### Fixed
- Favorite projects missing icons for Folders when using None or Seti Icon Theme (issue [#496](https://github.com/alefragnani/vscode-project-manager/issues/496))

### Internal
- Security Alert: lodash (dependabot [PR #503](https://github.com/alefragnani/vscode-project-manager/pull/503))
- Security Alert: ssri (dependabot [PR #495](https://github.com/alefragnani/vscode-project-manager/pull/495))

## [12.1.0] - 2021-04-02
### Added
- Save GitHub Codespaces projects always as "remote project" (issue [#479](https://github.com/alefragnani/vscode-project-manager/issues/479))

### Changed
- Do not show welcome message if installed by Settings Sync (issue [#459](https://github.com/alefragnani/vscode-project-manager/issues/459))

### Fixed
- Mercurial projects not found (issue [#438](https://github.com/alefragnani/vscode-project-manager/issues/438))

### Internal
- Update whats-new submodule API (issue [#456](https://github.com/alefragnani/vscode-project-manager/issues/456))
- Add badges to Readme (issue [#359](https://github.com/alefragnani/vscode-project-manager/issues/359))
- Security Alert: y18n (dependabot [PR #482](https://github.com/alefragnani/vscode-project-manager/pull/482))
- Security Alert: elliptic (dependabot [PR #472](https://github.com/alefragnani/vscode-project-manager/pull/472))

## [12.0.1] - 2020-11-23
### Fixed
- Conflict with non-unique command (issue [#441](https://github.com/alefragnani/vscode-project-manager/issues/441))

## [12.0.0] - 2020-11-19
### Added
- `Open Settings` command to the Side Bar (issue [#434](https://github.com/alefragnani/vscode-project-manager/issues/434))
- Concatenates the "Number of Projects" on each Panel in the Side Bar (issue [#267](https://github.com/alefragnani/vscode-project-manager/issues/267))
- `Reveal in Finder/Explorer` command in the Side Bar's context menu (issue [#322](https://github.com/alefragnani/vscode-project-manager/issues/322))
- Setting to decide if auto-detected projects should ignore projects found inside other projects (issue [#189](https://github.com/alefragnani/vscode-project-manager/issues/189))

### Internal
- Use `vscode-ext-help-and-feedback` package (issue [#432](https://github.com/alefragnani/vscode-project-manager/issues/432))

## [11.3.1] - 2020-10-16
### Internal
- Update CodeStream sponsorship details

## [11.3.0] - 2020-09-06
### Added
- Support `$home` and `~` (tilde) symbol on `projectLocation` setting (issue [#384](https://github.com/alefragnani/vscode-project-manager/issues/384))
- Support `~` (tilde) symbol on any path related setting (issue [#414](https://github.com/alefragnani/vscode-project-manager/issues/414))
- Support `glob` patterns in `ignoredFolders` settings (issue [#278](https://github.com/alefragnani/vscode-project-manager/issues/278))
- Localization - Czech (Thanks to @Amereyeu [PR #412](https://github.com/alefragnani/vscode-project-manager/pull/412))

## [11.2.0] - 2020-08-19
### Added
- Support string array in Settings UI (issue [#410](https://github.com/alefragnani/vscode-project-manager/issues/410))
- Use new remote codicon (issue [#396](https://github.com/alefragnani/vscode-project-manager/issues/396))

### Fixed
- Weird icon behaviour when no ThemeIcon is selected (issue [#392](https://github.com/alefragnani/vscode-project-manager/issues/392))
- maxDepthRecursion worried about extra trailing path separator (issue [#404](https://github.com/alefragnani/vscode-project-manager/issues/404))
- Localization - Simplified Chinese (Thanks to @loniceras [PR #403](https://github.com/alefragnani/vscode-project-manager/pull/403))
- Typo in What's New (Thanks to @geauxtigers [PR #390](https://github.com/alefragnani/vscode-project-manager/pull/390))

## [11.1.0] - 2020-06-19
### Changed
- Internal commands can't be customisable (issue [#388](https://github.com/alefragnani/vscode-project-manager/issues/388))

### Fixed
- Status bar not working on remotes (issue [#379](https://github.com/alefragnani/vscode-project-manager/issues/379))
- `Command Palette` showing ”Path does not exists” for remote projects (issue [#380](https://github.com/alefragnani/vscode-project-manager/issues/380))
- `Open Folder` command in Welcome view not working on Windows (issue [#387](https://github.com/alefragnani/vscode-project-manager/issues/387))

### Internal
- Migrate from TSLint to ESLint (issue [#360](https://github.com/alefragnani/vscode-project-manager/issues/360))
- Use `vscode-ext-codicons` package (issue [#386](https://github.com/alefragnani/vscode-project-manager/issues/386))

## [11.0.1] - 2020-05-19
### Fixed
- Path does not exists for SSH remote project (issue [#375](https://github.com/alefragnani/vscode-project-manager/issues/375))
- `Open` command in Side Bar's context menu does not work (issue [#376](https://github.com/alefragnani/vscode-project-manager/issues/376))
- Path does not exists for Docker remote project on Windows (issue [#377](https://github.com/alefragnani/vscode-project-manager/issues/377))

## [11.0.0] - 2020-05-14
### Added
- Support open **Remote Projects** from your local installation (issue [#345](https://github.com/alefragnani/vscode-project-manager/issues/345))
- **Side Bar** welcome message (issue [#353](https://github.com/alefragnani/vscode-project-manager/issues/353))

### Internal
- Remove `vscode` module dependency (issue [#369](https://github.com/alefragnani/vscode-project-manager/issues/369))

## [10.12.0] - 2020-04-25
### Added
- Setting to decide if the `Open in New Window` command should open in the current window, if empty (issue [#188](https://github.com/alefragnani/vscode-project-manager/issues/188))

### Fixed
- Typo in README (Thanks to @1st [PR #348](https://github.com/alefragnani/vscode-project-manager/pull/348))
- Typo in README (issue [#337](https://github.com/alefragnani/vscode-project-manager/issues/337))

## Internal
- Support VS Code package split  (issue [#361](https://github.com/alefragnani/vscode-project-manager/issues/361))
- Support Extension View Context Menu (issue [#327](https://github.com/alefragnani/vscode-project-manager/issues/327))

## [10.11.0] - 2020-03-06
### Added
- Increase **Remote Development** support (issues [#323](https://github.com/alefragnani/vscode-project-manager/issues/323) and (Thanks to @egamma [PR #331](https://github.com/alefragnani/vscode-project-manager/pull/331))
- `Add Project to Workspace` command in Command Palette (issues [#283](https://github.com/alefragnani/vscode-project-manager/issues/283)

## Internal
- Support **ThemeIcon** (issues [#326](https://github.com/alefragnani/vscode-project-manager/issues/326)

## [10.10.0] - 2020-01-25
### Added
- Support **Remote Development** (issues [#284](https://github.com/alefragnani/vscode-project-manager/issues/284) and [#318](https://github.com/alefragnani/vscode-project-manager/issues/318))

## [10.9.1] - 2019-11-21
### Changed
- Update CodeStream Ad and URL

## [10.9.0] - 2019-11-18
### Added
- Localization support - Simplified Chinese (Thanks to @L1cardo [PR #300](https://github.com/alefragnani/vscode-project-manager/pull/300))
- `Open in New Window` hover command in Side Bar

## [10.8.0] - 2019-09-25
### Added
- Support to save **Workspaces** as projects

## [10.7.0] - 2019-08-25
### Added
- New Side Bar icon matching new VS Code icon style

## [10.6.0] - 2019-07-28
### Added
- Support for _auto-detected_ projects only scenario
- Localization support - Portuguese (Brazil)
- `Save Button` button in Side Bar

## [10.5.2] - 2019-05-28
### Fixed
- Security Alert: tar

## [10.5.1] - 2019-04-05
### Fixed
- Deprecate `projectManager.treeview.visible` setting. (issue [#265](https://github.com/alefragnani/vscode-project-manager/issues/265))

## [10.5.0] - 2019-04-02
### Added
- Faster startup (Side Bar) (issue [#264](https://github.com/alefragnani/vscode-project-manager/issues/264))

## [10.4.0] - 2019-03-14
### Added
- `GlobalStoragePath` Support (Thanks to @Chuxel [PR #250](https://github.com/alefragnani/vscode-project-manager/pull/250))
- Localization support - Russian (Thanks to @Inter-Net-Pro [PR #222](https://github.com/alefragnani/vscode-project-manager/pull/222))

### Fixed
- What's New page broken in VS Code 1.32 due to CSS API changes

## [10.3.2] - 2019-02-01
### Fixed
- Error in _clean install_ (issue [Bookmarks #178](https://github.com/alefragnani/vscode-bookmarks/issues/178))

## [10.3.1] - 2019-01-31
### Fixed
- Update CodeStream logo

## [10.3.0] - 2019-01-17
### Changed
- The **Side Bar** is now visible by default, even with no projects (issue [#227](https://github.com/alefragnani/vscode-project-manager/issues/227))

### Fixed
- The projects in the **Side Bar** should not be sorted case-sensitive (issue [#243](https://github.com/alefragnani/vscode-project-manager/issues/243))

## [10.2.0] - 2019-01-06
### Added
- Support **Portable Mode** (thanks to @hcwhan [PR 204](https://github.com/alefragnani/vscode-project-manager/pull/204) and @TanShun [PR 242](https://github.com/alefragnani/vscode-project-manager/pull/242))
- `Disable Project` command in Side Bar (thanks to @tekerson [PR 226](https://github.com/alefragnani/vscode-project-manager/pull/226))

## [10.1.0] - 2018-12-17
### Added
- `Add to Favorites` command in Side Bar (thanks to @ckaczor [PR 229](https://github.com/alefragnani/vscode-project-manager/pull/229))
- `Refresh Project` commands in Side Bar for every kind of auto-detected project (thanks to @ckaczor [PR 231](https://github.com/alefragnani/vscode-project-manager/pull/231))

## [10.0.0] - 2018-11-28
### Added
- What's New

## [9.1.0] - 2018-11-06
### Added
- CodeStream becomes a Sponsor

## [9.0.1] - 2018-09-25
### Fixed
- Avoid installation in unsupported VSCode version (issue [#198](https://github.com/alefragnani/vscode-project-manager/issues/198))

## [9.0.0] - 2018-09-19
### Added
- Support _any folder_ as project (issue [#137](https://github.com/alefragnani/vscode-project-manager/issues/137))
- Use the new NotificationUI for refresh progress (issue [#174](https://github.com/alefragnani/vscode-project-manager/issues/174))
- Add instructions for install the extension and modifying its settings (issue [#176](https://github.com/alefragnani/vscode-project-manager/issues/176))

## [8.1.0] - 2018-09-15
### Added
- Patreon button

## [8.0.0] - 2018-07-04
### Added
- Project Manager Side Bar (issue [#183](https://github.com/alefragnani/vscode-project-manager/issues/183))
- New Command in TreeView `Add to Workspace` (issue [#161](https://github.com/alefragnani/vscode-project-manager/issues/161))
- New Version Numbering based on `semver`

### Fixed
- `Save Project` command raises error when no folder is open (issue [#191](https://github.com/alefragnani/vscode-project-manager/issues/191))

## [0.25.2 - 7.2.2] - 2018-04-23
### Fixed
- Support _OSS_ releases, using the correct _User folder_ to store the projects (kudos to @Kurolox [PR 179](https://github.com/alefragnani/vscode-project-manager/pull/179))

## [0.25.0 - 7.2.0] - 2018-03-18
### New
- Support _Mercurial_ projects, similar to VSCode, Git and SVN (kudos to @lavir [PR 168](https://github.com/alefragnani/vscode-project-manager/pull/168))

### Changed
- The _sort by name_ option is now case-insensitive (kudos to @lavir [PR 169](https://github.com/alefragnani/vscode-project-manager/pull/169))

### Fixed
- Readme typo (thanks to @gavinr [PR 171](https://github.com/alefragnani/vscode-project-manager/pull/171))

## [0.24.1 - 7.1.1] - 2018-03-06
### Fixed
- `Refresh Projects` and Automatic Detection of Projects not working correctly (issues [#157](https://github.com/alefragnani/vscode-project-manager/issues/157), [#164](https://github.com/alefragnani/vscode-project-manager/issues/164), [#167](https://github.com/alefragnani/vscode-project-manager/issues/167) and [#172](https://github.com/alefragnani/vscode-project-manager/issues/172))

## [0.24.0 - 7.1.0] - 2018-02-03
### Added
- Setting to filter projects through full path (Thanks to @R3oLoN [PR #166](https://github.com/alefragnani/vscode-project-manager/pull/166))

## [0.23.1 - 7.0.1] - 2017-12-14
### Fixed
- Paths are now OS independent (issue [#152](https://github.com/alefragnani/vscode-project-manager/issues/152))
- Detect changes on any `git`, `vscode` or `svn` config (Thanks to @jcw- [PR #150](https://github.com/alefragnani/vscode-project-manager/pull/150))

## [0.23.0 - 7.0.0] - 2017-11-02
### Added
- Multi-root support (issue [#149](https://github.com/alefragnani/vscode-project-manager/issues/149))

## [0.22.0 - 6.0.0] - 2017-10-27
### Added
- Setting to display the Treeview (issue [#143](https://github.com/alefragnani/vscode-project-manager/issues/143))
- Setting to remove current project from list (Thanks to @rockingskier [PR #146](https://github.com/alefragnani/vscode-project-manager/pull/146))

### Changed
- Add `.haxelib` to `git.ignoredFolders` (Thanks to @Gamma11 [PR #140](https://github.com/alefragnani/vscode-project-manager/pull/140))

## [0.21.1 - 5.0.1] - 2017-09-08
### Fixed
- Error opening _Favorite_ projects in Treeview (issue [#141](https://github.com/alefragnani/vscode-project-manager/issues/141))

## [0.21.0 - 5.0.0] - 2017-09-07
### Added
- Projects Treeview (issue [#103](https://github.com/alefragnani/vscode-project-manager/issues/103))

## [0.20.0 - 4.5.0] - 2017-08-26
### Added
- Status Bar now also displays for auto-detected projects (VSCode, Git and SVN) (issue [#116](https://github.com/alefragnani/vscode-project-manager/issues/116))
- Support keyboard navigation (Vim like) in the project list (issue [#136](https://github.com/alefragnani/vscode-project-manager/issues/136))

## [0.19.0 - 4.4.0] - 2017-08-03
### Added
- Support _git-worktree_ projects (issue [#134](https://github.com/alefragnani/vscode-project-manager/issues/134))

## [0.18.1 - 4.3.1] - 2017-06-18
### Fixed
- Status Bar sometimes not showing in MacOS  (issue [#127](https://github.com/alefragnani/vscode-project-manager/issues/127))

## [0.18.0 - 4.3.0] - 2017-05-25
### Added
- Setting to decide if it would open projects in New Window when clicking in Status Bar
- Setting to disable checking for invalid paths before listing projects

### Changed
- Source code moved to `src` folder

## [0.17.0 - 4.2.0] - 2017-05-20
### Added
- Support grouping projects by type in `List Projects...` commands.

### Changed
- The `projectManager.openInNewWindow` setting was removed, since you already have `List Projects to Open in New Window` command.

## [0.16.0 - 4.1.0] - 2017-05-04
### Added
- Support cross platform path definitions also in VSCode, Git and SVN Projects (issue [#88](https://github.com/alefragnani/vscode-project-manager/issues/88))

## [0.15.1 - 4.1.1] - 2017-04-27
### Added
- Avoid _unnecessary_ cache delete when no `baseFolder` setting is changed in `User Settings` (issue [#111](https://github.com/alefragnani/vscode-project-manager/issues/111))

## [0.15.0 - 4.1.0] - 2017-04-18
### Added
- Projects now detect _configuration changes_ to update Git/VSCode/SVN caches (issue [#110](https://github.com/alefragnani/vscode-project-manager/issues/110))

## [0.14.0 - 4.0.0] - 2017-04-12
### Added
- Projects now detect _external changes_ to update cache (Thanks to @likun7981 [PR #107](https://github.com/alefragnani/vscode-project-manager/pull/107))

## [0.13.5 - 3.8.5] - 2017-03-18
### Fixed
- Duplicate projects being listed (Thanks to @mlewand [PR #101](https://github.com/alefragnani/vscode-project-manager/pull/101))

## [0.13.4 - 3.8.4] - 2017-05-08
### Fixed
- `Delete Project` wasn't working (Thanks to @mlewand [PR #100](https://github.com/alefragnani/vscode-project-manager/pull/100))

## [0.13.3 - 3.8.3] - 2017-05-05
### Fixed
- Extension loading delay (Thanks to @Gama11 [PR #97](https://github.com/alefragnani/vscode-project-manager/pull/97))

## [0.13.2 - 3.8.2] - 2017-02-01
### Fixed
- Status Bar not working for newly saved projects in macOS and Linux (issue [#84](https://github.com/alefragnani/vscode-project-manager/issues/84))

## [0.13.1 - 3.8.1] - 2017-01-28
### Fixed
- Invalid `projects.json` file causing erros (issue [#82](https://github.com/alefragnani/vscode-project-manager/issues/82))
- Projects not displaying when no projects saved (Thanks to @samuelsuarez [PR #81](https://github.com/alefragnani/vscode-project-manager/pull/81))
- Typo in message (Thanks to @Gama11 [PR #83](https://github.com/alefragnani/vscode-project-manager/pull/83))

### Changed
- Enabled **TSLint**

## [0.13.0 - 3.8.0] - 2017-01-15
### Added
- Also list _Git_ and _SVN_ projects
- Setting to support Git and SVN projects (`baseFolders`, `maxDepthRecursion` and `ignoredFolders`)
- Setting to cache VSCode, Git and SVN projects 

### Added
- New Command `Refresh Projects`

### Changed
- `projects.json` file has been refactored to support upcoming features 

## [0.12.2 - 3.7.2] - 2016-11-06
### Fixed
- Saving a project with a new name was duplicating the Status Bar (issue [#69](https://github.com/alefragnani/vscode-project-manager/issues/69))

## [0.12.1 - 3.7.1] - 2016-11-05
### Fixed
- The `path` should not be relevant while filtering projects (issue [#67](https://github.com/alefragnani/vscode-project-manager/issues/67))

## [0.12.0 - 3.7.0] - 2016-10-26
### Added
- Display the _Project Name_ in the Status Bar (kudos to @BonDoQ)
- Setting to display the _Project Name_ in the Status Bar 
- Improved message when there is project saved yet (issue [#57](https://github.com/alefragnani/vscode-project-manager/issues/57))

## [0.11.0 - 3.6.0] - 2016-10-19
### Added
- Also list _VS Code_ projects
- Setting to support VS Code projects (`baseFolders`, `maxDepthRecursion` and `ignoredFolders`)

## [0.10.0 - 3.5.0] - 2016-09-20
### Added
- New Command `List Projects to Open in New Window`
- Comment for `sortList` setting now shows available options (issue [#52](https://github.com/alefragnani/vscode-project-manager/issues/52))

### Changed
- Renamed Command `List Projects to Open`

## [0.9.2 - 3.4.2] - 2016-09-09
### Fixed
- Interim fix for project's name suggestion not working (also in _Stable_ release) (issue [#51](https://github.com/alefragnani/vscode-project-manager/issues/51))

## [0.9.1 - 3.4.1] - 2016-09-04
### Fixed
- Saving projects with no name (_Insider_ release) (issue [#42](https://github.com/alefragnani/vscode-project-manager/issues/42))

## [0.9.0 - 3.4.0] - 2016-09-01
### Added
- Added another **Sort** option (`Recent`)

## [0.8.3 - 3.3.1] - 2016-08-03
### Fixed
- Linux support broken (issue [#39](https://github.com/alefragnani/vscode-project-manager/issues/39))

## [0.8.2 - 3.3.0] - 2016-07-29
### Added
- The extension now supports **VSCode Insiders** version and has its own `projects.json` file. Use the **new setting** if you want to have **Stable** and **Insider** versions sharing the project list. 
- Setting to indicate an alternative location where the `projects.json` file is located

### Fixed
- Not working on machines with _only_ **VSCode Insider** version installed (issue [#22](https://github.com/alefragnani/vscode-project-manager/issues/22))

## [0.8.1 - 3.2.1] - 2016-07-27
### Fixed
- Sort by _Saved_ not available (issue [#37](https://github.com/alefragnani/vscode-project-manager/issues/37))

## [0.8.0 - 3.2.0] - 2016-07-14
### Added
- Support `$home` variable in project paths (kudos to @efidiles)

## [0.7.1 - 3.1.1] - 2016-05-30
### Fixed
- List Projects command failed when no folder is open (issue [#32](https://github.com/alefragnani/vscode-project-manager/issues/32))

## [0.7.0 - 3.1.0] - 2016-05-17
### Added
- Don't show the current folder/project in the project list (issue [#28](https://github.com/alefragnani/vscode-project-manager/issues/28))
- Indicate _invalid paths_ in the project list (issue [#30](https://github.com/alefragnani/vscode-project-manager/issues/30))

## [0.6.0 - 3.0.0] - 2016-04-26
### Added
- Use new native API for opening folders _(requires VSCode 1.1.0 or higher)_

### Changed
- The `projectManager.codePath` and `projectManager.useAlternativeMacOSXPath` where removed because are not necessary anymore.

### Fixed
- Click or enter in project list does not work (Linux / Mac) (issue [#27](https://github.com/alefragnani/vscode-project-manager/issues/27))

## [0.5.5 - 2.0.5] - 2016-04-03
### Fixed
- Saving projects not working in Linux (issue [#16](https://github.com/alefragnani/vscode-project-manager/issues/16)
- Readme updated to better explain how to install and configure the extension

## [0.5.4 - 2.0.4] - 2016-03-14
### Fixed
- Updated instructions for Mac OS X after Code February Release (issue [#14](https://github.com/alefragnani/vscode-project-manager/issues/14) - Thanks to @satokaz, @janmarek and @csholmq)

## [0.5.3 - 2.0.3] - 2016-03-09
### Fixed
- Save Project was using the whole path (issue [#12](https://github.com/alefragnani/vscode-project-manager/issues/12))

## [0.5.2 - 2.0.2] - 2016-02-24
### Fixed
- Project switch not working for network folders (UNC Notation) (issue [#10](https://github.com/alefragnani/vscode-project-manager/issues/10))

## [0.5.1 - 2.0.1] - 2016-02-11
### Fixed
- Interim fix for project switching not working in Mac OS X (issue [#7](https://github.com/alefragnani/vscode-project-manager/issues/7) - Thanks to @satokaz)

## [0.5.0 - 2.0.0] - 2016-02-10
### Added
- The `projects.json` file is now formatted (Thanks to @cuth [PR #6](https://github.com/alefragnani/vscode-project-manager/pull/6))

### Fixed
- The `List Projects` keybinding was not working property (issue [#8](https://github.com/alefragnani/vscode-project-manager/issues/8)) 

## [0.4.0 - 1.3.0] - 2016-01-20
### Added
- New Command `Edit Projects`

## [0.3.1 - 1.2.1] - 2016-01-18
### Fixed
- Project switch not working properly (issue [#5](https://github.com/alefragnani/vscode-project-manager/issues/5))

## [0.3.0 - 1.2.0] - 2016-01-18
### Added
- Setting to Indicate Code path
- Setting to Open a New Window when you choose a project, or just switch the current

### Fixed
- Spaces in Project Path (issue [#3](https://github.com/alefragnani/vscode-project-manager/issues/3))

## [0.2.0 - 1.1.0] - 2016-01-16
### Added
* License updated

## [0.1.1 - 1.0.0] - 2016-01--6
* Initial release