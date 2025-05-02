# ActMultiV3StageListDetailState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `RectTransform _topMenuContainer`

- `ActMultiV3StageListDetailView _view`

- `Boolean m_inited`

- `StateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _OnJumpToEnemyHandbook(IStateBean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnBtnSwitchStageClicked(Boolean)`

- `Void _OnBtnEnemyHandbookClicked()`

- `Void OnBackClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListDetailState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 MSG_BTN_LEFT_CLICKED; // 0x0
	public const Int32 MSG_BTN_RIGHT_CLICKED; // 0x0
	public const Int32 MSG_BTN_ENEMY_HANDBOOK_CLICKED; // 0x0
	private RectTransform _topMenuContainer; // 0x70
	private ActMultiV3StageListDetailView _view; // 0x78
	private Boolean m_inited; // 0x80
	private StateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandbook; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__OnBtnSwitchStageClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnBtnEnemyHandbookClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x314853c VA: 0x759576053c
	private Void _InitIfNot() { }
	// RVA: 0x3148648 VA: 0x7595760648
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31486b0 VA: 0x75957606b0
	protected override Void OnEnter() { }
	// RVA: 0x3148754 VA: 0x7595760754
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x31488cc VA: 0x75957608cc
	private Void _OnJumpToEnemyHandbook(IStateBean stateBean) { }
	// RVA: 0x3148b28 VA: 0x7595760b28
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3148c00 VA: 0x7595760c00
	private Void _OnBtnSwitchStageClicked(Boolean isRight) { }
	// RVA: 0x3148d84 VA: 0x7595760d84
	private Void _OnBtnEnemyHandbookClicked() { }
	// RVA: 0x3148fec VA: 0x7595760fec
	public Void OnBackClicked() { }
	// RVA: 0x31490f0 VA: 0x75957610f0
	public Void .ctor() { }
	// RVA: 0x3149248 VA: 0x7595761248
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3149250 VA: 0x7595761250
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```