# CompoundPeriodicTicker

**Namespace:** `Torappu.Battle`


## Fields

- `PeriodicTicker m_tranditionalFindTargetTicker`

- `PeriodicTickerNoUpdateNeeded m_deterministicFindTargetTicker`

- `IPeriodicTicker m_findTargetTicker`

- `Int32 m_cachedPeriod`


## Properties

- `Boolean isReady`


## Methods

- `Boolean get_isReady()`

- `Void Reset(Boolean)`

- `Void Reset(Int32, Boolean)`

- `Void Reset(Boolean, Int32, Boolean)`

- `Void Reset(Boolean, Boolean)`

- `Boolean Tick()`

- `Boolean Next()`

- `Void _InitIfNot(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CompoundPeriodicTicker : IPeriodicTicker
{
	private PeriodicTicker m_tranditionalFindTargetTicker; // 0x10
	private PeriodicTickerNoUpdateNeeded m_deterministicFindTargetTicker; // 0x18
	private IPeriodicTicker m_findTargetTicker; // 0x20
	private Int32 m_cachedPeriod; // 0x28

	public Boolean isReady { get; }

	// RVA: 0x409c648 VA: 0x75966b4648
	public Boolean get_isReady() { }
	// RVA: 0x409c6e8 VA: 0x75966b46e8
	public Void .ctor(Int32 period, Boolean waitFirstPeriod) { }
	// RVA: 0x409c720 VA: 0x75966b4720
	public Void .ctor(Int32 period, Boolean isDeterministic, Boolean waitFirstPeriod) { }
	// RVA: 0x409c858 VA: 0x75966b4858
	public Void Reset(Boolean waitFirstPeriod) { }
	// RVA: 0x409c8a0 VA: 0x75966b48a0
	public Void Reset(Int32 period, Boolean waitFirstPeriod) { }
	// RVA: 0x409c918 VA: 0x75966b4918
	public Void Reset(Boolean isDeterministic, Int32 period, Boolean waitFirstPeriod) { }
	// RVA: 0x409c9ec VA: 0x75966b49ec
	public Void Reset(Boolean isDeterministic, Boolean waitFirstPeriod) { }
	// RVA: 0x409cab4 VA: 0x75966b4ab4
	public Boolean Tick() { }
	// RVA: 0x409cb58 VA: 0x75966b4b58
	public Boolean Next() { }
	// RVA: 0x409c764 VA: 0x75966b4764
	private Void _InitIfNot(Boolean isDeterministic, Boolean waitFirstPeriod) { }
}
```