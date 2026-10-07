## Golden Model

The original FalconSign SamplerZ RTL implementation from the
YiOuyang1/FalconSign repository was synthesized using AMD Vivado 2025.2.

### Target Device

- Family: Artix-7
- Device: xc7a200tfbg484-3
- Tool: Vivado 2025.2
- Top Module: samplerz

### Synthesis Results

| Resource | Used |
|---|---:|
| Slice LUTs | 14652 |
| LUT as Logic | 14652 |
| LUT as Memory | 0 |
| Slice Registers | 10505 |
| Flip-Flops | 10505 |
| Latches | 0 |
| BRAM | 0 |
| DSP | 80 |
| F7 Muxes | 561 |
| F8 Muxes | 6 |

### Main Area Metrics

| Metric | Value |
|---|---:|
| LUTs | 14652 |
| Flip-Flops / Registers | 10505 |
| BRAM | 0 |
| DSP | 80 |

### Power Estimation

| Metric | Power |
|---|---:|
| Total On-Chip Power | 397.990 W |
| Dynamic Power | 396.315 W |
| Device Static Power | 1.674 W |
| Signals | 163.195 W |
| Logic | 139.395 W |
| DSP | 51.062 W |
| I/O | 42.663 W |

The power report was generated from the synthesized design using
Vivado's default switching activity assumptions.

The power estimation confidence level reported by Vivado was **Low**.

### Notes

The SamplerZ module was synthesized using the floating-point IP
configurations described by the original FalconSign project.

The required Floating-Point IP cores were recreated in Vivado 2025.2
while the original SamplerZ RTL source code was kept unchanged.

The synthesized top-level design requires more I/O ports than available
on the selected Artix-7 device.