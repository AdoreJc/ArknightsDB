# SandboxV2DungeonHomePortableNodeViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonMonthBrief <monthBriefInfo>k__BackingField`


## Properties

- `SandboxV2DungeonMonthBrief monthBriefInfo`


## Methods

- `SandboxV2DungeonMonthBrief get_monthBriefInfo()`

- `Void set_monthBriefInfo(SandboxV2DungeonMonthBrief)`

- `Boolean <>xLuaBaseProxy_CanSelectWhenEmergency()`

- `Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonHomePortableNodeViewModel : SandboxV2DungeonConstructNodeViewModel
{
	private const Single PORTABLE_SEVERELY_DAMAGED_THRESHOLD; // 0x0
	private SandboxV2DungeonMonthBrief <monthBriefInfo>k__BackingField; // 0x120
	private static DelegateBridge __Hotfix0_get_monthBriefInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_monthBriefInfo; // 0x8
	private static DelegateBridge __Hotfix0_CanSelectWhenEmergency; // 0x10
	private static DelegateBridge __Hotfix0_UpdateCustomData; // 0x18
	private static DelegateBridge __Hotfix0_SupportBuildingTrapType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public SandboxV2DungeonMonthBrief monthBriefInfo { get; set; }

	// RVA: 0x25be918 VA: 0x7594bd6918
	public SandboxV2DungeonMonthBrief get_monthBriefInfo() { }
	// RVA: 0x25be9a0 VA: 0x7594bd69a0
	private Void set_monthBriefInfo(SandboxV2DungeonMonthBrief value) { }
	// RVA: 0x25bea28 VA: 0x7594bd6a28
	protected override Boolean CanSelectWhenEmergency() { }
	// RVA: 0x25bea90 VA: 0x7594bd6a90
	protected override Void UpdateCustomData(UpdateParam updateParam) { }
	// RVA: 0x25bec2c VA: 0x7594bd6c2c
	protected override Boolean SupportBuildingTrapType(SandboxV2TrapItemType buildingTrapType) { }
	// RVA: 0x25bb13c VA: 0x7594bd313c
	public Void .ctor() { }
	// RVA: 0x25becac VA: 0x7594bd6cac
	private Boolean <>xLuaBaseProxy_CanSelectWhenEmergency() { }
	// RVA: 0x25becb0 VA: 0x7594bd6cb0
	private Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam P0) { }
}
```