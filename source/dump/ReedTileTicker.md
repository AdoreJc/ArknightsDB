# ReedTileTicker

**Namespace:** ` `


## Fields

- `Boolean isValid`

- `FP m_maxDuration`

- `FP m_curDuration`


## Properties

- `Boolean isReady`

- `FP remainProcess`


## Methods

- `Boolean get_isReady()`

- `FP get_remainProcess()`

- `Void OnTick(FP)`

- `Void Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ReedTileTicker
{
	public Boolean isValid; // 0x10
	private FP m_maxDuration; // 0x18
	private FP m_curDuration; // 0x20

	public Boolean isReady { get; }
	public FP remainProcess { get; }

	// RVA: 0x1b28fb4 VA: 0x7594140fb4
	public Boolean get_isReady() { }
	// RVA: 0x1b29918 VA: 0x7594141918
	public FP get_remainProcess() { }
	// RVA: 0x1b2873c VA: 0x759414073c
	public Void .ctor(Blackboard blackboard, String durationKey, Boolean isValid) { }
	// RVA: 0x1b28f40 VA: 0x7594140f40
	public Void OnTick(FP deltaTIme) { }
	// RVA: 0x1b2947c VA: 0x759414147c
	public Void Reset() { }
}
```