# SandboxV2AdminMainShopPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainShopTopBarView _topBarView`

- `SandboxV2AdminMainShopTraderView _traderView`

- `SandboxV2AdminMainShopItemGroupView _itemGroupView`

- `SandboxV2AdminMainShopProperty m_property`

- `Int32 m_cachedSelectedIndex`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnGoodItemClicked(Int32)`

- `Void _OnJumpToDetailState(IStateBean)`

- `Void _OnJumpFromDetailState(IStateBean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainShopPanel : SandboxV2AdminMainTabPanel, IHotfixable
{
	private SandboxV2AdminMainShopTopBarView _topBarView; // 0x60
	private SandboxV2AdminMainShopTraderView _traderView; // 0x68
	private SandboxV2AdminMainShopItemGroupView _itemGroupView; // 0x70
	private SandboxV2AdminMainShopProperty m_property; // 0x78
	private Int32 m_cachedSelectedIndex; // 0x80
	private Boolean m_hasInited; // 0x84
	private static DelegateBridge __Hotfix0_get_panelType; // 0x0
	private static DelegateBridge __Hotfix0_get_topTitle; // 0x8
	private static DelegateBridge __Hotfix0_OnGetActiveCheckFunc; // 0x10
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x18
	private static DelegateBridge __Hotfix0_GetToDataListener; // 0x20
	private static DelegateBridge __Hotfix0_GetFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnGoodItemClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnJumpToDetailState; // 0x40
	private static DelegateBridge __Hotfix0__OnJumpFromDetailState; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override SandboxV2AdminMainPanelType panelType { get; }
	public override String topTitle { get; }

	// RVA: 0x24e9658 VA: 0x7594b01658
	public override SandboxV2AdminMainPanelType get_panelType() { }
	// RVA: 0x24e96c0 VA: 0x7594b016c0
	public override String get_topTitle() { }
	// RVA: 0x24e974c VA: 0x7594b0174c
	protected override Func`2 OnGetActiveCheckFunc() { }
	// RVA: 0x24e9800 VA: 0x7594b01800
	protected override Void OnUpdate(SandboxV2AdminMainTabPanelUpdateCase updateCase) { }
	// RVA: 0x24e9d8c VA: 0x7594b01d8c
	public override IEnumerable`1 GetToDataListener() { }
	// RVA: 0x24e9e7c VA: 0x7594b01e7c
	public override IEnumerable`1 GetFromDataListener() { }
	// RVA: 0x24e98dc VA: 0x7594b018dc
	private Void _InitIfNot() { }
	// RVA: 0x24ea620 VA: 0x7594b02620
	private Void _OnGoodItemClicked(Int32 index) { }
	// RVA: 0x24ea948 VA: 0x7594b02948
	private Void _OnJumpToDetailState(IStateBean sb) { }
	// RVA: 0x24eaa64 VA: 0x7594b02a64
	private Void _OnJumpFromDetailState(IStateBean sb) { }
	// RVA: 0x24eab98 VA: 0x7594b02b98
	public Void .ctor() { }
	// RVA: 0x24eac48 VA: 0x7594b02c48
	private Func`2 <>xLuaBaseProxy_OnGetActiveCheckFunc() { }
	// RVA: 0x24eac50 VA: 0x7594b02c50
	private IEnumerable`1 <>xLuaBaseProxy_GetToDataListener() { }
	// RVA: 0x24eac58 VA: 0x7594b02c58
	private IEnumerable`1 <>xLuaBaseProxy_GetFromDataListener() { }
}
```