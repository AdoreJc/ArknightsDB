# PillarCtrl

**Namespace:** ` `


## Fields

- `PollutedAreaManager m_manager`


## Methods

- `Void OnTick()`

- `Void InitPillarData(PollutedAreaManager)`

- `Void _GetNearbyTileData(List`1, GridPosition)`

- `Void _UpdatePillarGraphic()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PillarCtrl
{
	private static readonly Int32 EMISSION_COLOR; // 0x0
	private PollutedAreaManager m_manager; // 0x10
	private ListDict`2 m_pillarDatas; // 0x18
	private readonly Vector2Int[] m_tileDirs; // 0x20


	// RVA: 0x405d25c VA: 0x759667525c
	public Void OnTick() { }
	// RVA: 0x405c62c VA: 0x759667462c
	public Void InitPillarData(PollutedAreaManager manager) { }
	// RVA: 0x4060ea8 VA: 0x7596678ea8
	private Void _GetNearbyTileData(List`1 dataList, GridPosition curGrid) { }
	// RVA: 0x4060be8 VA: 0x7596678be8
	private Void _UpdatePillarGraphic() { }
	// RVA: 0x40607b0 VA: 0x75966787b0
	public Void .ctor() { }
	// RVA: 0x40612ac VA: 0x75966792ac
	private static Void .cctor() { }
}
```