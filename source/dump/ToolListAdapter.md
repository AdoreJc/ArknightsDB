# ToolListAdapter

**Namespace:** ` `


## Fields

- `SandboxV2SquadModel m_squadModel`


## Methods

- `Void UpdateData(SandboxV2SquadGroupModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ToolListAdapter : SimpleLayoutAdapter
{
	private SandboxV2SquadModel m_squadModel; // 0x20
	private Action`1 m_onToolClick; // 0x28
	private Action`1 m_onBtnBuildClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18

	public override Int32 count { get; }

	// RVA: 0x261d32c VA: 0x7594c3532c
	public Void .ctor(Action`1 onToolClick, Action`1 onBtnBuildClick) { }
	// RVA: 0x261d3d8 VA: 0x7594c353d8
	public override Int32 get_count() { }
	// RVA: 0x261d454 VA: 0x7594c35454
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x261d650 VA: 0x7594c35650
	public Void UpdateData(SandboxV2SquadGroupModel squadGroupModel) { }
}
```