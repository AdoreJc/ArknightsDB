# SandboxV2AdminMainInventoryItemDetailState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainInventoryItemDetailView _view`

- `SandboxV2AdminMainInventoryItemDetailStateBean m_stateBean`


## Methods

- `Void EventBack()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainInventoryItemDetailState : PopupFloatState
{
	private SandboxV2AdminMainInventoryItemDetailView _view; // 0x70
	private SandboxV2AdminMainInventoryItemDetailStateBean m_stateBean; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventBack; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x24d265c VA: 0x7594aea65c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x24d26c4 VA: 0x7594aea6c4
	protected override Void OnEnter() { }
	// RVA: 0x24d283c VA: 0x7594aea83c
	public Void EventBack() { }
	// RVA: 0x24d28b0 VA: 0x7594aea8b0
	public Void .ctor() { }
	// RVA: 0x24d29cc VA: 0x7594aea9cc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```