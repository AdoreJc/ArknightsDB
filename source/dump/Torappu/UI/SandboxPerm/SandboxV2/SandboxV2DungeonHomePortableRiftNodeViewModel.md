# SandboxV2DungeonHomePortableRiftNodeViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_riftNodeDesc`

- `String m_riftEnemyRushNodeDesc`


## Methods

- `String <>xLuaBaseProxy_GetNodeDesc()`

- `Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam)`

- `Vector2 <>xLuaBaseProxy_GetConnectorOffset(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonHomePortableRiftNodeViewModel : SandboxV2DungeonHomePortableNodeViewModel
{
	private const Int32 HOME_PORTABLE_RIFT_CONNECTOR_DISTANCE; // 0x0
	private String m_riftNodeDesc; // 0x140
	private String m_riftEnemyRushNodeDesc; // 0x148
	private static DelegateBridge __Hotfix0_GetNodeDesc; // 0x0
	private static DelegateBridge __Hotfix0_UpdateCustomData; // 0x8
	private static DelegateBridge __Hotfix0_GetConnectorOffset; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25becdc VA: 0x7594bd6cdc
	protected override String GetNodeDesc() { }
	// RVA: 0x25bed60 VA: 0x7594bd6d60
	protected override Void UpdateCustomData(UpdateParam updateParam) { }
	// RVA: 0x25bee68 VA: 0x7594bd6e68
	public override Vector2 GetConnectorOffset(Vector2 otherNodePos) { }
	// RVA: 0x25bb1a8 VA: 0x7594bd31a8
	public Void .ctor() { }
	// RVA: 0x25bf038 VA: 0x7594bd7038
	private String <>xLuaBaseProxy_GetNodeDesc() { }
	// RVA: 0x25bf03c VA: 0x7594bd703c
	private Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam P0) { }
	// RVA: 0x25bf068 VA: 0x7594bd7068
	private Vector2 <>xLuaBaseProxy_GetConnectorOffset(Vector2 P0) { }
}
```