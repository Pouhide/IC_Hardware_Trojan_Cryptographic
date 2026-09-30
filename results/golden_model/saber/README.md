## Golden Model

The original SABER RTL implementation from the sujoyetc/SABER_HW repository
was synthesized using AMD Vivado 2025.2.

### Target Device

- Family: Artix-7
- Device: xc7a200tfbg484-3
- Tool: Vivado 2025.2
- Top Module: ComputeCore3

### Synthesis Results

| Resource | Used |
|---|---:|
| Slice LUTs | 23091 |
| LUT as Logic | 23091 |
| LUT as Memory | 0 |
| Slice Registers | 9756 |
| Flip-Flops | 9756 |
| Latches | 0 |
| BRAM | 2 |
| DSP | 0 |
| F7 Muxes | 1 |
| F8 Muxes | 0 |

### Main Area Metrics

| Metric | Value |
|---|---:|
| LUTs | 23091 |
| Flip-Flops / Registers | 9756 |
| BRAM | 2 |
| DSP | 0 |

### Power Estimation

| Metric | Power |
|---|---:|
| Total On-Chip Power | 277.920 W |
| Dynamic Power | 276.245 W |
| Device Static Power | 1.675 W |
| Signals | 105.252 W |
| Logic | 108.742 W |
| BRAM | 0.348 W |
| I/O | 61.903 W |

The power report was generated from the synthesized design using
Vivado's default switching activity assumptions.

### Notes

The legacy `BRAM64_1024` Block Memory Generator IP was upgraded for
compatibility with AMD Vivado 2025.2.