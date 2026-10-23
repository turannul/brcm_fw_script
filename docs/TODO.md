# TODO

- [X] Gather Wi‑Fi/Bluetooth firmware from macOS and install to ESP (external first, internal fallback).
- [x] Implement/Verify PCIe Bluetooth firmware installation for BCM4377 cards (hci_bcm4377).
- [?] Add UART Bluetooth firmware conversion (macOS *.hex → Linux *.hcd) and driver reload for BCM4364/4355 cards.
- [ ] Test script on target hardware; verify Wi‑Fi and Bluetooth checkboxes in SupportedCards.md.
- [?] Decide on final language (Bash vs Python) after UART support is functional.
- [x] Keep original brcm_fw.sh unchanged; all modifications in brcm_fw_v2.sh only.
- [ ] Create pkgbuild
- [ ] Distribute via repo.
- [ ] Test on Live 
- [ ] Profit?
