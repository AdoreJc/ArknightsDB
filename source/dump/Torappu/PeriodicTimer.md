# PeriodicTimer

**Namespace:** `Torappu`


## Fields

- `FP m_periodTime`

- `FP m_remainingTime`


## Properties

- `Boolean isValid`

- `FP remainingTime`

- `FP periodTime`

- `FP progress`


## Methods

- `Boolean get_isValid()`

- `FP get_remainingTime()`

- `FP get_periodTime()`

- `FP get_progress()`

- `Void Reset(Boolean)`

- `Void Reset(FP, Boolean)`

- `Void ResetButKeepPastTime(FP)`

- `Void ResetButKeepProgress(FP)`

- `Void MarkInvalid()`

- `Void SetProgress(FP)`

- `Void SetRemainingTime(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PeriodicTimer
{
	protected FP m_periodTime; // 0x10
	protected FP m_remainingTime; // 0x18

	public Boolean isValid { get; }
	public virtual Boolean isReady { get; }
	public FP remainingTime { get; }
	public FP periodTime { get; }
	public FP progress { get; }

	// RVA: 0x3103064 VA: 0x759571b064
	public Boolean get_isValid() { }
	// RVA: 0x31030fc VA: 0x759571b0fc
	public virtual Boolean get_isReady() { }
	// RVA: 0x3103158 VA: 0x759571b158
	public FP get_remainingTime() { }
	// RVA: 0x3103160 VA: 0x759571b160
	public FP get_periodTime() { }
	// RVA: 0x3103168 VA: 0x759571b168
	public FP get_progress() { }
	// RVA: 0x3103270 VA: 0x759571b270
	public Void .ctor() { }
	// RVA: 0x31032d0 VA: 0x759571b2d0
	public Void .ctor(FP periodTime) { }
	// RVA: 0x310334c VA: 0x759571b34c
	public Void Reset(Boolean waitFirstPeriod) { }
	// RVA: 0x31033c4 VA: 0x759571b3c4
	public Void Reset(FP newPeriod, Boolean waitFirstPeriod) { }
	// RVA: 0x3103478 VA: 0x759571b478
	public Void ResetButKeepPastTime(FP newPeriod) { }
	// RVA: 0x3103544 VA: 0x759571b544
	public Void ResetButKeepProgress(FP newPeriod) { }
	// RVA: 0x3103630 VA: 0x759571b630
	public Void MarkInvalid() { }
	// RVA: 0x3103570 VA: 0x759571b570
	public Void SetProgress(FP progress) { }
	// RVA: 0x3103690 VA: 0x759571b690
	public Void SetRemainingTime(FP remainingTime) { }
	// RVA: 0x3103704 VA: 0x759571b704
	public virtual Boolean Update(FP deltaTime) { }
	// RVA: 0x31037c8 VA: 0x759571b7c8
	public virtual Boolean Update(FP deltaTime, Boolean ignoreSmallEps) { }
	// RVA: 0x3103900 VA: 0x759571b900
	public virtual Boolean Next() { }
}
```