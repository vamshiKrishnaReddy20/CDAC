# [counter1] counter1

| Property | Value |
|----------|-------|
| **Difficulty** | Medium |
| **Category** | N/A |
| **Language** | SystemVerilog |
| **Solved** | March 31, 2026 |
| **Platform** | [LeetSilicon](https://leetsilicon.com/?view=question&question=counter1) |

## Module Interface

```systemverilog
module sync_counter #(
  parameter int unsigned N = 8,
  parameter logic [N-1:0] RESET_VALUE = '0
) (
  input  logic         clk,
  input  logic         rst_n,    // TODO: define active-low vs active-high reset
  input  logic         enable,
  output logic [N-1:0] count
);
```

## Files

| File | Type |
|------|------|
| `rtl/design.sv` | RTL Design |
| `dv/testbench.sv` | Testbench |

## Simulation Results

| Metric | Value |
|--------|-------|
| **Status** | ✅ Passed |
| **Tests** | 7 passed, 0 failed |
| **Max Cycles** | 10 |
| **Lint Warnings** | 0 |
| **Timestamp** | 2026-03-30T20:34:04.136Z |

## Waveforms

> View simulation waveforms on [LeetSilicon](https://leetsilicon.com/?view=question&question=counter1) → Run Code → Waveform tab

---
*Auto-synced by [SiliconHub](https://github.com) · March 31, 2026*
