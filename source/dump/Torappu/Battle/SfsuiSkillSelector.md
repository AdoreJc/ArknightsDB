# SfsuiSkillSelector

**Namespace:** `Torappu.Battle`


## Fields

- `SfsuiSkillFilterType _filter`

- `BuildableType _specificBuildableTypeFirst`

- `Vector2 _posOffset`

- `String _buffKey`

- `Int32 _rowCount`


## Properties

- `Boolean IsNoSpecificBuffFilter`

- `Boolean IsDistRelatedFilter`

- `Boolean IsAllRightTilesToFirstTargetFilter`


## Methods

- `Boolean get_IsNoSpecificBuffFilter()`

- `Boolean get_IsDistRelatedFilter()`

- `Boolean get_IsAllRightTilesToFirstTargetFilter()`

- `Boolean _Filter_RowDistToPosDec(Entity, Entity, out, out)`

- `Boolean _Filter_DistToPosDec(Entity, Entity, out, out)`

- `Boolean _Filter_NoSpecificBuffFirst(Entity, Entity, out, out)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SfsuiSkillSelector : AdvancedSelector
{
	private SfsuiSkillFilterType _filter; // 0xe8
	private BuildableType _specificBuildableTypeFirst; // 0xec
	private Vector2 _posOffset; // 0xf0
	private String _buffKey; // 0xf8
	private Int32 _rowCount; // 0x100
	private List`1 m_castTiles; // 0x108
	private static DelegateBridge __Hotfix0_get_IsNoSpecificBuffFilter; // 0x0
	private static DelegateBridge __Hotfix0_get_IsDistRelatedFilter; // 0x8
	private static DelegateBridge __Hotfix0_get_IsAllRightTilesToFirstTargetFilter; // 0x10
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x18
	private static DelegateBridge __Hotfix0_FindTiles; // 0x20
	private static DelegateBridge __Hotfix0__Filter_RowDistToPosDec; // 0x28
	private static DelegateBridge __Hotfix0__Filter_DistToPosDec; // 0x30
	private static DelegateBridge __Hotfix0__Filter_NoSpecificBuffFirst; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean IsNoSpecificBuffFilter { get; }
	private Boolean IsDistRelatedFilter { get; }
	private Boolean IsAllRightTilesToFirstTargetFilter { get; }

	// RVA: 0x1bc01d0 VA: 0x75941d81d0
	private Boolean get_IsNoSpecificBuffFilter() { }
	// RVA: 0x1bc0240 VA: 0x75941d8240
	private Boolean get_IsDistRelatedFilter() { }
	// RVA: 0x1bc02b4 VA: 0x75941d82b4
	private Boolean get_IsAllRightTilesToFirstTargetFilter() { }
	// RVA: 0x1bc0324 VA: 0x75941d8324
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bc0524 VA: 0x75941d8524
	public override List`1 FindTiles(Vector2 pos) { }
	// RVA: 0x1bc0d74 VA: 0x75941d8d74
	private Boolean _Filter_RowDistToPosDec(Entity candidate, Entity source, out FP weight, out FP priorWeight) { }
	// RVA: 0x1bc0fd0 VA: 0x75941d8fd0
	private Boolean _Filter_DistToPosDec(Entity candidate, Entity source, out FP weight, out FP priorWeight) { }
	// RVA: 0x1bc11e8 VA: 0x75941d91e8
	private Boolean _Filter_NoSpecificBuffFirst(Entity candidate, Entity source, out FP weight, out FP priorWeight) { }
	// RVA: 0x1bc148c VA: 0x75941d948c
	public Void .ctor() { }
	// RVA: 0x1bc15c8 VA: 0x75941d95c8
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
	// RVA: 0x1bc15d0 VA: 0x75941d95d0
	private List`1 <>xLuaBaseProxy_FindTiles(Vector2 P0) { }
}
```