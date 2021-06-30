# Changes since 2021-06-16

## Changes in Analysis

- [#6466](https://github.com/AliceO2Group/AliceO2/pull/6466) 2021-06-24: Move MFT track labels to a separate table + some cleanups by [@nburmaso](https://github.com/nburmaso)
- [#6521](https://github.com/AliceO2Group/AliceO2/pull/6521) 2021-06-25: Include TMap.h (Root v6-24) by [@pzhristov](https://github.com/pzhristov)
- [#6527](https://github.com/AliceO2Group/AliceO2/pull/6527) 2021-06-25: Updated copyright headers in files omitted in the previous update by [@ihrivnac](https://github.com/ihrivnac)
- [#6503](https://github.com/AliceO2Group/AliceO2/pull/6503) 2021-06-25: adding meta data to aod merger by [@jgrosseo](https://github.com/jgrosseo)
- [#6520](https://github.com/AliceO2Group/AliceO2/pull/6520) 2021-06-27: Split J/ψ selector to ALICE 2 and 3 by [@vkucera](https://github.com/vkucera)
- [#6513](https://github.com/AliceO2Group/AliceO2/pull/6513) 2021-06-28: PWGPP: Enable all species by default by [@njacazio](https://github.com/njacazio)
- [#6538](https://github.com/AliceO2Group/AliceO2/pull/6538) 2021-06-28: Workarounds for fmt 8.0.0 by [@davidrohr](https://github.com/davidrohr)
- [#6523](https://github.com/AliceO2Group/AliceO2/pull/6523) 2021-06-28: correct names for mcparticle mother and daughter indices by [@jgrosseo](https://github.com/jgrosseo)
- [#6545](https://github.com/AliceO2Group/AliceO2/pull/6545) 2021-06-30: PWGHF: Add message for hyperloop tests by [@fgrosa](https://github.com/fgrosa)
## Changes in Common

- [#6490](https://github.com/AliceO2Group/AliceO2/pull/6490) 2021-06-22: DPL: provide level everywhere when mapping FairLogger to InfoLogger by [@ktf](https://github.com/ktf)
- [#6486](https://github.com/AliceO2Group/AliceO2/pull/6486) 2021-06-22: suppress overlaps check option in AlignParam::apply by [@shahor02](https://github.com/shahor02)
- [#6537](https://github.com/AliceO2Group/AliceO2/pull/6537) 2021-06-28: Add missing includes by [@davidrohr](https://github.com/davidrohr)
## Changes in DataFormats

- [#6471](https://github.com/AliceO2Group/AliceO2/pull/6471) 2021-06-21: Fix array out of bounds access in TOF clusterizer by [@davidrohr](https://github.com/davidrohr)
- [#6483](https://github.com/AliceO2Group/AliceO2/pull/6483) 2021-06-22: CPV missing TF handling by [@sevdokim](https://github.com/sevdokim)
- [#6486](https://github.com/AliceO2Group/AliceO2/pull/6486) 2021-06-22: suppress overlaps check option in AlignParam::apply by [@shahor02](https://github.com/shahor02)
- [#6527](https://github.com/AliceO2Group/AliceO2/pull/6527) 2021-06-25: Updated copyright headers in files omitted in the previous update by [@ihrivnac](https://github.com/ihrivnac)
- [#6533](https://github.com/AliceO2Group/AliceO2/pull/6533) 2021-06-29: TRD: Fix TRD digit method names by [@jolopezl](https://github.com/jolopezl)
## Changes in Detectors

- [#6464](https://github.com/AliceO2Group/AliceO2/pull/6464) 2021-06-20: Add MFT-specific fillDecodedDigits, use/reset ordering helper by [@shahor02](https://github.com/shahor02)
- [#6477](https://github.com/AliceO2Group/AliceO2/pull/6477) 2021-06-20: Fix typo in PVertexer debris cleanup by [@shahor02](https://github.com/shahor02)
- [#6469](https://github.com/AliceO2Group/AliceO2/pull/6469) 2021-06-20: Fix typo in the fmt::format by [@shahor02](https://github.com/shahor02)
- [#6467](https://github.com/AliceO2Group/AliceO2/pull/6467) 2021-06-20: trivial fix to suppress the snprintf warning by [@shahor02](https://github.com/shahor02)
- [#6471](https://github.com/AliceO2Group/AliceO2/pull/6471) 2021-06-21: Fix array out of bounds access in TOF clusterizer by [@davidrohr](https://github.com/davidrohr)
- [#6470](https://github.com/AliceO2Group/AliceO2/pull/6470) 2021-06-21: Fix invalid headers sent by TOF and add some protection in header parsing by [@davidrohr](https://github.com/davidrohr)
- [#6478](https://github.com/AliceO2Group/AliceO2/pull/6478) 2021-06-21: Fix missing ROOT dependencies (Headers were there, but typeinfo was not linked by [@davidrohr](https://github.com/davidrohr)
- [#6463](https://github.com/AliceO2Group/AliceO2/pull/6463) 2021-06-21: [O2-2401] Correction of variables initialization by [@frmanso](https://github.com/frmanso)
- [#6495](https://github.com/AliceO2Group/AliceO2/pull/6495) 2021-06-22: Bug fix: use correct index over neighbour boards by [@dstocco](https://github.com/dstocco)
- [#6488](https://github.com/AliceO2Group/AliceO2/pull/6488) 2021-06-22: CPV digi2raw must set triggered mode to write SOX by [@shahor02](https://github.com/shahor02)
- [#6483](https://github.com/AliceO2Group/AliceO2/pull/6483) 2021-06-22: CPV missing TF handling by [@sevdokim](https://github.com/sevdokim)
- [#6497](https://github.com/AliceO2Group/AliceO2/pull/6497) 2021-06-22: Do not use std::array in ConfigurableParam by [@shahor02](https://github.com/shahor02)
- [#6458](https://github.com/AliceO2Group/AliceO2/pull/6458) 2021-06-22: Raw: make the output directory creation more robust. by [@aphecetche](https://github.com/aphecetche)
- [#6501](https://github.com/AliceO2Group/AliceO2/pull/6501) 2021-06-22: ZDC Digits2Raw: labels are not guaranteed to be present by [@shahor02](https://github.com/shahor02)
- [#6481](https://github.com/AliceO2Group/AliceO2/pull/6481) 2021-06-22: inf. loop fixed; hwerror handling improved by [@peressounko](https://github.com/peressounko)
- [#6482](https://github.com/AliceO2Group/AliceO2/pull/6482) 2021-06-22: snprintf -> fmt::format to suppress warnings by [@shahor02](https://github.com/shahor02)
- [#6486](https://github.com/AliceO2Group/AliceO2/pull/6486) 2021-06-22: suppress overlaps check option in AlignParam::apply by [@shahor02](https://github.com/shahor02)
- [#6504](https://github.com/AliceO2Group/AliceO2/pull/6504) 2021-06-23: CPV: Never take ownership CCDB objects by [@shahor02](https://github.com/shahor02)
- [#6510](https://github.com/AliceO2Group/AliceO2/pull/6510) 2021-06-23: Updated g4config.in: by [@ihrivnac](https://github.com/ihrivnac)
- [#6506](https://github.com/AliceO2Group/AliceO2/pull/6506) 2021-06-23: make ccdb-url a ZDC device option, rather than global of w.flow by [@shahor02](https://github.com/shahor02)
- [#6466](https://github.com/AliceO2Group/AliceO2/pull/6466) 2021-06-24: Move MFT track labels to a separate table + some cleanups by [@nburmaso](https://github.com/nburmaso)
- [#6489](https://github.com/AliceO2Group/AliceO2/pull/6489) 2021-06-24: TPC: Add possibility to read StfBuilder files directly in raw reader by [@wiechula](https://github.com/wiechula)
- [#6525](https://github.com/AliceO2Group/AliceO2/pull/6525) 2021-06-25: Bug fix in computing angular position of step supports on IB Side C End Wheels by [@mario6829](https://github.com/mario6829)
- [#6505](https://github.com/AliceO2Group/AliceO2/pull/6505) 2021-06-25: Correction of the numbering of ts array by [@frmanso](https://github.com/frmanso)
- [#6527](https://github.com/AliceO2Group/AliceO2/pull/6527) 2021-06-25: Updated copyright headers in files omitted in the previous update by [@ihrivnac](https://github.com/ihrivnac)
- [#6518](https://github.com/AliceO2Group/AliceO2/pull/6518) 2021-06-27: fix for cpv clusterer by [@sevdokim](https://github.com/sevdokim)
- [#6514](https://github.com/AliceO2Group/AliceO2/pull/6514) 2021-06-27: swap HG/LG channels by [@peressounko](https://github.com/peressounko)
- [#6537](https://github.com/AliceO2Group/AliceO2/pull/6537) 2021-06-28: Add missing includes by [@davidrohr](https://github.com/davidrohr)
- [#6538](https://github.com/AliceO2Group/AliceO2/pull/6538) 2021-06-28: Workarounds for fmt 8.0.0 by [@davidrohr](https://github.com/davidrohr)
- [#6491](https://github.com/AliceO2Group/AliceO2/pull/6491) 2021-06-29: MCH: remove usage of to-be-banned #pragma once by [@aphecetche](https://github.com/aphecetche)
- [#6541](https://github.com/AliceO2Group/AliceO2/pull/6541) 2021-06-29: TPC: finalize trigger handling + unrelated fixes and improvements by [@wiechula](https://github.com/wiechula)
- [#6533](https://github.com/AliceO2Group/AliceO2/pull/6533) 2021-06-29: TRD: Fix TRD digit method names by [@jolopezl](https://github.com/jolopezl)
- [#6522](https://github.com/AliceO2Group/AliceO2/pull/6522) 2021-06-29: alignment of FT0 modules by [@AllaMaevskaya](https://github.com/AllaMaevskaya)
## Changes in Framework

- [#6468](https://github.com/AliceO2Group/AliceO2/pull/6468) 2021-06-21: Add virtual destructors to allow save casting to base class in web socket handling avoiding new / delete mismatch by [@davidrohr](https://github.com/davidrohr)
- [#6479](https://github.com/AliceO2Group/AliceO2/pull/6479) 2021-06-21: DPL: apparently memcpy(something, 0, 0) is UB by [@ktf](https://github.com/ktf)
- [#6470](https://github.com/AliceO2Group/AliceO2/pull/6470) 2021-06-21: Fix invalid headers sent by TOF and add some protection in header parsing by [@davidrohr](https://github.com/davidrohr)
- [#6490](https://github.com/AliceO2Group/AliceO2/pull/6490) 2021-06-22: DPL: provide level everywhere when mapping FairLogger to InfoLogger by [@ktf](https://github.com/ktf)
- [#6466](https://github.com/AliceO2Group/AliceO2/pull/6466) 2021-06-24: Move MFT track labels to a separate table + some cleanups by [@nburmaso](https://github.com/nburmaso)
- [#6524](https://github.com/AliceO2Group/AliceO2/pull/6524) 2021-06-27: DPL: add api to easily load and act on a plugin by [@ktf](https://github.com/ktf)
- [#6499](https://github.com/AliceO2Group/AliceO2/pull/6499) 2021-06-28: A new attempt to add an option to disable exception catching by [@davidrohr](https://github.com/davidrohr)
- [#6517](https://github.com/AliceO2Group/AliceO2/pull/6517) 2021-06-28: DPL: add code to enable multithreaded dispatch by [@ktf](https://github.com/ktf)
- [#6523](https://github.com/AliceO2Group/AliceO2/pull/6523) 2021-06-28: correct names for mcparticle mother and daughter indices by [@jgrosseo](https://github.com/jgrosseo)
## Changes in Steer

- [#6483](https://github.com/AliceO2Group/AliceO2/pull/6483) 2021-06-22: CPV missing TF handling by [@sevdokim](https://github.com/sevdokim)
## Changes in Utilities

- [#6542](https://github.com/AliceO2Group/AliceO2/pull/6542) 2021-06-29: Fixes for M1 by [@pzhristov](https://github.com/pzhristov)
