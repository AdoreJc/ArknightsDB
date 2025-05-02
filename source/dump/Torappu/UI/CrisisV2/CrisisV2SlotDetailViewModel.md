# CrisisV2SlotDetailViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2NodeViewData m_nodeViewData`


## Properties

- `Vector2 mapSize`


## Methods

- `Vector2 get_mapSize()`

- `Void LoadData(CrisisV2MapDetailData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SlotDetailViewModel : IHotfixable
{
	private CrisisV2NodeViewData m_nodeViewData; // 0x10
	private static DelegateBridge __Hotfix0_get_mapSize; // 0x0
	private static DelegateBridge __Hotfix0_get_roadPosMap; // 0x8
	private static DelegateBridge __Hotfix0_get_nodePosMap; // 0x10
	private static DelegateBridge __Hotfix0_get_bagPosMap; // 0x18
	private static DelegateBridge __Hotfix0_get_exclusionMap; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Vector2 mapSize { get; }
	public Dictionary`2 roadPosMap { get; }
	public Dictionary`2 nodePosMap { get; }
	public Dictionary`2 bagPosMap { get; }
	public Dictionary`2 exclusionMap { get; }

	// RVA: 0x2bf3040 VA: 0x759520b040
	public Vector2 get_mapSize() { }
	// RVA: 0x2bf30e4 VA: 0x759520b0e4
	public Dictionary`2 get_roadPosMap() { }
	// RVA: 0x2bf12c4 VA: 0x75952092c4
	public Dictionary`2 get_nodePosMap() { }
	// RVA: 0x2bf115c VA: 0x759520915c
	public Dictionary`2 get_bagPosMap() { }
	// RVA: 0x2bf315c VA: 0x759520b15c
	public Dictionary`2 get_exclusionMap() { }
	// RVA: 0x2bec284 VA: 0x7595204284
	public Void LoadData(CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bf2c88 VA: 0x759520ac88
	public Void .ctor() { }
}
```