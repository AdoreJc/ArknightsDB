# Act27SideTileData

**Namespace:** ` `


## Fields

- `PeriodicTicker refreshTicker`

- `PeriodicTicker durationTicker`

- `MechanismSideType tileSideType`

- `MechanismSideType cachedType`

- `Tile tile`

- `Effect tileEffect`


## Methods

- `Boolean OnTick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act27SideTileData
{
	public PeriodicTicker refreshTicker; // 0x10
	public PeriodicTicker durationTicker; // 0x18
	public MechanismSideType tileSideType; // 0x20
	public MechanismSideType cachedType; // 0x24
	public Tile tile; // 0x28
	public Effect tileEffect; // 0x30


	// RVA: 0x402c07c VA: 0x759664407c
	public Void .ctor(Int32 tickPeriodic, Int32 maxDuration, Tile tile) { }
	// RVA: 0x402c4e8 VA: 0x75966444e8
	public Boolean OnTick() { }
}
```