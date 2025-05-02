# TemplateShopGroupState

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `PrefabInstHolder _topMenuHolder`

- `TemplateGroupShopStateBean m_stateBean`

- `TemplateShopGroupListView _listView`

- `Image _shopIcon`

- `Text _shopName`

- `Image _shopLongBar`

- `Image _shopBack`

- `Text _timeText`

- `Transform _titleContainer`

- `TemplateShopResHolder m_resHolder`

- `AsyncGameObjectLoader m_objLoader`


## Methods

- `Void UpdateTime(Single)`

- `Void OnEnable()`

- `Void OnDisable()`

- `IEnumerator _FocusOnLatest()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopGroupState : PopupFadeState, ITimeWatcher
{
	private PrefabInstHolder _topMenuHolder; // 0x70
	private TemplateGroupShopStateBean m_stateBean; // 0x78
	private TemplateShopGroupListView _listView; // 0x80
	private Image _shopIcon; // 0x88
	private Text _shopName; // 0x90
	private Image _shopLongBar; // 0x98
	private Image _shopBack; // 0xa0
	private Text _timeText; // 0xa8
	private Transform _titleContainer; // 0xb0
	private TemplateShopResHolder m_resHolder; // 0xb8
	private AsyncGameObjectLoader m_objLoader; // 0xc0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0_OnDisable; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0__FocusOnLatest; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x235492c VA: 0x759496c92c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2354994 VA: 0x759496c994
	public Void UpdateTime(Single delta) { }
	// RVA: 0x2354a28 VA: 0x759496ca28
	private Void OnEnable() { }
	// RVA: 0x2354a98 VA: 0x759496ca98
	private Void OnDisable() { }
	// RVA: 0x2354b08 VA: 0x759496cb08
	protected override Void OnResume() { }
	// RVA: 0x23551e0 VA: 0x759496d1e0
	protected override Void OnEnter() { }
	// RVA: 0x2355808 VA: 0x759496d808
	private IEnumerator _FocusOnLatest() { }
	// RVA: 0x2355ab0 VA: 0x759496dab0
	public Void .ctor() { }
	// RVA: 0x2355c58 VA: 0x759496dc58
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2355c60 VA: 0x759496dc60
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```