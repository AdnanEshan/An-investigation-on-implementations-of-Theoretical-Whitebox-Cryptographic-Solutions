Whitebox cryptography addresses the challenge of securing cryptographic keys and algorithms in situations where attackers have complete visibility into the internal workings of a system. This approach is particularly crucial in scenarios where the code execution environment is not fully trusted.

Untrusted Environments: Whitebox cryptography provides a defense mechanism in situations where cryptographic implementations must operate in untrusted environments, safeguarding keys even when the internal details are exposed.

Resistance to Reverse Engineering: The techniques employed in white-box cryptography make it considerably more difficult for adversaries to reverse engineer cryptographic algorithms, enhancing the overall resilience against unauthorized access.

Application Security: In applications such as mobile banking, digital rights management (DRM), or secure messaging, where code execution environments may be susceptible to various attacks, whitebox cryptography plays a pivotal role in fortifying the security of cryptographic operations.

Implemented Modes of AES 128-bits
ECB

CTR

C++ Header Files Overview
1. structure.h
Description: This comprehensive header file encapsulates the foundational functions of the Advanced Encryption Standard (AES) algorithm. It not only includes the core operations required for encryption and decryption but also incorporates vital tables such as the SBox and MixColumn.

Purpose: The primary objective of structure.h is to provide a modular and organized structure for implementing key AES operations. By bundling fundamental functionalities and tables together, it ensures a clean and maintainable codebase.

2. table.h
Description: table.h is designed to enhance the efficiency of the AES algorithm by introducing a mechanism for table lookups instead of direct operations. This header file specifically generates and manages crucial tables like the TBox, TyiTable, and XorTable.

Purpose: The purpose of this file is to optimize the execution of AES operations by utilizing precomputed tables. This approach not only accelerates key computations but also simplifies the overall algorithm's implementation.

3. encoding.h
Description: encoding.h plays a pivotal role in the AES implementation by housing essential functions for bijection in both internal and external encoding. These functions are crucial for transforming data during various stages of the algorithm.

Purpose: By encapsulating bijection functions in encoding.h, this header file enhances code readability and maintainability. It ensures that the encoding processes, both internal and external, are clearly defined and separated, contributing to a more comprehensible and modular AES implementation.

Note: It is imperative to include these header files appropriately and leverage their functionalities within your broader AES implementation for a robust and efficient cryptographic solution.
