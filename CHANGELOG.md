# [4.42.0](https://github.com/Ombi-app/Ombi/compare/v4.41.1...v4.42.0) (2023-06-02)


### Bug Fixes

* **translations:** 🌐 New translations from Crowdin [skip ci] ([#4926](https://github.com/Ombi-app/Ombi/issues/4926)) ([151efe1](https://github.com/Ombi-app/Ombi/commit/151efe19d0012b85f317c175da5ab4802ea14e20))


### Features

* **emby:** Show watched status for TV requests ([1f37de0](https://github.com/Ombi-app/Ombi/commit/1f37de08888812b6d130d92bb664a89e89149105))



## [4.41.1](https://github.com/Ombi-app/Ombi/compare/v4.41.0...v4.41.1) (2023-05-27)



# [4.41.0](https://github.com/Ombi-app/Ombi/compare/v4.40.0...v4.41.0) (2023-05-27)


### Bug Fixes

* Fix various styling issues ([#4935](https://github.com/Ombi-app/Ombi/issues/4935)) ([90b934a](https://github.com/Ombi-app/Ombi/commit/90b934a36996c0f489096f3641350a1c0d3b7c89))


### Features

* **emby:** Show end-user external IP address to Emby when logging in as an Emby user ([#4949](https://github.com/Ombi-app/Ombi/issues/4949)) ([79cef7e](https://github.com/Ombi-app/Ombi/commit/79cef7e0f8643e36536a9ea84dd1a07c232403a9)), closes [#4947](https://github.com/Ombi-app/Ombi/issues/4947)



# [4.40.0](https://github.com/Ombi-app/Ombi/compare/v4.39.1...v4.40.0) (2023-05-18)



# [4.39.0](https://github.com/Ombi-app/Ombi/compare/v4.35.11...v4.39.0) (2023-05-17)


### Bug Fixes

* **emby:** Fix Emby played sync running a full sync during recently added sync ([#4932](https://github.com/Ombi-app/Ombi/issues/4932)) ([9424586](https://github.com/Ombi-app/Ombi/commit/9424586e9c1b622b6475aeb8ee3cf4a8f346da6e))


### Features

* Hide watched status when request is not available ([#4934](https://github.com/Ombi-app/Ombi/issues/4934)) ([82c7f1c](https://github.com/Ombi-app/Ombi/commit/82c7f1c44fd7c87d57cc2b0c34a10fcda7628f4e))



## [4.38.2](https://github.com/Ombi-app/Ombi/compare/v4.38.1...v4.38.2) (2023-05-17)



## [4.38.1](https://github.com/Ombi-app/Ombi/compare/v4.38.0...v4.38.1) (2023-05-09)


### Bug Fixes

* **API:** Allow RequestOnBehalf rights if requested from the API ([#4919](https://github.com/Ombi-app/Ombi/issues/4919)) ([bb6dedd](https://github.com/Ombi-app/Ombi/commit/bb6deddfaecb3d6c7c3c6970414444b619bb9106))
* **notificaitons:** Add the RequestedByAlias field to the Notification Message ([7e9c8be](https://github.com/Ombi-app/Ombi/commit/7e9c8bec6b02bb4e11f8db50394e493d4dd07723))



# [4.38.0](https://github.com/Ombi-app/Ombi/compare/v4.37.3...v4.38.0) (2023-05-07)


### Bug Fixes

* remove sort header ([969bc7b](https://github.com/Ombi-app/Ombi/commit/969bc7bb25ea900ab9199509b079b36843e5bd6f))


### Features

* **emby:** Show watched status for Movie requests ([9cfb10b](https://github.com/Ombi-app/Ombi/commit/9cfb10bb1ee69067a6f47bd2c8a72d4e6834350e))



## [4.37.3](https://github.com/Ombi-app/Ombi/compare/v4.37.2...v4.37.3) (2023-05-07)


### Bug Fixes

* Show the ApiAlias in the requests-list ([9ff624c](https://github.com/Ombi-app/Ombi/commit/9ff624ce4646815b239fbb8327117947f0a90e4b))



## [4.37.2](https://github.com/Ombi-app/Ombi/compare/v4.37.1...v4.37.2) (2023-05-03)


### Bug Fixes

* **jellyfin:** Fixed an issue where the sync could stop working. Removed unused properties so the deseralization no longer fails ([0e5e0ad](https://github.com/Ombi-app/Ombi/commit/0e5e0adf862701d0f672beff14ec0aa75e4b5220))



## [4.37.1](https://github.com/Ombi-app/Ombi/compare/v4.37.0...v4.37.1) (2023-05-02)


### Bug Fixes

* Cron Validation ([#4842](https://github.com/Ombi-app/Ombi/issues/4842)) ([97cc42f](https://github.com/Ombi-app/Ombi/commit/97cc42ffa8672e7d0d0996b5fbda7f7fe699da2d))
* **discover:** :children_crossing: Improved the new Genre buttons, it now includes TV results ([b087d60](https://github.com/Ombi-app/Ombi/commit/b087d606ff36565208e564f8856903f2a4098db5))
* **lidarr:** Change monitor to Existing to properly add artist [#3597](https://github.com/Ombi-app/Ombi/issues/3597) ([506f607](https://github.com/Ombi-app/Ombi/commit/506f60773bf1031d0be51ccd34289b855a04ea40)), closes [/github.com/Lidarr/Lidarr/issues/3597#issuecomment-1530804055](https://github.com//github.com/Lidarr/Lidarr/issues/3597/issues/issuecomment-1530804055)



# [4.37.0](https://github.com/Ombi-app/Ombi/compare/v4.36.1...v4.37.0) (2023-04-24)


### Features

* Search by genre ([1837419](https://github.com/Ombi-app/Ombi/commit/18374198f9f2462ba85c5781b0fcc05892728b21))



## [4.36.1](https://github.com/Ombi-app/Ombi/compare/v4.36.0...v4.36.1) (2023-04-20)


### Bug Fixes

* **healthchecks:** Removed redundant ping check ([1751305](https://github.com/Ombi-app/Ombi/commit/1751305064176d2c0135f867773ccc46b03915ec))



# [4.36.0](https://github.com/Ombi-app/Ombi/compare/v4.35.19...v4.36.0) (2023-04-20)


### Features

* **discover:** Add deny option to recently requested ([#4907](https://github.com/Ombi-app/Ombi/issues/4907)) ([78f340e](https://github.com/Ombi-app/Ombi/commit/78f340ee5f309c55690497170897533801957668))



## [4.35.19](https://github.com/Ombi-app/Ombi/compare/v4.35.18...v4.35.19) (2023-04-20)


### Bug Fixes

* **radarr:** Fixed an issue where the radarr sync would break ([de4baad](https://github.com/Ombi-app/Ombi/commit/de4baade9f87248d77106ff1a313a498870f4fb3))



## [4.35.18](https://github.com/Ombi-app/Ombi/compare/v4.35.17...v4.35.18) (2023-04-15)


### Bug Fixes

* **#4906:** :bug: Fixed an issue with power users and permissions ([80884bc](https://github.com/Ombi-app/Ombi/commit/80884bcd725c329867c278ad235cd4096cd4fe7a))



## [4.35.17](https://github.com/Ombi-app/Ombi/compare/v4.35.16...v4.35.17) (2023-04-15)


### Bug Fixes

* **discover:** Fix denied requests displayed as approved ([#4901](https://github.com/Ombi-app/Ombi/issues/4901)) ([1e87f20](https://github.com/Ombi-app/Ombi/commit/1e87f2010491b0f3fdda70d2b19d9afd94438df7))
* Fix denied movie shown as 'processing request' in details view ([#4900](https://github.com/Ombi-app/Ombi/issues/4900)) ([0069bfd](https://github.com/Ombi-app/Ombi/commit/0069bfdf54e0785bad45c832ca052f19fd4b940b))



## [4.35.16](https://github.com/Ombi-app/Ombi/compare/v4.35.15...v4.35.16) (2023-04-13)


### Bug Fixes

* Support duplicates in Emby/JF collections ([#4902](https://github.com/Ombi-app/Ombi/issues/4902)) ([141f96d](https://github.com/Ombi-app/Ombi/commit/141f96da5e45d5b3fa5f496806b102e473da6607))



## [4.35.15](https://github.com/Ombi-app/Ombi/compare/v4.35.14...v4.35.15) (2023-04-06)


### Bug Fixes

* **sonarr:** :bug: Stop the sonarr version endpoint from breaking when Sonarr is down [#4895](https://github.com/Ombi-app/Ombi/issues/4895) ([7bb8bec](https://github.com/Ombi-app/Ombi/commit/7bb8becfb140ef6012356752a71d53b5b404e482))



## [4.35.14](https://github.com/Ombi-app/Ombi/compare/v4.35.13...v4.35.14) (2023-04-06)


### Bug Fixes

* Some minor tweaks to the movie info panel ([#4883](https://github.com/Ombi-app/Ombi/issues/4883)) ([1244487](https://github.com/Ombi-app/Ombi/commit/12444871df2f7602200f73971fce962f06b4a80b))



## [4.35.13](https://github.com/Ombi-app/Ombi/compare/v4.35.12...v4.35.13) (2023-03-28)


### Bug Fixes

* **sonarr:** :bug: Added some more error handling and information around testing sonarr ([bd2c2d3](https://github.com/Ombi-app/Ombi/commit/bd2c2d3901e239393010fd582b207f1571fb4b7e)), closes [#4877](https://github.com/Ombi-app/Ombi/issues/4877)



## [4.35.12](https://github.com/Ombi-app/Ombi/compare/v4.35.10...v4.35.12) (2023-03-25)


### Bug Fixes

* **sonarr:** :bug: Improved the error handling in the sonarr settings page in the UI ([fcd78fe](https://github.com/Ombi-app/Ombi/commit/fcd78fee619d10ec7d78e8c8ec6c3ac4b0a361a1)), closes [#4877](https://github.com/Ombi-app/Ombi/issues/4877)



## [4.35.9](https://github.com/Ombi-app/Ombi/compare/v4.35.8...v4.35.9) (2023-02-24)



## [4.35.8](https://github.com/Ombi-app/Ombi/compare/v4.35.7...v4.35.8) (2023-02-17)


### Bug Fixes

* **plex-oauth:** 🐛 Fixed an issue where using OAuth you could log in as a Ombi Local user [#4835](https://github.com/Ombi-app/Ombi/issues/4835) ([4098da3](https://github.com/Ombi-app/Ombi/commit/4098da305aaea9dae9a552644268a4fed7204cfe))



## [4.35.7](https://github.com/Ombi-app/Ombi/compare/v4.35.6...v4.35.7) (2023-02-10)


### Bug Fixes

* **wizard:** :bug: Stop access to the wizard when you have already setup ombi ([#4866](https://github.com/Ombi-app/Ombi/issues/4866)) ([353de98](https://github.com/Ombi-app/Ombi/commit/353de981a462e1753288d225ec4644a44a62d2bc))



## [4.35.6](https://github.com/Ombi-app/Ombi/compare/v4.35.5...v4.35.6) (2023-01-31)


### Bug Fixes

* Fixed the issue where the login page is still present after logging in with oauth ([aca4ee3](https://github.com/Ombi-app/Ombi/commit/aca4ee37915a28200e5233be3dc711ccc4a5aee9))



## [4.35.5](https://github.com/Ombi-app/Ombi/compare/v4.35.4...v4.35.5) (2023-01-24)


### Bug Fixes

* **radarr-settings:** 🐛 Fixed a typo ([4a50a00](https://github.com/Ombi-app/Ombi/commit/4a50a00d4729d99f4359874b9af4dbc58a0c220b))



## [4.35.4](https://github.com/Ombi-app/Ombi/compare/v4.35.3...v4.35.4) (2023-01-22)


### Bug Fixes

* **discover:** :bug: Fixed the default poster not taking into account the base url in some scenarios [#4845](https://github.com/Ombi-app/Ombi/issues/4845) ([8eda250](https://github.com/Ombi-app/Ombi/commit/8eda250367953183daec03ccb5cdf9fe94275b27))
* **Hide music from navbar and request list when not enabled:** :bug: ([5123a76](https://github.com/Ombi-app/Ombi/commit/5123a76954e9f81d58c05e31afc7a29aec19cb7a))



## [4.35.3](https://github.com/Ombi-app/Ombi/compare/v4.35.2...v4.35.3) (2023-01-13)


### Bug Fixes

* **#4847:** Invalid Discord request fixed, also fixed an issue where App Only users would not show as logged in on the user management page ([#4848](https://github.com/Ombi-app/Ombi/issues/4848)) ([f229d88](https://github.com/Ombi-app/Ombi/commit/f229d88bd744bc5253b5d3db69ae5ef22d014230))



## [4.35.2](https://github.com/Ombi-app/Ombi/compare/v4.35.1...v4.35.2) (2023-01-08)


### Bug Fixes

* **database:** Just some tweaks, shouldn't notice any difference, maybe a less error in the log ([67fb992](https://github.com/Ombi-app/Ombi/commit/67fb9921c0c025025286eb6c0a9d09fd01b18465))



## [4.35.1](https://github.com/Ombi-app/Ombi/compare/v4.35.0...v4.35.1) (2023-01-06)


### Bug Fixes

* **plex-watchlist:** Index out of bounds error ([8cd556e](https://github.com/Ombi-app/Ombi/commit/8cd556e268931596b9c1d1ae0ce533bfaaf330f4))



# [4.35.0](https://github.com/Ombi-app/Ombi/compare/v4.34.1...v4.35.0) (2023-01-04)


### Features

* Add the option for header authentication to create users ([#4841](https://github.com/Ombi-app/Ombi/issues/4841)) ([e6c9ce5](https://github.com/Ombi-app/Ombi/commit/e6c9ce5ad0056608ecda8273fb8124ed292e2942))



## [4.34.1](https://github.com/Ombi-app/Ombi/compare/v4.34.0...v4.34.1) (2023-01-04)


### Bug Fixes

* **plex-watchlist:** Lookup the ID from different sources when Plex doesn't contain the metadata ([#4843](https://github.com/Ombi-app/Ombi/issues/4843)) ([a2cc23b](https://github.com/Ombi-app/Ombi/commit/a2cc23b351c4a568c44e6c855f94db9f71ad084a))



# [4.34.0](https://github.com/Ombi-app/Ombi/compare/v4.33.1...v4.34.0) (2023-01-04)


### Features

* Radarr tags ([#4815](https://github.com/Ombi-app/Ombi/issues/4815)) ([6fa5064](https://github.com/Ombi-app/Ombi/commit/6fa506491fe867cdeef9df79991ae49319d71c3d))



## [4.33.1](https://github.com/Ombi-app/Ombi/compare/v4.33.0...v4.33.1) (2022-12-22)


### Bug Fixes

* **plex:** Added the watchlist request whole show back into the settings ([10701c4](https://github.com/Ombi-app/Ombi/commit/10701c4a0b6190eebb75c5d8b18224f3d0bc8502))



# [4.33.0](https://github.com/Ombi-app/Ombi/compare/v4.32.3...v4.33.0) (2022-12-01)


### Features

* Angular 15 and Dependency upgrades ([#4818](https://github.com/Ombi-app/Ombi/issues/4818)) ([4816acf](https://github.com/Ombi-app/Ombi/commit/4816acf6f94443d23ebef6091d4cfcbca580f9ca))



## [4.32.3](https://github.com/Ombi-app/Ombi/compare/v4.32.2...v4.32.3) (2022-11-24)


### Bug Fixes

* **sonarr:** V4 actually works this time around ([f62e70f](https://github.com/Ombi-app/Ombi/commit/f62e70fc493c7971da5e4508ce10522f5df0bbf7))



## [4.32.2](https://github.com/Ombi-app/Ombi/compare/v4.32.1...v4.32.2) (2022-11-23)


### Bug Fixes

* **sonarr:** :bug: Sonarr V4 should work now ([#4810](https://github.com/Ombi-app/Ombi/issues/4810)) ([37655af](https://github.com/Ombi-app/Ombi/commit/37655aff9d3d133b42f5664bc9445d6571e966d6))



## [4.32.1](https://github.com/Ombi-app/Ombi/compare/v4.32.0...v4.32.1) (2022-11-21)


### Bug Fixes

* **plex:** :bug: Fixed the issue where you couldn't add a new server on a fresh setup after the settings page rework ([187b18d](https://github.com/Ombi-app/Ombi/commit/187b18d5c01f6a13831e4a410b5d7c349e27d847))



# [4.32.0](https://github.com/Ombi-app/Ombi/compare/v4.31.0...v4.32.0) (2022-11-18)


### Bug Fixes

* **translations:** 🌐 New translations from Crowdin [skip ci] ([#4801](https://github.com/Ombi-app/Ombi/issues/4801)) ([4692003](https://github.com/Ombi-app/Ombi/commit/46920032baed04675b2ffbe1700afdc0740a4ac4))


### Features

* **plex:** Rework the Plex Settings page ([#4805](https://github.com/Ombi-app/Ombi/issues/4805)) ([1b8c47f](https://github.com/Ombi-app/Ombi/commit/1b8c47f3163f618851d4904732cb07015e1e93ff))



# [4.31.0](https://github.com/Ombi-app/Ombi/compare/v4.30.0...v4.31.0) (2022-11-18)


### Features

* **sonarr:** Added the ability to add default tags when sending to Sonarr ([#4803](https://github.com/Ombi-app/Ombi/issues/4803)) ([ecfbb8e](https://github.com/Ombi-app/Ombi/commit/ecfbb8eda91e1a90239dcf8be847afcc2394a78e))



# [4.30.0](https://github.com/Ombi-app/Ombi/compare/v4.29.3...v4.30.0) (2022-11-17)


### Features

* **sonarr:** :sparkles: Add the username to a Sonarr tag when sent to Sonarr ([#4802](https://github.com/Ombi-app/Ombi/issues/4802)) ([1d5fabd](https://github.com/Ombi-app/Ombi/commit/1d5fabd317e3ce8f6dd31f06d15dc81277f39dbd))



## [4.29.3](https://github.com/Ombi-app/Ombi/compare/v4.29.2...v4.29.3) (2022-11-14)


### Bug Fixes

* **notifications:** Fixed the Partially TV notifications going to the admin [#4797](https://github.com/Ombi-app/Ombi/issues/4797) ([#4799](https://github.com/Ombi-app/Ombi/issues/4799)) ([bcb3e7f](https://github.com/Ombi-app/Ombi/commit/bcb3e7f00380a4c4278f59dc55febf43e6d05d47))
* Only log error messages from Microsoft ([#4787](https://github.com/Ombi-app/Ombi/issues/4787)) ([c614e0c](https://github.com/Ombi-app/Ombi/commit/c614e0ca5fe5023cbe7ced326145273cd75be85d))



## [4.29.2](https://github.com/Ombi-app/Ombi/compare/v4.29.1...v4.29.2) (2022-10-24)


### Bug Fixes

* **plex:** Fixed an issue where sometimes the availability checker would throw an exception when checking episodes ([17ba202](https://github.com/Ombi-app/Ombi/commit/17ba2020ee0950c2c0e0e03fdb7835b579da75a9))



## [4.29.1](https://github.com/Ombi-app/Ombi/compare/v4.29.0...v4.29.1) (2022-10-22)


### Bug Fixes

* Consistently reset loading flag when requesting movies on discover page. ([#4777](https://github.com/Ombi-app/Ombi/issues/4777)) ([a40ab5c](https://github.com/Ombi-app/Ombi/commit/a40ab5cddf769d4147696eca50c1610b466ab99b))
* **sonarr:** :bug: Fixed an issue where the language list didn't correctly load for power users in the advanced options [#4782](https://github.com/Ombi-app/Ombi/issues/4782) ([2173670](https://github.com/Ombi-app/Ombi/commit/217367047d1568070dd507e54ad3fd2c68f05b88))



# [4.29.0](https://github.com/Ombi-app/Ombi/compare/v4.28.1...v4.29.0) (2022-10-19)


### Bug Fixes

* Partially Available prevents further TV requests ([#4768](https://github.com/Ombi-app/Ombi/issues/4768)) ([#4779](https://github.com/Ombi-app/Ombi/issues/4779)) ([031e2b9](https://github.com/Ombi-app/Ombi/commit/031e2b9283b239827cabaca4e35f69f2f93a4d7b))
* Unable to Delete Jellyfin Server ([#4705](https://github.com/Ombi-app/Ombi/issues/4705)) ([#4780](https://github.com/Ombi-app/Ombi/issues/4780)) ([76a0d0d](https://github.com/Ombi-app/Ombi/commit/76a0d0d26893bd480fea4735f77522ac6261a425))


### Features

* Provide a flag for missing users on Plex Server ([#4688](https://github.com/Ombi-app/Ombi/issues/4688)) ([#4778](https://github.com/Ombi-app/Ombi/issues/4778)) ([b4a14c2](https://github.com/Ombi-app/Ombi/commit/b4a14c2d28218409390e517b226130e3e84efee1))



## [4.28.1](https://github.com/Ombi-app/Ombi/compare/v4.28.0...v4.28.1) (2022-10-19)


### Bug Fixes

* **plex:** :bug: Fixed not being able to enable watchlist requests in the Plex settings ([3e5158e](https://github.com/Ombi-app/Ombi/commit/3e5158ef9cda58ea2dd3be143f07aa5433691d79))
* Reworked the version check ([#4719](https://github.com/Ombi-app/Ombi/issues/4719)) ([#4781](https://github.com/Ombi-app/Ombi/issues/4781)) ([55855c5](https://github.com/Ombi-app/Ombi/commit/55855c5adda3cd1c51b7fbd0c19b469fc813f98e))



# [4.28.0](https://github.com/Ombi-app/Ombi/compare/v4.27.8...v4.28.0) (2022-10-07)


### Features

* **plex:** ✨ Added the ability to configure the watchlist to request the whole TV show rather than latest season ([#4774](https://github.com/Ombi-app/Ombi/issues/4774)) ([fa65712](https://github.com/Ombi-app/Ombi/commit/fa65712bd570fe8d5d21b8ca0abe182b84960017))



## [4.27.8](https://github.com/Ombi-app/Ombi/compare/v4.27.7...v4.27.8) (2022-10-07)



## [4.27.7](https://github.com/Ombi-app/Ombi/compare/v4.27.6...v4.27.7) (2022-10-07)


### Bug Fixes

* Fixes default image for recently requested items. ([#4767](https://github.com/Ombi-app/Ombi/issues/4767)) ([2e6f35f](https://github.com/Ombi-app/Ombi/commit/2e6f35f89abb3dd3685ec8289f8620c7ef7072cd))



## [4.27.6](https://github.com/Ombi-app/Ombi/compare/v4.27.5...v4.27.6) (2022-10-01)


### Bug Fixes

* **notifications:** Fixed the error when sending multiple test notifications. Added more logging when Discord complains the message is invalid ([fc14780](https://github.com/Ombi-app/Ombi/commit/fc14780bd354483119ddcbb55a8c382e1890a783))



## [4.27.5](https://github.com/Ombi-app/Ombi/compare/v4.27.4...v4.27.5) (2022-09-30)


### Bug Fixes

* **importer:** 🐛 Allow you to only import Plex Admins without the Plex Users ([8c9ad9b](https://github.com/Ombi-app/Ombi/commit/8c9ad9b414fdc6c88bdb911d6057ae5d38783b98))



## [4.27.4](https://github.com/Ombi-app/Ombi/compare/v4.27.3...v4.27.4) (2022-09-30)



## [4.27.3](https://github.com/Ombi-app/Ombi/compare/v4.27.2...v4.27.3) (2022-09-30)


### Bug Fixes

* **availability:** 🐛 Fixed a issue with the availability checker after the previous update. Added full test coverage around that area ([28e2480](https://github.com/Ombi-app/Ombi/commit/28e248046ad56390595f84172bbd5f5961325b4d))



## [4.27.2](https://github.com/Ombi-app/Ombi/compare/v4.27.1...v4.27.2) (2022-09-29)


### Bug Fixes

* **sonarr:** :bug: Cleaned up and removed Sonarr v3 option, sonarr v3 is now the default. This allows us to get ready for the upcoming Sonarr v4 ([#4764](https://github.com/Ombi-app/Ombi/issues/4764)) ([2cddec7](https://github.com/Ombi-app/Ombi/commit/2cddec759004b6490f686ff74cb092238e3dc946))



## [4.27.1](https://github.com/Ombi-app/Ombi/compare/v4.27.0...v4.27.1) (2022-09-20)


### Bug Fixes

* **plex:** stop the plex sync from deleting episodes when we can't find the plex key ([66b05e5](https://github.com/Ombi-app/Ombi/commit/66b05e5a85dbfe1fec5f9366e80987f2cfa1f4fe))



# [4.27.0](https://github.com/Ombi-app/Ombi/compare/v4.26.0...v4.27.0) (2022-09-14)


### Features

* Recently requested improvements ([#4755](https://github.com/Ombi-app/Ombi/issues/4755)) ([ff04d87](https://github.com/Ombi-app/Ombi/commit/ff04d875343604c77c391bf55d0968977e480281))



# [4.26.0](https://github.com/Ombi-app/Ombi/compare/v4.25.1...v4.26.0) (2022-09-07)


### Features

* **notifications:** Add more curly variables for partially available notification ([66aa101](https://github.com/Ombi-app/Ombi/commit/66aa101019c4c4b34e186db9d303049d02b9c781))



## [4.25.1](https://github.com/Ombi-app/Ombi/compare/v4.25.0...v4.25.1) (2022-09-07)


### Bug Fixes

* **webhook:** Remove added trailing slash from webhook URL [#4710](https://github.com/Ombi-app/Ombi/issues/4710) ([369eb33](https://github.com/Ombi-app/Ombi/commit/369eb339171671101be219486e2aab27a20f3d74))



# [4.25.0](https://github.com/Ombi-app/Ombi/compare/v4.24.0...v4.25.0) (2022-08-23)


### Bug Fixes

* fixed stats controller ([#4742](https://github.com/Ombi-app/Ombi/issues/4742)) ([47ea64b](https://github.com/Ombi-app/Ombi/commit/47ea64b5a401770f1943b575ca40f84d515e96b3))


### Features

* Watchlist history errors([#4741](https://github.com/Ombi-app/Ombi/issues/4741)) ([c222f1a](https://github.com/Ombi-app/Ombi/commit/c222f1a945e944ef34e68cad2b61f40e57cab823))



# [4.24.0](https://github.com/Ombi-app/Ombi/compare/v4.23.2...v4.24.0) (2022-08-22)


### Features

* add crew on movie page ([#4722](https://github.com/Ombi-app/Ombi/issues/4722)) ([1d53261](https://github.com/Ombi-app/Ombi/commit/1d532613823804b25984bd1d223d081a54ad143d))



## [4.23.2](https://github.com/Ombi-app/Ombi/compare/v4.23.1...v4.23.2) (2022-08-22)


### Bug Fixes

* Fix conflicting property name for Swagger ([#4733](https://github.com/Ombi-app/Ombi/issues/4733)) ([d661f32](https://github.com/Ombi-app/Ombi/commit/d661f32e8a9e105faab6380b4b7b642896b98163))



## [4.23.1](https://github.com/Ombi-app/Ombi/compare/v4.23.0...v4.23.1) (2022-08-12)


### Bug Fixes

* Localize recently requested on discover page ([#4729](https://github.com/Ombi-app/Ombi/issues/4729)) ([bf65c76](https://github.com/Ombi-app/Ombi/commit/bf65c76ff9ce38f65a9e5feb872734e8d8e35eb6))



# [4.23.0](https://github.com/Ombi-app/Ombi/compare/v4.22.5...v4.23.0) (2022-08-09)


### Bug Fixes

* Log Microsoft warnings to log file ([#4723](https://github.com/Ombi-app/Ombi/issues/4723)) ([26ac75f](https://github.com/Ombi-app/Ombi/commit/26ac75f0c223c2a91e3471797ae46ede3fde89cc))


### Features

* ✨ Recently Requested on Discover Page ([#4387](https://github.com/Ombi-app/Ombi/issues/4387)) ([44d38fb](https://github.com/Ombi-app/Ombi/commit/44d38fbaae521dbb467b61c7471b2384015ac52e))



## [4.22.4](https://github.com/Ombi-app/Ombi/compare/v4.22.3...v4.22.4) (2022-08-04)


### Bug Fixes

* :bug: Fixed missing externals ([#4712](https://github.com/Ombi-app/Ombi/issues/4712)) ([fcc1eaa](https://github.com/Ombi-app/Ombi/commit/fcc1eaaa377683dcdc81d62a2a688fb0c4490c7b))
* fixed trakt image not loading when base url present ([#4711](https://github.com/Ombi-app/Ombi/issues/4711)) ([f102dcf](https://github.com/Ombi-app/Ombi/commit/f102dcf751c2eb62ebfe30f9f8e4b2ad863c3b0d))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([#4713](https://github.com/Ombi-app/Ombi/issues/4713)) ([ff142b0](https://github.com/Ombi-app/Ombi/commit/ff142b09abbb2f9540387284222552e6e12639fe))



## [4.22.3](https://github.com/Ombi-app/Ombi/compare/v4.22.2...v4.22.3) (2022-07-28)


### Bug Fixes

* Override Sonarr V3 Profiles endpoint ([#4678](https://github.com/Ombi-app/Ombi/issues/4678)) ([875da95](https://github.com/Ombi-app/Ombi/commit/875da959f353119b05138d68ee6d32a49e14b91e))



## [4.22.2](https://github.com/Ombi-app/Ombi/compare/v4.22.1...v4.22.2) (2022-07-25)


### Bug Fixes

* fixed an issue where I broke images for some users ([81ddc85](https://github.com/Ombi-app/Ombi/commit/81ddc8553b9094c3f6843b036daebb2eb9262e00))



## [4.22.1](https://github.com/Ombi-app/Ombi/compare/v4.22.0...v4.22.1) (2022-07-25)


### Bug Fixes

* **discover:** :bug: Created new Image component to handle 429's from TMDB ([#4698](https://github.com/Ombi-app/Ombi/issues/4698)) and fixed [#4635](https://github.com/Ombi-app/Ombi/issues/4635) ([#4699](https://github.com/Ombi-app/Ombi/issues/4699)) ([f22d3da](https://github.com/Ombi-app/Ombi/commit/f22d3da765799365455b919027f7563e52b347c3))



# [4.22.0](https://github.com/Ombi-app/Ombi/compare/v4.21.2...v4.22.0) (2022-07-22)


### Features

* **discover:** ✨ Added infinite scroll on advanced search results ([898bc89](https://github.com/Ombi-app/Ombi/commit/898bc89fa78245c1f3de9481f6c724f087a16e39))



## [4.21.2](https://github.com/Ombi-app/Ombi/compare/v4.21.1...v4.21.2) (2022-07-22)


### Bug Fixes

* Landing and Login page improvements ([#4690](https://github.com/Ombi-app/Ombi/issues/4690)) ([6d423b5](https://github.com/Ombi-app/Ombi/commit/6d423b5447c52c5e59d8d2bd92a23b47468eb736))



## [4.21.1](https://github.com/Ombi-app/Ombi/compare/v4.21.0...v4.21.1) (2022-07-11)


### Bug Fixes

* **images:** Retry images with a backoff when we get a Too Many requests from TheMovieDb [#4685](https://github.com/Ombi-app/Ombi/issues/4685) ([3f1f35d](https://github.com/Ombi-app/Ombi/commit/3f1f35df3164db6739691cdda8f925c296239791))



# [4.21.0](https://github.com/Ombi-app/Ombi/compare/v4.20.4...v4.21.0) (2022-06-22)


### Features

* Upgrade to Angular14 ([#4668](https://github.com/Ombi-app/Ombi/issues/4668)) ([b9d55a4](https://github.com/Ombi-app/Ombi/commit/b9d55a469b412558cbf67c1e25db7fdda5964cd8))


### Performance Improvements

* stop populating obsolete subscribe fields ([#4625](https://github.com/Ombi-app/Ombi/issues/4625)) ([9a73463](https://github.com/Ombi-app/Ombi/commit/9a734637665f671b17c2bb440d93b35a891c142b))



## [4.20.4](https://github.com/Ombi-app/Ombi/compare/v4.20.3...v4.20.4) (2022-06-15)


### Bug Fixes

* fixed build ([f877921](https://github.com/Ombi-app/Ombi/commit/f8779219146051ea74f8b6408658ff7975afb88b))



## [4.20.3](https://github.com/Ombi-app/Ombi/compare/v4.20.2...v4.20.3) (2022-06-05)


### Bug Fixes

* **plex:** 🐛 Fixed an issue with the Plex Sync ([ab1a11a](https://github.com/Ombi-app/Ombi/commit/ab1a11af78efbe9d37bd55aa80a640796c138a98))



## [4.20.2](https://github.com/Ombi-app/Ombi/compare/v4.20.1...v4.20.2) (2022-06-03)


### Bug Fixes

* :bug: Fixed the Request on Behalf of having blanks ([#4667](https://github.com/Ombi-app/Ombi/issues/4667)) ([7dd9b1c](https://github.com/Ombi-app/Ombi/commit/7dd9b1cac07f571dd35b362544e4fe0226c4b817))



## [4.20.1](https://github.com/Ombi-app/Ombi/compare/v4.20.0...v4.20.1) (2022-05-27)


### Bug Fixes

* added media type tag to media type text ([#4638](https://github.com/Ombi-app/Ombi/issues/4638)) ([fe501d3](https://github.com/Ombi-app/Ombi/commit/fe501d34a0c36ac9f000b107eca49dbc6694d006))
* **API:** Fix pagination in some edge cases ([#4649](https://github.com/Ombi-app/Ombi/issues/4649)) ([a70bf8f](https://github.com/Ombi-app/Ombi/commit/a70bf8f46c76d74c9dfdf908c53bd9955ca0a35d))
* **discover:** Carousel touch not working when scrolling page and recommendations and similar movie navigation ([#4633](https://github.com/Ombi-app/Ombi/issues/4633)) ([d5ef1d5](https://github.com/Ombi-app/Ombi/commit/d5ef1d53e5f77d19dba8b8059c80b538a3e14f2a))
* Improve Swagger documentation ([#4652](https://github.com/Ombi-app/Ombi/issues/4652)) ([181892b](https://github.com/Ombi-app/Ombi/commit/181892bcfe88e6d76febf49ef57745d04552d08e))
* Missing Poster broken link fix ([#4637](https://github.com/Ombi-app/Ombi/issues/4637)) ([4070f0d](https://github.com/Ombi-app/Ombi/commit/4070f0d093b1c92487a1c80cabad8283a9650f51))
* **sickrage:** Fixed issue with incorrect handling of SiCKRAGE episode results returned during episode status changes, now expects array of objects from data path if present ([#4648](https://github.com/Ombi-app/Ombi/issues/4648)) ([6d16442](https://github.com/Ombi-app/Ombi/commit/6d16442d4d714920367df065a3ced42b729f4233))
* **sync:** Emby+Jellyfin - sync multi-episode files of 3+ episodes ([bd8fd89](https://github.com/Ombi-app/Ombi/commit/bd8fd890554c9d85d6da4d2cee813e82ce698e52))



# [4.20.0](https://github.com/Ombi-app/Ombi/compare/v4.19.1...v4.20.0) (2022-04-28)


### Features

* **discover:** Show more relevant shows in upcoming TV ([8357819](https://github.com/Ombi-app/Ombi/commit/8357819b53b8c675c0b246d7006b5a778bdba33f))



## [4.19.1](https://github.com/Ombi-app/Ombi/compare/v4.19.0...v4.19.1) (2022-04-27)



# [4.19.0](https://github.com/Ombi-app/Ombi/compare/v4.18.0...v4.19.0) (2022-04-27)


### Features

* **sync:** Detect reidentified movies in Emby and Jellyfin ([5938077](https://github.com/Ombi-app/Ombi/commit/5938077d82a5357f79c07b218b3986557a5816e8))
* **sync:** Detect reidentified series in Emby and Jellyfin ([9096e91](https://github.com/Ombi-app/Ombi/commit/9096e91d55d268819bce22831f8a8b27f2a1776b))



# [4.18.0](https://github.com/Ombi-app/Ombi/compare/v4.17.0...v4.18.0) (2022-04-26)


### Bug Fixes

* **discover:** Fix cache mix up ([03d9422](https://github.com/Ombi-app/Ombi/commit/03d94220c7eaafb50c6c80a6ed1150794b873ac3))
* **discover:** Fix new trending feature detection ([6794b88](https://github.com/Ombi-app/Ombi/commit/6794b887f6544fb41528bdd9728b7824b65e47ee))
* **settings:** Allow toggling features when there are more than one ([a373359](https://github.com/Ombi-app/Ombi/commit/a373359ae8e6bad42b558a6e01a8ff2840d3bbaa))


### Features

* **discover:** Add new trending source experimental feature ([1a0823c](https://github.com/Ombi-app/Ombi/commit/1a0823ca80559417c67323aaeaa1ef5243e98031))
* **discover:** Default trending source to new logic ([4f12939](https://github.com/Ombi-app/Ombi/commit/4f12939e22020a67a5ee75e2907923faea136e8d))



# [4.17.0](https://github.com/Ombi-app/Ombi/compare/v4.16.17...v4.17.0) (2022-04-25)



## [4.16.17](https://github.com/Ombi-app/Ombi/compare/v4.16.16...v4.16.17) (2022-04-25)



## [4.16.16](https://github.com/Ombi-app/Ombi/compare/v4.16.15...v4.16.16) (2022-04-25)


### Bug Fixes

* **4616:** :bug: fixed mandatory fields ([d8f2260](https://github.com/Ombi-app/Ombi/commit/d8f2260c7ae3ed48386743b7adbd06e284487034))



## [4.16.15](https://github.com/Ombi-app/Ombi/compare/v4.16.14...v4.16.15) (2022-04-24)


### Features

* **discover:** Add original language filter ([ef7ec86](https://github.com/Ombi-app/Ombi/commit/ef7ec861d8aede2a4817752c990617f583805391))



## [4.16.14](https://github.com/Ombi-app/Ombi/compare/v4.16.13...v4.16.14) (2022-04-19)



## [4.16.13](https://github.com/Ombi-app/Ombi/compare/v4.16.12...v4.16.13) (2022-04-19)



## [4.39.1](https://github.com/Ombi-app/Ombi/compare/v4.39.0...v4.39.1) (2023-05-18)



## [4.35.11](https://github.com/Ombi-app/Ombi/compare/v4.38.2...v4.35.11) (2023-05-17)



## [4.35.10](https://github.com/Ombi-app/Ombi/compare/v4.35.9...v4.35.10) (2023-02-25)



# [4.39.0](https://github.com/Ombi-app/Ombi/compare/v4.35.11...v4.39.0) (2023-05-17)


### Bug Fixes

* **emby:** Fix Emby played sync running a full sync during recently added sync ([#4932](https://github.com/Ombi-app/Ombi/issues/4932)) ([9424586](https://github.com/Ombi-app/Ombi/commit/9424586e9c1b622b6475aeb8ee3cf4a8f346da6e))


### Features

* Hide watched status when request is not available ([#4934](https://github.com/Ombi-app/Ombi/issues/4934)) ([82c7f1c](https://github.com/Ombi-app/Ombi/commit/82c7f1c44fd7c87d57cc2b0c34a10fcda7628f4e))



## [4.38.2](https://github.com/Ombi-app/Ombi/compare/v4.38.1...v4.38.2) (2023-05-17)



## [4.38.1](https://github.com/Ombi-app/Ombi/compare/v4.38.0...v4.38.1) (2023-05-09)


### Bug Fixes

* **API:** Allow RequestOnBehalf rights if requested from the API ([#4919](https://github.com/Ombi-app/Ombi/issues/4919)) ([bb6dedd](https://github.com/Ombi-app/Ombi/commit/bb6deddfaecb3d6c7c3c6970414444b619bb9106))
* **notificaitons:** Add the RequestedByAlias field to the Notification Message ([7e9c8be](https://github.com/Ombi-app/Ombi/commit/7e9c8bec6b02bb4e11f8db50394e493d4dd07723))



# [4.38.0](https://github.com/Ombi-app/Ombi/compare/v4.37.3...v4.38.0) (2023-05-07)


### Bug Fixes

* remove sort header ([969bc7b](https://github.com/Ombi-app/Ombi/commit/969bc7bb25ea900ab9199509b079b36843e5bd6f))


### Features

* **emby:** Show watched status for Movie requests ([9cfb10b](https://github.com/Ombi-app/Ombi/commit/9cfb10bb1ee69067a6f47bd2c8a72d4e6834350e))



## [4.37.3](https://github.com/Ombi-app/Ombi/compare/v4.37.2...v4.37.3) (2023-05-07)


### Bug Fixes

* Show the ApiAlias in the requests-list ([9ff624c](https://github.com/Ombi-app/Ombi/commit/9ff624ce4646815b239fbb8327117947f0a90e4b))



## [4.37.2](https://github.com/Ombi-app/Ombi/compare/v4.37.1...v4.37.2) (2023-05-03)


### Bug Fixes

* **jellyfin:** Fixed an issue where the sync could stop working. Removed unused properties so the deseralization no longer fails ([0e5e0ad](https://github.com/Ombi-app/Ombi/commit/0e5e0adf862701d0f672beff14ec0aa75e4b5220))



## [4.37.1](https://github.com/Ombi-app/Ombi/compare/v4.37.0...v4.37.1) (2023-05-02)


### Bug Fixes

* Cron Validation ([#4842](https://github.com/Ombi-app/Ombi/issues/4842)) ([97cc42f](https://github.com/Ombi-app/Ombi/commit/97cc42ffa8672e7d0d0996b5fbda7f7fe699da2d))
* **discover:** :children_crossing: Improved the new Genre buttons, it now includes TV results ([b087d60](https://github.com/Ombi-app/Ombi/commit/b087d606ff36565208e564f8856903f2a4098db5))
* **lidarr:** Change monitor to Existing to properly add artist [#3597](https://github.com/Ombi-app/Ombi/issues/3597) ([506f607](https://github.com/Ombi-app/Ombi/commit/506f60773bf1031d0be51ccd34289b855a04ea40)), closes [/github.com/Lidarr/Lidarr/issues/3597#issuecomment-1530804055](https://github.com//github.com/Lidarr/Lidarr/issues/3597/issues/issuecomment-1530804055)



# [4.37.0](https://github.com/Ombi-app/Ombi/compare/v4.36.1...v4.37.0) (2023-04-24)


### Features

* Search by genre ([1837419](https://github.com/Ombi-app/Ombi/commit/18374198f9f2462ba85c5781b0fcc05892728b21))



## [4.36.1](https://github.com/Ombi-app/Ombi/compare/v4.36.0...v4.36.1) (2023-04-20)


### Bug Fixes

* **healthchecks:** Removed redundant ping check ([1751305](https://github.com/Ombi-app/Ombi/commit/1751305064176d2c0135f867773ccc46b03915ec))



# [4.36.0](https://github.com/Ombi-app/Ombi/compare/v4.35.19...v4.36.0) (2023-04-20)


### Features

* **discover:** Add deny option to recently requested ([#4907](https://github.com/Ombi-app/Ombi/issues/4907)) ([78f340e](https://github.com/Ombi-app/Ombi/commit/78f340ee5f309c55690497170897533801957668))



## [4.35.19](https://github.com/Ombi-app/Ombi/compare/v4.35.18...v4.35.19) (2023-04-20)


### Bug Fixes

* **radarr:** Fixed an issue where the radarr sync would break ([de4baad](https://github.com/Ombi-app/Ombi/commit/de4baade9f87248d77106ff1a313a498870f4fb3))



## [4.35.18](https://github.com/Ombi-app/Ombi/compare/v4.35.17...v4.35.18) (2023-04-15)


### Bug Fixes

* **#4906:** :bug: Fixed an issue with power users and permissions ([80884bc](https://github.com/Ombi-app/Ombi/commit/80884bcd725c329867c278ad235cd4096cd4fe7a))



## [4.35.17](https://github.com/Ombi-app/Ombi/compare/v4.35.16...v4.35.17) (2023-04-15)


### Bug Fixes

* **discover:** Fix denied requests displayed as approved ([#4901](https://github.com/Ombi-app/Ombi/issues/4901)) ([1e87f20](https://github.com/Ombi-app/Ombi/commit/1e87f2010491b0f3fdda70d2b19d9afd94438df7))
* Fix denied movie shown as 'processing request' in details view ([#4900](https://github.com/Ombi-app/Ombi/issues/4900)) ([0069bfd](https://github.com/Ombi-app/Ombi/commit/0069bfdf54e0785bad45c832ca052f19fd4b940b))



## [4.35.16](https://github.com/Ombi-app/Ombi/compare/v4.35.15...v4.35.16) (2023-04-13)


### Bug Fixes

* Support duplicates in Emby/JF collections ([#4902](https://github.com/Ombi-app/Ombi/issues/4902)) ([141f96d](https://github.com/Ombi-app/Ombi/commit/141f96da5e45d5b3fa5f496806b102e473da6607))



## [4.35.15](https://github.com/Ombi-app/Ombi/compare/v4.35.14...v4.35.15) (2023-04-06)


### Bug Fixes

* **sonarr:** :bug: Stop the sonarr version endpoint from breaking when Sonarr is down [#4895](https://github.com/Ombi-app/Ombi/issues/4895) ([7bb8bec](https://github.com/Ombi-app/Ombi/commit/7bb8becfb140ef6012356752a71d53b5b404e482))



## [4.35.14](https://github.com/Ombi-app/Ombi/compare/v4.35.13...v4.35.14) (2023-04-06)


### Bug Fixes

* Some minor tweaks to the movie info panel ([#4883](https://github.com/Ombi-app/Ombi/issues/4883)) ([1244487](https://github.com/Ombi-app/Ombi/commit/12444871df2f7602200f73971fce962f06b4a80b))



## [4.35.13](https://github.com/Ombi-app/Ombi/compare/v4.35.12...v4.35.13) (2023-03-28)


### Bug Fixes

* **sonarr:** :bug: Added some more error handling and information around testing sonarr ([bd2c2d3](https://github.com/Ombi-app/Ombi/commit/bd2c2d3901e239393010fd582b207f1571fb4b7e)), closes [#4877](https://github.com/Ombi-app/Ombi/issues/4877)



## [4.35.12](https://github.com/Ombi-app/Ombi/compare/v4.35.10...v4.35.12) (2023-03-25)


### Bug Fixes

* **sonarr:** :bug: Improved the error handling in the sonarr settings page in the UI ([fcd78fe](https://github.com/Ombi-app/Ombi/commit/fcd78fee619d10ec7d78e8c8ec6c3ac4b0a361a1)), closes [#4877](https://github.com/Ombi-app/Ombi/issues/4877)



## [4.35.9](https://github.com/Ombi-app/Ombi/compare/v4.35.8...v4.35.9) (2023-02-24)



## [4.35.8](https://github.com/Ombi-app/Ombi/compare/v4.35.7...v4.35.8) (2023-02-17)


### Bug Fixes

* **plex-oauth:** 🐛 Fixed an issue where using OAuth you could log in as a Ombi Local user [#4835](https://github.com/Ombi-app/Ombi/issues/4835) ([4098da3](https://github.com/Ombi-app/Ombi/commit/4098da305aaea9dae9a552644268a4fed7204cfe))



## [4.35.7](https://github.com/Ombi-app/Ombi/compare/v4.35.6...v4.35.7) (2023-02-10)


### Bug Fixes

* **wizard:** :bug: Stop access to the wizard when you have already setup ombi ([#4866](https://github.com/Ombi-app/Ombi/issues/4866)) ([353de98](https://github.com/Ombi-app/Ombi/commit/353de981a462e1753288d225ec4644a44a62d2bc))



## [4.35.6](https://github.com/Ombi-app/Ombi/compare/v4.35.5...v4.35.6) (2023-01-31)


### Bug Fixes

* Fixed the issue where the login page is still present after logging in with oauth ([aca4ee3](https://github.com/Ombi-app/Ombi/commit/aca4ee37915a28200e5233be3dc711ccc4a5aee9))



## [4.35.5](https://github.com/Ombi-app/Ombi/compare/v4.35.4...v4.35.5) (2023-01-24)


### Bug Fixes

* **radarr-settings:** 🐛 Fixed a typo ([4a50a00](https://github.com/Ombi-app/Ombi/commit/4a50a00d4729d99f4359874b9af4dbc58a0c220b))



## [4.35.4](https://github.com/Ombi-app/Ombi/compare/v4.35.3...v4.35.4) (2023-01-22)


### Bug Fixes

* **discover:** :bug: Fixed the default poster not taking into account the base url in some scenarios [#4845](https://github.com/Ombi-app/Ombi/issues/4845) ([8eda250](https://github.com/Ombi-app/Ombi/commit/8eda250367953183daec03ccb5cdf9fe94275b27))
* **Hide music from navbar and request list when not enabled:** :bug: ([5123a76](https://github.com/Ombi-app/Ombi/commit/5123a76954e9f81d58c05e31afc7a29aec19cb7a))



## [4.35.3](https://github.com/Ombi-app/Ombi/compare/v4.35.2...v4.35.3) (2023-01-13)


### Bug Fixes

* **#4847:** Invalid Discord request fixed, also fixed an issue where App Only users would not show as logged in on the user management page ([#4848](https://github.com/Ombi-app/Ombi/issues/4848)) ([f229d88](https://github.com/Ombi-app/Ombi/commit/f229d88bd744bc5253b5d3db69ae5ef22d014230))



## [4.35.2](https://github.com/Ombi-app/Ombi/compare/v4.35.1...v4.35.2) (2023-01-08)


### Bug Fixes

* **database:** Just some tweaks, shouldn't notice any difference, maybe a less error in the log ([67fb992](https://github.com/Ombi-app/Ombi/commit/67fb9921c0c025025286eb6c0a9d09fd01b18465))



## [4.35.1](https://github.com/Ombi-app/Ombi/compare/v4.35.0...v4.35.1) (2023-01-06)


### Bug Fixes

* **plex-watchlist:** Index out of bounds error ([8cd556e](https://github.com/Ombi-app/Ombi/commit/8cd556e268931596b9c1d1ae0ce533bfaaf330f4))



# [4.35.0](https://github.com/Ombi-app/Ombi/compare/v4.34.1...v4.35.0) (2023-01-04)


### Features

* Add the option for header authentication to create users ([#4841](https://github.com/Ombi-app/Ombi/issues/4841)) ([e6c9ce5](https://github.com/Ombi-app/Ombi/commit/e6c9ce5ad0056608ecda8273fb8124ed292e2942))



## [4.34.1](https://github.com/Ombi-app/Ombi/compare/v4.34.0...v4.34.1) (2023-01-04)


### Bug Fixes

* **plex-watchlist:** Lookup the ID from different sources when Plex doesn't contain the metadata ([#4843](https://github.com/Ombi-app/Ombi/issues/4843)) ([a2cc23b](https://github.com/Ombi-app/Ombi/commit/a2cc23b351c4a568c44e6c855f94db9f71ad084a))



# [4.34.0](https://github.com/Ombi-app/Ombi/compare/v4.33.1...v4.34.0) (2023-01-04)


### Features

* Radarr tags ([#4815](https://github.com/Ombi-app/Ombi/issues/4815)) ([6fa5064](https://github.com/Ombi-app/Ombi/commit/6fa506491fe867cdeef9df79991ae49319d71c3d))



## [4.33.1](https://github.com/Ombi-app/Ombi/compare/v4.33.0...v4.33.1) (2022-12-22)


### Bug Fixes

* **plex:** Added the watchlist request whole show back into the settings ([10701c4](https://github.com/Ombi-app/Ombi/commit/10701c4a0b6190eebb75c5d8b18224f3d0bc8502))



# [4.33.0](https://github.com/Ombi-app/Ombi/compare/v4.32.3...v4.33.0) (2022-12-01)


### Features

* Angular 15 and Dependency upgrades ([#4818](https://github.com/Ombi-app/Ombi/issues/4818)) ([4816acf](https://github.com/Ombi-app/Ombi/commit/4816acf6f94443d23ebef6091d4cfcbca580f9ca))



## [4.32.3](https://github.com/Ombi-app/Ombi/compare/v4.32.2...v4.32.3) (2022-11-24)


### Bug Fixes

* **sonarr:** V4 actually works this time around ([f62e70f](https://github.com/Ombi-app/Ombi/commit/f62e70fc493c7971da5e4508ce10522f5df0bbf7))



## [4.32.2](https://github.com/Ombi-app/Ombi/compare/v4.32.1...v4.32.2) (2022-11-23)


### Bug Fixes

* **sonarr:** :bug: Sonarr V4 should work now ([#4810](https://github.com/Ombi-app/Ombi/issues/4810)) ([37655af](https://github.com/Ombi-app/Ombi/commit/37655aff9d3d133b42f5664bc9445d6571e966d6))



## [4.32.1](https://github.com/Ombi-app/Ombi/compare/v4.32.0...v4.32.1) (2022-11-21)


### Bug Fixes

* **plex:** :bug: Fixed the issue where you couldn't add a new server on a fresh setup after the settings page rework ([187b18d](https://github.com/Ombi-app/Ombi/commit/187b18d5c01f6a13831e4a410b5d7c349e27d847))



# [4.32.0](https://github.com/Ombi-app/Ombi/compare/v4.31.0...v4.32.0) (2022-11-18)


### Bug Fixes

* **translations:** 🌐 New translations from Crowdin [skip ci] ([#4801](https://github.com/Ombi-app/Ombi/issues/4801)) ([4692003](https://github.com/Ombi-app/Ombi/commit/46920032baed04675b2ffbe1700afdc0740a4ac4))


### Features

* **plex:** Rework the Plex Settings page ([#4805](https://github.com/Ombi-app/Ombi/issues/4805)) ([1b8c47f](https://github.com/Ombi-app/Ombi/commit/1b8c47f3163f618851d4904732cb07015e1e93ff))



# [4.31.0](https://github.com/Ombi-app/Ombi/compare/v4.30.0...v4.31.0) (2022-11-18)


### Features

* **sonarr:** Added the ability to add default tags when sending to Sonarr ([#4803](https://github.com/Ombi-app/Ombi/issues/4803)) ([ecfbb8e](https://github.com/Ombi-app/Ombi/commit/ecfbb8eda91e1a90239dcf8be847afcc2394a78e))



# [4.30.0](https://github.com/Ombi-app/Ombi/compare/v4.29.3...v4.30.0) (2022-11-17)


### Features

* **sonarr:** :sparkles: Add the username to a Sonarr tag when sent to Sonarr ([#4802](https://github.com/Ombi-app/Ombi/issues/4802)) ([1d5fabd](https://github.com/Ombi-app/Ombi/commit/1d5fabd317e3ce8f6dd31f06d15dc81277f39dbd))



## [4.29.3](https://github.com/Ombi-app/Ombi/compare/v4.29.2...v4.29.3) (2022-11-14)


### Bug Fixes

* **notifications:** Fixed the Partially TV notifications going to the admin [#4797](https://github.com/Ombi-app/Ombi/issues/4797) ([#4799](https://github.com/Ombi-app/Ombi/issues/4799)) ([bcb3e7f](https://github.com/Ombi-app/Ombi/commit/bcb3e7f00380a4c4278f59dc55febf43e6d05d47))
* Only log error messages from Microsoft ([#4787](https://github.com/Ombi-app/Ombi/issues/4787)) ([c614e0c](https://github.com/Ombi-app/Ombi/commit/c614e0ca5fe5023cbe7ced326145273cd75be85d))



## [4.29.2](https://github.com/Ombi-app/Ombi/compare/v4.29.1...v4.29.2) (2022-10-24)


### Bug Fixes

* **plex:** Fixed an issue where sometimes the availability checker would throw an exception when checking episodes ([17ba202](https://github.com/Ombi-app/Ombi/commit/17ba2020ee0950c2c0e0e03fdb7835b579da75a9))



## [4.29.1](https://github.com/Ombi-app/Ombi/compare/v4.29.0...v4.29.1) (2022-10-22)


### Bug Fixes

* Consistently reset loading flag when requesting movies on discover page. ([#4777](https://github.com/Ombi-app/Ombi/issues/4777)) ([a40ab5c](https://github.com/Ombi-app/Ombi/commit/a40ab5cddf769d4147696eca50c1610b466ab99b))
* **sonarr:** :bug: Fixed an issue where the language list didn't correctly load for power users in the advanced options [#4782](https://github.com/Ombi-app/Ombi/issues/4782) ([2173670](https://github.com/Ombi-app/Ombi/commit/217367047d1568070dd507e54ad3fd2c68f05b88))



# [4.29.0](https://github.com/Ombi-app/Ombi/compare/v4.28.1...v4.29.0) (2022-10-19)


### Bug Fixes

* Partially Available prevents further TV requests ([#4768](https://github.com/Ombi-app/Ombi/issues/4768)) ([#4779](https://github.com/Ombi-app/Ombi/issues/4779)) ([031e2b9](https://github.com/Ombi-app/Ombi/commit/031e2b9283b239827cabaca4e35f69f2f93a4d7b))
* Unable to Delete Jellyfin Server ([#4705](https://github.com/Ombi-app/Ombi/issues/4705)) ([#4780](https://github.com/Ombi-app/Ombi/issues/4780)) ([76a0d0d](https://github.com/Ombi-app/Ombi/commit/76a0d0d26893bd480fea4735f77522ac6261a425))


### Features

* Provide a flag for missing users on Plex Server ([#4688](https://github.com/Ombi-app/Ombi/issues/4688)) ([#4778](https://github.com/Ombi-app/Ombi/issues/4778)) ([b4a14c2](https://github.com/Ombi-app/Ombi/commit/b4a14c2d28218409390e517b226130e3e84efee1))



## [4.28.1](https://github.com/Ombi-app/Ombi/compare/v4.28.0...v4.28.1) (2022-10-19)


### Bug Fixes

* **plex:** :bug: Fixed not being able to enable watchlist requests in the Plex settings ([3e5158e](https://github.com/Ombi-app/Ombi/commit/3e5158ef9cda58ea2dd3be143f07aa5433691d79))
* Reworked the version check ([#4719](https://github.com/Ombi-app/Ombi/issues/4719)) ([#4781](https://github.com/Ombi-app/Ombi/issues/4781)) ([55855c5](https://github.com/Ombi-app/Ombi/commit/55855c5adda3cd1c51b7fbd0c19b469fc813f98e))



# [4.28.0](https://github.com/Ombi-app/Ombi/compare/v4.27.8...v4.28.0) (2022-10-07)


### Features

* **plex:** ✨ Added the ability to configure the watchlist to request the whole TV show rather than latest season ([#4774](https://github.com/Ombi-app/Ombi/issues/4774)) ([fa65712](https://github.com/Ombi-app/Ombi/commit/fa65712bd570fe8d5d21b8ca0abe182b84960017))



## [4.27.8](https://github.com/Ombi-app/Ombi/compare/v4.27.7...v4.27.8) (2022-10-07)



## [4.27.7](https://github.com/Ombi-app/Ombi/compare/v4.27.6...v4.27.7) (2022-10-07)


### Bug Fixes

* Fixes default image for recently requested items. ([#4767](https://github.com/Ombi-app/Ombi/issues/4767)) ([2e6f35f](https://github.com/Ombi-app/Ombi/commit/2e6f35f89abb3dd3685ec8289f8620c7ef7072cd))



## [4.27.6](https://github.com/Ombi-app/Ombi/compare/v4.27.5...v4.27.6) (2022-10-01)


### Bug Fixes

* **notifications:** Fixed the error when sending multiple test notifications. Added more logging when Discord complains the message is invalid ([fc14780](https://github.com/Ombi-app/Ombi/commit/fc14780bd354483119ddcbb55a8c382e1890a783))



## [4.27.5](https://github.com/Ombi-app/Ombi/compare/v4.27.4...v4.27.5) (2022-09-30)


### Bug Fixes

* **importer:** 🐛 Allow you to only import Plex Admins without the Plex Users ([8c9ad9b](https://github.com/Ombi-app/Ombi/commit/8c9ad9b414fdc6c88bdb911d6057ae5d38783b98))



## [4.27.4](https://github.com/Ombi-app/Ombi/compare/v4.27.3...v4.27.4) (2022-09-30)



## [4.27.3](https://github.com/Ombi-app/Ombi/compare/v4.27.2...v4.27.3) (2022-09-30)


### Bug Fixes

* **availability:** 🐛 Fixed a issue with the availability checker after the previous update. Added full test coverage around that area ([28e2480](https://github.com/Ombi-app/Ombi/commit/28e248046ad56390595f84172bbd5f5961325b4d))



## [4.27.2](https://github.com/Ombi-app/Ombi/compare/v4.27.1...v4.27.2) (2022-09-29)


### Bug Fixes

* **sonarr:** :bug: Cleaned up and removed Sonarr v3 option, sonarr v3 is now the default. This allows us to get ready for the upcoming Sonarr v4 ([#4764](https://github.com/Ombi-app/Ombi/issues/4764)) ([2cddec7](https://github.com/Ombi-app/Ombi/commit/2cddec759004b6490f686ff74cb092238e3dc946))



## [4.27.1](https://github.com/Ombi-app/Ombi/compare/v4.27.0...v4.27.1) (2022-09-20)


### Bug Fixes

* **plex:** stop the plex sync from deleting episodes when we can't find the plex key ([66b05e5](https://github.com/Ombi-app/Ombi/commit/66b05e5a85dbfe1fec5f9366e80987f2cfa1f4fe))



# [4.27.0](https://github.com/Ombi-app/Ombi/compare/v4.26.0...v4.27.0) (2022-09-14)


### Features

* Recently requested improvements ([#4755](https://github.com/Ombi-app/Ombi/issues/4755)) ([ff04d87](https://github.com/Ombi-app/Ombi/commit/ff04d875343604c77c391bf55d0968977e480281))



# [4.26.0](https://github.com/Ombi-app/Ombi/compare/v4.25.1...v4.26.0) (2022-09-07)


### Features

* **notifications:** Add more curly variables for partially available notification ([66aa101](https://github.com/Ombi-app/Ombi/commit/66aa101019c4c4b34e186db9d303049d02b9c781))



## [4.25.1](https://github.com/Ombi-app/Ombi/compare/v4.25.0...v4.25.1) (2022-09-07)


### Bug Fixes

* **webhook:** Remove added trailing slash from webhook URL [#4710](https://github.com/Ombi-app/Ombi/issues/4710) ([369eb33](https://github.com/Ombi-app/Ombi/commit/369eb339171671101be219486e2aab27a20f3d74))



# [4.25.0](https://github.com/Ombi-app/Ombi/compare/v4.24.0...v4.25.0) (2022-08-23)


### Bug Fixes

* fixed stats controller ([#4742](https://github.com/Ombi-app/Ombi/issues/4742)) ([47ea64b](https://github.com/Ombi-app/Ombi/commit/47ea64b5a401770f1943b575ca40f84d515e96b3))


### Features

* Watchlist history errors([#4741](https://github.com/Ombi-app/Ombi/issues/4741)) ([c222f1a](https://github.com/Ombi-app/Ombi/commit/c222f1a945e944ef34e68cad2b61f40e57cab823))



# [4.24.0](https://github.com/Ombi-app/Ombi/compare/v4.23.2...v4.24.0) (2022-08-22)


### Features

* add crew on movie page ([#4722](https://github.com/Ombi-app/Ombi/issues/4722)) ([1d53261](https://github.com/Ombi-app/Ombi/commit/1d532613823804b25984bd1d223d081a54ad143d))



## [4.23.2](https://github.com/Ombi-app/Ombi/compare/v4.23.1...v4.23.2) (2022-08-22)


### Bug Fixes

* Fix conflicting property name for Swagger ([#4733](https://github.com/Ombi-app/Ombi/issues/4733)) ([d661f32](https://github.com/Ombi-app/Ombi/commit/d661f32e8a9e105faab6380b4b7b642896b98163))



## [4.23.1](https://github.com/Ombi-app/Ombi/compare/v4.23.0...v4.23.1) (2022-08-12)


### Bug Fixes

* Localize recently requested on discover page ([#4729](https://github.com/Ombi-app/Ombi/issues/4729)) ([bf65c76](https://github.com/Ombi-app/Ombi/commit/bf65c76ff9ce38f65a9e5feb872734e8d8e35eb6))



# [4.23.0](https://github.com/Ombi-app/Ombi/compare/v4.22.5...v4.23.0) (2022-08-09)


### Bug Fixes

* Log Microsoft warnings to log file ([#4723](https://github.com/Ombi-app/Ombi/issues/4723)) ([26ac75f](https://github.com/Ombi-app/Ombi/commit/26ac75f0c223c2a91e3471797ae46ede3fde89cc))


### Features

* ✨ Recently Requested on Discover Page ([#4387](https://github.com/Ombi-app/Ombi/issues/4387)) ([44d38fb](https://github.com/Ombi-app/Ombi/commit/44d38fbaae521dbb467b61c7471b2384015ac52e))



## [4.22.4](https://github.com/Ombi-app/Ombi/compare/v4.22.3...v4.22.4) (2022-08-04)


### Bug Fixes

* :bug: Fixed missing externals ([#4712](https://github.com/Ombi-app/Ombi/issues/4712)) ([fcc1eaa](https://github.com/Ombi-app/Ombi/commit/fcc1eaaa377683dcdc81d62a2a688fb0c4490c7b))
* fixed trakt image not loading when base url present ([#4711](https://github.com/Ombi-app/Ombi/issues/4711)) ([f102dcf](https://github.com/Ombi-app/Ombi/commit/f102dcf751c2eb62ebfe30f9f8e4b2ad863c3b0d))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([#4713](https://github.com/Ombi-app/Ombi/issues/4713)) ([ff142b0](https://github.com/Ombi-app/Ombi/commit/ff142b09abbb2f9540387284222552e6e12639fe))



## [4.22.3](https://github.com/Ombi-app/Ombi/compare/v4.22.2...v4.22.3) (2022-07-28)


### Bug Fixes

* Override Sonarr V3 Profiles endpoint ([#4678](https://github.com/Ombi-app/Ombi/issues/4678)) ([875da95](https://github.com/Ombi-app/Ombi/commit/875da959f353119b05138d68ee6d32a49e14b91e))



## [4.22.2](https://github.com/Ombi-app/Ombi/compare/v4.22.1...v4.22.2) (2022-07-25)


### Bug Fixes

* fixed an issue where I broke images for some users ([81ddc85](https://github.com/Ombi-app/Ombi/commit/81ddc8553b9094c3f6843b036daebb2eb9262e00))



## [4.22.1](https://github.com/Ombi-app/Ombi/compare/v4.22.0...v4.22.1) (2022-07-25)


### Bug Fixes

* **discover:** :bug: Created new Image component to handle 429's from TMDB ([#4698](https://github.com/Ombi-app/Ombi/issues/4698)) and fixed [#4635](https://github.com/Ombi-app/Ombi/issues/4635) ([#4699](https://github.com/Ombi-app/Ombi/issues/4699)) ([f22d3da](https://github.com/Ombi-app/Ombi/commit/f22d3da765799365455b919027f7563e52b347c3))



# [4.22.0](https://github.com/Ombi-app/Ombi/compare/v4.21.2...v4.22.0) (2022-07-22)


### Features

* **discover:** ✨ Added infinite scroll on advanced search results ([898bc89](https://github.com/Ombi-app/Ombi/commit/898bc89fa78245c1f3de9481f6c724f087a16e39))



## [4.21.2](https://github.com/Ombi-app/Ombi/compare/v4.21.1...v4.21.2) (2022-07-22)


### Bug Fixes

* Landing and Login page improvements ([#4690](https://github.com/Ombi-app/Ombi/issues/4690)) ([6d423b5](https://github.com/Ombi-app/Ombi/commit/6d423b5447c52c5e59d8d2bd92a23b47468eb736))



## [4.21.1](https://github.com/Ombi-app/Ombi/compare/v4.21.0...v4.21.1) (2022-07-11)


### Bug Fixes

* **images:** Retry images with a backoff when we get a Too Many requests from TheMovieDb [#4685](https://github.com/Ombi-app/Ombi/issues/4685) ([3f1f35d](https://github.com/Ombi-app/Ombi/commit/3f1f35df3164db6739691cdda8f925c296239791))



# [4.21.0](https://github.com/Ombi-app/Ombi/compare/v4.20.4...v4.21.0) (2022-06-22)


### Features

* Upgrade to Angular14 ([#4668](https://github.com/Ombi-app/Ombi/issues/4668)) ([b9d55a4](https://github.com/Ombi-app/Ombi/commit/b9d55a469b412558cbf67c1e25db7fdda5964cd8))


### Performance Improvements

* stop populating obsolete subscribe fields ([#4625](https://github.com/Ombi-app/Ombi/issues/4625)) ([9a73463](https://github.com/Ombi-app/Ombi/commit/9a734637665f671b17c2bb440d93b35a891c142b))



## [4.20.4](https://github.com/Ombi-app/Ombi/compare/v4.20.3...v4.20.4) (2022-06-15)


### Bug Fixes

* fixed build ([f877921](https://github.com/Ombi-app/Ombi/commit/f8779219146051ea74f8b6408658ff7975afb88b))



## [4.20.3](https://github.com/Ombi-app/Ombi/compare/v4.20.2...v4.20.3) (2022-06-05)


### Bug Fixes

* **plex:** 🐛 Fixed an issue with the Plex Sync ([ab1a11a](https://github.com/Ombi-app/Ombi/commit/ab1a11af78efbe9d37bd55aa80a640796c138a98))



## [4.20.2](https://github.com/Ombi-app/Ombi/compare/v4.20.1...v4.20.2) (2022-06-03)


### Bug Fixes

* :bug: Fixed the Request on Behalf of having blanks ([#4667](https://github.com/Ombi-app/Ombi/issues/4667)) ([7dd9b1c](https://github.com/Ombi-app/Ombi/commit/7dd9b1cac07f571dd35b362544e4fe0226c4b817))



## [4.20.1](https://github.com/Ombi-app/Ombi/compare/v4.20.0...v4.20.1) (2022-05-27)


### Bug Fixes

* added media type tag to media type text ([#4638](https://github.com/Ombi-app/Ombi/issues/4638)) ([fe501d3](https://github.com/Ombi-app/Ombi/commit/fe501d34a0c36ac9f000b107eca49dbc6694d006))
* **API:** Fix pagination in some edge cases ([#4649](https://github.com/Ombi-app/Ombi/issues/4649)) ([a70bf8f](https://github.com/Ombi-app/Ombi/commit/a70bf8f46c76d74c9dfdf908c53bd9955ca0a35d))
* **discover:** Carousel touch not working when scrolling page and recommendations and similar movie navigation ([#4633](https://github.com/Ombi-app/Ombi/issues/4633)) ([d5ef1d5](https://github.com/Ombi-app/Ombi/commit/d5ef1d53e5f77d19dba8b8059c80b538a3e14f2a))
* Improve Swagger documentation ([#4652](https://github.com/Ombi-app/Ombi/issues/4652)) ([181892b](https://github.com/Ombi-app/Ombi/commit/181892bcfe88e6d76febf49ef57745d04552d08e))
* Missing Poster broken link fix ([#4637](https://github.com/Ombi-app/Ombi/issues/4637)) ([4070f0d](https://github.com/Ombi-app/Ombi/commit/4070f0d093b1c92487a1c80cabad8283a9650f51))
* **sickrage:** Fixed issue with incorrect handling of SiCKRAGE episode results returned during episode status changes, now expects array of objects from data path if present ([#4648](https://github.com/Ombi-app/Ombi/issues/4648)) ([6d16442](https://github.com/Ombi-app/Ombi/commit/6d16442d4d714920367df065a3ced42b729f4233))
* **sync:** Emby+Jellyfin - sync multi-episode files of 3+ episodes ([bd8fd89](https://github.com/Ombi-app/Ombi/commit/bd8fd890554c9d85d6da4d2cee813e82ce698e52))



# [4.20.0](https://github.com/Ombi-app/Ombi/compare/v4.19.1...v4.20.0) (2022-04-28)


### Features

* **discover:** Show more relevant shows in upcoming TV ([8357819](https://github.com/Ombi-app/Ombi/commit/8357819b53b8c675c0b246d7006b5a778bdba33f))



## [4.19.1](https://github.com/Ombi-app/Ombi/compare/v4.19.0...v4.19.1) (2022-04-27)



# [4.19.0](https://github.com/Ombi-app/Ombi/compare/v4.18.0...v4.19.0) (2022-04-27)


### Features

* **sync:** Detect reidentified movies in Emby and Jellyfin ([5938077](https://github.com/Ombi-app/Ombi/commit/5938077d82a5357f79c07b218b3986557a5816e8))
* **sync:** Detect reidentified series in Emby and Jellyfin ([9096e91](https://github.com/Ombi-app/Ombi/commit/9096e91d55d268819bce22831f8a8b27f2a1776b))



# [4.18.0](https://github.com/Ombi-app/Ombi/compare/v4.17.0...v4.18.0) (2022-04-26)


### Bug Fixes

* **discover:** Fix cache mix up ([03d9422](https://github.com/Ombi-app/Ombi/commit/03d94220c7eaafb50c6c80a6ed1150794b873ac3))
* **discover:** Fix new trending feature detection ([6794b88](https://github.com/Ombi-app/Ombi/commit/6794b887f6544fb41528bdd9728b7824b65e47ee))
* **settings:** Allow toggling features when there are more than one ([a373359](https://github.com/Ombi-app/Ombi/commit/a373359ae8e6bad42b558a6e01a8ff2840d3bbaa))


### Features

* **discover:** Add new trending source experimental feature ([1a0823c](https://github.com/Ombi-app/Ombi/commit/1a0823ca80559417c67323aaeaa1ef5243e98031))
* **discover:** Default trending source to new logic ([4f12939](https://github.com/Ombi-app/Ombi/commit/4f12939e22020a67a5ee75e2907923faea136e8d))



# [4.17.0](https://github.com/Ombi-app/Ombi/compare/v4.16.17...v4.17.0) (2022-04-25)



## [4.16.17](https://github.com/Ombi-app/Ombi/compare/v4.16.16...v4.16.17) (2022-04-25)



## [4.16.16](https://github.com/Ombi-app/Ombi/compare/v4.16.15...v4.16.16) (2022-04-25)


### Bug Fixes

* **4616:** :bug: fixed mandatory fields ([d8f2260](https://github.com/Ombi-app/Ombi/commit/d8f2260c7ae3ed48386743b7adbd06e284487034))



## [4.16.15](https://github.com/Ombi-app/Ombi/compare/v4.16.14...v4.16.15) (2022-04-24)


### Features

* **discover:** Add original language filter ([ef7ec86](https://github.com/Ombi-app/Ombi/commit/ef7ec861d8aede2a4817752c990617f583805391))



## [4.16.14](https://github.com/Ombi-app/Ombi/compare/v4.16.13...v4.16.14) (2022-04-19)



## [4.16.13](https://github.com/Ombi-app/Ombi/compare/v4.16.12...v4.16.13) (2022-04-19)



## [4.35.11](https://github.com/Ombi-app/Ombi/compare/v4.38.2...v4.35.11) (2023-05-17)



## [4.35.10](https://github.com/Ombi-app/Ombi/compare/v4.35.9...v4.35.10) (2023-02-25)



## [4.38.2](https://github.com/Ombi-app/Ombi/compare/v4.38.1...v4.38.2) (2023-05-17)



## [4.38.1](https://github.com/Ombi-app/Ombi/compare/v4.38.0...v4.38.1) (2023-05-09)


### Bug Fixes

* **API:** Allow RequestOnBehalf rights if requested from the API ([#4919](https://github.com/Ombi-app/Ombi/issues/4919)) ([bb6dedd](https://github.com/Ombi-app/Ombi/commit/bb6deddfaecb3d6c7c3c6970414444b619bb9106))
* **notificaitons:** Add the RequestedByAlias field to the Notification Message ([7e9c8be](https://github.com/Ombi-app/Ombi/commit/7e9c8bec6b02bb4e11f8db50394e493d4dd07723))



# [4.38.0](https://github.com/Ombi-app/Ombi/compare/v4.37.3...v4.38.0) (2023-05-07)


### Bug Fixes

* remove sort header ([969bc7b](https://github.com/Ombi-app/Ombi/commit/969bc7bb25ea900ab9199509b079b36843e5bd6f))


### Features

* **emby:** Show watched status for Movie requests ([9cfb10b](https://github.com/Ombi-app/Ombi/commit/9cfb10bb1ee69067a6f47bd2c8a72d4e6834350e))



## [4.37.3](https://github.com/Ombi-app/Ombi/compare/v4.37.2...v4.37.3) (2023-05-07)


### Bug Fixes

* Show the ApiAlias in the requests-list ([9ff624c](https://github.com/Ombi-app/Ombi/commit/9ff624ce4646815b239fbb8327117947f0a90e4b))



## [4.37.2](https://github.com/Ombi-app/Ombi/compare/v4.37.1...v4.37.2) (2023-05-03)


### Bug Fixes

* **jellyfin:** Fixed an issue where the sync could stop working. Removed unused properties so the deseralization no longer fails ([0e5e0ad](https://github.com/Ombi-app/Ombi/commit/0e5e0adf862701d0f672beff14ec0aa75e4b5220))



## [4.37.1](https://github.com/Ombi-app/Ombi/compare/v4.37.0...v4.37.1) (2023-05-02)


### Bug Fixes

* Cron Validation ([#4842](https://github.com/Ombi-app/Ombi/issues/4842)) ([97cc42f](https://github.com/Ombi-app/Ombi/commit/97cc42ffa8672e7d0d0996b5fbda7f7fe699da2d))
* **discover:** :children_crossing: Improved the new Genre buttons, it now includes TV results ([b087d60](https://github.com/Ombi-app/Ombi/commit/b087d606ff36565208e564f8856903f2a4098db5))
* **lidarr:** Change monitor to Existing to properly add artist [#3597](https://github.com/Ombi-app/Ombi/issues/3597) ([506f607](https://github.com/Ombi-app/Ombi/commit/506f60773bf1031d0be51ccd34289b855a04ea40)), closes [/github.com/Lidarr/Lidarr/issues/3597#issuecomment-1530804055](https://github.com//github.com/Lidarr/Lidarr/issues/3597/issues/issuecomment-1530804055)



# [4.37.0](https://github.com/Ombi-app/Ombi/compare/v4.36.1...v4.37.0) (2023-04-24)


### Features

* Search by genre ([1837419](https://github.com/Ombi-app/Ombi/commit/18374198f9f2462ba85c5781b0fcc05892728b21))



## [4.36.1](https://github.com/Ombi-app/Ombi/compare/v4.36.0...v4.36.1) (2023-04-20)


### Bug Fixes

* **healthchecks:** Removed redundant ping check ([1751305](https://github.com/Ombi-app/Ombi/commit/1751305064176d2c0135f867773ccc46b03915ec))



# [4.36.0](https://github.com/Ombi-app/Ombi/compare/v4.35.19...v4.36.0) (2023-04-20)


### Features

* **discover:** Add deny option to recently requested ([#4907](https://github.com/Ombi-app/Ombi/issues/4907)) ([78f340e](https://github.com/Ombi-app/Ombi/commit/78f340ee5f309c55690497170897533801957668))



## [4.35.19](https://github.com/Ombi-app/Ombi/compare/v4.35.18...v4.35.19) (2023-04-20)


### Bug Fixes

* **radarr:** Fixed an issue where the radarr sync would break ([de4baad](https://github.com/Ombi-app/Ombi/commit/de4baade9f87248d77106ff1a313a498870f4fb3))



## [4.35.18](https://github.com/Ombi-app/Ombi/compare/v4.35.17...v4.35.18) (2023-04-15)


### Bug Fixes

* **#4906:** :bug: Fixed an issue with power users and permissions ([80884bc](https://github.com/Ombi-app/Ombi/commit/80884bcd725c329867c278ad235cd4096cd4fe7a))



## [4.35.17](https://github.com/Ombi-app/Ombi/compare/v4.35.16...v4.35.17) (2023-04-15)


### Bug Fixes

* **discover:** Fix denied requests displayed as approved ([#4901](https://github.com/Ombi-app/Ombi/issues/4901)) ([1e87f20](https://github.com/Ombi-app/Ombi/commit/1e87f2010491b0f3fdda70d2b19d9afd94438df7))
* Fix denied movie shown as 'processing request' in details view ([#4900](https://github.com/Ombi-app/Ombi/issues/4900)) ([0069bfd](https://github.com/Ombi-app/Ombi/commit/0069bfdf54e0785bad45c832ca052f19fd4b940b))



## [4.35.16](https://github.com/Ombi-app/Ombi/compare/v4.35.15...v4.35.16) (2023-04-13)


### Bug Fixes

* Support duplicates in Emby/JF collections ([#4902](https://github.com/Ombi-app/Ombi/issues/4902)) ([141f96d](https://github.com/Ombi-app/Ombi/commit/141f96da5e45d5b3fa5f496806b102e473da6607))



## [4.35.15](https://github.com/Ombi-app/Ombi/compare/v4.35.14...v4.35.15) (2023-04-06)


### Bug Fixes

* **sonarr:** :bug: Stop the sonarr version endpoint from breaking when Sonarr is down [#4895](https://github.com/Ombi-app/Ombi/issues/4895) ([7bb8bec](https://github.com/Ombi-app/Ombi/commit/7bb8becfb140ef6012356752a71d53b5b404e482))



## [4.35.14](https://github.com/Ombi-app/Ombi/compare/v4.35.13...v4.35.14) (2023-04-06)


### Bug Fixes

* Some minor tweaks to the movie info panel ([#4883](https://github.com/Ombi-app/Ombi/issues/4883)) ([1244487](https://github.com/Ombi-app/Ombi/commit/12444871df2f7602200f73971fce962f06b4a80b))



## [4.35.13](https://github.com/Ombi-app/Ombi/compare/v4.35.12...v4.35.13) (2023-03-28)


### Bug Fixes

* **sonarr:** :bug: Added some more error handling and information around testing sonarr ([bd2c2d3](https://github.com/Ombi-app/Ombi/commit/bd2c2d3901e239393010fd582b207f1571fb4b7e)), closes [#4877](https://github.com/Ombi-app/Ombi/issues/4877)



## [4.35.12](https://github.com/Ombi-app/Ombi/compare/v4.35.10...v4.35.12) (2023-03-25)


### Bug Fixes

* **sonarr:** :bug: Improved the error handling in the sonarr settings page in the UI ([fcd78fe](https://github.com/Ombi-app/Ombi/commit/fcd78fee619d10ec7d78e8c8ec6c3ac4b0a361a1)), closes [#4877](https://github.com/Ombi-app/Ombi/issues/4877)



## [4.35.9](https://github.com/Ombi-app/Ombi/compare/v4.35.8...v4.35.9) (2023-02-24)



## [4.35.8](https://github.com/Ombi-app/Ombi/compare/v4.35.7...v4.35.8) (2023-02-17)


### Bug Fixes

* **plex-oauth:** 🐛 Fixed an issue where using OAuth you could log in as a Ombi Local user [#4835](https://github.com/Ombi-app/Ombi/issues/4835) ([4098da3](https://github.com/Ombi-app/Ombi/commit/4098da305aaea9dae9a552644268a4fed7204cfe))



## [4.35.7](https://github.com/Ombi-app/Ombi/compare/v4.35.6...v4.35.7) (2023-02-10)


### Bug Fixes

* **wizard:** :bug: Stop access to the wizard when you have already setup ombi ([#4866](https://github.com/Ombi-app/Ombi/issues/4866)) ([353de98](https://github.com/Ombi-app/Ombi/commit/353de981a462e1753288d225ec4644a44a62d2bc))



## [4.35.6](https://github.com/Ombi-app/Ombi/compare/v4.35.5...v4.35.6) (2023-01-31)


### Bug Fixes

* Fixed the issue where the login page is still present after logging in with oauth ([aca4ee3](https://github.com/Ombi-app/Ombi/commit/aca4ee37915a28200e5233be3dc711ccc4a5aee9))



## [4.35.5](https://github.com/Ombi-app/Ombi/compare/v4.35.4...v4.35.5) (2023-01-24)


### Bug Fixes

* **radarr-settings:** 🐛 Fixed a typo ([4a50a00](https://github.com/Ombi-app/Ombi/commit/4a50a00d4729d99f4359874b9af4dbc58a0c220b))



## [4.35.4](https://github.com/Ombi-app/Ombi/compare/v4.35.3...v4.35.4) (2023-01-22)


### Bug Fixes

* **discover:** :bug: Fixed the default poster not taking into account the base url in some scenarios [#4845](https://github.com/Ombi-app/Ombi/issues/4845) ([8eda250](https://github.com/Ombi-app/Ombi/commit/8eda250367953183daec03ccb5cdf9fe94275b27))
* **Hide music from navbar and request list when not enabled:** :bug: ([5123a76](https://github.com/Ombi-app/Ombi/commit/5123a76954e9f81d58c05e31afc7a29aec19cb7a))



## [4.35.3](https://github.com/Ombi-app/Ombi/compare/v4.35.2...v4.35.3) (2023-01-13)


### Bug Fixes

* **#4847:** Invalid Discord request fixed, also fixed an issue where App Only users would not show as logged in on the user management page ([#4848](https://github.com/Ombi-app/Ombi/issues/4848)) ([f229d88](https://github.com/Ombi-app/Ombi/commit/f229d88bd744bc5253b5d3db69ae5ef22d014230))



## [4.35.2](https://github.com/Ombi-app/Ombi/compare/v4.35.1...v4.35.2) (2023-01-08)


### Bug Fixes

* **database:** Just some tweaks, shouldn't notice any difference, maybe a less error in the log ([67fb992](https://github.com/Ombi-app/Ombi/commit/67fb9921c0c025025286eb6c0a9d09fd01b18465))



## [4.35.1](https://github.com/Ombi-app/Ombi/compare/v4.35.0...v4.35.1) (2023-01-06)


### Bug Fixes

* **plex-watchlist:** Index out of bounds error ([8cd556e](https://github.com/Ombi-app/Ombi/commit/8cd556e268931596b9c1d1ae0ce533bfaaf330f4))



# [4.35.0](https://github.com/Ombi-app/Ombi/compare/v4.34.1...v4.35.0) (2023-01-04)


### Features

* Add the option for header authentication to create users ([#4841](https://github.com/Ombi-app/Ombi/issues/4841)) ([e6c9ce5](https://github.com/Ombi-app/Ombi/commit/e6c9ce5ad0056608ecda8273fb8124ed292e2942))



## [4.34.1](https://github.com/Ombi-app/Ombi/compare/v4.34.0...v4.34.1) (2023-01-04)


### Bug Fixes

* **plex-watchlist:** Lookup the ID from different sources when Plex doesn't contain the metadata ([#4843](https://github.com/Ombi-app/Ombi/issues/4843)) ([a2cc23b](https://github.com/Ombi-app/Ombi/commit/a2cc23b351c4a568c44e6c855f94db9f71ad084a))



# [4.34.0](https://github.com/Ombi-app/Ombi/compare/v4.33.1...v4.34.0) (2023-01-04)


### Features

* Radarr tags ([#4815](https://github.com/Ombi-app/Ombi/issues/4815)) ([6fa5064](https://github.com/Ombi-app/Ombi/commit/6fa506491fe867cdeef9df79991ae49319d71c3d))



## [4.33.1](https://github.com/Ombi-app/Ombi/compare/v4.33.0...v4.33.1) (2022-12-22)


### Bug Fixes

* **plex:** Added the watchlist request whole show back into the settings ([10701c4](https://github.com/Ombi-app/Ombi/commit/10701c4a0b6190eebb75c5d8b18224f3d0bc8502))



# [4.33.0](https://github.com/Ombi-app/Ombi/compare/v4.32.3...v4.33.0) (2022-12-01)


### Features

* Angular 15 and Dependency upgrades ([#4818](https://github.com/Ombi-app/Ombi/issues/4818)) ([4816acf](https://github.com/Ombi-app/Ombi/commit/4816acf6f94443d23ebef6091d4cfcbca580f9ca))



## [4.32.3](https://github.com/Ombi-app/Ombi/compare/v4.32.2...v4.32.3) (2022-11-24)


### Bug Fixes

* **sonarr:** V4 actually works this time around ([f62e70f](https://github.com/Ombi-app/Ombi/commit/f62e70fc493c7971da5e4508ce10522f5df0bbf7))



## [4.32.2](https://github.com/Ombi-app/Ombi/compare/v4.32.1...v4.32.2) (2022-11-23)


### Bug Fixes

* **sonarr:** :bug: Sonarr V4 should work now ([#4810](https://github.com/Ombi-app/Ombi/issues/4810)) ([37655af](https://github.com/Ombi-app/Ombi/commit/37655aff9d3d133b42f5664bc9445d6571e966d6))



## [4.32.1](https://github.com/Ombi-app/Ombi/compare/v4.32.0...v4.32.1) (2022-11-21)


### Bug Fixes

* **plex:** :bug: Fixed the issue where you couldn't add a new server on a fresh setup after the settings page rework ([187b18d](https://github.com/Ombi-app/Ombi/commit/187b18d5c01f6a13831e4a410b5d7c349e27d847))



# [4.32.0](https://github.com/Ombi-app/Ombi/compare/v4.31.0...v4.32.0) (2022-11-18)


### Bug Fixes

* **translations:** 🌐 New translations from Crowdin [skip ci] ([#4801](https://github.com/Ombi-app/Ombi/issues/4801)) ([4692003](https://github.com/Ombi-app/Ombi/commit/46920032baed04675b2ffbe1700afdc0740a4ac4))


### Features

* **plex:** Rework the Plex Settings page ([#4805](https://github.com/Ombi-app/Ombi/issues/4805)) ([1b8c47f](https://github.com/Ombi-app/Ombi/commit/1b8c47f3163f618851d4904732cb07015e1e93ff))



# [4.31.0](https://github.com/Ombi-app/Ombi/compare/v4.30.0...v4.31.0) (2022-11-18)


### Features

* **sonarr:** Added the ability to add default tags when sending to Sonarr ([#4803](https://github.com/Ombi-app/Ombi/issues/4803)) ([ecfbb8e](https://github.com/Ombi-app/Ombi/commit/ecfbb8eda91e1a90239dcf8be847afcc2394a78e))



# [4.30.0](https://github.com/Ombi-app/Ombi/compare/v4.29.3...v4.30.0) (2022-11-17)


### Features

* **sonarr:** :sparkles: Add the username to a Sonarr tag when sent to Sonarr ([#4802](https://github.com/Ombi-app/Ombi/issues/4802)) ([1d5fabd](https://github.com/Ombi-app/Ombi/commit/1d5fabd317e3ce8f6dd31f06d15dc81277f39dbd))



## [4.29.3](https://github.com/Ombi-app/Ombi/compare/v4.29.2...v4.29.3) (2022-11-14)


### Bug Fixes

* **notifications:** Fixed the Partially TV notifications going to the admin [#4797](https://github.com/Ombi-app/Ombi/issues/4797) ([#4799](https://github.com/Ombi-app/Ombi/issues/4799)) ([bcb3e7f](https://github.com/Ombi-app/Ombi/commit/bcb3e7f00380a4c4278f59dc55febf43e6d05d47))
* Only log error messages from Microsoft ([#4787](https://github.com/Ombi-app/Ombi/issues/4787)) ([c614e0c](https://github.com/Ombi-app/Ombi/commit/c614e0ca5fe5023cbe7ced326145273cd75be85d))



## [4.29.2](https://github.com/Ombi-app/Ombi/compare/v4.29.1...v4.29.2) (2022-10-24)


### Bug Fixes

* **plex:** Fixed an issue where sometimes the availability checker would throw an exception when checking episodes ([17ba202](https://github.com/Ombi-app/Ombi/commit/17ba2020ee0950c2c0e0e03fdb7835b579da75a9))



## [4.29.1](https://github.com/Ombi-app/Ombi/compare/v4.29.0...v4.29.1) (2022-10-22)


### Bug Fixes

* Consistently reset loading flag when requesting movies on discover page. ([#4777](https://github.com/Ombi-app/Ombi/issues/4777)) ([a40ab5c](https://github.com/Ombi-app/Ombi/commit/a40ab5cddf769d4147696eca50c1610b466ab99b))
* **sonarr:** :bug: Fixed an issue where the language list didn't correctly load for power users in the advanced options [#4782](https://github.com/Ombi-app/Ombi/issues/4782) ([2173670](https://github.com/Ombi-app/Ombi/commit/217367047d1568070dd507e54ad3fd2c68f05b88))



# [4.29.0](https://github.com/Ombi-app/Ombi/compare/v4.28.1...v4.29.0) (2022-10-19)


### Bug Fixes

* Partially Available prevents further TV requests ([#4768](https://github.com/Ombi-app/Ombi/issues/4768)) ([#4779](https://github.com/Ombi-app/Ombi/issues/4779)) ([031e2b9](https://github.com/Ombi-app/Ombi/commit/031e2b9283b239827cabaca4e35f69f2f93a4d7b))
* Unable to Delete Jellyfin Server ([#4705](https://github.com/Ombi-app/Ombi/issues/4705)) ([#4780](https://github.com/Ombi-app/Ombi/issues/4780)) ([76a0d0d](https://github.com/Ombi-app/Ombi/commit/76a0d0d26893bd480fea4735f77522ac6261a425))


### Features

* Provide a flag for missing users on Plex Server ([#4688](https://github.com/Ombi-app/Ombi/issues/4688)) ([#4778](https://github.com/Ombi-app/Ombi/issues/4778)) ([b4a14c2](https://github.com/Ombi-app/Ombi/commit/b4a14c2d28218409390e517b226130e3e84efee1))



## [4.28.1](https://github.com/Ombi-app/Ombi/compare/v4.28.0...v4.28.1) (2022-10-19)


### Bug Fixes

* **plex:** :bug: Fixed not being able to enable watchlist requests in the Plex settings ([3e5158e](https://github.com/Ombi-app/Ombi/commit/3e5158ef9cda58ea2dd3be143f07aa5433691d79))
* Reworked the version check ([#4719](https://github.com/Ombi-app/Ombi/issues/4719)) ([#4781](https://github.com/Ombi-app/Ombi/issues/4781)) ([55855c5](https://github.com/Ombi-app/Ombi/commit/55855c5adda3cd1c51b7fbd0c19b469fc813f98e))



# [4.28.0](https://github.com/Ombi-app/Ombi/compare/v4.27.8...v4.28.0) (2022-10-07)


### Features

* **plex:** ✨ Added the ability to configure the watchlist to request the whole TV show rather than latest season ([#4774](https://github.com/Ombi-app/Ombi/issues/4774)) ([fa65712](https://github.com/Ombi-app/Ombi/commit/fa65712bd570fe8d5d21b8ca0abe182b84960017))



## [4.27.8](https://github.com/Ombi-app/Ombi/compare/v4.27.7...v4.27.8) (2022-10-07)



## [4.27.7](https://github.com/Ombi-app/Ombi/compare/v4.27.6...v4.27.7) (2022-10-07)


### Bug Fixes

* Fixes default image for recently requested items. ([#4767](https://github.com/Ombi-app/Ombi/issues/4767)) ([2e6f35f](https://github.com/Ombi-app/Ombi/commit/2e6f35f89abb3dd3685ec8289f8620c7ef7072cd))



## [4.27.6](https://github.com/Ombi-app/Ombi/compare/v4.27.5...v4.27.6) (2022-10-01)


### Bug Fixes

* **notifications:** Fixed the error when sending multiple test notifications. Added more logging when Discord complains the message is invalid ([fc14780](https://github.com/Ombi-app/Ombi/commit/fc14780bd354483119ddcbb55a8c382e1890a783))



## [4.27.5](https://github.com/Ombi-app/Ombi/compare/v4.27.4...v4.27.5) (2022-09-30)


### Bug Fixes

* **importer:** 🐛 Allow you to only import Plex Admins without the Plex Users ([8c9ad9b](https://github.com/Ombi-app/Ombi/commit/8c9ad9b414fdc6c88bdb911d6057ae5d38783b98))



## [4.27.4](https://github.com/Ombi-app/Ombi/compare/v4.27.3...v4.27.4) (2022-09-30)



## [4.27.3](https://github.com/Ombi-app/Ombi/compare/v4.27.2...v4.27.3) (2022-09-30)


### Bug Fixes

* **availability:** 🐛 Fixed a issue with the availability checker after the previous update. Added full test coverage around that area ([28e2480](https://github.com/Ombi-app/Ombi/commit/28e248046ad56390595f84172bbd5f5961325b4d))



## [4.27.2](https://github.com/Ombi-app/Ombi/compare/v4.27.1...v4.27.2) (2022-09-29)


### Bug Fixes

* **sonarr:** :bug: Cleaned up and removed Sonarr v3 option, sonarr v3 is now the default. This allows us to get ready for the upcoming Sonarr v4 ([#4764](https://github.com/Ombi-app/Ombi/issues/4764)) ([2cddec7](https://github.com/Ombi-app/Ombi/commit/2cddec759004b6490f686ff74cb092238e3dc946))



## [4.27.1](https://github.com/Ombi-app/Ombi/compare/v4.27.0...v4.27.1) (2022-09-20)


### Bug Fixes

* **plex:** stop the plex sync from deleting episodes when we can't find the plex key ([66b05e5](https://github.com/Ombi-app/Ombi/commit/66b05e5a85dbfe1fec5f9366e80987f2cfa1f4fe))



# [4.27.0](https://github.com/Ombi-app/Ombi/compare/v4.26.0...v4.27.0) (2022-09-14)


### Features

* Recently requested improvements ([#4755](https://github.com/Ombi-app/Ombi/issues/4755)) ([ff04d87](https://github.com/Ombi-app/Ombi/commit/ff04d875343604c77c391bf55d0968977e480281))



# [4.26.0](https://github.com/Ombi-app/Ombi/compare/v4.25.1...v4.26.0) (2022-09-07)


### Features

* **notifications:** Add more curly variables for partially available notification ([66aa101](https://github.com/Ombi-app/Ombi/commit/66aa101019c4c4b34e186db9d303049d02b9c781))



## [4.25.1](https://github.com/Ombi-app/Ombi/compare/v4.25.0...v4.25.1) (2022-09-07)


### Bug Fixes

* **webhook:** Remove added trailing slash from webhook URL [#4710](https://github.com/Ombi-app/Ombi/issues/4710) ([369eb33](https://github.com/Ombi-app/Ombi/commit/369eb339171671101be219486e2aab27a20f3d74))



# [4.25.0](https://github.com/Ombi-app/Ombi/compare/v4.24.0...v4.25.0) (2022-08-23)


### Bug Fixes

* fixed stats controller ([#4742](https://github.com/Ombi-app/Ombi/issues/4742)) ([47ea64b](https://github.com/Ombi-app/Ombi/commit/47ea64b5a401770f1943b575ca40f84d515e96b3))


### Features

* Watchlist history errors([#4741](https://github.com/Ombi-app/Ombi/issues/4741)) ([c222f1a](https://github.com/Ombi-app/Ombi/commit/c222f1a945e944ef34e68cad2b61f40e57cab823))



# [4.24.0](https://github.com/Ombi-app/Ombi/compare/v4.23.2...v4.24.0) (2022-08-22)


### Features

* add crew on movie page ([#4722](https://github.com/Ombi-app/Ombi/issues/4722)) ([1d53261](https://github.com/Ombi-app/Ombi/commit/1d532613823804b25984bd1d223d081a54ad143d))



## [4.23.2](https://github.com/Ombi-app/Ombi/compare/v4.23.1...v4.23.2) (2022-08-22)


### Bug Fixes

* Fix conflicting property name for Swagger ([#4733](https://github.com/Ombi-app/Ombi/issues/4733)) ([d661f32](https://github.com/Ombi-app/Ombi/commit/d661f32e8a9e105faab6380b4b7b642896b98163))



## [4.23.1](https://github.com/Ombi-app/Ombi/compare/v4.23.0...v4.23.1) (2022-08-12)


### Bug Fixes

* Localize recently requested on discover page ([#4729](https://github.com/Ombi-app/Ombi/issues/4729)) ([bf65c76](https://github.com/Ombi-app/Ombi/commit/bf65c76ff9ce38f65a9e5feb872734e8d8e35eb6))



# [4.23.0](https://github.com/Ombi-app/Ombi/compare/v4.22.5...v4.23.0) (2022-08-09)


### Bug Fixes

* Log Microsoft warnings to log file ([#4723](https://github.com/Ombi-app/Ombi/issues/4723)) ([26ac75f](https://github.com/Ombi-app/Ombi/commit/26ac75f0c223c2a91e3471797ae46ede3fde89cc))


### Features

* ✨ Recently Requested on Discover Page ([#4387](https://github.com/Ombi-app/Ombi/issues/4387)) ([44d38fb](https://github.com/Ombi-app/Ombi/commit/44d38fbaae521dbb467b61c7471b2384015ac52e))



## [4.22.4](https://github.com/Ombi-app/Ombi/compare/v4.22.3...v4.22.4) (2022-08-04)


### Bug Fixes

* :bug: Fixed missing externals ([#4712](https://github.com/Ombi-app/Ombi/issues/4712)) ([fcc1eaa](https://github.com/Ombi-app/Ombi/commit/fcc1eaaa377683dcdc81d62a2a688fb0c4490c7b))
* fixed trakt image not loading when base url present ([#4711](https://github.com/Ombi-app/Ombi/issues/4711)) ([f102dcf](https://github.com/Ombi-app/Ombi/commit/f102dcf751c2eb62ebfe30f9f8e4b2ad863c3b0d))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([#4713](https://github.com/Ombi-app/Ombi/issues/4713)) ([ff142b0](https://github.com/Ombi-app/Ombi/commit/ff142b09abbb2f9540387284222552e6e12639fe))



## [4.22.3](https://github.com/Ombi-app/Ombi/compare/v4.22.2...v4.22.3) (2022-07-28)


### Bug Fixes

* Override Sonarr V3 Profiles endpoint ([#4678](https://github.com/Ombi-app/Ombi/issues/4678)) ([875da95](https://github.com/Ombi-app/Ombi/commit/875da959f353119b05138d68ee6d32a49e14b91e))



## [4.22.2](https://github.com/Ombi-app/Ombi/compare/v4.22.1...v4.22.2) (2022-07-25)


### Bug Fixes

* fixed an issue where I broke images for some users ([81ddc85](https://github.com/Ombi-app/Ombi/commit/81ddc8553b9094c3f6843b036daebb2eb9262e00))



## [4.22.1](https://github.com/Ombi-app/Ombi/compare/v4.22.0...v4.22.1) (2022-07-25)


### Bug Fixes

* **discover:** :bug: Created new Image component to handle 429's from TMDB ([#4698](https://github.com/Ombi-app/Ombi/issues/4698)) and fixed [#4635](https://github.com/Ombi-app/Ombi/issues/4635) ([#4699](https://github.com/Ombi-app/Ombi/issues/4699)) ([f22d3da](https://github.com/Ombi-app/Ombi/commit/f22d3da765799365455b919027f7563e52b347c3))



# [4.22.0](https://github.com/Ombi-app/Ombi/compare/v4.21.2...v4.22.0) (2022-07-22)


### Features

* **discover:** ✨ Added infinite scroll on advanced search results ([898bc89](https://github.com/Ombi-app/Ombi/commit/898bc89fa78245c1f3de9481f6c724f087a16e39))



## [4.21.2](https://github.com/Ombi-app/Ombi/compare/v4.21.1...v4.21.2) (2022-07-22)


### Bug Fixes

* Landing and Login page improvements ([#4690](https://github.com/Ombi-app/Ombi/issues/4690)) ([6d423b5](https://github.com/Ombi-app/Ombi/commit/6d423b5447c52c5e59d8d2bd92a23b47468eb736))



## [4.21.1](https://github.com/Ombi-app/Ombi/compare/v4.21.0...v4.21.1) (2022-07-11)


### Bug Fixes

* **images:** Retry images with a backoff when we get a Too Many requests from TheMovieDb [#4685](https://github.com/Ombi-app/Ombi/issues/4685) ([3f1f35d](https://github.com/Ombi-app/Ombi/commit/3f1f35df3164db6739691cdda8f925c296239791))



# [4.21.0](https://github.com/Ombi-app/Ombi/compare/v4.20.4...v4.21.0) (2022-06-22)


### Features

* Upgrade to Angular14 ([#4668](https://github.com/Ombi-app/Ombi/issues/4668)) ([b9d55a4](https://github.com/Ombi-app/Ombi/commit/b9d55a469b412558cbf67c1e25db7fdda5964cd8))


### Performance Improvements

* stop populating obsolete subscribe fields ([#4625](https://github.com/Ombi-app/Ombi/issues/4625)) ([9a73463](https://github.com/Ombi-app/Ombi/commit/9a734637665f671b17c2bb440d93b35a891c142b))



## [4.20.4](https://github.com/Ombi-app/Ombi/compare/v4.20.3...v4.20.4) (2022-06-15)


### Bug Fixes

* fixed build ([f877921](https://github.com/Ombi-app/Ombi/commit/f8779219146051ea74f8b6408658ff7975afb88b))



## [4.20.3](https://github.com/Ombi-app/Ombi/compare/v4.20.2...v4.20.3) (2022-06-05)


### Bug Fixes

* **plex:** 🐛 Fixed an issue with the Plex Sync ([ab1a11a](https://github.com/Ombi-app/Ombi/commit/ab1a11af78efbe9d37bd55aa80a640796c138a98))



## [4.20.2](https://github.com/Ombi-app/Ombi/compare/v4.20.1...v4.20.2) (2022-06-03)


### Bug Fixes

* :bug: Fixed the Request on Behalf of having blanks ([#4667](https://github.com/Ombi-app/Ombi/issues/4667)) ([7dd9b1c](https://github.com/Ombi-app/Ombi/commit/7dd9b1cac07f571dd35b362544e4fe0226c4b817))



## [4.20.1](https://github.com/Ombi-app/Ombi/compare/v4.20.0...v4.20.1) (2022-05-27)


### Bug Fixes

* added media type tag to media type text ([#4638](https://github.com/Ombi-app/Ombi/issues/4638)) ([fe501d3](https://github.com/Ombi-app/Ombi/commit/fe501d34a0c36ac9f000b107eca49dbc6694d006))
* **API:** Fix pagination in some edge cases ([#4649](https://github.com/Ombi-app/Ombi/issues/4649)) ([a70bf8f](https://github.com/Ombi-app/Ombi/commit/a70bf8f46c76d74c9dfdf908c53bd9955ca0a35d))
* **discover:** Carousel touch not working when scrolling page and recommendations and similar movie navigation ([#4633](https://github.com/Ombi-app/Ombi/issues/4633)) ([d5ef1d5](https://github.com/Ombi-app/Ombi/commit/d5ef1d53e5f77d19dba8b8059c80b538a3e14f2a))
* Improve Swagger documentation ([#4652](https://github.com/Ombi-app/Ombi/issues/4652)) ([181892b](https://github.com/Ombi-app/Ombi/commit/181892bcfe88e6d76febf49ef57745d04552d08e))
* Missing Poster broken link fix ([#4637](https://github.com/Ombi-app/Ombi/issues/4637)) ([4070f0d](https://github.com/Ombi-app/Ombi/commit/4070f0d093b1c92487a1c80cabad8283a9650f51))
* **sickrage:** Fixed issue with incorrect handling of SiCKRAGE episode results returned during episode status changes, now expects array of objects from data path if present ([#4648](https://github.com/Ombi-app/Ombi/issues/4648)) ([6d16442](https://github.com/Ombi-app/Ombi/commit/6d16442d4d714920367df065a3ced42b729f4233))
* **sync:** Emby+Jellyfin - sync multi-episode files of 3+ episodes ([bd8fd89](https://github.com/Ombi-app/Ombi/commit/bd8fd890554c9d85d6da4d2cee813e82ce698e52))



# [4.20.0](https://github.com/Ombi-app/Ombi/compare/v4.19.1...v4.20.0) (2022-04-28)


### Features

* **discover:** Show more relevant shows in upcoming TV ([8357819](https://github.com/Ombi-app/Ombi/commit/8357819b53b8c675c0b246d7006b5a778bdba33f))



## [4.19.1](https://github.com/Ombi-app/Ombi/compare/v4.19.0...v4.19.1) (2022-04-27)



# [4.19.0](https://github.com/Ombi-app/Ombi/compare/v4.18.0...v4.19.0) (2022-04-27)


### Features

* **sync:** Detect reidentified movies in Emby and Jellyfin ([5938077](https://github.com/Ombi-app/Ombi/commit/5938077d82a5357f79c07b218b3986557a5816e8))
* **sync:** Detect reidentified series in Emby and Jellyfin ([9096e91](https://github.com/Ombi-app/Ombi/commit/9096e91d55d268819bce22831f8a8b27f2a1776b))



# [4.18.0](https://github.com/Ombi-app/Ombi/compare/v4.17.0...v4.18.0) (2022-04-26)


### Bug Fixes

* **discover:** Fix cache mix up ([03d9422](https://github.com/Ombi-app/Ombi/commit/03d94220c7eaafb50c6c80a6ed1150794b873ac3))
* **discover:** Fix new trending feature detection ([6794b88](https://github.com/Ombi-app/Ombi/commit/6794b887f6544fb41528bdd9728b7824b65e47ee))
* **settings:** Allow toggling features when there are more than one ([a373359](https://github.com/Ombi-app/Ombi/commit/a373359ae8e6bad42b558a6e01a8ff2840d3bbaa))


### Features

* **discover:** Add new trending source experimental feature ([1a0823c](https://github.com/Ombi-app/Ombi/commit/1a0823ca80559417c67323aaeaa1ef5243e98031))
* **discover:** Default trending source to new logic ([4f12939](https://github.com/Ombi-app/Ombi/commit/4f12939e22020a67a5ee75e2907923faea136e8d))



# [4.17.0](https://github.com/Ombi-app/Ombi/compare/v4.16.17...v4.17.0) (2022-04-25)



## [4.16.17](https://github.com/Ombi-app/Ombi/compare/v4.16.16...v4.16.17) (2022-04-25)



## [4.16.16](https://github.com/Ombi-app/Ombi/compare/v4.16.15...v4.16.16) (2022-04-25)


### Bug Fixes

* **4616:** :bug: fixed mandatory fields ([d8f2260](https://github.com/Ombi-app/Ombi/commit/d8f2260c7ae3ed48386743b7adbd06e284487034))



## [4.16.15](https://github.com/Ombi-app/Ombi/compare/v4.16.14...v4.16.15) (2022-04-24)


### Features

* **discover:** Add original language filter ([ef7ec86](https://github.com/Ombi-app/Ombi/commit/ef7ec861d8aede2a4817752c990617f583805391))



## [4.16.14](https://github.com/Ombi-app/Ombi/compare/v4.16.13...v4.16.14) (2022-04-19)



## [4.16.13](https://github.com/Ombi-app/Ombi/compare/v4.16.12...v4.16.13) (2022-04-19)



## [4.35.10](https://github.com/Ombi-app/Ombi/compare/v4.35.9...v4.35.10) (2023-02-25)



## [4.35.9](https://github.com/Ombi-app/Ombi/compare/v4.35.8...v4.35.9) (2023-02-24)



## [4.22.5](https://github.com/Ombi-app/Ombi/compare/v4.22.4...v4.22.5) (2022-08-05)



## [4.35.8](https://github.com/Ombi-app/Ombi/compare/v4.35.7...v4.35.8) (2023-02-17)


### Bug Fixes

* **plex-oauth:** 🐛 Fixed an issue where using OAuth you could log in as a Ombi Local user [#4835](https://github.com/Ombi-app/Ombi/issues/4835) ([4098da3](https://github.com/Ombi-app/Ombi/commit/4098da305aaea9dae9a552644268a4fed7204cfe))



## [4.35.7](https://github.com/Ombi-app/Ombi/compare/v4.35.6...v4.35.7) (2023-02-10)


### Bug Fixes

* **wizard:** :bug: Stop access to the wizard when you have already setup ombi ([#4866](https://github.com/Ombi-app/Ombi/issues/4866)) ([353de98](https://github.com/Ombi-app/Ombi/commit/353de981a462e1753288d225ec4644a44a62d2bc))



## [4.35.6](https://github.com/Ombi-app/Ombi/compare/v4.35.5...v4.35.6) (2023-01-31)


### Bug Fixes

* Fixed the issue where the login page is still present after logging in with oauth ([aca4ee3](https://github.com/Ombi-app/Ombi/commit/aca4ee37915a28200e5233be3dc711ccc4a5aee9))



## [4.35.5](https://github.com/Ombi-app/Ombi/compare/v4.35.4...v4.35.5) (2023-01-24)


### Bug Fixes

* **radarr-settings:** 🐛 Fixed a typo ([4a50a00](https://github.com/Ombi-app/Ombi/commit/4a50a00d4729d99f4359874b9af4dbc58a0c220b))



## [4.35.4](https://github.com/Ombi-app/Ombi/compare/v4.35.3...v4.35.4) (2023-01-22)


### Bug Fixes

* **discover:** :bug: Fixed the default poster not taking into account the base url in some scenarios [#4845](https://github.com/Ombi-app/Ombi/issues/4845) ([8eda250](https://github.com/Ombi-app/Ombi/commit/8eda250367953183daec03ccb5cdf9fe94275b27))
* **Hide music from navbar and request list when not enabled:** :bug: ([5123a76](https://github.com/Ombi-app/Ombi/commit/5123a76954e9f81d58c05e31afc7a29aec19cb7a))



## [4.35.3](https://github.com/Ombi-app/Ombi/compare/v4.35.2...v4.35.3) (2023-01-13)


### Bug Fixes

* **#4847:** Invalid Discord request fixed, also fixed an issue where App Only users would not show as logged in on the user management page ([#4848](https://github.com/Ombi-app/Ombi/issues/4848)) ([f229d88](https://github.com/Ombi-app/Ombi/commit/f229d88bd744bc5253b5d3db69ae5ef22d014230))



## [4.35.2](https://github.com/Ombi-app/Ombi/compare/v4.35.1...v4.35.2) (2023-01-08)


### Bug Fixes

* **database:** Just some tweaks, shouldn't notice any difference, maybe a less error in the log ([67fb992](https://github.com/Ombi-app/Ombi/commit/67fb9921c0c025025286eb6c0a9d09fd01b18465))



## [4.35.1](https://github.com/Ombi-app/Ombi/compare/v4.35.0...v4.35.1) (2023-01-06)


### Bug Fixes

* **plex-watchlist:** Index out of bounds error ([8cd556e](https://github.com/Ombi-app/Ombi/commit/8cd556e268931596b9c1d1ae0ce533bfaaf330f4))



# [4.35.0](https://github.com/Ombi-app/Ombi/compare/v4.34.1...v4.35.0) (2023-01-04)


### Features

* Add the option for header authentication to create users ([#4841](https://github.com/Ombi-app/Ombi/issues/4841)) ([e6c9ce5](https://github.com/Ombi-app/Ombi/commit/e6c9ce5ad0056608ecda8273fb8124ed292e2942))



## [4.34.1](https://github.com/Ombi-app/Ombi/compare/v4.34.0...v4.34.1) (2023-01-04)


### Bug Fixes

* **plex-watchlist:** Lookup the ID from different sources when Plex doesn't contain the metadata ([#4843](https://github.com/Ombi-app/Ombi/issues/4843)) ([a2cc23b](https://github.com/Ombi-app/Ombi/commit/a2cc23b351c4a568c44e6c855f94db9f71ad084a))



# [4.34.0](https://github.com/Ombi-app/Ombi/compare/v4.33.1...v4.34.0) (2023-01-04)


### Features

* Radarr tags ([#4815](https://github.com/Ombi-app/Ombi/issues/4815)) ([6fa5064](https://github.com/Ombi-app/Ombi/commit/6fa506491fe867cdeef9df79991ae49319d71c3d))



## [4.33.1](https://github.com/Ombi-app/Ombi/compare/v4.33.0...v4.33.1) (2022-12-22)


### Bug Fixes

* **plex:** Added the watchlist request whole show back into the settings ([10701c4](https://github.com/Ombi-app/Ombi/commit/10701c4a0b6190eebb75c5d8b18224f3d0bc8502))



# [4.33.0](https://github.com/Ombi-app/Ombi/compare/v4.32.3...v4.33.0) (2022-12-01)


### Features

* Angular 15 and Dependency upgrades ([#4818](https://github.com/Ombi-app/Ombi/issues/4818)) ([4816acf](https://github.com/Ombi-app/Ombi/commit/4816acf6f94443d23ebef6091d4cfcbca580f9ca))



## [4.32.3](https://github.com/Ombi-app/Ombi/compare/v4.32.2...v4.32.3) (2022-11-24)


### Bug Fixes

* **sonarr:** V4 actually works this time around ([f62e70f](https://github.com/Ombi-app/Ombi/commit/f62e70fc493c7971da5e4508ce10522f5df0bbf7))



