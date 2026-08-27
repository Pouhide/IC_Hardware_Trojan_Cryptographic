## Golden Model

The original SHA-256 RTL implementation from the secworks/sha256 repository
was synthesized using AMD Vivado 2025.2.

### Target Device

- Family: Artix-7
- Device: xc7a200tfbg484-3
- Tool: Vivado 2025.2

### Synthesis Results

| Resource | Used |
|---|---:|
| Slice LUTs | 1993 |
| LUT as Logic | 1993 |
| LUT as Memory | 0 |
| Slice Registers | 1830 |
| BRAM | 0 |
| DSP | 0 |
| F7 Muxes | 159 |
| F8 Muxes | 30 |

### Main Area Metrics

| Metric | Value |
|---|---:|
| LUTs | 1993 |
| Flip-Flops / Registers | 1830 |
| BRAM | 0 |
| DSP | 0 |

### Power Estimation

| Metric | Power |
|---|---:|
| Total On-Chip Power | 8.805 W |
| Dynamic Power | 8.623 W |
| Device Static Power | 0.182 W |
| Signals | 4.505 W |
| Logic | 3.212 W |
| I/O | 0.905 W |

The power report was generated from the implemented design using
Vivado's default switching activity assumptions.