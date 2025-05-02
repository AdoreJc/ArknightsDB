# CharmRewardListState

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Text _intro`

- `CharmCard _cardPrefab`

- `RectTransform _listRoot`

- `Text _title`

- `Text _cnt`


## Methods

- `Void _Refresh()`

- `Void _InitIfNot()`

- `Void EventOnClose()`

- `String _GetTheActivityOpenedMe()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmRewardListState : PopupFloatState
{
	private Text _intro; // 0x70
	private CharmCard _cardPrefab; // 0x78
	private RectTransform _listRoot; // 0x80
	private Text _title; // 0x88
	private Text _cnt; // 0x90
	private List`1 m_charmModels; // 0x98
	private List`1 m_items; // 0xa0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0__Refresh; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClose; // 0x28
	private static DelegateBridge __Hotfix0__GetTheActivityOpenedMe; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3456b20 VA: 0x7595a6eb20
	protected override Void OnEnter() { }
	// RVA: 0x3456e6c VA: 0x7595a6ee6c
	protected override Void OnResume() { }
	// RVA: 0x3456ed4 VA: 0x7595a6eed4
	private Void _Refresh() { }
	// RVA: 0x3456b88 VA: 0x7595a6eb88
	private Void _InitIfNot() { }
	// RVA: 0x34574a8 VA: 0x7595a6f4a8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x345750c VA: 0x7595a6f50c
	public Void EventOnClose() { }
	// RVA: 0x3457330 VA: 0x7595a6f330
	private String _GetTheActivityOpenedMe() { }
	// RVA: 0x3457580 VA: 0x7595a6f580
	public Void .ctor() { }
	// RVA: 0x34575f0 VA: 0x7595a6f5f0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x34575f8 VA: 0x7595a6f5f8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```