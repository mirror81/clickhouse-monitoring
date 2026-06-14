# Changelog

All notable changes to this project are documented in this file. Versioned
entries are generated automatically by [release-please](.github/workflows/release-please.yml)
from conventional commits; the `Unreleased` section below is a human-curated
preview of the next release.

## [0.2.9](https://github.com/mirror81/clickhouse-monitoring/compare/v0.2.8...v0.2.9) (2026-06-14)


### ✨ Features

* add perf-compare script for Win Metrics ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1514](https://github.com/mirror81/clickhouse-monitoring/issues/1514)) ([faa6972](https://github.com/mirror81/clickhouse-monitoring/commit/faa697231f10a44d280ea8188046855a597e9f89))
* **agent:** add conversation storage adapters ([#1517](https://github.com/mirror81/clickhouse-monitoring/issues/1517)) ([34ac9d4](https://github.com/mirror81/clickhouse-monitoring/commit/34ac9d4b847124c19d31ccae9eea90a56ec469f4))
* **agent:** auto-generate conversation titles from first message ([#1319](https://github.com/mirror81/clickhouse-monitoring/issues/1319)) ([be8fec7](https://github.com/mirror81/clickhouse-monitoring/commit/be8fec73c614e1cdcbc757ef01f324e9a4f9c2b2))
* **agent:** multi-provider config + chat UI redesign ([#1296](https://github.com/mirror81/clickhouse-monitoring/issues/1296)) ([8378e93](https://github.com/mirror81/clickhouse-monitoring/commit/8378e936cd6df3a30d60752c7bf2812eeba6067c))
* **agent:** persist agent findings + record/list findings tools ([#1312](https://github.com/mirror81/clickhouse-monitoring/issues/1312)) ([8a4ca14](https://github.com/mirror81/clickhouse-monitoring/commit/8a4ca14799311063457867da2c9d8ab3bedbe3e0))
* **agents:** chain-of-thought, error, stats, timing, ghost reasoning ([#1188](https://github.com/mirror81/clickhouse-monitoring/issues/1188)) ([46bb457](https://github.com/mirror81/clickhouse-monitoring/commit/46bb457b5470c1788d2b7ed42491746dd64bb05a))
* **agents:** MCP config panel in right sidebar ([#1185](https://github.com/mirror81/clickhouse-monitoring/issues/1185)) ([4f5ed71](https://github.com/mirror81/clickhouse-monitoring/commit/4f5ed719494f87fcf1a9d3b914d744dbc2da89d3))
* **agents:** polish agents page — dialogs, scrollable popovers, header cleanup ([#1239](https://github.com/mirror81/clickhouse-monitoring/issues/1239)) ([214956a](https://github.com/mirror81/clickhouse-monitoring/commit/214956a0d2e478b2bc2591783a414c991852e70c))
* **agents:** show chat UI for everyone, gate sending on sign-in ([#1238](https://github.com/mirror81/clickhouse-monitoring/issues/1238)) ([ef6e3b1](https://github.com/mirror81/clickhouse-monitoring/commit/ef6e3b19ba2ec7646db126a785492dd1497d5fde))
* **agents:** Streamdown audit + theme-aware syntax highlighting ([#1187](https://github.com/mirror81/clickhouse-monitoring/issues/1187)) ([e5f2f7e](https://github.com/mirror81/clickhouse-monitoring/commit/e5f2f7ef3066fa69d2b767a808e02d3130269b36))
* **agents:** theme-aware mermaid diagrams in chat ([#1186](https://github.com/mirror81/clickhouse-monitoring/issues/1186)) ([d18550a](https://github.com/mirror81/clickhouse-monitoring/commit/d18550acdf351ff50a0917eb8721bc4dd9813c75))
* **agent:** workflow harness with dynamic workflow templates ([#1279](https://github.com/mirror81/clickhouse-monitoring/issues/1279)) ([026e8aa](https://github.com/mirror81/clickhouse-monitoring/commit/026e8aad6cf7ab50c41eb1849b604205c34cdbd2))
* **alerting:** autonomous scheduled health-sweep cron ([#1305](https://github.com/mirror81/clickhouse-monitoring/issues/1305)) ([a0e3beb](https://github.com/mirror81/clickhouse-monitoring/commit/a0e3beb9175ae5e27d98335019d7c616678cb193))
* **auth:** activate CHM_CLERK_PUBLIC_READ on dash + dash-tsr ([#1536](https://github.com/mirror81/clickhouse-monitoring/issues/1536)) ([e9b7e45](https://github.com/mirror81/clickhouse-monitoring/commit/e9b7e45d46cce5ce796e23f71d2e9f3d3e4befcd))
* **auth:** read/write permission model + CHM_CLERK_PUBLIC_READ ([#1535](https://github.com/mirror81/clickhouse-monitoring/issues/1535)) ([1112238](https://github.com/mirror81/clickhouse-monitoring/commit/1112238714d3d3d24ec01757e089c10c3752e477))
* **charts:** add dictionary-count client chart and register lazy import ([#1258](https://github.com/mirror81/clickhouse-monitoring/issues/1258)) ([50de54d](https://github.com/mirror81/clickhouse-monitoring/commit/50de54dc52e9946faa6f6dc17e7ed145ab4835f5))
* **charts:** extract ProportionList primitive from 3 duplicated bar charts ([#1266](https://github.com/mirror81/clickhouse-monitoring/issues/1266)) ([f245c10](https://github.com/mirror81/clickhouse-monitoring/commit/f245c10120bc68eadd9d9ace11bb4b09369210c2))
* **charts:** render correct units in compact chart row mode ([#1208](https://github.com/mirror81/clickhouse-monitoring/issues/1208)) ([024125c](https://github.com/mirror81/clickhouse-monitoring/commit/024125c204ba0b2274c0b0074a1d2e8fb4766f92))
* **charts:** route status colors through shared tokens ([#1267](https://github.com/mirror81/clickhouse-monitoring/issues/1267)) ([f018987](https://github.com/mirror81/clickhouse-monitoring/commit/f018987b779472414e5bdec5f4938692a59b37d9))
* **charts:** smart compact chart row with KPI summaries while hidden ([#1195](https://github.com/mirror81/clickhouse-monitoring/issues/1195)) ([62490d1](https://github.com/mirror81/clickhouse-monitoring/commit/62490d1af1256be68b4da72f7f70ec3af3355442))
* **ci:** add preview deployment for TanStack Start dashboard ([#1424](https://github.com/mirror81/clickhouse-monitoring/issues/1424)) ([d9f6336](https://github.com/mirror81/clickhouse-monitoring/commit/d9f6336ff94b8b9d91679baf0bae84c960e42b4e))
* **cloudflare:** cloud→dash 301 via edge Redirect Rule + track MCP secret ([#1385](https://github.com/mirror81/clickhouse-monitoring/issues/1385)) ([822956e](https://github.com/mirror81/clickhouse-monitoring/commit/822956e8ea1f879fb3fb10768b722f8ce38d1427))
* **cluster:** real-data topology API for all cluster shapes ([#1332](https://github.com/mirror81/clickhouse-monitoring/issues/1332)) ([3455ecb](https://github.com/mirror81/clickhouse-monitoring/commit/3455ecb9b354aa9724dcb7b93b056e1c8a0ae587))
* **cluster:** robust offset-hull cluster overlays for all topology shapes ([#1334](https://github.com/mirror81/clickhouse-monitoring/issues/1334)) ([8a1be85](https://github.com/mirror81/clickhouse-monitoring/commit/8a1be8525245d7d6d84aba99f75b826b9ba66882))
* **cluster:** upgrade /cluster into Cluster Topology visualization ([#1328](https://github.com/mirror81/clickhouse-monitoring/issues/1328)) ([11b1d9d](https://github.com/mirror81/clickhouse-monitoring/commit/11b1d9d337aeb970975813ab6732cb4af9ee0569))
* **dashboard-tsr:** BI-style SQL Console + fix explorer tab-switch freeze ([#1531](https://github.com/mirror81/clickhouse-monitoring/issues/1531)) ([b42ebb9](https://github.com/mirror81/clickhouse-monitoring/commit/b42ebb9be1af587008e531436c941eae9a4e026e))
* **dashboard-tsr:** chart components + API routes + query-config bulk port ([#1394](https://github.com/mirror81/clickhouse-monitoring/issues/1394)) ([#1419](https://github.com/mirror81/clickhouse-monitoring/issues/1419)) ([4fcfa8f](https://github.com/mirror81/clickhouse-monitoring/commit/4fcfa8fb7bb33c4252d0c9fd195977ae3a5aee2d))
* **dashboard-tsr:** Clerk auth provider gating (@clerk/tanstack-react-start) ([#1400](https://github.com/mirror81/clickhouse-monitoring/issues/1400)) ([#1413](https://github.com/mirror81/clickhouse-monitoring/issues/1413)) ([7e04a03](https://github.com/mirror81/clickhouse-monitoring/commit/7e04a03c4f54a08126c53cfa27baec57b1882768))
* **dashboard-tsr:** data-table system + chart base + shared components ([#1393](https://github.com/mirror81/clickhouse-monitoring/issues/1393)) ([7427547](https://github.com/mirror81/clickhouse-monitoring/commit/74275477d1d270995c9f46e1601ed2bf96239e24))
* **dashboard-tsr:** dual-target build — Cloudflare Workers + Docker/Node ([#1409](https://github.com/mirror81/clickhouse-monitoring/issues/1409)) ([#1410](https://github.com/mirror81/clickhouse-monitoring/issues/1410)) ([8e7c7ff](https://github.com/mirror81/clickhouse-monitoring/commit/8e7c7ff43d12e6b2a448e7ef9e177d6b4512d711))
* **dashboard-tsr:** in-process MCP route + fix logs/ gitignore drop ([#1398](https://github.com/mirror81/clickhouse-monitoring/issues/1398)) ([#1421](https://github.com/mirror81/clickhouse-monitoring/issues/1421)) ([dc91918](https://github.com/mirror81/clickhouse-monitoring/commit/dc91918c738aeaf20197ee7f0d2aae3c759aa22f))
* **dashboard-tsr:** pluggable auth providers (none|clerk|proxy) + CF Access/proxy + auth docs + v0.3 changelog ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1440](https://github.com/mirror81/clickhouse-monitoring/issues/1440)) ([4c2a50c](https://github.com/mirror81/clickhouse-monitoring/commit/4c2a50c3b6ed892dce862338b753a5eab3e68772))
* **dashboard-tsr:** port ~22 Next API routes to TanStack Start (Phase 5, [#1396](https://github.com/mirror81/clickhouse-monitoring/issues/1396)) ([#1422](https://github.com/mirror81/clickhouse-monitoring/issues/1422)) ([91211f9](https://github.com/mirror81/clickhouse-monitoring/commit/91211f97ad37a3d67fc4b461022a1fde102bcd21))
* **dashboard-tsr:** port 4 API routes (timezone, host-status, notifications, health) ([#1396](https://github.com/mirror81/clickhouse-monitoring/issues/1396)) ([#1412](https://github.com/mirror81/clickhouse-monitoring/issues/1412)) ([dc6fd79](https://github.com/mirror81/clickhouse-monitoring/commit/dc6fd791619f7c6e25f3b9065bf02febfc8930e7))
* **dashboard-tsr:** port 75 dashboard pages → TanStack Start (Phase 4, [#1402](https://github.com/mirror81/clickhouse-monitoring/issues/1402)) ([#1420](https://github.com/mirror81/clickhouse-monitoring/issues/1420)) ([9e08522](https://github.com/mirror81/clickhouse-monitoring/commit/9e08522d10dc4b55edf84a7fae84af30a4552f63))
* **dashboard-tsr:** port AI agent subsystem to TanStack Start ([#1401](https://github.com/mirror81/clickhouse-monitoring/issues/1401)) ([#1426](https://github.com/mirror81/clickhouse-monitoring/issues/1426)) ([179a710](https://github.com/mirror81/clickhouse-monitoring/commit/179a7101a8e2b3e25db94f74371a52b84e2e393b))
* **dashboard-tsr:** port cluster-topology API + fix explorer 400 validation ([#1429](https://github.com/mirror81/clickhouse-monitoring/issues/1429)) ([85c7f30](https://github.com/mirror81/clickhouse-monitoring/commit/85c7f301dbc0f9e11bd2ea729d607bc870eb8f71)), closes [#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)
* **dashboard-tsr:** port logs/peerdb/docs pages + simple/infra API routes ([#1396](https://github.com/mirror81/clickhouse-monitoring/issues/1396) [#1402](https://github.com/mirror81/clickhouse-monitoring/issues/1402)) ([#1425](https://github.com/mirror81/clickhouse-monitoring/issues/1425)) ([4ec082e](https://github.com/mirror81/clickhouse-monitoring/commit/4ec082efdcff800a230ca089cf028ee660e5b1ba))
* **dashboard-tsr:** port middleware.ts to TanStack auth guards ([#1397](https://github.com/mirror81/clickhouse-monitoring/issues/1397)) ([#1428](https://github.com/mirror81/clickhouse-monitoring/issues/1428)) ([fe031f5](https://github.com/mirror81/clickhouse-monitoring/commit/fe031f52ff3156d7038adff46a7d7c878d4bff09))
* **dashboard-tsr:** post-deploy verify skill + env normalization ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1436](https://github.com/mirror81/clickhouse-monitoring/issues/1436)) ([eb64ac5](https://github.com/mirror81/clickhouse-monitoring/commit/eb64ac546d96e17a5a25ab7050e9d95d8fa6c7ce))
* **dashboard-tsr:** query-config + chart/table registry foundation ([#1396](https://github.com/mirror81/clickhouse-monitoring/issues/1396)) ([#1415](https://github.com/mirror81/clickhouse-monitoring/issues/1415)) ([38754ac](https://github.com/mirror81/clickhouse-monitoring/commit/38754acea6227894a2f58f9990007dcbc93f5af4))
* **dashboard-tsr:** routing + TanStack Query + static prerender ([#1395](https://github.com/mirror81/clickhouse-monitoring/issues/1395)) ([#1411](https://github.com/mirror81/clickhouse-monitoring/issues/1411)) ([f69f542](https://github.com/mirror81/clickhouse-monitoring/commit/f69f542e4bf1063048f688e6c87b36e98d0a1939))
* **dashboard-tsr:** shadcn UI primitives + skeletons foundation ([#1395](https://github.com/mirror81/clickhouse-monitoring/issues/1395)) ([#1416](https://github.com/mirror81/clickhouse-monitoring/issues/1416)) ([130014e](https://github.com/mirror81/clickhouse-monitoring/commit/130014e5ff4f0d967c9b7313b937872c48e0922e))
* **dashboard-tsr:** shared config + env bridge + @chm/* seam ([#1394](https://github.com/mirror81/clickhouse-monitoring/issues/1394)) ([#1407](https://github.com/mirror81/clickhouse-monitoring/issues/1407)) ([2c63189](https://github.com/mirror81/clickhouse-monitoring/commit/2c6318907c62a364daa52a83abe2fc0101df50d6))
* **dashboard-tsr:** TanStack Start substrate spike ([#1406](https://github.com/mirror81/clickhouse-monitoring/issues/1406)) ([a9937ea](https://github.com/mirror81/clickhouse-monitoring/commit/a9937eac08d54845f715b7555f405baeee7b1d37))
* **dashboard-tsr:** wire @chm/clickhouse-client on workerd + 3 API routes ([#1396](https://github.com/mirror81/clickhouse-monitoring/issues/1396)) ([#1408](https://github.com/mirror81/clickhouse-monitoring/issues/1408)) ([bdcb481](https://github.com/mirror81/clickhouse-monitoring/commit/bdcb48132a55c606ac41d68342f6e7cbe82aaa6f))
* **dashboard-tsr:** wire app chrome + port shadcn theme ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1433](https://github.com/mirror81/clickhouse-monitoring/issues/1433)) ([478378f](https://github.com/mirror81/clickhouse-monitoring/commit/478378f4cc73c6493fef174e35b2c955c771501b))
* **data-table:** address review feedback and mobile cards expand ([4600d05](https://github.com/mirror81/clickhouse-monitoring/commit/4600d0575bc42a523e02b7c12659b2160bc72d5c))
* **data-table:** card grid layout for all pages with phone support ([ca821c2](https://github.com/mirror81/clickhouse-monitoring/commit/ca821c21525a4e3af5e8467ae6bd02086df47993))
* **data-table:** declarative card layout via QueryConfig.card ([#1339](https://github.com/mirror81/clickhouse-monitoring/issues/1339)) ([490639f](https://github.com/mirror81/clickhouse-monitoring/commit/490639fd26266171a8b0f2dbe1e67c7c9d401cd6))
* **data-table:** declarative rich expand panels via createExpandedPanel ([#1340](https://github.com/mirror81/clickhouse-monitoring/issues/1340)) ([7fb743e](https://github.com/mirror81/clickhouse-monitoring/commit/7fb743e6782844acf22f49fbc159ae57c3888c0b))
* **data-table:** responsive card grid for entity pages ([#1346](https://github.com/mirror81/clickhouse-monitoring/issues/1346)) ([dfc59b4](https://github.com/mirror81/clickhouse-monitoring/commit/dfc59b43d458841b9d01a9ab61f5cbdc7331806e))
* **data-table:** row expansion, per-column filters, filter bar ([#1193](https://github.com/mirror81/clickhouse-monitoring/issues/1193)) ([4600d05](https://github.com/mirror81/clickhouse-monitoring/commit/4600d0575bc42a523e02b7c12659b2160bc72d5c))
* **data-table:** SQL-hero mobile cards + table/card toggle on mobile ([#1278](https://github.com/mirror81/clickhouse-monitoring/issues/1278)) ([84c59e7](https://github.com/mirror81/clickhouse-monitoring/commit/84c59e7a833a2673dcdb56954e6b6af0020cbc52))
* **deploy:** kustomize base + kubeconform/helm-lint CI gate + k8s guide ([#1314](https://github.com/mirror81/clickhouse-monitoring/issues/1314)) ([368923e](https://github.com/mirror81/clickhouse-monitoring/commit/368923e35c30ca9556a63c8fc3189a7ef161b563))
* **deploy:** vendor production Helm chart in-repo ([#1306](https://github.com/mirror81/clickhouse-monitoring/issues/1306)) ([7a6fdd0](https://github.com/mirror81/clickhouse-monitoring/commit/7a6fdd0698e78167cb18be98b62035944b19644c))
* **disks:** redesign disks page with bento grid cards ([#1327](https://github.com/mirror81/clickhouse-monitoring/issues/1327)) ([a6e883d](https://github.com/mirror81/clickhouse-monitoring/commit/a6e883d728e3af80557e44f086289f2e73914482))
* **docs:** add standalone Astro Starlight docs scaffold ([#1373](https://github.com/mirror81/clickhouse-monitoring/issues/1373)) ([0014be6](https://github.com/mirror81/clickhouse-monitoring/commit/0014be66e20d3729006ea485aca0d9bb8e5ea3eb))
* **docs:** astro-design-system theme + per-release versioning ([#1529](https://github.com/mirror81/clickhouse-monitoring/issues/1529)) ([2552de4](https://github.com/mirror81/clickhouse-monitoring/commit/2552de4365481cabd796526ed1e8d1d42b7ca78a))
* **docs:** surface AI Agent, Env Reference, PeerDB in sidebar nav ([#1301](https://github.com/mirror81/clickhouse-monitoring/issues/1301)) ([80dacb4](https://github.com/mirror81/clickhouse-monitoring/commit/80dacb406212470e32bb7f36d61a10235d202b18))
* **docs:** sync dashboard docs into Starlight site ([#1374](https://github.com/mirror81/clickhouse-monitoring/issues/1374)) ([a2d3ccc](https://github.com/mirror81/clickhouse-monitoring/commit/a2d3ccc8aebf62e2be29091429c6b3969c029857))
* **expensive-queries:** redesigned responsive table with expand, filters, highlight ([#1320](https://github.com/mirror81/clickhouse-monitoring/issues/1320)) ([d3f5096](https://github.com/mirror81/clickhouse-monitoring/commit/d3f50960d860fa5f1909ac6d6704fee21173047e))
* **explain:** render query plan as a tree visualization ([#1325](https://github.com/mirror81/clickhouse-monitoring/issues/1325)) ([5f9dbc4](https://github.com/mirror81/clickhouse-monitoring/commit/5f9dbc4e998479507fb84ff1c611126dff32c238))
* **failed-queries:** add filters + fix truncated action-column header ([#1317](https://github.com/mirror81/clickhouse-monitoring/issues/1317)) ([6be30c3](https://github.com/mirror81/clickhouse-monitoring/commit/6be30c36176ab3b6596d402ee2e2df8d53a5624a))
* **filters:** add per-page quick filters with segmented control ([fb07706](https://github.com/mirror81/clickhouse-monitoring/commit/fb07706150819c8892eb29414736f90d4aee4e6b))
* **health,data-table:** mobile-first grid + filter URL builder tests ([1800d9e](https://github.com/mirror81/clickhouse-monitoring/commit/1800d9e5cef78dec2e8699058cf3f5e35d559378))
* **health:** address review feedback and server webhook proxy ([9899733](https://github.com/mirror81/clickhouse-monitoring/commit/9899733e5f541fe3050d30def2c71b1840707d21))
* **health:** expand checks, drop shadows, add threshold + alert config ([#1198](https://github.com/mirror81/clickhouse-monitoring/issues/1198)) ([9899733](https://github.com/mirror81/clickhouse-monitoring/commit/9899733e5f541fe3050d30def2c71b1840707d21))
* **health:** SQL in detail dialog + audit-prompt toggles & token count ([#1244](https://github.com/mirror81/clickhouse-monitoring/issues/1244)) ([8362a9a](https://github.com/mirror81/clickhouse-monitoring/commit/8362a9a2b04c6e631e8b41038a4b36707afbe58f))
* **host:** show version and uptime in host switcher popover ([#1199](https://github.com/mirror81/clickhouse-monitoring/issues/1199)) ([9a4d71d](https://github.com/mirror81/clickhouse-monitoring/commit/9a4d71db0285ad322c2f5a401894ffd45cdbb980))
* **keeper:** Keeper monitoring ([#1214](https://github.com/mirror81/clickhouse-monitoring/issues/1214)) ([5a66c38](https://github.com/mirror81/clickhouse-monitoring/commit/5a66c38ec58ca6742aba7ed24a217556fa6d6d2a))
* **keeper:** render /keeper/info with KeeperNodeCards ([#1257](https://github.com/mirror81/clickhouse-monitoring/issues/1257)) ([4548f79](https://github.com/mirror81/clickhouse-monitoring/commit/4548f79a2956de55d00701dcaed41df856338f8e))
* **landing:** add Astro marketing scaffold (chmonitor.dev) ([#1370](https://github.com/mirror81/clickhouse-monitoring/issues/1370)) ([b45e96f](https://github.com/mirror81/clickhouse-monitoring/commit/b45e96f2292ca6df1b85ba250a805b6c1ea855ba))
* **landing:** add remaining marketing sections ([#1371](https://github.com/mirror81/clickhouse-monitoring/issues/1371)) ([9c357c0](https://github.com/mirror81/clickhouse-monitoring/commit/9c357c0cffd207fb44608140065714df1333f4c4))
* **mcp:** Clerk OAuth for MCP — login/consent flow + REST verify ([#1388](https://github.com/mirror81/clickhouse-monitoring/issues/1388)) ([9ca3844](https://github.com/mirror81/clickhouse-monitoring/commit/9ca3844ef594a74f5f0050a29324017766a4396e))
* **menu:** sidebar table-availability muting + version-mismatch/permission UX ([#1349](https://github.com/mirror81/clickhouse-monitoring/issues/1349)) ([33292f7](https://github.com/mirror81/clickhouse-monitoring/commit/33292f774b1db7468b88cd941739bea532895d7b))
* **monitoring:** add Kafka consumer view from system.kafka_consumers ([#1304](https://github.com/mirror81/clickhouse-monitoring/issues/1304)) ([e73798a](https://github.com/mirror81/clickhouse-monitoring/commit/e73798ac8a3c74ec69640d3b6d745252bb9149bc))
* **monitoring:** add part lifecycle timeline from system.part_log ([#1303](https://github.com/mirror81/clickhouse-monitoring/issues/1303)) ([ed4b094](https://github.com/mirror81/clickhouse-monitoring/commit/ed4b09414747eaa1c31e7c3d4d1730fc5698c7d7))
* **monitoring:** add system.dropped_tables view at /dropped-tables ([#1290](https://github.com/mirror81/clickhouse-monitoring/issues/1290)) ([61351ca](https://github.com/mirror81/clickhouse-monitoring/commit/61351ca67d33c1d39c966bf343ae075fb568163c))
* **monitoring:** add system.moves view at /moves ([#1291](https://github.com/mirror81/clickhouse-monitoring/issues/1291)) ([1128e11](https://github.com/mirror81/clickhouse-monitoring/commit/1128e11d81d0c13282b1c8f3d602ec1f8ada5f37))
* **monitoring:** add system.query_metric_log view ([#1309](https://github.com/mirror81/clickhouse-monitoring/issues/1309)) ([1209aac](https://github.com/mirror81/clickhouse-monitoring/commit/1209aac227b96d191cacf0c6b058ba3f5fb157a1))
* **monitoring:** add system.replicated_fetches view at /replicated-fetches ([#1294](https://github.com/mirror81/clickhouse-monitoring/issues/1294)) ([8de1a92](https://github.com/mirror81/clickhouse-monitoring/commit/8de1a92f280a784c54f177e736f9230e5d80646f))
* **monitoring:** add system.replicated_merge_tree_settings view at /replicated-merge-tree-settings ([#1295](https://github.com/mirror81/clickhouse-monitoring/issues/1295)) ([a6fb6ee](https://github.com/mirror81/clickhouse-monitoring/commit/a6fb6ee98a6528defcede32965aef4d5d94f827e))
* **monitoring:** add system.user_processes view at /user-processes ([#1293](https://github.com/mirror81/clickhouse-monitoring/issues/1293)) ([1cc5c41](https://github.com/mirror81/clickhouse-monitoring/commit/1cc5c4148ba50a7c7444bc02c7006c35a669dbff))
* **monitoring:** add system.warnings view at /warnings ([#1292](https://github.com/mirror81/clickhouse-monitoring/issues/1292)) ([1c1538f](https://github.com/mirror81/clickhouse-monitoring/commit/1c1538fb8c94cf48f3c014255f35a1b350273ff5))
* **part-log:** redesign page with lifecycle charts, KPIs, and rich events table ([#1323](https://github.com/mirror81/clickhouse-monitoring/issues/1323)) ([15f4f0b](https://github.com/mirror81/clickhouse-monitoring/commit/15f4f0b0c220336aea39a5692ac906ca84d9b27b))
* **peerdb:** enhance peers table with logos + mirror stats, center topology expand button ([#1297](https://github.com/mirror81/clickhouse-monitoring/issues/1297)) ([b732f8c](https://github.com/mirror81/clickhouse-monitoring/commit/b732f8c15e6cc9a5c3d12ae1a02ba8ed20dd6f61))
* **peerdb:** PeerDB monitoring ([#1209](https://github.com/mirror81/clickhouse-monitoring/issues/1209)) ([4bcfa2e](https://github.com/mirror81/clickhouse-monitoring/commit/4bcfa2e3214d7e6d26909d58c9c1bdeff526ebbc))
* **query-config:** card + rich expand for the query-log query lists ([#1341](https://github.com/mirror81/clickhouse-monitoring/issues/1341)) ([971aa98](https://github.com/mirror81/clickhouse-monitoring/commit/971aa98d339640dd30faf34c67e63a44f42b1a98))
* **query-config:** card view for all table/replication pages ([#1342](https://github.com/mirror81/clickhouse-monitoring/issues/1342)) ([e2d08ea](https://github.com/mirror81/clickhouse-monitoring/commit/e2d08ea2baf8952d9fb34af4e776041b44af982d))
* **query-config:** card view for merges + system entity pages ([#1343](https://github.com/mirror81/clickhouse-monitoring/issues/1343)) ([75660ba](https://github.com/mirror81/clickhouse-monitoring/commit/75660bacb1e84ec1c3b44fc7e68056a4109e51bc))
* **query-config:** card view for more/ + keeper/ pages ([#1344](https://github.com/mirror81/clickhouse-monitoring/issues/1344)) ([0c23915](https://github.com/mirror81/clickhouse-monitoring/commit/0c239150ba9773ea291ba07deebfd12fdd1b89f5))
* **query-config:** card view for remaining query diagnostic pages ([#1345](https://github.com/mirror81/clickhouse-monitoring/issues/1345)) ([ac7e9fc](https://github.com/mirror81/clickhouse-monitoring/commit/ac7e9fc5a7a6ca2e9d2a785406422fc3f39dda8b))
* **readonly-tables:** add expandable diagnostics row and AI fix prompt action ([#1261](https://github.com/mirror81/clickhouse-monitoring/issues/1261)) ([e23b794](https://github.com/mirror81/clickhouse-monitoring/commit/e23b7944af7fdf372e0e18a916cbb32d1358f572))
* **release:** tiered LLM notes (Copilot→Models→AnyRouter), recap stats, docker pin ([#1582](https://github.com/mirror81/clickhouse-monitoring/issues/1582)) ([3009f99](https://github.com/mirror81/clickhouse-monitoring/commit/3009f994a9c73f3a018ddae6f148a7a8bce9103b))
* **running-queries:** cap completed list to 10, add Done badge per row ([#1330](https://github.com/mirror81/clickhouse-monitoring/issues/1330)) ([993d89a](https://github.com/mirror81/clickhouse-monitoring/commit/993d89afa6e1f67d5962da4b7101452641391feb))
* **running-queries:** split into running + recently-completed tables with live transition ([#1321](https://github.com/mirror81/clickhouse-monitoring/issues/1321)) ([e07dd63](https://github.com/mirror81/clickhouse-monitoring/commit/e07dd63bd9ba2012caf91fb4b1963f7725d8b0ae))
* **running-queries:** SQL-first card view + table/card toggle ([#1280](https://github.com/mirror81/clickhouse-monitoring/issues/1280)) ([17cad57](https://github.com/mirror81/clickhouse-monitoring/commit/17cad5764f869e0e1e38dd83e180df1f758c868b))
* **seo:** add sitemap.xml and robots.txt ([#1333](https://github.com/mirror81/clickhouse-monitoring/issues/1333)) ([21c6cec](https://github.com/mirror81/clickhouse-monitoring/commit/21c6cec0c603321137418166444772c6e35f0947))
* **slow-queries:** redesigned responsive table with expand, filters, highlight ([#1322](https://github.com/mirror81/clickhouse-monitoring/issues/1322)) ([d53ab82](https://github.com/mirror81/clickhouse-monitoring/commit/d53ab8210bc9bc0a36a7b5129cd622bfd3bb10af))
* **tables:** card view for low-cardinality tables ([#1249](https://github.com/mirror81/clickhouse-monitoring/issues/1249)) ([8e1d92c](https://github.com/mirror81/clickhouse-monitoring/commit/8e1d92c9e62f68f80ecdf47702dcba52d7f1d8f4))
* **tables:** expandable "more info" rows for config tables ([#1248](https://github.com/mirror81/clickhouse-monitoring/issues/1248)) ([ae0b2e8](https://github.com/mirror81/clickhouse-monitoring/commit/ae0b2e8464e5b248c5b78fdff3ecaa7b5ae02067))
* **topology:** label & toggle physical clusters, data-driven height, Claude palette ([#1354](https://github.com/mirror81/clickhouse-monitoring/issues/1354)) ([235e790](https://github.com/mirror81/clickhouse-monitoring/commit/235e7905d6a08d55fe4c1c874fc59f23b6558851))
* **topology:** redesign cluster topo — distinct node shapes, CH logo, fix black fills ([#1350](https://github.com/mirror81/clickhouse-monitoring/issues/1350)) ([4bcd50e](https://github.com/mirror81/clickhouse-monitoring/commit/4bcd50e53a7904efaf43103c70b6b43a0107b818))
* **tracking:** direct CSV export from any chart card ([#1311](https://github.com/mirror81/clickhouse-monitoring/issues/1311)) ([0e0a83f](https://github.com/mirror81/clickhouse-monitoring/commit/0e0a83fb77a31462bcef90f6c5182e448f19800f))
* **tracking:** persist auto-refresh interval across reloads ([#1307](https://github.com/mirror81/clickhouse-monitoring/issues/1307)) ([0e604a1](https://github.com/mirror81/clickhouse-monitoring/commit/0e604a1dba00f0218926203306d2d4fc8c110f4c))
* **tracking:** persist global time range to localStorage + URL ([#1300](https://github.com/mirror81/clickhouse-monitoring/issues/1300)) ([ad28a61](https://github.com/mirror81/clickhouse-monitoring/commit/ad28a61bff4ac949330813bf8aec7cb6faf2f006))
* **ui:** add PageHeader primitive and adopt in health/cluster/running-queries ([#1270](https://github.com/mirror81/clickhouse-monitoring/issues/1270)) ([4dc9e3d](https://github.com/mirror81/clickhouse-monitoring/commit/4dc9e3d178ce28f2057d812eca54d9efe8621c08))
* **ui:** keeper cards + connections expand, health cards, security charts, menu ([#1241](https://github.com/mirror81/clickhouse-monitoring/issues/1241)) ([d87ca71](https://github.com/mirror81/clickhouse-monitoring/commit/d87ca711f956b23f755bfb660e4f5a2902c99b38))
* **ui:** premium redesign of Request Info (SQL) dialog ([#1318](https://github.com/mirror81/clickhouse-monitoring/issues/1318)) ([6804ab1](https://github.com/mirror81/clickhouse-monitoring/commit/6804ab1eb58fdb4acf11d58224c06b3847585fb5))
* **user-processes:** format columns (user badge, memory bars, readable values) ([#1326](https://github.com/mirror81/clickhouse-monitoring/issues/1326)) ([13de92a](https://github.com/mirror81/clickhouse-monitoring/commit/13de92aff53a88568e15ddb8ffd68274562329f5))
* **ux:** first-run onboarding, explorer skeleton, explain empty state ([#1313](https://github.com/mirror81/clickhouse-monitoring/issues/1313)) ([21b88f3](https://github.com/mirror81/clickhouse-monitoring/commit/21b88f305893fa8778b24651c3a259f1555fb21f))
* **web:** enhance data table with search, filters, and sleek headers ([#1355](https://github.com/mirror81/clickhouse-monitoring/issues/1355)) ([7bb5f18](https://github.com/mirror81/clickhouse-monitoring/commit/7bb5f184b3349a4fe9deec18f5a784312c4e1ca3))
* **workers:** rename workers and wire chmonitor.dev subdomains ([#1376](https://github.com/mirror81/clickhouse-monitoring/issues/1376)) ([85888ae](https://github.com/mirror81/clickhouse-monitoring/commit/85888ae0b85d8b3034d521c416b00bb2970b212c))


### 🐛 Bug Fixes

* **a11y:** expose BackgroundBar as a progressbar + GPU-composited fill ([#1348](https://github.com/mirror81/clickhouse-monitoring/issues/1348)) ([ece6d31](https://github.com/mirror81/clickhouse-monitoring/commit/ece6d313443020694397df8a4beb4732b5b5f84d))
* add missing WASM artifact upload step in CI workflow ([#1553](https://github.com/mirror81/clickhouse-monitoring/issues/1553)) ([13fcd92](https://github.com/mirror81/clickhouse-monitoring/commit/13fcd928eb426b1bf520317d5a685e01db03f809))
* add Running Queries and Clusters as top-level sidebar items ([#1569](https://github.com/mirror81/clickhouse-monitoring/issues/1569)) ([74fc5eb](https://github.com/mirror81/clickhouse-monitoring/commit/74fc5eb6f2dae1a7bfe931cac07d0d57470c7bde))
* **agent:** apply robust, preprocessed hostId Zod schemas to all tools ([c523479](https://github.com/mirror81/clickhouse-monitoring/commit/c5234798454832c26ed726991f5ad14998e18020))
* **agent:** change default model away from broken preset ([#1182](https://github.com/mirror81/clickhouse-monitoring/issues/1182)) ([593061a](https://github.com/mirror81/clickhouse-monitoring/commit/593061a40727ce398f9237965493a4a25ba81603))
* **agent:** coerce string hostId in tool calls and add system-tables skill ([df4316f](https://github.com/mirror81/clickhouse-monitoring/commit/df4316f62bf9f5c3a55e741c4e428df7a638f35c))
* **agents:** break mcp-panel↔dialog import cycle ([#1242](https://github.com/mirror81/clickhouse-monitoring/issues/1242)) ([dc7f507](https://github.com/mirror81/clickhouse-monitoring/commit/dc7f507faadef14c0195cae28f9088f31aef417f))
* **agents:** don't auto-scroll the welcome screen on open ([#1240](https://github.com/mirror81/clickhouse-monitoring/issues/1240)) ([2d27e11](https://github.com/mirror81/clickhouse-monitoring/commit/2d27e115dfaedee0a2f2ff546311a7bb0b556e3b))
* **agent:** send AnyRouter category in X-AnyRouter-Categories, not the source header ([#1516](https://github.com/mirror81/clickhouse-monitoring/issues/1516)) ([20cb0a3](https://github.com/mirror81/clickhouse-monitoring/commit/20cb0a39a5d2493ddca163b15e7a5612af7561ea))
* **agents:** gate useUser behind isClerkEnabled + fail-fast query-config test ([#1235](https://github.com/mirror81/clickhouse-monitoring/issues/1235)) ([0534493](https://github.com/mirror81/clickhouse-monitoring/commit/05344934d0413465756162b2c8f87e361ea27b3f))
* **agents:** hide Thinking on error, surface CF 1027 cleanly ([#1197](https://github.com/mirror81/clickhouse-monitoring/issues/1197)) ([97fdad6](https://github.com/mirror81/clickhouse-monitoring/commit/97fdad68103515ca93f2db71f9485d8ae5f1b0e2))
* **agents:** mobile-responsive settings via shadcn Drawer ([#1190](https://github.com/mirror81/clickhouse-monitoring/issues/1190)) ([e8df1f8](https://github.com/mirror81/clickhouse-monitoring/commit/e8df1f852d72d70d5aa1f528a9fe53b136829bbe))
* **agents:** render agents page as client component for static output ([257bc97](https://github.com/mirror81/clickhouse-monitoring/commit/257bc972a9057e221d1416b2442dca892d9a7684))
* **agents:** tighten SQL/code block vertical spacing ([#1184](https://github.com/mirror81/clickhouse-monitoring/issues/1184)) ([c95b2d3](https://github.com/mirror81/clickhouse-monitoring/commit/c95b2d30708523ac503b4a873201d4495209107f))
* **api:** add missing /api/v1/tables list endpoint for autocomplete ([1d1f6bf](https://github.com/mirror81/clickhouse-monitoring/commit/1d1f6bfaab4f71b7f65610767cd507ebf3b9e9a3))
* **api:** enforce auth on clean/init/pageview endpoints and sanitize error responses ([#1602](https://github.com/mirror81/clickhouse-monitoring/issues/1602)) ([9b9d239](https://github.com/mirror81/clickhouse-monitoring/commit/9b9d2398bba240573de50977a83be313e2ba0f99))
* **cf:** resolve nested standalone path in stub script for monorepo ([#1223](https://github.com/mirror81/clickhouse-monitoring/issues/1223)) ([d1e90d1](https://github.com/mirror81/clickhouse-monitoring/commit/d1e90d1288b70c1bebfe75a5b51d1c3d015d56d4))
* change regex to /\bunion\s+(all\s+)?select\b/i. ([0f15879](https://github.com/mirror81/clickhouse-monitoring/commit/0f15879e33cba3e9743041e9d8b626a8ec48083a))
* **charts:** convert query-duration and query-memory to area charts ([#1264](https://github.com/mirror81/clickhouse-monitoring/issues/1264)) ([54ae62e](https://github.com/mirror81/clickhouse-monitoring/commit/54ae62eda0a969f03582dc74070f1368a210e4ee))
* **charts:** stabilize scroll while lazy charts render ([#1246](https://github.com/mirror81/clickhouse-monitoring/issues/1246)) ([1bcbb97](https://github.com/mirror81/clickhouse-monitoring/commit/1bcbb97a96cfb0d02966556e1d3a52a581c2ce72))
* **charts:** stop dictionary-count 500 + make chart route resilient ([#1276](https://github.com/mirror81/clickhouse-monitoring/issues/1276)) ([a19f3b6](https://github.com/mirror81/clickhouse-monitoring/commit/a19f3b6104b64c911fd61a22d0884f3141fefdbc))
* **charts:** stop lazy charts reloading on scroll-back ([#1383](https://github.com/mirror81/clickhouse-monitoring/issues/1383)) ([5d7c0f2](https://github.com/mirror81/clickhouse-monitoring/commit/5d7c0f2d5db86e1f9f457baedd2b5ed1e41af333))
* **ci:** make component-test green (Recharts mount size + quarantine headless flakes) ([#1250](https://github.com/mirror81/clickhouse-monitoring/issues/1250)) ([8d5cfda](https://github.com/mirror81/clickhouse-monitoring/commit/8d5cfda41506383c145332564b134007c24ed4c8))
* **ci:** pass -R to gh workflow run in release-please ([#1608](https://github.com/mirror81/clickhouse-monitoring/issues/1608)) ([da18863](https://github.com/mirror81/clickhouse-monitoring/commit/da18863b3132467cbd69fb8ab8450c5478ffb258))
* **ci:** quarantine flaky table-client polling test ([#1251](https://github.com/mirror81/clickhouse-monitoring/issues/1251)) ([e604b0a](https://github.com/mirror81/clickhouse-monitoring/commit/e604b0a2f458d1cb1c7192b453ad903b9c850f8c))
* **ci:** stop component-test 30-min hang ([#1247](https://github.com/mirror81/clickhouse-monitoring/issues/1247)) ([ea6e005](https://github.com/mirror81/clickhouse-monitoring/commit/ea6e00507a6e9cb339812d50380f26a18cb631de))
* classify unknown table errors as table_not_found ([#1546](https://github.com/mirror81/clickhouse-monitoring/issues/1546)) ([b0618af](https://github.com/mirror81/clickhouse-monitoring/commit/b0618afc55dad189b35bea0122dd1abbf9f1400a))
* **clerk:** handle signOut error gracefully, prevent uncaught rejection ([#1356](https://github.com/mirror81/clickhouse-monitoring/issues/1356)) ([bcad679](https://github.com/mirror81/clickhouse-monitoring/commit/bcad679e62af106ad0df13d2ee3f5ce5e2f31d67))
* **clickhouse-client:** fix module cache isolation in unit tests ([cadcc24](https://github.com/mirror81/clickhouse-monitoring/commit/cadcc2432404437d5547b17b4de8738860df9d59))
* **clickhouse-client:** fix module cache isolation in unit tests ([bd5881d](https://github.com/mirror81/clickhouse-monitoring/commit/bd5881d318ec18f0c1921a3208625dba0d25060c))
* **clickhouse-client:** harden http status code regex in clickhouse-fetch ([#1578](https://github.com/mirror81/clickhouse-monitoring/issues/1578)) ([0d27e33](https://github.com/mirror81/clickhouse-monitoring/commit/0d27e33811e223c4d5a3e569e3dd1a95f8218530))
* **clickhouse-client:** redact inline credentials from host config debug logs ([#1581](https://github.com/mirror81/clickhouse-monitoring/issues/1581)) ([6d0609b](https://github.com/mirror81/clickhouse-monitoring/commit/6d0609b5a3cbf442730ed2cd2880200810e3ee78))
* **cluster:** address topology review feedback ([#1331](https://github.com/mirror81/clickhouse-monitoring/issues/1331)) ([fc98fcb](https://github.com/mirror81/clickhouse-monitoring/commit/fc98fcb79e543f0215956a3580fb2cbbd9e4dd5b))
* **clusters:** remove redundant breadcrumb and add Suspense to table ([#1269](https://github.com/mirror81/clickhouse-monitoring/issues/1269)) ([1d4ca54](https://github.com/mirror81/clickhouse-monitoring/commit/1d4ca54f10b1e007da3d5454d98a8cd7f1863e01))
* **dashboard-tsr:** accept Clerk session in /api/v1 guard ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1437](https://github.com/mirror81/clickhouse-monitoring/issues/1437)) ([6b894e7](https://github.com/mirror81/clickhouse-monitoring/commit/6b894e71a02839574e5e880cb4f0ea8f1faf1bbb))
* **dashboard-tsr:** add a11y attributes to KpiCard loading skeleton ([#1473](https://github.com/mirror81/clickhouse-monitoring/issues/1473)) ([6ff8d63](https://github.com/mirror81/clickhouse-monitoring/commit/6ff8d6370a1e6ca9f20e4b66101f640d3052e009))
* **dashboard-tsr:** add a11y loading announcement to LazyChartWrapper placeholder ([#1485](https://github.com/mirror81/clickhouse-monitoring/issues/1485)) ([d4b56b9](https://github.com/mirror81/clickhouse-monitoring/commit/d4b56b997cc10a835ffe5156a3b5aaa2c93f1fa6))
* **dashboard-tsr:** add focus-visible ring to explorer tree expand button ([#1458](https://github.com/mirror81/clickhouse-monitoring/issues/1458)) ([88bfda7](https://github.com/mirror81/clickhouse-monitoring/commit/88bfda75a2ff7416ddea1c4a44d7e6a297def59d))
* **dashboard-tsr:** add keyboard a11y to ChartEmpty clickable card ([#1478](https://github.com/mirror81/clickhouse-monitoring/issues/1478)) ([1789061](https://github.com/mirror81/clickhouse-monitoring/commit/17890619984ba0f91cf18d4c337e0d6c701f3fe4))
* **dashboard-tsr:** add keyboard a11y to explorer database cards ([#1481](https://github.com/mirror81/clickhouse-monitoring/issues/1481)) ([0c91dc2](https://github.com/mirror81/clickhouse-monitoring/commit/0c91dc2b8ef23e0155264f03649cbf7488e94424))
* **dashboard-tsr:** add security headers to static pages via _headers ([#1491](https://github.com/mirror81/clickhouse-monitoring/issues/1491)) ([bc516dc](https://github.com/mirror81/clickhouse-monitoring/commit/bc516dc876f34bf00678e1b3e52a16ee6841024f))
* **dashboard-tsr:** add security response headers ([#1487](https://github.com/mirror81/clickhouse-monitoring/issues/1487)) ([0035c84](https://github.com/mirror81/clickhouse-monitoring/commit/0035c8451491c7390264d04d076515edb65718c2))
* **dashboard-tsr:** add SheetTitle to ExplorerSidebar for screen-reader a11y ([#1457](https://github.com/mirror81/clickhouse-monitoring/issues/1457)) ([bc9f76d](https://github.com/mirror81/clickhouse-monitoring/commit/bc9f76d08cf74056788d162f43ef942a95d4fe40))
* **dashboard-tsr:** add SQL validation to browser-connections proxy endpoint ([#1471](https://github.com/mirror81/clickhouse-monitoring/issues/1471)) ([cd9b309](https://github.com/mirror81/clickhouse-monitoring/commit/cd9b309260aab9c3611ca9452ae83737101671dc))
* **dashboard-tsr:** add SQL validation to POST /api/v1/data with queryConfigName ([#1483](https://github.com/mirror81/clickhouse-monitoring/issues/1483)) ([f54fa04](https://github.com/mirror81/clickhouse-monitoring/commit/f54fa0418e5fcb66ba8773e04676d45405747354))
* **dashboard-tsr:** add underline variant to TabsSkeleton to prevent CLS on overview load ([#1460](https://github.com/mirror81/clickhouse-monitoring/issues/1460)) ([7d17fe3](https://github.com/mirror81/clickhouse-monitoring/commit/7d17fe38a846d0fd98b9aed510622fc85734d51c))
* **dashboard-tsr:** address Codex P1 runtime bugs ([#1421](https://github.com/mirror81/clickhouse-monitoring/issues/1421)) ([#1423](https://github.com/mirror81/clickhouse-monitoring/issues/1423)) ([1b8de93](https://github.com/mirror81/clickhouse-monitoring/commit/1b8de93247c47a380d9439a68cf8344d8d213026))
* **dashboard-tsr:** auth=none opens everything; frontend renders, backend enforces ([#1533](https://github.com/mirror81/clickhouse-monitoring/issues/1533)) ([497d474](https://github.com/mirror81/clickhouse-monitoring/commit/497d4745403f3bed64de5f9259021c854a425e43))
* **dashboard-tsr:** auto-reload on stale dynamic-import after deploy ([#1538](https://github.com/mirror81/clickhouse-monitoring/issues/1538)) ([2ee1f31](https://github.com/mirror81/clickhouse-monitoring/commit/2ee1f3146fd00ccc780ad7808fe25d6686b3c89f))
* **dashboard-tsr:** bridge CLICKHOUSE_DATABASE and EVENTS_TABLE_NAME on workers ([#1576](https://github.com/mirror81/clickhouse-monitoring/issues/1576)) ([8096672](https://github.com/mirror81/clickhouse-monitoring/commit/80966727cf779cd2731b375261d7eb0e3e85adef))
* **dashboard-tsr:** collapse root redirect to one edge hop + unblock e2e CI ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([763184e](https://github.com/mirror81/clickhouse-monitoring/commit/763184e3923efca1bffcf570abefd9104ca970f7))
* **dashboard-tsr:** collapse root redirect to single edge hop + unblock e2e CI ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([2674450](https://github.com/mirror81/clickhouse-monitoring/commit/2674450db5ad99ade9342908b73a7604bb02d36f))
* **dashboard-tsr:** convention fixes, stable keys, ai-agent docs sync, regression tests ([#1555](https://github.com/mirror81/clickhouse-monitoring/issues/1555)) ([9c5944d](https://github.com/mirror81/clickhouse-monitoring/commit/9c5944d30d58c4bead7b1772229d4f5845c6bbff))
* **dashboard-tsr:** correct explorer page height to account for shell padding ([#1479](https://github.com/mirror81/clickhouse-monitoring/issues/1479)) ([2fd5802](https://github.com/mirror81/clickhouse-monitoring/commit/2fd5802ee343b37ed44077c88a2f4f0a4fba7cb7))
* **dashboard-tsr:** deploy CHM_CLERK_PUBLIC_READ var (CI patch script) ([#1537](https://github.com/mirror81/clickhouse-monitoring/issues/1537)) ([90d1378](https://github.com/mirror81/clickhouse-monitoring/commit/90d13786d1b5a36995f31bf66625b3dc525a312d))
* **dashboard-tsr:** deterministic cache-bust in clerk-client test ([#1503](https://github.com/mirror81/clickhouse-monitoring/issues/1503)) ([121184f](https://github.com/mirror81/clickhouse-monitoring/commit/121184fc36005ff501184fff0100c79d44d11a31))
* **dashboard-tsr:** drop hardcoded clerk key default, sync env docs ([#1561](https://github.com/mirror81/clickhouse-monitoring/issues/1561)) ([3bb9df9](https://github.com/mirror81/clickhouse-monitoring/commit/3bb9df9148954f4cd2c3bc92efd412f6b5ad44cd))
* **dashboard-tsr:** drop trailing-slash redirect on prerendered routes ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1432](https://github.com/mirror81/clickhouse-monitoring/issues/1432)) ([8a4234e](https://github.com/mirror81/clickhouse-monitoring/commit/8a4234ec8aada5ea53c405837f699cc6a4275cb0))
* **dashboard-tsr:** enforce chart feature perms + port deprecated chart variants ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1445](https://github.com/mirror81/clickhouse-monitoring/issues/1445)) ([07dc70c](https://github.com/mirror81/clickhouse-monitoring/commit/07dc70c44cf963f3f4a1bc54ca5c520a90f0d2ab))
* **dashboard-tsr:** enforce ClickHouse readonly mode in /api/v1/data ([#1476](https://github.com/mirror81/clickhouse-monitoring/issues/1476)) ([54f3af1](https://github.com/mirror81/clickhouse-monitoring/commit/54f3af1cad64de6fc7ae9ebce28c9e5cb556b261))
* **dashboard-tsr:** fix a11y violations in health, dashboard, and menu ([#1588](https://github.com/mirror81/clickhouse-monitoring/issues/1588)) ([5340ce8](https://github.com/mirror81/clickhouse-monitoring/commit/5340ce8b477510c51c28737b1c5123dd73dc70e1))
* **dashboard-tsr:** keep agent menu visible when signed in ([#1453](https://github.com/mirror81/clickhouse-monitoring/issues/1453)) ([5853abc](https://github.com/mirror81/clickhouse-monitoring/commit/5853abca2a276b2c23fb3a7eb8e00a72f08b454a))
* **dashboard-tsr:** lint cleanup, flaky test, and query-config SQL fixes ([#1554](https://github.com/mirror81/clickhouse-monitoring/issues/1554)) ([5ae1c49](https://github.com/mirror81/clickhouse-monitoring/commit/5ae1c49656cef72b7cac0c54cd5cdb8f32fe3675))
* **dashboard-tsr:** listen for swr:revalidate event to refresh TanStack Query cache ([#1579](https://github.com/mirror81/clickhouse-monitoring/issues/1579)) ([7927f18](https://github.com/mirror81/clickhouse-monitoring/commit/7927f18fd6dd831861bb2757c477ff06fb0084c6))
* **dashboard-tsr:** make SSR stub constructable so prerender stops throwing ([#1499](https://github.com/mirror81/clickhouse-monitoring/issues/1499)) ([a220610](https://github.com/mirror81/clickhouse-monitoring/commit/a2206105cd3092dce29a0613f50e887c4e332dd6))
* **dashboard-tsr:** match overview fallback skeleton to KpiCard layout ([#1480](https://github.com/mirror81/clickhouse-monitoring/issues/1480)) ([60af83d](https://github.com/mirror81/clickhouse-monitoring/commit/60af83d87d7dad77a9675ee78ca2a197dd738430))
* **dashboard-tsr:** migrate client env from NEXT_PUBLIC_* to VITE_* ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1435](https://github.com/mirror81/clickhouse-monitoring/issues/1435)) ([a06c591](https://github.com/mirror81/clickhouse-monitoring/commit/a06c59108e20b1265e1553bf4d20333d35c9da3a))
* **dashboard-tsr:** perf + dual-target build fixes ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1430](https://github.com/mirror81/clickhouse-monitoring/issues/1430)) ([6b37fbc](https://github.com/mirror81/clickhouse-monitoring/commit/6b37fbca350630bf49592a93cb44d90d2438a336))
* **dashboard-tsr:** populate client chart-component registry (71 charts) ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1443](https://github.com/mirror81/clickhouse-monitoring/issues/1443)) ([7fcf623](https://github.com/mirror81/clickhouse-monitoring/commit/7fcf623ec7834c57d1fe430baa6820a994c16cfb))
* **dashboard-tsr:** query detail button + collapse charts instead of hiding ([#1497](https://github.com/mirror81/clickhouse-monitoring/issues/1497)) ([15a43d5](https://github.com/mirror81/clickhouse-monitoring/commit/15a43d56219e2205326e7e732ec680e851dbd7ef))
* **dashboard-tsr:** re-export shape-matched TableSkeleton to prevent CLS ([#1474](https://github.com/mirror81/clickhouse-monitoring/issues/1474)) ([80a163b](https://github.com/mirror81/clickhouse-monitoring/commit/80a163bdc07eb7f60433d5f5cb96ff29e3e8ba26))
* **dashboard-tsr:** register all chart modules so charts resolve ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1441](https://github.com/mirror81/clickhouse-monitoring/issues/1441)) ([c42ed90](https://github.com/mirror81/clickhouse-monitoring/commit/c42ed90385456f08ecb141deb2ba62ffa7a15a1f))
* **dashboard-tsr:** register clerkMiddleware + missing explorer configs ([#1496](https://github.com/mirror81/clickhouse-monitoring/issues/1496)) ([6bf699e](https://github.com/mirror81/clickhouse-monitoring/commit/6bf699e056004bfb64b37e7291ad4645e615433e))
* **dashboard-tsr:** remove aria-hidden that suppresses skeleton loading announcements ([#1482](https://github.com/mirror81/clickhouse-monitoring/issues/1482)) ([a1d2af8](https://github.com/mirror81/clickhouse-monitoring/commit/a1d2af8bfc16c6056e487a9d24c6aab71e6515b8))
* **dashboard-tsr:** replace require() Clerk gating with ESM imports ([#1532](https://github.com/mirror81/clickhouse-monitoring/issues/1532)) ([764f8fb](https://github.com/mirror81/clickhouse-monitoring/commit/764f8fb2211b04e585392918e62f718b4b97ce5b))
* **dashboard-tsr:** replace running-queries Suspense fallback with full-page skeleton ([#1467](https://github.com/mirror81/clickhouse-monitoring/issues/1467)) ([f0c3a30](https://github.com/mirror81/clickhouse-monitoring/commit/f0c3a3000e3b9266d8b31f52fd3c4317985e66ca))
* **dashboard-tsr:** restore focus-visible ring on overview tab triggers ([#1461](https://github.com/mirror81/clickhouse-monitoring/issues/1461)) ([5a0639c](https://github.com/mirror81/clickhouse-monitoring/commit/5a0639cd643e0c2944327e85eb917cc51f831d66))
* **dashboard-tsr:** shrink OverviewPageFallback status strip skeleton h-10→h-5 ([#1456](https://github.com/mirror81/clickhouse-monitoring/issues/1456)) ([4781009](https://github.com/mirror81/clickhouse-monitoring/commit/47810096794299ca5abfef54904ab5592103525b))
* **dashboard-tsr:** skip hash-anchor URLs in prerender crawl to unblock Docker build ([#1583](https://github.com/mirror81/clickhouse-monitoring/issues/1583)) ([f001263](https://github.com/mirror81/clickhouse-monitoring/commit/f001263953dbb4c459b4b84de6b2bec1d6273494))
* **dashboard-tsr:** skip prerender for e2e build so the gate actually runs ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([cfa550c](https://github.com/mirror81/clickhouse-monitoring/commit/cfa550cd86eeffc70ca1e80a250701ce3eef8dbf))
* **dashboard-tsr:** stabilize table/chart renders (memoize context + columns, keepPreviousData) ([#1543](https://github.com/mirror81/clickhouse-monitoring/issues/1543)) ([c90b03c](https://github.com/mirror81/clickhouse-monitoring/commit/c90b03c34f0aaf0b9904e8e67cc204f6d782799e))
* **dashboard-tsr:** stop full-page skeleton flash on overview tab switch ([#1454](https://github.com/mirror81/clickhouse-monitoring/issues/1454)) ([02d5292](https://github.com/mirror81/clickhouse-monitoring/commit/02d5292c53d6ebb8d12c69a0df935066f01458e7))
* **dashboard-tsr:** stub browser-only libs in SSR build to fit 3 MiB worker limit ([#1427](https://github.com/mirror81/clickhouse-monitoring/issues/1427)) ([803db26](https://github.com/mirror81/clickhouse-monitoring/commit/803db26e760f71a2885fe081d56c2912e1e4db93))
* **dashboard-tsr:** surface D1 persist failures + bound repoCache + guard conversation routes ([#1511](https://github.com/mirror81/clickhouse-monitoring/issues/1511)) ([305341b](https://github.com/mirror81/clickhouse-monitoring/commit/305341b72eadc9b4d8f63f106ed6741ce9c60176))
* **dashboard-tsr:** type menu-counts test to unblock type-check:test ([#1605](https://github.com/mirror81/clickhouse-monitoring/issues/1605)) ([850162e](https://github.com/mirror81/clickhouse-monitoring/commit/850162e2fe6d56f62731c7adef787ea2bfb39449))
* **dashboard-tsr:** unblock main — chainable SSR stub + readonly string type ([#1488](https://github.com/mirror81/clickhouse-monitoring/issues/1488)) ([4b84603](https://github.com/mirror81/clickhouse-monitoring/commit/4b8460306c2d9362d33c069ccc876ef34dcc4bbc))
* **dashboard-tsr:** unmount collapsed query charts ([#1498](https://github.com/mirror81/clickhouse-monitoring/issues/1498)) ([9584c68](https://github.com/mirror81/clickhouse-monitoring/commit/9584c6846e0d04e1db11ecd8644f2966a1b6f580))
* **dashboard-tsr:** update readonly structural test for string value ([#1490](https://github.com/mirror81/clickhouse-monitoring/issues/1490)) ([941d4e9](https://github.com/mirror81/clickhouse-monitoring/commit/941d4e9004fa3d6ccd34792433db8db5ae159b42))
* **dashboard-tsr:** use 100dvh in explorer to match agents page ([#1463](https://github.com/mirror81/clickhouse-monitoring/issues/1463)) ([9527ef1](https://github.com/mirror81/clickhouse-monitoring/commit/9527ef1097ae7747563baca1680ed786127ab28b))
* **dashboard-tsr:** use grid skeleton for dashboard page loading state ([#1468](https://github.com/mirror81/clickhouse-monitoring/issues/1468)) ([af05aa8](https://github.com/mirror81/clickhouse-monitoring/commit/af05aa837708b4d5a8de3a17558702e684a63947))
* **dashboard-tsr:** use h-96 instead of h-screen for table redirect skeleton ([#1486](https://github.com/mirror81/clickhouse-monitoring/issues/1486)) ([c767498](https://github.com/mirror81/clickhouse-monitoring/commit/c76749879d9b39a2315a46456d2e4aa043bdd69a))
* **dashboard-tsr:** use port 8443 for Tailscale funnel ([#1539](https://github.com/mirror81/clickhouse-monitoring/issues/1539)) ([49a9250](https://github.com/mirror81/clickhouse-monitoring/commit/49a9250ba51c36dfa4e9611bbc2b88733f2f9d9b))
* **dashboard-tsr:** use shared ChartSkeleton/TableSkeleton in page skeletons ([#1470](https://github.com/mirror81/clickhouse-monitoring/issues/1470)) ([bf592c4](https://github.com/mirror81/clickhouse-monitoring/commit/bf592c456eb6d65f70e6b6d530592aacadd0f9d3))
* **dashboard-tsr:** use Skeleton shimmer in KpiCard loading state ([#1459](https://github.com/mirror81/clickhouse-monitoring/issues/1459)) ([f44a9df](https://github.com/mirror81/clickhouse-monitoring/commit/f44a9df4bd58d1df88d9d726abc1e4e7e1b10904))
* **dashboard-tsr:** wire table filterSchema + restore actions feature-auth ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1444](https://github.com/mirror81/clickhouse-monitoring/issues/1444)) ([8d3ca79](https://github.com/mirror81/clickhouse-monitoring/commit/8d3ca79cc11f29ff9a74e0f0bc7a2568c247dee5))
* **dashboard:** improve mobile layout for page header and table cards ([#1384](https://github.com/mirror81/clickhouse-monitoring/issues/1384)) ([da3929f](https://github.com/mirror81/clickhouse-monitoring/commit/da3929f48df4dcbf1ca4dd0e96a637eaf8a6d1e4))
* **dashboard:** keep view state local so toggle clicks work in Cypress ([#1557](https://github.com/mirror81/clickhouse-monitoring/issues/1557)) ([a216552](https://github.com/mirror81/clickhouse-monitoring/commit/a2165524ac528c044e3268fb06fde4319f00888a))
* **dashboard:** restore health-sweep cron after decommission ([#1382](https://github.com/mirror81/clickhouse-monitoring/issues/1382)) ([f8aa745](https://github.com/mirror81/clickhouse-monitoring/commit/f8aa745945cc97e6fa8fa8a7077ee52cd7963969))
* **dashboard:** unblock production deploy (cron over account limit) + shiki theme type ([#1380](https://github.com/mirror81/clickhouse-monitoring/issues/1380)) ([d78024f](https://github.com/mirror81/clickhouse-monitoring/commit/d78024f3c00cbef00914ac0dc42b1a6842e6d883))
* **data-table:** address review feedback on filterable columns ([#1358](https://github.com/mirror81/clickhouse-monitoring/issues/1358)) ([b251e82](https://github.com/mirror81/clickhouse-monitoring/commit/b251e82e8ce13166f2ec366d58338266de615735))
* **data-table:** card review follow-ups (empty-state, hit area, zone dedup) ([#1347](https://github.com/mirror81/clickhouse-monitoring/issues/1347)) ([f8f2e5c](https://github.com/mirror81/clickhouse-monitoring/commit/f8f2e5c20e95572bed9e3c84e3dbba7f503b15b2))
* **data-table:** content-aware column widths, stop header truncation, square table corners ([c7b0fb5](https://github.com/mirror81/clickhouse-monitoring/commit/c7b0fb5bd4e63f8b2932722b3b0ec95425e1ae79))
* **data-table:** move card Sort into toolbar, add density support to cards ([07fc556](https://github.com/mirror81/clickhouse-monitoring/commit/07fc5566ab551c2e72964bddd7000fd66dab0792))
* **data-table:** pass view='table' in component tests for row selection and border assertions ([#1351](https://github.com/mirror81/clickhouse-monitoring/issues/1351)) ([346d2f4](https://github.com/mirror81/clickhouse-monitoring/commit/346d2f4ee90af1a07caaa5cc089f6cdeda2e087b))
* **data-table:** re-render body on table state changes ([172fa51](https://github.com/mirror81/clickhouse-monitoring/commit/172fa51575a0d01bf0c0ba2e566caf3889bffc7e))
* **data-table:** re-render memoized body on row expansion (and all row state) ([#1275](https://github.com/mirror81/clickhouse-monitoring/issues/1275)) ([141a01e](https://github.com/mirror81/clickhouse-monitoring/commit/141a01e9ba356794cd2813d7a25b07069257411b))
* **data-table:** redesign column headers (Cloudflare-style) ([#1361](https://github.com/mirror81/clickhouse-monitoring/issues/1361)) ([4099a7a](https://github.com/mirror81/clickhouse-monitoring/commit/4099a7aae22cf8ed83961eca70ca3d9806949b31))
* **data-table:** render filter chip label as single text node ([#1366](https://github.com/mirror81/clickhouse-monitoring/issues/1366)) ([c2cb51c](https://github.com/mirror81/clickhouse-monitoring/commit/c2cb51c8fb53d34fde882e3d46bcb1fe767157b2))
* **data-table:** replace pill-shaped bar fill with clean full-height background bar ([#1259](https://github.com/mirror81/clickhouse-monitoring/issues/1259)) ([a9f5055](https://github.com/mirror81/clickhouse-monitoring/commit/a9f50558414f6701916c7ac8610e038c1d71821d))
* **data-table:** restore column resize, sort, and header layout ([#1196](https://github.com/mirror81/clickhouse-monitoring/issues/1196)) ([1e07cd1](https://github.com/mirror81/clickhouse-monitoring/commit/1e07cd1a9725197aacf7b8e4cb2bc3345ce8eb00))
* **data-table:** scale heading in compact/dense density modes ([#1183](https://github.com/mirror81/clickhouse-monitoring/issues/1183)) ([51bcdc6](https://github.com/mirror81/clickhouse-monitoring/commit/51bcdc65124533a8b1ef76d84b79e99dd86dfecc))
* **data-table:** sort/resize hit areas + dense BackgroundBar ([#1180](https://github.com/mirror81/clickhouse-monitoring/issues/1180)) ([5c81f37](https://github.com/mirror81/clickhouse-monitoring/commit/5c81f370cf8808298ca8fe23080a623f75c510b3))
* **data-table:** unify query-page toolbar + exclude action column from filters ([#1357](https://github.com/mirror81/clickhouse-monitoring/issues/1357)) ([e666b39](https://github.com/mirror81/clickhouse-monitoring/commit/e666b391f01f76bcf53aed22e9e59f7a00dd57a9))
* **data-table:** use defaultView='table' in queryConfig for component tests ([a8f015b](https://github.com/mirror81/clickhouse-monitoring/commit/a8f015be82aec025856867d7e48f7a022526dd05))
* **deps:** update dependency astro to v6 [security] ([#1372](https://github.com/mirror81/clickhouse-monitoring/issues/1372)) ([b978df0](https://github.com/mirror81/clickhouse-monitoring/commit/b978df096688b7a4251ed3f947c8ec9aa9e6b763))
* **docker:** build dashboard only, exclude standalone astro apps ([#1375](https://github.com/mirror81/clickhouse-monitoring/issues/1375)) ([e668985](https://github.com/mirror81/clickhouse-monitoring/commit/e66898569118774bb93b3d890dac7ef8ececec18))
* **docker:** copy packages/ before bun install for workspace deps ([f4add66](https://github.com/mirror81/clickhouse-monitoring/commit/f4add663c24939bc4e79571fb9afbed82adfe15b))
* **docker:** copy tsconfig.base.json into builder stage ([#1556](https://github.com/mirror81/clickhouse-monitoring/issues/1556)) ([e74c70a](https://github.com/mirror81/clickhouse-monitoring/commit/e74c70a0741bd5992f11a865b1557a6177750530))
* **docker:** healthcheck hits /api/healthz instead of root ([#1299](https://github.com/mirror81/clickhouse-monitoring/issues/1299)) ([e77b0d8](https://github.com/mirror81/clickhouse-monitoring/commit/e77b0d8c6a5e1034e36685bade428e75271f6b45))
* **docs:** add remark-gfm for markdown table rendering in MDX ([#1390](https://github.com/mirror81/clickhouse-monitoring/issues/1390)) ([0d16a26](https://github.com/mirror81/clickhouse-monitoring/commit/0d16a2642d1096ff19a66ff982b39afcd6accedf))
* **e2e:** expand collapsible menu sections before checking sidebar links ([#1568](https://github.com/mirror81/clickhouse-monitoring/issues/1568)) ([cc6cdbd](https://github.com/mirror81/clickhouse-monitoring/commit/cc6cdbd33ea75a7abfedde6659e2a3a5ea23f340))
* **e2e:** green e2e-test and e2e-test-tsr on main ([#1558](https://github.com/mirror81/clickhouse-monitoring/issues/1558)) ([bc6e451](https://github.com/mirror81/clickhouse-monitoring/commit/bc6e451a12883e53fb0fea1741c7281bf7c360e5))
* enable rust build in docker jobs after WASM build removal ([#1552](https://github.com/mirror81/clickhouse-monitoring/issues/1552)) ([6783aab](https://github.com/mirror81/clickhouse-monitoring/commit/6783aab20fec81657ce4b1d093a2e0e70014b188))
* **explorer:** address review comments to optimize useTabVisitTracker ([6269cc2](https://github.com/mirror81/clickhouse-monitoring/commit/6269cc25568d14a040bddf77dfdd117e73773758))
* **explorer:** address review feedback on tab tracking and ddl count ([341262c](https://github.com/mirror81/clickhouse-monitoring/commit/341262cb9a44068802df8f98771dc45e743c6432))
* **explorer:** dedup @codemirror/state to fix SQL editor crash ([#1260](https://github.com/mirror81/clickhouse-monitoring/issues/1260)) ([4186fe7](https://github.com/mirror81/clickhouse-monitoring/commit/4186fe7a2e31fbbc8d234a3769c15a4a27aa39f5))
* **explorer:** preserve selected tab when switching tables in tree ([64e189d](https://github.com/mirror81/clickhouse-monitoring/commit/64e189dc2b4567cc3d47e9d530db7533cff7023e))
* **explorer:** render deep-linked tab and stop 500 on missing ddl queue ([407711e](https://github.com/mirror81/clickhouse-monitoring/commit/407711eb754ad72876eeb852b5332f98da6378bf))
* **explorer:** reseed query tab SQL when selected table changes ([#1262](https://github.com/mirror81/clickhouse-monitoring/issues/1262)) ([6470646](https://github.com/mirror81/clickhouse-monitoring/commit/64706463b614949e8ad6d8088038fc4517215d11))
* **explorer:** resolve dependency graph hydration mismatch and infinite loop ([#1510](https://github.com/mirror81/clickhouse-monitoring/issues/1510)) ([e2d9618](https://github.com/mirror81/clickhouse-monitoring/commit/e2d9618dd1627b62b34c652075f8112f4f21f127))
* **explorer:** share truncateLargeValues across query and preview routes ([#1192](https://github.com/mirror81/clickhouse-monitoring/issues/1192)) ([a6ea0ea](https://github.com/mirror81/clickhouse-monitoring/commit/a6ea0ea0b4d891d3cc029734d8f84163564e2af1))
* **feedback:** render table guidance instructions as markdown ([#1194](https://github.com/mirror81/clickhouse-monitoring/issues/1194)) ([5f9d65c](https://github.com/mirror81/clickhouse-monitoring/commit/5f9d65c22a9dd5dce7f4dd51045d678e16ccebd9))
* **filters:** hide filter bar when empty, keep display options open, normal button sizes ([#1359](https://github.com/mirror81/clickhouse-monitoring/issues/1359)) ([c532096](https://github.com/mirror81/clickhouse-monitoring/commit/c532096fbdff6e45d547c917c37172dca89021ba))
* **filters:** pass resolved queryConfig to fetchData so WHERE clause is preserved ([1a9b738](https://github.com/mirror81/clickhouse-monitoring/commit/1a9b73879540b4b7d17e4988ce6bcf5b720d29d3))
* **filters:** stop full-page re-render when opening Presets menu ([#1360](https://github.com/mirror81/clickhouse-monitoring/issues/1360)) ([5d54fcd](https://github.com/mirror81/clickhouse-monitoring/commit/5d54fcd4190108fe5af74f2f698a58b271fd1d7d))
* green main — prerender crawl crashes and root Dockerfile tsconfig ([#1563](https://github.com/mirror81/clickhouse-monitoring/issues/1563)) ([053fd62](https://github.com/mirror81/clickhouse-monitoring/commit/053fd62dcd91e37cdea6390b9cad7c8333f1e312))
* **logger:** safely guard process.env access for browser and serverless runtimes ([#1589](https://github.com/mirror81/clickhouse-monitoring/issues/1589)) ([36f3b1d](https://github.com/mirror81/clickhouse-monitoring/commit/36f3b1d357e138fecb7b342636f7828eeded8da5))
* **maintenance:** guard PeerDB cache envs and release reruns ([#1215](https://github.com/mirror81/clickhouse-monitoring/issues/1215)) ([0640d3e](https://github.com/mirror81/clickhouse-monitoring/commit/0640d3e0a621430a1edc9ea38ab0915b88cba17d))
* **mcp:** wire CLERK_SECRET_KEY to MCP worker deploys + bound Clerk verify ([#1391](https://github.com/mirror81/clickhouse-monitoring/issues/1391)) ([4c90b02](https://github.com/mirror81/clickhouse-monitoring/commit/4c90b0291914d6d79ffe2d6c37fa4c377ccd31bd))
* **overview:** keep page scrollable to bottom during loading ([#1316](https://github.com/mirror81/clickhouse-monitoring/issues/1316)) ([32a4f31](https://github.com/mirror81/clickhouse-monitoring/commit/32a4f31354beb1b6327bdabc97fb0549ed9df253))
* **overview:** swap tabs without re-flashing the KPI cards ([#1352](https://github.com/mirror81/clickhouse-monitoring/issues/1352)) ([c509a80](https://github.com/mirror81/clickhouse-monitoring/commit/c509a80e2bb041fa1d855b17439c6b80ef459922))
* **peerdb:** correctness fixes + code review P1 fixes ([#1234](https://github.com/mirror81/clickhouse-monitoring/issues/1234)) ([c6a8bc6](https://github.com/mirror81/clickhouse-monitoring/commit/c6a8bc6a7ae7452845dcbdcd1954e429b812c501))
* **peerdb:** normalize log-level casing for tabs, counts, and pills ([#1211](https://github.com/mirror81/clickhouse-monitoring/issues/1211)) ([3911979](https://github.com/mirror81/clickhouse-monitoring/commit/39119792509bda1282a0c1df77e27f145bb336fd))
* **query-tables:** deduplicate shared components and fix filter/sort bugs ([#1336](https://github.com/mirror81/clickhouse-monitoring/issues/1336)) ([3696e9c](https://github.com/mirror81/clickhouse-monitoring/commit/3696e9cb1c3ae77a003fdf1afe27aebb0984cd5b))
* **readonly-tables:** render is_readonly in red (readonly = problem state) ([#1263](https://github.com/mirror81/clickhouse-monitoring/issues/1263)) ([ff54890](https://github.com/mirror81/clickhouse-monitoring/commit/ff5489011f3d995c05843d103134b4a1c4be26cd))
* **refactor:** extract shared query-table components and deduplicate code across 6 files ([#1337](https://github.com/mirror81/clickhouse-monitoring/issues/1337)) ([48d50d9](https://github.com/mirror81/clickhouse-monitoring/commit/48d50d92003e68dca7a8646efa702876ce3e7a39))
* **release:** remove duplicated Git changes and Docker tags from release notes ([#1442](https://github.com/mirror81/clickhouse-monitoring/issues/1442)) ([4810b40](https://github.com/mirror81/clickhouse-monitoring/commit/4810b404f49621c62c7983c8fe53f2d62a93ffbc))
* resolve TSR cutover blockers (hydration, layout, zoom dialog) ([#1527](https://github.com/mirror81/clickhouse-monitoring/issues/1527)) ([fd187ce](https://github.com/mirror81/clickhouse-monitoring/commit/fd187ceb99b5cc289a8a12eb5af80f889fa118a1))
* **rust/ch-json:** prevent normalization of numeric strings with leading zeros ([#1590](https://github.com/mirror81/clickhouse-monitoring/issues/1590)) ([eb9a091](https://github.com/mirror81/clickhouse-monitoring/commit/eb9a091d9ba39dc3204083458caaee84af94a88e))
* **sql-builder:** fix 8 failing test assertions to match implementation ([5ecd8cd](https://github.com/mirror81/clickhouse-monitoring/commit/5ecd8cd2c1606a1eb438ab4021ac32518e5f0890))
* **sql-validator:** catch UNION ALL SELECT injection bypass ([#1475](https://github.com/mirror81/clickhouse-monitoring/issues/1475)) ([0f15879](https://github.com/mirror81/clickhouse-monitoring/commit/0f15879e33cba3e9743041e9d8b626a8ec48083a))
* switch root Dockerfile and docker-compose to dashboard-tsr ([#1548](https://github.com/mirror81/clickhouse-monitoring/issues/1548)) ([03a3c44](https://github.com/mirror81/clickhouse-monitoring/commit/03a3c4461bc49e0d15d4e8b1620b65ed19b95a46))
* table resize, agent UI cleanup, longer agent step budget ([#1181](https://github.com/mirror81/clickhouse-monitoring/issues/1181)) ([e06a8e1](https://github.com/mirror81/clickhouse-monitoring/commit/e06a8e1a86d6898d50ff15cf01d26eb5ee7a9c73))
* **tables:** broken data tab query, large column OOM, and table re-render performance ([#1191](https://github.com/mirror81/clickhouse-monitoring/issues/1191)) ([29736da](https://github.com/mirror81/clickhouse-monitoring/commit/29736da9b817104b4602793159fb5f5a136ecbe2))
* **test:** abort query-config version probe instead of request_timeout ([#1236](https://github.com/mirror81/clickhouse-monitoring/issues/1236)) ([bcadbc6](https://github.com/mirror81/clickhouse-monitoring/commit/bcadbc691f4c383608cbe052c3d69e59cee513d4))
* **test:** await async execute in resolvedModel tests ([3acf93d](https://github.com/mirror81/clickhouse-monitoring/commit/3acf93d99a0f29705ff6af1f65151d1e55850e33))
* **test:** bound query-config probe with a wall-clock race ([#1237](https://github.com/mirror81/clickhouse-monitoring/issues/1237)) ([ba87c98](https://github.com/mirror81/clickhouse-monitoring/commit/ba87c987e6b3cb2f0884418cb766beb93f71e06a))
* **tests:** fix 3 Cypress component test failures ([3ad1018](https://github.com/mirror81/clickhouse-monitoring/commit/3ad1018a68076495b787cb4f60de91b58e12a63c))
* **tests:** green up unit-tests on main ([#1189](https://github.com/mirror81/clickhouse-monitoring/issues/1189)) ([e4050a9](https://github.com/mirror81/clickhouse-monitoring/commit/e4050a9675b6fd4f865f7d5e20740f8598d335f9))
* **test:** stop global mock.module('react'/clerk) pollution in unit suite ([#1281](https://github.com/mirror81/clickhouse-monitoring/issues/1281)) ([e311ce6](https://github.com/mirror81/clickhouse-monitoring/commit/e311ce6c48d1d2d7a148a69b9a19a6db7604cbbf))
* **tests:** update component tests for recent data-table changes ([7a1242d](https://github.com/mirror81/clickhouse-monitoring/commit/7a1242d73e06b0d14b00423ef9d240bd8b8aa38d))
* **topology:** clamp nodes to viewBox after collision avoidance ([36b52b1](https://github.com/mirror81/clickhouse-monitoring/commit/36b52b1dfb8fec5f61087e01ebd05f7efe43306e))
* **topology:** fix node overlap, visibility in dark mode, and text readability ([#1338](https://github.com/mirror81/clickhouse-monitoring/issues/1338)) ([23486ea](https://github.com/mirror81/clickhouse-monitoring/commit/23486ea0354394b8ce0ffb3d3baec45192c71feb))
* **topology:** relax layout, fix black nodes in dark mode ([99a266d](https://github.com/mirror81/clickhouse-monitoring/commit/99a266dc9139b54a174cb0c67c618f449745ecfe))
* **topology:** stop label overlap, enclose keeper labels, move cluster pills to bottom ([#1353](https://github.com/mirror81/clickhouse-monitoring/issues/1353)) ([c745ae4](https://github.com/mirror81/clickhouse-monitoring/commit/c745ae4e5c1d3f183ab9d99902c2f9357cef8de7))
* **ui,data-table,filters:** address CodeRabbit review on PR [#1200](https://github.com/mirror81/clickhouse-monitoring/issues/1200) ([75bf345](https://github.com/mirror81/clickhouse-monitoring/commit/75bf3453b2c98e469fe6970ce9a2d7b4ccbb74e0))
* **ui:** error-page hero icon, redirect skeletons, root 404 ([#1302](https://github.com/mirror81/clickhouse-monitoring/issues/1302)) ([76ffc62](https://github.com/mirror81/clickhouse-monitoring/commit/76ffc629355c9669efe176894d6667ac4acdd03d))
* **ui:** overview scroll-jump, agent menu gating, host badge truncation ([#1289](https://github.com/mirror81/clickhouse-monitoring/issues/1289)) ([05587f5](https://github.com/mirror81/clickhouse-monitoring/commit/05587f59f45cf6c72cca8c48ac07abc836fb6510))
* **ui:** remove redundant padding from insights page root container ([#1268](https://github.com/mirror81/clickhouse-monitoring/issues/1268)) ([5d3ce2a](https://github.com/mirror81/clickhouse-monitoring/commit/5d3ce2ab55bc828749136cc382f9dafafb9e7b5c))
* **ui:** standardize toolbar element heights to h-8 across all filter bar components ([afce135](https://github.com/mirror81/clickhouse-monitoring/commit/afce13540251af99dd87f19dfcbbaf5998735de8))
* **ui:** unify chart-grid and stack spacing to gap-3/gap-4 rhythm ([#1265](https://github.com/mirror81/clickhouse-monitoring/issues/1265)) ([80e5e93](https://github.com/mirror81/clickhouse-monitoring/commit/80e5e939cf5d1fe305e6b660fb69980a70be6358))
* **validate-docker:** bundle @clickhouse/client-common + follow root redirect ([#1604](https://github.com/mirror81/clickhouse-monitoring/issues/1604)) ([6d280d9](https://github.com/mirror81/clickhouse-monitoring/commit/6d280d9d74cc0d56d5779b754c502e6b113965ef))
* **verify-deploy:** degrade ClickHouse-upstream timeouts to warnings ([8b5b16f](https://github.com/mirror81/clickhouse-monitoring/commit/8b5b16f9a5523671f450324292f1da456d0f4300))


### ⚡ Performance

* **build:** optimizePackageImports for webpack production build ([#1298](https://github.com/mirror81/clickhouse-monitoring/issues/1298)) ([59dd101](https://github.com/mirror81/clickhouse-monitoring/commit/59dd101b4cbf5212d14b6d67af085c64a97919cb))
* **charts:** memoize MiniAreaChart and MiniBarChart ([44c955f](https://github.com/mirror81/clickhouse-monitoring/commit/44c955fb1f789960362759c95bef8ea3ac74bc0d))
* **ci:** validate-docker reuses prebuilt amd64 image ([#1245](https://github.com/mirror81/clickhouse-monitoring/issues/1245)) ([c345b61](https://github.com/mirror81/clickhouse-monitoring/commit/c345b61f40acc56f0d42ceec73f6c670dd6501a7))
* **dashboard-tsr:** cache content-hashed assets immutably for lower TTFB ([#1507](https://github.com/mirror81/clickhouse-monitoring/issues/1507)) ([8c26970](https://github.com/mirror81/clickhouse-monitoring/commit/8c269709f8269749013fa4b06b1b8cd972e3b6fc))
* **dashboard-tsr:** combine SSR stubs for xyflow/streamdown/highlight.js/assistant-ui ([#1472](https://github.com/mirror81/clickhouse-monitoring/issues/1472)) ([f7dfc4c](https://github.com/mirror81/clickhouse-monitoring/commit/f7dfc4ce878ce8f6b1786b662bd71243e464ef63))
* **dashboard-tsr:** fix loading CLS drift + cut hidden-tab polling and re-renders ([#1515](https://github.com/mirror81/clickhouse-monitoring/issues/1515)) ([1818e80](https://github.com/mirror81/clickhouse-monitoring/commit/1818e803565134984026f721278ebb3e6232ffaa))
* **dashboard-tsr:** hover-prefetch, lazy-init providers, visibility-guard pollers ([#1544](https://github.com/mirror81/clickhouse-monitoring/issues/1544)) ([ac3baeb](https://github.com/mirror81/clickhouse-monitoring/commit/ac3baeb41d634540c805674a430f5156b4b57cb5))
* **dashboard-tsr:** make loading skeletons static for faster first paint ([#1506](https://github.com/mirror81/clickhouse-monitoring/issues/1506)) ([d627154](https://github.com/mirror81/clickhouse-monitoring/commit/d627154fb286e6967cc70e74724d1006036cc05f))
* **dashboard-tsr:** memoize data-table filter context and handlers ([#1524](https://github.com/mirror81/clickhouse-monitoring/issues/1524)) ([12248d1](https://github.com/mirror81/clickhouse-monitoring/commit/12248d13762a932817c0bb25b7703c7b4b762d30))
* **dashboard-tsr:** optimize menu counts endpoint to use single batched query ([#1591](https://github.com/mirror81/clickhouse-monitoring/issues/1591)) ([dff6ed4](https://github.com/mirror81/clickhouse-monitoring/commit/dff6ed4b531424f969bff5181ad7aa68f2a7715a))
* **dashboard-tsr:** persist query cache + host list to localStorage for instant warm loads ([#1508](https://github.com/mirror81/clickhouse-monitoring/issues/1508)) ([2d31e38](https://github.com/mirror81/clickhouse-monitoring/commit/2d31e38a97f13d78ed571e79a4c5e7f4436148d6))
* **dashboard-tsr:** persist query cache to localStorage for instant repeat loads ([#1505](https://github.com/mirror81/clickhouse-monitoring/issues/1505)) ([ae5b31f](https://github.com/mirror81/clickhouse-monitoring/commit/ae5b31fe09320b2c84e7e7bc72b180182a66eae3))
* **dashboard-tsr:** set query gcTime to 30m for instant back-nav ([#1489](https://github.com/mirror81/clickhouse-monitoring/issues/1489)) ([3413444](https://github.com/mirror81/clickhouse-monitoring/commit/3413444f9b62a94178e60e4d3243f5cb4bc94c02))
* **dashboard-tsr:** stop background polling on hidden tabs and inactive chart tabs ([#1523](https://github.com/mirror81/clickhouse-monitoring/issues/1523)) ([0591e7d](https://github.com/mirror81/clickhouse-monitoring/commit/0591e7d83513191ff0fcdb58f29a06328234e879))
* **dashboard-tsr:** stub @json-render/shadcn + @json-render/react from SSR bundle ([#1477](https://github.com/mirror81/clickhouse-monitoring/issues/1477)) ([76a6cfe](https://github.com/mirror81/clickhouse-monitoring/commit/76a6cfe1c077ab8fc709b0c4660caf2e8f0ab891))
* **dashboard-tsr:** stub assistant-stream out of CF Worker bundle ([#1484](https://github.com/mirror81/clickhouse-monitoring/issues/1484)) ([2f34d4f](https://github.com/mirror81/clickhouse-monitoring/commit/2f34d4fe186b39cc646e59e29eee29247d177116))
* **dashboard-tsr:** stub recharts in SSR worker bundle (~1 MiB reduction) ([#1462](https://github.com/mirror81/clickhouse-monitoring/issues/1462)) ([e719f7e](https://github.com/mirror81/clickhouse-monitoring/commit/e719f7e791d479e1af9a7ddc042f844160a9d25f))
* **dashboard-tsr:** unmount collapsed chart rows to stop background polling ([#1580](https://github.com/mirror81/clickhouse-monitoring/issues/1580)) ([1400632](https://github.com/mirror81/clickhouse-monitoring/commit/14006320758aef09b3485b5d99d4d9dabbda2e3b))
* **data-table:** stabilize useColumnFilters callbacks and memoize hasFilters ([ef7059c](https://github.com/mirror81/clickhouse-monitoring/commit/ef7059c00b3de27f0670e77b484956562e34b801))
* **explorer:** memoize TreeNode and ColumnNode to skip re-renders ([aaa52b4](https://github.com/mirror81/clickhouse-monitoring/commit/aaa52b4b8b8e1845a2b219862c59cd22bacc65d0))
* **notifications:** memoize NotificationItem to skip parent re-renders ([5c898f4](https://github.com/mirror81/clickhouse-monitoring/commit/5c898f419772fe0c70f93a8b68764317487195cb))
* **peerdb:** memoize smoothPath in PdbSparkline and PdbAreaChart ([#1213](https://github.com/mirror81/clickhouse-monitoring/issues/1213)) ([917bb7e](https://github.com/mirror81/clickhouse-monitoring/commit/917bb7e54931c6de4ebe01b7ebcc9485ca5434ba))
* **query-metric-log:** optimize query for Worker limits + surface server errors ([#1324](https://github.com/mirror81/clickhouse-monitoring/issues/1324)) ([c4cf088](https://github.com/mirror81/clickhouse-monitoring/commit/c4cf08895d80de75cbad2e97a93c505596e7fa61))
* **react-compiler:** enable React Compiler and strip redundant manual memoization ([#1216](https://github.com/mirror81/clickhouse-monitoring/issues/1216)) ([8358523](https://github.com/mirror81/clickhouse-monitoring/commit/8358523540689e8273fc3ca346c4f7f75987f9b1))
* **sidebar:** batch menu-count requests into a single endpoint ([#1308](https://github.com/mirror81/clickhouse-monitoring/issues/1308)) ([a62fe4b](https://github.com/mirror81/clickhouse-monitoring/commit/a62fe4bb3644f6064bf9d93faa4d89486c992e7a))
* **tables:** make the `query` pane be able to be rendered ([3dc62ae](https://github.com/mirror81/clickhouse-monitoring/commit/3dc62ae2cd3c79cd98e1d4b429fe38cd782ab90b))


### ♻️ Refactoring

* **agents:** drop hostId prop from InsightCard ([c626795](https://github.com/mirror81/clickhouse-monitoring/commit/c626795bd32b9690faec7febaf94c378ec9783f7))
* **api:** cache headers, parallel queries, and shared validators in dashboard-tsr ([#1526](https://github.com/mirror81/clickhouse-monitoring/issues/1526)) ([208c645](https://github.com/mirror81/clickhouse-monitoring/commit/208c645621f4bae423c898e304c1a24d31d07b4e))
* **cluster:** merge topology into /clusters page, redirect /cluster ([#1335](https://github.com/mirror81/clickhouse-monitoring/issues/1335)) ([d518ad8](https://github.com/mirror81/clickhouse-monitoring/commit/d518ad8c8d05874c23d300dd39ef4d31b871802e))
* **dashboard-tsr:** address CodeRabbit review findings ([#1406](https://github.com/mirror81/clickhouse-monitoring/issues/1406)-[#1413](https://github.com/mirror81/clickhouse-monitoring/issues/1413)) ([#1414](https://github.com/mirror81/clickhouse-monitoring/issues/1414)) ([4033689](https://github.com/mirror81/clickhouse-monitoring/commit/403368968b41d117dff042606ab7ed1222e79a6a))
* **dashboard-tsr:** adopt activateOnEnterOrSpace in chart-empty + expandable-text ([#1495](https://github.com/mirror81/clickhouse-monitoring/issues/1495)) ([3aa6bec](https://github.com/mirror81/clickhouse-monitoring/commit/3aa6bec8854750c819736f35f4a4ae80b25e205c))
* **dashboard-tsr:** dedup components and fix false keeper-leader layout ([#1525](https://github.com/mirror81/clickhouse-monitoring/issues/1525)) ([866a874](https://github.com/mirror81/clickhouse-monitoring/commit/866a8741bdae3547e728ed4870cadf85d8090991))
* **dashboard-tsr:** docs route hygiene, dead hooks, lazy sql-formatter ([#1564](https://github.com/mirror81/clickhouse-monitoring/issues/1564)) ([7cbed3d](https://github.com/mirror81/clickhouse-monitoring/commit/7cbed3d6e10b78a1dd79a76e254b18bd1fb0e655))
* **dashboard-tsr:** extract activateOnEnterOrSpace a11y helper ([#1494](https://github.com/mirror81/clickhouse-monitoring/issues/1494)) ([9b01572](https://github.com/mirror81/clickhouse-monitoring/commit/9b015729db1c65381c4337a34f5b6bd50d1a87c6))
* **dashboard-tsr:** import zod directly instead of the zod/v3 compat shim ([#1521](https://github.com/mirror81/clickhouse-monitoring/issues/1521)) ([6e55851](https://github.com/mirror81/clickhouse-monitoring/commit/6e55851b9f599df7c32e9e54b063902a8cb379d9))
* **dashboard-tsr:** replace last swr usage with tanstack query, drop swr dep ([#1562](https://github.com/mirror81/clickhouse-monitoring/issues/1562)) ([6ccb7f5](https://github.com/mirror81/clickhouse-monitoring/commit/6ccb7f51751bd29e67267c16c9cceea50a70abce))
* **dashboard-tsr:** split + dedup large components for reuse ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1449](https://github.com/mirror81/clickhouse-monitoring/issues/1449)) ([966d96e](https://github.com/mirror81/clickhouse-monitoring/commit/966d96e7dfe50c61490c37888f97707da0a6b4bf))
* **dashboard-tsr:** split the 4 largest faithful-port components ([#1392](https://github.com/mirror81/clickhouse-monitoring/issues/1392)) ([#1434](https://github.com/mirror81/clickhouse-monitoring/issues/1434)) ([34ada17](https://github.com/mirror81/clickhouse-monitoring/commit/34ada17c5cd0f6d74e8e5c033fd894e313953c67))
* **data-table,explain:** extract useTableBehavior hook + 1-col explain settings on mobile ([ee72c58](https://github.com/mirror81/clickhouse-monitoring/commit/ee72c58911f58a13e52632a0aa489a9098483f5f))
* **explorer/tree:** drop hostId from DatabaseNode and TableNode ([defe928](https://github.com/mirror81/clickhouse-monitoring/commit/defe9284f22c0b56bf48f18a33d37392f8c39bcd))
* **explorer:** drop hostId prop drilling from sidebar layer ([d23c565](https://github.com/mirror81/clickhouse-monitoring/commit/d23c565d3b0ed8314b0da5b7a1d5b207c9a0e211))
* **explorer:** drop hostId prop from DependencyGraph ([e25db4e](https://github.com/mirror81/clickhouse-monitoring/commit/e25db4e72e5d662118d7a31fc5fd5db48c784c22))
* **explorer:** pull useHostId() down into DatabaseOverview ([37123d0](https://github.com/mirror81/clickhouse-monitoring/commit/37123d0088443a1da1732071462b548fadeba3e7))
* **filters:** split filter-bar into focused subcomponents ([8e47898](https://github.com/mirror81/clickhouse-monitoring/commit/8e47898a21b5d807a5f2e613e53dcfcafa0eeb6f))
* **mcp:** unify MCP HTTP handler across worker + in-process route ([#1386](https://github.com/mirror81/clickhouse-monitoring/issues/1386)) ([edcb1cd](https://github.com/mirror81/clickhouse-monitoring/commit/edcb1cdcb93420ae8d282bee54efa31aacbbfc9e))
* **monorepo:** add tsconfig.base.json + Turbo pipeline (Phase 0) ([#1219](https://github.com/mirror81/clickhouse-monitoring/issues/1219)) ([841bff8](https://github.com/mirror81/clickhouse-monitoring/commit/841bff8bb19531c8133a71895aa681f7bb099cf2))
* **monorepo:** extract @chm/clickhouse-client + @chm/mcp-server (Phase 4) ([#1230](https://github.com/mirror81/clickhouse-monitoring/issues/1230)) ([9abd2df](https://github.com/mirror81/clickhouse-monitoring/commit/9abd2df6466b183b1ea6925756e2378ae3398e97))
* **monorepo:** extract @chm/logger package (Phase 4a) ([#1228](https://github.com/mirror81/clickhouse-monitoring/issues/1228)) ([30e7db3](https://github.com/mirror81/clickhouse-monitoring/commit/30e7db3178222a42416ae84e38a8f36996d6aefa))
* **monorepo:** extract Tier-1 packages + break HostInfo cycle (Phase 1) ([#1221](https://github.com/mirror81/clickhouse-monitoring/issues/1221)) ([321c4b2](https://github.com/mirror81/clickhouse-monitoring/commit/321c4b2ff97b1a107021241aeafa56d15083abaa))
* **monorepo:** move mcp worker into apps/mcp-worker (Phase 3) ([#1225](https://github.com/mirror81/clickhouse-monitoring/issues/1225)) ([abc4e2e](https://github.com/mirror81/clickhouse-monitoring/commit/abc4e2e2d874a7191d238c80d13f9cb46afa58c9))
* **monorepo:** move web app into apps/web/ (Phase 2) ([#1222](https://github.com/mirror81/clickhouse-monitoring/issues/1222)) ([5ec9ee3](https://github.com/mirror81/clickhouse-monitoring/commit/5ec9ee319674871a5eebcb9e51065506d992e6d8))
* **notifications,dashboard:** more drills + dashboard toolbar mobile ([dd08836](https://github.com/mirror81/clickhouse-monitoring/commit/dd08836c9474dcf697d9802ec57aca2b233e7211))
* **query-page:** drop hostId chain through DynamicChart layers ([ff28b7a](https://github.com/mirror81/clickhouse-monitoring/commit/ff28b7a734feddc8ebcc2acc21e53dd4c1aa57d2))
* **query-page:** drop hostId prop drilling through ChartRowSummary ([3714b2d](https://github.com/mirror81/clickhouse-monitoring/commit/3714b2d3ad1e5f09d230918b67802d8187dd0271))
* **running-queries:** drop hostId prop from RunningQueriesCharts ([073a3ae](https://github.com/mirror81/clickhouse-monitoring/commit/073a3ae207a98631d7b14211bff34e59894b56d1))
* **rust:** unify tools/ into the rust/ Cargo workspace ([#1224](https://github.com/mirror81/clickhouse-monitoring/issues/1224)) ([850cd6b](https://github.com/mirror81/clickhouse-monitoring/commit/850cd6b70f916f0029e2ef9782af1b95ee826b24))
* **ui:** adopt cn() for class composition, memoize filter field map ([672aa5c](https://github.com/mirror81/clickhouse-monitoring/commit/672aa5cb642e96218ee08011d0224763a2ed8184))

## [0.2.8](https://github.com/duyet/clickhouse-monitoring/compare/v0.2.7...v0.2.8) (2026-06-13)


### ✨ Features

* **release:** tiered LLM notes (Copilot→Models→AnyRouter), recap stats, docker pin ([#1582](https://github.com/duyet/clickhouse-monitoring/issues/1582)) ([3009f99](https://github.com/duyet/clickhouse-monitoring/commit/3009f994a9c73f3a018ddae6f148a7a8bce9103b))


### 🐛 Bug Fixes

* add Running Queries and Clusters as top-level sidebar items ([#1569](https://github.com/duyet/clickhouse-monitoring/issues/1569)) ([74fc5eb](https://github.com/duyet/clickhouse-monitoring/commit/74fc5eb6f2dae1a7bfe931cac07d0d57470c7bde))
* **api:** enforce auth on clean/init/pageview endpoints and sanitize error responses ([#1602](https://github.com/duyet/clickhouse-monitoring/issues/1602)) ([9b9d239](https://github.com/duyet/clickhouse-monitoring/commit/9b9d2398bba240573de50977a83be313e2ba0f99))
* **clickhouse-client:** harden http status code regex in clickhouse-fetch ([#1578](https://github.com/duyet/clickhouse-monitoring/issues/1578)) ([0d27e33](https://github.com/duyet/clickhouse-monitoring/commit/0d27e33811e223c4d5a3e569e3dd1a95f8218530))
* **clickhouse-client:** redact inline credentials from host config debug logs ([#1581](https://github.com/duyet/clickhouse-monitoring/issues/1581)) ([6d0609b](https://github.com/duyet/clickhouse-monitoring/commit/6d0609b5a3cbf442730ed2cd2880200810e3ee78))
* **dashboard-tsr:** bridge CLICKHOUSE_DATABASE and EVENTS_TABLE_NAME on workers ([#1576](https://github.com/duyet/clickhouse-monitoring/issues/1576)) ([8096672](https://github.com/duyet/clickhouse-monitoring/commit/80966727cf779cd2731b375261d7eb0e3e85adef))
* **dashboard-tsr:** fix a11y violations in health, dashboard, and menu ([#1588](https://github.com/duyet/clickhouse-monitoring/issues/1588)) ([5340ce8](https://github.com/duyet/clickhouse-monitoring/commit/5340ce8b477510c51c28737b1c5123dd73dc70e1))
* **dashboard-tsr:** listen for swr:revalidate event to refresh TanStack Query cache ([#1579](https://github.com/duyet/clickhouse-monitoring/issues/1579)) ([7927f18](https://github.com/duyet/clickhouse-monitoring/commit/7927f18fd6dd831861bb2757c477ff06fb0084c6))
* **dashboard-tsr:** skip hash-anchor URLs in prerender crawl to unblock Docker build ([#1583](https://github.com/duyet/clickhouse-monitoring/issues/1583)) ([f001263](https://github.com/duyet/clickhouse-monitoring/commit/f001263953dbb4c459b4b84de6b2bec1d6273494))
* **dashboard-tsr:** type menu-counts test to unblock type-check:test ([#1605](https://github.com/duyet/clickhouse-monitoring/issues/1605)) ([850162e](https://github.com/duyet/clickhouse-monitoring/commit/850162e2fe6d56f62731c7adef787ea2bfb39449))
* **e2e:** expand collapsible menu sections before checking sidebar links ([#1568](https://github.com/duyet/clickhouse-monitoring/issues/1568)) ([cc6cdbd](https://github.com/duyet/clickhouse-monitoring/commit/cc6cdbd33ea75a7abfedde6659e2a3a5ea23f340))
* **logger:** safely guard process.env access for browser and serverless runtimes ([#1589](https://github.com/duyet/clickhouse-monitoring/issues/1589)) ([36f3b1d](https://github.com/duyet/clickhouse-monitoring/commit/36f3b1d357e138fecb7b342636f7828eeded8da5))
* **rust/ch-json:** prevent normalization of numeric strings with leading zeros ([#1590](https://github.com/duyet/clickhouse-monitoring/issues/1590)) ([eb9a091](https://github.com/duyet/clickhouse-monitoring/commit/eb9a091d9ba39dc3204083458caaee84af94a88e))
* **validate-docker:** bundle @clickhouse/client-common + follow root redirect ([#1604](https://github.com/duyet/clickhouse-monitoring/issues/1604)) ([6d280d9](https://github.com/duyet/clickhouse-monitoring/commit/6d280d9d74cc0d56d5779b754c502e6b113965ef))


### ⚡ Performance

* **dashboard-tsr:** optimize menu counts endpoint to use single batched query ([#1591](https://github.com/duyet/clickhouse-monitoring/issues/1591)) ([dff6ed4](https://github.com/duyet/clickhouse-monitoring/commit/dff6ed4b531424f969bff5181ad7aa68f2a7715a))
* **dashboard-tsr:** unmount collapsed chart rows to stop background polling ([#1580](https://github.com/duyet/clickhouse-monitoring/issues/1580)) ([1400632](https://github.com/duyet/clickhouse-monitoring/commit/14006320758aef09b3485b5d99d4d9dabbda2e3b))

## [Unreleased] — v0.3 preview

> **v0.3 rebuilds the dashboard on TanStack Start.** Full upgrade steps:
> [Migrate to v0.3](docs/content/migrating/v0-3.mdx) ·
> What's new: [Release notes](docs/content/releases/v0-3.mdx).

### 💥 Breaking Changes

- **Runtime app switched from Next.js to TanStack Start** (`apps/dashboard-tsr`
  replaces `apps/dashboard` as the primary app). Same features, routes, and
  ClickHouse setup.
- **Browser env vars renamed `NEXT_PUBLIC_*` → `VITE_*`** (build-time inlined).
  The old `NEXT_PUBLIC_*` names still work as a compatibility fallback, so the
  rename is recommended but not required.
- **Docker entrypoint changed** from `node server.js` (OpenNext standalone) to
  `node server/index.mjs` (Nitro node-server). Port `3000` and the
  `/api/healthz` healthcheck are unchanged.

### 🔧 Environment Changes

| Old (v0.2) | New (v0.3) | Notes |
|---|---|---|
| `NEXT_PUBLIC_AUTH_PROVIDER` | `VITE_AUTH_PROVIDER` | client; server uses `CHM_AUTH_PROVIDER` |
| `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` | `VITE_CLERK_PUBLISHABLE_KEY` | client, build-time |
| `NEXT_PUBLIC_FEATURE_CONVERSATION_DB` | `VITE_FEATURE_CONVERSATION_DB` | client, build-time |
| `NEXT_PUBLIC_AUTOCOMPLETE_LIMIT` | `VITE_AUTOCOMPLETE_LIMIT` | client, build-time |
| `NEXT_PUBLIC_RUNNING_QUERIES_REFRESH_MS` | `VITE_RUNNING_QUERIES_REFRESH_MS` | client, build-time |
| `CLICKHOUSE_*`, `CHM_*`, `CLERK_SECRET_KEY`, `*_API_KEY` | _unchanged_ | server vars |

New optional vars: `CHM_AUTH_PROVIDER` (`none\|clerk\|proxy`), `CHM_API_KEY_SECRET`,
`CHM_CF_ACCESS_TEAM_DOMAIN` + `CHM_CF_ACCESS_AUD`, `CHM_PROXY_AUTH_SECRET`,
`HEALTH_ALERT_ENABLED` + `HEALTH_ALERT_WEBHOOK_URL`,
`AGENT_CONVERSATION_PERSISTENCE` + `AGENT_CONVERSATION_STORE`.

### 🤖 Migrate with an AI assistant

Paste your config into any AI assistant with the prompt in
[`.github/release-migration-prompt.md`](.github/release-migration-prompt.md)
(also published in every breaking-change GitHub Release and in the
[README](README.md#upgrading-to-v03)).

## [0.2.7](https://github.com/duyet/clickhouse-monitoring/compare/v0.2.6...v0.2.7) (2026-06-13)


### ✨ Features

* add perf-compare script for Win Metrics ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([#1514](https://github.com/duyet/clickhouse-monitoring/issues/1514)) ([faa6972](https://github.com/duyet/clickhouse-monitoring/commit/faa697231f10a44d280ea8188046855a597e9f89))
* **agent:** add conversation storage adapters ([#1517](https://github.com/duyet/clickhouse-monitoring/issues/1517)) ([34ac9d4](https://github.com/duyet/clickhouse-monitoring/commit/34ac9d4b847124c19d31ccae9eea90a56ec469f4))
* **auth:** activate CHM_CLERK_PUBLIC_READ on dash + dash-tsr ([#1536](https://github.com/duyet/clickhouse-monitoring/issues/1536)) ([e9b7e45](https://github.com/duyet/clickhouse-monitoring/commit/e9b7e45d46cce5ce796e23f71d2e9f3d3e4befcd))
* **auth:** read/write permission model + CHM_CLERK_PUBLIC_READ ([#1535](https://github.com/duyet/clickhouse-monitoring/issues/1535)) ([1112238](https://github.com/duyet/clickhouse-monitoring/commit/1112238714d3d3d24ec01757e089c10c3752e477))
* **dashboard-tsr:** BI-style SQL Console + fix explorer tab-switch freeze ([#1531](https://github.com/duyet/clickhouse-monitoring/issues/1531)) ([b42ebb9](https://github.com/duyet/clickhouse-monitoring/commit/b42ebb9be1af587008e531436c941eae9a4e026e))
* **dashboard-tsr:** pluggable auth providers (none|clerk|proxy) + CF Access/proxy + auth docs + v0.3 changelog ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([#1440](https://github.com/duyet/clickhouse-monitoring/issues/1440)) ([4c2a50c](https://github.com/duyet/clickhouse-monitoring/commit/4c2a50c3b6ed892dce862338b753a5eab3e68772))
* **docs:** astro-design-system theme + per-release versioning ([#1529](https://github.com/duyet/clickhouse-monitoring/issues/1529)) ([2552de4](https://github.com/duyet/clickhouse-monitoring/commit/2552de4365481cabd796526ed1e8d1d42b7ca78a))


### 🐛 Bug Fixes

* add missing WASM artifact upload step in CI workflow ([#1553](https://github.com/duyet/clickhouse-monitoring/issues/1553)) ([13fcd92](https://github.com/duyet/clickhouse-monitoring/commit/13fcd928eb426b1bf520317d5a685e01db03f809))
* **agent:** send AnyRouter category in X-AnyRouter-Categories, not the source header ([#1516](https://github.com/duyet/clickhouse-monitoring/issues/1516)) ([20cb0a3](https://github.com/duyet/clickhouse-monitoring/commit/20cb0a39a5d2493ddca163b15e7a5612af7561ea))
* change regex to /\bunion\s+(all\s+)?select\b/i. ([0f15879](https://github.com/duyet/clickhouse-monitoring/commit/0f15879e33cba3e9743041e9d8b626a8ec48083a))
* classify unknown table errors as table_not_found ([#1546](https://github.com/duyet/clickhouse-monitoring/issues/1546)) ([b0618af](https://github.com/duyet/clickhouse-monitoring/commit/b0618afc55dad189b35bea0122dd1abbf9f1400a))
* **dashboard-tsr:** accept Clerk session in /api/v1 guard ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([#1437](https://github.com/duyet/clickhouse-monitoring/issues/1437)) ([6b894e7](https://github.com/duyet/clickhouse-monitoring/commit/6b894e71a02839574e5e880cb4f0ea8f1faf1bbb))
* **dashboard-tsr:** add a11y attributes to KpiCard loading skeleton ([#1473](https://github.com/duyet/clickhouse-monitoring/issues/1473)) ([6ff8d63](https://github.com/duyet/clickhouse-monitoring/commit/6ff8d6370a1e6ca9f20e4b66101f640d3052e009))
* **dashboard-tsr:** add a11y loading announcement to LazyChartWrapper placeholder ([#1485](https://github.com/duyet/clickhouse-monitoring/issues/1485)) ([d4b56b9](https://github.com/duyet/clickhouse-monitoring/commit/d4b56b997cc10a835ffe5156a3b5aaa2c93f1fa6))
* **dashboard-tsr:** add focus-visible ring to explorer tree expand button ([#1458](https://github.com/duyet/clickhouse-monitoring/issues/1458)) ([88bfda7](https://github.com/duyet/clickhouse-monitoring/commit/88bfda75a2ff7416ddea1c4a44d7e6a297def59d))
* **dashboard-tsr:** add keyboard a11y to ChartEmpty clickable card ([#1478](https://github.com/duyet/clickhouse-monitoring/issues/1478)) ([1789061](https://github.com/duyet/clickhouse-monitoring/commit/17890619984ba0f91cf18d4c337e0d6c701f3fe4))
* **dashboard-tsr:** add keyboard a11y to explorer database cards ([#1481](https://github.com/duyet/clickhouse-monitoring/issues/1481)) ([0c91dc2](https://github.com/duyet/clickhouse-monitoring/commit/0c91dc2b8ef23e0155264f03649cbf7488e94424))
* **dashboard-tsr:** add security headers to static pages via _headers ([#1491](https://github.com/duyet/clickhouse-monitoring/issues/1491)) ([bc516dc](https://github.com/duyet/clickhouse-monitoring/commit/bc516dc876f34bf00678e1b3e52a16ee6841024f))
* **dashboard-tsr:** add security response headers ([#1487](https://github.com/duyet/clickhouse-monitoring/issues/1487)) ([0035c84](https://github.com/duyet/clickhouse-monitoring/commit/0035c8451491c7390264d04d076515edb65718c2))
* **dashboard-tsr:** add SheetTitle to ExplorerSidebar for screen-reader a11y ([#1457](https://github.com/duyet/clickhouse-monitoring/issues/1457)) ([bc9f76d](https://github.com/duyet/clickhouse-monitoring/commit/bc9f76d08cf74056788d162f43ef942a95d4fe40))
* **dashboard-tsr:** add SQL validation to browser-connections proxy endpoint ([#1471](https://github.com/duyet/clickhouse-monitoring/issues/1471)) ([cd9b309](https://github.com/duyet/clickhouse-monitoring/commit/cd9b309260aab9c3611ca9452ae83737101671dc))
* **dashboard-tsr:** add SQL validation to POST /api/v1/data with queryConfigName ([#1483](https://github.com/duyet/clickhouse-monitoring/issues/1483)) ([f54fa04](https://github.com/duyet/clickhouse-monitoring/commit/f54fa0418e5fcb66ba8773e04676d45405747354))
* **dashboard-tsr:** add underline variant to TabsSkeleton to prevent CLS on overview load ([#1460](https://github.com/duyet/clickhouse-monitoring/issues/1460)) ([7d17fe3](https://github.com/duyet/clickhouse-monitoring/commit/7d17fe38a846d0fd98b9aed510622fc85734d51c))
* **dashboard-tsr:** auth=none opens everything; frontend renders, backend enforces ([#1533](https://github.com/duyet/clickhouse-monitoring/issues/1533)) ([497d474](https://github.com/duyet/clickhouse-monitoring/commit/497d4745403f3bed64de5f9259021c854a425e43))
* **dashboard-tsr:** auto-reload on stale dynamic-import after deploy ([#1538](https://github.com/duyet/clickhouse-monitoring/issues/1538)) ([2ee1f31](https://github.com/duyet/clickhouse-monitoring/commit/2ee1f3146fd00ccc780ad7808fe25d6686b3c89f))
* **dashboard-tsr:** collapse root redirect to one edge hop + unblock e2e CI ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([763184e](https://github.com/duyet/clickhouse-monitoring/commit/763184e3923efca1bffcf570abefd9104ca970f7))
* **dashboard-tsr:** collapse root redirect to single edge hop + unblock e2e CI ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([2674450](https://github.com/duyet/clickhouse-monitoring/commit/2674450db5ad99ade9342908b73a7604bb02d36f))
* **dashboard-tsr:** convention fixes, stable keys, ai-agent docs sync, regression tests ([#1555](https://github.com/duyet/clickhouse-monitoring/issues/1555)) ([9c5944d](https://github.com/duyet/clickhouse-monitoring/commit/9c5944d30d58c4bead7b1772229d4f5845c6bbff))
* **dashboard-tsr:** correct explorer page height to account for shell padding ([#1479](https://github.com/duyet/clickhouse-monitoring/issues/1479)) ([2fd5802](https://github.com/duyet/clickhouse-monitoring/commit/2fd5802ee343b37ed44077c88a2f4f0a4fba7cb7))
* **dashboard-tsr:** deploy CHM_CLERK_PUBLIC_READ var (CI patch script) ([#1537](https://github.com/duyet/clickhouse-monitoring/issues/1537)) ([90d1378](https://github.com/duyet/clickhouse-monitoring/commit/90d13786d1b5a36995f31bf66625b3dc525a312d))
* **dashboard-tsr:** deterministic cache-bust in clerk-client test ([#1503](https://github.com/duyet/clickhouse-monitoring/issues/1503)) ([121184f](https://github.com/duyet/clickhouse-monitoring/commit/121184fc36005ff501184fff0100c79d44d11a31))
* **dashboard-tsr:** drop hardcoded clerk key default, sync env docs ([#1561](https://github.com/duyet/clickhouse-monitoring/issues/1561)) ([3bb9df9](https://github.com/duyet/clickhouse-monitoring/commit/3bb9df9148954f4cd2c3bc92efd412f6b5ad44cd))
* **dashboard-tsr:** enforce chart feature perms + port deprecated chart variants ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([#1445](https://github.com/duyet/clickhouse-monitoring/issues/1445)) ([07dc70c](https://github.com/duyet/clickhouse-monitoring/commit/07dc70c44cf963f3f4a1bc54ca5c520a90f0d2ab))
* **dashboard-tsr:** enforce ClickHouse readonly mode in /api/v1/data ([#1476](https://github.com/duyet/clickhouse-monitoring/issues/1476)) ([54f3af1](https://github.com/duyet/clickhouse-monitoring/commit/54f3af1cad64de6fc7ae9ebce28c9e5cb556b261))
* **dashboard-tsr:** keep agent menu visible when signed in ([#1453](https://github.com/duyet/clickhouse-monitoring/issues/1453)) ([5853abc](https://github.com/duyet/clickhouse-monitoring/commit/5853abca2a276b2c23fb3a7eb8e00a72f08b454a))
* **dashboard-tsr:** lint cleanup, flaky test, and query-config SQL fixes ([#1554](https://github.com/duyet/clickhouse-monitoring/issues/1554)) ([5ae1c49](https://github.com/duyet/clickhouse-monitoring/commit/5ae1c49656cef72b7cac0c54cd5cdb8f32fe3675))
* **dashboard-tsr:** make SSR stub constructable so prerender stops throwing ([#1499](https://github.com/duyet/clickhouse-monitoring/issues/1499)) ([a220610](https://github.com/duyet/clickhouse-monitoring/commit/a2206105cd3092dce29a0613f50e887c4e332dd6))
* **dashboard-tsr:** match overview fallback skeleton to KpiCard layout ([#1480](https://github.com/duyet/clickhouse-monitoring/issues/1480)) ([60af83d](https://github.com/duyet/clickhouse-monitoring/commit/60af83d87d7dad77a9675ee78ca2a197dd738430))
* **dashboard-tsr:** populate client chart-component registry (71 charts) ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([#1443](https://github.com/duyet/clickhouse-monitoring/issues/1443)) ([7fcf623](https://github.com/duyet/clickhouse-monitoring/commit/7fcf623ec7834c57d1fe430baa6820a994c16cfb))
* **dashboard-tsr:** query detail button + collapse charts instead of hiding ([#1497](https://github.com/duyet/clickhouse-monitoring/issues/1497)) ([15a43d5](https://github.com/duyet/clickhouse-monitoring/commit/15a43d56219e2205326e7e732ec680e851dbd7ef))
* **dashboard-tsr:** re-export shape-matched TableSkeleton to prevent CLS ([#1474](https://github.com/duyet/clickhouse-monitoring/issues/1474)) ([80a163b](https://github.com/duyet/clickhouse-monitoring/commit/80a163bdc07eb7f60433d5f5cb96ff29e3e8ba26))
* **dashboard-tsr:** register all chart modules so charts resolve ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([#1441](https://github.com/duyet/clickhouse-monitoring/issues/1441)) ([c42ed90](https://github.com/duyet/clickhouse-monitoring/commit/c42ed90385456f08ecb141deb2ba62ffa7a15a1f))
* **dashboard-tsr:** register clerkMiddleware + missing explorer configs ([#1496](https://github.com/duyet/clickhouse-monitoring/issues/1496)) ([6bf699e](https://github.com/duyet/clickhouse-monitoring/commit/6bf699e056004bfb64b37e7291ad4645e615433e))
* **dashboard-tsr:** remove aria-hidden that suppresses skeleton loading announcements ([#1482](https://github.com/duyet/clickhouse-monitoring/issues/1482)) ([a1d2af8](https://github.com/duyet/clickhouse-monitoring/commit/a1d2af8bfc16c6056e487a9d24c6aab71e6515b8))
* **dashboard-tsr:** replace require() Clerk gating with ESM imports ([#1532](https://github.com/duyet/clickhouse-monitoring/issues/1532)) ([764f8fb](https://github.com/duyet/clickhouse-monitoring/commit/764f8fb2211b04e585392918e62f718b4b97ce5b))
* **dashboard-tsr:** replace running-queries Suspense fallback with full-page skeleton ([#1467](https://github.com/duyet/clickhouse-monitoring/issues/1467)) ([f0c3a30](https://github.com/duyet/clickhouse-monitoring/commit/f0c3a3000e3b9266d8b31f52fd3c4317985e66ca))
* **dashboard-tsr:** restore focus-visible ring on overview tab triggers ([#1461](https://github.com/duyet/clickhouse-monitoring/issues/1461)) ([5a0639c](https://github.com/duyet/clickhouse-monitoring/commit/5a0639cd643e0c2944327e85eb917cc51f831d66))
* **dashboard-tsr:** shrink OverviewPageFallback status strip skeleton h-10→h-5 ([#1456](https://github.com/duyet/clickhouse-monitoring/issues/1456)) ([4781009](https://github.com/duyet/clickhouse-monitoring/commit/47810096794299ca5abfef54904ab5592103525b))
* **dashboard-tsr:** skip prerender for e2e build so the gate actually runs ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([cfa550c](https://github.com/duyet/clickhouse-monitoring/commit/cfa550cd86eeffc70ca1e80a250701ce3eef8dbf))
* **dashboard-tsr:** stabilize table/chart renders (memoize context + columns, keepPreviousData) ([#1543](https://github.com/duyet/clickhouse-monitoring/issues/1543)) ([c90b03c](https://github.com/duyet/clickhouse-monitoring/commit/c90b03c34f0aaf0b9904e8e67cc204f6d782799e))
* **dashboard-tsr:** stop full-page skeleton flash on overview tab switch ([#1454](https://github.com/duyet/clickhouse-monitoring/issues/1454)) ([02d5292](https://github.com/duyet/clickhouse-monitoring/commit/02d5292c53d6ebb8d12c69a0df935066f01458e7))
* **dashboard-tsr:** surface D1 persist failures + bound repoCache + guard conversation routes ([#1511](https://github.com/duyet/clickhouse-monitoring/issues/1511)) ([305341b](https://github.com/duyet/clickhouse-monitoring/commit/305341b72eadc9b4d8f63f106ed6741ce9c60176))
* **dashboard-tsr:** unblock main — chainable SSR stub + readonly string type ([#1488](https://github.com/duyet/clickhouse-monitoring/issues/1488)) ([4b84603](https://github.com/duyet/clickhouse-monitoring/commit/4b8460306c2d9362d33c069ccc876ef34dcc4bbc))
* **dashboard-tsr:** unmount collapsed query charts ([#1498](https://github.com/duyet/clickhouse-monitoring/issues/1498)) ([9584c68](https://github.com/duyet/clickhouse-monitoring/commit/9584c6846e0d04e1db11ecd8644f2966a1b6f580))
* **dashboard-tsr:** update readonly structural test for string value ([#1490](https://github.com/duyet/clickhouse-monitoring/issues/1490)) ([941d4e9](https://github.com/duyet/clickhouse-monitoring/commit/941d4e9004fa3d6ccd34792433db8db5ae159b42))
* **dashboard-tsr:** use 100dvh in explorer to match agents page ([#1463](https://github.com/duyet/clickhouse-monitoring/issues/1463)) ([9527ef1](https://github.com/duyet/clickhouse-monitoring/commit/9527ef1097ae7747563baca1680ed786127ab28b))
* **dashboard-tsr:** use grid skeleton for dashboard page loading state ([#1468](https://github.com/duyet/clickhouse-monitoring/issues/1468)) ([af05aa8](https://github.com/duyet/clickhouse-monitoring/commit/af05aa837708b4d5a8de3a17558702e684a63947))
* **dashboard-tsr:** use h-96 instead of h-screen for table redirect skeleton ([#1486](https://github.com/duyet/clickhouse-monitoring/issues/1486)) ([c767498](https://github.com/duyet/clickhouse-monitoring/commit/c76749879d9b39a2315a46456d2e4aa043bdd69a))
* **dashboard-tsr:** use port 8443 for Tailscale funnel ([#1539](https://github.com/duyet/clickhouse-monitoring/issues/1539)) ([49a9250](https://github.com/duyet/clickhouse-monitoring/commit/49a9250ba51c36dfa4e9611bbc2b88733f2f9d9b))
* **dashboard-tsr:** use shared ChartSkeleton/TableSkeleton in page skeletons ([#1470](https://github.com/duyet/clickhouse-monitoring/issues/1470)) ([bf592c4](https://github.com/duyet/clickhouse-monitoring/commit/bf592c456eb6d65f70e6b6d530592aacadd0f9d3))
* **dashboard-tsr:** use Skeleton shimmer in KpiCard loading state ([#1459](https://github.com/duyet/clickhouse-monitoring/issues/1459)) ([f44a9df](https://github.com/duyet/clickhouse-monitoring/commit/f44a9df4bd58d1df88d9d726abc1e4e7e1b10904))
* **dashboard-tsr:** wire table filterSchema + restore actions feature-auth ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([#1444](https://github.com/duyet/clickhouse-monitoring/issues/1444)) ([8d3ca79](https://github.com/duyet/clickhouse-monitoring/commit/8d3ca79cc11f29ff9a74e0f0bc7a2568c247dee5))
* **dashboard:** keep view state local so toggle clicks work in Cypress ([#1557](https://github.com/duyet/clickhouse-monitoring/issues/1557)) ([a216552](https://github.com/duyet/clickhouse-monitoring/commit/a2165524ac528c044e3268fb06fde4319f00888a))
* **docker:** copy tsconfig.base.json into builder stage ([#1556](https://github.com/duyet/clickhouse-monitoring/issues/1556)) ([e74c70a](https://github.com/duyet/clickhouse-monitoring/commit/e74c70a0741bd5992f11a865b1557a6177750530))
* **e2e:** green e2e-test and e2e-test-tsr on main ([#1558](https://github.com/duyet/clickhouse-monitoring/issues/1558)) ([bc6e451](https://github.com/duyet/clickhouse-monitoring/commit/bc6e451a12883e53fb0fea1741c7281bf7c360e5))
* enable rust build in docker jobs after WASM build removal ([#1552](https://github.com/duyet/clickhouse-monitoring/issues/1552)) ([6783aab](https://github.com/duyet/clickhouse-monitoring/commit/6783aab20fec81657ce4b1d093a2e0e70014b188))
* **explorer:** resolve dependency graph hydration mismatch and infinite loop ([#1510](https://github.com/duyet/clickhouse-monitoring/issues/1510)) ([e2d9618](https://github.com/duyet/clickhouse-monitoring/commit/e2d9618dd1627b62b34c652075f8112f4f21f127))
* green main — prerender crawl crashes and root Dockerfile tsconfig ([#1563](https://github.com/duyet/clickhouse-monitoring/issues/1563)) ([053fd62](https://github.com/duyet/clickhouse-monitoring/commit/053fd62dcd91e37cdea6390b9cad7c8333f1e312))
* **release:** remove duplicated Git changes and Docker tags from release notes ([#1442](https://github.com/duyet/clickhouse-monitoring/issues/1442)) ([4810b40](https://github.com/duyet/clickhouse-monitoring/commit/4810b404f49621c62c7983c8fe53f2d62a93ffbc))
* resolve TSR cutover blockers (hydration, layout, zoom dialog) ([#1527](https://github.com/duyet/clickhouse-monitoring/issues/1527)) ([fd187ce](https://github.com/duyet/clickhouse-monitoring/commit/fd187ceb99b5cc289a8a12eb5af80f889fa118a1))
* **sql-validator:** catch UNION ALL SELECT injection bypass ([#1475](https://github.com/duyet/clickhouse-monitoring/issues/1475)) ([0f15879](https://github.com/duyet/clickhouse-monitoring/commit/0f15879e33cba3e9743041e9d8b626a8ec48083a))
* switch root Dockerfile and docker-compose to dashboard-tsr ([#1548](https://github.com/duyet/clickhouse-monitoring/issues/1548)) ([03a3c44](https://github.com/duyet/clickhouse-monitoring/commit/03a3c4461bc49e0d15d4e8b1620b65ed19b95a46))
* **verify-deploy:** degrade ClickHouse-upstream timeouts to warnings ([8b5b16f](https://github.com/duyet/clickhouse-monitoring/commit/8b5b16f9a5523671f450324292f1da456d0f4300))


### ⚡ Performance

* **dashboard-tsr:** cache content-hashed assets immutably for lower TTFB ([#1507](https://github.com/duyet/clickhouse-monitoring/issues/1507)) ([8c26970](https://github.com/duyet/clickhouse-monitoring/commit/8c269709f8269749013fa4b06b1b8cd972e3b6fc))
* **dashboard-tsr:** combine SSR stubs for xyflow/streamdown/highlight.js/assistant-ui ([#1472](https://github.com/duyet/clickhouse-monitoring/issues/1472)) ([f7dfc4c](https://github.com/duyet/clickhouse-monitoring/commit/f7dfc4ce878ce8f6b1786b662bd71243e464ef63))
* **dashboard-tsr:** fix loading CLS drift + cut hidden-tab polling and re-renders ([#1515](https://github.com/duyet/clickhouse-monitoring/issues/1515)) ([1818e80](https://github.com/duyet/clickhouse-monitoring/commit/1818e803565134984026f721278ebb3e6232ffaa))
* **dashboard-tsr:** hover-prefetch, lazy-init providers, visibility-guard pollers ([#1544](https://github.com/duyet/clickhouse-monitoring/issues/1544)) ([ac3baeb](https://github.com/duyet/clickhouse-monitoring/commit/ac3baeb41d634540c805674a430f5156b4b57cb5))
* **dashboard-tsr:** make loading skeletons static for faster first paint ([#1506](https://github.com/duyet/clickhouse-monitoring/issues/1506)) ([d627154](https://github.com/duyet/clickhouse-monitoring/commit/d627154fb286e6967cc70e74724d1006036cc05f))
* **dashboard-tsr:** memoize data-table filter context and handlers ([#1524](https://github.com/duyet/clickhouse-monitoring/issues/1524)) ([12248d1](https://github.com/duyet/clickhouse-monitoring/commit/12248d13762a932817c0bb25b7703c7b4b762d30))
* **dashboard-tsr:** persist query cache + host list to localStorage for instant warm loads ([#1508](https://github.com/duyet/clickhouse-monitoring/issues/1508)) ([2d31e38](https://github.com/duyet/clickhouse-monitoring/commit/2d31e38a97f13d78ed571e79a4c5e7f4436148d6))
* **dashboard-tsr:** persist query cache to localStorage for instant repeat loads ([#1505](https://github.com/duyet/clickhouse-monitoring/issues/1505)) ([ae5b31f](https://github.com/duyet/clickhouse-monitoring/commit/ae5b31fe09320b2c84e7e7bc72b180182a66eae3))
* **dashboard-tsr:** set query gcTime to 30m for instant back-nav ([#1489](https://github.com/duyet/clickhouse-monitoring/issues/1489)) ([3413444](https://github.com/duyet/clickhouse-monitoring/commit/3413444f9b62a94178e60e4d3243f5cb4bc94c02))
* **dashboard-tsr:** stop background polling on hidden tabs and inactive chart tabs ([#1523](https://github.com/duyet/clickhouse-monitoring/issues/1523)) ([0591e7d](https://github.com/duyet/clickhouse-monitoring/commit/0591e7d83513191ff0fcdb58f29a06328234e879))
* **dashboard-tsr:** stub @json-render/shadcn + @json-render/react from SSR bundle ([#1477](https://github.com/duyet/clickhouse-monitoring/issues/1477)) ([76a6cfe](https://github.com/duyet/clickhouse-monitoring/commit/76a6cfe1c077ab8fc709b0c4660caf2e8f0ab891))
* **dashboard-tsr:** stub assistant-stream out of CF Worker bundle ([#1484](https://github.com/duyet/clickhouse-monitoring/issues/1484)) ([2f34d4f](https://github.com/duyet/clickhouse-monitoring/commit/2f34d4fe186b39cc646e59e29eee29247d177116))
* **dashboard-tsr:** stub recharts in SSR worker bundle (~1 MiB reduction) ([#1462](https://github.com/duyet/clickhouse-monitoring/issues/1462)) ([e719f7e](https://github.com/duyet/clickhouse-monitoring/commit/e719f7e791d479e1af9a7ddc042f844160a9d25f))


### ♻️ Refactoring

* **api:** cache headers, parallel queries, and shared validators in dashboard-tsr ([#1526](https://github.com/duyet/clickhouse-monitoring/issues/1526)) ([208c645](https://github.com/duyet/clickhouse-monitoring/commit/208c645621f4bae423c898e304c1a24d31d07b4e))
* **dashboard-tsr:** adopt activateOnEnterOrSpace in chart-empty + expandable-text ([#1495](https://github.com/duyet/clickhouse-monitoring/issues/1495)) ([3aa6bec](https://github.com/duyet/clickhouse-monitoring/commit/3aa6bec8854750c819736f35f4a4ae80b25e205c))
* **dashboard-tsr:** dedup components and fix false keeper-leader layout ([#1525](https://github.com/duyet/clickhouse-monitoring/issues/1525)) ([866a874](https://github.com/duyet/clickhouse-monitoring/commit/866a8741bdae3547e728ed4870cadf85d8090991))
* **dashboard-tsr:** docs route hygiene, dead hooks, lazy sql-formatter ([#1564](https://github.com/duyet/clickhouse-monitoring/issues/1564)) ([7cbed3d](https://github.com/duyet/clickhouse-monitoring/commit/7cbed3d6e10b78a1dd79a76e254b18bd1fb0e655))
* **dashboard-tsr:** extract activateOnEnterOrSpace a11y helper ([#1494](https://github.com/duyet/clickhouse-monitoring/issues/1494)) ([9b01572](https://github.com/duyet/clickhouse-monitoring/commit/9b015729db1c65381c4337a34f5b6bd50d1a87c6))
* **dashboard-tsr:** import zod directly instead of the zod/v3 compat shim ([#1521](https://github.com/duyet/clickhouse-monitoring/issues/1521)) ([6e55851](https://github.com/duyet/clickhouse-monitoring/commit/6e55851b9f599df7c32e9e54b063902a8cb379d9))
* **dashboard-tsr:** replace last swr usage with tanstack query, drop swr dep ([#1562](https://github.com/duyet/clickhouse-monitoring/issues/1562)) ([6ccb7f5](https://github.com/duyet/clickhouse-monitoring/commit/6ccb7f51751bd29e67267c16c9cceea50a70abce))
* **dashboard-tsr:** split + dedup large components for reuse ([#1392](https://github.com/duyet/clickhouse-monitoring/issues/1392)) ([#1449](https://github.com/duyet/clickhouse-monitoring/issues/1449)) ([966d96e](https://github.com/duyet/clickhouse-monitoring/commit/966d96e7dfe50c61490c37888f97707da0a6b4bf))

## [0.2.0] - 2026-01-08

### 🏗️ Major Architecture Changes

#### Static Site + SWR Migration
- **Migrated from SSR/dynamic routes to fully static site with client-side API routes**
  - Changed routing from `/[host]/overview` to `/overview?host=0` for better CDN caching
  - All pages are now static pre-rendered and served from edge
  - Client-side data fetching with SWR for real-time data updates
  - Benefits: Faster initial page load, better CDN distribution, simpler deployment

- **Data Fetching Pattern Overhaul**
  - Centralized data fetching through `/api/v1/*` API routes
  - All client components now use SWR hooks (`useChartData`, `useTableData`)
  - `fetchData()` now requires explicit `hostId` parameter (breaking change)
  - Introduced `useHostId()` hook to extract host from query parameters
  - Enables independent data refresh on host switching without full page reload

#### Framework & Build Updates
- **Next.js 15 with React 19** and Turbopack
- **Migrated to Bun** as the primary package manager
  - Better performance and compatibility with modern JavaScript ecosystem
  - Replaced PNPM with Bun (`bun install`, `bun run dev`, etc.)
- **Biome** for code formatting and linting (replacing ESLint/Prettier)
- **Bun test runner** replacing Jest for unit tests
  - Faster test execution and better Node.js compatibility
  - Note: Jest was experiencing hanging issues - Bun provides a stable alternative

#### Cloudflare Workers Deployment
- **Full support for Cloudflare Workers deployment**
  - Uses OpenNextJS for Next.js compatibility
  - API routes run on Workers using Fetch API
  - Hybrid static + API architecture
  - Deploy with: `bun run cf:deploy`
- **Enhanced CI/CD with Docker tagging strategy**
  - Release workflows with automatic Docker image versioning
  - Cloudflare deployment summaries in CI output

### ✨ New Features

#### UI/UX Enhancements
- **User Settings Modal**: Timezone and theme management per user
- **Settings Page**: Column ordering with drag-and-drop, context-aware help
- **Dark Mode Improvements**: Fixed ClickHouse logo visibility in dark mode
- **Command Palette**: Keyboard shortcuts for navigation
- **Readonly Tables Warning**: Indicator for replica tables in cluster overview

#### Data Explorer & Analytics
- **Page Views Analytics**: 4 new charts for usage insights (browsers, devices, pages, referrers)
- **Part Info Page**: Detailed information about ClickHouse table parts
- **Improved Table Validation**: Graceful handling of optional system tables (backup_log, error_log, zookeeper)

#### Developer Tools
- **Enhanced Query EXPLAIN**: Better visualization and context
- **Query Kill Functionality**: Kill long-running queries from UI
- **Zookeeper Explorer**: Monitor cluster coordination

### 🚀 Performance & Infrastructure

#### CDN & Caching
- **Static site architecture** enables aggressive CDN caching at edge
- **Query parameters routing** improves cache hit rates
- **Cloudflare Workers deployment** pre-renders static pages at edge
- **Supports multiple ClickHouse hosts** without cache invalidation

#### Database Query Optimization
- **Version-aware queries** using chronological `sql` arrays
  - Handle ClickHouse schema changes across versions (v23.8, v24.1, etc.)
  - Graceful degradation for missing columns/tables
- **Table validation system** with 5-minute caching
  - Prevents errors on optional tables
  - User-friendly error messages

#### Chart & Visualization
- **30+ metric charts** across all pages
- **Replaced donut charts with progress bars** for better readability
- **Heat maps** for visual performance analysis
- **Graceful error handling** during SWR revalidation preserves user experience

### 🛠️ Development & Testing

#### Testing Infrastructure
- **Cypress component tests** for UI validation
- **Cypress E2E tests** for user workflows
- **Bun test runner** for unit and integration tests
  - `bun run test` - Run all tests with coverage
  - `bun run test:unit` - Unit tests only
  - `bun run test:query-config` - ClickHouse query config validation
- **Query Config Validation**: Automated testing against multiple ClickHouse versions

#### Code Quality
- **Biome** for consistent formatting and linting
- **Type safety** with TypeScript 5
- **React Compiler** for automatic performance optimizations
- **Husky + lint-staged** for pre-commit checks

#### CI/CD Pipeline
- **GitHub Actions workflows** for automated testing and deployment
- **Claude Code integration** for AI-assisted code review
- **Multi-stage Docker builds** for optimized container images
- **Cloudflare Workers deployment** with automatic URL generation

### 🔄 Breaking Changes

1. **Routing**: `/[host]/overview` → `/overview?host=0`
   - Update bookmarks and API clients to use query parameter format

2. **API - `fetchData()` now requires `hostId`**:
   ```typescript
   // Old
   const data = await fetchData(query, variables)

   // New - hostId is required, not optional
   const data = await fetchData(query, variables, hostId)
   ```

3. **Component Props**: All chart/table components require `hostId` prop
   - `<MyChart hostId={hostId} />` instead of relying on context
   - Prevents prop drilling through explicit prop passing at usage site

4. **Package Manager**: Requires Bun 10.18.2+
   - `bun install` instead of `npm install`
   - `bun run dev` instead of `npm run dev`

### 📦 Dependencies

#### Major Upgrades
- React: 18 → 19
- Next.js: 13 → 15
- Tailwind CSS: 3 → 4
- TypeScript: 4 → 5
- Radix UI: Updated to latest versions with new primitives

#### New Dependencies
- `@dnd-kit/*` - Drag-and-drop functionality for column reordering
- `@xyflow/react` - Zookeeper explorer visualization
- `opennextjs-cloudflare` - Next.js on Cloudflare Workers
- `biome` - Code formatter and linter
- `sonner` - Toast notifications

### 🐛 Bug Fixes

- Fixed host switcher not triggering data refresh on navigation
- Fixed darkmode logo visibility issues
- Fixed cluster routing badge counts
- Fixed E2E test navigation with /tables redirect
- Fixed mock import order for Bun test runner
- Improved error handling in env-utils for client components

### 📊 Monitoring & Observability

- **Query Performance Monitoring**: Enhanced query detail page
- **Cluster Health Metrics**: Expanded system metrics coverage
- **Error Logging**: Better error context and user-friendly messages
- **Table Validation**: Prevents confusing errors from optional tables

### 📝 Documentation

- **Migration Guide**: From v0.1 dynamic routing to v0.2 static routing
- **Cloudflare Workers Deployment**: Complete setup and configuration guide
- **Schema Documentation**: Per-version ClickHouse schema compatibility
- **Development Conventions**: Code organization, patterns, and best practices
- **AI Generated Docs**: Available at zread.ai/duyet/clickhouse-monitoring

### 🎯 Comparison: v0.1.16 → v0.2.0

| Aspect | v0.1.16 | v0.2.0 |
|--------|---------|--------|
| **Architecture** | SSR + Dynamic Routes | Static Site + SWR API |
| **Routing** | `/[host]/overview` | `/overview?host=0` |
| **Build Tool** | Turbopack | Turbopack (same, optimized) |
| **Framework** | React 18 + Next.js 13 | React 19 + Next.js 15 |
| **Package Manager** | PNPM | Bun |
| **Linting** | ESLint + Prettier | Biome |
| **Testing** | Jest (with issues) | Bun test runner + Cypress |
| **Deployment** | Vercel + Docker | Vercel + Docker + Cloudflare Workers |
| **Pages** | ~12 static pages | ~15+ static pages + analytics |
| **Charts** | ~20 charts | ~30+ charts |
| **CDN Caching** | Limited (dynamic routes) | Aggressive (static pages) |
| **Load Time** | ~2-3s | ~0.5-1s (edge cache) |

### ⚠️ Known Issues & Limitations

- **Jest Test Runner**: Currently hangs indefinitely in CI environment
  - Workaround: Using Bun test runner instead
  - Alternative: Cypress for testing until resolved

- **Cloudflare Workers Build**: Requires Webpack instead of Turbopack
  - Performance impact during build (CF Workers compatibility requirement)

### 🔮 Future Improvements

- Real-time query streaming with WebSockets
- Advanced analytics dashboard
- Custom metric definitions
- Query performance history and trends
- Cluster topology visualization
- Advanced access control and RBAC

---

## [0.1.16] - Previous Release

For details on v0.1.x releases, see [GitHub Releases](https://github.com/duyet/clickhouse-monitoring/releases).

### Key Features (v0.1 era)

- Multi-host ClickHouse cluster monitoring
- 20+ metric visualization charts
- Query monitoring and management
- Cluster overview and analytics
- Database and table explorer
- Real-time system metrics
- Docker and Vercel deployment support

---

## Version History

- **0.2.0-beta.4** - Pre-release with migration features
- **0.2.0-beta.3** - Cloudflare Workers support
- **0.2.0-beta.2** - SWR migration improvements
- **0.2.0-beta.1** - Initial static site migration
- **0.1.16** - Final v0.1 release
- **0.1.0** - Initial release
