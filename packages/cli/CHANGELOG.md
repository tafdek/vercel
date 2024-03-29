# vercel

## 33.6.3

### Patch Changes

- Revert "[cli] extract `isZeroConfigBuild` into utility function (#11316)" ([#11350](https://github.com/vercel/vercel/pull/11350))

## 33.6.2

### Patch Changes

- Added sunset warning to secrets command. ([#11333](https://github.com/vercel/vercel/pull/11333))

- Swap jest for vitest in CLI unit tests ([#11302](https://github.com/vercel/vercel/pull/11302))

- Updated dependencies [[`988f7b75a`](https://github.com/vercel/vercel/commit/988f7b75a27387e84fce541b844f984d2c151980), [`1825b58df`](https://github.com/vercel/vercel/commit/1825b58df8d783e79f0addf262618f422246f4b3)]:
  - @vercel/remix-builder@2.1.5
  - @vercel/build-utils@7.10.0
  - @vercel/node@3.0.25
  - @vercel/static-build@2.4.5

## 33.6.1

### Patch Changes

- Don't send `projectSettings.nodeVersion` for unsupported versions ([#11277](https://github.com/vercel/vercel/pull/11277))

- Updated dependencies [[`4bca0c6d0`](https://github.com/vercel/vercel/commit/4bca0c6d0bc25052b95bd02b12a0b891c86c4b49), [`a67ad4b5a`](https://github.com/vercel/vercel/commit/a67ad4b5a130bf0e56e18111b3f9ddad69cec0e1), [`11218a179`](https://github.com/vercel/vercel/commit/11218a179870a5420c5a6ff720cd4aec4f7e1c5e), [`64b97bf4b`](https://github.com/vercel/vercel/commit/64b97bf4b5203ecf9a95f63ce26a5c3360208966)]:
  - @vercel/next@4.1.6
  - @vercel/remix-builder@2.1.4
  - @vercel/build-utils@7.9.1
  - @vercel/static-build@2.4.4
  - @vercel/node@3.0.24

## 33.6.0

### Minor Changes

- Set `projectSettings.nodeVersion` in `vc deploy` based on "engines.node" field ([#11261](https://github.com/vercel/vercel/pull/11261))

### Patch Changes

- Stops warning about legacy Speed Insights for Next.js apps ([#11268](https://github.com/vercel/vercel/pull/11268))

- Fix framework version detection in monorepos ([#11212](https://github.com/vercel/vercel/pull/11212))

- Updated dependencies [[`8ea93839c`](https://github.com/vercel/vercel/commit/8ea93839ccc70816f3ece9d7cfdb857aa7a4b015), [`58ef91bfe`](https://github.com/vercel/vercel/commit/58ef91bfe8c2e7176e8783cc4eb91ee8580c70dc)]:
  - @vercel/build-utils@7.9.0
  - @vercel/remix-builder@2.1.3
  - @vercel/node@3.0.23
  - @vercel/static-build@2.4.3

## 33.5.5

### Patch Changes

- Rename variants to flags and remove legacy flags ([#11121](https://github.com/vercel/vercel/pull/11121))

- fix vc with root dir issues ([#11243](https://github.com/vercel/vercel/pull/11243))

- Updated dependencies [[`908e7837d`](https://github.com/vercel/vercel/commit/908e7837d55bc02e708f402c700e00208415e954), [`5e3656ec1`](https://github.com/vercel/vercel/commit/5e3656ec1b3f0561091636582715ba09ddd8cb2d), [`a53d1b0d3`](https://github.com/vercel/vercel/commit/a53d1b0d38efa9637f8b8f81a70898add87530e3)]:
  - @vercel/build-utils@7.8.0
  - @vercel/next@4.1.5
  - @vercel/remix-builder@2.1.2
  - @vercel/node@3.0.22
  - @vercel/static-build@2.4.2

## 33.5.4

### Patch Changes

- [build-utils] increase max memory limit ([#11209](https://github.com/vercel/vercel/pull/11209))

- Updated dependencies [[`b1d8b83ab`](https://github.com/vercel/vercel/commit/b1d8b83abbf23a3485aedb490992d0a3bf44573f), [`37b193c84`](https://github.com/vercel/vercel/commit/37b193c845d8b63d93bb0017fbc1a6a35306ef1f), [`20237d4f7`](https://github.com/vercel/vercel/commit/20237d4f7b55b0697b57db15636c11204cb0dc39), [`f8fab639b`](https://github.com/vercel/vercel/commit/f8fab639bf49a60389b8d0b7b265a737c17b4ae1), [`6ed0fe6fb`](https://github.com/vercel/vercel/commit/6ed0fe6fb1e487545a790ff5b9fc691cf625f005)]:
  - @vercel/next@4.1.4
  - @vercel/build-utils@7.7.1
  - @vercel/remix-builder@2.1.1
  - @vercel/static-build@2.4.1
  - @vercel/node@3.0.21

## 33.5.3

### Patch Changes

- Updated dependencies [[`c2d99855e`](https://github.com/vercel/vercel/commit/c2d99855ea6132380434ed29643120680f95fad7), [`1333071a3`](https://github.com/vercel/vercel/commit/1333071a3a2d324679327bfdd4e872f8fd3521c6)]:
  - @vercel/next@4.1.3
  - @vercel/remix-builder@2.1.0

## 33.5.2

### Patch Changes

- Updated dependencies [[`e109e3325`](https://github.com/vercel/vercel/commit/e109e3325ab5299da0903034175fabe72d486a4e), [`d17abf463`](https://github.com/vercel/vercel/commit/d17abf463acabf9e1e43b91200f18efd34e91f62), [`644721a90`](https://github.com/vercel/vercel/commit/644721a90da8cf98414d272be9da0a821a2ce217), [`ea0e9aeae`](https://github.com/vercel/vercel/commit/ea0e9aeaec8ddddb5a726be0d252df9cdbd84808), [`e318a0eea`](https://github.com/vercel/vercel/commit/e318a0eea55c9b8536b0874f66cfd03aca6f0adf), [`1fee87e76`](https://github.com/vercel/vercel/commit/1fee87e76f18d2f5e5524247cfce615fa1832e49), [`bfc01fd98`](https://github.com/vercel/vercel/commit/bfc01fd98f760a008d0d2e6c52b5216503b44b75), [`7910f2f30`](https://github.com/vercel/vercel/commit/7910f2f3070ff69742e845e795d4db77d598c181), [`440ef3ba9`](https://github.com/vercel/vercel/commit/440ef3ba98af8f05e7714c86c67c36dbda11e85c)]:
  - @vercel/remix-builder@2.0.20
  - @vercel/next@4.1.2
  - @vercel/node@3.0.20
  - @vercel/redwood@2.0.8

## 33.5.1

### Patch Changes

- build: upgrade edge-runtime ([#11148](https://github.com/vercel/vercel/pull/11148))

- Updated dependencies [[`24c3dd282`](https://github.com/vercel/vercel/commit/24c3dd282d7714cd63d2b94fb94745c45fdc79ab), [`10e200e0b`](https://github.com/vercel/vercel/commit/10e200e0bf8f692b6740e098e0572b4e7de83850), [`678ebbe52`](https://github.com/vercel/vercel/commit/678ebbe5255766656bf2dddc574e86b2999f11c8)]:
  - @vercel/build-utils@7.7.0
  - @vercel/static-build@2.4.0
  - @vercel/node@3.0.19

## 33.5.0

### Minor Changes

- Mark `flags` as deprecated and replace them with `variants` ([#11098](https://github.com/vercel/vercel/pull/11098))

### Patch Changes

- Updated dependencies [[`c32a909af`](https://github.com/vercel/vercel/commit/c32a909afcedf0ee55777d5dcaecc0c8383dd8c8), [`b6ed28b9b`](https://github.com/vercel/vercel/commit/b6ed28b9b1712f882c93fe053b70d3eb1df21819), [`d21bb9f87`](https://github.com/vercel/vercel/commit/d21bb9f87e1d837666fe8104d4e199b2590725d6), [`4027a1833`](https://github.com/vercel/vercel/commit/4027a1833718a92be74b2b3c5a4df23745d19a36), [`8ba0ce932`](https://github.com/vercel/vercel/commit/8ba0ce932434c6295fedb5307bee59a804b7e6a8), [`0d034b682`](https://github.com/vercel/vercel/commit/0d034b6820c0f3252949c0ffc483048c5aac7f04), [`abaa700ce`](https://github.com/vercel/vercel/commit/abaa700cea44c723cfc851baa2dfe9e1ae2e8a5c), [`3bad73401`](https://github.com/vercel/vercel/commit/3bad73401b4ec1f61e515965732cde8dcc052b17)]:
  - @vercel/next@4.1.1
  - @vercel/node@3.0.18
  - @vercel/redwood@2.0.7
  - @vercel/remix-builder@2.0.19
  - @vercel/build-utils@7.6.0
  - @vercel/static-build@2.3.0

## 33.4.1

### Patch Changes

- Updated dependencies [[`d05e41eea`](https://github.com/vercel/vercel/commit/d05e41eeaf97a024157d2bd843782c95c39389be), [`de63e3562`](https://github.com/vercel/vercel/commit/de63e356223467447cda539ddc435a892303afc7)]:
  - @vercel/static-build@2.2.0

## 33.4.0

### Minor Changes

- Added a new option to add a sensitive environment variable ([#11033](https://github.com/vercel/vercel/pull/11033))

## 33.3.0

### Minor Changes

- Emit "filePathMap" in `vc-config.json` for `FileFsRef` instances ([#11060](https://github.com/vercel/vercel/pull/11060))

### Patch Changes

- Update `vc dev` to support `Lambda` instances without `zipBuffer` ([#11080](https://github.com/vercel/vercel/pull/11080))

- Updated dependencies [[`322c88536`](https://github.com/vercel/vercel/commit/322c88536dfa0ba3892eb580858ee54f6b04ed3f), [`62ca2efa7`](https://github.com/vercel/vercel/commit/62ca2efa731c4df46d586b94078b2dcb1c0bb934)]:
  - @vercel/ruby@2.0.5
  - @vercel/python@4.1.1

## 33.2.0

### Minor Changes

- chore: deprecate next/nuxt/gastby Speed Insights injection in favor of @vercel/speed-insights ([#11048](https://github.com/vercel/vercel/pull/11048))

### Patch Changes

- fix error when @vercel/analytics is a transitive dependency of the deployed application ([#10892](https://github.com/vercel/vercel/pull/10892))

- [cli] Add documentation string for `skip-domain` option ([#11051](https://github.com/vercel/vercel/pull/11051))

- Updated dependencies [[`260125784`](https://github.com/vercel/vercel/commit/2601257846fa201fc9efde021a906c706f6191aa), [`cdddb33ad`](https://github.com/vercel/vercel/commit/cdddb33ad49f6080c49f4fff3767e6111acd0bbe), [`72d8604c9`](https://github.com/vercel/vercel/commit/72d8604c9dba108ccca41d6288b765a7ba727295), [`90d0455e1`](https://github.com/vercel/vercel/commit/90d0455e1ff7b5892ff4960226535f57f704ef6f), [`0716130e5`](https://github.com/vercel/vercel/commit/0716130e580a920d92d249d029ed37f92f2ca847), [`b6b151f39`](https://github.com/vercel/vercel/commit/b6b151f3917c5cb47226951446b9dbb96c7d872b), [`b185a7e20`](https://github.com/vercel/vercel/commit/b185a7e207b153c378bd3db2618eece3a3b6a93e)]:
  - @vercel/static-build@2.1.0
  - @vercel/build-utils@7.5.1
  - @vercel/next@4.1.0
  - @vercel/remix-builder@2.0.18
  - @vercel/node@3.0.17

## 33.1.0

### Minor Changes

- Serialize duplicate `EdgeFunction` references as symlinks in `vc build` ([#11027](https://github.com/vercel/vercel/pull/11027))

### Patch Changes

- Handle rate limit response when fetching /teams ([#11013](https://github.com/vercel/vercel/pull/11013))

- Display actual deployment's 'target' ([#11025](https://github.com/vercel/vercel/pull/11025))

- Updated dependencies [[`98040ec24`](https://github.com/vercel/vercel/commit/98040ec24e1ee585865d11eb216b6525d39d209e)]:
  - @vercel/build-utils@7.5.0
  - @vercel/static-build@2.0.17
  - @vercel/hydrogen@1.0.2
  - @vercel/remix-builder@2.0.17
  - @vercel/node@3.0.16

## 33.0.2

### Patch Changes

- Log extension execution failures ([#10937](https://github.com/vercel/vercel/pull/10937))

- Updated dependencies [[`fbe08fe57`](https://github.com/vercel/vercel/commit/fbe08fe57eededc0bcd2409692b23d185c70069d), [`77585013d`](https://github.com/vercel/vercel/commit/77585013dec5fc406b8b7ea00918e49fdb8f10ec), [`c536a74bc`](https://github.com/vercel/vercel/commit/c536a74bc9e7188a87b292615fa88d6fc506b105), [`91f8763ed`](https://github.com/vercel/vercel/commit/91f8763edce672a3c05b6096db6084f1e6741384), [`7f8f5f865`](https://github.com/vercel/vercel/commit/7f8f5f86516934acb0c4b936ea601433c8d30c5c)]:
  - @vercel/next@4.0.17
  - @vercel/go@3.0.5
  - @vercel/node@3.0.15
  - @vercel/redwood@2.0.6
  - @vercel/remix-builder@2.0.16

## 33.0.1

### Patch Changes

- Updated dependencies [[`67fa2f3dd`](https://github.com/vercel/vercel/commit/67fa2f3dd6a6d5a3504b7f9081e56deff7b36eab), [`7b0adf371`](https://github.com/vercel/vercel/commit/7b0adf371bae64d33ed0a1b966fc50b1f7c9639b)]:
  - @vercel/build-utils@7.4.1
  - @vercel/next@4.0.16
  - @vercel/static-build@2.0.16
  - @vercel/node@3.0.14

## 33.0.0

### Major Changes

- [cli] replace `--deprecated` with `--update-required` in `vc project ls` ([#10965](https://github.com/vercel/vercel/pull/10965))

### Patch Changes

- Fix `vercel bisect` selecting too many deployments ([#10956](https://github.com/vercel/vercel/pull/10956))

- Updated dependencies [[`6a9002f22`](https://github.com/vercel/vercel/commit/6a9002f2296c5ccce4522c0fa9a8938c3d7a4849), [`4d63d9e95`](https://github.com/vercel/vercel/commit/4d63d9e954549d811063d259250d1865b7de2ba1)]:
  - @vercel/remix-builder@2.0.15
  - @vercel/build-utils@7.4.0
  - @vercel/static-build@2.0.15
  - @vercel/node@3.0.13

## 32.7.2

### Patch Changes

- [cli] Use new `deprecated` query param in projects api for `vc project ls --deprecated` ([#10938](https://github.com/vercel/vercel/pull/10938))

## 32.7.1

### Patch Changes

- [cli] double page limit for vc project ls --deprecated ([#10932](https://github.com/vercel/vercel/pull/10932))

- Updated dependencies [[`d09dd1794`](https://github.com/vercel/vercel/commit/d09dd1794b5ffa28c15d3ad2880b90db2f4c06f0)]:
  - @vercel/remix-builder@2.0.14

## 32.7.0

### Minor Changes

- [cli] add `--deprecated` option to `vc project ls` command ([#10919](https://github.com/vercel/vercel/pull/10919))

### Patch Changes

- Remove some debug statements and make log into warning ([#10926](https://github.com/vercel/vercel/pull/10926))

- Updated dependencies [[`3cede43ca`](https://github.com/vercel/vercel/commit/3cede43ca7ea3aec3ff33864b7d33da57891ddb2), [`dfe47f6e6`](https://github.com/vercel/vercel/commit/dfe47f6e6c1d395ae24d802f4b7c98e39b9f90f4), [`1dbb22bb6`](https://github.com/vercel/vercel/commit/1dbb22bb6d33657faa78376f527fe350188c5257), [`204c3592c`](https://github.com/vercel/vercel/commit/204c3592c78fc544e62f0210b0e7e1e4cd382a0c)]:
  - @vercel/ruby@2.0.4
  - @vercel/build-utils@7.3.0
  - @vercel/remix-builder@2.0.13
  - @vercel/node@3.0.12
  - @vercel/static-build@2.0.14

## 32.6.1

### Patch Changes

- Revert "forbids globally installed @vercel/speed-insights and @vercel/analytics (#10848)" ([#10895](https://github.com/vercel/vercel/pull/10895))

## 32.6.0

### Minor Changes

- forbids globally installed @vercel/speed-insights and @vercel/analytics ([#10848](https://github.com/vercel/vercel/pull/10848))

### Patch Changes

- [cli] Fix behavior for combination of northstar user + team scope provided to cli as an argument. ([#10884](https://github.com/vercel/vercel/pull/10884))

- Updated dependencies [[`4edfcd74b`](https://github.com/vercel/vercel/commit/4edfcd74b6dfd8e9cbc05a71d47578051a2a7d63), [`0e9bb30fd`](https://github.com/vercel/vercel/commit/0e9bb30fd285492beadc365bece2ab1df67b387b), [`ca2cbf06f`](https://github.com/vercel/vercel/commit/ca2cbf06fbf252e23aff6e007d0df5ffc243b56e), [`c52bdf775`](https://github.com/vercel/vercel/commit/c52bdf77585dfa41b25cabe2f9403827d0964169)]:
  - @vercel/remix-builder@2.0.12
  - @vercel/static-build@2.0.13
  - @vercel/go@3.0.4

## 32.5.6

### Patch Changes

- Updated dependencies [[`ffd2f34c6`](https://github.com/vercel/vercel/commit/ffd2f34c6c3d53bbb673aa3241845abc50e67c5e), [`4636ae54c`](https://github.com/vercel/vercel/commit/4636ae54c6c17709c1a058169cdca19c3df73ddb)]:
  - @vercel/next@4.0.15
  - @vercel/ruby@2.0.3

## 32.5.5

### Patch Changes

- Updated dependencies [[`88da7463c`](https://github.com/vercel/vercel/commit/88da7463ce12df91d49fbde85cb617030d55f558)]:
  - @vercel/build-utils@7.2.5
  - @vercel/node@3.0.11
  - @vercel/static-build@2.0.12

## 32.5.4

### Patch Changes

- Updated dependencies [[`65dec5b7e`](https://github.com/vercel/vercel/commit/65dec5b7e752f4da8fe0ffdb25215170453f6f8b)]:
  - @vercel/build-utils@7.2.4
  - @vercel/node@3.0.10
  - @vercel/static-build@2.0.11

## 32.5.3

### Patch Changes

- Handle `TooManyProjects` error in places where projects are created ([#10807](https://github.com/vercel/vercel/pull/10807))

- Updated dependencies [[`89c1e0323`](https://github.com/vercel/vercel/commit/89c1e032335d9ec0fcfc84fe499cf004fe73fafc), [`fd29b966d`](https://github.com/vercel/vercel/commit/fd29b966d39776318b0e11a53909edb43d1fc5f2)]:
  - @vercel/node@3.0.9
  - @vercel/next@4.0.14

## 32.5.2

### Patch Changes

- Updated dependencies [[`c94a082f6`](https://github.com/vercel/vercel/commit/c94a082f6bb1b84eaf420ac47ea83640dc83668e)]:
  - @vercel/next@4.0.13

## 32.5.1

### Patch Changes

- Debug log load user exceptions ([#10773](https://github.com/vercel/vercel/pull/10773))

- bump: edge-runtime ([#10712](https://github.com/vercel/vercel/pull/10712))

- Updated dependencies [[`fc90a3dc0`](https://github.com/vercel/vercel/commit/fc90a3dc0bd998453f6527c03d211c35bb0d5770), [`644b8a52c`](https://github.com/vercel/vercel/commit/644b8a52cb2cc8f05e215e2230f95f902cdf8ae8), [`0861dc8fb`](https://github.com/vercel/vercel/commit/0861dc8fbcea1037626b00664a4b6c22f1b0a7ed), [`33cc8e0ac`](https://github.com/vercel/vercel/commit/33cc8e0acf1b3466d50d45b2e5bbe66b89a87c14), [`f5296c3c0`](https://github.com/vercel/vercel/commit/f5296c3c06e620a39c5f88287ac94e58703bdaac), [`d9065c210`](https://github.com/vercel/vercel/commit/d9065c2102223e9cdb5b22df14db41c363cf7828)]:
  - @vercel/next@4.0.12
  - @vercel/node@3.0.8
  - @vercel/build-utils@7.2.3
  - @vercel/remix-builder@2.0.11
  - @vercel/static-build@2.0.10

## 32.5.0

### Minor Changes

- Indicates whether @vercel/speed-insights or @vercel/analytics are used ([#10623](https://github.com/vercel/vercel/pull/10623))

- [cli] update env var validation rule to allow name start with underscore ([#10697](https://github.com/vercel/vercel/pull/10697))

### Patch Changes

- Updated dependencies [[`da300030c`](https://github.com/vercel/vercel/commit/da300030c999b3555c608a321c9d0a4d36923a5a), [`de84743e1`](https://github.com/vercel/vercel/commit/de84743e10d4c9701d409355c0fe057f35e6e435), [`913608de4`](https://github.com/vercel/vercel/commit/913608de4dd4e37557533d732ca8449a5737d4a6), [`7fa08088e`](https://github.com/vercel/vercel/commit/7fa08088ea0d5df6955ea4af7f08513cf4027bb3)]:
  - @vercel/next@4.0.11
  - @vercel/python@4.1.0
  - @vercel/remix-builder@2.0.10
  - @vercel/redwood@2.0.5
  - @vercel/static-build@2.0.9

## 32.4.1

### Patch Changes

- Updated dependencies [[`c523a755f`](https://github.com/vercel/vercel/commit/c523a755f8e4bc41f7c353ebc0b939c21703df00), [`58215906f`](https://github.com/vercel/vercel/commit/58215906f9ee28da3a7f2f3f4aeb862ab53bf55e)]:
  - @vercel/next@4.0.10

## 32.4.0

### Minor Changes

- Restore unsetting teamId for non-team accounts ([#10612](https://github.com/vercel/vercel/pull/10612))

### Patch Changes

- remove unused source map pkg ([#10577](https://github.com/vercel/vercel/pull/10577))

- disable source map for prod build ([#10575](https://github.com/vercel/vercel/pull/10575))

- Better rendering upon authentication error in `vc cert ls` ([#10551](https://github.com/vercel/vercel/pull/10551))

- Updated dependencies [[`e9026c7a6`](https://github.com/vercel/vercel/commit/e9026c7a692937122e60e73b91100cf7009e022d), [`ea5bc8806`](https://github.com/vercel/vercel/commit/ea5bc8806276abf5ba14bdb4a966267497e5d14d), [`a4996e1c5`](https://github.com/vercel/vercel/commit/a4996e1c5a7e6986d5410b662014dc584c0f7c54), [`a18ed98f2`](https://github.com/vercel/vercel/commit/a18ed98f2df78fe1256410ea8676686564ed9b35), [`2f5b0aeeb`](https://github.com/vercel/vercel/commit/2f5b0aeeb183ed3ea8cbc68cb3bc3c949c486ada), [`09f1bbfa4`](https://github.com/vercel/vercel/commit/09f1bbfa41a87cf0063a3fb3022b7531d03862b5), [`ce7e82fa7`](https://github.com/vercel/vercel/commit/ce7e82fa7aa6cec5f5d7b4953353b297b7ad1694)]:
  - @vercel/next@4.0.9
  - @vercel/go@3.0.3
  - @vercel/build-utils@7.2.2
  - @vercel/node@3.0.7
  - @vercel/redwood@2.0.4
  - @vercel/remix-builder@2.0.9
  - @vercel/static-build@2.0.8

## 32.3.1

### Patch Changes

- Use "esbuild" to build CLI ([#10555](https://github.com/vercel/vercel/pull/10555))

- Updated dependencies [[`9f63ca60a`](https://github.com/vercel/vercel/commit/9f63ca60ad914af0f7ba18c9bbe1656eeea68a0a), [`e3f9faf51`](https://github.com/vercel/vercel/commit/e3f9faf513bd97900d8966f2f1116fc3ca07221b)]:
  - @vercel/next@4.0.8
  - @vercel/remix-builder@2.0.8

## 32.3.0

### Minor Changes

- [cli] Support northstar users ([#10535](https://github.com/vercel/vercel/pull/10535))

### Patch Changes

- Internal variants ([#10549](https://github.com/vercel/vercel/pull/10549))

- [speed insights] Prepare for migration to new speed insights package ([#10500](https://github.com/vercel/vercel/pull/10500))

- Updated dependencies [[`b0898a665`](https://github.com/vercel/vercel/commit/b0898a66591d5296dc38ffcf0e8345c9338b72f3), [`10d4e51ac`](https://github.com/vercel/vercel/commit/10d4e51ac57b76f05ddc0bf3adf220e2490244fc), [`decdf27fb`](https://github.com/vercel/vercel/commit/decdf27fb5ca914fe50a9320c4fd50ef79d2fbb3), [`f5ca497b7`](https://github.com/vercel/vercel/commit/f5ca497b7522a2dad637cef238da9716ac133057), [`ab329f0fe`](https://github.com/vercel/vercel/commit/ab329f0fe88e9cb72607d0cba41f5e168d77e077), [`d0d052011`](https://github.com/vercel/vercel/commit/d0d0520111264434d57d5920de0f622f6a2588dc), [`9bb3067de`](https://github.com/vercel/vercel/commit/9bb3067de28be77f3ce268a31a7aa6184836dfb1)]:
  - @vercel/static-build@2.0.7
  - @vercel/node@3.0.6
  - @vercel/build-utils@7.2.1
  - @vercel/next@4.0.7
  - @vercel/python@4.0.2
  - @vercel/redwood@2.0.3
  - @vercel/remix-builder@2.0.7
  - @vercel/go@3.0.2

## 32.2.5

### Patch Changes

- Updated dependencies [[`849eedf0f`](https://github.com/vercel/vercel/commit/849eedf0f2841211e4175d374f1cf01330bf9611), [`f6f16b034`](https://github.com/vercel/vercel/commit/f6f16b0347bac9f5c33c79ccb1fb9fd9d254cae5), [`3035e18fb`](https://github.com/vercel/vercel/commit/3035e18fb67dfe7031e235a74136a41948f86d5a), [`cb784aeb9`](https://github.com/vercel/vercel/commit/cb784aeb9c9e4eddf1c65b61849a87edb1117af1)]:
  - @vercel/next@4.0.6
  - @vercel/remix-builder@2.0.6

## 32.2.4

### Patch Changes

- Add support for bun detection in monorepo ([#10511](https://github.com/vercel/vercel/pull/10511))

- Updated dependencies [[`1b6f3a0f6`](https://github.com/vercel/vercel/commit/1b6f3a0f6534f71c7486a4e33ac199f1da330626)]:
  - @vercel/static-build@2.0.6

## 32.2.3

### Patch Changes

- Updated dependencies [[`083aad448`](https://github.com/vercel/vercel/commit/083aad448e45edae296da3201eec9f890a01d22d)]:
  - @vercel/next@4.0.5

## 32.2.2

### Patch Changes

- Updated dependencies [[`7a0fed970`](https://github.com/vercel/vercel/commit/7a0fed970c39cb8f4df70544ded3284d3538b06a), [`2f461a8b0`](https://github.com/vercel/vercel/commit/2f461a8b0bcbdd05da0516395c2905c2d0242682), [`1bab21026`](https://github.com/vercel/vercel/commit/1bab21026ec0bb8a4a8fbeac3d6e4a197f1030fd)]:
  - @vercel/next@4.0.4
  - @vercel/remix-builder@2.0.5

## 32.2.1

### Patch Changes

- Update @vercel/fun@1.1.0 ([#10477](https://github.com/vercel/vercel/pull/10477))

- [node] upgrade edge-runtime ([#10451](https://github.com/vercel/vercel/pull/10451))

- Updated dependencies [[`6784e7751`](https://github.com/vercel/vercel/commit/6784e77516ba180a691e3c48323b32bb4506d7b6), [`a8ad17626`](https://github.com/vercel/vercel/commit/a8ad176262ef822860ce338927e6f959961d2d32), [`0ee089a50`](https://github.com/vercel/vercel/commit/0ee089a501ebb78901c4afe1658e794917998f8f), [`f15cba614`](https://github.com/vercel/vercel/commit/f15cba6148a0cdb6975db7724775c35ab7d929b2), [`b265e13d4`](https://github.com/vercel/vercel/commit/b265e13d40d541b77148fa79ac60b4c4dd10974c), [`50e04dd85`](https://github.com/vercel/vercel/commit/50e04dd8584664c842a86c15d92d654f4ea8dcbb), [`45b73c7e8`](https://github.com/vercel/vercel/commit/45b73c7e86458564dc0bab007f6f6365c4c4ab5d), [`a732d30c8`](https://github.com/vercel/vercel/commit/a732d30c8409f96f59ea5406e974a6c4186cc130), [`9d64312aa`](https://github.com/vercel/vercel/commit/9d64312aaaa875a4e193b7602c50e5dc68979aad), [`6baefc825`](https://github.com/vercel/vercel/commit/6baefc825ad7cfc3a5edce31cb4244721452f753), [`989f0d813`](https://github.com/vercel/vercel/commit/989f0d813910d8d67ed355de93018f1dcd91b6ba), [`d8bc570f6`](https://github.com/vercel/vercel/commit/d8bc570f604950d97156d4f33c8accecf3b3b28f)]:
  - @vercel/go@3.0.1
  - @vercel/redwood@2.0.2
  - @vercel/remix-builder@2.0.4
  - @vercel/hydrogen@1.0.1
  - @vercel/static-build@2.0.5
  - @vercel/build-utils@7.2.0
  - @vercel/next@4.0.3
  - @vercel/node@3.0.5
  - @vercel/python@4.0.1
  - @vercel/ruby@2.0.2

## 32.2.0

### Minor Changes

- show instant preview url on deploy ([#10458](https://github.com/vercel/vercel/pull/10458))

### Patch Changes

- N, not n. ([#10460](https://github.com/vercel/vercel/pull/10460))

- Fix team URL on `vercel help switch` ([#10466](https://github.com/vercel/vercel/pull/10466))

- Migrates the vc env command to the command data structure for use in the help output. ([#10429](https://github.com/vercel/vercel/pull/10429))

- Update domains command to new structure ([#10427](https://github.com/vercel/vercel/pull/10427))

- Updated semver dependency ([#10411](https://github.com/vercel/vercel/pull/10411))

- migrate `rollback` command structure for help output ([#10426](https://github.com/vercel/vercel/pull/10426))

- migrate `inti` command structure for help output ([#10428](https://github.com/vercel/vercel/pull/10428))

- Remove mri workaround ([#10452](https://github.com/vercel/vercel/pull/10452))

- migrate dev command structure for help output ([#10433](https://github.com/vercel/vercel/pull/10433))

- Update secrets to more recent structure ([#10461](https://github.com/vercel/vercel/pull/10461))

- Migrate `vc secrets` to new help command structure ([#10435](https://github.com/vercel/vercel/pull/10435))

- migrate `promote` command structure for help output ([#10425](https://github.com/vercel/vercel/pull/10425))

- migrate `git` command structure for help output ([#10431](https://github.com/vercel/vercel/pull/10431))

- Update project command to new data structure ([#10432](https://github.com/vercel/vercel/pull/10432))

- migrate teams command ([#10434](https://github.com/vercel/vercel/pull/10434))

- Updated dependencies [[`5609a1187`](https://github.com/vercel/vercel/commit/5609a1187be9d6cf8d5f16825690c5ea72f17dc5), [`caaba0d68`](https://github.com/vercel/vercel/commit/caaba0d6855eff4350b6a04acc3ea502025bff8f), [`1b4de4a98`](https://github.com/vercel/vercel/commit/1b4de4a986f7a612aac834ebae3ec7bb9e9b8cf8), [`c3c54d6e6`](https://github.com/vercel/vercel/commit/c3c54d6e695ec078777c4b1f4f23acbeee3c3b09), [`6aa0aa4e6`](https://github.com/vercel/vercel/commit/6aa0aa4e65b81903f4fce677a198dcfaebee744b), [`e43191b18`](https://github.com/vercel/vercel/commit/e43191b1866da70a3dab3815a3f2176942240ef3), [`fc1e13c09`](https://github.com/vercel/vercel/commit/fc1e13c09928c654410b373fc1775c2b63c6ef4a)]:
  - @vercel/build-utils@7.1.1
  - @vercel/next@4.0.2
  - @vercel/static-build@2.0.4
  - @vercel/redwood@2.0.1
  - @vercel/remix-builder@2.0.3
  - @vercel/ruby@2.0.1
  - @vercel/node@3.0.4

## 32.1.0

### Minor Changes

- Improve error messages for JSON parse failures ([#10396](https://github.com/vercel/vercel/pull/10396))

### Patch Changes

- Updated dependencies [[`9e3827c78`](https://github.com/vercel/vercel/commit/9e3827c785e1bc45f2bed421132167381481770f)]:
  - @vercel/build-utils@7.1.0
  - @vercel/node@3.0.3
  - @vercel/remix-builder@2.0.2
  - @vercel/static-build@2.0.3

## 32.0.2

### Patch Changes

- Remove use of mri preferring use of arg package ([#10389](https://github.com/vercel/vercel/pull/10389))

- upgrade edge-runtime ([#10385](https://github.com/vercel/vercel/pull/10385))

- Update dns commands to new structure ([#10379](https://github.com/vercel/vercel/pull/10379))

- Updated dependencies [[`09446a8fe`](https://github.com/vercel/vercel/commit/09446a8fe8b8201dbe3ead3ca645ef0aa1833b6b), [`597a8a817`](https://github.com/vercel/vercel/commit/597a8a81764c39e70c65b98e78bf4c3827a779a7), [`442232686`](https://github.com/vercel/vercel/commit/44223268651f1bbd5c6f2b0b315239685dd5716e), [`3f6d99470`](https://github.com/vercel/vercel/commit/3f6d99470db86681e006d66507f32afcea086b41), [`37e93a91a`](https://github.com/vercel/vercel/commit/37e93a91a8659934eac7f5cd441b310511bf5646)]:
  - @vercel/next@4.0.1
  - @vercel/node@3.0.2
  - @vercel/remix-builder@2.0.1
  - @vercel/static-build@2.0.2

## 32.0.1

### Patch Changes

- Add `--git-branch` to pull command help output ([#10382](https://github.com/vercel/vercel/pull/10382))

- Update new help structure to support subcommands ([#10372](https://github.com/vercel/vercel/pull/10372))

- Migrate certs command to new structure ([#10377](https://github.com/vercel/vercel/pull/10377))

- Updated dependencies []:
  - @vercel/static-build@2.0.1
  - @vercel/node@3.0.1

## 32.0.0

### Major Changes

- BREAKING CHANGE: Drop Node.js 14, bump minimum to Node.js 16 ([#10369](https://github.com/vercel/vercel/pull/10369))

### Patch Changes

- text wrap help output description ([#10370](https://github.com/vercel/vercel/pull/10370))

- Updated dependencies [[`37f5c6270`](https://github.com/vercel/vercel/commit/37f5c6270058336072ca733673ea72dd6c56bd6a), [`09174df6c`](https://github.com/vercel/vercel/commit/09174df6cfbe697ea13e75468b9cd3c6ec7ad01c)]:
  - @vercel/build-utils@7.0.0
  - @vercel/go@3.0.0
  - @vercel/hydrogen@1.0.0
  - @vercel/next@4.0.0
  - @vercel/node@3.0.0
  - @vercel/python@4.0.0
  - @vercel/redwood@2.0.0
  - @vercel/remix-builder@2.0.0
  - @vercel/ruby@2.0.0
  - @vercel/static-build@2.0.0

## 31.4.0

### Minor Changes

- Force-publish ([#10358](https://github.com/vercel/vercel/pull/10358))

### Patch Changes

- Updated dependencies [[`6e44757ff`](https://github.com/vercel/vercel/commit/6e44757ff5d7d80ba6db2ab5ea65213392ecf1cd)]:
  - @vercel/static-build@1.4.0

## 31.3.1

### Patch Changes

- Updated dependencies [[`844fb6e88`](https://github.com/vercel/vercel/commit/844fb6e880a980f26945f15a7437b4d67bcb5394)]:
  - @vercel/remix-builder@1.10.1

## 31.3.0

### Minor Changes

- Update help output to use cli-table3 ([#10333](https://github.com/vercel/vercel/pull/10333))

### Patch Changes

- Sanitize argv in log during `vc build`. ([#10311](https://github.com/vercel/vercel/pull/10311))

- Respect `--yes` flag for all prompts during `vc link --repo` ([#10337](https://github.com/vercel/vercel/pull/10337))

- Updated dependencies [[`8cb9385fd`](https://github.com/vercel/vercel/commit/8cb9385fd306d0c2b8771d7bb063e6948ed15729), [`94c93dfb5`](https://github.com/vercel/vercel/commit/94c93dfb5b29aa58317f9d0854273d4880d91a62)]:
  - @vercel/node@2.15.10
  - @vercel/static-build@1.3.46

## 31.2.3

### Patch Changes

- Be looser in tests with mock server urls ([#10300](https://github.com/vercel/vercel/pull/10300))

- Handle calls for deployment aliases when mocking deployments ([#10303](https://github.com/vercel/vercel/pull/10303))

- Remove unused code ([#10309](https://github.com/vercel/vercel/pull/10309))

- Updated dependencies [[`5bf1fe4c7`](https://github.com/vercel/vercel/commit/5bf1fe4c743f6be3f7d5a24447ea5b083a68dc67), [`a8ecf40d6`](https://github.com/vercel/vercel/commit/a8ecf40d6f50e2fc8b13b02c8ef50b3dcafad3a6), [`08da4b9c9`](https://github.com/vercel/vercel/commit/08da4b9c923501d9d28eb6e3f26f4605fee83042), [`0945d24cb`](https://github.com/vercel/vercel/commit/0945d24cbe901ca3f0eedd011251ad499c72d472)]:
  - @vercel/next@3.9.4
  - @vercel/build-utils@6.8.3
  - @vercel/remix-builder@1.10.0
  - @vercel/node@2.15.9
  - @vercel/static-build@1.3.45

## 31.2.2

### Patch Changes

- Migrate list command to new structure ([#10284](https://github.com/vercel/vercel/pull/10284))

- Migrate whoami command to new structure ([#10266](https://github.com/vercel/vercel/pull/10266))

- Migrate logs command to new structure ([#10281](https://github.com/vercel/vercel/pull/10281))

- Migrate login command to new structure ([#10283](https://github.com/vercel/vercel/pull/10283))

- Migrate pull command to new structure ([#10280](https://github.com/vercel/vercel/pull/10280))

- Migrate logout command to new structure ([#10282](https://github.com/vercel/vercel/pull/10282))

- Migrate build command to new structure ([#10286](https://github.com/vercel/vercel/pull/10286))

- Migrate inspect command to new structure ([#10277](https://github.com/vercel/vercel/pull/10277))

- Migrate redeploy command to new structure ([#10279](https://github.com/vercel/vercel/pull/10279))

- Migrate link command to new structure ([#10285](https://github.com/vercel/vercel/pull/10285))

- Update spacing of --help output for CLI ([#10287](https://github.com/vercel/vercel/pull/10287))

- Updated dependencies [[`4af242af8`](https://github.com/vercel/vercel/commit/4af242af8633e58b6a9bf920564416da3ef22ad4), [`0cbdae141`](https://github.com/vercel/vercel/commit/0cbdae1411aa7936ff7dfe551919ca5e56cd6e98), [`85dd66778`](https://github.com/vercel/vercel/commit/85dd667781693539d753d587566e53964bbe189d)]:
  - @vercel/node@2.15.8
  - @vercel/remix-builder@1.9.1
  - @vercel/static-build@1.3.44

## 31.2.1

### Patch Changes

- Migrate bisect command to new structure ([#10276](https://github.com/vercel/vercel/pull/10276))

- Migrate remove command to new structure ([#10268](https://github.com/vercel/vercel/pull/10268))

- Updated dependencies [[`fc413707d`](https://github.com/vercel/vercel/commit/fc413707d017e234d5013b761d885f65f9b981bc)]:
  - @vercel/node@2.15.7
  - @vercel/static-build@1.3.43

## 31.2.0

### Minor Changes

- Add a "Global Options" section to help output ([#10250](https://github.com/vercel/vercel/pull/10250))

### Patch Changes

- Updated dependencies [[`d1b0dbe3a`](https://github.com/vercel/vercel/commit/d1b0dbe3a7d8754286aa2b7ba0c8b55d3adafdea), [`4a8622a10`](https://github.com/vercel/vercel/commit/4a8622a10d52260cb629a1c4a6f797ade05ea154), [`6469ef1b8`](https://github.com/vercel/vercel/commit/6469ef1b8ce37e93f50ab4a108aa0953d7631fe8)]:
  - @vercel/remix-builder@1.9.0
  - @vercel/next@3.9.3

## 31.1.1

### Patch Changes

- Updated dependencies [[`7c30b13cc`](https://github.com/vercel/vercel/commit/7c30b13ccb79bdf0ac240282bba4c084f1d0d122)]:
  - @vercel/next@3.9.2

## 31.1.0

### Minor Changes

- Add 'Environment' column to 'vc list' with new '--environment' filter and pipe URLs to stdout ([#10239](https://github.com/vercel/vercel/pull/10239))

### Patch Changes

- Update `proxy-agent` to v6.3.0 ([#10226](https://github.com/vercel/vercel/pull/10226))

- Use `getNodeBinPaths()` in `vc dev` ([#10225](https://github.com/vercel/vercel/pull/10225))

- Updated dependencies [[`b1c14cde0`](https://github.com/vercel/vercel/commit/b1c14cde03f94b2c15ba12c9be9d19c72df2fdbb), [`ce4633fe4`](https://github.com/vercel/vercel/commit/ce4633fe4d00cb5c251cdabbfab08f39ec3f3b5f)]:
  - @vercel/next@3.9.1
  - @vercel/static-build@1.3.42

## 31.0.4

### Patch Changes

- Detect multiple frameworks within the same root directory during `vc link --repo` ([#10203](https://github.com/vercel/vercel/pull/10203))

- Updated dependencies [[`b56639b62`](https://github.com/vercel/vercel/commit/b56639b624e9ad1df048a4c85083e26888696060), [`cae60155f`](https://github.com/vercel/vercel/commit/cae60155f34883f08a5e4f51b547e2a1a5fee694), [`c670e5171`](https://github.com/vercel/vercel/commit/c670e51712022193e078bd68b055f7e61013015d), [`5439d7c0c`](https://github.com/vercel/vercel/commit/5439d7c0c9b79e7161bf4fa84ffdb357365f9e7e)]:
  - @vercel/node@2.15.6
  - @vercel/next@3.9.0
  - @vercel/remix-builder@1.8.18
  - @vercel/static-build@1.3.41

## 31.0.3

### Patch Changes

- Fix redeploy target to be undefined when null ([#10201](https://github.com/vercel/vercel/pull/10201))

- Respect forbidden API responses ([#10178](https://github.com/vercel/vercel/pull/10178))

- Update `supports-hyperlinks` to v3 ([#10208](https://github.com/vercel/vercel/pull/10208))

- Updated dependencies [[`0750517af`](https://github.com/vercel/vercel/commit/0750517af99aea41410d4f1f772ce427699554e7)]:
  - @vercel/build-utils@6.8.2
  - @vercel/static-build@1.3.40
  - @vercel/node@2.15.5
  - @vercel/remix-builder@1.8.17

## 31.0.2

### Patch Changes

- Allow additional project settings in `createProject()` ([#10172](https://github.com/vercel/vercel/pull/10172))

- Run local Project detection during `vc link --repo`. ([#10094](https://github.com/vercel/vercel/pull/10094))
  This allows for creation of new Projects that do not yet exist under the selected scope.

- Redeploy command no longer redeploys preview deployments to production ([#10186](https://github.com/vercel/vercel/pull/10186))

- Added trailing new line at end of help output ([#10170](https://github.com/vercel/vercel/pull/10170))

- Create new help output and arg parsing for deploy command ([#10090](https://github.com/vercel/vercel/pull/10090))

- [cli] Remove `preinstall` script ([#10157](https://github.com/vercel/vercel/pull/10157))

- Updated dependencies [[`7021279b2`](https://github.com/vercel/vercel/commit/7021279b284f314a4d1bdbb4306b4c22291efa08), [`5e5332fbc`](https://github.com/vercel/vercel/commit/5e5332fbc9317a8f3cc4ed0b72ec1a2c76020891), [`027bce00b`](https://github.com/vercel/vercel/commit/027bce00b3821d9b4a8f7ec320cd1c43ab9f4215)]:
  - @vercel/build-utils@6.8.1
  - @vercel/node@2.15.4
  - @vercel/remix-builder@1.8.16
  - @vercel/static-build@1.3.39

## 31.0.1

### Patch Changes

- Updated dependencies [[`aa734efc6`](https://github.com/vercel/vercel/commit/aa734efc6c42badd4aa9bf64487904aa64e9bd49)]:
  - @vercel/next@3.8.8

## 31.0.0

### Major Changes

- Update `vc dev` redirect response to match production behavior ([#10143](https://github.com/vercel/vercel/pull/10143))

### Patch Changes

- require `--yes` to promote preview deployment ([#10135](https://github.com/vercel/vercel/pull/10135))

- [cli] Optimize write build result for vc build ([#10154](https://github.com/vercel/vercel/pull/10154))

- Only show relevant Project matches in Project selector ([#10114](https://github.com/vercel/vercel/pull/10114))

- [cli] Fix error message when token is invalid ([#10131](https://github.com/vercel/vercel/pull/10131))

- Updated dependencies [[`e4895d979`](https://github.com/vercel/vercel/commit/e4895d979b57e369e0618481c5974243887d72cc), [`346892210`](https://github.com/vercel/vercel/commit/3468922108f411482a72acd0331f0f2ee52a6d4c), [`346892210`](https://github.com/vercel/vercel/commit/3468922108f411482a72acd0331f0f2ee52a6d4c), [`a6de052ed`](https://github.com/vercel/vercel/commit/a6de052ed2f09cc80bf4c2d0f06bedd267a63cdc)]:
  - @vercel/next@3.8.7
  - @vercel/static-build@1.3.38
  - @vercel/build-utils@6.8.0
  - @vercel/remix-builder@1.8.15
  - @vercel/node@2.15.3

## 30.2.3

### Patch Changes

- [cli] do not force auto-assign value on deployments ([#10110](https://github.com/vercel/vercel/pull/10110))

- Updated dependencies [[`91406abdb`](https://github.com/vercel/vercel/commit/91406abdb0c332152fc6c7c1e4bd3a872b084434), [`2230ea6cc`](https://github.com/vercel/vercel/commit/2230ea6cc1b84c1f03227a4e197b7684635b5955), [`8b3a4146a`](https://github.com/vercel/vercel/commit/8b3a4146af68d2b7288c80a5b919d832dba929b5)]:
  - @vercel/node@2.15.2
  - @vercel/remix-builder@1.8.14
  - @vercel/static-build@1.3.37

## 30.2.2

### Patch Changes

- [cli] vc env pull should add `.env*.local` to `.gitignore` ([#10085](https://github.com/vercel/vercel/pull/10085))

- [cli] Fix team validation bug where you are apart of a team ([#10092](https://github.com/vercel/vercel/pull/10092))

- Add support for `vc dev` command with repo link ([#10082](https://github.com/vercel/vercel/pull/10082))

- Add support for `vc deploy --prebuilt` command with repo link ([#10083](https://github.com/vercel/vercel/pull/10083))

- Move readme copy logic to a helper function for `vc link` ([#10084](https://github.com/vercel/vercel/pull/10084))

- Add support for `vc pull` command with repo link ([#10078](https://github.com/vercel/vercel/pull/10078))

- Add support for `vc build` command with repo link ([#10075](https://github.com/vercel/vercel/pull/10075))

## 30.2.1

### Patch Changes

- Updated dependencies [[`a04bf557f`](https://github.com/vercel/vercel/commit/a04bf557fc6e1080a117428977d0993dec78b004)]:
  - @vercel/node@2.15.1
  - @vercel/static-build@1.3.36

## 30.2.0

### Minor Changes

- [node] Add isomorphic functions ([#9947](https://github.com/vercel/vercel/pull/9947))

### Patch Changes

- Add `client.fetchPaginated()` helper function ([#10054](https://github.com/vercel/vercel/pull/10054))

- Updated dependencies [[`bc5afe24c`](https://github.com/vercel/vercel/commit/bc5afe24c4547dbf798b939199e8212c4b34038e), [`49c717856`](https://github.com/vercel/vercel/commit/49c7178567ec5bcebe633b598c8c9c0e1aa40fbb), [`0039c8b5c`](https://github.com/vercel/vercel/commit/0039c8b5cea975316a62c4f6aaca5d66d731cc0d)]:
  - @vercel/node@2.15.0
  - @vercel/remix-builder@1.8.13
  - @vercel/static-build@1.3.35

## 30.1.2

### Patch Changes

- Publish missing build-utils ([`cd35071f6`](https://github.com/vercel/vercel/commit/cd35071f609d615d47bc04634c123b33768436cb))

- Updated dependencies [[`cd35071f6`](https://github.com/vercel/vercel/commit/cd35071f609d615d47bc04634c123b33768436cb)]:
  - @vercel/build-utils@6.7.5
  - @vercel/node@2.14.5
  - @vercel/remix-builder@1.8.12
  - @vercel/static-build@1.3.34

## 30.1.1

### Patch Changes

- [cli] vc build ignore '.env\*' & ignore files for '@vercel/static' ([#10056](https://github.com/vercel/vercel/pull/10056))

- [cli] Ensure .npmrc does not contain use-node-version ([#10049](https://github.com/vercel/vercel/pull/10049))

## 30.1.0

### Minor Changes

- New `vc promote` command ([#9984](https://github.com/vercel/vercel/pull/9984))

### Patch Changes

- Support `deploy` subcommand in "repo linked" mode ([#10013](https://github.com/vercel/vercel/pull/10013))

- [cli] Update `vc rollback` to use `lastRequestAlias` instead of `lastRollbackTarget` ([#10019](https://github.com/vercel/vercel/pull/10019))

- Fix `--cwd` flag with a relative path for `env`, `link`, `promote`, and `rollback` subcommands ([#10031](https://github.com/vercel/vercel/pull/10031))

- Updated dependencies [[`c6c19354e`](https://github.com/vercel/vercel/commit/c6c19354e852cfc1338b223058c4b07fdc71c723), [`b56ac2717`](https://github.com/vercel/vercel/commit/b56ac2717d6769eb400f9746f0a05431929b4501), [`c63679ea0`](https://github.com/vercel/vercel/commit/c63679ea0a6bc48c0759ccf3c0c0a8106bd324f0), [`c7bcea408`](https://github.com/vercel/vercel/commit/c7bcea408131df2d65338e50ce319a6d8e4a8a82)]:
  - @vercel/next@3.8.6
  - @vercel/build-utils@6.7.4
  - @vercel/node@2.14.4
  - @vercel/remix-builder@1.8.11
  - @vercel/static-build@1.3.33

## 30.0.0

### Major Changes

- Change `vc env pull` default output file to `.env.local` ([#9892](https://github.com/vercel/vercel/pull/9892))

- Remove `--platform-version` global common arg ([#9807](https://github.com/vercel/vercel/pull/9807))

### Minor Changes

- [cli] implement `vc deploy --prod --skip-build` ([#9836](https://github.com/vercel/vercel/pull/9836))

- New `vc redeploy` command ([#9956](https://github.com/vercel/vercel/pull/9956))

### Patch Changes

- Fix `vercel git connect` command when passing a URL parameter ([#9967](https://github.com/vercel/vercel/pull/9967))

## 29.4.0

### Minor Changes

- Add `vercel link --repo` flag to link to repository (multiple projects), rather than an individual project (alpha) ([#8931](https://github.com/vercel/vercel/pull/8931))

## 29.3.6

### Patch Changes

- Updated dependencies []:
  - @vercel/static-build@1.3.32

## 29.3.5

### Patch Changes

- Updated dependencies [[`2c950d47a`](https://github.com/vercel/vercel/commit/2c950d47aeb22a3de16f983259ea6f37a4555189), [`71b9f3a94`](https://github.com/vercel/vercel/commit/71b9f3a94b7922607f8f24bf7b2bd1742e62cc05), [`f00b08a82`](https://github.com/vercel/vercel/commit/f00b08a82085c3a63059f34f67f10ced92f2979c)]:
  - @vercel/static-build@1.3.31
  - @vercel/build-utils@6.7.3
  - @vercel/next@3.8.5
  - @vercel/node@2.14.3
  - @vercel/remix-builder@1.8.10

## 29.3.4

### Patch Changes

- Updated dependencies [[`67e556bc8`](https://github.com/vercel/vercel/commit/67e556bc80c821c233120a2ec1611adb8e195baa), [`ba10fb4dd`](https://github.com/vercel/vercel/commit/ba10fb4dd4155a75df79b98a0c43a6c42eac7b62)]:
  - @vercel/remix-builder@1.8.9
  - @vercel/next@3.8.4

## 29.3.3

### Patch Changes

- Updated dependencies [[`6c6f3ce9d`](https://github.com/vercel/vercel/commit/6c6f3ce9d228b1e038641e4bafb38c3487e7dff7)]:
  - @vercel/next@3.8.3

## 29.3.2

### Patch Changes

- [vc dev] Fix serverless function size limit condition ([#9961](https://github.com/vercel/vercel/pull/9961))

## 29.3.1

### Patch Changes

- Sort environment variables alphabetically in `vercel env pull` ([#9949](https://github.com/vercel/vercel/pull/9949))
- Skip 50MB zip size limit for Python ([#9944](https://github.com/vercel/vercel/pull/9944))

## 29.3.0

### Minor Changes

- [cli] remove `vc rollback` beta label ([#9928](https://github.com/vercel/vercel/pull/9928))

## 29.2.1

### Patch Changes

- Updated dependencies [[`6d5983eaa`](https://github.com/vercel/vercel/commit/6d5983eaaefe3fd2204f49c3228718ac64a452e3)]:
  - @vercel/remix-builder@1.8.8
