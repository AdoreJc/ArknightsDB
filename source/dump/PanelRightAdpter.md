# PanelRightAdpter

**Namespace:** ` `


## Fields

- `NameCardV2ModuleContainerView m_closure`


## Methods

- `Void RebuildAll()`

- `Void PlayViewSwitchTween(Boolean, Int32)`

- `Void ResetViewSwitchTween(Boolean, Int32)`

- `Void RenderView(Int32, NameCardV2ModuleBaseModel)`

- `Void RemoveView(IVirtualView)`

- `Void InsertView(Int32, IVirtualView)`

- `Void UpdateSize()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PanelRightAdpter : UIRecycleLayoutAdapter
{
	private NameCardV2ModuleContainerView m_closure; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge __Hotfix0_RebuildAll; // 0x10
	private static DelegateBridge __Hotfix0_PlayViewSwitchTween; // 0x18
	private static DelegateBridge __Hotfix0_ResetViewSwitchTween; // 0x20
	private static DelegateBridge __Hotfix0_RenderView; // 0x28
	private static DelegateBridge __Hotfix0_RemoveView; // 0x30
	private static DelegateBridge __Hotfix0_InsertView; // 0x38
	private static DelegateBridge __Hotfix0_UpdateSize; // 0x40


	// RVA: 0x28e6498 VA: 0x7594efe498
	public Void .ctor(NameCardV2ModuleContainerView closure) { }
	// RVA: 0x28e7348 VA: 0x7594eff348
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x28e6734 VA: 0x7594efe734
	public Void RebuildAll() { }
	// RVA: 0x28e6c18 VA: 0x7594efec18
	public Void PlayViewSwitchTween(Boolean isShow, Int32 index) { }
	// RVA: 0x28e6aa4 VA: 0x7594efeaa4
	public Void ResetViewSwitchTween(Boolean isShow, Int32 index) { }
	// RVA: 0x28e6930 VA: 0x7594efe930
	public Void RenderView(Int32 index, NameCardV2ModuleBaseModel model) { }
	// RVA: 0x28e700c VA: 0x7594eff00c
	public Void RemoveView(IVirtualView view) { }
	// RVA: 0x28e6824 VA: 0x7594efe824
	public Void InsertView(Int32 index, IVirtualView view) { }
	// RVA: 0x28e5990 VA: 0x7594efd990
	public Void UpdateSize() { }
}
```