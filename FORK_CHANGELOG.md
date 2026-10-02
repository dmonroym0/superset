# Fork changelog

## Upstream sync 2026-10-02 (d2fb52a..0fdfd66)

### feat
- feat\(table\): add multi\-level column header groups \(\#43938\) ([e5ec22a](https://github.com/apache/superset/commit/e5ec22ab3e9d5c158107cfd0236251871430155d))
- feat\(mcp\): support tab\-scoped dashboard layouts \(\#44797\) ([33292f2](https://github.com/apache/superset/commit/33292f249dad32c08921d6eac2a866be53c6c5e5))
- feat\(export/import\): add annotation layer export/import support for charts and dashboards \(\#43232\) ([ba3500e](https://github.com/apache/superset/commit/ba3500e0e9a21353060c68065a608e0bcd370385))

### fix
- fix: increase dataset edit modal size \(\#38215\) \(\#39257\) ([4cdd680](https://github.com/apache/superset/commit/4cdd680f39918012bdfe254bc7ca938aa4cd6939))
- fix\(doris\): offer the connection form by matching the installed driver \(\#44736\) ([4911dbe](https://github.com/apache/superset/commit/4911dbe00b0abebe59af196452887b5e5b875a1c))
- fix\(oauth2\): refresh a token rejected when a connection opens \(\#44765\) ([ee39954](https://github.com/apache/superset/commit/ee39954adb66f86f781debaed292e45e32dfd20a))
- fix\(mcp\): enforce tool deadlines without blocking the server \(\#44581\) ([a12d1b8](https://github.com/apache/superset/commit/a12d1b8e127c94cb536ef8aeb2500596dc843164))
- fix: size 'Drill to detail' table header correctly \(\#44807\) ([4ae8fe7](https://github.com/apache/superset/commit/4ae8fe712250851cf285cdecafee336470179766))
- fix\(mcp\): use DEFAULT\_PAGE\_SIZE constant in list\_charts test \(\#44786\) ([2c72d4d](https://github.com/apache/superset/commit/2c72d4d4fee83b03a07d87dc8c4402b24db153cb))
- fix\(mcp\): keep a bubble chart's colors and row limit across updates \(\#44618\) ([4468530](https://github.com/apache/superset/commit/446853004a4bc8334adb246806e5354c72149b82))
- fix\(frontend\): use html2canvas for chart image export on Safari \(\#44529\) ([217e4c0](https://github.com/apache/superset/commit/217e4c0223f03e86cdd1dfdc0cbc0e1efc14ac98))
- fix\(home\): redirect users without an ID before rendering \(\#44456\) ([abdf2e6](https://github.com/apache/superset/commit/abdf2e6c702503a83294e0f3aefeb604163d1087))
- fix\(mcp\): enforce dashboard filter scope on dataset, SQL and chart tool calls \(\#44800\) ([6a832cb](https://github.com/apache/superset/commit/6a832cb210223ce0cf45a63c268a6cf4c7e6aaa5))
- fix\(postprocessing\): preserve NULL index values through pivot\(\) \(\#43547\) \(\#43693\) ([e770202](https://github.com/apache/superset/commit/e770202034400ff755bc4bfd52fea373bdd4df42))
- fix\(mcp\): execute\_sql request limit caps, never raises, an explicit SQL LIMIT \(\#44604\) ([f7badeb](https://github.com/apache/superset/commit/f7badeb095bbd86db31e9c0ee15a71a911d8adb8))
- fix\(mcp\): report a chart's live dataset id and name \(\#44681\) ([342a8f1](https://github.com/apache/superset/commit/342a8f1e4e0361833a42cabc907fb92af5e0bbdc))
- fix\(retention\): skip models without purge policies before scanning \(\#44874\) ([21b937b](https://github.com/apache/superset/commit/21b937b59d7c5146fdac31572c12f44bd5032b3a))
- fix\(semantic\-layers\): export/import semantic\-view charts by typed reference \(\#44396\) ([6d97cde](https://github.com/apache/superset/commit/6d97cde59a6ab74cc84db168b2ace0c86feee20a))
- fix\(semantic\-layer\): require explicit member identity reselection \(\#44370\) ([b94f88f](https://github.com/apache/superset/commit/b94f88ffbb47c8b98dfacbb12f4753c2cbca162d))
- fix\(logging\): register LogRestApi only once \(\#44732\) ([9c7c96f](https://github.com/apache/superset/commit/9c7c96fe05741acd43b7a3ac84544cea84d4cc64))
- fix\(users\): stop update\_me setting self\-referential changed\_by\_fk \(\#44866\) ([1b0a37c](https://github.com/apache/superset/commit/1b0a37cf223849abb7613d650ffec1fae464a02d))
- fix\(ci\): floor pyfakefs at 5.7.4 to fix Python 3.13 pytest\-cov crash \(\#44853\) ([10d0685](https://github.com/apache/superset/commit/10d06859b834749ce2e48698d4ef77f998bc62f1))

### docs
- docs\(databases\): add ClickHouse Managed Postgres \(\#44870\) ([0fdfd66](https://github.com/apache/superset/commit/0fdfd6660e0ac33280f6b075d8fd35ea735821b4))

### test
- test\(playwright\): select existing dashboards without creating duplicates \(\#44856\) ([0a0a197](https://github.com/apache/superset/commit/0a0a1974c50ac46544068897b4d4f78eccceaef4))

### ci
- ci: require babel\-extract to pass before merging master \(\#44543\) ([db56168](https://github.com/apache/superset/commit/db56168a861f5cd09b2fca27b2e86eafffe8924d))

### chore
- chore\(deps\): bump @googleapis/sheets from 18.0.0 to 18.0.1 in /superset\-frontend \(\#44862\) ([3109cfa](https://github.com/apache/superset/commit/3109cfaf6d61aeb89f98870839f5f133c229b736))
- chore\(deps\): bump github/codeql\-action/analyze from 4.38.1 to 4.38.2 \(\#44861\) ([4f9c22d](https://github.com/apache/superset/commit/4f9c22db6dcf3b1ad81ba24e52ffaeea3ccc12e2))
- chore\(deps\): bump github/codeql\-action/upload\-sarif from 4.38.1 to 4.38.2 \(\#44859\) ([6418473](https://github.com/apache/superset/commit/6418473be146d1b93e726a0790f0016973d87aea))
- chore: add sadpandajoe as a codeowner for .asf.yaml \(\#44855\) ([8b64351](https://github.com/apache/superset/commit/8b643519ca0b45088a4e02dd8a183cb357018d62))
- chore: drop cypress\-matrix\-required from required status checks \(\#44854\) ([b98e19f](https://github.com/apache/superset/commit/b98e19f6eb23784db5d874346b4a14dd36eb786d))
- chore\(deps\): bump github/codeql\-action/init from 4.38.1 to 4.38.2 \(\#44860\) ([74d8852](https://github.com/apache/superset/commit/74d885233dec37c87bfbc15f87a913f0cb902fd5))
- chore\(e2e\): remove Cypress infrastructure \(\#44829\) ([8ab7a85](https://github.com/apache/superset/commit/8ab7a85a3d7e697d0ef5ee27b66b2f39164d0393))
- chore\(deps\): bump deck.gl and luma.gl from 9.2.5 to 9.4.0 in /superset\-frontend \(\#42608\) ([c82f97b](https://github.com/apache/superset/commit/c82f97b69d619815aa37aad40e131f00bc7c02e9))
- chore\(deps\-dev\): update google\-cloud\-storage requirement from &gt;=1.37 to &gt;=3.14.1 \(\#44693\) ([3f6d4cd](https://github.com/apache/superset/commit/3f6d4cd689648eb5ed320d31dc9feb27e147e644))
- chore\(deps\-dev\): bump baseline\-browser\-mapping from 2.11.25 to 2.11.26 in /superset\-frontend \(\#44890\) ([edc91b8](https://github.com/apache/superset/commit/edc91b86e5c35cd62eecf9fe2fbf5310df870bb1))
- chore\(deps\): bump dompurify from 3.4.15 to 3.4.16 in /superset\-frontend \(\#44889\) ([338e640](https://github.com/apache/superset/commit/338e640df9300c9f0ec1a59251c9f67f68a32597))
- chore\(deps\): bump dom\-to\-image\-more from 3.10.2 to 3.11.0 in /superset\-frontend \(\#44888\) ([4a19948](https://github.com/apache/superset/commit/4a19948659911a6551bfda8d9064230b3cc9e43f))
- chore\(deps\): bump maplibre\-gl from 6.8.0 to 6.11.2 in /superset\-frontend \(\#44887\) ([6559b48](https://github.com/apache/superset/commit/6559b483f28d0e338d98f4048374a4930dc30363))
- chore\(deps\-dev\): bump minimizer\-webpack\-plugin from 5.11.0 to 5.12.0 in /superset\-frontend \(\#44886\) ([dfccc2e](https://github.com/apache/superset/commit/dfccc2e1e9cc7b54569de9cd1c01dc860c565915))
- chore\(deps\-dev\): bump webpack\-sources from 3.5.1 to 3.5.3 in /superset\-frontend \(\#44885\) ([c43770e](https://github.com/apache/superset/commit/c43770e12da9a812d9cd2acba759eb99c68aa107))
- chore\(deps\-dev\): bump oxlint\-tsgolint from 7.0.2002 to 7.0.2003 in /docs \(\#44883\) ([95faf3a](https://github.com/apache/superset/commit/95faf3a6a049cdc74e809f9d4a153e8929973fa5))
- chore\(deps\-dev\): bump oxlint\-tsgolint from 7.0.2002 to 7.0.2003 in /superset\-websocket \(\#44882\) ([27c9213](https://github.com/apache/superset/commit/27c9213cca2ec14f084a3380897c4024c35595b3))
- chore\(superset\-ui\-chart\-controls\): forward\-compat fixes for TypeScript 6.0 \(\#44877\) ([25956d6](https://github.com/apache/superset/commit/25956d6c4485bfa96e3a9119cc1599185c713d06))
- chore\(deps\): bump dawidd6/action\-download\-artifact from 24 to 25 \(\#44884\) ([7bb2964](https://github.com/apache/superset/commit/7bb296494167bcfd7a5bbbec0180d390c7a2fc21))
- chore\(build\): de\-vendor \`helm/chart\-testing\-action\` GHA \(\#44722\) ([005edd7](https://github.com/apache/superset/commit/005edd74234a31ba44c9e67e7a2013fc61e74d7d))

### Dependency changes
- requirements/development.txt
_Dependency list may be incomplete: GitHub compare returned its 300-file cap._
