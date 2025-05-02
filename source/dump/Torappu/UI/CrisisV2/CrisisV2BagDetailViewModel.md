# CrisisV2BagDetailViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2BagViewData m_bagViewData`


## Properties

- `Vector2 mapSize`


## Methods

- `Vector2 get_mapSize()`

- `Void LoadData(CrisisV2MapDetailData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2BagDetailViewModel : IHotfixable
{
	private CrisisV2BagViewData m_bagViewData; // 0x10
	private static DelegateBridge __Hotfix0_get_mapSize; // 0x0
	private static DelegateBridge __Hotfix0_get_roadPosMap; // 0x8
	private static DelegateBridge __Hotfix0_get_bagPosMap; // 0x10
	private static DelegateBridge __Hotfix0_get_nodePosMap; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Vector2 mapSize { get; }
	public Dictionary`2 roadPosMap { get; }
	public Dictionary`2 bagPosMap { get; }
	public Dictionary`2 nodePosMap { get; }

	// RVA: 0x2bf2f24 VA: 0x759520af24
	public Vector2 get_mapSize() { }
	// RVA: 0x2bf2fc8 VA: 0x759520afc8
	public Dictionary`2 get_roadPosMap() { }
	// RVA: 0x2bf11d4 VA: 0x75952091d4
	public Dictionary`2 get_bagPosMap() { }
	// RVA: 0x2bf124c VA: 0x759520924c
	public Dictionary`2 get_nodePosMap() { }
	// RVA: 0x2bec31c VA: 0x759520431c
	public Void LoadData(CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bf2cf8 VA: 0x759520acf8
	public Void .ctor() { }
}
```