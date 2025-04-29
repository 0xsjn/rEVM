# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [4.0.0](https://github.com/0xsjn/rEVM/compare/revm-context-v3.0.1...revm-context-v4.0.0) - 2025-04-29

### Added

- *(Handler)* merge state validation with deduct_caller ([#2460](https://github.com/0xsjn/rEVM/pull/2460))
- add chain_ref method to ContextTr trait ([#2450](https://github.com/0xsjn/rEVM/pull/2450))
- *(tx)* Add Either RecoveredAuthorization ([#2448](https://github.com/0xsjn/rEVM/pull/2448))
- *(EOF)* Changes needed for devnet-1 ([#2377](https://github.com/0xsjn/rEVM/pull/2377))
- Move SharedMemory buffer to context ([#2382](https://github.com/0xsjn/rEVM/pull/2382))
- cache precompile warming ([#2317](https://github.com/0xsjn/rEVM/pull/2317))
- Add JournalInner ([#2311](https://github.com/0xsjn/rEVM/pull/2311))
- InspectEvm fn renames, inspector docs, book cleanup ([#2275](https://github.com/0xsjn/rEVM/pull/2275))
- Remove PrecompileError from PrecompileProvider ([#2233](https://github.com/0xsjn/rEVM/pull/2233))
- allow reuse of API for calculating initial tx gas for tx ([#2215](https://github.com/0xsjn/rEVM/pull/2215))
- *(docs)* MyEvm example and book cleanup ([#2218](https://github.com/0xsjn/rEVM/pull/2218))
- add custom error to context ([#2197](https://github.com/0xsjn/rEVM/pull/2197))
- Add tx/block to EvmExecution trait ([#2195](https://github.com/0xsjn/rEVM/pull/2195))
- added with_ref_db fn to Context ([#2164](https://github.com/0xsjn/rEVM/pull/2164))
- remove specification crate ([#2165](https://github.com/0xsjn/rEVM/pull/2165))
- make journal entries generic ([#2154](https://github.com/0xsjn/rEVM/pull/2154))
- Standalone Host, remove default fn from context ([#2147](https://github.com/0xsjn/rEVM/pull/2147))
- add constructor with hardfork ([#2135](https://github.com/0xsjn/rEVM/pull/2135))
- implement AccessListTr for Vec ([#2136](https://github.com/0xsjn/rEVM/pull/2136))
- allow host to be implemented on custom context ([#2112](https://github.com/0xsjn/rEVM/pull/2112))
- add the debug impl for Evm and EvmData type ([#2126](https://github.com/0xsjn/rEVM/pull/2126))
- book structure ([#2082](https://github.com/0xsjn/rEVM/pull/2082))
- Split Inspector trait from EthHandler into standalone crate ([#2075](https://github.com/0xsjn/rEVM/pull/2075))
- Introduce Auth and AccessList traits ([#2079](https://github.com/0xsjn/rEVM/pull/2079))
- integrate alloy-eips ([#2078](https://github.com/0xsjn/rEVM/pull/2078))
- *(eip7702)* devnet6 changes and bump eest tests ([#2055](https://github.com/0xsjn/rEVM/pull/2055))
- Evm structure (Cached Instructions and Precompiles) ([#2049](https://github.com/0xsjn/rEVM/pull/2049))
- Context execution ([#2013](https://github.com/0xsjn/rEVM/pull/2013))
- EthHandler trait ([#2001](https://github.com/0xsjn/rEVM/pull/2001))
- *(EIP-7840)* Add blob schedule to execution client cfg ([#1980](https://github.com/0xsjn/rEVM/pull/1980))
- *(eip7702)* apply latest EIP-7702 changes, backport from v52 ([#1969](https://github.com/0xsjn/rEVM/pull/1969))
- *(EIP-7623)* Increase calldata cost. backport from rel/v51 ([#1965](https://github.com/0xsjn/rEVM/pull/1965))
- simplify Transaction trait ([#1959](https://github.com/0xsjn/rEVM/pull/1959))
- align Block trait ([#1957](https://github.com/0xsjn/rEVM/pull/1957))
- expose precompile address in Journal, DB::Error: StdError ([#1956](https://github.com/0xsjn/rEVM/pull/1956))
- Make Ctx journal generic ([#1933](https://github.com/0xsjn/rEVM/pull/1933))
- Restucturing Part7 Handler and Context rework ([#1865](https://github.com/0xsjn/rEVM/pull/1865))
- restructuring Part6 transaction crate ([#1814](https://github.com/0xsjn/rEVM/pull/1814))
- *(examples)* generate block traces ([#895](https://github.com/0xsjn/rEVM/pull/895))
- implement EIP-4844 ([#668](https://github.com/0xsjn/rEVM/pull/668))
- *(Shanghai)* All EIPs: push0, warm coinbase, limit/measure initcode ([#376](https://github.com/0xsjn/rEVM/pull/376))
- Migrate `primitive_types::U256` to `ruint::Uint<256, 4>` ([#239](https://github.com/0xsjn/rEVM/pull/239))
- Introduce ByteCode format, Update Readme ([#156](https://github.com/0xsjn/rEVM/pull/156))

### Fixed

- use HashMap::default in LocalContext ([#2451](https://github.com/0xsjn/rEVM/pull/2451))
- fix typo and update links ([#2387](https://github.com/0xsjn/rEVM/pull/2387))
- Effective gas price should check tx type ([#2375](https://github.com/0xsjn/rEVM/pull/2375))
- remove duplicated load_account() ([#2225](https://github.com/0xsjn/rEVM/pull/2225))
- correct propagate features ([#2177](https://github.com/0xsjn/rEVM/pull/2177))
- clear JournalState and set first journal vec ([#1929](https://github.com/0xsjn/rEVM/pull/1929))
- Clear journal ([#1927](https://github.com/0xsjn/rEVM/pull/1927))
- *(revme)* include correct bytecode for snailtracer  ([#1917](https://github.com/0xsjn/rEVM/pull/1917))
- fix typos ([#620](https://github.com/0xsjn/rEVM/pull/620))

### Other

- remove default capacity on journal reverts ([#2449](https://github.com/0xsjn/rEVM/pull/2449))
- *(journal)* flatten journal entries ([#2440](https://github.com/0xsjn/rEVM/pull/2440))
- clone_from precompile addresses ([#2438](https://github.com/0xsjn/rEVM/pull/2438))
- bump dependency version ([#2431](https://github.com/0xsjn/rEVM/pull/2431))
- fixed broken link ([#2421](https://github.com/0xsjn/rEVM/pull/2421))
- backport from release branch ([#2415](https://github.com/0xsjn/rEVM/pull/2415)) ([#2416](https://github.com/0xsjn/rEVM/pull/2416))
- *(lints)* revm-context lints ([#2404](https://github.com/0xsjn/rEVM/pull/2404))
- bump v68 revm v22.0.0 ([#2396](https://github.com/0xsjn/rEVM/pull/2396))
- make blob params u64 ([#2385](https://github.com/0xsjn/rEVM/pull/2385))
- set gas_priority_fee to None in TxEnv ([#2371](https://github.com/0xsjn/rEVM/pull/2371))
- tag v67 revm v21.0.0 ([#2341](https://github.com/0xsjn/rEVM/pull/2341))
- release-plz ([#2340](https://github.com/0xsjn/rEVM/pull/2340))
- Remove LATEST variant from SpecId enum ([#2299](https://github.com/0xsjn/rEVM/pull/2299))
- links to main readme ([#2298](https://github.com/0xsjn/rEVM/pull/2298))
- add links to arch page ([#2297](https://github.com/0xsjn/rEVM/pull/2297))
- revm v20.0.0 stable version, tag v66 ([#2294](https://github.com/0xsjn/rEVM/pull/2294))
- v65 revm: v20.0.0-alpha.7 ([#2280](https://github.com/0xsjn/rEVM/pull/2280))
- remove wrong `&mut` and duplicated spec ([#2276](https://github.com/0xsjn/rEVM/pull/2276))
- Add custom instruction example ([#2261](https://github.com/0xsjn/rEVM/pull/2261))
- fix clippy ([#2238](https://github.com/0xsjn/rEVM/pull/2238))
- use AccessListItem associated type instead of AccessList ([#2214](https://github.com/0xsjn/rEVM/pull/2214))
- tag v63 revm v20.0.0-alpha.6 ([#2219](https://github.com/0xsjn/rEVM/pull/2219))
- tag v62 revm v20.0.0-alpha.5 ([#2198](https://github.com/0xsjn/rEVM/pull/2198))
- tag v61 revm v20.0.0-alpha.4 ([#2190](https://github.com/0xsjn/rEVM/pull/2190))
- Add comments to handler methods ([#2188](https://github.com/0xsjn/rEVM/pull/2188))
- v59 release-plz update ([#2170](https://github.com/0xsjn/rEVM/pull/2170))
- pre EIP-7702 does not need to load code ([#2162](https://github.com/0xsjn/rEVM/pull/2162))
- JournalTr, JournalOutput, op only using revm crate ([#2155](https://github.com/0xsjn/rEVM/pull/2155))
- rename transact_previous to replay, move EvmTr traits ([#2153](https://github.com/0xsjn/rEVM/pull/2153))
- rename revm-optimism to op-revm ([#2141](https://github.com/0xsjn/rEVM/pull/2141))
- move mainnet builder to handler crate ([#2138](https://github.com/0xsjn/rEVM/pull/2138))
- fix README link ([#2139](https://github.com/0xsjn/rEVM/pull/2139))
- remove `optional_gas_refund` as unused ([#2132](https://github.com/0xsjn/rEVM/pull/2132))
- Adding function derive_tx_type to TxEnv ([#2118](https://github.com/0xsjn/rEVM/pull/2118))
- fix eofcreate error typo ([#2120](https://github.com/0xsjn/rEVM/pull/2120))
- remove wrong `&mut`/`TODO`, and avoid useless `get_mut` ([#2111](https://github.com/0xsjn/rEVM/pull/2111))
- Add docs to revm-bytecode crate ([#2108](https://github.com/0xsjn/rEVM/pull/2108))
- export eip2930 eip7702 types from one place ([#2097](https://github.com/0xsjn/rEVM/pull/2097))
- move all dependencies to workspace ([#2092](https://github.com/0xsjn/rEVM/pull/2092))
- re-export all crates from `revm` ([#2088](https://github.com/0xsjn/rEVM/pull/2088))
- rm database from context-interface ([#2087](https://github.com/0xsjn/rEVM/pull/2087))
- tag v57 revm 20.0.0-alpha.1 ([#2086](https://github.com/0xsjn/rEVM/pull/2086))
- Rename NameTrait to NameTr ([#2084](https://github.com/0xsjn/rEVM/pull/2084))
- API cleanup ([#2067](https://github.com/0xsjn/rEVM/pull/2067))
- Add helpers with_inspector with_precompile ([#2063](https://github.com/0xsjn/rEVM/pull/2063))
- relax halt reason bounds ([#2041](https://github.com/0xsjn/rEVM/pull/2041))
- simplify some generics ([#2032](https://github.com/0xsjn/rEVM/pull/2032))
- Add helper functions for JournalInit #1879 ([#1961](https://github.com/0xsjn/rEVM/pull/1961))
- fix journal naming for inc/dec balance ([#1976](https://github.com/0xsjn/rEVM/pull/1976))
- Make inspector use generics, rm associated types ([#1934](https://github.com/0xsjn/rEVM/pull/1934))
- fix comments and docs into more sensible ([#1920](https://github.com/0xsjn/rEVM/pull/1920))
- *(readme)* add tycho-simulation to "Used by" ([#1926](https://github.com/0xsjn/rEVM/pull/1926))
- tie journal database with database getter ([#1923](https://github.com/0xsjn/rEVM/pull/1923))
- Move CfgEnv from context-interface to context crate ([#1910](https://github.com/0xsjn/rEVM/pull/1910))
- Update README.md examples section ([#1853](https://github.com/0xsjn/rEVM/pull/1853))
- Bump new logo ([#1735](https://github.com/0xsjn/rEVM/pull/1735))
- *(README)* add rbuilder to used-by ([#1585](https://github.com/0xsjn/rEVM/pull/1585))
- added simular to used-by ([#1521](https://github.com/0xsjn/rEVM/pull/1521))
- add Trin to used by list ([#1393](https://github.com/0xsjn/rEVM/pull/1393))
- Fix typo in readme ([#1185](https://github.com/0xsjn/rEVM/pull/1185))
- Add Hardhat to the "Used by" list ([#1164](https://github.com/0xsjn/rEVM/pull/1164))
- Add VERBS to used by list ([#1141](https://github.com/0xsjn/rEVM/pull/1141))
- license date and revm docs ([#1080](https://github.com/0xsjn/rEVM/pull/1080))
- *(docs)* Update the benchmark docs to point to revm package ([#906](https://github.com/0xsjn/rEVM/pull/906))
- *(docs)* Update top-level benchmark docs ([#894](https://github.com/0xsjn/rEVM/pull/894))
- clang requirement ([#784](https://github.com/0xsjn/rEVM/pull/784))
- Readme Updates ([#756](https://github.com/0xsjn/rEVM/pull/756))
- Logo ([#743](https://github.com/0xsjn/rEVM/pull/743))
- book workflow ([#537](https://github.com/0xsjn/rEVM/pull/537))
- add example to revm crate ([#468](https://github.com/0xsjn/rEVM/pull/468))
- Update README.md ([#424](https://github.com/0xsjn/rEVM/pull/424))
- add no_std to primitives ([#366](https://github.com/0xsjn/rEVM/pull/366))
- revm-precompiles to revm-precompile
- Bump v20, changelog ([#350](https://github.com/0xsjn/rEVM/pull/350))
- typos ([#232](https://github.com/0xsjn/rEVM/pull/232))
- Add support for old forks. ([#191](https://github.com/0xsjn/rEVM/pull/191))
- revm bump 1.8. update libs. snailtracer rename ([#159](https://github.com/0xsjn/rEVM/pull/159))
- typo fixes
- fix readme typo
- Big Refactor. Machine to Interpreter. refactor instructions. call/create struct ([#52](https://github.com/0xsjn/rEVM/pull/52))
- readme. debuger update
- Bump revm v0.3.0. README updated
- readme
- Add time elapsed for tests
- readme updated
- Include Basefee into cost calc. readme change
- Initialize precompile accounts
- Status update. Taking a break
- Merkle calc. Tweaks and debugging for eip158
- Replace aurora bn lib with parity's. All Bn128Add/Mul/Pair tests passes
- TEMP
- one tab removed
- readme
- README Example simplified
- Gas calculation for Call/Create. Example Added
- readme usage
- README changes
- Static gas cost added
- Subroutine changelogs and reverts
- Readme postulates
- Spelling
- Restructure project
- First iteration. Machine is looking okay

## [3.0.1](https://github.com/bluealloy/revm/compare/revm-context-v3.0.0...revm-context-v3.0.1) - 2025-04-15

### Other

## [3.0.0](https://github.com/bluealloy/revm/compare/revm-context-v2.0.0...revm-context-v3.0.0) - 2025-04-09

### Fixed

- Effective gas price should check tx type ([#2375](https://github.com/bluealloy/revm/pull/2375))

### Other

- make blob params u64 ([#2385](https://github.com/bluealloy/revm/pull/2385))
- set gas_priority_fee to None in TxEnv ([#2371](https://github.com/bluealloy/revm/pull/2371))

## [2.0.0](https://github.com/bluealloy/revm/compare/revm-context-v1.0.0...revm-context-v2.0.0) - 2025-03-28

### Added

- cache precompile warming ([#2317](https://github.com/bluealloy/revm/pull/2317))
- Add JournalInner ([#2311](https://github.com/bluealloy/revm/pull/2311))

### Other

- Remove LATEST variant from SpecId enum ([#2299](https://github.com/bluealloy/revm/pull/2299))

## [1.0.0](https://github.com/bluealloy/revm/compare/revm-context-v1.0.0-alpha.6...revm-context-v1.0.0) - 2025-03-24

### Other

- updated the following local packages: revm-database

## [1.0.0-alpha.6](https://github.com/bluealloy/revm/compare/revm-context-v1.0.0-alpha.5...revm-context-v1.0.0-alpha.6) - 2025-03-21

### Added

- InspectEvm fn renames, inspector docs, book cleanup ([#2275](https://github.com/bluealloy/revm/pull/2275))

### Fixed

- remove duplicated load_account() ([#2225](https://github.com/bluealloy/revm/pull/2225))

### Other

- remove wrong `&mut` and duplicated spec ([#2276](https://github.com/bluealloy/revm/pull/2276))
- Add custom instruction example ([#2261](https://github.com/bluealloy/revm/pull/2261))
- fix clippy ([#2238](https://github.com/bluealloy/revm/pull/2238))
- use AccessListItem associated type instead of AccessList ([#2214](https://github.com/bluealloy/revm/pull/2214))

## [1.0.0-alpha.5](https://github.com/bluealloy/revm/compare/revm-context-v1.0.0-alpha.4...revm-context-v1.0.0-alpha.5) - 2025-03-16

### Added

- *(docs)* MyEvm example and book cleanup ([#2218](https://github.com/bluealloy/revm/pull/2218))

## [1.0.0-alpha.4](https://github.com/bluealloy/revm/compare/revm-context-v1.0.0-alpha.3...revm-context-v1.0.0-alpha.4) - 2025-03-12

### Added

- add custom error to context ([#2197](https://github.com/bluealloy/revm/pull/2197))
- Add tx/block to EvmExecution trait ([#2195](https://github.com/bluealloy/revm/pull/2195))

## [1.0.0-alpha.3](https://github.com/bluealloy/revm/compare/revm-context-v1.0.0-alpha.2...revm-context-v1.0.0-alpha.3) - 2025-03-11

### Fixed

- correct propagate features ([#2177](https://github.com/bluealloy/revm/pull/2177))

## [1.0.0-alpha.2](https://github.com/bluealloy/revm/compare/revm-context-v1.0.0-alpha.1...revm-context-v1.0.0-alpha.2) - 2025-03-10

### Added

- added with_ref_db fn to Context ([#2164](https://github.com/bluealloy/revm/pull/2164))
- remove specification crate ([#2165](https://github.com/bluealloy/revm/pull/2165))
- make journal entries generic ([#2154](https://github.com/bluealloy/revm/pull/2154))
- Standalone Host, remove default fn from context ([#2147](https://github.com/bluealloy/revm/pull/2147))
- add constructor with hardfork ([#2135](https://github.com/bluealloy/revm/pull/2135))
- allow host to be implemented on custom context ([#2112](https://github.com/bluealloy/revm/pull/2112))
- add the debug impl for Evm and EvmData type ([#2126](https://github.com/bluealloy/revm/pull/2126))

### Other

- pre EIP-7702 does not need to load code ([#2162](https://github.com/bluealloy/revm/pull/2162))
- JournalTr, JournalOutput, op only using revm crate ([#2155](https://github.com/bluealloy/revm/pull/2155))
- rename transact_previous to replay, move EvmTr traits ([#2153](https://github.com/bluealloy/revm/pull/2153))
- move mainnet builder to handler crate ([#2138](https://github.com/bluealloy/revm/pull/2138))
- remove `optional_gas_refund` as unused ([#2132](https://github.com/bluealloy/revm/pull/2132))
- Adding function derive_tx_type to TxEnv ([#2118](https://github.com/bluealloy/revm/pull/2118))
- remove wrong `&mut`/`TODO`, and avoid useless `get_mut` ([#2111](https://github.com/bluealloy/revm/pull/2111))
- export eip2930 eip7702 types from one place ([#2097](https://github.com/bluealloy/revm/pull/2097))
- move all dependencies to workspace ([#2092](https://github.com/bluealloy/revm/pull/2092))
- re-export all crates from `revm` ([#2088](https://github.com/bluealloy/revm/pull/2088))

## [1.0.0-alpha.1](https://github.com/bluealloy/revm/releases/tag/revm-context-v1.0.0-alpha.1) - 2025-02-16

### Added

- Split Inspector trait from EthHandler into standalone crate (#2075)
- Introduce Auth and AccessList traits (#2079)
- integrate alloy-eips (#2078)
- *(eip7702)* devnet6 changes and bump eest tests (#2055)
- Evm structure (Cached Instructions and Precompiles) (#2049)
- Context execution (#2013)
- EthHandler trait (#2001)
- *(EIP-7840)* Add blob schedule to execution client cfg (#1980)
- *(eip7702)* apply latest EIP-7702 changes, backport from v52 (#1969)
- simplify Transaction trait (#1959)
- align Block trait (#1957)
- expose precompile address in Journal, DB::Error: StdError (#1956)
- Make Ctx journal generic (#1933)
- Restucturing Part7 Handler and Context rework (#1865)
- restructuring Part6 transaction crate (#1814)
- *(examples)* generate block traces (#895)
- implement EIP-4844 (#668)
- *(Shanghai)* All EIPs: push0, warm coinbase, limit/measure initcode (#376)
- Migrate `primitive_types::U256` to `ruint::Uint<256, 4>` (#239)
- Introduce ByteCode format, Update Readme (#156)

### Fixed

- clear JournalState and set first journal vec (#1929)
- Clear journal (#1927)
- *(revme)* include correct bytecode for snailtracer  (#1917)
- fix typos ([#620](https://github.com/bluealloy/revm/pull/620))

### Other

- set alpha.1 version
- Add helpers with_inspector with_precompile (#2063)
- simplify some generics (#2032)
- Add helper functions for JournalInit #1879 (#1961)
- fix journal naming for inc/dec balance (#1976)
- Make inspector use generics, rm associated types (#1934)
- fix comments and docs into more sensible (#1920)
- tie journal database with database getter (#1923)
- Move CfgEnv from context-interface to context crate (#1910)
- Bump new logo (#1735)
- *(README)* add rbuilder to used-by (#1585)
- added simular to used-by (#1521)
- add Trin to used by list (#1393)
- Fix typo in readme ([#1185](https://github.com/bluealloy/revm/pull/1185))
- Add Hardhat to the "Used by" list ([#1164](https://github.com/bluealloy/revm/pull/1164))
- Add VERBS to used by list ([#1141](https://github.com/bluealloy/revm/pull/1141))
- license date and revm docs (#1080)
- *(docs)* Update the benchmark docs to point to revm package (#906)
- *(docs)* Update top-level benchmark docs (#894)
- clang requirement (#784)
- Readme Updates (#756)
- Logo (#743)
- book workflow ([#537](https://github.com/bluealloy/revm/pull/537))
- add example to revm crate ([#468](https://github.com/bluealloy/revm/pull/468))
- Update README.md ([#424](https://github.com/bluealloy/revm/pull/424))
- add no_std to primitives ([#366](https://github.com/bluealloy/revm/pull/366))
- revm-precompiles to revm-precompile
- Bump v20, changelog ([#350](https://github.com/bluealloy/revm/pull/350))
- typos (#232)
- Add support for old forks. ([#191](https://github.com/bluealloy/revm/pull/191))
- revm bump 1.8. update libs. snailtracer rename ([#159](https://github.com/bluealloy/revm/pull/159))
- typo fixes
- fix readme typo
- Big Refactor. Machine to Interpreter. refactor instructions. call/create struct ([#52](https://github.com/bluealloy/revm/pull/52))
- readme. debuger update
- Bump revm v0.3.0. README updated
- readme
- Add time elapsed for tests
- readme updated
- Include Basefee into cost calc. readme change
- Initialize precompile accounts
- Status update. Taking a break
- Merkle calc. Tweaks and debugging for eip158
- Replace aurora bn lib with parity's. All Bn128Add/Mul/Pair tests passes
- TEMP
- one tab removed
- readme
- README Example simplified
- Gas calculation for Call/Create. Example Added
- readme usage
- README changes
- Static gas cost added
- Subroutine changelogs and reverts
- Readme postulates
- Spelling
- Restructure project
- First iteration. Machine is looking okay
