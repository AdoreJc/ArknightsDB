# SandboxV2AdminCharSelectState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminSelectListView _listView`

- `RectTransform _btnBack`

- `SandboxV2AdminCharSelectStateBean m_stateBean`


## Methods

- `Void OnOpenCharDetail()`

- `Void OnOpenEatFood()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnEnsure()`

- `Void _DismissWithEnsure()`

- `Void _OnProduceDrink()`

- `Void _OnSwitchPopView(Boolean)`

- `Void <RegisterToDataListener>b__21_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminCharSelectState : PopupFadeState, IValueMsgReceiver
{
	private SandboxV2AdminSelectListView _listView; // 0x70
	private RectTransform _btnBack; // 0x78
	public const Int32 ATTR_SELECT_TAB_CLICKED; // 0x0
	public const Int32 ON_CHAR_SELECT_CLICKED; // 0x0
	public const Int32 ON_CHANGE_SKILL; // 0x0
	public const Int32 ON_CHANGE_EQUIP; // 0x0
	public const Int32 ON_SHUFFLE_PROF_OPEN; // 0x0
	public const Int32 ON_CLOSE_SHUFFLE_PROF; // 0x0
	public const Int32 ON_SHUFFLE_STATE_OPEN; // 0x0
	public const Int32 ON_SHUFFLE_STATE_CLOSE; // 0x0
	public const Int32 ON_SHUFFLE_PROF_CHANGE; // 0x0
	public const Int32 ON_SHUFFLE_STATE_CHANGE; // 0x0
	public const Int32 ON_CLICK_ENSURE; // 0x0
	public const Int32 ON_CLICK_CLEAR; // 0x0
	public const Int32 TO_CHAR_DETAIL; // 0x0
	public const Int32 TO_FOOD_INFO; // 0x0
	public const Int32 ON_PRODUCE_DRINK; // 0x0
	public const Int32 ON_POP_VIEW_OPEN; // 0x0
	public const Int32 ON_POP_VIEW_CLOSE; // 0x0
	private SandboxV2AdminCharSelectStateBean m_stateBean; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_OnOpenCharDetail; // 0x20
	private static DelegateBridge __Hotfix0_OnOpenEatFood; // 0x28
	private static DelegateBridge __Hotfix0_OnMessage; // 0x30
	private static DelegateBridge __Hotfix0__OnEnsure; // 0x38
	private static DelegateBridge __Hotfix0__DismissWithEnsure; // 0x40
	private static DelegateBridge __Hotfix0__OnProduceDrink; // 0x48
	private static DelegateBridge __Hotfix0__OnSwitchPopView; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x24ae7dc VA: 0x7594ac67dc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x24ae844 VA: 0x7594ac6844
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x24ae9bc VA: 0x7594ac69bc
	protected override Void OnEnter() { }
	// RVA: 0x24af0b8 VA: 0x7594ac70b8
	protected override Void OnResume() { }
	// RVA: 0x24af1f0 VA: 0x7594ac71f0
	public Void OnOpenCharDetail() { }
	// RVA: 0x24af348 VA: 0x7594ac7348
	public Void OnOpenEatFood() { }
	// RVA: 0x24af454 VA: 0x7594ac7454
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x24afe2c VA: 0x7594ac7e2c
	private Void _OnEnsure() { }
	// RVA: 0x24b0524 VA: 0x7594ac8524
	private Void _DismissWithEnsure() { }
	// RVA: 0x24b01dc VA: 0x7594ac81dc
	private Void _OnProduceDrink() { }
	// RVA: 0x24b049c VA: 0x7594ac849c
	private Void _OnSwitchPopView(Boolean isShow) { }
	// RVA: 0x24b0714 VA: 0x7594ac8714
	public Void .ctor() { }
	// RVA: 0x24b086c VA: 0x7594ac886c
	private Void <RegisterToDataListener>b__21_0(IStateBean statebean) { }
	// RVA: 0x24b095c VA: 0x7594ac895c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x24b0964 VA: 0x7594ac8964
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x24b096c VA: 0x7594ac896c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```