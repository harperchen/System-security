# System-security

## Kernel Fuzzing
1. [[CCS'21] SyzGen: Automated Generation of Syscall Specification of Closed-Source macOS Drivers](https://www.cs.ucr.edu/~zhiyunq/pub/ccs21_syzgen.pdf)
2. [[Oakland'21] NTFUZZ: Enabling Type-Aware Kernel Fuzzing on Windows with Static Binary Analysis](https://softsec.kaist.ac.kr/~jschoi/data/oakland2021.pdf)
3. [[SOSP'21] HEALER: Relation Learning Guided Kernel Fuzzing]()
4. [[SOSP'21] Snowboard: Finding Kernel Concurrency Bugs through Systematic Inter-thread Communication Analysis]()

## Kernel Bug Detection

### Data Race
1. [[Oakland'20] KRACE: Data Race Fuzzing for Kernel File Systems](https://taesoo.kim/pubs/2020/xu:krace.pdf)
2. [[Oakland'19] Razzer: Finding Kernel Race Bugs through Fuzzing](https://ieeexplore.ieee.org/abstract/document/8835326)

### Double-Fetch

1. [[Security'19] Precise and Scalable Detection of Double-Fetch Bugs in OS Kernels](https://www-users.cse.umn.edu/~kjlu/papers/deadline.pdf)
2. [[Security'17] How Double-Fetch Situations turn into DoubleFetch Vulnerabilities: A Study of Double Fetches in the Linux Kernel](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-wang.pdf)

### Missing check

1. [[Security'19] Detecting Missing-Check Bugs via Semantic- and Context-Aware Criticalness and Constraints Inferences](https://www-users.cse.umn.edu/~kjlu/papers/crix.pdf)

### Use Before Initialization

1. [[ESEC/FSE'20] UBITect: a precise and scalable method to detect use-before-initialization bugs in Linux kernel](https://dl.acm.org/doi/pdf/10.1145/3368089.3409686)
2. [[CCS'16] UniSan: Proactive Kernel Memory Initialization to Eliminate Data Leakages](https://dl.acm.org/doi/10.1145/2976749.2978366)

### RefCount Bugs
1. [[Security'21] Detecting Kernel Refcount Bugs with Two-Dimensional Consistency Checking](https://www.usenix.org/conference/usenixsecurity21/presentation/tan)

### Misc.

1. [[Security'21] Static Detection of Unsafe DMA Accesses in Device Drivers](https://www.usenix.org/system/files/sec21-bai.pdf)
2. [[CCS'21] CPscan: Detecting Bugs Caused by Code Pruning in IoT Kernels]()
3. [[CCS'21] Statically Discovering High-Order Taint Style Vulnerabilities in OS Kernels](https://www.cs.ucr.edu/~zhiyunq/pub/ccs21_static_high_order.pdf)

## Kernel Bug Exploitation

### Data Race
1. [[Security'21] ExpRace: Exploiting Kernel Races through Raising Interrupts](https://www.usenix.org/conference/usenixsecurity21/presentation/lee-yoochan)


## Kernel Bug Repair

1. [[Security'21] An Investigation of the Android Kernel Patch Ecosystem](https://www.usenix.org/conference/usenixsecurity21/presentation/zhang-zheng)
2. [[Security'21] Preventing Use-After-Free Attacks with Fast Forward Allocation](https://www.usenix.org/conference/usenixsecurity21/presentation/wickman)

## Kernel Debloating

1. [[Security'21] SHARD: Fine-Grained Kernel Specialization with Context-Aware Hardening](https://www.usenix.org/conference/usenixsecurity21/presentation/abubakar)


## Hypervisor Fuzzing
1. [[Security'21] Nyx: Greybox Hypervisor Fuzzing using Fast Snapshots and Affine Types](https://www.usenix.org/conference/usenixsecurity21/presentation/schumilo)
2. [[CCS'21] Demons in the Shared Kernel: Abstract Resource Attacks Against OS-level Virtualization]()
3. [[CCS'21] V-SHUTTLE: Scalable and Semantics-Aware Hypervisor Fuzzing]()
4. [[Oakland'21] A Secure and Formally Verified Linux KVM Hypervisor]()
## Fuzzing
1. [[CCS'21] Same Coverage, Less Bloat: Accelerating Binary-only Fuzzing with Coverage-preserving Coverage-guided Tracing]()


## Interests
1. [PalmTree: Learning an Assembly Language Model for Instruction Embedding](https://arxiv.org/abs/2103.03809)
