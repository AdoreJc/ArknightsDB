# SandboxV2DungeonHomeNodeViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_enemyRushNodeDesc`


## Methods

- `String <>xLuaBaseProxy_GetNodeDesc()`

- `Boolean <>xLuaBaseProxy_CanSelectWhenEmergency()`

- `Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam)`

- `Vector2 <>xLuaBaseProxy_GetConnectorOffset(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonHomeNodeViewModel : SandboxV2DungeonConstructNodeViewModel
{
	private const Int32 HOME_CONNECTOR_DISTANCE; // 0x0
	private String m_enemyRushNodeDesc; // 0x120
	private static DelegateBridge __Hotfix0_GetNodeDesc; // 0x0
	private static DelegateBridge __Hotfix0_CanSelectWhenEmergency; // 0x8
	private static DelegateBridge __Hotfix0_UpdateCustomData; // 0x10
	private static DelegateBridge __Hotfix0_SupportBuildingTrapType; // 0x18
	private static DelegateBridge __Hotfix0_GetConnectorOffset; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x25be3f0 VA: 0x7594bd63f0
	protected override String GetNodeDesc() { }
	// RVA: 0x25be474 VA: 0x7594bd6474
	protected override Boolean CanSelectWhenEmergency() { }
	// RVA: 0x25be4dc VA: 0x7594bd64dc
	protected override Void UpdateCustomData(UpdateParam updateParam) { }
	// RVA: 0x25be68c VA: 0x7594bd668c
	protected override Boolean SupportBuildingTrapType(SandboxV2TrapItemType buildingTrapType) { }
	// RVA: 0x25be710 VA: 0x7594bd6710
	public override Vector2 GetConnectorOffset(Vector2 otherNodePos) { }
	// RVA: 0x25bb0d0 VA: 0x7594bd30d0
	public Void .ctor() { }
	// RVA: 0x25be8e0 VA: 0x7594bd68e0
	private String <>xLuaBaseProxy_GetNodeDesc() { }
	// RVA: 0x25be8e4 VA: 0x7594bd68e4
	private Boolean <>xLuaBaseProxy_CanSelectWhenEmergency() { }
	// RVA: 0x25be8e8 VA: 0x7594bd68e8
	private Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam P0) { }
	// RVA: 0x25be914 VA: 0x7594bd6914
	private Vector2 <>xLuaBaseProxy_GetConnectorOffset(Vector2 P0) { }
}
```