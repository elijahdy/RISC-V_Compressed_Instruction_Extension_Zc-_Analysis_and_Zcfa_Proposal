The embedded processor market is larger than ever before. This growth necessi-
tates innovation in task-specific processor architectures. RISC-V is an open source
instruction-set architecture that has gained traction in recent years, now even compet-
ing with ARM, which has long reigned as the common choice for an embedded ISA.
RISC-V’s recent success is underpinned by its ethos of "bespoke" configurability for
any system. This manifests itself as a wide range of possible extensions, each of which
implement some new functionality. One of these functionalities is code compression
for reduced memory and power consumption. For years, there was only one extension
which implemented code compression, the standard RISC-V C extension, commonly
referred to as RVC. In 2023, a new collection of code compression extensions, all
prefixed with Zc, were ratified. These provide further code size optimisations and in-
creased configurability. In this project, I attempt to analyse the compression impact
of each of these extensions, and provide insight on which one is best suited to various
application types. I also propose additions to RISC-V for improved compression of
floating point intensive applications.