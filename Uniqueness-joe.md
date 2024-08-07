The uniqueness of MAC addresses stems from the combination of two components: the Organizationally Unique Identifier (OUI) and the device-specific identifier. Let's break down how uniqueness is achieved:

### 1. Organizationally Unique Identifier (OUI):

- **What is OUI?**
  - The first 24 bits (the first three pairs or six hexadecimal digits) of a MAC address represent the Organizationally Unique Identifier (OUI). This identifier is assigned to manufacturers or vendors by the IEEE (Institute of Electrical and Electronics Engineers).

- **Example:**
  - Suppose the OUI for a particular manufacturer is `00:1A:2B`. This means that all devices manufactured by this company will have MAC addresses starting with these three pairs.


### 2. Device-Specific Identifier:

- **What is Device-Specific Identifier?**
  - The remaining 24 bits (the last three pairs or six hexadecimal digits) of the MAC address are assigned by the manufacturer to uniquely identify each network interface card (NIC) they produce.

- **Example:**
  - Continuing with the example OUI `00:1A:2B`, a specific device from this manufacturer might have a MAC address like `00:1A:2B:3C:4D:5E`, where `3C:4D:5E` is the unique identifier assigned to that particular NIC.

### Uniqueness Example:

- **Scenario:**
  - Two different manufacturers, Manufacturer A and Manufacturer B, both have OUIs assigned by the IEEE. Devices from each manufacturer use their respective OUIs and unique device-specific identifiers.

- **Examples:**
  - Manufacturer A's devices might have MAC addresses like `AA:BB:CC:12:34:56`.
  - Manufacturer B's devices might have MAC addresses like `DD:EE:FF:78:90:AB`.

- **Conclusion:**
  - Due to the combination of unique OUIs and device-specific identifiers, the likelihood of two devices from different manufacturers having the exact same MAC address is extremely low. This uniqueness is what allows network devices to be identified globally based on their MAC addresses.

It's important to note that while MAC addresses are designed to be globally unique, there are cases where certain devices or network administrators may manually set or "spoof" MAC addresses. Additionally, virtualization technologies and other network configurations can introduce complexities, but the principles of OUI-based uniqueness still hold in most scenarios.
