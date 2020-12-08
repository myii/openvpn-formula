# Changelog

## [1.15.1](https://github.com/myii/openvpn-formula/compare/v1.15.0...v1.15.1) (2020-12-08)


### Code Refactoring

* **gitlab-ci:** set final format before testing with other repos ([2f6f9c4](https://github.com/myii/openvpn-formula/commit/2f6f9c4443a0886ce759f21a34fe515abd574498))

# [1.15.0](https://github.com/myii/openvpn-formula/compare/v1.14.7...v1.15.0) (2020-12-07)


### Features

* **gitlab-ci:** use custom `commitlint` image ([c62f770](https://github.com/myii/openvpn-formula/commit/c62f770614a8cb0ac72a971f026b0b90ec4cbd50))
* **gitlab-ci:** use custom `dind-ruby` image ([3acc86c](https://github.com/myii/openvpn-formula/commit/3acc86c42aeb8a2f1a75fcbacdb56b389254cdf9))
* **gitlab-ci:** use custom `pre-commit` image ([0ffb4f3](https://github.com/myii/openvpn-formula/commit/0ffb4f32106defa2a7315fcb3f78f67900d8b768))
* **gitlab-ci:** use custom `semantic-release` image ([312e6db](https://github.com/myii/openvpn-formula/commit/312e6db5267ea7572a197414fac0ea7f657fe67e))

## [1.14.7](https://github.com/myii/openvpn-formula/compare/v1.14.6...v1.14.7) (2020-12-06)


### Code Refactoring

* **gitlab:** use `variables` for `MAINTAINER_TOKEN` ([f6990cc](https://github.com/myii/openvpn-formula/commit/f6990cc79cc9f1803402d5a3c22e13e9478f8a7f))

## [1.14.6](https://github.com/myii/openvpn-formula/compare/v1.14.5...v1.14.6) (2020-12-06)


### Bug Fixes

* **gitlab:** add caches where `npm install` is used ([0c34547](https://github.com/myii/openvpn-formula/commit/0c345475d0a0728b47f58824fd52423bcc50a7ea))

## [1.14.5](https://github.com/myii/openvpn-formula/compare/v1.14.4...v1.14.5) (2020-12-06)


### Bug Fixes

* **m2r:** move back to script so latest changelog is included ([de357c8](https://github.com/myii/openvpn-formula/commit/de357c8ff1fa416c8c19a1618c9bdad0350b312a))

## [1.14.4](https://github.com/myii/openvpn-formula/compare/v1.14.3...v1.14.4) (2020-12-06)


### Bug Fixes

* **m2r:** ensure `setuptools` & `wheel` available ([f80c334](https://github.com/myii/openvpn-formula/commit/f80c334ba219ac988009c0108c0f6ecc25c8ee7d))
* **m2r:** run in CI directly rather than via. `semantic-release` ([a764dfd](https://github.com/myii/openvpn-formula/commit/a764dfda4a4e168d3640b8e3f9a4c0f50b82843a))

## [1.14.3](https://github.com/myii/openvpn-formula/compare/v1.14.2...v1.14.3) (2020-12-06)


### Bug Fixes

* **pre-commit_semantic-release.sh:** install `m2r` without `sudo` ([e6ee33d](https://github.com/myii/openvpn-formula/commit/e6ee33d972cda933ae7e1814e131ed977fa7b180))

## [1.14.2](https://github.com/myii/openvpn-formula/compare/v1.14.1...v1.14.2) (2020-12-06)


### Bug Fixes

* **gitlab:** finalise `semantic-release` job ([916e2eb](https://github.com/myii/openvpn-formula/commit/916e2eb5b9614a967aa30bd3616ced56c40bebc7))


### Continuous Integration

* **github:** use official GitLab CI caching for `pre-commit` ([5ea7ed0](https://github.com/myii/openvpn-formula/commit/5ea7ed037ab1ab82d37e5826a4b2da962b4b6cc3))
* **gitlab:** add bundler caching for test jobs ([175561c](https://github.com/myii/openvpn-formula/commit/175561c935cd90029063539574bb5cf26ee9819c))
* **gitlab:** add pre-commit ([e9425f0](https://github.com/myii/openvpn-formula/commit/e9425f0f18a4798d90739504b1fe52b9f8b0abae))
* **gitlab:** finalise configuration ([84a9006](https://github.com/myii/openvpn-formula/commit/84a90067163f201e2a8ed9dd9a554802e9845c78))
* **gitlab:** fix `semantic-release` settings ([bc0eeb5](https://github.com/myii/openvpn-formula/commit/bc0eeb5d0f64d0d552429314143efc84d80d7fc5))
* **gitlab:** use `${CI_PROJECT_URL}` for `commitlint` ([74483ae](https://github.com/myii/openvpn-formula/commit/74483ae4bea6a7e8ba3318077568995499ae7086))

## [1.14.1](https://github.com/myii/openvpn-formula/compare/v1.14.0...v1.14.1) (2020-12-05)


### Bug Fixes

* **gitlab:** ensure changelog working as required ([228ae32](https://github.com/myii/openvpn-formula/commit/228ae327bf168b6662b50916cb0859bd6dad38f8))

# [1.14.0](https://github.com/myii/openvpn-formula/compare/v1.13.0...v1.14.0) (2020-12-05)


### Bug Fixes

* **adapters:** call `adapters.sls` in `init.sls` ([3ebcbe9](https://github.com/myii/openvpn-formula/commit/3ebcbe93f8245fb435c3e9af91853930683e16b1))
* **auth_nocache:** fix typo in client template ([c8f0971](https://github.com/myii/openvpn-formula/commit/c8f0971d148be9efb8405ff7eef5bbe4eeae9ea8)), closes [#125](https://github.com/myii/openvpn-formula/issues/125)
* **centos:** install OpenSSL on CentOS ([7e4c8d6](https://github.com/myii/openvpn-formula/commit/7e4c8d6719eff5610a55c04a5b042a44726d553d))
* **centos-6:** has only _one_ service 'openvpn' ([3d5723d](https://github.com/myii/openvpn-formula/commit/3d5723d385174b9b05d720112e4f4c35654dee58))
* **config:** configurable distinction between server and client services ([18c4c4a](https://github.com/myii/openvpn-formula/commit/18c4c4a11c98409ac3dba1ef0fc8b88785c853ba))
* **config:** script-security is a common option ([b1b482c](https://github.com/myii/openvpn-formula/commit/b1b482cda8867025a88ea4660e7cc59f792e0435))
* **config:** set tls-auth and tls-crypt independentyl of ta_content ([d3787b6](https://github.com/myii/openvpn-formula/commit/d3787b63d28fd11eb3692c75e312704d2a48f66c))
* **config:** sub-mappings for client and server ([b30b23d](https://github.com/myii/openvpn-formula/commit/b30b23dfdcb68a0f904c3a8643c7846d4b61b5f0))
* **config.sls:** fix `salt-lint` errors ([1b3f7f6](https://github.com/myii/openvpn-formula/commit/1b3f7f6aa70072f2c895c9430deaa6b05459c2ad))
* **debian-ish:** root owns the logs ([3276d3b](https://github.com/myii/openvpn-formula/commit/3276d3bc82499da9174d95d4bb8cdaa1fcd0e387))
* **dhparams:** allow generating Diffie Hellman parameters on Windows ([3802024](https://github.com/myii/openvpn-formula/commit/3802024a69d5e4008d192084d10858511f3dca4d))
* **fedora:** honor working directory & service name ([4f8e899](https://github.com/myii/openvpn-formula/commit/4f8e8992a8691d215d65fc1757cb66c3b4ca30bf))
* **freebsd:** load if_tap module ([d63581a](https://github.com/myii/openvpn-formula/commit/d63581a37a4033be2db886669401a1115bdf5c50))
* **gitlab:** use Travis instances ([44f6bc1](https://github.com/myii/openvpn-formula/commit/44f6bc1d04afa98fd6f77a9b36b83165ec910d31))
* **ifconfig_pool_persist.sls:** fix `salt-lint` errors ([6969083](https://github.com/myii/openvpn-formula/commit/6969083052cf6c35f1f0decddb8917fe385438e7))
* **jinja:** don't call pillar.get ([33b98f5](https://github.com/myii/openvpn-formula/commit/33b98f53cb4d235235b4ecbfcad4181b1e2df14e))
* **logging:** set replace=False and add dependencies for log files ([9b71fcf](https://github.com/myii/openvpn-formula/commit/9b71fcfb3eeff41745000d71a385c71fd85cceab))
* **macros:** use openvpn/macros.jinja ([637387e](https://github.com/myii/openvpn-formula/commit/637387ec5d15917708c5ccb71b947c73df2e870c))
* **map.jinja:** fix `salt-lint` errors ([eabfc57](https://github.com/myii/openvpn-formula/commit/eabfc57ea9794c351e120d9b7b6d469d50008597))
* **network_manager_networks:** properly override port ([1d58ec6](https://github.com/myii/openvpn-formula/commit/1d58ec6d708a80066e7334505a0fc07cb8d3c607))
* **network_manager_networks:** reduced pillar.get calls ([7ee9eed](https://github.com/myii/openvpn-formula/commit/7ee9eed4f2cb0fd0a260e5c5f99eabfadd0432c4))
* **release.config.js:** use full commit hash in commit link [skip ci] ([81d922d](https://github.com/myii/openvpn-formula/commit/81d922d7a3053c309e0e8f965825063df576921e))
* **repo:** provide EPEL repo configuration for `Amazon Linux-2` ([bfb29bd](https://github.com/myii/openvpn-formula/commit/bfb29bd57fc74907bd6eeb8899cc8ec2f2d856ec))
* **service:** make sure the now obsolete systemd services are disabled ([2dfae46](https://github.com/myii/openvpn-formula/commit/2dfae465fc87ba06f37710f919bdaf3ce18732c9))
* **service:** removed trailing whitespace ([85d2458](https://github.com/myii/openvpn-formula/commit/85d24580c6ad68c8d6f9db5bc47fa52674989773))
* **service:** stop old service only if name is different to new service ([1724dfd](https://github.com/myii/openvpn-formula/commit/1724dfd683d2d2d9c1d0e1a37f31123a922fda03)), closes [#119](https://github.com/myii/openvpn-formula/issues/119)
* **service:** use OS-specific service name in multi-service setups ([b16756c](https://github.com/myii/openvpn-formula/commit/b16756cb018baed16fe45df0645d4f7c92ed7a6f))
* **specs:** use boolean operator ([89fa956](https://github.com/myii/openvpn-formula/commit/89fa95614cf07d4fa0ec174ee9665673dc3ad325))
* **tap-adapter.ps1:** work with alternate name `Local Area Connection` ([372b3b6](https://github.com/myii/openvpn-formula/commit/372b3b6d80ef5ede742961bca44d726d16249646))
* **test:** drop ' then$' ([62c2f70](https://github.com/myii/openvpn-formula/commit/62c2f70b92bbbbc4991009a39c48fd89a47bf561))
* **test:** dropped redundant permission checks ([9c3ea71](https://github.com/myii/openvpn-formula/commit/9c3ea716042a2e00fba7c2bcfac78e8ecbbda188))


### Continuous Integration

* **cleanup:** dropped obsolete opensuse-leap-15 workaround ([1e1719d](https://github.com/myii/openvpn-formula/commit/1e1719d84d7149dd3d83e07d8331dce55b9d8398))
* **gemfile:** restrict `train` gem version until upstream fix [skip ci] ([ed6b7f0](https://github.com/myii/openvpn-formula/commit/ed6b7f0c0d6a9171eadca2ffbc3682e24a3e346b))
* **gemfile.lock:** add to repo with updated `Gemfile` [skip ci] ([0aa9fd6](https://github.com/myii/openvpn-formula/commit/0aa9fd6d93533d824f4c6d144474d6721dd1bca6))
* **github:** add Windows testing using Actions ([2d4b79c](https://github.com/myii/openvpn-formula/commit/2d4b79c5f8afe73eeeef187e63d9613bbf7bd793))
* **gitlab:** test `semantic-release` back to GitHub ([0ead7f1](https://github.com/myii/openvpn-formula/commit/0ead7f18b3b5b34ea328c448cb296f6f5962474e))
* **gitlab:** use GitLab CI as Travis CI replacement ([c9e4a8c](https://github.com/myii/openvpn-formula/commit/c9e4a8cbdf778ba3dd91b3a9c98b6e97a7b8cf24))
* **kitchen:** add kitchen file + testinfra ([9c5ee26](https://github.com/myii/openvpn-formula/commit/9c5ee269dd9a5ee40cd69a30ab1903ad430aebdb))
* **kitchen:** avoid using bootstrap for `master` instances [skip ci] ([6eb1b44](https://github.com/myii/openvpn-formula/commit/6eb1b4437df9e2b8bb3171f8811bcf1d091113d9))
* **kitchen:** change `log_level` to `debug` instead of `info` ([e94c9ba](https://github.com/myii/openvpn-formula/commit/e94c9ba56865333e8ec848f9fbcebbab72910932))
* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([b76dcc9](https://github.com/myii/openvpn-formula/commit/b76dcc9d737286202280525012181e971bbafb9d))
* **kitchen:** rename pillar ([4122fc0](https://github.com/myii/openvpn-formula/commit/4122fc0e02715959a219c2217e5d4cdaae265cfe))
* **kitchen:** test/config/pillars: add jinja for user on debian >= 9 ([3c7f947](https://github.com/myii/openvpn-formula/commit/3c7f947a94c2d043f9c36bfc882b1f36aedaa873))
* **kitchen:** use `debian-10-master-py3` instead of `develop` [skip ci] ([83e00e1](https://github.com/myii/openvpn-formula/commit/83e00e1c4d64e86f79b2fa9cb6e8be0490cdb83e))
* **kitchen:** use `develop` image until `master` is ready (`amazonlinux`) [skip ci] ([06a09f2](https://github.com/myii/openvpn-formula/commit/06a09f29e187f9b01865b582eff944c30e294302))
* **kitchen:** use `saltimages` Docker Hub where available [skip ci] ([740ba4e](https://github.com/myii/openvpn-formula/commit/740ba4e80e01a724b7833ee6b3d7e66740ced795))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([0db9651](https://github.com/myii/openvpn-formula/commit/0db9651a1a10f16ec7babed8c5031d925b84be12))
* **kitchen+travis:** modify matrix to include `develop` platform ([91b5798](https://github.com/myii/openvpn-formula/commit/91b579823fab95bc6148aa7084f48e1f8f08764e))
* **kitchen+travis:** remove `master-py2-arch-base-latest` [skip ci] ([9e7aa34](https://github.com/myii/openvpn-formula/commit/9e7aa34a499b30eab737295ae4649e510365deab))
* **kitchen+travis:** replace EOL pre-salted images ([2577535](https://github.com/myii/openvpn-formula/commit/25775355c11cec61ec58dee9a1459f6a97cbfc66))
* **kitchen+travis:** upgrade matrix after `2019.2.2` release [skip ci] ([4eb9d3b](https://github.com/myii/openvpn-formula/commit/4eb9d3bed2df51360822db639c2085414bfc13e3))
* **platform:** add `arch-base-latest` (commented out for now) [skip ci] ([75d7aaa](https://github.com/myii/openvpn-formula/commit/75d7aaae13bc721f0c3bc3dd391b4b13564c425f))
* **pre-commit:** add to formula [skip ci] ([95bbd5e](https://github.com/myii/openvpn-formula/commit/95bbd5eee34dd7ae36642ea38f2fc388c385cb30))
* **pre-commit:** enable/disable `rstcheck` as relevant [skip ci] ([92e02f2](https://github.com/myii/openvpn-formula/commit/92e02f2b549ed599786bb08562dc4bc60df84c49))
* **pre-commit:** finalise `rstcheck` configuration [skip ci] ([44e040d](https://github.com/myii/openvpn-formula/commit/44e040d3a143c7d3a2ad6805ae1f42e261bb7f32))
* avoid `init_environment` failing due to saltstack/salt[#57628](https://github.com/myii/openvpn-formula/issues/57628) ([398932b](https://github.com/myii/openvpn-formula/commit/398932b8332b701b6a1430018629d097b2f41155))
* **specs:** increased readability ([b2c9cf1](https://github.com/myii/openvpn-formula/commit/b2c9cf165ae0ad63d745533704d7c0be74540c60))
* **test data:** moved Pillar test data ([2fff1ee](https://github.com/myii/openvpn-formula/commit/2fff1eeb9a7e77b45b7f69f6a2799a650d90b923))
* **testing:** added bin/kitchen ([15bea7b](https://github.com/myii/openvpn-formula/commit/15bea7b1755ec334c1a0d91a3f7c0827321a4b94))
* **travis:** add notifications => zulip [skip ci] ([80930cd](https://github.com/myii/openvpn-formula/commit/80930cdb479fb9f2eef7a0044b93e08fabb1d804))
* **travis:** apply changes from build config validation [skip ci] ([ea3336a](https://github.com/myii/openvpn-formula/commit/ea3336af6f3657d24c0657173f07ed224140a46b))
* **travis:** exclude Fedora 29 from Travis CI ([4a1f9ed](https://github.com/myii/openvpn-formula/commit/4a1f9ed11112ee3ce2dd483bde1a83caa1a22794))
* **travis:** merge `rubocop` linter into main `lint` job ([9f82955](https://github.com/myii/openvpn-formula/commit/9f82955081169661780b8a236c1b20da15bf9aa2))
* **travis:** opt-in to `dpl v2` to complete build config validation [skip ci] ([bb43f31](https://github.com/myii/openvpn-formula/commit/bb43f31450ccb48601ef61620a42c9904c502e0d))
* **travis:** quote pathspecs used with `git ls-files` [skip ci] ([667bc1f](https://github.com/myii/openvpn-formula/commit/667bc1f04b7e96bd2c5cdce8a91d76552d34c884))
* **travis:** run `shellcheck` during lint job [skip ci] ([9d63e36](https://github.com/myii/openvpn-formula/commit/9d63e36fa618df6d966ad1278bfa64153db0a9fe))
* **travis:** test based on template-formula and [#98](https://github.com/myii/openvpn-formula/issues/98) ([b9daf9b](https://github.com/myii/openvpn-formula/commit/b9daf9bb06b9f6c9b89adcfa7b26845a9f3493bb))
* **travis:** update `salt-lint` config for `v0.0.10` [skip ci] ([d465b4f](https://github.com/myii/openvpn-formula/commit/d465b4f6063ab78864cf2f25a26c339e74b64c18))
* **travis:** use `major.minor` for `semantic-release` version [skip ci] ([4099f15](https://github.com/myii/openvpn-formula/commit/4099f15a1440bf7d9dfde707137593d9cf495d02))
* **travis:** use build config validation (beta) [skip ci] ([d2f7fe2](https://github.com/myii/openvpn-formula/commit/d2f7fe24a19033b8db907be89f184b26b128b326))
* **workflows/commitlint:** add to repo [skip ci] ([5900915](https://github.com/myii/openvpn-formula/commit/5900915e5b86cdad1fdca9163873e1fd9ee44f98))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([d7f1607](https://github.com/myii/openvpn-formula/commit/d7f1607118c007de79be0fe64be9506079d5240f))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([70dab6c](https://github.com/myii/openvpn-formula/commit/70dab6c4ee9d9d69f80c81ae314df0d97c79114e))
* **yamllint:** add rule `empty-values` & use new `yaml-files` setting ([a437b3b](https://github.com/myii/openvpn-formula/commit/a437b3b4e04267f7b8eeb5bd47509fa5b51d85f7))
* use `dist: bionic` & apply `opensuse-leap-15` SCP error workaround ([5e02797](https://github.com/myii/openvpn-formula/commit/5e02797e8d4ba6257838d3b1b2f63c9ac6128213))


### Documentation

* add steps required for testing using Vagrant ([0229d14](https://github.com/myii/openvpn-formula/commit/0229d1446f89d0ebe44f70b1834a0a9aa8cb68e1))
* **contributing:** remove to use org-level file instead [skip ci] ([8703eb5](https://github.com/myii/openvpn-formula/commit/8703eb50a6ea7505716b2350e34b88f894a4e725))
* **pillar.example:** update with quoted "yes" for comp-lzo ([1b49b24](https://github.com/myii/openvpn-formula/commit/1b49b24aa380edd52170b6234151dadf416f1a10))
* **readme:** update link to `CONTRIBUTING` [skip ci] ([a72049f](https://github.com/myii/openvpn-formula/commit/a72049f738005c95548db7e3b87847d8ce741eda))


### Features

* **auth_gen_token:** support for auth-gen-token ([333edd7](https://github.com/myii/openvpn-formula/commit/333edd7ac836b3e510124642df32361a548a6213))
* **auth_nocache:** support for auth-nocache ([c21b7f5](https://github.com/myii/openvpn-formula/commit/c21b7f52cc0ce24c96cf1b9173a9fda9e3eb7ae7))
* **syslog:** support for syslog ([24b370c](https://github.com/myii/openvpn-formula/commit/24b370ccac24a0905d00e1706db480878b400383))
* **yamllint:** include for this repo and apply rules throughout ([4355ac6](https://github.com/myii/openvpn-formula/commit/4355ac6413e0c3284fc2be08abb183552b3a2bf3))


### Performance Improvements

* **travis:** improve `salt-lint` invocation [skip ci] ([26838e5](https://github.com/myii/openvpn-formula/commit/26838e5ccd0400390bb3a2eb29741d36a8992ac3))


### Tests

* **map:** verify `map.jinja` dump using `_mapdata` state ([ecac1b1](https://github.com/myii/openvpn-formula/commit/ecac1b107f8a5309b803cb7fe41d1802b427b5fe))
* add test for auth-nocache option ([79c1055](https://github.com/myii/openvpn-formula/commit/79c10556dee2431d93ce9d678d002ec1036d219b))
* **kitchen:** debian and ubuntu use different paths now ([dfd784e](https://github.com/myii/openvpn-formula/commit/dfd784e3653dba1b26b055d2cf5afc80dc58a75f))
* **pillar:** set 'status' to fix kitchen tests ([07bb5b6](https://github.com/myii/openvpn-formula/commit/07bb5b63d454dd95b136b2dcabf7e9eda37b4112))
* **windows:** add local testing of Windows using Vagrant/Virtualbox ([96c3001](https://github.com/myii/openvpn-formula/commit/96c300125dfa86c67d14e09f772b453eddde7c84))

## [0.16.4](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.16.3...v0.16.4) (2020-10-30)


### Continuous Integration

* **kitchen:** use `saltimages` Docker Hub where available [skip ci] ([740ba4e](https://github.com/saltstack-formulas/openvpn-formula/commit/740ba4e80e01a724b7833ee6b3d7e66740ced795))
* **pre-commit:** add to formula [skip ci] ([95bbd5e](https://github.com/saltstack-formulas/openvpn-formula/commit/95bbd5eee34dd7ae36642ea38f2fc388c385cb30))
* **pre-commit:** enable/disable `rstcheck` as relevant [skip ci] ([92e02f2](https://github.com/saltstack-formulas/openvpn-formula/commit/92e02f2b549ed599786bb08562dc4bc60df84c49))
* **pre-commit:** finalise `rstcheck` configuration [skip ci] ([44e040d](https://github.com/saltstack-formulas/openvpn-formula/commit/44e040d3a143c7d3a2ad6805ae1f42e261bb7f32))
* avoid `init_environment` failing due to saltstack/salt[#57628](https://github.com/saltstack-formulas/openvpn-formula/issues/57628) ([398932b](https://github.com/saltstack-formulas/openvpn-formula/commit/398932b8332b701b6a1430018629d097b2f41155))


### Tests

* **map:** verify `map.jinja` dump using `_mapdata` state ([ecac1b1](https://github.com/saltstack-formulas/openvpn-formula/commit/ecac1b107f8a5309b803cb7fe41d1802b427b5fe))

## [0.16.3](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.16.2...v0.16.3) (2020-06-10)


### Bug Fixes

* **tap-adapter.ps1:** work with alternate name `Local Area Connection` ([372b3b6](https://github.com/saltstack-formulas/openvpn-formula/commit/372b3b6d80ef5ede742961bca44d726d16249646))


### Continuous Integration

* **gemfile.lock:** add to repo with updated `Gemfile` [skip ci] ([0aa9fd6](https://github.com/saltstack-formulas/openvpn-formula/commit/0aa9fd6d93533d824f4c6d144474d6721dd1bca6))
* **github:** add Windows testing using Actions ([2d4b79c](https://github.com/saltstack-formulas/openvpn-formula/commit/2d4b79c5f8afe73eeeef187e63d9613bbf7bd793))
* **kitchen:** avoid using bootstrap for `master` instances [skip ci] ([6eb1b44](https://github.com/saltstack-formulas/openvpn-formula/commit/6eb1b4437df9e2b8bb3171f8811bcf1d091113d9))
* **kitchen+travis:** remove `master-py2-arch-base-latest` [skip ci] ([9e7aa34](https://github.com/saltstack-formulas/openvpn-formula/commit/9e7aa34a499b30eab737295ae4649e510365deab))
* **travis:** add notifications => zulip [skip ci] ([80930cd](https://github.com/saltstack-formulas/openvpn-formula/commit/80930cdb479fb9f2eef7a0044b93e08fabb1d804))
* **travis:** use `major.minor` for `semantic-release` version [skip ci] ([4099f15](https://github.com/saltstack-formulas/openvpn-formula/commit/4099f15a1440bf7d9dfde707137593d9cf495d02))
* **workflows/commitlint:** add to repo [skip ci] ([5900915](https://github.com/saltstack-formulas/openvpn-formula/commit/5900915e5b86cdad1fdca9163873e1fd9ee44f98))

## [0.16.2](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.16.1...v0.16.2) (2019-12-16)


### Continuous Integration

* **gemfile:** restrict `train` gem version until upstream fix [skip ci] ([ed6b7f0](https://github.com/saltstack-formulas/openvpn-formula/commit/ed6b7f0c0d6a9171eadca2ffbc3682e24a3e346b))


### Tests

* add test for auth-nocache option ([79c1055](https://github.com/saltstack-formulas/openvpn-formula/commit/79c10556dee2431d93ce9d678d002ec1036d219b))

## [0.16.1](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.16.0...v0.16.1) (2019-12-06)


### Bug Fixes

* **auth_nocache:** fix typo in client template ([c8f0971](https://github.com/saltstack-formulas/openvpn-formula/commit/c8f0971d148be9efb8405ff7eef5bbe4eeae9ea8)), closes [#125](https://github.com/saltstack-formulas/openvpn-formula/issues/125)

# [0.16.0](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.4...v0.16.0) (2019-11-29)


### Continuous Integration

* **travis:** apply changes from build config validation [skip ci] ([ea3336a](https://github.com/saltstack-formulas/openvpn-formula/commit/ea3336af6f3657d24c0657173f07ed224140a46b))
* **travis:** opt-in to `dpl v2` to complete build config validation [skip ci] ([bb43f31](https://github.com/saltstack-formulas/openvpn-formula/commit/bb43f31450ccb48601ef61620a42c9904c502e0d))
* **travis:** quote pathspecs used with `git ls-files` [skip ci] ([667bc1f](https://github.com/saltstack-formulas/openvpn-formula/commit/667bc1f04b7e96bd2c5cdce8a91d76552d34c884))
* **travis:** run `shellcheck` during lint job [skip ci] ([9d63e36](https://github.com/saltstack-formulas/openvpn-formula/commit/9d63e36fa618df6d966ad1278bfa64153db0a9fe))
* **travis:** use build config validation (beta) [skip ci] ([d2f7fe2](https://github.com/saltstack-formulas/openvpn-formula/commit/d2f7fe24a19033b8db907be89f184b26b128b326))


### Features

* **auth_nocache:** support for auth-nocache ([c21b7f5](https://github.com/saltstack-formulas/openvpn-formula/commit/c21b7f52cc0ce24c96cf1b9173a9fda9e3eb7ae7))

## [0.15.4](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.3...v0.15.4) (2019-11-06)


### Bug Fixes

* **adapters:** call `adapters.sls` in `init.sls` ([3ebcbe9](https://github.com/saltstack-formulas/openvpn-formula/commit/3ebcbe93f8245fb435c3e9af91853930683e16b1))
* **dhparams:** allow generating Diffie Hellman parameters on Windows ([3802024](https://github.com/saltstack-formulas/openvpn-formula/commit/3802024a69d5e4008d192084d10858511f3dca4d))
* **release.config.js:** use full commit hash in commit link [skip ci] ([81d922d](https://github.com/saltstack-formulas/openvpn-formula/commit/81d922d7a3053c309e0e8f965825063df576921e))


### Continuous Integration

* **kitchen:** use `debian-10-master-py3` instead of `develop` [skip ci] ([83e00e1](https://github.com/saltstack-formulas/openvpn-formula/commit/83e00e1c4d64e86f79b2fa9cb6e8be0490cdb83e))
* **kitchen:** use `develop` image until `master` is ready (`amazonlinux`) [skip ci] ([06a09f2](https://github.com/saltstack-formulas/openvpn-formula/commit/06a09f29e187f9b01865b582eff944c30e294302))
* **kitchen+travis:** upgrade matrix after `2019.2.2` release [skip ci] ([4eb9d3b](https://github.com/saltstack-formulas/openvpn-formula/commit/4eb9d3bed2df51360822db639c2085414bfc13e3))
* **travis:** merge `rubocop` linter into main `lint` job ([9f82955](https://github.com/saltstack-formulas/openvpn-formula/commit/9f82955081169661780b8a236c1b20da15bf9aa2))
* **travis:** update `salt-lint` config for `v0.0.10` [skip ci] ([d465b4f](https://github.com/saltstack-formulas/openvpn-formula/commit/d465b4f6063ab78864cf2f25a26c339e74b64c18))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([70dab6c](https://github.com/saltstack-formulas/openvpn-formula/commit/70dab6c4ee9d9d69f80c81ae314df0d97c79114e))


### Documentation

* add steps required for testing using Vagrant ([0229d14](https://github.com/saltstack-formulas/openvpn-formula/commit/0229d1446f89d0ebe44f70b1834a0a9aa8cb68e1))
* **contributing:** remove to use org-level file instead [skip ci] ([8703eb5](https://github.com/saltstack-formulas/openvpn-formula/commit/8703eb50a6ea7505716b2350e34b88f894a4e725))
* **readme:** update link to `CONTRIBUTING` [skip ci] ([a72049f](https://github.com/saltstack-formulas/openvpn-formula/commit/a72049f738005c95548db7e3b87847d8ce741eda))


### Performance Improvements

* **travis:** improve `salt-lint` invocation [skip ci] ([26838e5](https://github.com/saltstack-formulas/openvpn-formula/commit/26838e5ccd0400390bb3a2eb29741d36a8992ac3))


### Tests

* **windows:** add local testing of Windows using Vagrant/Virtualbox ([96c3001](https://github.com/saltstack-formulas/openvpn-formula/commit/96c300125dfa86c67d14e09f772b453eddde7c84))

## [0.15.3](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.2...v0.15.3) (2019-10-10)


### Bug Fixes

* **config.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/openvpn-formula/commit/1b3f7f6))
* **ifconfig_pool_persist.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/openvpn-formula/commit/6969083))
* **map.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/openvpn-formula/commit/eabfc57))


### Continuous Integration

* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([](https://github.com/saltstack-formulas/openvpn-formula/commit/b76dcc9))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([](https://github.com/saltstack-formulas/openvpn-formula/commit/0db9651))
* **platform:** add `arch-base-latest` (commented out for now) [skip ci] ([](https://github.com/saltstack-formulas/openvpn-formula/commit/75d7aaa))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/openvpn-formula/commit/d7f1607))

## [0.15.2](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.1...v0.15.2) (2019-09-25)


### Bug Fixes

* **service:** stop old service only if name is different to new service ([1724dfd](https://github.com/saltstack-formulas/openvpn-formula/commit/1724dfd)), closes [#119](https://github.com/saltstack-formulas/openvpn-formula/issues/119)


### Continuous Integration

* **kitchen:** change `log_level` to `debug` instead of `info` ([e94c9ba](https://github.com/saltstack-formulas/openvpn-formula/commit/e94c9ba))

## [0.15.1](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.0...v0.15.1) (2019-09-21)


### Bug Fixes

* **repo:** provide EPEL repo configuration for `Amazon Linux-2` ([bfb29bd](https://github.com/saltstack-formulas/openvpn-formula/commit/bfb29bd))


### Continuous Integration

* use `dist: bionic` & apply `opensuse-leap-15` SCP error workaround ([5e02797](https://github.com/saltstack-formulas/openvpn-formula/commit/5e02797))
* **yamllint:** add rule `empty-values` & use new `yaml-files` setting ([a437b3b](https://github.com/saltstack-formulas/openvpn-formula/commit/a437b3b))

# [0.15.0](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.14.2...v0.15.0) (2019-09-07)


### Features

* **auth_gen_token:** support for auth-gen-token ([333edd7](https://github.com/saltstack-formulas/openvpn-formula/commit/333edd7))
* **syslog:** support for syslog ([24b370c](https://github.com/saltstack-formulas/openvpn-formula/commit/24b370c))

## [0.14.2](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.14.1...v0.14.2) (2019-09-06)


### Documentation

* **pillar.example:** update with quoted "yes" for comp-lzo ([1b49b24](https://github.com/saltstack-formulas/openvpn-formula/commit/1b49b24))

## [0.14.1](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.14.0...v0.14.1) (2019-09-01)


### Bug Fixes

* **config:** configurable distinction between server and client services ([18c4c4a](https://github.com/saltstack-formulas/openvpn-formula/commit/18c4c4a))
* **config:** sub-mappings for client and server ([b30b23d](https://github.com/saltstack-formulas/openvpn-formula/commit/b30b23d))
* **service:** make sure the now obsolete systemd services are disabled ([2dfae46](https://github.com/saltstack-formulas/openvpn-formula/commit/2dfae46))
* **service:** removed trailing whitespace ([85d2458](https://github.com/saltstack-formulas/openvpn-formula/commit/85d2458))
* **test:** drop ' then$' ([62c2f70](https://github.com/saltstack-formulas/openvpn-formula/commit/62c2f70))
* **test:** dropped redundant permission checks ([9c3ea71](https://github.com/saltstack-formulas/openvpn-formula/commit/9c3ea71))


### Continuous Integration

* **kitchen+travis:** replace EOL pre-salted images ([2577535](https://github.com/saltstack-formulas/openvpn-formula/commit/2577535))


### Tests

* **kitchen:** debian and ubuntu use different paths now ([dfd784e](https://github.com/saltstack-formulas/openvpn-formula/commit/dfd784e))
* **pillar:** set 'status' to fix kitchen tests ([07bb5b6](https://github.com/saltstack-formulas/openvpn-formula/commit/07bb5b6))

# [0.14.0](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.13.1...v0.14.0) (2019-08-15)


### Bug Fixes

* **network_manager_networks:** properly override port ([1d58ec6](https://github.com/saltstack-formulas/openvpn-formula/commit/1d58ec6))
* **network_manager_networks:** reduced pillar.get calls ([7ee9eed](https://github.com/saltstack-formulas/openvpn-formula/commit/7ee9eed))


### Features

* **yamllint:** include for this repo and apply rules throughout ([4355ac6](https://github.com/saltstack-formulas/openvpn-formula/commit/4355ac6))

## [0.13.1](https://github.com/saltstack-formulas/openvpn-formula/compare/v0.13.0...v0.13.1) (2019-07-19)


### Bug Fixes

* **centos:** install OpenSSL on CentOS ([7e4c8d6](https://github.com/saltstack-formulas/openvpn-formula/commit/7e4c8d6))
* **centos-6:** has only _one_ service 'openvpn' ([3d5723d](https://github.com/saltstack-formulas/openvpn-formula/commit/3d5723d))
* **config:** script-security is a common option ([b1b482c](https://github.com/saltstack-formulas/openvpn-formula/commit/b1b482c))
* **config:** set tls-auth and tls-crypt independentyl of ta_content ([d3787b6](https://github.com/saltstack-formulas/openvpn-formula/commit/d3787b6))
* **debian-ish:** root owns the logs ([3276d3b](https://github.com/saltstack-formulas/openvpn-formula/commit/3276d3b))
* **fedora:** honor working directory & service name ([4f8e899](https://github.com/saltstack-formulas/openvpn-formula/commit/4f8e899))
* **freebsd:** load if_tap module ([d63581a](https://github.com/saltstack-formulas/openvpn-formula/commit/d63581a))
* **jinja:** don't call pillar.get ([33b98f5](https://github.com/saltstack-formulas/openvpn-formula/commit/33b98f5))
* **logging:** set replace=False and add dependencies for log files ([9b71fcf](https://github.com/saltstack-formulas/openvpn-formula/commit/9b71fcf))
* **macros:** use openvpn/macros.jinja ([637387e](https://github.com/saltstack-formulas/openvpn-formula/commit/637387e))
* **service:** use OS-specific service name in multi-service setups ([b16756c](https://github.com/saltstack-formulas/openvpn-formula/commit/b16756c))
* **specs:** use boolean operator ([89fa956](https://github.com/saltstack-formulas/openvpn-formula/commit/89fa956))


### Continuous Integration

* **cleanup:** dropped obsolete opensuse-leap-15 workaround ([1e1719d](https://github.com/saltstack-formulas/openvpn-formula/commit/1e1719d))
* **kitchen:** add kitchen file + testinfra ([9c5ee26](https://github.com/saltstack-formulas/openvpn-formula/commit/9c5ee26))
* **kitchen:** rename pillar ([4122fc0](https://github.com/saltstack-formulas/openvpn-formula/commit/4122fc0))
* **kitchen:** test/config/pillars: add jinja for user on debian >= 9 ([3c7f947](https://github.com/saltstack-formulas/openvpn-formula/commit/3c7f947))
* **kitchen+travis:** modify matrix to include `develop` platform ([91b5798](https://github.com/saltstack-formulas/openvpn-formula/commit/91b5798))
* **specs:** increased readability ([b2c9cf1](https://github.com/saltstack-formulas/openvpn-formula/commit/b2c9cf1))
* **test data:** moved Pillar test data ([2fff1ee](https://github.com/saltstack-formulas/openvpn-formula/commit/2fff1ee))
* **testing:** added bin/kitchen ([15bea7b](https://github.com/saltstack-formulas/openvpn-formula/commit/15bea7b))
* **travis:** exclude Fedora 29 from Travis CI ([4a1f9ed](https://github.com/saltstack-formulas/openvpn-formula/commit/4a1f9ed))
* **travis:** test based on template-formula and [#98](https://github.com/saltstack-formulas/openvpn-formula/issues/98) ([b9daf9b](https://github.com/saltstack-formulas/openvpn-formula/commit/b9daf9b))
