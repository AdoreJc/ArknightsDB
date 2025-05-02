# PolluteTileData

**Namespace:** ` `


## Fields

- `PolluteAreaData m_area`

- `Int32 m_curPollute`

- `Int32 curFlushV`

- `Int32 extraTgtPollute`


## Properties

- `Int32 curPollute`

- `Int32 areaTgtPollute`


## Methods

- `Void set_curPollute(Int32)`

- `Int32 get_curPollute()`

- `Int32 get_areaTgtPollute()`

- `PolluteAreaData GetArea()`

- `Void SetArea(PolluteAreaData)`

- `Void SetInitPollute(Int32)`

- `Void VerifyCurPollute()`

- `Void AddAreaPolluteValue(Int32)`

- `Void Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PolluteTileData
{
	private PolluteAreaData m_area; // 0x10
	private Int32 m_curPollute; // 0x18
	public Int32 curFlushV; // 0x1c
	public Int32 extraTgtPollute; // 0x20

	public Int32 curPollute { get; set; }
	public Int32 areaTgtPollute { get; }

	// RVA: 0x406018c VA: 0x759667818c
	public Void set_curPollute(Int32 value) { }
	// RVA: 0x4060bc0 VA: 0x7596678bc0
	public Int32 get_curPollute() { }
	// RVA: 0x405e390 VA: 0x7596676390
	public Int32 get_areaTgtPollute() { }
	// RVA: 0x4060bc8 VA: 0x7596678bc8
	public PolluteAreaData GetArea() { }
	// RVA: 0x4060bd0 VA: 0x7596678bd0
	public Void SetArea(PolluteAreaData area) { }
	// RVA: 0x4060bd8 VA: 0x7596678bd8
	public Void SetInitPollute(Int32 pv) { }
	// RVA: 0x40601c4 VA: 0x75966781c4
	public Void VerifyCurPollute() { }
	// RVA: 0x405e968 VA: 0x7596676968
	public Void AddAreaPolluteValue(Int32 pv) { }
	// RVA: 0x405e240 VA: 0x7596676240
	public static Boolean CheckSameArea(PolluteTileData tile1, PolluteTileData tile2) { }
	// RVA: 0x40601fc VA: 0x75966781fc
	public Void Reset() { }
	// RVA: 0x40601ec VA: 0x75966781ec
	public Void .ctor() { }
}
```