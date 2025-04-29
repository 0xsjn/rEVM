# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [5.0.0](https://github.com/0xsjn/rEVM/compare/revme-v4.0.2...revme-v5.0.0) - 2025-04-29

### Added

- *(tx)* Add Either RecoveredAuthorization ([#2448](https://github.com/0xsjn/rEVM/pull/2448))
- *(EOF)* Changes needed for devnet-1 ([#2377](https://github.com/0xsjn/rEVM/pull/2377))
- Move SharedMemory buffer to context ([#2382](https://github.com/0xsjn/rEVM/pull/2382))
- Add JournalInner ([#2311](https://github.com/0xsjn/rEVM/pull/2311))
- Add criterion to revme bench command ([#2295](https://github.com/0xsjn/rEVM/pull/2295))
- InspectEvm fn renames, inspector docs, book cleanup ([#2275](https://github.com/0xsjn/rEVM/pull/2275))
- rename inspect_previous to inspect_replay ([#2194](https://github.com/0xsjn/rEVM/pull/2194))
- remove specification crate ([#2165](https://github.com/0xsjn/rEVM/pull/2165))
- Split Inspector trait from EthHandler into standalone crate ([#2075](https://github.com/0xsjn/rEVM/pull/2075))
- integrate alloy-eips ([#2078](https://github.com/0xsjn/rEVM/pull/2078))
- *(op)* Isthmus precompiles ([#2054](https://github.com/0xsjn/rEVM/pull/2054))
- Evm structure (Cached Instructions and Precompiles) ([#2049](https://github.com/0xsjn/rEVM/pull/2049))
- Context execution ([#2013](https://github.com/0xsjn/rEVM/pull/2013))
- EthHandler trait ([#2001](https://github.com/0xsjn/rEVM/pull/2001))
- *(EIP-7840)* Add blob schedule to execution client cfg ([#1980](https://github.com/0xsjn/rEVM/pull/1980))
- bump eof validation tests ([#1963](https://github.com/0xsjn/rEVM/pull/1963))
- simplify Transaction trait ([#1959](https://github.com/0xsjn/rEVM/pull/1959))
- Split inspector.rs ([#1958](https://github.com/0xsjn/rEVM/pull/1958))
- align Block trait ([#1957](https://github.com/0xsjn/rEVM/pull/1957))
- integrate codspeed ([#1935](https://github.com/0xsjn/rEVM/pull/1935))
- Restucturing Part7 Handler and Context rework ([#1865](https://github.com/0xsjn/rEVM/pull/1865))
- restructuring Part6 transaction crate ([#1814](https://github.com/0xsjn/rEVM/pull/1814))
- extract statetest models/structs to standalone crate ([#1808](https://github.com/0xsjn/rEVM/pull/1808))
- Merge validation/analyzis with Bytecode ([#1793](https://github.com/0xsjn/rEVM/pull/1793))
- restructure part3 fix examples  ([#1792](https://github.com/0xsjn/rEVM/pull/1792))
- Restructuring Part3 inspector crate ([#1788](https://github.com/0xsjn/rEVM/pull/1788))
- restructure Part2 database crate ([#1784](https://github.com/0xsjn/rEVM/pull/1784))
- use TestAuthorization and skip decoding of eip7702 tx ([#1785](https://github.com/0xsjn/rEVM/pull/1785))
- project restructuring Part1 ([#1776](https://github.com/0xsjn/rEVM/pull/1776))
- introducing EvmWiring, a chain-specific configuration ([#1672](https://github.com/0xsjn/rEVM/pull/1672))
- *(statetest)* enable EOF in Prague tests ([#1753](https://github.com/0xsjn/rEVM/pull/1753))
- *(eip7702)* Impl newest version of EIP  ([#1695](https://github.com/0xsjn/rEVM/pull/1695))
- c-kzg bump, cleanup on kzgsetting ([#1719](https://github.com/0xsjn/rEVM/pull/1719))
- *(EOF)* Run EOF tests from eth/tests ([#1690](https://github.com/0xsjn/rEVM/pull/1690))
- *(EOF)* add evmone test suite ([#1689](https://github.com/0xsjn/rEVM/pull/1689))
- *(EOF)* Add EOF validation in revme bytecode cmd ([#1660](https://github.com/0xsjn/rEVM/pull/1660))
- *(EOF)* EOF Validation add code type and sub container tracker ([#1648](https://github.com/0xsjn/rEVM/pull/1648))
- *(eof)* cli eof-validation ([#1622](https://github.com/0xsjn/rEVM/pull/1622))
- *(EOF)* Bytecode::new_raw supports EOF, new_raw_checked added ([#1607](https://github.com/0xsjn/rEVM/pull/1607))
- *(EOF)* Put EOF bytecode behind an Arc ([#1517](https://github.com/0xsjn/rEVM/pull/1517))
- *(revme)* add prague spec ([#1506](https://github.com/0xsjn/rEVM/pull/1506))
- *(precompile)* Prague - EIP-2537 - BLS12-381 curve operations ([#1389](https://github.com/0xsjn/rEVM/pull/1389))
- add trace option in `revme evm` ([#1376](https://github.com/0xsjn/rEVM/pull/1376))
- *(revme)* add --keep-going to statetest command ([#1277](https://github.com/0xsjn/rEVM/pull/1277))
- EOF (Ethereum Object Format) ([#1143](https://github.com/0xsjn/rEVM/pull/1143))
- [**breaking**] TracerEip3155 optionally traces memory ([#1234](https://github.com/0xsjn/rEVM/pull/1234))
- use `impl` instead of `dyn` in `GetInspector` ([#1157](https://github.com/0xsjn/rEVM/pull/1157))
- add evm script ([#1039](https://github.com/0xsjn/rEVM/pull/1039))
- split off serde_json dependency to its own feature ([#1104](https://github.com/0xsjn/rEVM/pull/1104))
- tweeks for v4.0 revm release ([#1048](https://github.com/0xsjn/rEVM/pull/1048))
- *(revme)* make it runnable by goevmlab ([#990](https://github.com/0xsjn/rEVM/pull/990))
- EvmBuilder and External Contexts ([#888](https://github.com/0xsjn/rEVM/pull/888))
- Loop call stack ([#851](https://github.com/0xsjn/rEVM/pull/851))
- *(revme)* format kzg setup ([#818](https://github.com/0xsjn/rEVM/pull/818))
- *(interpreter)* add more helper methods to memory ([#794](https://github.com/0xsjn/rEVM/pull/794))
- derive more traits ([#745](https://github.com/0xsjn/rEVM/pull/745))
- Alloy primitives ([#724](https://github.com/0xsjn/rEVM/pull/724))
- implement EIP-4844 ([#668](https://github.com/0xsjn/rEVM/pull/668))
- *(StateBuilder)* switch builder option from without_bundle to with_bundle ([#688](https://github.com/0xsjn/rEVM/pull/688))
- alloy migration ([#535](https://github.com/0xsjn/rEVM/pull/535))
- State with account status ([#499](https://github.com/0xsjn/rEVM/pull/499))
- *(cancun)* EIP-5656: MCOPY - Memory copying instruction ([#528](https://github.com/0xsjn/rEVM/pull/528))
- json opcode traces EIP-3155 ([#356](https://github.com/0xsjn/rEVM/pull/356))
- *(Shanghai)* All EIPs: push0, warm coinbase, limit/measure initcode ([#376](https://github.com/0xsjn/rEVM/pull/376))
- revm-interpreter created ([#320](https://github.com/0xsjn/rEVM/pull/320))
- Export CustomPrinter insector from revm ([#300](https://github.com/0xsjn/rEVM/pull/300))
- substitute web3db to ethersdb ([#293](https://github.com/0xsjn/rEVM/pull/293))
- *(interpreter)* Unify instruction fn signature ([#283](https://github.com/0xsjn/rEVM/pull/283))
- *(revm)* Add prevrandao field to EnvBlock ([#271](https://github.com/0xsjn/rEVM/pull/271))
- Migrate `primitive_types::U256` to `ruint::Uint<256, 4>` ([#239](https://github.com/0xsjn/rEVM/pull/239))
- *(revm, revme)* gas inspector ([#222](https://github.com/0xsjn/rEVM/pull/222))
- Introduce ByteCode format, Update Readme ([#156](https://github.com/0xsjn/rEVM/pull/156))
- mutable call inputs

### Fixed

- correct eof kind in verification tests ([#2250](https://github.com/0xsjn/rEVM/pull/2250))
- *(revme)* Statetest stop exec when print output is true ([#1995](https://github.com/0xsjn/rEVM/pull/1995))
- *(revme)* statetest remove redundant json output ([#1994](https://github.com/0xsjn/rEVM/pull/1994))
- *(eof)* dont run precompile on ext delegate call ([#1964](https://github.com/0xsjn/rEVM/pull/1964))
- *(revme)* Burntpix bench ([#1937](https://github.com/0xsjn/rEVM/pull/1937))
- *(revme)* include correct bytecode for snailtracer  ([#1917](https://github.com/0xsjn/rEVM/pull/1917))
- statetest json set spec_id ([#1766](https://github.com/0xsjn/rEVM/pull/1766))
- *(statetest)* make bytecode analyzed ([#1666](https://github.com/0xsjn/rEVM/pull/1666))
- *(EOF)* returning to non-returning jumpf, enable valition error ([#1664](https://github.com/0xsjn/rEVM/pull/1664))
- *(statetest)* Add back Merge spec ([#1658](https://github.com/0xsjn/rEVM/pull/1658))
- *(eip7702)* Add tests and fix some bugs ([#1605](https://github.com/0xsjn/rEVM/pull/1605))
- *(eof)* fixture 2 tests ([#1550](https://github.com/0xsjn/rEVM/pull/1550))
- *(revme)* Print one json outcome in statetest ([#1347](https://github.com/0xsjn/rEVM/pull/1347))
- Drops check for .json when testing a single file ([#1301](https://github.com/0xsjn/rEVM/pull/1301))
- *(revme)* revme error output and remove double summary ([#1169](https://github.com/0xsjn/rEVM/pull/1169))
- *(eip4844)* Pass eth tests, additional conditions added. ([#735](https://github.com/0xsjn/rEVM/pull/735))
- *(test)* Check expect exception and revm error ([#734](https://github.com/0xsjn/rEVM/pull/734))
- k256 compile error ([#451](https://github.com/0xsjn/rEVM/pull/451))
- make DatabaseRef::basic consistent with Database ([#201](https://github.com/0xsjn/rEVM/pull/201))
- impose a memory limit ([#86](https://github.com/0xsjn/rEVM/pull/86))
- various inspector fixes ([#69](https://github.com/0xsjn/rEVM/pull/69))

### Other

- *(revme)* simplify repeated code ([#2432](https://github.com/0xsjn/rEVM/pull/2432))
- backport from release branch ([#2415](https://github.com/0xsjn/rEVM/pull/2415)) ([#2416](https://github.com/0xsjn/rEVM/pull/2416))
- *(lints)* revm-context lints ([#2404](https://github.com/0xsjn/rEVM/pull/2404))
- bump v68 revm v22.0.0 ([#2396](https://github.com/0xsjn/rEVM/pull/2396))
- *(revme)* remove revm-handler dependency ([#2366](https://github.com/0xsjn/rEVM/pull/2366))
- release-plz ([#2340](https://github.com/0xsjn/rEVM/pull/2340))
- add criterion benchmark for evm build ([#2319](https://github.com/0xsjn/rEVM/pull/2319))
- add check for path and existence existence ([#2320](https://github.com/0xsjn/rEVM/pull/2320))
- bump bench time, and reduce burntpix iterations ([#2315](https://github.com/0xsjn/rEVM/pull/2315))
- update EOF validation logic and improve error handling ([#2304](https://github.com/0xsjn/rEVM/pull/2304))
- revm v20.0.0 stable version, tag v66 ([#2294](https://github.com/0xsjn/rEVM/pull/2294))
- group cargo imports ([#2289](https://github.com/0xsjn/rEVM/pull/2289))
- v65 revm: v20.0.0-alpha.7 ([#2280](https://github.com/0xsjn/rEVM/pull/2280))
- *(revme)* remove deprecated #[clap] attribute
- tag v63 revm v20.0.0-alpha.6 ([#2219](https://github.com/0xsjn/rEVM/pull/2219))
- tag v62 revm v20.0.0-alpha.5 ([#2198](https://github.com/0xsjn/rEVM/pull/2198))
- tag v61 revm v20.0.0-alpha.4 ([#2190](https://github.com/0xsjn/rEVM/pull/2190))
- Add comments to handler methods ([#2188](https://github.com/0xsjn/rEVM/pull/2188))
- tag v60, revm v20.0.0-alpha.3 ([#2176](https://github.com/0xsjn/rEVM/pull/2176))
- v59 release-plz update ([#2170](https://github.com/0xsjn/rEVM/pull/2170))
- JournalTr, JournalOutput, op only using revm crate ([#2155](https://github.com/0xsjn/rEVM/pull/2155))
- rename transact_previous to replay, move EvmTr traits ([#2153](https://github.com/0xsjn/rEVM/pull/2153))
- Add docs to revm-bytecode crate ([#2108](https://github.com/0xsjn/rEVM/pull/2108))
- *(deps)* bump breaking deps ([#2093](https://github.com/0xsjn/rEVM/pull/2093))
- move all dependencies to workspace ([#2092](https://github.com/0xsjn/rEVM/pull/2092))
- tag v57 revm 20.0.0-alpha.1 ([#2086](https://github.com/0xsjn/rEVM/pull/2086))
- Bump licence year to 2025 ([#2058](https://github.com/0xsjn/rEVM/pull/2058))
- improve EIP-3155 tracer ([#2033](https://github.com/0xsjn/rEVM/pull/2033))
- align crates versions ([#1983](https://github.com/0xsjn/rEVM/pull/1983))
- remove analysis bench inner loops ([#1936](https://github.com/0xsjn/rEVM/pull/1936))
- fix comments and docs into more sensible ([#1920](https://github.com/0xsjn/rEVM/pull/1920))
- tie journal database with database getter ([#1923](https://github.com/0xsjn/rEVM/pull/1923))
- use stderr for revme tracer. not panic on bytecode ([#1916](https://github.com/0xsjn/rEVM/pull/1916))
- put snailtracer and analysis contracts in files ([#1911](https://github.com/0xsjn/rEVM/pull/1911))
- Move CfgEnv from context-interface to context crate ([#1910](https://github.com/0xsjn/rEVM/pull/1910))
- Rename PRAGUE_EOF to OSAKA ([#1903](https://github.com/0xsjn/rEVM/pull/1903))
- bump EOF evmone tests to v0.13.0 ([#1816](https://github.com/0xsjn/rEVM/pull/1816))
- *(primitives)* replace HashMap re-exports with alloy_primitives::map ([#1805](https://github.com/0xsjn/rEVM/pull/1805))
- *(revme)* replace `structopt` with `clap` ([#1754](https://github.com/0xsjn/rEVM/pull/1754))
- release ([#1729](https://github.com/0xsjn/rEVM/pull/1729))
- release ([#1722](https://github.com/0xsjn/rEVM/pull/1722))
- tag v41 revm v13.0.0 ([#1692](https://github.com/0xsjn/rEVM/pull/1692))
- release ([#1683](https://github.com/0xsjn/rEVM/pull/1683))
- Add EOF Layout Fuzz Loop to `revme bytecode` ([#1677](https://github.com/0xsjn/rEVM/pull/1677))
- *(clippy)* 1.80 rust clippy list paragraph ident ([#1661](https://github.com/0xsjn/rEVM/pull/1661))
- use `is_zero` for `U256` and `B256` ([#1638](https://github.com/0xsjn/rEVM/pull/1638))
- bump versions bcs of primitives ([#1631](https://github.com/0xsjn/rEVM/pull/1631))
- release ([#1620](https://github.com/0xsjn/rEVM/pull/1620))
- *(GeneralState)* skip fewer specs ([#1603](https://github.com/0xsjn/rEVM/pull/1603))
- release ([#1579](https://github.com/0xsjn/rEVM/pull/1579))
- replace AccessList with alloy version ([#1552](https://github.com/0xsjn/rEVM/pull/1552))
- release ([#1548](https://github.com/0xsjn/rEVM/pull/1548))
- replace TransactTo with TxKind ([#1542](https://github.com/0xsjn/rEVM/pull/1542))
- skip tests with storage check and return status ([#1452](https://github.com/0xsjn/rEVM/pull/1452))
- release ([#1261](https://github.com/0xsjn/rEVM/pull/1261))
- *(revme)* increment statetest bar *after* running the test ([#1377](https://github.com/0xsjn/rEVM/pull/1377))
- *(interpreter)* branch less in as_usize_or_fail ([#1374](https://github.com/0xsjn/rEVM/pull/1374))
- release ([#1231](https://github.com/0xsjn/rEVM/pull/1231))
- use uint macro & fix various small things ([#1253](https://github.com/0xsjn/rEVM/pull/1253))
- release ([#1175](https://github.com/0xsjn/rEVM/pull/1175))
- tag v32 revm v7.1.0 ([#1176](https://github.com/0xsjn/rEVM/pull/1176))
- release ([#1125](https://github.com/0xsjn/rEVM/pull/1125))
- *(deps)* bump walkdir from 2.4.0 to 2.5.0 ([#1149](https://github.com/0xsjn/rEVM/pull/1149))
- release tag v30 revm v6.1.0 ([#1100](https://github.com/0xsjn/rEVM/pull/1100))
- release ([#1082](https://github.com/0xsjn/rEVM/pull/1082))
- license date and revm docs ([#1080](https://github.com/0xsjn/rEVM/pull/1080))
- release ([#1067](https://github.com/0xsjn/rEVM/pull/1067))
- *(revme)* statetests new format and return error ([#1066](https://github.com/0xsjn/rEVM/pull/1066))
- tag v27, revm v4.0.0 release ([#1061](https://github.com/0xsjn/rEVM/pull/1061))
- *(EvmBuilder)* rename builder functions to HandlerCfg ([#1050](https://github.com/0xsjn/rEVM/pull/1050))
- *(Interpreter)* Split calls to separate functions ([#1005](https://github.com/0xsjn/rEVM/pull/1005))
- *(revme)* EmptyDb Blockhash string, json-outcome flag, set prevrandao in statetest ([#994](https://github.com/0xsjn/rEVM/pull/994))
- *(revme)* add recovery of address from secret key ([#992](https://github.com/0xsjn/rEVM/pull/992))
- *(log)* use alloy_primitives::Log ([#975](https://github.com/0xsjn/rEVM/pull/975))
- *(docs)* revme readme update ([#898](https://github.com/0xsjn/rEVM/pull/898))
- simplify use statements ([#864](https://github.com/0xsjn/rEVM/pull/864))
- decode KZG points directly into the buffers ([#840](https://github.com/0xsjn/rEVM/pull/840))
- bump v26 revm v3.5.0 ([#765](https://github.com/0xsjn/rEVM/pull/765))
- tag v25, revm v3.4.0 ([#755](https://github.com/0xsjn/rEVM/pull/755))
- BLOBBASEFEE opcode ([#721](https://github.com/0xsjn/rEVM/pull/721))
- Never inline the prepare functions ([#712](https://github.com/0xsjn/rEVM/pull/712))
- *(deps)* bump bytes from 1.4.0 to 1.5.0 ([#707](https://github.com/0xsjn/rEVM/pull/707))
- make `impl Default for StateBuilder` generic ([#690](https://github.com/0xsjn/rEVM/pull/690))
- *(deps)* bump walkdir from 2.3.3 to 2.4.0 ([#692](https://github.com/0xsjn/rEVM/pull/692))
- *(cfg)* convert chain_id from u256 to u64 ([#693](https://github.com/0xsjn/rEVM/pull/693))
- Revert "feat: alloy migration ([#535](https://github.com/0xsjn/rEVM/pull/535))" ([#616](https://github.com/0xsjn/rEVM/pull/616))
- spell check ([#615](https://github.com/0xsjn/rEVM/pull/615))
- avoid unnecessary allocations ([#581](https://github.com/0xsjn/rEVM/pull/581))
- clippy and fmt ([#568](https://github.com/0xsjn/rEVM/pull/568))
- optimize stack usage for recursive `call` and `create` programs ([#522](https://github.com/0xsjn/rEVM/pull/522))
- *(deps)* bump hashbrown from 0.13.2 to 0.14.0 ([#519](https://github.com/0xsjn/rEVM/pull/519))
- Bump v24, revm v3.3.0 ([#476](https://github.com/0xsjn/rEVM/pull/476))
- *(deps)* bump ruint from 1.7.0 to 1.8.0 ([#465](https://github.com/0xsjn/rEVM/pull/465))
- Release v23, revm v3.2.0 ([#464](https://github.com/0xsjn/rEVM/pull/464))
- Release v22, revm v3.1.1 ([#460](https://github.com/0xsjn/rEVM/pull/460))
- v21, revm v3.1.0 ([#444](https://github.com/0xsjn/rEVM/pull/444))
- bump all
- remove gas blocks ([#391](https://github.com/0xsjn/rEVM/pull/391))
- *(deps)* bump bytes from 1.3.0 to 1.4.0 ([#355](https://github.com/0xsjn/rEVM/pull/355))
- Bump v20, changelog ([#350](https://github.com/0xsjn/rEVM/pull/350))
- Cleanup imports ([#348](https://github.com/0xsjn/rEVM/pull/348))
- includes to libs ([#338](https://github.com/0xsjn/rEVM/pull/338))
- Creating revm-primitives, revm better errors and db components  ([#334](https://github.com/0xsjn/rEVM/pull/334))
- Correct typo ([#282](https://github.com/0xsjn/rEVM/pull/282))
- Integer overflow while calculating the remaining gas in GasInspector ([#287](https://github.com/0xsjn/rEVM/pull/287))
- native bits ([#278](https://github.com/0xsjn/rEVM/pull/278))
- *(release)* Bump revm and precompiles versions
- Bump primitive_types. Add statetest spec
- Bump revm to v2.3.0
- typos ([#263](https://github.com/0xsjn/rEVM/pull/263))
- *(eth/test)* Added OEF spec for tests. Skip HighGasPrice ([#261](https://github.com/0xsjn/rEVM/pull/261))
- Bump revm v2.1.0 ([#224](https://github.com/0xsjn/rEVM/pull/224))
- revm bump v2.0.0, precompile bump v1.1.1 ([#212](https://github.com/0xsjn/rEVM/pull/212))
- current_opcode fn and rename program_counter to instruction_pointer ([#211](https://github.com/0xsjn/rEVM/pull/211))
- Cfg choose create analysis, option on bytecode size limit ([#210](https://github.com/0xsjn/rEVM/pull/210))
- revme some cleanup ([#202](https://github.com/0xsjn/rEVM/pull/202))
- Add support for old forks. ([#191](https://github.com/0xsjn/rEVM/pull/191))
- add lib target, make utils public ([#185](https://github.com/0xsjn/rEVM/pull/185))
- Handle HighNonce tests ([#176](https://github.com/0xsjn/rEVM/pull/176))
- JournaledState ([#175](https://github.com/0xsjn/rEVM/pull/175))
- Return `ExecutionResult`, which includes `gas_refunded` ([#169](https://github.com/0xsjn/rEVM/pull/169))
- Make CacheDB fields pub ([#145](https://github.com/0xsjn/rEVM/pull/145))
- Introduce account Touched/Cleared/None state in CacheDB ([#140](https://github.com/0xsjn/rEVM/pull/140))
- update statetest model to pass merge tests ([#133](https://github.com/0xsjn/rEVM/pull/133))
- don't delete account and storage entries on commit ([#126](https://github.com/0xsjn/rEVM/pull/126))
- *(clippy)* make clippy happy ([#120](https://github.com/0xsjn/rEVM/pull/120))
- typo fixes
- v6 changelog, bump versions
- some cleanup, checking on failed example tests
- Rework analysis ([#89](https://github.com/0xsjn/rEVM/pull/89))
- refactor to exact option combinators ([#96](https://github.com/0xsjn/rEVM/pull/96))
- Enable statetest for Berlin/Istanbul ([#78](https://github.com/0xsjn/rEVM/pull/78))
- Big Refactor. Machine to Interpreter. refactor instructions. call/create struct ([#52](https://github.com/0xsjn/rEVM/pull/52))
- [revm] pop_top and unsafe comments ([#51](https://github.com/0xsjn/rEVM/pull/51))
- Inspector fixup
- Bump precompiles to v0.4.0 bump revm v1.2.0
- [revme] return error on failes statetest
- clippy
- [recompl] Bump precompile deps, cargo sort on workspace
- cargo fmt
- [revm_precompiles] added flag for k256 lib
- [revm] Bump to v1.1.0
- Omit edgecase high nonce test. tracer gas fix
- Bug fix for unknown OpCode
- internal cleanups
- [revm] output log. Stetetest test log output. fmt
- Bump versions, Changelogs, fmt, revm readme, clippy.
- GasBlock for all Spec
- [revm] Run test multiple times. fmt, BenchmarkDB
- [revm][perf] GasBlock analazis and optimizations.
- wip
- [revm] Optimize PC, some perf
- [revme][debug] added help ctrl
- [revme][debugger] stack pop/push
- [revme] full env as cli
- [revme][debug] some print cli
- readme. debuger update
- [revm] Rename Handler to Host
- [revm] Simplified host inspector
- [revme] debugger cli history
- [revme][debugger] wip terminal
- [revm][revme] statetest merged
- [revme] initial commit. Cmd skeleton added.statetests moved

## [4.0.2](https://github.com/bluealloy/revm/compare/revme-v4.0.0..revme-v4.0.1) - 2025-04-15

### Other


## [4.0.1](https://github.com/bluealloy/revm/compare/revme-v4.0.0...revme-v4.0.1) - 2025-04-09

### Other

- *(revme)* remove revm-handler dependency ([#2366](https://github.com/bluealloy/revm/pull/2366))

## [4.0.0](https://github.com/bluealloy/revm/compare/revme-v3.0.0...revme-v4.0.0) - 2025-03-28

### Added

- Add JournalInner ([#2311](https://github.com/bluealloy/revm/pull/2311))
- Add criterion to revme bench command ([#2295](https://github.com/bluealloy/revm/pull/2295))

### Other

- add criterion benchmark for evm build ([#2319](https://github.com/bluealloy/revm/pull/2319))
- add check for path and existence existence ([#2320](https://github.com/bluealloy/revm/pull/2320))
- bump bench time, and reduce burntpix iterations ([#2315](https://github.com/bluealloy/revm/pull/2315))
- update EOF validation logic and improve error handling ([#2304](https://github.com/bluealloy/revm/pull/2304))

## [3.0.0](https://github.com/bluealloy/revm/compare/revme-v3.0.0-alpha.7...revme-v3.0.0) - 2025-03-24

### Other

- updated the following local packages: revm-database

## [3.0.0-alpha.7](https://github.com/bluealloy/revm/compare/revme-v3.0.0-alpha.6...revme-v3.0.0-alpha.7) - 2025-03-21

### Added

- InspectEvm fn renames, inspector docs, book cleanup ([#2275](https://github.com/bluealloy/revm/pull/2275))

### Fixed

- correct eof kind in verification tests ([#2250](https://github.com/bluealloy/revm/pull/2250))

### Other

- *(revme)* remove deprecated #[clap] attribute

## [3.0.0-alpha.6](https://github.com/bluealloy/revm/compare/revme-v3.0.0-alpha.5...revme-v3.0.0-alpha.6) - 2025-03-16

### Other

- updated the following local packages: revm-primitives, revm-bytecode, revm-context-interface, revm-context, revm-handler, revm-inspector

## [3.0.0-alpha.5](https://github.com/bluealloy/revm/compare/revme-v3.0.0-alpha.4...revme-v3.0.0-alpha.5) - 2025-03-12

### Added

- rename inspect_previous to inspect_replay ([#2194](https://github.com/bluealloy/revm/pull/2194))

## [3.0.0-alpha.4](https://github.com/bluealloy/revm/compare/revme-v3.0.0-alpha.3...revme-v3.0.0-alpha.4) - 2025-03-11

### Other

- Add comments to handler methods ([#2188](https://github.com/bluealloy/revm/pull/2188))

## [3.0.0-alpha.3](https://github.com/bluealloy/revm/compare/revme-v3.0.0-alpha.2...revme-v3.0.0-alpha.3) - 2025-03-10

### Other

- updated the following local packages: revm

## [3.0.0-alpha.2](https://github.com/bluealloy/revm/compare/revme-v3.0.0-alpha.1...revme-v3.0.0-alpha.2) - 2025-03-10

### Added

- remove specification crate ([#2165](https://github.com/bluealloy/revm/pull/2165))

### Other

- JournalTr, JournalOutput, op only using revm crate ([#2155](https://github.com/bluealloy/revm/pull/2155))
- rename transact_previous to replay, move EvmTr traits ([#2153](https://github.com/bluealloy/revm/pull/2153))
- Add docs to revm-bytecode crate ([#2108](https://github.com/bluealloy/revm/pull/2108))
- *(deps)* bump breaking deps ([#2093](https://github.com/bluealloy/revm/pull/2093))
- move all dependencies to workspace ([#2092](https://github.com/bluealloy/revm/pull/2092))

## [3.0.0-alpha.1](https://github.com/bluealloy/revm/compare/revme-v2.5.0...revme-v3.0.0-alpha.1) - 2025-02-16

### Added

- Split Inspector trait from EthHandler into standalone crate (#2075)
- integrate alloy-eips (#2078)
- *(op)* Isthmus precompiles (#2054)
- Evm structure (Cached Instructions and Precompiles) (#2049)
- Context execution (#2013)
- EthHandler trait (#2001)
- *(EIP-7840)* Add blob schedule to execution client cfg (#1980)
- bump eof validation tests (#1963)
- simplify Transaction trait (#1959)
- Split inspector.rs (#1958)
- align Block trait (#1957)
- integrate codspeed (#1935)
- Restucturing Part7 Handler and Context rework (#1865)
- restructuring Part6 transaction crate (#1814)
- extract statetest models/structs to standalone crate (#1808)
- Merge validation/analyzis with Bytecode (#1793)
- restructure part3 fix examples  (#1792)
- Restructuring Part3 inspector crate (#1788)
- restructure Part2 database crate (#1784)
- use TestAuthorization and skip decoding of eip7702 tx (#1785)
- project restructuring Part1 (#1776)
- introducing EvmWiring, a chain-specific configuration (#1672)

### Fixed

- *(revme)* Statetest stop exec when print output is true (#1995)
- *(revme)* statetest remove redundant json output (#1994)
- *(eof)* dont run precompile on ext delegate call (#1964)
- *(revme)* Burntpix bench (#1937)
- *(revme)* include correct bytecode for snailtracer  (#1917)
- statetest json set spec_id (#1766)

### Other

- set alpha.1 version
- Bump licence year to 2025 (#2058)
- improve EIP-3155 tracer (#2033)
- align crates versions (#1983)
- remove analysis bench inner loops (#1936)
- fix comments and docs into more sensible (#1920)
- tie journal database with database getter (#1923)
- use stderr for revme tracer. not panic on bytecode (#1916)
- put snailtracer and analysis contracts in files (#1911)
- Move CfgEnv from context-interface to context crate (#1910)
- Rename PRAGUE_EOF to OSAKA (#1903)
- bump EOF evmone tests to v0.13.0 (#1816)
- *(primitives)* replace HashMap re-exports with alloy_primitives::map (#1805)
- *(revme)* replace `structopt` with `clap` (#1754)

## [2.5.0](https://github.com/bluealloy/revm/compare/revme-v2.4.0...revme-v2.5.0) - 2025-02-11

### Other

- updated the following local packages: revm

## [2.4.0](https://github.com/bluealloy/revm/compare/revme-v2.3.0...revme-v2.4.0) - 2025-01-28

### Other

- devnet5 tests v1.3.0 ([#2021](https://github.com/bluealloy/revm/pull/2021))

## [2.3.0](https://github.com/bluealloy/revm/compare/revme-v2.2.0...revme-v2.3.0) - 2025-01-13

### Added

- *(EIP-7623)* adjuct floor gas check order ([#1990](https://github.com/bluealloy/revm/pull/1990))

### Other

- v53 revm v19.2.0 ([#1972](https://github.com/bluealloy/revm/pull/1972))

## [2.2.0](https://github.com/bluealloy/revm/compare/revme-v2.1.0...revme-v2.2.0) - 2024-12-26

### Added

- blst reprice, remove g1/g2 mul, eest test bump ([#1951](https://github.com/bluealloy/revm/pull/1951))
- eip7691 fraction update ([#1900](https://github.com/bluealloy/revm/pull/1900))

### Other

- Uncouple blob count between CL and EL ([#1899](https://github.com/bluealloy/revm/pull/1899))

## [2.1.0](https://github.com/bluealloy/revm/compare/revme-v2.0.0...revme-v2.1.0) - 2024-11-06

### Other

- Osaka Activation (release_49 branch) ([#1835](https://github.com/bluealloy/revm/pull/1835))
- v49 release ([#1833](https://github.com/bluealloy/revm/pull/1833))

## [2.0.0](https://github.com/bluealloy/revm/compare/revme-v1.0.0...revme-v2.0.0) - 2024-10-23

### Other

- update Cargo.lock dependencies

## [1.0.0](https://github.com/bluealloy/revm/compare/revme-v0.11.0...revme-v1.0.0) - 2024-09-26

### Other

- update Cargo.lock dependencies

## [0.11.0](https://github.com/bluealloy/revm/compare/revme-v0.10.3...revme-v0.11.0) - 2024-10-17

### Added

- Rename PRAGUE_EOF to OSAKA ([#1822](https://github.com/bluealloy/revm/pull/1822))
- *(EIP-7702)* devnet-4 changes ([#1821](https://github.com/bluealloy/revm/pull/1821))

### Other

- remove test u8 check ([#1825](https://github.com/bluealloy/revm/pull/1825))

## [0.10.3](https://github.com/bluealloy/revm/compare/revme-v0.10.2...revme-v0.10.3) - 2024-09-26

### Other

- update Cargo.lock dependencies

## [0.10.2](https://github.com/bluealloy/revm/compare/revme-v0.10.1...revme-v0.10.2) - 2024-09-18

### Added

- *(statetest)* enable EOF in Prague tests ([#1753](https://github.com/bluealloy/revm/pull/1753))


## [0.10.1](https://github.com/bluealloy/revm/compare/revme-v0.10.0...revme-v0.10.1) - 2024-08-30

### Other
- updated the following local packages: revm

## [0.10.0](https://github.com/bluealloy/revm/compare/revme-v0.9.0...revme-v0.10.0) - 2024-08-29

### Added
- *(eip7702)* Impl newest version of EIP  ([#1695](https://github.com/bluealloy/revm/pull/1695))
- c-kzg bump, cleanup on kzgsetting ([#1719](https://github.com/bluealloy/revm/pull/1719))

## [0.9.0](https://github.com/bluealloy/revm/compare/revme-v0.8.0...revme-v0.9.0) - 2024-08-08

### Added
- *(EOF)* Run EOF tests from eth/tests ([#1690](https://github.com/bluealloy/revm/pull/1690))
- *(EOF)* add evmone test suite ([#1689](https://github.com/bluealloy/revm/pull/1689))
- *(EOF)* Add EOF validation in revme bytecode cmd ([#1660](https://github.com/bluealloy/revm/pull/1660))
- *(EOF)* EOF Validation add code type and sub container tracker ([#1648](https://github.com/bluealloy/revm/pull/1648))

### Fixed
- *(statetest)* make bytecode analyzed ([#1666](https://github.com/bluealloy/revm/pull/1666))
- *(EOF)* returning to non-returning jumpf, enable valition error ([#1664](https://github.com/bluealloy/revm/pull/1664))
- *(statetest)* Add back Merge spec ([#1658](https://github.com/bluealloy/revm/pull/1658))

### Other
- Add EOF Layout Fuzz Loop to `revme bytecode` ([#1677](https://github.com/bluealloy/revm/pull/1677))
- *(clippy)* 1.80 rust clippy list paragraph ident ([#1661](https://github.com/bluealloy/revm/pull/1661))
- use `is_zero` for `U256` and `B256` ([#1638](https://github.com/bluealloy/revm/pull/1638))
- bump versions bcs of primitives ([#1631](https://github.com/bluealloy/revm/pull/1631))

## [0.8.0](https://github.com/bluealloy/revm/compare/revme-v0.7.0...revme-v0.8.0) - 2024-07-16

### Added
- *(eof)* cli eof-validation ([#1622](https://github.com/bluealloy/revm/pull/1622))
- *(EOF)* Bytecode::new_raw supports EOF, new_raw_checked added ([#1607](https://github.com/bluealloy/revm/pull/1607))

### Fixed
- *(eip7702)* Add tests and fix some bugs ([#1605](https://github.com/bluealloy/revm/pull/1605))

### Other
- *(GeneralState)* skip fewer specs ([#1603](https://github.com/bluealloy/revm/pull/1603))

## [0.7.0](https://github.com/bluealloy/revm/compare/revme-v0.6.0...revme-v0.7.0) - 2024-07-08

### Other
- replace AccessList with alloy version ([#1552](https://github.com/bluealloy/revm/pull/1552))

## [0.6.0](https://github.com/bluealloy/revm/compare/revme-v0.5.0...revme-v0.6.0) - 2024-06-20

### Added
- *(EOF)* Put EOF bytecode behind an Arc ([#1517](https://github.com/bluealloy/revm/pull/1517))
- *(revme)* add prague spec ([#1506](https://github.com/bluealloy/revm/pull/1506))

### Fixed
- *(eof)* fixture 2 tests ([#1550](https://github.com/bluealloy/revm/pull/1550))

### Other
- replace TransactTo with TxKind ([#1542](https://github.com/bluealloy/revm/pull/1542))
- skip tests with storage check and return status ([#1452](https://github.com/bluealloy/revm/pull/1452))

## [0.5.0](https://github.com/bluealloy/revm/compare/revme-v0.4.0...revme-v0.5.0) - 2024-05-12

### Added
- *(precompile)* Prague - EIP-2537 - BLS12-381 curve operations ([#1389](https://github.com/bluealloy/revm/pull/1389))
- add trace option in `revme evm` ([#1376](https://github.com/bluealloy/revm/pull/1376))
- *(revme)* add --keep-going to statetest command ([#1277](https://github.com/bluealloy/revm/pull/1277))
- EOF (Ethereum Object Format) ([#1143](https://github.com/bluealloy/revm/pull/1143))

### Fixed
- *(revme)* Print one json outcome in statetest ([#1347](https://github.com/bluealloy/revm/pull/1347))
- Drops check for .json when testing a single file ([#1301](https://github.com/bluealloy/revm/pull/1301))

### Other
- *(revme)* increment statetest bar *after* running the test ([#1377](https://github.com/bluealloy/revm/pull/1377))
- *(interpreter)* branch less in as_usize_or_fail ([#1374](https://github.com/bluealloy/revm/pull/1374))

## [0.4.0](https://github.com/bluealloy/revm/compare/revme-v0.3.1...revme-v0.4.0) - 2024-04-02

### Added
- [**breaking**] TracerEip3155 optionally traces memory ([#1234](https://github.com/bluealloy/revm/pull/1234))

### Other
- use uint macro & fix various small things ([#1253](https://github.com/bluealloy/revm/pull/1253))

## [0.3.1](https://github.com/bluealloy/revm/compare/revme-v0.3.0...revme-v0.3.1) - 2024-03-19

### Other
- tag v32 revm v7.1.0 ([#1176](https://github.com/bluealloy/revm/pull/1176))

## [0.3.0](https://github.com/bluealloy/revm/compare/revme-v0.2.2...revme-v0.3.0) - 2024-03-08

### Added
- use `impl` instead of `dyn` in `GetInspector` ([#1157](https://github.com/bluealloy/revm/pull/1157))
- add evm script ([#1039](https://github.com/bluealloy/revm/pull/1039))

### Fixed
- *(revme)* revme error output and remove double summary ([#1169](https://github.com/bluealloy/revm/pull/1169))

### Other
- *(deps)* bump walkdir from 2.4.0 to 2.5.0 ([#1149](https://github.com/bluealloy/revm/pull/1149))

## [0.2.2](https://github.com/bluealloy/revm/compare/revme-v0.2.1...revme-v0.2.2) - 2024-02-22

### Added
- split off serde_json dependency to its own feature ([#1104](https://github.com/bluealloy/revm/pull/1104))

## [0.2.1](https://github.com/bluealloy/revm/compare/revme-v0.2.0...revme-v0.2.1) - 2024-02-07

### Added
- tweeks for v4.0 revm release ([#1048](https://github.com/bluealloy/revm/pull/1048))
- *(revme)* make it runnable by goevmlab ([#990](https://github.com/bluealloy/revm/pull/990))
- EvmBuilder and External Contexts ([#888](https://github.com/bluealloy/revm/pull/888))
- Loop call stack ([#851](https://github.com/bluealloy/revm/pull/851))
- *(revme)* format kzg setup ([#818](https://github.com/bluealloy/revm/pull/818))
- *(interpreter)* add more helper methods to memory ([#794](https://github.com/bluealloy/revm/pull/794))
- derive more traits ([#745](https://github.com/bluealloy/revm/pull/745))
- Alloy primitives ([#724](https://github.com/bluealloy/revm/pull/724))
- implement EIP-4844 ([#668](https://github.com/bluealloy/revm/pull/668))
- *(StateBuilder)* switch builder option from without_bundle to with_bundle ([#688](https://github.com/bluealloy/revm/pull/688))
- alloy migration ([#535](https://github.com/bluealloy/revm/pull/535))
- State with account status ([#499](https://github.com/bluealloy/revm/pull/499))
- *(cancun)* EIP-5656: MCOPY - Memory copying instruction ([#528](https://github.com/bluealloy/revm/pull/528))
- json opcode traces EIP-3155 ([#356](https://github.com/bluealloy/revm/pull/356))
- *(Shanghai)* All EIPs: push0, warm coinbase, limit/measure initcode ([#376](https://github.com/bluealloy/revm/pull/376))
- revm-interpreter created ([#320](https://github.com/bluealloy/revm/pull/320))
- Export CustomPrinter insector from revm ([#300](https://github.com/bluealloy/revm/pull/300))
- substitute web3db to ethersdb ([#293](https://github.com/bluealloy/revm/pull/293))
- *(interpreter)* Unify instruction fn signature ([#283](https://github.com/bluealloy/revm/pull/283))
- *(revm)* Add prevrandao field to EnvBlock ([#271](https://github.com/bluealloy/revm/pull/271))
- Migrate `primitive_types::U256` to `ruint::Uint<256, 4>` ([#239](https://github.com/bluealloy/revm/pull/239))
- *(revm, revme)* gas inspector ([#222](https://github.com/bluealloy/revm/pull/222))

### Fixed
- *(eip4844)* Pass eth tests, additional conditions added. ([#735](https://github.com/bluealloy/revm/pull/735))
- *(test)* Check expect exception and revm error ([#734](https://github.com/bluealloy/revm/pull/734))
- k256 compile error ([#451](https://github.com/bluealloy/revm/pull/451))

### Other
- *(EvmBuilder)* rename builder functions to HandlerCfg ([#1050](https://github.com/bluealloy/revm/pull/1050))
- *(Interpreter)* Split calls to separate functions ([#1005](https://github.com/bluealloy/revm/pull/1005))
- *(revme)* EmptyDb Blockhash string, json-outcome flag, set prevrandao in statetest ([#994](https://github.com/bluealloy/revm/pull/994))
- *(revme)* add recovery of address from secret key ([#992](https://github.com/bluealloy/revm/pull/992))
- *(log)* use alloy_primitives::Log ([#975](https://github.com/bluealloy/revm/pull/975))
- *(docs)* revme readme update ([#898](https://github.com/bluealloy/revm/pull/898))
- simplify use statements ([#864](https://github.com/bluealloy/revm/pull/864))
- decode KZG points directly into the buffers ([#840](https://github.com/bluealloy/revm/pull/840))
- bump v26 revm v3.5.0 ([#765](https://github.com/bluealloy/revm/pull/765))
- tag v25, revm v3.4.0 ([#755](https://github.com/bluealloy/revm/pull/755))
- BLOBBASEFEE opcode ([#721](https://github.com/bluealloy/revm/pull/721))
- Never inline the prepare functions ([#712](https://github.com/bluealloy/revm/pull/712))
- *(deps)* bump bytes from 1.4.0 to 1.5.0 ([#707](https://github.com/bluealloy/revm/pull/707))
- make `impl Default for StateBuilder` generic ([#690](https://github.com/bluealloy/revm/pull/690))
- *(deps)* bump walkdir from 2.3.3 to 2.4.0 ([#692](https://github.com/bluealloy/revm/pull/692))
- *(cfg)* convert chain_id from u256 to u64 ([#693](https://github.com/bluealloy/revm/pull/693))
- Revert "feat: alloy migration ([#535](https://github.com/bluealloy/revm/pull/535))" ([#616](https://github.com/bluealloy/revm/pull/616))
- spell check ([#615](https://github.com/bluealloy/revm/pull/615))
- avoid unnecessary allocations ([#581](https://github.com/bluealloy/revm/pull/581))
- clippy and fmt ([#568](https://github.com/bluealloy/revm/pull/568))
- optimize stack usage for recursive `call` and `create` programs ([#522](https://github.com/bluealloy/revm/pull/522))
- *(deps)* bump hashbrown from 0.13.2 to 0.14.0 ([#519](https://github.com/bluealloy/revm/pull/519))
- Bump v24, revm v3.3.0 ([#476](https://github.com/bluealloy/revm/pull/476))
- *(deps)* bump ruint from 1.7.0 to 1.8.0 ([#465](https://github.com/bluealloy/revm/pull/465))
- Release v23, revm v3.2.0 ([#464](https://github.com/bluealloy/revm/pull/464))
- Release v22, revm v3.1.1 ([#460](https://github.com/bluealloy/revm/pull/460))
- v21, revm v3.1.0 ([#444](https://github.com/bluealloy/revm/pull/444))
- bump all
- remove gas blocks ([#391](https://github.com/bluealloy/revm/pull/391))
- *(deps)* bump bytes from 1.3.0 to 1.4.0 ([#355](https://github.com/bluealloy/revm/pull/355))
- Bump v20, changelog ([#350](https://github.com/bluealloy/revm/pull/350))
- Cleanup imports ([#348](https://github.com/bluealloy/revm/pull/348))
- includes to libs ([#338](https://github.com/bluealloy/revm/pull/338))
- Creating revm-primitives, revm better errors and db components  ([#334](https://github.com/bluealloy/revm/pull/334))
- Correct typo ([#282](https://github.com/bluealloy/revm/pull/282))
- Integer overflow while calculating the remaining gas in GasInspector ([#287](https://github.com/bluealloy/revm/pull/287))
- native bits ([#278](https://github.com/bluealloy/revm/pull/278))
- *(release)* Bump revm and precompiles versions
- Bump primitive_types. Add statetest spec
- Bump revm to v2.3.0
- typos ([#263](https://github.com/bluealloy/revm/pull/263))
- *(eth/test)* Added OEF spec for tests. Skip HighGasPrice ([#261](https://github.com/bluealloy/revm/pull/261))
- Bump revm v2.1.0 ([#224](https://github.com/bluealloy/revm/pull/224))
# v0.1.0
date: 18.12.2021

Initial release. statetest are done, other things I have just started working on.