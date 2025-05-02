# SandboxV2AdminMainInventoryPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainInventoryLeftTabView _leftTabView`

- `SandboxV2AdminMainInventoryEmptyView _emptyTabView`

- `SandboxV2AdminMainInventoryItemView _itemView`

- `SandboxV2AdminMainInventoryPanelModelProperty m_prop`


## Methods

- `Void _InitIfNot()`

- `Void _OpenDetailState(Int32)`

- `Void <GetToDataListener>b__10_0(IStateBean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainInventoryPanel : SandboxV2AdminMainTabPanel
{
	private SandboxV2AdminMainInventoryLeftTabView _leftTabView; // 0x60
	private SandboxV2AdminMainInventoryEmptyView _emptyTabView; // 0x68
	private SandboxV2AdminMainInventoryItemView _itemView; // 0x70
	private SandboxV2AdminMainInventoryPanelModelProperty m_prop; // 0x78
	private static DelegateBridge __Hotfix0_get_panelType; // 0x0
	private static DelegateBridge __Hotfix0_get_topTitle; // 0x8
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_GetToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__OpenDetailState; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override SandboxV2AdminMainPanelType panelType { get; }
	public override String topTitle { get; }

	// RVA: 0x24d4e5c VA: 0x7594aece5c
	public override SandboxV2AdminMainPanelType get_panelType() { }
	// RVA: 0x24d4ec4 VA: 0x7594aecec4
	public override String get_topTitle() { }
	// RVA: 0x24d4f50 VA: 0x7594aecf50
	protected override Void OnUpdate(SandboxV2AdminMainTabPanelUpdateCase updateCase) { }
	// RVA: 0x24d5044 VA: 0x7594aed044
	private Void _InitIfNot() { }
	// RVA: 0x24d5290 VA: 0x7594aed290
	public override IEnumerable`1 GetToDataListener() { }
	// RVA: 0x24d533c VA: 0x7594aed33c
	private Void _OpenDetailState(Int32 idx) { }
	// RVA: 0x24d54a0 VA: 0x7594aed4a0
	public Void .ctor() { }
	// RVA: 0x24d5510 VA: 0x7594aed510
	private Void <GetToDataListener>b__10_0(IStateBean stateBean) { }
	// RVA: 0x24d55f0 VA: 0x7594aed5f0
	private IEnumerable`1 <>xLuaBaseProxy_GetToDataListener() { }
}
```