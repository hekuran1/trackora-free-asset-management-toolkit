# QR Asset Labeling Guide

## 1. What to encode
Encode a **short, stable identifier** (for example the asset tag `IT-0001`) or a URL ending in it (`https://assets.example.com/a/IT-0001`). Do not encode details that change, such as assignee or location. Look those up in your register.

## 2. Tag numbering
- Sequential with a category prefix: `IT-0001`, `FAC-0001`, `AV-0001`.
- Never reuse a tag, even for retired assets.
- Print the human-readable tag beside the QR code in case the code is damaged.

## 3. Label hardware and size
- Durable polyester or vinyl labels with permanent adhesive; tamper-evident for high-value items.
- Minimum QR size of roughly 20 x 20 mm for handheld scanning; larger for racks or ceilings.
- Use error correction level M or Q, black on white, with a quiet margin.

## 4. Placement
- Same spot on each asset type (for example underside-left of laptops) so staff know where to look.
- Avoid heat, heavy-handling zones and surfaces cleaned with solvents.
- Add a second label on large items.

## 5. Generating labels in bulk
1. Export tags from your register.
2. Generate QR images with any QR library or generator (for example the free `qrencode` CLI or Python `qrcode`).
3. Merge onto a label sheet template and print a test page first.

## 6. Scanning workflow
Scan to open the record, then check out, check in, move or audit. Scan every asset during audits and compare against the register.
