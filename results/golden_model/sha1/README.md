## Golden Model

The original SHA-1 RTL implementation from the secworks/sha1 repository
was synthesized using AMD Vivado 2025.2.

### Target Device

- Family: Artix-7
- Device: xc7a200tfbg484-3
- Tool: Vivado 2025.2

### Synthesis Results

| Resource | Used |
|---|---:|
| Slice LUTs | 1551 |
| LUT as Logic | 1551 |
| LUT as Memory | 0 |
| Slice Registers | 1531 |
| BRAM | 0 |
| DSP | 0 |
| F7 Muxes | 126 |
| F8 Muxes | 47 |

### Main Area Metrics

| Metric | Value |
|---|---:|
| LUTs | 1551 |
| Flip-Flops / Registers | 1531 |
| BRAM | 0 |
| DSP | 0 |

### Power Estimation

| Metric | Power |
|---|---:|
| Total On-Chip Power | 3.284 W |
| Dynamic Power | 3.140 W |
| Device Static Power | 0.144 W |
| Signals | 0.886 W |
| Logic | 0.988 W |
| I/O | 1.266 W |

The power report was generated from the synthesized design using
Vivado's default switching activity assumptions.