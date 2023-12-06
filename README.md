# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [2.8.2](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/compare/v2.8.1...v2.8.2) (2023-12-06)


### Features

* allow location editing for manually placed photos ([4742526](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/commit/4742526bd93f2f5478600d96a333a59506056e74))

### [2.8.1](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/compare/v2.8.0...v2.8.1) (2023-10-20)


### Features

* added super users ([2f72703](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/commit/2f72703237fc703e5eee6018829fb3eaa5d20e4c))

## [2.8.0](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/compare/v2.7.2...v2.8.0) (2023-08-29)

* upgraded arcgis version

### [2.7.2](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/compare/v2.7.1...v2.7.2) (2023-07-18)


### Bug Fixes

* fix race condition for zooming to photos on initial load ([0b3ab01](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/commit/0b3ab017b8da6caaa3b5c90f9fd23a038187c4f9))

### [2.7.1](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/compare/v2.7.0...v2.7.1) (2023-05-31)


### Bug Fixes

* **project-info:** only make read only for existing projects when not the owner ([885ded4](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/commit/885ded45c16049448a1c228e844f38a7c1d0dab0))

## [2.7.0](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/compare/v2.6.0...v2.7.0) (2023-05-31)


### Features

* added sentry for bug monitoring ([7ddf01a](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/commit/7ddf01a42838d54cecc22a09af5e6a35f32a678d))
* allow project creators to delete projects ([9ba943f](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/commit/9ba943f09a17c5de42e9dd0d11898571e7b54cb8))
* **project-details:** allow project creators to delete projects ([a99a058](https://gitlab.com/bolton-and-menk/internal-apps/geocp-projects/commit/a99a058509d30ea8fbc3c592c2e7d599632f5405))

## [2.6.0](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.5.5...v2.6.0) (2023-03-13)


### Features

* implemented asure SSO ([2d67b04](https://github.com/Bolton-and-Menk/geocp-projects/commit/2d67b04941093c899cbb10467617ff351b0877a7))


### Bug Fixes

* fixed project zoom issue on load ([d748d03](https://github.com/Bolton-and-Menk/geocp-projects/commit/d748d03bc43bb3013bc70859361f0cc84a82dc19))
* **router:** make sure to redirect to nested route after oauth flow ([aa42b95](https://github.com/Bolton-and-Menk/geocp-projects/commit/aa42b958c8ebc836d23dce1fce61dc4ec1174868))

### [2.5.5](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.5.4...v2.5.5) (2023-01-23)


### Features

* **projects:** sort by most views ([ea761e4](https://github.com/Bolton-and-Menk/geocp-projects/commit/ea761e46e865c2b8d651d62ccd3fef451ec30de2))

### [2.5.4](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.5.3...v2.5.4) (2023-01-23)


### Features

* **projects:** added sort functionality for projects ([89ccadd](https://github.com/Bolton-and-Menk/geocp-projects/commit/89ccadd56ac7fab3ac63c95f90331987198684c5))
* show date created for projects ([adaadae](https://github.com/Bolton-and-Menk/geocp-projects/commit/adaadae05d692b6a6b890aaadb2a49506e1b036b))

### [2.5.3](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.5.2...v2.5.3) (2023-01-16)


### Bug Fixes

* **action-panel:** switch back to visible image view after showing all hidden photos ([72ef3f5](https://github.com/Bolton-and-Menk/geocp-projects/commit/72ef3f5e6b9781913103105c6305da3e5c61f154))

### [2.5.2](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.5.1...v2.5.2) (2023-01-15)


### Features

* **action-panel-item:** added property to set badge color ([f4ac0b2](https://github.com/Bolton-and-Menk/geocp-projects/commit/f4ac0b22d51c8e26e20e1a80612a2294072a4c3d))


### Bug Fixes

* do not use fields filter for openasset keywords search ([e3160e1](https://github.com/Bolton-and-Menk/geocp-projects/commit/e3160e11310945dead99588a1c1491b9033a76ec))
* **image-tags:** update model value for image tags ([d7658e3](https://github.com/Bolton-and-Menk/geocp-projects/commit/d7658e3a1495ccd800daf0e8846dee334aa16ca9))

### [2.5.1](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.5.0...v2.5.1) (2023-01-13)


### Features

* **action-panel-item:** add disabled property ([17235e8](https://github.com/Bolton-and-Menk/geocp-projects/commit/17235e8f032cb062881c7393ba4fb50067bbb951))
* **projects:** all users to toggle project photo visibility on and off ([514ddde](https://github.com/Bolton-and-Menk/geocp-projects/commit/514ddde44ab4e656a56021b48f4415bd27dc3a5b))
* prompt user before hiding photos ([4883fd1](https://github.com/Bolton-and-Menk/geocp-projects/commit/4883fd16d04ccedf0abe74869631682b6b7fcf2c))

## [2.5.0](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.4.3...v2.5.0) (2023-01-13)


### Features

* **action-item:** support spinners and badges ([6391b1b](https://github.com/Bolton-and-Menk/geocp-projects/commit/6391b1b43d9955e9e55ffd09d6273719d47583d6))
* **project-details:** show project creator at bottom of page ([1eba53c](https://github.com/Bolton-and-Menk/geocp-projects/commit/1eba53c7127bdf34e6e7c1f59d86fe2f63d7cd13))
* **projects:** added the ability to hide images ([8c601be](https://github.com/Bolton-and-Menk/geocp-projects/commit/8c601be90177489f7f952e67f41c08543eef0779))

### [2.4.3](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.4.2...v2.4.3) (2023-01-11)


### Bug Fixes

* **projects:** prevent project photos from being loaded without valid project_id ([41ec259](https://github.com/Bolton-and-Menk/geocp-projects/commit/41ec259a0a02828bb9ae6fa60ccefcca9b1119e9))

### [2.4.2](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.4.1...v2.4.2) (2022-12-20)


### Features

* increment photo views from new endpoint ([016be04](https://github.com/Bolton-and-Menk/geocp-projects/commit/016be04fddd20a61e53971d5c666856fb9642da8))

### [2.4.1](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.4.0...v2.4.1) (2022-12-15)


### Bug Fixes

* emit 'loaded-project-photos' event for public projects ([d0b8b8c](https://github.com/Bolton-and-Menk/geocp-projects/commit/d0b8b8c3e09ba373020fbf4f9ca9e6918abf3998))

## [2.4.0](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.2.3...v2.4.0) (2022-11-30)


### Features

* **mapview:** improved performance for map view ([34d7387](https://github.com/Bolton-and-Menk/geocp-projects/commit/34d7387712652393de4e2f1eef6b19a4e16a68f9))

## [2.3.0](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.2.3...v2.3.0) (2022-11-30)


### Features

* **mapview:** improved performance for map view ([34d7387](https://github.com/Bolton-and-Menk/geocp-projects/commit/34d7387712652393de4e2f1eef6b19a4e16a68f9))

### [2.2.3](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.2.2...v2.2.3) (2022-11-02)


### Bug Fixes

* **image-details:** resolved image url inconsistency issue ([a575e8d](https://github.com/Bolton-and-Menk/geocp-projects/commit/a575e8df384c30cc923cd7cc75dcda2bc0591db1))

## [2.2.2](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.2.1...v2.3.0) (2022-11-02)


### Features

* added staging deployment script ([5f00622](https://github.com/Bolton-and-Menk/geocp-projects/commit/5f006227c4245031e62ac887853530179253bfdf))
* **config:** added development env for config ([b80ab18](https://github.com/Bolton-and-Menk/geocp-projects/commit/b80ab18c18e66183b222410be3fbc03f37e0b3a3))

## [2.2.1](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.1.0...v2.2.0) (2022-11-01)


### Features

* **user-settings:** remember show my projects toggle state ([b609567](https://github.com/Bolton-and-Menk/geocp-projects/commit/b6095670ee94faa9aba430965201f74c83661f05))


### Bug Fixes

* **image-details:** show image details caption overlay on 360 images ([ee5ef46](https://github.com/Bolton-and-Menk/geocp-projects/commit/ee5ef46068f5a0b0eab08dbb939c6e07a6958ad5))

## [2.1.0](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.0.1...v2.1.0) (2022-10-31)


### Features

* add lightweight viewer for 360 degree images ([649a699](https://github.com/Bolton-and-Menk/geocp-projects/commit/649a6996a42461788f9e2d912fc0d2869694785b))

### [2.0.1](https://github.com/Bolton-and-Menk/geocp-projects/compare/v2.0.0...v2.0.1) (2022-10-13)


### Bug Fixes

* make sure _perPage is integer for pagination ([6c9dfc7](https://github.com/Bolton-and-Menk/geocp-projects/commit/6c9dfc7d0b2c054d87c57ff03b7bf7155e2bd3eb))

## [2.0.0](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.30...v2.0.0) (2022-10-03)

### [0.1.30](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.29...v0.1.30) (2022-09-28)


### Bug Fixes

* fix vantage point urls ([6c6b3f3](https://github.com/Bolton-and-Menk/geocp-projects/commit/6c6b3f365a4bbe07542156437b1f50ba8720d45a))


### [0.1.29](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.28...v0.1.29) (2022-09-13)


### Features

* use overflow for main app container in projects view ([49dae8d](https://github.com/Bolton-and-Menk/geocp-projects/commit/49dae8d02ac427ac417091ecab944c6799a3b632))

### [0.1.28](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.27...v0.1.28) (2022-09-12)


### Bug Fixes

* remove null values for date_taken in photo filters ([9246478](https://github.com/Bolton-and-Menk/geocp-projects/commit/92464781656acc9a2d275a695446cac544116fc0))

### [0.1.27](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.26...v0.1.27) (2022-09-12)


### Features

* use vantage point to pull clients and vision projects ([c62fdb2](https://github.com/Bolton-and-Menk/geocp-projects/commit/c62fdb20bbc62498a71ff22fa5f417bc90004286))

### [0.1.26](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.25...v0.1.26) (2022-08-11)


### Features

* show public user editing warnings ([1a302e0](https://github.com/Bolton-and-Menk/geocp-projects/commit/1a302e06a42bef2a5876864680c39660a0ccc18f))

### [0.1.25](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.24...v0.1.25) (2022-08-01)


### Bug Fixes

* **create-project:** improved project number parser ([f88ee98](https://github.com/Bolton-and-Menk/geocp-projects/commit/f88ee9815693919e2ef280a26cb13c9242c87611))

### [0.1.24](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.23...v0.1.24) (2022-07-27)
### Features

* emit theme changed event ([bb20777](https://github.com/Bolton-and-Menk/geocp-projects/commit/bb207778398bc6c12985582c9495fd1d34dae19b))


### Bug Fixes

* fixed basemap switching bug on theme switch ([0bee9c3](https://github.com/Bolton-and-Menk/geocp-projects/commit/0bee9c38160ef11f40c7775058fa29677f5c9829))

* remove duplicate photo tags from open asset ([c829349](https://github.com/Bolton-and-Menk/geocp-projects/commit/c82934971c274abe32da9b6bb5f563a529faa154))


### [0.1.23](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.22...v0.1.23) (2022-07-20)


### Bug Fixes

* **map-view:** fixed empty basemap bug from user preferences ([1e023a9](https://github.com/Bolton-and-Menk/geocp-projects/commit/1e023a974cd2b4f509d07cf5225a4e01ff7796de))

### [0.1.22](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.21...v0.1.22) (2022-07-18)


### Features

* **home:** make project list overflow option config driven ([f4f8394](https://github.com/Bolton-and-Menk/geocp-projects/commit/f4f8394e7a42aed6f86f592a7cdc79e19ed94c03))


### Bug Fixes

* **flask:** clear user session on failed token refresh ([968ff31](https://github.com/Bolton-and-Menk/geocp-projects/commit/968ff3179a1b3d2e50b3f222698f9e43eba071c7))
* **home:** fix filter bug on determining to show only my projects ([442100d](https://github.com/Bolton-and-Menk/geocp-projects/commit/442100d92e1169678ea007eb2e51b77800114c54))

### [0.1.21](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.20...v0.1.21) (2022-07-14)


### Features

* **action-panel:** added link to help page ([3c4be41](https://github.com/Bolton-and-Menk/geocp-projects/commit/3c4be4136a76f1a6590b94acba0febd249a032a3))
* added help guide content ([54c8d62](https://github.com/Bolton-and-Menk/geocp-projects/commit/54c8d6270f84f528eb98741dd3f741b1641bd47d))
* added help guide content ([2fb092e](https://github.com/Bolton-and-Menk/geocp-projects/commit/2fb092e29350b18dd2256b4d7f103e2ff5ac4178))

### [0.1.20](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.19...v0.1.20) (2022-07-12)


### Features

* inceased banner preview size for create project ([487018c](https://github.com/Bolton-and-Menk/geocp-projects/commit/487018c7280b2dda0d34345adc0a57c0ed1f5ea0))
* **user-info:** show public view context info ([18ef2ab](https://github.com/Bolton-and-Menk/geocp-projects/commit/18ef2abd14fb7c4b381f8e8b1e280ec12d4a21b4))


### Bug Fixes

* **create-project:** fix bug with resetting form after project is submitted ([2f2fdac](https://github.com/Bolton-and-Menk/geocp-projects/commit/2f2fdac174fc0735220af49def96b6824715f289))

### [0.1.19](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.18...v0.1.19) (2022-07-08)


### Bug Fixes

* fixed image details url source ([eb22c67](https://github.com/Bolton-and-Menk/geocp-projects/commit/eb22c67998f850c711289b3245f24536441c37b2))
* fixed user profile state bug ([f5ae3af](https://github.com/Bolton-and-Menk/geocp-projects/commit/f5ae3afa0c4450ba8f2e9d56bfbec75e670c7402))

### [0.1.18](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.17...v0.1.18) (2022-07-07)


### Features

* **action-pandel:** allow user to view changelog, submit issue or enhancement ([aa6a6b2](https://github.com/Bolton-and-Menk/geocp-projects/commit/aa6a6b2006f4fc59e2fabe2c1ecdfaf3c8ce6079))

### [0.1.17](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.16...v0.1.17) (2022-07-07)


### Features

* scroll to thumbnail when clicking on map ([4c68698](https://github.com/Bolton-and-Menk/geocp-projects/commit/4c686985f1ccdb419a6f00239e27d0a4ce921d2a))

### [0.1.16](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.15...v0.1.16) (2022-07-05)


### Features

* make flask environment configurable ([dc8daa3](https://github.com/Bolton-and-Menk/geocp-projects/commit/dc8daa3b5fca504c54d7f8402d0dc0e76e707a1d))

### [0.1.15](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.14...v0.1.15) (2022-06-23)


### Features

* allow user to toggle photo direction symbols and clustering ([f3bc06e](https://github.com/Bolton-and-Menk/geocp-projects/commit/f3bc06ed3398bf9618f8e04b28a4c8fb55feec91))
* **create-project:** convert unc paths to mapped folder drives (panzura only) ([ee5f7d6](https://github.com/Bolton-and-Menk/geocp-projects/commit/ee5f7d60c17dcea8c448047ea63573e07bac7ea6))

### [0.1.14](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.13...v0.1.14) (2022-06-20)


### Features

* **create-project:** get list of matching project names by given project number ([cb637ba](https://github.com/Bolton-and-Menk/geocp-projects/commit/cb637bacc7288902b78722dade3316ee03cb3506))

### [0.1.13](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.12...v0.1.13) (2022-06-10)


### Features

* **map:** make basemap widget configurable ([f9fbb81](https://github.com/Bolton-and-Menk/geocp-projects/commit/f9fbb81b29dd97269540c1369fd67f34a4f21390))


### Bug Fixes

* fixed public token parser ([2a894b2](https://github.com/Bolton-and-Menk/geocp-projects/commit/2a894b21c75526207710439fdae353786ec5e177))
* make project description optional ([f57f247](https://github.com/Bolton-and-Menk/geocp-projects/commit/f57f24725d0f94ebc5d7f10fe9acbb0af4cdd4bc))
* **thumbnail-view:** do not let public users set image locations with missing gps ([3fb3027](https://github.com/Bolton-and-Menk/geocp-projects/commit/3fb30273f1e45867759aab57ce9d46d125076b90))

### [0.1.12](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.11...v0.1.12) (2022-06-10)


### Features

* **auth:** support refreshing session and improved auth manager ([0c1ec34](https://github.com/Bolton-and-Menk/geocp-projects/commit/0c1ec3407892a5cca993586da3d9446fc4056023))
* **project-card:** added quick action buttons ([a2285c6](https://github.com/Bolton-and-Menk/geocp-projects/commit/a2285c6e447457aacf06d565bd086f7310779c5d))
* **thumbnail-view:** support adding location for photos with missing gps info ([8b8db49](https://github.com/Bolton-and-Menk/geocp-projects/commit/8b8db490230336011ffccde67f24fb0e652c0f3a))


### Bug Fixes

* fixed race condition on restoring auth session ([8ed0b59](https://github.com/Bolton-and-Menk/geocp-projects/commit/8ed0b5940f67355ce32d63f8d6d9ea9450d64fb0))
* **photo-viewer:** hide loader when project has been loaded ([e1846bd](https://github.com/Bolton-and-Menk/geocp-projects/commit/e1846bd13f6f8f63a7a342273519840c48a8fdf8))

### [0.1.11](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.10...v0.1.11) (2022-06-02)


### Features

* support shapefile exports ([fe3487e](https://github.com/Bolton-and-Menk/geocp-projects/commit/fe3487ef22c3da006c327571ca6bfb5588ebc933))

### [0.1.10](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.9...v0.1.10) (2022-05-25)


### Features

* integrate tags with openasset ([6d9cf41](https://github.com/Bolton-and-Menk/geocp-projects/commit/6d9cf41a7134a6d2aedc6c1c984ac94b7d06fb46))
* **project-info:** validate form immediately ([f6a400a](https://github.com/Bolton-and-Menk/geocp-projects/commit/f6a400a2a3002124502b5ae96028a7b6bb483801))
* sort tags alphabetically ([7dd5c92](https://github.com/Bolton-and-Menk/geocp-projects/commit/7dd5c92c4f7e17ed7eba49d103dbab7bfcea44fb))


### Bug Fixes

* broken public link from project card ([fc6d7d7](https://github.com/Bolton-and-Menk/geocp-projects/commit/fc6d7d7c9b42b5279fba6c9c02e7321a9b3b81a5))
* load all projects when user logs in after using public access token ([2cc1bbb](https://github.com/Bolton-and-Menk/geocp-projects/commit/2cc1bbb9df1c07fba5d0a613ce2c5a803e62586a))

### [0.1.9](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.7...v0.1.9) (2022-05-20)


### Features

* **image-details:** open full image in new tab when clicking on image ([d4df2c6](https://github.com/Bolton-and-Menk/geocp-projects/commit/d4df2c69411595de26f48dffd55097e763c94c04))
* improved mobile responsive design ([cdfdb5b](https://github.com/Bolton-and-Menk/geocp-projects/commit/cdfdb5b3f814fe737f5d5609baff99c369bc3644))
* show version history when clicking on version number ([ecf276e](https://github.com/Bolton-and-Menk/geocp-projects/commit/ecf276eb9fd4fe5b95480a0a8d9f7de21ff2574b))
* use tabbed view for project home on mobile ([7e25187](https://github.com/Bolton-and-Menk/geocp-projects/commit/7e25187e3bb50baf8eebde0f668ea163bf4842a7))

### 0.1.8 (2022-05-20)

### [0.1.7](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.6...v0.1.7) (2022-05-19)


### Features

* check for image tags on image details ([b561684](https://github.com/Bolton-and-Menk/geocp-projects/commit/b561684e4c556c98301157cb9f1cbdbb5625ca75))
* improved performance for loading public viewer photos ([a83f782](https://github.com/Bolton-and-Menk/geocp-projects/commit/a83f782b68ab7b19cb86beb7ff82e13c6df8f8ad))
* **popup:** added open image details action ([40b4a4a](https://github.com/Bolton-and-Menk/geocp-projects/commit/40b4a4a6472bbda273d38501f9e61ac419ae5bd4))


### Bug Fixes

* **app:** also set user info on auth manager ready ([d31cdda](https://github.com/Bolton-and-Menk/geocp-projects/commit/d31cdda526bba1965566e4a6fc85e30af4083b7a))
* **flask:** fixed race condition for auth manager ready ([3549949](https://github.com/Bolton-and-Menk/geocp-projects/commit/3549949b1c3c4fdb753b8ceb857c510509c1f0f3))
* **image-tags:** fixed image tag readonly bug ([54bc71d](https://github.com/Bolton-and-Menk/geocp-projects/commit/54bc71d6cbf93eeebd8a02bea7c43189ac966a25))
* use login status to set tag editability ([bf16831](https://github.com/Bolton-and-Menk/geocp-projects/commit/bf168317ede119a461988b5fae7a08e25b21719c))

### [0.1.6](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.5...v0.1.6) (2022-05-19)


### Features

* use config file ([ff59d23](https://github.com/Bolton-and-Menk/geocp-projects/commit/ff59d23a0dbf7ad6a55bfb12bebbcc5ae7ee1d4c))

### [0.1.5](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.4...v0.1.5) (2022-05-19)


### Bug Fixes

* missing photo tag filters for public viewer ([c410834](https://github.com/Bolton-and-Menk/geocp-projects/commit/c4108349832ffa5a4a3fccea4daab9c435f30677))

### [0.1.4](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.3...v0.1.4) (2022-05-17)


### Features

* **bmi-flask2:** improve local storage caching ([9785965](https://github.com/Bolton-and-Menk/geocp-projects/commit/978596594341196498447c5d0ce672db5ae6c076))
* enabled public viewing functionality ([1288e75](https://github.com/Bolton-and-Menk/geocp-projects/commit/1288e755ea7c52f9ae88786c68c5ba2c5246b66a))

### [0.1.3](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.0-beta.0...v0.1.3) (2022-05-12)


### Features

* added project sync feature ([ff3a3f9](https://github.com/Bolton-and-Menk/geocp-projects/commit/ff3a3f92108bb0feafa7a36b7adaa2b4dcda568d))
* **image-gallery:** show loader while images are still loading ([528d378](https://github.com/Bolton-and-Menk/geocp-projects/commit/528d3780d6a7cc73f5e5849fd138ac44d036a13a))
* **project-home:** add project filtering capabilities ([8e0942e](https://github.com/Bolton-and-Menk/geocp-projects/commit/8e0942ee3dee14bf0135009e539221fc55f3d474))
* support the ability to batch tag images ([258494e](https://github.com/Bolton-and-Menk/geocp-projects/commit/258494e4ef7f3d558d4acda2007f2cd4c357648b))


### Bug Fixes

* **photo-viewer:** fixed photo viewer stale state bug ([038d3ae](https://github.com/Bolton-and-Menk/geocp-projects/commit/038d3ae75fac6bf1ddca5e55a4ee2893f7be134d))
* **property-filter:** model dropdowns when filter is reopened ([413f01b](https://github.com/Bolton-and-Menk/geocp-projects/commit/413f01bd38f73f193487ea03344b584175bf0af8))

## [0.1.0-beta.0](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.1.0-alpha.0...v0.1.0-beta.0) (2022-05-06)


### Features

* **create-project:** improved invalid folder handlers ([1c0ae30](https://github.com/Bolton-and-Menk/geocp-projects/commit/1c0ae3076291ffba21ac7595a14292e6183f70e6))
* **filters:** apply filters to mapped features ([72759c5](https://github.com/Bolton-and-Menk/geocp-projects/commit/72759c5839dce495493f9bb1ca8fabbffd43e743))
* **filters:** filter based on location information ([9e7fd8e](https://github.com/Bolton-and-Menk/geocp-projects/commit/9e7fd8e02df5d9e0ac963626abf015d37da18352))
* **image-details:** add icons for date and camera ([5672818](https://github.com/Bolton-and-Menk/geocp-projects/commit/56728181df8876ace2d635d6ea618dc0ef131f3a))
* **image-details:** use direction icon ([7d60be6](https://github.com/Bolton-and-Menk/geocp-projects/commit/7d60be632622f3015e7a8a9e25b114299d55ab9f))
* **map-view:** show views and web view fields ([46e5c3b](https://github.com/Bolton-and-Menk/geocp-projects/commit/46e5c3b3b17805089f1a265da7429e2d49f258c5))
* **mapping:** improved user experience for zooming to points ([fa72c7f](https://github.com/Bolton-and-Menk/geocp-projects/commit/fa72c7f89f25fb41176c6c120e5f253b02d9f3e0))
* **project-details:** update cached project list after updates ([7808c7f](https://github.com/Bolton-and-Menk/geocp-projects/commit/7808c7f876c3a29d3e5029c3f9cdc82b2fda2197))
* **project-home:** filter by dates and photo properties ([366b288](https://github.com/Bolton-and-Menk/geocp-projects/commit/366b288df8d49f598b09eef4cdcdbbcc2740a08f))
* **project-home:** show floating remove filter button when filter is active ([c333c61](https://github.com/Bolton-and-Menk/geocp-projects/commit/c333c61e23b709bea42716b59d02f969abeceb23))
* **thumbnails:** show different icons based on location availability ([4bf7258](https://github.com/Bolton-and-Menk/geocp-projects/commit/4bf72587612183a17f1d53e86fe082536ead985d))


### Bug Fixes

* **filters:** dropdowns bug on change field ([51f58f4](https://github.com/Bolton-and-Menk/geocp-projects/commit/51f58f420385d056d8b1a77c0b49c4474ec1c93c))
* **filters:** fixed numeric as string bug ([663653a](https://github.com/Bolton-and-Menk/geocp-projects/commit/663653a01888fc8770825f89f0231a985518aaaa))
* **filters:** fixed time filter bug ([7fef16b](https://github.com/Bolton-and-Menk/geocp-projects/commit/7fef16b64a11c595f8d474131af6441f5835746c))
* **project-home:** fix project loading bug ([aa2d380](https://github.com/Bolton-and-Menk/geocp-projects/commit/aa2d3808f10805da3405004a7f5377427cf4efa4))
* **utils:** use openasset urls ([6504524](https://github.com/Bolton-and-Menk/geocp-projects/commit/65045241e4b120e0ff69793bcefe2131ddaa5770))

## [0.1.0-alpha.0](https://github.com/Bolton-and-Menk/geocp-projects/compare/v0.0.1-alpha.0...v0.1.0-alpha.0) (2022-04-29)


### Features

* **action-panel:** added link to project details ([7351756](https://github.com/Bolton-and-Menk/geocp-projects/commit/7351756dae2091d128767d49677a312bb6c677e1))
* added favicon and logo ([83ee53c](https://github.com/Bolton-and-Menk/geocp-projects/commit/83ee53ce2f754a4dcdea4c67473bf1ca99fd7d60))
* added project details page ([3762a47](https://github.com/Bolton-and-Menk/geocp-projects/commit/3762a47ac71a7e3ea7f5c7b103fb1df967beaecd))
* autofill project properties based on project number ([6098407](https://github.com/Bolton-and-Menk/geocp-projects/commit/6098407776b39c48b3e708cbf3e334eb531c4076))
* **create-project:** show preview for file uploads ([c28221e](https://github.com/Bolton-and-Menk/geocp-projects/commit/c28221e9af04523735594e5923cb9cbcfd0db89e))
* improve app loading flow ([8fc65a4](https://github.com/Bolton-and-Menk/geocp-projects/commit/8fc65a4f895d5b021e8c7c74e498bd3b4cd54311))
* **navbar:** show app version ([81207d3](https://github.com/Bolton-and-Menk/geocp-projects/commit/81207d3f178dcd22a1bcf81574219f59e6c64309))
* **project-card:** show thousands separator for photo and views count ([35bc5a2](https://github.com/Bolton-and-Menk/geocp-projects/commit/35bc5a2f40ad953eac9aa749da02a303ff7553e9))
* **router:** load project before navigating to all project routes ([100a4de](https://github.com/Bolton-and-Menk/geocp-projects/commit/100a4dec3d35569104d67659178ea1b541a374ec))


### Bug Fixes

* **create-project:** reset form after creation ([017d62b](https://github.com/Bolton-and-Menk/geocp-projects/commit/017d62b1477526d7724caa803b7fde88b77e8c79))
* use standalone notify in project utils ([ddb3e78](https://github.com/Bolton-and-Menk/geocp-projects/commit/ddb3e78b2c62b6fa643d1459301dacb267f8d607))

### 0.0.1-alpha.0 (2022-04-25)


### Features

* **action-panel:** add project actions ([7d8bebc](https://github.com/Bolton-and-Menk/geocp-projects/commit/7d8bebc5f50957054936dd8d753bd200781de5cc))
* **action-panel:** added project view link ([208c09f](https://github.com/Bolton-and-Menk/geocp-projects/commit/208c09fd512ee3f19293ba8c3662554cabfddb15))
* add image gallery skeleton while project loads ([2a8083f](https://github.com/Bolton-and-Menk/geocp-projects/commit/2a8083fb41ac26a64635a83e65ad54e2042cdd50))
* added loading route ([80bb866](https://github.com/Bolton-and-Menk/geocp-projects/commit/80bb86653c894a34945b729e423fdd42bdba3fc3))
* **auth:** added login page ([f4cc13d](https://github.com/Bolton-and-Menk/geocp-projects/commit/f4cc13d3589b35134895a1056ec504b4a7e21edd))
* autofill client and project number when possible ([04bf0d2](https://github.com/Bolton-and-Menk/geocp-projects/commit/04bf0d27c4a2b91cd9560af17c8405b265d168d0))
* **create-project:** show banner preview ([6f72086](https://github.com/Bolton-and-Menk/geocp-projects/commit/6f720860226dec55f6efb60cc4171d1e3b955225))
* **events:** expose image details update event ([dcfeac6](https://github.com/Bolton-and-Menk/geocp-projects/commit/dcfeac6bc5699ab11d2a546d6f339ff7fc588797))
* getters for image urls ([f8ceb13](https://github.com/Bolton-and-Menk/geocp-projects/commit/f8ceb136c10aacf462c1f5bc71f3391f1bbbec06))
* image details tooltip ([1a15fc5](https://github.com/Bolton-and-Menk/geocp-projects/commit/1a15fc5fedf63453472a333b32ea61647e22dacb))
* **image-gallery:** show folder structure ([44cce55](https://github.com/Bolton-and-Menk/geocp-projects/commit/44cce55fd8434e44227ae234be2be66acd9baf99))
* immediately load map and fetch geojson later ([c055299](https://github.com/Bolton-and-Menk/geocp-projects/commit/c055299979df2d82a53ccf37408bef63fb343f28))
* improved initial load performance ([823a6e9](https://github.com/Bolton-and-Menk/geocp-projects/commit/823a6e974e5ba1a3459b563aa38960fed4ddb0f1))
* improved user settings cache ([f71ee1f](https://github.com/Bolton-and-Menk/geocp-projects/commit/f71ee1fac71f90dfe7b654ad955bad38dbbde1e5))
* large image preview ([243bda6](https://github.com/Bolton-and-Menk/geocp-projects/commit/243bda6d55c1703cb987d6074b76c96a27182f76))
* **login-page:** add spinner on login button ([cc19bc0](https://github.com/Bolton-and-Menk/geocp-projects/commit/cc19bc00c2c240fe11fed7781912478ee7cab9eb))
* **projectStore:** enable cache bust for banner images ([208c166](https://github.com/Bolton-and-Menk/geocp-projects/commit/208c166e33ea812ee9b8b3176f1361c5c85fc69f))
* **projectStore:** enable daily cache bust for banner images ([32f1fa0](https://github.com/Bolton-and-Menk/geocp-projects/commit/32f1fa059043645c957876162b069e266c1fd1c5))
* **router:** added authentication check navigation gaurd ([ac2d74a](https://github.com/Bolton-and-Menk/geocp-projects/commit/ac2d74a1bff51bca2fec91ef727e18c00975f481))
* show project and image views ([b9988f9](https://github.com/Bolton-and-Menk/geocp-projects/commit/b9988f947ce59a5735fb1a331073ce728d1b8237))
* store user preferences for session ([e63bec5](https://github.com/Bolton-and-Menk/geocp-projects/commit/e63bec5d434bf4cef7217c46230a73c5a57c5684))
* store user preferences for session ([85a1a70](https://github.com/Bolton-and-Menk/geocp-projects/commit/85a1a70a1b2352a37becac668d5dd02c90b99930))
* support creating new projects ([1bdf78e](https://github.com/Bolton-and-Menk/geocp-projects/commit/1bdf78ea24641b16737cf5e901bbd8a1abc24a5d))
* support creating projects ([a6afde3](https://github.com/Bolton-and-Menk/geocp-projects/commit/a6afde3ed9809927a160ae05a66a9d708468a16d))
* support image description edits and tagging ([0ad3bfb](https://github.com/Bolton-and-Menk/geocp-projects/commit/0ad3bfb90132887cc8cdbea2de9fe30e4d80b1f7))
* sync mapview location with thumbnail events ([a4829e6](https://github.com/Bolton-and-Menk/geocp-projects/commit/a4829e658ae41bfdcb4ab227816f3e308a75ae4c))
* **utils:** add file preview for uploading ([0575059](https://github.com/Bolton-and-Menk/geocp-projects/commit/0575059ee201d685b341a6652f7621e842170136))


### Bug Fixes

* **action-panel:** only show project actions based on current route ([61e5a21](https://github.com/Bolton-and-Menk/geocp-projects/commit/61e5a21dd2fab57121fb8acfb9669e9c446b3062))
* bad import ([9d8b679](https://github.com/Bolton-and-Menk/geocp-projects/commit/9d8b679c1ba1499aae6ce9544af143c320c29c02))
* **dropzone:** emit files-dropped from file picker ([bd8bb59](https://github.com/Bolton-and-Menk/geocp-projects/commit/bd8bb59444ba8fca4f8ac630dd3a614e16bd04e0))
* fix project home navigation bug ([b17b943](https://github.com/Bolton-and-Menk/geocp-projects/commit/b17b943723c6c5daf14cffcfc279bfcf52f91c1d))
* format date for image details ([62ee260](https://github.com/Bolton-and-Menk/geocp-projects/commit/62ee260e6038921be6261ee8653446a946b32342))
* **ImageDetails:** photo ratio fix ([2c68580](https://github.com/Bolton-and-Menk/geocp-projects/commit/2c6858020ecba38bd01e486b88ea3902762e514a))
* **ImageDetails:** photo ratio fix ([b598b28](https://github.com/Bolton-and-Menk/geocp-projects/commit/b598b28d09441c7e1206eebdba0e187dced15da1))
* load user preferences after auth manager ([17323bb](https://github.com/Bolton-and-Menk/geocp-projects/commit/17323bbbd95889dd460c44d487c750a5392c961a))
