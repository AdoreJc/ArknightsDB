# PeriodicTickerNoUpdateNeeded

**Namespace:** `Torappu.Battle`


## Fields

- `UInt32 m_tickPeriod`

- `UInt32 m_nextReadyFrame`


## Properties

- `Boolean isReady`

- `Int32 remainingTick`


## Methods

- `Boolean get_isReady()`

- `Int32 get_remainingTick()`

- `Void Reset(Boolean)`

- `Void Reset(Int32, Boolean)`

- `Boolean Next()`

- `Boolean Tick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class PeriodicTickerNoUpdateNeeded : IPeriodicTicker
{
	private UInt32 m_tickPeriod; // 0x10
	private UInt32 m_nextReadyFrame; // 0x14

	public Boolean isReady { get; }
	public Int32 remainingTick { get; }

	// RVA: 0x409c418 VA: 0x75966b4418
	public Boolean get_isReady() { }
	// RVA: 0x409c47c VA: 0x75966b447c
	public Int32 get_remainingTick() { }
	// RVA: 0x409c508 VA: 0x75966b4508
	public Void .ctor(Int32 period, Boolean waitFirstPeriod) { }
	// RVA: 0x409c54c VA: 0x75966b454c
	public Void Reset(Boolean waitFirstPeriod) { }
	// RVA: 0x409c53c VA: 0x75966b453c
	public Void Reset(Int32 newPeriod, Boolean waitFirstPeriod) { }
	// RVA: 0x409c5c8 VA: 0x75966b45c8
	public Boolean Next() { }
	// RVA: 0x409c644 VA: 0x75966b4644
	public Boolean Tick() { }
}
```