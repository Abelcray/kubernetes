<!-- BEGIN MUNGE: GENERATED_TOC -->

- [v1.21.0-alpha.2](#v1210-alpha2)
  - [Downloads for v1.21.0-alpha.2](#downloads-for-v1210-alpha2)
    - [Source Code](#source-code)
    - [Client binaries](#client-binaries)
    - [Server binaries](#server-binaries)
    - [Node binaries](#node-binaries)
  - [Changelog since v1.21.0-alpha.1](#changelog-since-v1210-alpha1)
  - [Urgent Upgrade Notes](#urgent-upgrade-notes)
    - [(No, really, you MUST read this before you upgrade)](#no-really-you-must-read-this-before-you-upgrade)
  - [Changes by Kind](#changes-by-kind)
    - [Deprecation](#deprecation)
    - [API Change](#api-change)
    - [Documentation](#documentation)
    - [Bug or Regression](#bug-or-regression)
    - [Other (Cleanup or Flake)](#other-cleanup-or-flake)
  - [Dependencies](#dependencies)
    - [Added](#added)
    - [Changed](#changed)
    - [Removed](#removed)
- [v1.21.0-alpha.1](#v1210-alpha1)
  - [Downloads for v1.21.0-alpha.1](#downloads-for-v1210-alpha1)
    - [Source Code](#source-code-1)
    - [Client binaries](#client-binaries-1)
    - [Server binaries](#server-binaries-1)
    - [Node binaries](#node-binaries-1)
  - [Changelog since v1.20.0](#changelog-since-v1200)
  - [Urgent Upgrade Notes](#urgent-upgrade-notes-1)
    - [(No, really, you MUST read this before you upgrade)](#no-really-you-must-read-this-before-you-upgrade-1)
  - [Changes by Kind](#changes-by-kind-1)
    - [Deprecation](#deprecation-1)
    - [API Change](#api-change-1)
    - [Feature](#feature)
    - [Bug or Regression](#bug-or-regression-1)
    - [Other (Cleanup or Flake)](#other-cleanup-or-flake-1)
    - [Uncategorized](#uncategorized)
  - [Dependencies](#dependencies-1)
    - [Added](#added-1)
    - [Changed](#changed-1)
    - [Removed](#removed-1)

<!-- END MUNGE: GENERATED_TOC -->

# v1.21.0-alpha.2


## Downloads for v1.21.0-alpha.2

### Source Code

filename | sha512 hash
-------- | -----------
[kubernetes.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes.tar.gz) | 6836f6c8514253fe0831fd171fc4ed92eb6d9a773491c8dc82b90d171a1b10076bd6bfaea56ec1e199c5f46c273265bdb9f174f0b2d99c5af1de4c99b862329e
[kubernetes-src.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-src.tar.gz) | d137694804741a05ab09e5f9a418448b66aba0146c028eafce61bcd9d7c276521e345ce9223ffbc703e8172041d58dfc56a3242a4df3686f24905a4541fcd306

### Client binaries

filename | sha512 hash
-------- | -----------
[kubernetes-client-darwin-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-client-darwin-amd64.tar.gz) | 9478b047a97717953f365c13a098feb7e3cb30a3df22e1b82aa945f2208dcc5cb90afc441ba059a3ae7aafb4ee000ec3a52dc65a8c043a5ac7255a391c875330
[kubernetes-client-linux-386.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-client-linux-386.tar.gz) | 44c8dd4b1ddfc256d35786c8abf45b0eb5f0794f5e310d2efc865748adddc50e8bf38aa71295ae8a82884cb65f2e0b9b0737b000f96fd8f2d5c19971d7c4d8e8
[kubernetes-client-linux-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-client-linux-amd64.tar.gz) | e1291989892769de6b978c17b8612b94da6f3b735a4d895100af622ca9ebb968c75548afea7ab00445869625dd0da3afec979e333afbb445805f5d31c1c13cc7
[kubernetes-client-linux-arm.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-client-linux-arm.tar.gz) | 3c4bcb8cbe73822d68a2f62553a364e20bec56b638c71d0f58679b4f4b277d809142346f18506914e694f6122a3e0f767eab20b7b1c4dbb79e4c5089981ae0f1
[kubernetes-client-linux-arm64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-client-linux-arm64.tar.gz) | 9389974a790268522e187f5ba5237f3ee4684118c7db76bc3d4164de71d8208702747ec333b204c7a78073ab42553cbbce13a1883fab4fec617e093b05fab332
[kubernetes-client-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-client-linux-ppc64le.tar.gz) | 63399e53a083b5af3816c28ff162c9de6b64c75da4647f0d6bbaf97afdf896823cb1e556f2abac75c6516072293026d3ff9f30676fd75143ac6ca3f4d21f4327
[kubernetes-client-linux-s390x.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-client-linux-s390x.tar.gz) | 50898f197a9d923971ff9046c9f02779b57f7b3cea7da02f3ea9bab8c08d65a9c4a7531a2470fa14783460f52111a52b96ebf916c0a1d8215b4070e4e861c1b0
[kubernetes-client-windows-386.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-client-windows-386.tar.gz) | a7743e839e1aa19f5ee20b6ee5000ac8ef9e624ac5be63bb574fad6992e4b9167193ed07e03c9bc524e88bfeed66c95341a38a03bff1b10bc9910345f33019f0
[kubernetes-client-windows-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-client-windows-amd64.tar.gz) | 5f1d19c230bd3542866d16051808d184e9dd3e2f8c001ed4cee7b5df91f872380c2bf56a3add8c9413ead9d8c369efce2bcab4412174df9b823d3592677bf74e

### Server binaries

filename | sha512 hash
-------- | -----------
[kubernetes-server-linux-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-server-linux-amd64.tar.gz) | ef2cac10febde231aeb6f131e589450c560eeaab8046b49504127a091cddc17bc518c2ad56894a6a033033ab6fc6e121b1cc23691683bc36f45fe6b1dd8e0510
[kubernetes-server-linux-arm.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-server-linux-arm.tar.gz) | d11c9730307f08e80b2b8a7c64c3e9a9e43c622002e377dfe3a386f4541e24adc79a199a6f280f40298bb36793194fd44ed45defe8a3ee54a9cb1386bc26e905
[kubernetes-server-linux-arm64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-server-linux-arm64.tar.gz) | 28f8c32bf98ee1add7edf5d341c3bac1afc0085f90dcbbfb8b27a92087f13e2b53c327c8935ee29bf1dc3160655b32bbe3e29d5741a8124a3848a777e7d42933
[kubernetes-server-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-server-linux-ppc64le.tar.gz) | 99ae8d44b0de3518c27fa8bbddd2ecf053dfb789fb9d65f8a4ecf4c8331cf63d2f09a41c2bcd5573247d5f66a1b2e51944379df1715017d920d521b98589508a
[kubernetes-server-linux-s390x.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-server-linux-s390x.tar.gz) | f8c0e954a2dfc6845614488dadeed069cc7f3f08e33c351d7a77c6ef97867af590932e8576d12998a820a0e4d35d2eee797c764e2810f09ab1e90a5acaeaad33

### Node binaries

filename | sha512 hash
-------- | -----------
[kubernetes-node-linux-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-node-linux-amd64.tar.gz) | c5456d50bfbe0d75fb150b3662ed7468a0abd3970792c447824f326894382c47bbd3a2cc5a290f691c8c09585ff6fe505ab86b4aff2b7e5ccee11b5e6354ae6c
[kubernetes-node-linux-arm.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-node-linux-arm.tar.gz) | 335b5cd8672e053302fd94d932fb2fa2e48eeeb1799650b3f93acdfa635e03a8453637569ab710c46885c8317759f4c60aaaf24dca9817d9fa47500fe4a3ca53
[kubernetes-node-linux-arm64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-node-linux-arm64.tar.gz) | 3ee87dbeed8ace9351ac89bdaf7274dd10b4faec3ceba0825f690ec7a2bb7eb7c634274a1065a0939eec8ff3e43f72385f058f4ec141841550109e775bc5eff9
[kubernetes-node-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-node-linux-ppc64le.tar.gz) | 6956f965b8d719b164214ec9195fdb2c776b907fe6d2c524082f00c27872a73475927fd7d2a994045ce78f6ad2aa5aeaf1eb5514df1810d2cfe342fd4e5ce4a1
[kubernetes-node-linux-s390x.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-node-linux-s390x.tar.gz) | 3b643aa905c709c57083c28dd9e8ffd88cb64466cda1499da7fc54176b775003e08b9c7a07b0964064df67c8142f6f1e6c13bfc261bd65fb064049920bfa57d0
[kubernetes-node-windows-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.2/kubernetes-node-windows-amd64.tar.gz) | b2e6d6fb0091f2541f9925018c2bdbb0138a95bab06b4c6b38abf4b7144b2575422263b78fb3c6fd09e76d90a25a8d35a6d4720dc169794d42c95aa22ecc6d5f

## Changelog since v1.21.0-alpha.1

## Urgent Upgrade Notes

### (No, really, you MUST read this before you upgrade)

 - Remove storage metrics `storage_operation_errors_total`, since we already have `storage_operation_status_count`.And add new field `status` for `storage_operation_duration_seconds`, so that we can know about all status storage operation latency. ([#98332](https://github.com/kubernetes/kubernetes/pull/98332), [@JornShen](https://github.com/JornShen)) [SIG Instrumentation and Storage]
 
## Changes by Kind

### Deprecation

- Remove the TokenRequest and TokenRequestProjection feature gates ([#97148](https://github.com/kubernetes/kubernetes/pull/97148), [@wawa0210](https://github.com/wawa0210)) [SIG Node]
- Removing experimental windows container hyper-v support with Docker ([#97141](https://github.com/kubernetes/kubernetes/pull/97141), [@wawa0210](https://github.com/wawa0210)) [SIG Node and Windows]
- The `export` query parameter (inconsistently supported by API resources and deprecated in v1.14) is fully removed.  Requests setting this query parameter will now receive a 400 status response. ([#98312](https://github.com/kubernetes/kubernetes/pull/98312), [@deads2k](https://github.com/deads2k)) [SIG API Machinery, Auth and Testing]

### API Change

- Enable SPDY pings to keep connections alive, so that `kubectl exec` and `kubectl port-forward` won't be interrupted. ([#97083](https://github.com/kubernetes/kubernetes/pull/97083), [@knight42](https://github.com/knight42)) [SIG API Machinery and CLI]

### Documentation

- Official support to build kubernetes with docker-machine / remote docker is removed. This change does not affect building kubernetes with docker locally. ([#97935](https://github.com/kubernetes/kubernetes/pull/97935), [@adeniyistephen](https://github.com/adeniyistephen)) [SIG Release and Testing]
- Set kubelet option `--volume-stats-agg-period` to negative value to disable volume calculations. ([#96675](https://github.com/kubernetes/kubernetes/pull/96675), [@pacoxu](https://github.com/pacoxu)) [SIG Node]

### Bug or Regression

- Clean ReplicaSet by revision instead of creation timestamp in deployment controller ([#97407](https://github.com/kubernetes/kubernetes/pull/97407), [@waynepeking348](https://github.com/waynepeking348)) [SIG Apps]
- Ensure that client-go's EventBroadcaster is safe (non-racy) during shutdown. ([#95664](https://github.com/kubernetes/kubernetes/pull/95664), [@DirectXMan12](https://github.com/DirectXMan12)) [SIG API Machinery]
- Fix azure file migration issue ([#97877](https://github.com/kubernetes/kubernetes/pull/97877), [@andyzhangx](https://github.com/andyzhangx)) [SIG Auth, Cloud Provider and Storage]
- Fix kubelet from panic after getting the wrong signal ([#98200](https://github.com/kubernetes/kubernetes/pull/98200), [@wzshiming](https://github.com/wzshiming)) [SIG Node]
- Fix repeatedly acquire the inhibit lock ([#98088](https://github.com/kubernetes/kubernetes/pull/98088), [@wzshiming](https://github.com/wzshiming)) [SIG Node]
- Fixed a bug that the kubelet cannot start on BtrfS. ([#98042](https://github.com/kubernetes/kubernetes/pull/98042), [@gjkim42](https://github.com/gjkim42)) [SIG Node]
- Fixed an issue with garbage collection failing to clean up namespaced children of an object also referenced incorrectly by cluster-scoped children ([#98068](https://github.com/kubernetes/kubernetes/pull/98068), [@liggitt](https://github.com/liggitt)) [SIG API Machinery and Apps]
- Fixed no effect namespace when exposing deployment with --dry-run=client. ([#97492](https://github.com/kubernetes/kubernetes/pull/97492), [@masap](https://github.com/masap)) [SIG CLI]
- Fixing a bug where a failed node may not have the NoExecute taint set correctly ([#96876](https://github.com/kubernetes/kubernetes/pull/96876), [@howieyuen](https://github.com/howieyuen)) [SIG Apps and Node]
- Indentation of `Resource Quota` block in kubectl describe namespaces output gets correct. ([#97946](https://github.com/kubernetes/kubernetes/pull/97946), [@dty1er](https://github.com/dty1er)) [SIG CLI]
- KUBECTL_EXTERNAL_DIFF now accepts equal sign for additional parameters. ([#98158](https://github.com/kubernetes/kubernetes/pull/98158), [@dougsland](https://github.com/dougsland)) [SIG CLI]
- Kubeadm: fix a bug where "kubeadm join" would not properly handle missing names for existing etcd members. ([#97372](https://github.com/kubernetes/kubernetes/pull/97372), [@ihgann](https://github.com/ihgann)) [SIG Cluster Lifecycle]
- Kubelet should ignore cgroup driver check on Windows node. ([#97764](https://github.com/kubernetes/kubernetes/pull/97764), [@pacoxu](https://github.com/pacoxu)) [SIG Node and Windows]
- Make podTopologyHints protected by lock ([#95111](https://github.com/kubernetes/kubernetes/pull/95111), [@choury](https://github.com/choury)) [SIG Node]
- Readjust kubelet_containers_per_pod_count bucket ([#98169](https://github.com/kubernetes/kubernetes/pull/98169), [@wawa0210](https://github.com/wawa0210)) [SIG Instrumentation and Node]
- Scores from InterPodAffinity have stronger differentiation. ([#98096](https://github.com/kubernetes/kubernetes/pull/98096), [@leileiwan](https://github.com/leileiwan)) [SIG Scheduling]
- Specifying the KUBE_TEST_REPO environment variable when e2e tests are executed will instruct the test infrastructure to load that image from a location within the specified repo, using a predefined pattern. ([#93510](https://github.com/kubernetes/kubernetes/pull/93510), [@smarterclayton](https://github.com/smarterclayton)) [SIG Testing]
- Static pods will be deleted gracefully. ([#98103](https://github.com/kubernetes/kubernetes/pull/98103), [@gjkim42](https://github.com/gjkim42)) [SIG Node]
- Use network.Interface.VirtualMachine.ID to get the binded VM
  Skip standalone VM when reconciling LoadBalancer ([#97635](https://github.com/kubernetes/kubernetes/pull/97635), [@nilo19](https://github.com/nilo19)) [SIG Cloud Provider]

### Other (Cleanup or Flake)

- Kubeadm: change the default image repository for CI images from 'gcr.io/kubernetes-ci-images' to 'gcr.io/k8s-staging-ci-images' ([#97087](https://github.com/kubernetes/kubernetes/pull/97087), [@SataQiu](https://github.com/SataQiu)) [SIG Cluster Lifecycle]
- Migrate generic_scheduler.go and types.go to structured logging. ([#98134](https://github.com/kubernetes/kubernetes/pull/98134), [@tanjing2020](https://github.com/tanjing2020)) [SIG Scheduling]
- Migrate proxy/winuserspace/proxier.go logs to structured logging ([#97941](https://github.com/kubernetes/kubernetes/pull/97941), [@JornShen](https://github.com/JornShen)) [SIG Network]
- Migrate staging/src/k8s.io/apiserver/pkg/audit/policy/reader.go logs to structured logging. ([#98252](https://github.com/kubernetes/kubernetes/pull/98252), [@lala123912](https://github.com/lala123912)) [SIG API Machinery and Auth]
- Migrate staging\src\k8s.io\apiserver\pkg\endpoints logs to  structured logging ([#98093](https://github.com/kubernetes/kubernetes/pull/98093), [@lala123912](https://github.com/lala123912)) [SIG API Machinery]
- Node ([#96552](https://github.com/kubernetes/kubernetes/pull/96552), [@pandaamanda](https://github.com/pandaamanda)) [SIG Apps, Cloud Provider, Node and Scheduling]
- The kubectl alpha debug command was scheduled to be removed in v1.21. ([#98111](https://github.com/kubernetes/kubernetes/pull/98111), [@pandaamanda](https://github.com/pandaamanda)) [SIG CLI]
- Update cri-tools to [v1.20.0](https://github.com/kubernetes-sigs/cri-tools/releases/tag/v1.20.0) ([#97967](https://github.com/kubernetes/kubernetes/pull/97967), [@rajibmitra](https://github.com/rajibmitra)) [SIG Cloud Provider]
- Windows nodes on GCE will take longer to start due to dependencies installed at node creation time. ([#98284](https://github.com/kubernetes/kubernetes/pull/98284), [@pjh](https://github.com/pjh)) [SIG Cloud Provider]

## Dependencies

### Added
_Nothing has changed._

### Changed
- github.com/google/cadvisor: [v0.38.6 → v0.38.7](https://github.com/google/cadvisor/compare/v0.38.6...v0.38.7)
- k8s.io/gengo: 83324d8 → b6c5ce2

### Removed
_Nothing has changed._



# v1.21.0-alpha.1


## Downloads for v1.21.0-alpha.1

### Source Code

filename | sha512 hash
-------- | -----------
[kubernetes.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes.tar.gz) | b2bacd5c3fc9f829e6269b7d2006b0c6e464ff848bb0a2a8f2fe52ad2d7c4438f099bd8be847d8d49ac6e4087f4d74d5c3a967acd798e0b0cb4d7a2bdb122997
[kubernetes-src.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-src.tar.gz) | 518ac5acbcf23902fb1b902b69dbf3e86deca5d8a9b5f57488a15f185176d5a109558f3e4df062366af874eca1bcd61751ee8098b0beb9bcdc025d9a1c9be693

### Client binaries

filename | sha512 hash
-------- | -----------
[kubernetes-client-darwin-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-client-darwin-amd64.tar.gz) | eaa7aea84a5ed954df5ec710cbeb6ec88b46465f43cb3d09aabe2f714b84a050a50bf5736089f09dbf1090f2e19b44823d656c917e3c8c877630756c3026f2b6
[kubernetes-client-linux-386.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-client-linux-386.tar.gz) | 47f74b8d46ad1779c5b0b5f15aa15d5513a504eeb6f53db4201fbe9ff8956cb986b7c1b0e9d50a99f78e9e2a7f304f3fc1cc2fa239296d9a0dd408eb6069e975
[kubernetes-client-linux-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-client-linux-amd64.tar.gz) | 1a148e282628b008c8abd03dd12ec177ced17584b5115d92cd33dd251e607097d42e9da8c7089bd947134b900f85eb75a4740b6a5dd580c105455b843559df39
[kubernetes-client-linux-arm.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-client-linux-arm.tar.gz) | d13d2feb73bd032dc01f7e2955b98d8215a39fe1107d037a73fa1f7d06c3b93ebaa53ed4952d845c64454ef3cca533edb97132d234d50b6fb3bcbd8a8ad990eb
[kubernetes-client-linux-arm64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-client-linux-arm64.tar.gz) | 8252105a17b09a78e9ad2c024e4e401a69764ac869708a071aaa06f81714c17b9e7c5b2eb8efde33f24d0b59f75c5da607d5e1e72bdf12adfbb8c829205cd1c1
[kubernetes-client-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-client-linux-ppc64le.tar.gz) | 297a9082df4988389dc4be30eb636dff49f36f5d87047bab44745884e610f46a17ae3a08401e2cab155b7c439f38057bfd8288418215f7dd3bf6a49dbe61ea0e
[kubernetes-client-linux-s390x.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-client-linux-s390x.tar.gz) | 04c06490dd17cd5dccfd92bafa14acf64280ceaea370d9635f23aeb6984d1beae6d0d1d1506edc6f30f927deeb149b989d3e482b47fbe74008b371f629656e79
[kubernetes-client-windows-386.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-client-windows-386.tar.gz) | ec6e9e87a7d685f8751d7e58f24f417753cff5554a7229218cb3a08195d461b2e12409344950228e9fbbc92a8a06d35dd86242da6ff1e6652ec1fae0365a88c1
[kubernetes-client-windows-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-client-windows-amd64.tar.gz) | 51039e6221d3126b5d15e797002ae01d4f0b10789c5d2056532f27ef13f35c5a2e51be27764fda68e8303219963126559023aed9421313bec275c0827fbcaf8a

### Server binaries

filename | sha512 hash
-------- | -----------
[kubernetes-server-linux-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-server-linux-amd64.tar.gz) | 4edf820930c88716263560275e3bd7fadb8dc3700b9f8e1d266562e356e0abeb1a913f536377dab91218e3940b447d6bf1da343b85da25c2256dc4dcde5798dd
[kubernetes-server-linux-arm.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-server-linux-arm.tar.gz) | b15213e53a8ab4ba512ce6ef9ad42dd197d419c61615cd23de344227fd846c90448d8f3d98e555b63ba5b565afa627cca6b7e3990ebbbba359c96f2391302df1
[kubernetes-server-linux-arm64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-server-linux-arm64.tar.gz) | 5be29cca9a9358fc68351ee63e99d57dc2ffce6e42fc3345753dbbf7542ff2d770c4852424158540435fa6e097ce3afa9b13affc40c8b3b69fe8406798f8068f
[kubernetes-server-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-server-linux-ppc64le.tar.gz) | 89fd99ab9ce85db0b94b86709932105efc883cc93959cf7ea9a39e79a4acea23064d7010eeb577450cccabe521c04b7ba47bbec212ed37edeed7cb04bad34518
[kubernetes-server-linux-s390x.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-server-linux-s390x.tar.gz) | 2fbc30862c77d247aa8d96ab9d1a144599505287b0033a3a2d0988958e7bb2f2e8b67f52c1fec74b4ec47d74ba22cd0f6cb5c4228acbaa72b1678d5fece0254d

### Node binaries

filename | sha512 hash
-------- | -----------
[kubernetes-node-linux-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-node-linux-amd64.tar.gz) | 95658d321a0a371c0900b401d1469d96915310afbc4e4b9b11f031438bb188513b57d5a60b5316c3b0c18f541cda6f0ac42f59a76495f8abc743a067115da23a
[kubernetes-node-linux-arm.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-node-linux-arm.tar.gz) | f375acfb42aad6c65b833c270e7e3acfe9cd1d6b2441c33874e77faae263957f7acfe86f1b71f14298118595e4cc6952c7dea0c832f7f2e72428336f13034362
[kubernetes-node-linux-arm64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-node-linux-arm64.tar.gz) | 43b4baccd58d74e7f48d096ab92f2bbbcdf47e30e7a3d2b56c6cc9f90002cfd4fefaac894f69bd5f9f4dbdb09a4749a77eb76b1b97d91746bd96fe94457879ab
[kubernetes-node-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-node-linux-ppc64le.tar.gz) | e7962b522c6c7c14b9ee4c1d254d8bdd9846b2b33b0443fc9c4a41be6c40e5e6981798b720f0148f36263d5cc45d5a2bb1dd2f9ab2838e3d002e45b9bddeb7bf
[kubernetes-node-linux-s390x.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-node-linux-s390x.tar.gz) | 49ebc97f01829e65f7de15be00b882513c44782eaadd1b1825a227e3bd3c73cc6aca8345af05b303d8c43aa2cb944a069755b2709effb8cc22eae621d25d4ba5
[kubernetes-node-windows-amd64.tar.gz](https://dl.k8s.io/v1.21.0-alpha.1/kubernetes-node-windows-amd64.tar.gz) | 6e0fd7724b09e6befbcb53b33574e97f2db089f2eee4bbf391abb7f043103a5e6e32e3014c0531b88f9a3ca88887bbc68625752c44326f98dd53adb3a6d1bed8

## Changelog since v1.20.0

## Urgent Upgrade Notes

### (No, really, you MUST read this before you upgrade)

 - Kube-proxy's IPVS proxy mode no longer sets the net.ipv4.conf.all.route_localnet sysctl parameter. Nodes upgrading will have net.ipv4.conf.all.route_localnet set to 1 but new nodes will inherit the system default (usually 0). If you relied on any behavior requiring net.ipv4.conf.all.route_localnet, you must set ensure it is enabled as kube-proxy will no longer set it automatically. This change helps to further mitigate CVE-2020-8558. ([#92938](https://github.com/kubernetes/kubernetes/pull/92938), [@lbernail](https://github.com/lbernail)) [SIG Network and Release]
 
## Changes by Kind

### Deprecation

- Deprecate the `topologyKeys` field in Service. This capability will be replaced with upcoming work around Topology Aware Subsetting and Service Internal Traffic Policy. ([#96736](https://github.com/kubernetes/kubernetes/pull/96736), [@andrewsykim](https://github.com/andrewsykim)) [SIG Apps]
- Kubeadm: deprecated command "alpha selfhosting pivot" is removed now. ([#97627](https://github.com/kubernetes/kubernetes/pull/97627), [@knight42](https://github.com/knight42)) [SIG Cluster Lifecycle]
- Kubeadm: graduate the command `kubeadm alpha kubeconfig user` to `kubeadm kubeconfig user`. The `kubeadm alpha kubeconfig user` command is deprecated now. ([#97583](https://github.com/kubernetes/kubernetes/pull/97583), [@knight42](https://github.com/knight42)) [SIG Cluster Lifecycle]
- Kubeadm: the "kubeadm alpha certs" command is removed now, please use "kubeadm certs" instead. ([#97706](https://github.com/kubernetes/kubernetes/pull/97706), [@knight42](https://github.com/knight42)) [SIG Cluster Lifecycle]
- Remove the deprecated metrics "scheduling_algorithm_preemption_evaluation_seconds" and "binding_duration_seconds", suggest to use "scheduler_framework_extension_point_duration_seconds" instead. ([#96447](https://github.com/kubernetes/kubernetes/pull/96447), [@chendave](https://github.com/chendave)) [SIG Cluster Lifecycle, Instrumentation, Scheduling and Testing]
- The PodSecurityPolicy API is deprecated in 1.21, and will no longer be served starting in 1.25. ([#97171](https://github.com/kubernetes/kubernetes/pull/97171), [@deads2k](https://github.com/deads2k)) [SIG Auth and CLI]

### API Change

- Change the APIVersion proto name of BoundObjectRef from aPIVersion to apiVersion. ([#97379](https://github.com/kubernetes/kubernetes/pull/97379), [@kebe7jun](https://github.com/kebe7jun)) [SIG Auth]
- Promote Immutable Secrets/ConfigMaps feature to Stable.
  This allows to set `Immutable` field in Secrets or ConfigMap object to mark their contents as immutable. ([#97615](https://github.com/kubernetes/kubernetes/pull/97615), [@wojtek-t](https://github.com/wojtek-t)) [SIG Apps, Architecture, Node and Testing]

### Feature

- Add flag --lease-max-object-size and metric etcd_lease_object_counts for kube-apiserver to config and observe max objects attached to a single etcd lease. ([#97480](https://github.com/kubernetes/kubernetes/pull/97480), [@lingsamuel](https://github.com/lingsamuel)) [SIG API Machinery, Instrumentation and Scalability]
- Add flag --lease-reuse-duration-seconds for kube-apiserver to config etcd lease reuse duration. ([#97009](https://github.com/kubernetes/kubernetes/pull/97009), [@lingsamuel](https://github.com/lingsamuel)) [SIG API Machinery and Scalability]
- Adds the ability to pass --strict-transport-security-directives to the kube-apiserver to set the HSTS header appropriately.  Be sure you understand the consequences to browsers before setting this field. ([#96502](https://github.com/kubernetes/kubernetes/pull/96502), [@249043822](https://github.com/249043822)) [SIG Auth]
- Kubeadm now includes CoreDNS v1.8.0. ([#96429](https://github.com/kubernetes/kubernetes/pull/96429), [@rajansandeep](https://github.com/rajansandeep)) [SIG Cluster Lifecycle]
- Kubeadm: add support for certificate chain validation. When using kubeadm in external CA mode, this allows an intermediate CA to be used to sign the certificates. The intermediate CA certificate must be appended to each signed certificate for this to work correctly. ([#97266](https://github.com/kubernetes/kubernetes/pull/97266), [@robbiemcmichael](https://github.com/robbiemcmichael)) [SIG Cluster Lifecycle]
- Kubeadm: amend the node kernel validation to treat CGROUP_PIDS, FAIR_GROUP_SCHED as required and CFS_BANDWIDTH, CGROUP_HUGETLB as optional ([#96378](https://github.com/kubernetes/kubernetes/pull/96378), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle and Node]
- The Kubernetes pause image manifest list now contains an image for Windows Server 20H2. ([#97322](https://github.com/kubernetes/kubernetes/pull/97322), [@claudiubelu](https://github.com/claudiubelu)) [SIG Windows]
- The apimachinery util/net function used to detect the bind address `ResolveBindAddress()`
  takes into consideration global ip addresses on loopback interfaces when:
      - the host has default routes
      - there are no global IPs on those interfaces.
  in order to support more complex network scenarios like BGP Unnumbered RFC 5549 ([#95790](https://github.com/kubernetes/kubernetes/pull/95790), [@aojea](https://github.com/aojea)) [SIG Network]

### Bug or Regression

- ## Changelog
  
  ### General
  - Fix priority expander falling back to a random choice even though there is a higher priority option to choose
  - Clone `kubernetes/kubernetes` in `update-vendor.sh` shallowly, instead of fetching all revisions
  - Speed up binpacking by reducing the number of PreFilter calls (call once per pod instead of #pods*#nodes times)
  - Speed up finding unneeded nodes by 5x+ in very large clusters by reducing the number of PreFilter calls
  - Expose `--max-nodes-total` as a metric
  - Errors in `IncreaseSize` changed from type `apiError` to `cloudProviderError`
  - Make `build-in-docker` and `test-in-docker` work on Linux systems with SELinux enabled
  - Fix an error where existing nodes were not considered as destinations while finding place for pods in scale-down simulations
  - Remove redundant log lines and reduce severity around parsing kubeEnv
  - Don't treat nodes created by virtual kubelet as nodes from non-autoscaled node groups
  - Remove redundant logging around calculating node utilization
  - Add configurable `--network` and `--rm` flags for docker in `Makefile`
  - Subtract DaemonSet pods' requests from node allocatable in the denominator while computing node utilization
  - Include taints by condition when determining if a node is unready/still starting
  - Fix `update-vendor.sh` to work on OSX and zsh
  - Add best-effort eviction for DaemonSet pods while scaling down non-empty nodes
  - Add build support for ARM64
  
  ### AliCloud
  - Add missing daemonsets and replicasets to ALI example cluster role
  
  ### Apache CloudStack
  - Add support for Apache CloudStack
  
  ### AWS
  - Regenerate list of EC2 instances
  - Fix pricing endpoint in AWS China Region
  
  ### Azure
  - Add optional jitter on initial VMSS VM cache refresh, keep the refreshes spread over time
  - Serve from cache for the whole period of ongoing throttling
  - Fix unwanted VMSS VMs cache invalidations
  - Enforce setting the number of retries if cloud provider backoff is enabled
  - Don't update capacity if VMSS provisioning state is updating
  - Support allocatable resources overrides via VMSS tags
  - Add missing stable labels in template nodes
  - Proactively set instance status to deleting on node deletions
  
  ### Cluster API
  - Migrate interaction with the API from using internal types to using Unstructured
  - Improve tests to work better with constrained resources
  - Add support for node autodiscovery
  - Add support for `--cloud-config`
  - Update group identifier to use for Cluster API annotations
  
  ### Exoscale
  - Add support for Exoscale
  
  ### GCE
  - Decrease the number of GCE Read Requests made while deleting nodes
  - Base pricing of custom instances on their instance family type
  - Add pricing information for missing machine types
  - Add pricing information for different GPU types
  - Ignore the new `topology.gke.io/zone` label when comparing groups
  - Add missing stable labels to template nodes
  
  ### HuaweiCloud
  - Add auto scaling group support
  - Implement node group by AS
  - Implement getting desired instance number of node group
  - Implement increasing node group size
  - Implement TemplateNodeInfo
  - Implement caching instances
  
  ### IONOS
  - Add support for IONOS
  
  ### Kubemark
  - Skip non-kubemark nodes while computing node infos for node groups.
  
  ### Magnum
  - Add Magnum support in the Cluster Autoscaler helm chart
  
  ### Packet
  - Allow empty nodepools
  - Add support for multiple nodepools
  - Add pricing support
  
  ## Image
  Image: `k8s.gcr.io/autoscaling/cluster-autoscaler:v1.20.0` ([#97011](https://github.com/kubernetes/kubernetes/pull/97011), [@towca](https://github.com/towca)) [SIG Cloud Provider]
- AcceleratorStats will be available in the Summary API of kubelet when cri_stats_provider is used. ([#96873](https://github.com/kubernetes/kubernetes/pull/96873), [@ruiwen-zhao](https://github.com/ruiwen-zhao)) [SIG Node]
- Add limited lines to log when having tail option ([#93920](https://github.com/kubernetes/kubernetes/pull/93920), [@zhouya0](https://github.com/zhouya0)) [SIG Node]
- Avoid systemd-logind loading configuration warning ([#97950](https://github.com/kubernetes/kubernetes/pull/97950), [@wzshiming](https://github.com/wzshiming)) [SIG Node]
- Cloud-controller-manager: routes controller should not depend on --allocate-node-cidrs ([#97029](https://github.com/kubernetes/kubernetes/pull/97029), [@andrewsykim](https://github.com/andrewsykim)) [SIG Cloud Provider and Testing]
- Copy annotations with empty value when deployment rolls back ([#94858](https://github.com/kubernetes/kubernetes/pull/94858), [@waynepeking348](https://github.com/waynepeking348)) [SIG Apps]
- Detach volumes from vSphere nodes not tracked by attach-detach controller ([#96689](https://github.com/kubernetes/kubernetes/pull/96689), [@gnufied](https://github.com/gnufied)) [SIG Cloud Provider and Storage]
- Fix kubectl label error when local=true is set. ([#97440](https://github.com/kubernetes/kubernetes/pull/97440), [@pandaamanda](https://github.com/pandaamanda)) [SIG CLI]
- Fix Azure file share not deleted issue when the namespace is deleted ([#97417](https://github.com/kubernetes/kubernetes/pull/97417), [@andyzhangx](https://github.com/andyzhangx)) [SIG Cloud Provider and Storage]
- Fix CVE-2020-8555 for Gluster client connections. ([#97922](https://github.com/kubernetes/kubernetes/pull/97922), [@liggitt](https://github.com/liggitt)) [SIG Storage]
- Fix counting error in service/nodeport/loadbalancer quota check ([#97451](https://github.com/kubernetes/kubernetes/pull/97451), [@pacoxu](https://github.com/pacoxu)) [SIG API Machinery, Network and Testing]
- Fix kubectl-convert import known versions ([#97754](https://github.com/kubernetes/kubernetes/pull/97754), [@wzshiming](https://github.com/wzshiming)) [SIG CLI and Testing]
- Fix missing cadvisor machine metrics. ([#97006](https://github.com/kubernetes/kubernetes/pull/97006), [@lingsamuel](https://github.com/lingsamuel)) [SIG Node]
- Fix nil VMSS name when setting service to auto mode ([#97366](https://github.com/kubernetes/kubernetes/pull/97366), [@nilo19](https://github.com/nilo19)) [SIG Cloud Provider]
- Fix the panic when kubelet registers if a node object already exists with no Status.Capacity or Status.Allocatable ([#95269](https://github.com/kubernetes/kubernetes/pull/95269), [@SataQiu](https://github.com/SataQiu)) [SIG Node]
- Fix the regression with the slow pods termination. Before this fix pods may take an additional time to terminate - up to one minute. Reversing the change that ensured that CNI resources cleaned up when the pod is removed on API server. ([#97980](https://github.com/kubernetes/kubernetes/pull/97980), [@SergeyKanzhelev](https://github.com/SergeyKanzhelev)) [SIG Node]
- Fix to recover CSI volumes from certain dangling attachments ([#96617](https://github.com/kubernetes/kubernetes/pull/96617), [@yuga711](https://github.com/yuga711)) [SIG Apps and Storage]
- Fix: azure file latency issue for metadata-heavy workloads ([#97082](https://github.com/kubernetes/kubernetes/pull/97082), [@andyzhangx](https://github.com/andyzhangx)) [SIG Cloud Provider and Storage]
- Fixed Cinder volume IDs on OpenStack Train ([#96673](https://github.com/kubernetes/kubernetes/pull/96673), [@jsafrane](https://github.com/jsafrane)) [SIG Cloud Provider]
- Fixed FibreChannel volume plugin corrupting filesystems on detach of multipath volumes. ([#97013](https://github.com/kubernetes/kubernetes/pull/97013), [@jsafrane](https://github.com/jsafrane)) [SIG Storage]
- Fixed a bug in kubelet that will saturate CPU utilization after containerd got restarted. ([#97174](https://github.com/kubernetes/kubernetes/pull/97174), [@hanlins](https://github.com/hanlins)) [SIG Node]
- Fixed bug in CPUManager with race on container map access ([#97427](https://github.com/kubernetes/kubernetes/pull/97427), [@klueska](https://github.com/klueska)) [SIG Node]
- Fixed cleanup of block devices when /var/lib/kubelet is a symlink. ([#96889](https://github.com/kubernetes/kubernetes/pull/96889), [@jsafrane](https://github.com/jsafrane)) [SIG Storage]
- GCE Internal LoadBalancer sync loop will now release the ILB IP address upon sync failure. An error in ILB forwarding rule creation will no longer leak IP addresses. ([#97740](https://github.com/kubernetes/kubernetes/pull/97740), [@prameshj](https://github.com/prameshj)) [SIG Cloud Provider and Network]
- Ignore update pod with no new images in alwaysPullImages admission controller ([#96668](https://github.com/kubernetes/kubernetes/pull/96668), [@pacoxu](https://github.com/pacoxu)) [SIG Apps, Auth and Node]
- Kubeadm now installs version 3.4.13 of etcd when creating a cluster with v1.19 ([#97244](https://github.com/kubernetes/kubernetes/pull/97244), [@pacoxu](https://github.com/pacoxu)) [SIG Cluster Lifecycle]
- Kubeadm: avoid detection of the container runtime for commands that do not need it ([#97625](https://github.com/kubernetes/kubernetes/pull/97625), [@pacoxu](https://github.com/pacoxu)) [SIG Cluster Lifecycle]
- Kubeadm: fix a bug in the host memory detection code on 32bit Linux platforms ([#97403](https://github.com/kubernetes/kubernetes/pull/97403), [@abelbarrera15](https://github.com/abelbarrera15)) [SIG Cluster Lifecycle]
- Kubeadm: fix a bug where "kubeadm upgrade" commands can fail if CoreDNS v1.8.0 is installed. ([#97919](https://github.com/kubernetes/kubernetes/pull/97919), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle]
- Performance regression [#97685](https://github.com/kubernetes/kubernetes/issues/97685) has been fixed. ([#97860](https://github.com/kubernetes/kubernetes/pull/97860), [@MikeSpreitzer](https://github.com/MikeSpreitzer)) [SIG API Machinery]
- Remove deprecated --cleanup-ipvs flag of kube-proxy, and make --cleanup flag always to flush IPVS ([#97336](https://github.com/kubernetes/kubernetes/pull/97336), [@maaoBit](https://github.com/maaoBit)) [SIG Network]
- The current version of the container image publicly exposed IP serving a /metrics endpoint to the Internet. The new version of the container image serves /metrics endpoint on a different port. ([#97621](https://github.com/kubernetes/kubernetes/pull/97621), [@vbannai](https://github.com/vbannai)) [SIG Cloud Provider]
- Use force unmount for NFS volumes if regular mount fails after 1 minute timeout ([#96844](https://github.com/kubernetes/kubernetes/pull/96844), [@gnufied](https://github.com/gnufied)) [SIG Storage]
- Users will see increase in time for deletion of pods and also guarantee that removal of pod from api server  would mean deletion of all the resources from container runtime. ([#92817](https://github.com/kubernetes/kubernetes/pull/92817), [@kmala](https://github.com/kmala)) [SIG Node]
- Using exec auth plugins with kubectl no longer results in warnings about constructing many client instances from the same exec auth config. ([#97857](https://github.com/kubernetes/kubernetes/pull/97857), [@liggitt](https://github.com/liggitt)) [SIG API Machinery and Auth]
- Warning about using a deprecated volume plugin is logged only once. ([#96751](https://github.com/kubernetes/kubernetes/pull/96751), [@jsafrane](https://github.com/jsafrane)) [SIG Storage]

### Other (Cleanup or Flake)

- Bump github.com/Azure/go-autorest/autorest to v0.11.12 ([#97033](https://github.com/kubernetes/kubernetes/pull/97033), [@patrickshan](https://github.com/patrickshan)) [SIG API Machinery, CLI, Cloud Provider and Cluster Lifecycle]
- Delete deprecated mixed protocol annotation ([#97096](https://github.com/kubernetes/kubernetes/pull/97096), [@nilo19](https://github.com/nilo19)) [SIG Cloud Provider]
- Kube-proxy: Traffic from the cluster directed to ExternalIPs is always sent directly to the Service. ([#96296](https://github.com/kubernetes/kubernetes/pull/96296), [@aojea](https://github.com/aojea)) [SIG Network and Testing]
- Kubeadm: fix a whitespace issue in the output of the "kubeadm join" command shown as the output of "kubeadm init" and "kubeadm token create --print-join-command" ([#97413](https://github.com/kubernetes/kubernetes/pull/97413), [@SataQiu](https://github.com/SataQiu)) [SIG Cluster Lifecycle]
- Kubeadm: improve the error messaging when the user provides an invalid discovery token CA certificate hash. ([#97290](https://github.com/kubernetes/kubernetes/pull/97290), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle]
- Migrate log messages in pkg/scheduler/{scheduler.go,factory.go} to structured logging ([#97509](https://github.com/kubernetes/kubernetes/pull/97509), [@aldudko](https://github.com/aldudko)) [SIG Scheduling]
- Migrate proxy/iptables/proxier.go logs to structured logging ([#97678](https://github.com/kubernetes/kubernetes/pull/97678), [@JornShen](https://github.com/JornShen)) [SIG Network]
- Migrate some scheduler log messages to structured logging ([#97349](https://github.com/kubernetes/kubernetes/pull/97349), [@aldudko](https://github.com/aldudko)) [SIG Scheduling]
- NONE ([#97167](https://github.com/kubernetes/kubernetes/pull/97167), [@geegeea](https://github.com/geegeea)) [SIG Node]
- NetworkPolicy validation framework optimizations for rapidly verifying CNI's work correctly across several pods and namespaces ([#91592](https://github.com/kubernetes/kubernetes/pull/91592), [@jayunit100](https://github.com/jayunit100)) [SIG Network, Storage and Testing]
- Official support to build kubernetes with docker-machine / remote docker is removed. This change does not affect building kubernetes with docker locally. ([#97618](https://github.com/kubernetes/kubernetes/pull/97618), [@jherrera123](https://github.com/jherrera123)) [SIG Release and Testing]
- Scheduler plugin validation now provides all errors detected instead of the first one. ([#96745](https://github.com/kubernetes/kubernetes/pull/96745), [@lingsamuel](https://github.com/lingsamuel)) [SIG Node, Scheduling and Testing]
- Storage related e2e testsuite redesign & cleanup ([#96573](https://github.com/kubernetes/kubernetes/pull/96573), [@Jiawei0227](https://github.com/Jiawei0227)) [SIG Storage and Testing]
- The OIDC authenticator no longer waits 10 seconds before attempting to fetch the metadata required to verify tokens. ([#97693](https://github.com/kubernetes/kubernetes/pull/97693), [@enj](https://github.com/enj)) [SIG API Machinery and Auth]
- The `AttachVolumeLimit` feature gate that is GA since v1.17 is now removed. ([#96539](https://github.com/kubernetes/kubernetes/pull/96539), [@ialidzhikov](https://github.com/ialidzhikov)) [SIG Storage]
- The `CSINodeInfo` feature gate that is GA since v1.17 is unconditionally enabled, and can no longer be specified via the `--feature-gates` argument. ([#96561](https://github.com/kubernetes/kubernetes/pull/96561), [@ialidzhikov](https://github.com/ialidzhikov)) [SIG Apps, Auth, Scheduling, Storage and Testing]
- The deprecated feature gates `RotateKubeletClientCertificate`, `AttachVolumeLimit`, `VolumePVCDataSource` and `EvenPodsSpread` are now unconditionally enabled and can no longer be specified in component invocations. ([#97306](https://github.com/kubernetes/kubernetes/pull/97306), [@gavinfish](https://github.com/gavinfish)) [SIG Node, Scheduling and Storage]
- `ServiceNodeExclusion`, `NodeDisruptionExclusion` and `LegacyNodeRoleBehavior`(locked to false) features have been promoted to GA. 
  To prevent control plane nodes being added to load balancers automatically, upgrade users need to add "node.kubernetes.io/exclude-from-external-load-balancers"  label to control plane nodes. ([#97543](https://github.com/kubernetes/kubernetes/pull/97543), [@pacoxu](https://github.com/pacoxu)) [SIG API Machinery, Apps, Cloud Provider and Network]

### Uncategorized

- Adding Brazilian Portuguese translation for kubectl ([#61595](https://github.com/kubernetes/kubernetes/pull/61595), [@cpanato](https://github.com/cpanato)) [SIG CLI]

## Dependencies

### Added
_Nothing has changed._

### Changed
- github.com/Azure/go-autorest/autorest: [v0.11.1 → v0.11.12](https://github.com/Azure/go-autorest/autorest/compare/v0.11.1...v0.11.12)
- github.com/coredns/corefile-migration: [v1.0.10 → v1.0.11](https://github.com/coredns/corefile-migration/compare/v1.0.10...v1.0.11)
- github.com/golang/mock: [v1.4.1 → v1.4.4](https://github.com/golang/mock/compare/v1.4.1...v1.4.4)
- github.com/google/cadvisor: [v0.38.5 → v0.38.6](https://github.com/google/cadvisor/compare/v0.38.5...v0.38.6)
- github.com/heketi/heketi: [c2e2a4a → v10.2.0+incompatible](https://github.com/heketi/heketi/compare/c2e2a4a...v10.2.0)
- github.com/miekg/dns: [v1.1.4 → v1.1.35](https://github.com/miekg/dns/compare/v1.1.4...v1.1.35)
- k8s.io/system-validators: v1.2.0 → v1.3.0

### Removed
- rsc.io/quote/v3: v3.1.0
- rsc.io/sampler: v1.3.0