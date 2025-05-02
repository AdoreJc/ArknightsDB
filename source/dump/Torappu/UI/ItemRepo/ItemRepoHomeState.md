# ItemRepoHomeState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoStateBean _stateBean`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`


## Methods

- `Void ToDetailState(IStateBean)`

- `Void RefreshData(IStateBean)`

- `Void RefreshData()`

- `Void EventOnItemCardClick(Int32)`

- `Void EventOnHideItemDescClick()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _OnPageBack()`

- `Void OnClickToDetail(Int32)`

- `Void OnClickToChangeFilter(Int32)`

- `IEnumerator <>n__0()`

- `IEnumerator <>xLuaBaseProxy_OnPreload()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoHomeState : State
{
	private ItemRepoStateBean _stateBean; // 0x50
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x58
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_ToDetailState; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_RefreshData; // 0x18
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_OnPreload; // 0x28
	private static DelegateBridge __Hotfix1_RefreshData; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_EventOnItemCardClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnHideItemDescClick; // 0x48
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x50
	private static DelegateBridge __Hotfix0__OnPageBack; // 0x58
	private static DelegateBridge __Hotfix0_OnClickToDetail; // 0x60
	private static DelegateBridge __Hotfix0_OnClickToChangeFilter; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2d28674 VA: 0x7595340674
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d286dc VA: 0x75953406dc
	public Void ToDetailState(IStateBean stateBean) { }
	// RVA: 0x2d28890 VA: 0x7595340890
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2d28ad8 VA: 0x7595340ad8
	public Void RefreshData(IStateBean stateBean) { }
	// RVA: 0x2d28c30 VA: 0x7595340c30
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2d290a0 VA: 0x75953410a0
	protected override IEnumerator OnPreload() { }
	// RVA: 0x2d29174 VA: 0x7595341174
	public Void RefreshData() { }
	// RVA: 0x2d291e4 VA: 0x75953411e4
	protected override Void OnEnter() { }
	// RVA: 0x2d292a8 VA: 0x75953412a8
	public Void EventOnItemCardClick(Int32 position) { }
	// RVA: 0x2d29438 VA: 0x7595341438
	public Void EventOnHideItemDescClick() { }
	// RVA: 0x2d29548 VA: 0x7595341548
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2d29690 VA: 0x7595341690
	private Void _OnPageBack() { }
	// RVA: 0x2d2970c VA: 0x759534170c
	public Void OnClickToDetail(Int32 position) { }
	// RVA: 0x2d29920 VA: 0x7595341920
	public Void OnClickToChangeFilter(Int32 filter) { }
	// RVA: 0x2d29a74 VA: 0x7595341a74
	public Void .ctor() { }
	// RVA: 0x2d29ae4 VA: 0x7595341ae4
	private IEnumerator <>n__0() { }
	// RVA: 0x2d29aec VA: 0x7595341aec
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2d29af4 VA: 0x7595341af4
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x2d29afc VA: 0x7595341afc
	private IEnumerator <>xLuaBaseProxy_OnPreload() { }
	// RVA: 0x2d29b04 VA: 0x7595341b04
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```