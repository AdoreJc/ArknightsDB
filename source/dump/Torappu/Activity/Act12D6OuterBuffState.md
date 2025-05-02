# Act12D6OuterBuffState

**Namespace:** `Torappu.Activity`


## Fields

- `Act12D6OuterBuffView _view`

- `Act12D6CoinView _coinView`

- `RectTransform _topMenuContainer`

- `Act12D6OuterBuffStateBean m_stateBean`

- `CommonTopMenu m_topMenu`

- `Boolean m_inited`

- `String m_cachedBuffId`


## Methods

- `Void EventOnOuterBuffDetail(String)`

- `Void EventOnMaxLevel(String)`

- `Void _InitIfNot()`

- `Void <RegisterToDataListener>b__9_0(IStateBean)`

- `Void <RegisterFromDataListener>b__11_0(IStateBean)`

- `Void <_InitIfNot>b__14_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class Act12D6OuterBuffState : PopupFloatState, IHotfixable
{
	private Act12D6OuterBuffView _view; // 0x70
	private Act12D6CoinView _coinView; // 0x78
	private RectTransform _topMenuContainer; // 0x80
	private Act12D6OuterBuffStateBean m_stateBean; // 0x88
	private CommonTopMenu m_topMenu; // 0x90
	private Boolean m_inited; // 0x98
	private String m_cachedBuffId; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x18
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_EventOnOuterBuffDetail; // 0x28
	private static DelegateBridge __Hotfix0_EventOnMaxLevel; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x30b7624 VA: 0x75956cf624
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30b768c VA: 0x75956cf68c
	protected override Void OnEnter() { }
	// RVA: 0x30b784c VA: 0x75956cf84c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x30b79c4 VA: 0x75956cf9c4
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x30b7a3c VA: 0x75956cfa3c
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x30b7bb4 VA: 0x75956cfbb4
	public Void EventOnOuterBuffDetail(String buffId) { }
	// RVA: 0x30b7d7c VA: 0x75956cfd7c
	public Void EventOnMaxLevel(String buffId) { }
	// RVA: 0x30b7728 VA: 0x75956cf728
	private Void _InitIfNot() { }
	// RVA: 0x30b7e2c VA: 0x75956cfe2c
	public Void .ctor() { }
	// RVA: 0x30b7edc VA: 0x75956cfedc
	private Void <RegisterToDataListener>b__9_0(IStateBean stateBean) { }
	// RVA: 0x30b7f74 VA: 0x75956cff74
	private Void <RegisterFromDataListener>b__11_0(IStateBean stateBean) { }
	// RVA: 0x30b7fa8 VA: 0x75956cffa8
	private Void <_InitIfNot>b__14_0() { }
	// RVA: 0x30b7fb0 VA: 0x75956cffb0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x30b7fb8 VA: 0x75956cffb8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x30b7fc0 VA: 0x75956cffc0
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x30b7fc8 VA: 0x75956cffc8
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```