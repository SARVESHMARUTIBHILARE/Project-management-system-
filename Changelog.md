# Version: 3.5.9

* [1f45dc0](https://github.com/Leantime/leantime/commit/1f45dc06a7c596b6310a764e36f9fa6f52e1e526): task: version bump
* [2c0279a](https://github.com/Leantime/leantime/commit/2c0279adca06ec0d47b600c63e89c2b984a2a5c8): task: downgrade plugin route loader so that config updates load before route files
* [4dd0895](https://github.com/Leantime/leantime/commit/4dd08953c04e40a53532c9099f91e94cddaa00ef): feat: allow removing all new line characters from string sanitizer
* [bb31269](https://github.com/Leantime/leantime/commit/bb3126960324a0415f00ddd8d3275bc44c9edc7c): task: Update php-mcp to the latest version


# Version: 3.5.8

* [7474171](https://github.com/Leantime/leantime/commit/7474171b57235d4be8bdd051e759b99db24c1714): task: version bump
* [99275ca](https://github.com/Leantime/leantime/commit/99275ca751477ddaf9cd1f653502f848d5390c77): fix: allow loading commands from phar files


# Version: 3.5.7

* [99275ca](https://github.com/Leantime/leantime/commit/99275ca751477ddaf9cd1f653502f848d5390c77): fix: allow loading commands from phar files


# Version: 3.5.7

* [92d1521](https://github.com/Leantime/leantime/commit/92d1521e84118ca49d6d4c088ecbfd5964f9b6d3): task: version bump
* [0485867](https://github.com/Leantime/leantime/commit/04858678d93f602eeb887793934592d8778300fb): fix: Todowidget hierarchy issue with nested milestones
* [4cb4de5](https://github.com/Leantime/leantime/commit/4cb4de57d3bf7bf1e690a31d40e1341be5499aa5): task: update packages
* [9e7dda0](https://github.com/Leantime/leantime/commit/9e7dda0b2fe6bdc581b24bf5a977c3eff0549a7e): task: Claude code updates
* [e496168](https://github.com/Leantime/leantime/commit/e49616861e881666cc63f213d620d043ff9101e8): feat: Infinity scroll for tasks in todowidget to reduce HTML bloat
* [9d748a0](https://github.com/Leantime/leantime/commit/9d748a02e9d144b6a0dd04f15bff41eaa4bb7833): fix: dispatchFilter should return and not just echo
* [819fe66](https://github.com/Leantime/leantime/commit/819fe669d6e887f044e4fcacade273e982ffbe27): feat: new countNested macros for collections
* [a24ad44](https://github.com/Leantime/leantime/commit/a24ad442be9b64b7ef6eb52af51a81521d7acf09): fix: Ensure jsonrpc requests can be made from the frontend
* [ba55c55](https://github.com/Leantime/leantime/commit/ba55c55b03eb1171cdb7c480001ef7e0a36f0fdd): Update Plugins
* [f69ec85](https://github.com/Leantime/leantime/commit/f69ec85e5ebb626955bc5c1959ddcc2b97214302): task: update min stability setting
* [5e4f875](https://github.com/Leantime/leantime/commit/5e4f875c0bc4ce209916f6102b46ea86dee04f20): task: revert reverts
* [335b8e4](https://github.com/Leantime/leantime/commit/335b8e4b1b724bb2342385c66334bc8f5e365798): feat: claude code helpers
* [92168b9](https://github.com/Leantime/leantime/commit/92168b96bd49df38001f18c4b1b2a59d9232b7d4): feat: add link to marketplace in plugin news dropdown
* [7cec492](https://github.com/Leantime/leantime/commit/7cec49247186576081912f69774d7277b7a45d31): feat: add flag to allow turning off sortable via event filter
* [318182e](https://github.com/Leantime/leantime/commit/318182edbb03a1ed7b48c09721ba65eba04a7946): task: add additional template events to mytodo widget
* [02aeb7b](https://github.com/Leantime/leantime/commit/02aeb7b4efb2cea4c88696bf470f0489abd6a14f): feat: new string mixins for AI support
* [a8338bb](https://github.com/Leantime/leantime/commit/a8338bb745e7b9069b36c3f5aa706af6aab0de33): task: clean up how we load plugin paths
* [818c7ac](https://github.com/Leantime/leantime/commit/818c7acb8e8f2062c3888f6793eee6e3c7fc4388): feat: Add support for routes.php files in plugins and modules (takes precedence over frontcontroller routing)
* [a816dfb](https://github.com/Leantime/leantime/commit/a816dfb496294f01a49e5c7f44bc354e7d68b582): task: move config attribute to the appropriate folder


# Version: 3.5.6

* [1c8c3cc](https://github.com/Leantime/leantime/commit/1c8c3cc186f1f538eaf3de9384fde256177b3b4c): task: fix code style
* [98ce4c0](https://github.com/Leantime/leantime/commit/98ce4c05188b3b6a08d9d844b838ac0dfc363741): fix: project selector tabs break design in German
* [740fba1](https://github.com/Leantime/leantime/commit/740fba142670f9631557626d6ce493eb18a847e2): task: version bump
* [a17ee45](https://github.com/Leantime/leantime/commit/a17ee4550b2a18381b531faf63134a0df4a5da82): feat: add menu link to show latest plugin updates
* [8d0fcfd](https://github.com/Leantime/leantime/commit/8d0fcfdb36128a3c4fd59521ac1f9f16b8989d83): feat: preload tasks on kanban board
* [f01b11c](https://github.com/Leantime/leantime/commit/f01b11ce72864e6639481e87637deb52506f3ec4): feat: Show plugin updates
* [b8ccaeb](https://github.com/Leantime/leantime/commit/b8ccaebf827e164522129eb22e14f5a360a20a59): feat: optimize SQL indexes across the system
* [36fefc7](https://github.com/Leantime/leantime/commit/36fefc7a63990576fb48e75daa36909daa42e335): fix: readonly/commenter users were not able to see milestone cards and link was broken #3047
* [2975e15](https://github.com/Leantime/leantime/commit/2975e1536feba6055053a3c6a1c2184ecb6c331c): feat: update progress bar animation to be continuous
* [26efe4a](https://github.com/Leantime/leantime/commit/26efe4a5b114ce27b6cf21652e15ba22db9fa1f2): fix: show loading bar when reloading tasks on dashboard
* [10c4f5a](https://github.com/Leantime/leantime/commit/10c4f5ad12dfe68d3e8455611ad89f46f23b031b): task: add logging to failed event dispatches
* [a399425](https://github.com/Leantime/leantime/commit/a399425b55be743379cc1a3c88bbeeb85beb32a1): fix: users with project access through clients did not see all tasks due to wrong string comparison
* [465d1f2](https://github.com/Leantime/leantime/commit/465d1f2287f9c17554cf3280da5b1b33c9d9ebab): task: webpack update
* [1c06042](https://github.com/Leantime/leantime/commit/1c0604295bdd52602e0b5f55ad22a933d1bbb872): fix: project redirect for client-assigned projects was not working correctly.
* [8371932](https://github.com/Leantime/leantime/commit/837193234bd777eff18bd24af54e527e887ffead): task: Clean code style
* [8b56da3](https://github.com/Leantime/leantime/commit/8b56da38dad2d7a2d9e9a4fbba320b5db9515e95): task: add logging to composer loaded plugin init
* [aeb889f](https://github.com/Leantime/leantime/commit/aeb889f775ac2b16bd69727d59ea03f712f1bf23): task: update Claude code instructions
* [c946869](https://github.com/Leantime/leantime/commit/c946869313a58223aa8ee0d782dfe20e1c32accf): fix: minor CSS update for Mermaid support
* [9c34b99](https://github.com/Leantime/leantime/commit/9c34b99922a7cb8a1c9ec1c9123f8dcdaed75fa7): feat: improved subtask handling including HTMX events and additional properties for creation
* [ecfa46a](https://github.com/Leantime/leantime/commit/ecfa46ae9eac48030415269fb761bbccd74ebe2b): feat: create project model through constructor
* [62b136b](https://github.com/Leantime/leantime/commit/62b136b1f3d52217326f25d57b2a280a8585d445): fix: object parameter breaks jsonrpc usage
* [db42edd](https://github.com/Leantime/leantime/commit/db42edde5c8bd5205bc5cf5882ac858f3d01d9af): feat: add unique user ID to session
* [7d8d54d](https://github.com/Leantime/leantime/commit/7d8d54d264af767ceaa9d5e6e6f3a49ecb75ecd7): fix: Inconsistent datetime handling of ical events
* [b6ba0f5](https://github.com/Leantime/leantime/commit/b6ba0f5deb6fbcea4abfe8e1a97b2d9d64c68d21): fix: Welcome widget ticket counter should not count milestones as tasks left to do


# Version: 3.5.5

* [d2d20da](https://github.com/Leantime/leantime/commit/d2d20da533c9b81fc78479713509e52b1e22ef34): task: Version bump
* [4acb5c6](https://github.com/Leantime/leantime/commit/4acb5c6e6b090ce9481ed4da068b9a920a37b193): Update show.tpl.php
* [0445676](https://github.com/Leantime/leantime/commit/0445676192cbd92b090aff78b53da85b97c13006): task: Remove not needed config
* [359825a](https://github.com/Leantime/leantime/commit/359825a4addf0989298ff7cd5bd685a9941f55cc): fix: decimal issue on report screen
* [db99380](https://github.com/Leantime/leantime/commit/db993802df81d1bcc65f5c56d0e601d3be799e52): task: code style fix
* [f68be31](https://github.com/Leantime/leantime/commit/f68be3108389d3be8f216312be387b4a75eb5420): fix: automatic handling of invalid filenames
* [ba21c52](https://github.com/Leantime/leantime/commit/ba21c525b71b4d80621e82931c6723b6ec230c76): feat: Improve plugin marketplace URL handling
* [7fe069c](https://github.com/Leantime/leantime/commit/7fe069cd0bfa4953d9cb17b7b8d9504ad99c4df2): feat: Remove premium links and replace with one link to support site


# Version: 3.5.4

* [72bea52](https://github.com/Leantime/leantime/commit/72bea5211c8b91defe5edc6958463f68a5173f1e): task: version bump
* [8dd47b6](https://github.com/Leantime/leantime/commit/8dd47b6094b1e75b19f4e2648d30a8aa3926d9bc): task: adding claude.md which can be used for Claude code or other development environments
* [9ffda24](https://github.com/Leantime/leantime/commit/9ffda247fa9fd6690ca119e49804df174f1afc71): task: fix code style
* [7525056](https://github.com/Leantime/leantime/commit/75250562fbb28bfa69cef2a42e420dd52ab95241): task: add unit tests for filemanager
* [466fd76](https://github.com/Leantime/leantime/commit/466fd762e50efcbe6239984b878ffe9a6b8acc22): task: fix unit tests
* [ad07bce](https://github.com/Leantime/leantime/commit/ad07bce0823bab5553e33428f40a57fb9c6ea93a): Update Plugins
* [8180109](https://github.com/Leantime/leantime/commit/8180109c9cb7e6423da11c5e7041a687d6aae114): task: Code cleanup
* [dbe2293](https://github.com/Leantime/leantime/commit/dbe2293b6309aea7598d65539a59e5d4e248dd9b): fix: Fix broken file upload and refactor file management to use laravel file storage class
* [69b5e8e](https://github.com/Leantime/leantime/commit/69b5e8e5690db9f6c4d0147408613cadc1697f30): task: adding Junie config
* [c6aed5f](https://github.com/Leantime/leantime/commit/c6aed5f5e97c7bda009e06eb1246afa52d82248f): feat: Calendar improvements


# Version: 3.5.3

* [98cdaa0](https://github.com/Leantime/leantime/commit/98cdaa05e0824553af33bc6a7e4ab9395d5a0e84): task: version bump
* [0474f04](https://github.com/Leantime/leantime/commit/0474f041a34b9a412ff1dea98907c2448b17279b): task: fix code style
* [8da7ba2](https://github.com/Leantime/leantime/commit/8da7ba2ccbb56ab3627b1c0290d56c50ef3bc588): task: Improve db integration with Laravel
* [88d615c](https://github.com/Leantime/leantime/commit/88d615c5eb32e1675e5de1c211984c317321e405): task: fix code style
* [d91eb6a](https://github.com/Leantime/leantime/commit/d91eb6a7c90a521713068245eda98c22ef3fe128): fix: theme colors
* [6e90139](https://github.com/Leantime/leantime/commit/6e901399c3a2a403489f87f94adecac8e4244519): fix: Theme not saving reliably
* [f0e7716](https://github.com/Leantime/leantime/commit/f0e771681e6915867734f0d1a5b9b5cbd943a6e9): task: New Screenshot


# Version: 3.5.2

* [3de0011](https://github.com/Leantime/leantime/commit/3de001116ae9d79e1a0375bb6546f7f277874dba): task: fix exception format.
* [d6e3aef](https://github.com/Leantime/leantime/commit/d6e3aef83aa5f0b71b5949082553212eb5f602ee): fix: performance issue due to datetime parsing
* [15d9a0d](https://github.com/Leantime/leantime/commit/15d9a0d67920333336d14a2ef306d3e4567fae2f): fix: Moved class back to where it belongs
* [bd52903](https://github.com/Leantime/leantime/commit/bd52903a6d81f82c2c07dd896891ba99ff47a77e): Update headMenu.blade.php

feat: better submenu design
* [7a4c9a0](https://github.com/Leantime/leantime/commit/7a4c9a01b70107da379a412dba972320d3a990c0): task: version bump
* [01c25b5](https://github.com/Leantime/leantime/commit/01c25b548d00ef52c8d1c78126ff76cba432a716): task: cleanup
* [56ad95f](https://github.com/Leantime/leantime/commit/56ad95f22120c35c6add0a0dd9f0f5fd0601ffbd): fix: GetUserByEmail fails due to wrong user status #3034
* [ecb5893](https://github.com/Leantime/leantime/commit/ecb589380d12effbda79b2c037cfbe2816e2a7f7): feat: calendar CSS improvements
* [ddb45b3](https://github.com/Leantime/leantime/commit/ddb45b3311b9bfd2dd69188b65eb37cc14821d2a): feat: update default widget positions
* [f8e9b89](https://github.com/Leantime/leantime/commit/f8e9b89b42caa4c38986d7e59bc1ed92aed0721d): fix: Ensure session folder exists


# Version: 3.5.1

* [1a97372](https://github.com/Leantime/leantime/commit/1a97372dcbc91f30627ec0ad84045f2058661e36): timesheet test update
* [9c6cc20](https://github.com/Leantime/leantime/commit/9c6cc2096bcd05974f7a2354004f9d6f3535a96a): Update TimesheetCest.php
* [3ce02cf](https://github.com/Leantime/leantime/commit/3ce02cfa71ca8bf31014fddd6712081f04a67b67): Update loginInfo.blade.php
* [9b7020c](https://github.com/Leantime/leantime/commit/9b7020ce5cfa0640a761bc9caf74255a303f06cc): task: fix code styles
* [fdf0bf8](https://github.com/Leantime/leantime/commit/fdf0bf88ceeaf4d6bbd2324533ce38f977632660): fix: Improved bool management of config vars
* [946398d](https://github.com/Leantime/leantime/commit/946398d372b3d09d0df7e56d1d477080cd5f81c3): task: block list tasks
* [b60f25a](https://github.com/Leantime/leantime/commit/b60f25ae80ea94b6f14e8f041d141f51bec71f3a): version bump
* [001a097](https://github.com/Leantime/leantime/commit/001a097c34f1a9e5b4c3ce1fb893c5fefcd8a9ed): fix: logo padding
* [2463812](https://github.com/Leantime/leantime/commit/24638128e964d12bebc2289bac3fb5125a7dd8dc): Update package-lock.json
* [2cc3382](https://github.com/Leantime/leantime/commit/2cc33826a2d996f12e1af44fe10496292c51a60f): Revert core clean up changes due to plugin compatibility issues
* [7c332ac](https://github.com/Leantime/leantime/commit/7c332acb1bb14213038171352fe0e530e055fbbe): [Changelog CI] Add Changelog for Version 3.5.0
* [3e5009d](https://github.com/Leantime/leantime/commit/3e5009d9ce5174c7de2b94fa80caa604e821cf5b): Update composer.lock
* [5580212](https://github.com/Leantime/leantime/commit/558021212a3ea6314e1abd676994480be6b3b795): version bump
* [378864d](https://github.com/Leantime/leantime/commit/378864da12f1547955b80d6889a30b4c5f305498): task: additional test improvements
* [6e4ac76](https://github.com/Leantime/leantime/commit/6e4ac76ca0408c0364a5f54d7115a826e07b39d7): task: timesheet test wait update
* [31a41df](https://github.com/Leantime/leantime/commit/31a41df3d9165d4773917c80e233eb6f9ca062cf): task: unit tests different wait mechanisms
* [48e0101](https://github.com/Leantime/leantime/commit/48e0101f6eae3e7518fd81c34e8728e87cee5dc7): task: increast test timeouts
* [a0487ef](https://github.com/Leantime/leantime/commit/a0487effc520149abcd2b4a7d8532858905e9fcb): update tests
* [16af6e0](https://github.com/Leantime/leantime/commit/16af6e038740c760584f5203a0d38c1e2da97151): task: fix tests and clean up code
* [8fed5b1](https://github.com/Leantime/leantime/commit/8fed5b167b4decf5af94621a5c13410e17a0ae21): task: code cleanup
* [1483e0e](https://github.com/Leantime/leantime/commit/1483e0e9bea346dcfafbf36d180ef65a3717e4d0): task: Infrastructure cleanup
* [3ada64c](https://github.com/Leantime/leantime/commit/3ada64c009e1a134369268e50d1361b963b614b6): fix: sorting by date on timesheet list view
* [5c195d5](https://github.com/Leantime/leantime/commit/5c195d5c235ad8240d3214ce3857fd7fc59bfa28): fix: timesheet chart timezone issue
* [f87df7e](https://github.com/Leantime/leantime/commit/f87df7e6935561c75d4b5433e0d68376aebb4921): fix: move tasks to a different project not working on edit task screen
* [c7e155f](https://github.com/Leantime/leantime/commit/c7e155f1b8bcaedbd1d10593ff64d0836a45b002): task: fix code styles
* [82d1d98](https://github.com/Leantime/leantime/commit/82d1d98beaf71c619d2b6b2728b2d8f9b3184ef8): fix: first user login without project fixed.
* [76689f0](https://github.com/Leantime/leantime/commit/76689f059fbf202d471c80c980ec7f4a103bb6f6): fix: style updates for dark mode including onboarding
* [0e709a6](https://github.com/Leantime/leantime/commit/0e709a61b8fa2262e3ac87d145ade2363b701e27): task: Improved handling of env config in mailer
* [a902310](https://github.com/Leantime/leantime/commit/a902310ac5ceacdfe221ba6427079754008137e7): task: updated gridstack library
* [1438a4b](https://github.com/Leantime/leantime/commit/1438a4bd3a3d1b460a3bf0d7a91e38587788f906): task: updated gridstack library
* [9b3b4d3](https://github.com/Leantime/leantime/commit/9b3b4d379124f365e560498a334307c5fe084363): feat: Improved calendar widget layout
* [eded1fe](https://github.com/Leantime/leantime/commit/eded1febb62119367973995bb5d1ece5c3dc96b1): Update FUNDING.yml
* [0aee4c9](https://github.com/Leantime/leantime/commit/0aee4c9a039059f27d2a9c7abadc10c425163030): Update FUNDING.yml
* [13b942f](https://github.com/Leantime/leantime/commit/13b942f7e4800f5109b64373baca170ba22aef80): Update FUNDING.yml
* [aa0b1cf](https://github.com/Leantime/leantime/commit/aa0b1cf417f075ac9ad0d6fda04f1b231d963a93): task: update packages
* [9ec572d](https://github.com/Leantime/leantime/commit/9ec572d2ba69abf59c33a09a49125a2e28b330b8): fix: Trusted proxies not working
* [1a47c63](https://github.com/Leantime/leantime/commit/1a47c6319dc06aaf4fe8b532e2821c96cd7afffe): task: move docker file and generation into main repo part 1
* [a6b6767](https://github.com/Leantime/leantime/commit/a6b67671dc76094fa74d860221ac26af279d487d): task: update sentry
* [5f8cbc1](https://github.com/Leantime/leantime/commit/5f8cbc1653f524fa8070de15e8ac089ccaa90e59): feat: Add Limit and date range to ticket getAll methods
* [806df35](https://github.com/Leantime/leantime/commit/806df352eb865e44cf4e166b49ddcd939a747005): feat: Improve datetimehelper and add more standard formats.
* [ab86ba4](https://github.com/Leantime/leantime/commit/ab86ba46f51afb96e32e48477be3ccda410b52da): feat: Add milestone title to results query
* [9e0bcb8](https://github.com/Leantime/leantime/commit/9e0bcb8613313e200f3c50c140b8dfc1c00e92b8): task: code cleanup
* [a65536a](https://github.com/Leantime/leantime/commit/a65536a9dd53f55e11a59a65cd58080aea4e8ad4): feat: Improved general UX and tabs
* [758e053](https://github.com/Leantime/leantime/commit/758e053f88177904c92c2c39d1373f231182e73f): feat: Improved widget UX with content scrolling
* [a0db27a](https://github.com/Leantime/leantime/commit/a0db27aa2fbd040b2b1d8e66cbd039912391aa81): feat: Improved Calendar UX
* [ee20498](https://github.com/Leantime/leantime/commit/ee2049876e55ea6b0cdd7bc21ebeec92071c59f6): feat: Enhance datetime helper parser for api usage
* [93dbbbb](https://github.com/Leantime/leantime/commit/93dbbbb83131b718cf1da55a9680012e5eb3a6c9): task: Improve error handling with sentry/bugsink
* [a2ff8ae](https://github.com/Leantime/leantime/commit/a2ff8aea0b28d28f6bdd679dc64b899d6864856a): task: various small improvements to datetimehelper, calendar and ticket services
* [1574983](https://github.com/Leantime/leantime/commit/1574983aa7bb57608db28aa53715ff871e2a1a4e): build(deps): bump http-proxy-middleware from 2.0.6 to 2.0.9

Bumps [http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) from 2.0.6 to 2.0.9.
- [Release notes](https://github.com/chimurai/http-proxy-middleware/releases)
- [Changelog](https://github.com/chimurai/http-proxy-middleware/blob/v2.0.9/CHANGELOG.md)
- [Commits](https://github.com/chimurai/http-proxy-middleware/compare/v2.0.6...v2.0.9)

---
updated-dependencies:
- dependency-name: http-proxy-middleware
  dependency-version: 2.0.9
  dependency-type: indirect
...

Signed-off-by: dependabot[bot] <support@github.com>
* [ab4a81a](https://github.com/Leantime/leantime/commit/ab4a81a5173a085e3bb5c1f50d5ad38b4fef986a): task: fix code style
* [3358e45](https://github.com/Leantime/leantime/commit/3358e45d4e5edb9b66ebae7b98f72b487625f03d): task: remove attribute, reorganize code
* [18291a9](https://github.com/Leantime/leantime/commit/18291a9cc6d05eaf5b6b7cdc9830e9cc1aa4dc54): fix: first login 403 issue
* [24de527](https://github.com/Leantime/leantime/commit/24de527490a2e20681e465a552ae14fd2f319775): Update Plugins
* [76bf318](https://github.com/Leantime/leantime/commit/76bf3189f6a3101b6d415bfd2e4e50c9cb4b5c84): fix: type matching in ticket service
* [60c6272](https://github.com/Leantime/leantime/comm
