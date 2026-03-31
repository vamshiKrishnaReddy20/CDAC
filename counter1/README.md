# [counter1] counter1

| Property | Value |
|----------|-------|
| **Language** | SystemVerilog |
| **Solved** | March 31, 2026 |
| **Platform** | [LeetSilicon](https://leetsilicon.com/?view=question&question=counter1) |

## Files

| File | Type |
|------|------|
| [`rtl/design.sv`](rtl/design.sv) | RTL Design |
| [`dv/testbench.sv`](dv/testbench.sv) | Testbench |

## Simulation Results

| Metric | Value |
|--------|-------|
| **Status** | ✅ Passed |
| **Tests** | 7 passed, 0 failed |
| **Max Cycles** | 10 |
| **Lint Warnings** | 0 |

## Waveforms

### Signal List (top → bottom in waveform)

| # | Signal | Hierarchy | Width | Value |
|---|--------|-----------|-------|-------|
| 1 | **`N`** | `TOP.tb.N` | [31:0] | 4h |
| 2 | **`clk`** | `TOP.tb.clk` | 1-bit | 0 |
| 3 | **`rst_n`** | `TOP.tb.rst_n` | 1-bit | 0 |
| 4 | **`enable`** | `TOP.tb.enable` | 1-bit | 0 |
| 5 | **`count`** | `TOP.tb.count` | [3:0] | 0h |
| 6 | **`p`** | `TOP.tb.p` | [31:0] | 0h |
| 7 | **`f`** | `TOP.tb.f` | [31:0] | 0h |
| 8 | **`N`** | `TOP.tb.dut.N` | [31:0] | 4h |
| 9 | **`RESET_VALUE`** | `TOP.tb.dut.RESET_VALUE` | [3:0] | 0h |
| 10 | **`clk`** | `TOP.tb.dut.clk` | 1-bit | 0 |
| 11 | **`rst_n`** | `TOP.tb.dut.rst_n` | 1-bit | 0 |
| 12 | **`enable`** | `TOP.tb.dut.enable` | 1-bit | 0 |
| 13 | **`count`** | `TOP.tb.dut.count` | [3:0] | 0h |

![Simulation Waveform](waveform.png)

---
*Auto-synced by [SiliconHub](https://github.com) · March 31, 2026*
