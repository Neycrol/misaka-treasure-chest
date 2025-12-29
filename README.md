# Misaka Treasure Chest

WARNING: CPU-SPECIFIC BUILDS

Packages are built for a specific CPU target and will crash on machines that do not support the same ISA.
Do not use this repo unless your CPU matches (or exceeds) the target below.

Target details:
- CPU model: 12th Gen Intel(R) Core(TM) i9-12900HX
- GCC/Clang: -march=alderlake -mtune=alderlake
- ISA flags: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb ssbd ibrs ibpb stibp ibrs_enhanced tpr_shadow flexpriority ept vpid ept_ad fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb intel_pt sha_ni xsaveopt xsavec xgetbv1 xsaves split_lock_detect user_shstk avx_vnni dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp hwp_pkg_req hfi vnmi umip pku ospke waitpkg gfni vaes vpclmulqdq rdpid movdiri movdir64b fsrm md_clear serialize arch_lbr ibt flush_l1d arch_capabilities

Binary package repository for Build Factory packages.

Pacman config (raw GitHub):

[buildfactory]
SigLevel = Optional TrustAll
Server = https://raw.githubusercontent.com/Neycrol/misaka-treasure-chest/main/repo

Notes:
- Small packages are built by GitHub Actions from the source PKGBUILD repo.
- Heavy packages are built locally or on a self-hosted runner and uploaded into repo/.
