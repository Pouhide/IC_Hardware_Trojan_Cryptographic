## Golden Model

The original KeyExchangeFPGA RTL implementation from the borabarduk/KeyExchangeFPGA repository
was synthesized using AMD Vivado 2025.2

### Target Device

- Family: Artix-7
- Device: xc7a200tfbg484-3
- Tool: Vivado 2025.2
- Top Module: HLSM

### Synthesis Results

| Resource | Used |
|---|---:|
| Slice LUTs | 22 |
| LUT as Logic | 22 |
| LUT as Memory | 0 |
| Slice Registers | 12 |
| Flip-Flops | 8 |
| Latches | 4 |
| BRAM | 0 |
| DSP | 0 |

### Main Area Metrics

| Metric | Value |
|---|---:|
| LUTs | 22 |
| Flip-Flops / Registers | 12 |
| BRAM | 0 |
| DSP | 0 |

### Power Estimation

| Metric | Power |
|---|---:|
| Total On-Chip Power | 3.796 W |
| Dynamic Power | 3.649 W |
| Device Static Power | 0.147 W |
| Signals | 0.167 W |
| Logic | 0.144 W |
| I/O | 3.338 W |

The power report was generated from the synthesized design using
Vivado's default switching activity assumptions.

### Notes

The original RTL code was kept without modifications. Vivado reported synthesis
warnings, including port width mismatches, unreachable states, inferred latches,
and removal of unused sequential elements.