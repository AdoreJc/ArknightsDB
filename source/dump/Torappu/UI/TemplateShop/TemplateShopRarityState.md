# TemplateShopRarityState

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `PrefabInstHolder _topMenuHolder`

- `TemplateRarityShopStateBean m_stateBean`

- `TemplateShopRarityListView _listView`

- `Image _shopIcon`

- `Text _shopName`

- `Image _shopLongBar`

- `Image _shopBack`

- `Text _timeText`

- `Text _remainText`

- `Transform _titleContainer`

- `TemplateShopResHolder m_resHolder`


## Methods

- `IEnumerator _FocusListRarity()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopRarityState : PopupFadeState
{
	private PrefabInstHolder _topMenuHolder; // 0x70
	private TemplateRarityShopStateBean m_stateBean; // 0x78
	private TemplateShopRarityListView _listView; // 0x80
	private Image _shopIcon; // 0x88
	private Text _shopName; // 0x90
	private Image _shopLongBar; // 0x98
	private Image _shopBack; // 0xa0
	private Text _timeText; // 0xa8
	private Text _remainText; // 0xb0
	private Transform _titleContainer; // 0xb8
	private TemplateShopResHolder m_resHolder; // 0xc0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__FocusListRarity; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x235631c VA: 0x759496e31c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2356384 VA: 0x759496e384
	protected override Void OnResume() { }
	// RVA: 0x23568e4 VA: 0x759496e8e4
	protected override Void OnEnter() { }
	// RVA: 0x2356f88 VA: 0x759496ef88
	private IEnumerator _FocusListRarity() { }
	// RVA: 0x235705c VA: 0x759496f05c
	public Void .ctor() { }
	// RVA: 0x2357218 VA: 0x759496f218
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2357220 VA: 0x759496f220
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```