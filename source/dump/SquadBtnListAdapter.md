# SquadBtnListAdapter

**Namespace:** ` `


## Fields

- `SandboxV2SquadGroupModel m_squadGroupModel`


## Methods

- `Void UpdateData(SandboxV2SquadGroupModel)`

- `Void _RegisterTutorialGo(Int32, SandboxV2SquadTabItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SquadBtnListAdapter : SimpleLayoutAdapter
{
	private SandboxV2SquadGroupModel m_squadGroupModel; // 0x20
	private Action`1 m_onItemClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge __Hotfix0_RenderView; // 0x18
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x20

	public override Int32 count { get; }

	// RVA: 0x260e8a4 VA: 0x7594c268a4
	public Void .ctor(Action`1 onItemClick) { }
	// RVA: 0x260eab4 VA: 0x7594c26ab4
	public override Int32 get_count() { }
	// RVA: 0x260e820 VA: 0x7594c26820
	public Void UpdateData(SandboxV2SquadGroupModel squadGroupModel) { }
	// RVA: 0x260ebac VA: 0x7594c26bac
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x260f02c VA: 0x7594c2702c
	private Void _RegisterTutorialGo(Int32 index, SandboxV2SquadTabItemView itemView) { }
}
```