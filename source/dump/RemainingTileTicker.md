# RemainingTileTicker

**Namespace:** ` `


## Fields

- `ViewRangeFogManager manager`


## Methods

- `Void OnTick(FP)`

- `Void AddTickTime(Tile, FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RemainingTileTicker : IHotfixable
{
	public ViewRangeFogManager manager; // 0x10
	private ListDict`2 m_tickTiles; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x0
	private static DelegateBridge __Hotfix0_AddTickTime; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x406d978 VA: 0x7596685978
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x406db90 VA: 0x7596685b90
	public Void AddTickTime(Tile tile, FP time) { }
	// RVA: 0x406dd2c VA: 0x7596685d2c
	public Void .ctor() { }
}
```