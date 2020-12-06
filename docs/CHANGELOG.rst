
Changelog
=========

`1.14.6 <https://github.com/myii/openvpn-formula/compare/v1.14.5...v1.14.6>`_ (2020-12-06)
----------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **gitlab:** add caches where ``npm install`` is used (\ `0c34547 <https://github.com/myii/openvpn-formula/commit/0c345475d0a0728b47f58824fd52423bcc50a7ea>`_\ )

`1.14.5 <https://github.com/myii/openvpn-formula/compare/v1.14.4...v1.14.5>`_ (2020-12-06)
----------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **m2r:** move back to script so latest changelog is included (\ `de357c8 <https://github.com/myii/openvpn-formula/commit/de357c8ff1fa416c8c19a1618c9bdad0350b312a>`_\ )

`1.14.4 <https://github.com/myii/openvpn-formula/compare/v1.14.3...v1.14.4>`_ (2020-12-06)
----------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **m2r:** ensure ``setuptools`` & ``wheel`` available (\ `f80c334 <https://github.com/myii/openvpn-formula/commit/f80c334ba219ac988009c0108c0f6ecc25c8ee7d>`_\ )
* **m2r:** run in CI directly rather than via. ``semantic-release`` (\ `a764dfd <https://github.com/myii/openvpn-formula/commit/a764dfda4a4e168d3640b8e3f9a4c0f50b82843a>`_\ )

`1.14.3 <https://github.com/myii/openvpn-formula/compare/v1.14.2...v1.14.3>`_ (2020-12-06)
----------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **pre-commit_semantic-release.sh:** install ``m2r`` without ``sudo`` (\ `e6ee33d <https://github.com/myii/openvpn-formula/commit/e6ee33d972cda933ae7e1814e131ed977fa7b180>`_\ )

`1.14.2 <https://github.com/myii/openvpn-formula/compare/v1.14.1...v1.14.2>`_ (2020-12-06)
----------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **gitlab:** finalise ``semantic-release`` job (\ `916e2eb <https://github.com/myii/openvpn-formula/commit/916e2eb5b9614a967aa30bd3616ced56c40bebc7>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **github:** use official GitLab CI caching for ``pre-commit`` (\ `5ea7ed0 <https://github.com/myii/openvpn-formula/commit/5ea7ed037ab1ab82d37e5826a4b2da962b4b6cc3>`_\ )
* **gitlab:** add bundler caching for test jobs (\ `175561c <https://github.com/myii/openvpn-formula/commit/175561c935cd90029063539574bb5cf26ee9819c>`_\ )
* **gitlab:** add pre-commit (\ `e9425f0 <https://github.com/myii/openvpn-formula/commit/e9425f0f18a4798d90739504b1fe52b9f8b0abae>`_\ )
* **gitlab:** finalise configuration (\ `84a9006 <https://github.com/myii/openvpn-formula/commit/84a90067163f201e2a8ed9dd9a554802e9845c78>`_\ )
* **gitlab:** fix ``semantic-release`` settings (\ `bc0eeb5 <https://github.com/myii/openvpn-formula/commit/bc0eeb5d0f64d0d552429314143efc84d80d7fc5>`_\ )
* **gitlab:** use ``${CI_PROJECT_URL}`` for ``commitlint`` (\ `74483ae <https://github.com/myii/openvpn-formula/commit/74483ae4bea6a7e8ba3318077568995499ae7086>`_\ )

`1.14.1 <https://github.com/myii/openvpn-formula/compare/v1.14.0...v1.14.1>`_ (2020-12-05)
----------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **gitlab:** ensure changelog working as required (\ `228ae32 <https://github.com/myii/openvpn-formula/commit/228ae327bf168b6662b50916cb0859bd6dad38f8>`_\ )

`1.14.0 <https://github.com/myii/openvpn-formula/compare/v1.13.0...v1.14.0>`_ (2020-12-05)
----------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **adapters:** call ``adapters.sls`` in ``init.sls`` (\ `3ebcbe9 <https://github.com/myii/openvpn-formula/commit/3ebcbe93f8245fb435c3e9af91853930683e16b1>`_\ )
* **auth_nocache:** fix typo in client template (\ `c8f0971 <https://github.com/myii/openvpn-formula/commit/c8f0971d148be9efb8405ff7eef5bbe4eeae9ea8>`_\ ), closes `#125 <https://github.com/myii/openvpn-formula/issues/125>`_
* **centos:** install OpenSSL on CentOS (\ `7e4c8d6 <https://github.com/myii/openvpn-formula/commit/7e4c8d6719eff5610a55c04a5b042a44726d553d>`_\ )
* **centos-6:** has only *one* service 'openvpn' (\ `3d5723d <https://github.com/myii/openvpn-formula/commit/3d5723d385174b9b05d720112e4f4c35654dee58>`_\ )
* **config:** configurable distinction between server and client services (\ `18c4c4a <https://github.com/myii/openvpn-formula/commit/18c4c4a11c98409ac3dba1ef0fc8b88785c853ba>`_\ )
* **config:** script-security is a common option (\ `b1b482c <https://github.com/myii/openvpn-formula/commit/b1b482cda8867025a88ea4660e7cc59f792e0435>`_\ )
* **config:** set tls-auth and tls-crypt independentyl of ta_content (\ `d3787b6 <https://github.com/myii/openvpn-formula/commit/d3787b63d28fd11eb3692c75e312704d2a48f66c>`_\ )
* **config:** sub-mappings for client and server (\ `b30b23d <https://github.com/myii/openvpn-formula/commit/b30b23dfdcb68a0f904c3a8643c7846d4b61b5f0>`_\ )
* **config.sls:** fix ``salt-lint`` errors (\ `1b3f7f6 <https://github.com/myii/openvpn-formula/commit/1b3f7f6aa70072f2c895c9430deaa6b05459c2ad>`_\ )
* **debian-ish:** root owns the logs (\ `3276d3b <https://github.com/myii/openvpn-formula/commit/3276d3bc82499da9174d95d4bb8cdaa1fcd0e387>`_\ )
* **dhparams:** allow generating Diffie Hellman parameters on Windows (\ `3802024 <https://github.com/myii/openvpn-formula/commit/3802024a69d5e4008d192084d10858511f3dca4d>`_\ )
* **fedora:** honor working directory & service name (\ `4f8e899 <https://github.com/myii/openvpn-formula/commit/4f8e8992a8691d215d65fc1757cb66c3b4ca30bf>`_\ )
* **freebsd:** load if_tap module (\ `d63581a <https://github.com/myii/openvpn-formula/commit/d63581a37a4033be2db886669401a1115bdf5c50>`_\ )
* **gitlab:** use Travis instances (\ `44f6bc1 <https://github.com/myii/openvpn-formula/commit/44f6bc1d04afa98fd6f77a9b36b83165ec910d31>`_\ )
* **ifconfig_pool_persist.sls:** fix ``salt-lint`` errors (\ `6969083 <https://github.com/myii/openvpn-formula/commit/6969083052cf6c35f1f0decddb8917fe385438e7>`_\ )
* **jinja:** don't call pillar.get (\ `33b98f5 <https://github.com/myii/openvpn-formula/commit/33b98f53cb4d235235b4ecbfcad4181b1e2df14e>`_\ )
* **logging:** set replace=False and add dependencies for log files (\ `9b71fcf <https://github.com/myii/openvpn-formula/commit/9b71fcfb3eeff41745000d71a385c71fd85cceab>`_\ )
* **macros:** use openvpn/macros.jinja (\ `637387e <https://github.com/myii/openvpn-formula/commit/637387ec5d15917708c5ccb71b947c73df2e870c>`_\ )
* **map.jinja:** fix ``salt-lint`` errors (\ `eabfc57 <https://github.com/myii/openvpn-formula/commit/eabfc57ea9794c351e120d9b7b6d469d50008597>`_\ )
* **network_manager_networks:** properly override port (\ `1d58ec6 <https://github.com/myii/openvpn-formula/commit/1d58ec6d708a80066e7334505a0fc07cb8d3c607>`_\ )
* **network_manager_networks:** reduced pillar.get calls (\ `7ee9eed <https://github.com/myii/openvpn-formula/commit/7ee9eed4f2cb0fd0a260e5c5f99eabfadd0432c4>`_\ )
* **release.config.js:** use full commit hash in commit link [skip ci] (\ `81d922d <https://github.com/myii/openvpn-formula/commit/81d922d7a3053c309e0e8f965825063df576921e>`_\ )
* **repo:** provide EPEL repo configuration for ``Amazon Linux-2`` (\ `bfb29bd <https://github.com/myii/openvpn-formula/commit/bfb29bd57fc74907bd6eeb8899cc8ec2f2d856ec>`_\ )
* **service:** make sure the now obsolete systemd services are disabled (\ `2dfae46 <https://github.com/myii/openvpn-formula/commit/2dfae465fc87ba06f37710f919bdaf3ce18732c9>`_\ )
* **service:** removed trailing whitespace (\ `85d2458 <https://github.com/myii/openvpn-formula/commit/85d24580c6ad68c8d6f9db5bc47fa52674989773>`_\ )
* **service:** stop old service only if name is different to new service (\ `1724dfd <https://github.com/myii/openvpn-formula/commit/1724dfd683d2d2d9c1d0e1a37f31123a922fda03>`_\ ), closes `#119 <https://github.com/myii/openvpn-formula/issues/119>`_
* **service:** use OS-specific service name in multi-service setups (\ `b16756c <https://github.com/myii/openvpn-formula/commit/b16756cb018baed16fe45df0645d4f7c92ed7a6f>`_\ )
* **specs:** use boolean operator (\ `89fa956 <https://github.com/myii/openvpn-formula/commit/89fa95614cf07d4fa0ec174ee9665673dc3ad325>`_\ )
* **tap-adapter.ps1:** work with alternate name ``Local Area Connection`` (\ `372b3b6 <https://github.com/myii/openvpn-formula/commit/372b3b6d80ef5ede742961bca44d726d16249646>`_\ )
* **test:** drop ' then$' (\ `62c2f70 <https://github.com/myii/openvpn-formula/commit/62c2f70b92bbbbc4991009a39c48fd89a47bf561>`_\ )
* **test:** dropped redundant permission checks (\ `9c3ea71 <https://github.com/myii/openvpn-formula/commit/9c3ea716042a2e00fba7c2bcfac78e8ecbbda188>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **cleanup:** dropped obsolete opensuse-leap-15 workaround (\ `1e1719d <https://github.com/myii/openvpn-formula/commit/1e1719d84d7149dd3d83e07d8331dce55b9d8398>`_\ )
* **gemfile:** restrict ``train`` gem version until upstream fix [skip ci] (\ `ed6b7f0 <https://github.com/myii/openvpn-formula/commit/ed6b7f0c0d6a9171eadca2ffbc3682e24a3e346b>`_\ )
* **gemfile.lock:** add to repo with updated ``Gemfile`` [skip ci] (\ `0aa9fd6 <https://github.com/myii/openvpn-formula/commit/0aa9fd6d93533d824f4c6d144474d6721dd1bca6>`_\ )
* **github:** add Windows testing using Actions (\ `2d4b79c <https://github.com/myii/openvpn-formula/commit/2d4b79c5f8afe73eeeef187e63d9613bbf7bd793>`_\ )
* **gitlab:** test ``semantic-release`` back to GitHub (\ `0ead7f1 <https://github.com/myii/openvpn-formula/commit/0ead7f18b3b5b34ea328c448cb296f6f5962474e>`_\ )
* **gitlab:** use GitLab CI as Travis CI replacement (\ `c9e4a8c <https://github.com/myii/openvpn-formula/commit/c9e4a8cbdf778ba3dd91b3a9c98b6e97a7b8cf24>`_\ )
* **kitchen:** add kitchen file + testinfra (\ `9c5ee26 <https://github.com/myii/openvpn-formula/commit/9c5ee269dd9a5ee40cd69a30ab1903ad430aebdb>`_\ )
* **kitchen:** avoid using bootstrap for ``master`` instances [skip ci] (\ `6eb1b44 <https://github.com/myii/openvpn-formula/commit/6eb1b4437df9e2b8bb3171f8811bcf1d091113d9>`_\ )
* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ `e94c9ba <https://github.com/myii/openvpn-formula/commit/e94c9ba56865333e8ec848f9fbcebbab72910932>`_\ )
* **kitchen:** install required packages to bootstrapped ``opensuse`` [skip ci] (\ `b76dcc9 <https://github.com/myii/openvpn-formula/commit/b76dcc9d737286202280525012181e971bbafb9d>`_\ )
* **kitchen:** rename pillar (\ `4122fc0 <https://github.com/myii/openvpn-formula/commit/4122fc0e02715959a219c2217e5d4cdaae265cfe>`_\ )
* **kitchen:** test/config/pillars: add jinja for user on debian >= 9 (\ `3c7f947 <https://github.com/myii/openvpn-formula/commit/3c7f947a94c2d043f9c36bfc882b1f36aedaa873>`_\ )
* **kitchen:** use ``debian-10-master-py3`` instead of ``develop`` [skip ci] (\ `83e00e1 <https://github.com/myii/openvpn-formula/commit/83e00e1c4d64e86f79b2fa9cb6e8be0490cdb83e>`_\ )
* **kitchen:** use ``develop`` image until ``master`` is ready (\ ``amazonlinux``\ ) [skip ci] (\ `06a09f2 <https://github.com/myii/openvpn-formula/commit/06a09f29e187f9b01865b582eff944c30e294302>`_\ )
* **kitchen:** use ``saltimages`` Docker Hub where available [skip ci] (\ `740ba4e <https://github.com/myii/openvpn-formula/commit/740ba4e80e01a724b7833ee6b3d7e66740ced795>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` [skip ci] (\ `0db9651 <https://github.com/myii/openvpn-formula/commit/0db9651a1a10f16ec7babed8c5031d925b84be12>`_\ )
* **kitchen+travis:** modify matrix to include ``develop`` platform (\ `91b5798 <https://github.com/myii/openvpn-formula/commit/91b579823fab95bc6148aa7084f48e1f8f08764e>`_\ )
* **kitchen+travis:** remove ``master-py2-arch-base-latest`` [skip ci] (\ `9e7aa34 <https://github.com/myii/openvpn-formula/commit/9e7aa34a499b30eab737295ae4649e510365deab>`_\ )
* **kitchen+travis:** replace EOL pre-salted images (\ `2577535 <https://github.com/myii/openvpn-formula/commit/25775355c11cec61ec58dee9a1459f6a97cbfc66>`_\ )
* **kitchen+travis:** upgrade matrix after ``2019.2.2`` release [skip ci] (\ `4eb9d3b <https://github.com/myii/openvpn-formula/commit/4eb9d3bed2df51360822db639c2085414bfc13e3>`_\ )
* **platform:** add ``arch-base-latest`` (commented out for now) [skip ci] (\ `75d7aaa <https://github.com/myii/openvpn-formula/commit/75d7aaae13bc721f0c3bc3dd391b4b13564c425f>`_\ )
* **pre-commit:** add to formula [skip ci] (\ `95bbd5e <https://github.com/myii/openvpn-formula/commit/95bbd5eee34dd7ae36642ea38f2fc388c385cb30>`_\ )
* **pre-commit:** enable/disable ``rstcheck`` as relevant [skip ci] (\ `92e02f2 <https://github.com/myii/openvpn-formula/commit/92e02f2b549ed599786bb08562dc4bc60df84c49>`_\ )
* **pre-commit:** finalise ``rstcheck`` configuration [skip ci] (\ `44e040d <https://github.com/myii/openvpn-formula/commit/44e040d3a143c7d3a2ad6805ae1f42e261bb7f32>`_\ )
* avoid ``init_environment`` failing due to saltstack/salt\ `#57628 <https://github.com/myii/openvpn-formula/issues/57628>`_ (\ `398932b <https://github.com/myii/openvpn-formula/commit/398932b8332b701b6a1430018629d097b2f41155>`_\ )
* **specs:** increased readability (\ `b2c9cf1 <https://github.com/myii/openvpn-formula/commit/b2c9cf165ae0ad63d745533704d7c0be74540c60>`_\ )
* **test data:** moved Pillar test data (\ `2fff1ee <https://github.com/myii/openvpn-formula/commit/2fff1eeb9a7e77b45b7f69f6a2799a650d90b923>`_\ )
* **testing:** added bin/kitchen (\ `15bea7b <https://github.com/myii/openvpn-formula/commit/15bea7b1755ec334c1a0d91a3f7c0827321a4b94>`_\ )
* **travis:** add notifications => zulip [skip ci] (\ `80930cd <https://github.com/myii/openvpn-formula/commit/80930cdb479fb9f2eef7a0044b93e08fabb1d804>`_\ )
* **travis:** apply changes from build config validation [skip ci] (\ `ea3336a <https://github.com/myii/openvpn-formula/commit/ea3336af6f3657d24c0657173f07ed224140a46b>`_\ )
* **travis:** exclude Fedora 29 from Travis CI (\ `4a1f9ed <https://github.com/myii/openvpn-formula/commit/4a1f9ed11112ee3ce2dd483bde1a83caa1a22794>`_\ )
* **travis:** merge ``rubocop`` linter into main ``lint`` job (\ `9f82955 <https://github.com/myii/openvpn-formula/commit/9f82955081169661780b8a236c1b20da15bf9aa2>`_\ )
* **travis:** opt-in to ``dpl v2`` to complete build config validation [skip ci] (\ `bb43f31 <https://github.com/myii/openvpn-formula/commit/bb43f31450ccb48601ef61620a42c9904c502e0d>`_\ )
* **travis:** quote pathspecs used with ``git ls-files`` [skip ci] (\ `667bc1f <https://github.com/myii/openvpn-formula/commit/667bc1f04b7e96bd2c5cdce8a91d76552d34c884>`_\ )
* **travis:** run ``shellcheck`` during lint job [skip ci] (\ `9d63e36 <https://github.com/myii/openvpn-formula/commit/9d63e36fa618df6d966ad1278bfa64153db0a9fe>`_\ )
* **travis:** test based on template-formula and `#98 <https://github.com/myii/openvpn-formula/issues/98>`_ (\ `b9daf9b <https://github.com/myii/openvpn-formula/commit/b9daf9bb06b9f6c9b89adcfa7b26845a9f3493bb>`_\ )
* **travis:** update ``salt-lint`` config for ``v0.0.10`` [skip ci] (\ `d465b4f <https://github.com/myii/openvpn-formula/commit/d465b4f6063ab78864cf2f25a26c339e74b64c18>`_\ )
* **travis:** use ``major.minor`` for ``semantic-release`` version [skip ci] (\ `4099f15 <https://github.com/myii/openvpn-formula/commit/4099f15a1440bf7d9dfde707137593d9cf495d02>`_\ )
* **travis:** use build config validation (beta) [skip ci] (\ `d2f7fe2 <https://github.com/myii/openvpn-formula/commit/d2f7fe24a19033b8db907be89f184b26b128b326>`_\ )
* **workflows/commitlint:** add to repo [skip ci] (\ `5900915 <https://github.com/myii/openvpn-formula/commit/5900915e5b86cdad1fdca9163873e1fd9ee44f98>`_\ )
* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ `d7f1607 <https://github.com/myii/openvpn-formula/commit/d7f1607118c007de79be0fe64be9506079d5240f>`_\ )
* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ `70dab6c <https://github.com/myii/openvpn-formula/commit/70dab6c4ee9d9d69f80c81ae314df0d97c79114e>`_\ )
* **yamllint:** add rule ``empty-values`` & use new ``yaml-files`` setting (\ `a437b3b <https://github.com/myii/openvpn-formula/commit/a437b3b4e04267f7b8eeb5bd47509fa5b51d85f7>`_\ )
* use ``dist: bionic`` & apply ``opensuse-leap-15`` SCP error workaround (\ `5e02797 <https://github.com/myii/openvpn-formula/commit/5e02797e8d4ba6257838d3b1b2f63c9ac6128213>`_\ )

Documentation
^^^^^^^^^^^^^


* add steps required for testing using Vagrant (\ `0229d14 <https://github.com/myii/openvpn-formula/commit/0229d1446f89d0ebe44f70b1834a0a9aa8cb68e1>`_\ )
* **contributing:** remove to use org-level file instead [skip ci] (\ `8703eb5 <https://github.com/myii/openvpn-formula/commit/8703eb50a6ea7505716b2350e34b88f894a4e725>`_\ )
* **pillar.example:** update with quoted "yes" for comp-lzo (\ `1b49b24 <https://github.com/myii/openvpn-formula/commit/1b49b24aa380edd52170b6234151dadf416f1a10>`_\ )
* **readme:** update link to ``CONTRIBUTING`` [skip ci] (\ `a72049f <https://github.com/myii/openvpn-formula/commit/a72049f738005c95548db7e3b87847d8ce741eda>`_\ )

Features
^^^^^^^^


* **auth_gen_token:** support for auth-gen-token (\ `333edd7 <https://github.com/myii/openvpn-formula/commit/333edd7ac836b3e510124642df32361a548a6213>`_\ )
* **auth_nocache:** support for auth-nocache (\ `c21b7f5 <https://github.com/myii/openvpn-formula/commit/c21b7f52cc0ce24c96cf1b9173a9fda9e3eb7ae7>`_\ )
* **syslog:** support for syslog (\ `24b370c <https://github.com/myii/openvpn-formula/commit/24b370ccac24a0905d00e1706db480878b400383>`_\ )
* **yamllint:** include for this repo and apply rules throughout (\ `4355ac6 <https://github.com/myii/openvpn-formula/commit/4355ac6413e0c3284fc2be08abb183552b3a2bf3>`_\ )

Performance Improvements
^^^^^^^^^^^^^^^^^^^^^^^^


* **travis:** improve ``salt-lint`` invocation [skip ci] (\ `26838e5 <https://github.com/myii/openvpn-formula/commit/26838e5ccd0400390bb3a2eb29741d36a8992ac3>`_\ )

Tests
^^^^^


* **map:** verify ``map.jinja`` dump using ``_mapdata`` state (\ `ecac1b1 <https://github.com/myii/openvpn-formula/commit/ecac1b107f8a5309b803cb7fe41d1802b427b5fe>`_\ )
* add test for auth-nocache option (\ `79c1055 <https://github.com/myii/openvpn-formula/commit/79c10556dee2431d93ce9d678d002ec1036d219b>`_\ )
* **kitchen:** debian and ubuntu use different paths now (\ `dfd784e <https://github.com/myii/openvpn-formula/commit/dfd784e3653dba1b26b055d2cf5afc80dc58a75f>`_\ )
* **pillar:** set 'status' to fix kitchen tests (\ `07bb5b6 <https://github.com/myii/openvpn-formula/commit/07bb5b63d454dd95b136b2dcabf7e9eda37b4112>`_\ )
* **windows:** add local testing of Windows using Vagrant/Virtualbox (\ `96c3001 <https://github.com/myii/openvpn-formula/commit/96c300125dfa86c67d14e09f772b453eddde7c84>`_\ )

`0.16.4 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.16.3...v0.16.4>`_ (2020-10-30)
------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** use ``saltimages`` Docker Hub where available [skip ci] (\ `740ba4e <https://github.com/saltstack-formulas/openvpn-formula/commit/740ba4e80e01a724b7833ee6b3d7e66740ced795>`_\ )
* **pre-commit:** add to formula [skip ci] (\ `95bbd5e <https://github.com/saltstack-formulas/openvpn-formula/commit/95bbd5eee34dd7ae36642ea38f2fc388c385cb30>`_\ )
* **pre-commit:** enable/disable ``rstcheck`` as relevant [skip ci] (\ `92e02f2 <https://github.com/saltstack-formulas/openvpn-formula/commit/92e02f2b549ed599786bb08562dc4bc60df84c49>`_\ )
* **pre-commit:** finalise ``rstcheck`` configuration [skip ci] (\ `44e040d <https://github.com/saltstack-formulas/openvpn-formula/commit/44e040d3a143c7d3a2ad6805ae1f42e261bb7f32>`_\ )
* avoid ``init_environment`` failing due to saltstack/salt\ `#57628 <https://github.com/saltstack-formulas/openvpn-formula/issues/57628>`_ (\ `398932b <https://github.com/saltstack-formulas/openvpn-formula/commit/398932b8332b701b6a1430018629d097b2f41155>`_\ )

Tests
^^^^^


* **map:** verify ``map.jinja`` dump using ``_mapdata`` state (\ `ecac1b1 <https://github.com/saltstack-formulas/openvpn-formula/commit/ecac1b107f8a5309b803cb7fe41d1802b427b5fe>`_\ )

`0.16.3 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.16.2...v0.16.3>`_ (2020-06-10)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **tap-adapter.ps1:** work with alternate name ``Local Area Connection`` (\ `372b3b6 <https://github.com/saltstack-formulas/openvpn-formula/commit/372b3b6d80ef5ede742961bca44d726d16249646>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile.lock:** add to repo with updated ``Gemfile`` [skip ci] (\ `0aa9fd6 <https://github.com/saltstack-formulas/openvpn-formula/commit/0aa9fd6d93533d824f4c6d144474d6721dd1bca6>`_\ )
* **github:** add Windows testing using Actions (\ `2d4b79c <https://github.com/saltstack-formulas/openvpn-formula/commit/2d4b79c5f8afe73eeeef187e63d9613bbf7bd793>`_\ )
* **kitchen:** avoid using bootstrap for ``master`` instances [skip ci] (\ `6eb1b44 <https://github.com/saltstack-formulas/openvpn-formula/commit/6eb1b4437df9e2b8bb3171f8811bcf1d091113d9>`_\ )
* **kitchen+travis:** remove ``master-py2-arch-base-latest`` [skip ci] (\ `9e7aa34 <https://github.com/saltstack-formulas/openvpn-formula/commit/9e7aa34a499b30eab737295ae4649e510365deab>`_\ )
* **travis:** add notifications => zulip [skip ci] (\ `80930cd <https://github.com/saltstack-formulas/openvpn-formula/commit/80930cdb479fb9f2eef7a0044b93e08fabb1d804>`_\ )
* **travis:** use ``major.minor`` for ``semantic-release`` version [skip ci] (\ `4099f15 <https://github.com/saltstack-formulas/openvpn-formula/commit/4099f15a1440bf7d9dfde707137593d9cf495d02>`_\ )
* **workflows/commitlint:** add to repo [skip ci] (\ `5900915 <https://github.com/saltstack-formulas/openvpn-formula/commit/5900915e5b86cdad1fdca9163873e1fd9ee44f98>`_\ )

`0.16.2 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.16.1...v0.16.2>`_ (2019-12-16)
------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile:** restrict ``train`` gem version until upstream fix [skip ci] (\ `ed6b7f0 <https://github.com/saltstack-formulas/openvpn-formula/commit/ed6b7f0c0d6a9171eadca2ffbc3682e24a3e346b>`_\ )

Tests
^^^^^


* add test for auth-nocache option (\ `79c1055 <https://github.com/saltstack-formulas/openvpn-formula/commit/79c10556dee2431d93ce9d678d002ec1036d219b>`_\ )

`0.16.1 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.16.0...v0.16.1>`_ (2019-12-06)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **auth_nocache:** fix typo in client template (\ `c8f0971 <https://github.com/saltstack-formulas/openvpn-formula/commit/c8f0971d148be9efb8405ff7eef5bbe4eeae9ea8>`_\ ), closes `#125 <https://github.com/saltstack-formulas/openvpn-formula/issues/125>`_

`0.16.0 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.4...v0.16.0>`_ (2019-11-29)
------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **travis:** apply changes from build config validation [skip ci] (\ `ea3336a <https://github.com/saltstack-formulas/openvpn-formula/commit/ea3336af6f3657d24c0657173f07ed224140a46b>`_\ )
* **travis:** opt-in to ``dpl v2`` to complete build config validation [skip ci] (\ `bb43f31 <https://github.com/saltstack-formulas/openvpn-formula/commit/bb43f31450ccb48601ef61620a42c9904c502e0d>`_\ )
* **travis:** quote pathspecs used with ``git ls-files`` [skip ci] (\ `667bc1f <https://github.com/saltstack-formulas/openvpn-formula/commit/667bc1f04b7e96bd2c5cdce8a91d76552d34c884>`_\ )
* **travis:** run ``shellcheck`` during lint job [skip ci] (\ `9d63e36 <https://github.com/saltstack-formulas/openvpn-formula/commit/9d63e36fa618df6d966ad1278bfa64153db0a9fe>`_\ )
* **travis:** use build config validation (beta) [skip ci] (\ `d2f7fe2 <https://github.com/saltstack-formulas/openvpn-formula/commit/d2f7fe24a19033b8db907be89f184b26b128b326>`_\ )

Features
^^^^^^^^


* **auth_nocache:** support for auth-nocache (\ `c21b7f5 <https://github.com/saltstack-formulas/openvpn-formula/commit/c21b7f52cc0ce24c96cf1b9173a9fda9e3eb7ae7>`_\ )

`0.15.4 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.3...v0.15.4>`_ (2019-11-06)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **adapters:** call ``adapters.sls`` in ``init.sls`` (\ `3ebcbe9 <https://github.com/saltstack-formulas/openvpn-formula/commit/3ebcbe93f8245fb435c3e9af91853930683e16b1>`_\ )
* **dhparams:** allow generating Diffie Hellman parameters on Windows (\ `3802024 <https://github.com/saltstack-formulas/openvpn-formula/commit/3802024a69d5e4008d192084d10858511f3dca4d>`_\ )
* **release.config.js:** use full commit hash in commit link [skip ci] (\ `81d922d <https://github.com/saltstack-formulas/openvpn-formula/commit/81d922d7a3053c309e0e8f965825063df576921e>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** use ``debian-10-master-py3`` instead of ``develop`` [skip ci] (\ `83e00e1 <https://github.com/saltstack-formulas/openvpn-formula/commit/83e00e1c4d64e86f79b2fa9cb6e8be0490cdb83e>`_\ )
* **kitchen:** use ``develop`` image until ``master`` is ready (\ ``amazonlinux``\ ) [skip ci] (\ `06a09f2 <https://github.com/saltstack-formulas/openvpn-formula/commit/06a09f29e187f9b01865b582eff944c30e294302>`_\ )
* **kitchen+travis:** upgrade matrix after ``2019.2.2`` release [skip ci] (\ `4eb9d3b <https://github.com/saltstack-formulas/openvpn-formula/commit/4eb9d3bed2df51360822db639c2085414bfc13e3>`_\ )
* **travis:** merge ``rubocop`` linter into main ``lint`` job (\ `9f82955 <https://github.com/saltstack-formulas/openvpn-formula/commit/9f82955081169661780b8a236c1b20da15bf9aa2>`_\ )
* **travis:** update ``salt-lint`` config for ``v0.0.10`` [skip ci] (\ `d465b4f <https://github.com/saltstack-formulas/openvpn-formula/commit/d465b4f6063ab78864cf2f25a26c339e74b64c18>`_\ )
* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ `70dab6c <https://github.com/saltstack-formulas/openvpn-formula/commit/70dab6c4ee9d9d69f80c81ae314df0d97c79114e>`_\ )

Documentation
^^^^^^^^^^^^^


* add steps required for testing using Vagrant (\ `0229d14 <https://github.com/saltstack-formulas/openvpn-formula/commit/0229d1446f89d0ebe44f70b1834a0a9aa8cb68e1>`_\ )
* **contributing:** remove to use org-level file instead [skip ci] (\ `8703eb5 <https://github.com/saltstack-formulas/openvpn-formula/commit/8703eb50a6ea7505716b2350e34b88f894a4e725>`_\ )
* **readme:** update link to ``CONTRIBUTING`` [skip ci] (\ `a72049f <https://github.com/saltstack-formulas/openvpn-formula/commit/a72049f738005c95548db7e3b87847d8ce741eda>`_\ )

Performance Improvements
^^^^^^^^^^^^^^^^^^^^^^^^


* **travis:** improve ``salt-lint`` invocation [skip ci] (\ `26838e5 <https://github.com/saltstack-formulas/openvpn-formula/commit/26838e5ccd0400390bb3a2eb29741d36a8992ac3>`_\ )

Tests
^^^^^


* **windows:** add local testing of Windows using Vagrant/Virtualbox (\ `96c3001 <https://github.com/saltstack-formulas/openvpn-formula/commit/96c300125dfa86c67d14e09f772b453eddde7c84>`_\ )

`0.15.3 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.2...v0.15.3>`_ (2019-10-10)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **config.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/openvpn-formula/commit/1b3f7f6>`_\ )
* **ifconfig_pool_persist.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/openvpn-formula/commit/6969083>`_\ )
* **map.jinja:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/openvpn-formula/commit/eabfc57>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** install required packages to bootstrapped ``opensuse`` [skip ci] (\ ` <https://github.com/saltstack-formulas/openvpn-formula/commit/b76dcc9>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` [skip ci] (\ ` <https://github.com/saltstack-formulas/openvpn-formula/commit/0db9651>`_\ )
* **platform:** add ``arch-base-latest`` (commented out for now) [skip ci] (\ ` <https://github.com/saltstack-formulas/openvpn-formula/commit/75d7aaa>`_\ )
* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/openvpn-formula/commit/d7f1607>`_\ )

`0.15.2 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.1...v0.15.2>`_ (2019-09-25)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **service:** stop old service only if name is different to new service (\ `1724dfd <https://github.com/saltstack-formulas/openvpn-formula/commit/1724dfd>`_\ ), closes `#119 <https://github.com/saltstack-formulas/openvpn-formula/issues/119>`_

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ `e94c9ba <https://github.com/saltstack-formulas/openvpn-formula/commit/e94c9ba>`_\ )

`0.15.1 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.15.0...v0.15.1>`_ (2019-09-21)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **repo:** provide EPEL repo configuration for ``Amazon Linux-2`` (\ `bfb29bd <https://github.com/saltstack-formulas/openvpn-formula/commit/bfb29bd>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* use ``dist: bionic`` & apply ``opensuse-leap-15`` SCP error workaround (\ `5e02797 <https://github.com/saltstack-formulas/openvpn-formula/commit/5e02797>`_\ )
* **yamllint:** add rule ``empty-values`` & use new ``yaml-files`` setting (\ `a437b3b <https://github.com/saltstack-formulas/openvpn-formula/commit/a437b3b>`_\ )

`0.15.0 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.14.2...v0.15.0>`_ (2019-09-07)
------------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **auth_gen_token:** support for auth-gen-token (\ `333edd7 <https://github.com/saltstack-formulas/openvpn-formula/commit/333edd7>`_\ )
* **syslog:** support for syslog (\ `24b370c <https://github.com/saltstack-formulas/openvpn-formula/commit/24b370c>`_\ )

`0.14.2 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.14.1...v0.14.2>`_ (2019-09-06)
------------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **pillar.example:** update with quoted "yes" for comp-lzo (\ `1b49b24 <https://github.com/saltstack-formulas/openvpn-formula/commit/1b49b24>`_\ )

`0.14.1 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.14.0...v0.14.1>`_ (2019-09-01)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **config:** configurable distinction between server and client services (\ `18c4c4a <https://github.com/saltstack-formulas/openvpn-formula/commit/18c4c4a>`_\ )
* **config:** sub-mappings for client and server (\ `b30b23d <https://github.com/saltstack-formulas/openvpn-formula/commit/b30b23d>`_\ )
* **service:** make sure the now obsolete systemd services are disabled (\ `2dfae46 <https://github.com/saltstack-formulas/openvpn-formula/commit/2dfae46>`_\ )
* **service:** removed trailing whitespace (\ `85d2458 <https://github.com/saltstack-formulas/openvpn-formula/commit/85d2458>`_\ )
* **test:** drop ' then$' (\ `62c2f70 <https://github.com/saltstack-formulas/openvpn-formula/commit/62c2f70>`_\ )
* **test:** dropped redundant permission checks (\ `9c3ea71 <https://github.com/saltstack-formulas/openvpn-formula/commit/9c3ea71>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** replace EOL pre-salted images (\ `2577535 <https://github.com/saltstack-formulas/openvpn-formula/commit/2577535>`_\ )

Tests
^^^^^


* **kitchen:** debian and ubuntu use different paths now (\ `dfd784e <https://github.com/saltstack-formulas/openvpn-formula/commit/dfd784e>`_\ )
* **pillar:** set 'status' to fix kitchen tests (\ `07bb5b6 <https://github.com/saltstack-formulas/openvpn-formula/commit/07bb5b6>`_\ )

`0.14.0 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.13.1...v0.14.0>`_ (2019-08-15)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **network_manager_networks:** properly override port (\ `1d58ec6 <https://github.com/saltstack-formulas/openvpn-formula/commit/1d58ec6>`_\ )
* **network_manager_networks:** reduced pillar.get calls (\ `7ee9eed <https://github.com/saltstack-formulas/openvpn-formula/commit/7ee9eed>`_\ )

Features
^^^^^^^^


* **yamllint:** include for this repo and apply rules throughout (\ `4355ac6 <https://github.com/saltstack-formulas/openvpn-formula/commit/4355ac6>`_\ )

`0.13.1 <https://github.com/saltstack-formulas/openvpn-formula/compare/v0.13.0...v0.13.1>`_ (2019-07-19)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **centos:** install OpenSSL on CentOS (\ `7e4c8d6 <https://github.com/saltstack-formulas/openvpn-formula/commit/7e4c8d6>`_\ )
* **centos-6:** has only *one* service 'openvpn' (\ `3d5723d <https://github.com/saltstack-formulas/openvpn-formula/commit/3d5723d>`_\ )
* **config:** script-security is a common option (\ `b1b482c <https://github.com/saltstack-formulas/openvpn-formula/commit/b1b482c>`_\ )
* **config:** set tls-auth and tls-crypt independentyl of ta_content (\ `d3787b6 <https://github.com/saltstack-formulas/openvpn-formula/commit/d3787b6>`_\ )
* **debian-ish:** root owns the logs (\ `3276d3b <https://github.com/saltstack-formulas/openvpn-formula/commit/3276d3b>`_\ )
* **fedora:** honor working directory & service name (\ `4f8e899 <https://github.com/saltstack-formulas/openvpn-formula/commit/4f8e899>`_\ )
* **freebsd:** load if_tap module (\ `d63581a <https://github.com/saltstack-formulas/openvpn-formula/commit/d63581a>`_\ )
* **jinja:** don't call pillar.get (\ `33b98f5 <https://github.com/saltstack-formulas/openvpn-formula/commit/33b98f5>`_\ )
* **logging:** set replace=False and add dependencies for log files (\ `9b71fcf <https://github.com/saltstack-formulas/openvpn-formula/commit/9b71fcf>`_\ )
* **macros:** use openvpn/macros.jinja (\ `637387e <https://github.com/saltstack-formulas/openvpn-formula/commit/637387e>`_\ )
* **service:** use OS-specific service name in multi-service setups (\ `b16756c <https://github.com/saltstack-formulas/openvpn-formula/commit/b16756c>`_\ )
* **specs:** use boolean operator (\ `89fa956 <https://github.com/saltstack-formulas/openvpn-formula/commit/89fa956>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **cleanup:** dropped obsolete opensuse-leap-15 workaround (\ `1e1719d <https://github.com/saltstack-formulas/openvpn-formula/commit/1e1719d>`_\ )
* **kitchen:** add kitchen file + testinfra (\ `9c5ee26 <https://github.com/saltstack-formulas/openvpn-formula/commit/9c5ee26>`_\ )
* **kitchen:** rename pillar (\ `4122fc0 <https://github.com/saltstack-formulas/openvpn-formula/commit/4122fc0>`_\ )
* **kitchen:** test/config/pillars: add jinja for user on debian >= 9 (\ `3c7f947 <https://github.com/saltstack-formulas/openvpn-formula/commit/3c7f947>`_\ )
* **kitchen+travis:** modify matrix to include ``develop`` platform (\ `91b5798 <https://github.com/saltstack-formulas/openvpn-formula/commit/91b5798>`_\ )
* **specs:** increased readability (\ `b2c9cf1 <https://github.com/saltstack-formulas/openvpn-formula/commit/b2c9cf1>`_\ )
* **test data:** moved Pillar test data (\ `2fff1ee <https://github.com/saltstack-formulas/openvpn-formula/commit/2fff1ee>`_\ )
* **testing:** added bin/kitchen (\ `15bea7b <https://github.com/saltstack-formulas/openvpn-formula/commit/15bea7b>`_\ )
* **travis:** exclude Fedora 29 from Travis CI (\ `4a1f9ed <https://github.com/saltstack-formulas/openvpn-formula/commit/4a1f9ed>`_\ )
* **travis:** test based on template-formula and `#98 <https://github.com/saltstack-formulas/openvpn-formula/issues/98>`_ (\ `b9daf9b <https://github.com/saltstack-formulas/openvpn-formula/commit/b9daf9b>`_\ )
