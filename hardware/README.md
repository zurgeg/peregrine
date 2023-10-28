---
description: Our old friend
---

# The AES engine

The AES engine handles encryption and decryption with AES128-CBC. It consists of 5 registers, `AES_CTRL`, `AES_SRC`, `AES_DEST`, `AES_KEY`, and finally `AES_IV`. Writing 1 to bit 1 of `AES_CTRL` triggers the engine's activation.

It is only accessible to Starlet.
