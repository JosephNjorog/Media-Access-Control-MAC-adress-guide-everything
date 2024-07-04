
### Organizationally Unique Identifier (OUI):

1. **Definition:**
   - The Organizationally Unique Identifier (OUI) is a 24-bit (3-byte) identifier assigned by the IEEE (Institute of Electrical and Electronics Engineers) to manufacturers, vendors, or other organizations producing network interface cards (NICs) or networking hardware.


2. **Structure:**
   - The OUI is part of the MAC address and occupies the first 24 bits (first three pairs of hexadecimal digits) of a standard 48-bit MAC address.

3. **Format:**
   - Expressed in hexadecimal notation, the OUI typically looks like `XX:XX:XX`, where each `X` represents a hexadecimal digit (0-9, A-F).

4. **Uniqueness:**
   - The OUI ensures uniqueness for devices produced by a specific organization. It serves as a globally recognized identifier for the manufacturer.

5. **Assignment Process:**
   - The IEEE assigns OUIs to organizations upon request. Manufacturers apply for and receive a unique OUI, allowing them to create MAC addresses for their devices.

6. **Publicly Available Database:**
   - The IEEE maintains a publicly available database of assigned OUIs. This database helps in identifying the manufacturer or vendor associated with a particular OUI.

7. **Example:**
   - Suppose a manufacturer receives the OUI `00:1A:2B`. Devices produced by this manufacturer would then have MAC addresses starting with `00:1A:2B`.

8. **Usage in Device Identification:**
   - The OUI is a crucial component for identifying the origin of network devices on a global scale. It allows network administrators and devices to recognize the manufacturer of a particular NIC based on its MAC address.

### Locally Administered vs. Globally Unique:

- **Globally Unique Addresses:**
  - The OUI in a globally unique address is assigned by the manufacturer and is registered with the IEEE. It provides a globally recognized identifier for the device.

- **Locally Administered Addresses:**
  - In a locally administered address, the OUI is still used, but the least significant bit of the first byte (bit 1 of the first hexadecimal digit) is set to `1`. This indicates that the address is locally administered and not registered with the IEEE.

Understanding the OUI is fundamental to network management, device identification, and troubleshooting, as it plays a crucial role in ensuring the uniqueness and origin of MAC addresses.
