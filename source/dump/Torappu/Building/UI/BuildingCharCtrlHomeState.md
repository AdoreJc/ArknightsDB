# BuildingCharCtrlHomeState

**Namespace:** `Torappu.Building.UI`


## Fields

- `BuildingCharCtrlHomeView _homeView`

- `BuildingCharCtrlRoomTitleView _roomTitle`

- `RectTransform _rectTransformBack`

- `RectTransform _rectTransformArrow`

- `CanvasGroup _canvasGroupArrow`

- `BuildingCharCtrlHomeStateBean m_stateBean`

- `FadeSwitchTween m_arrowFadeTween`

- `Int64 m_cachedNextRequestTs`

- `Boolean m_isInited`


## Properties

- `Vector2 moveDir`


## Methods

- `Void Update()`

- `Void _InitIfNot()`

- `Vector2 _GetJoystickAxis()`

- `Void _ShowOrHideArrow(Boolean)`

- `Void _ShowOrHideEmojiPanel()`

- `Void _OnEmojiListBtnClick(String)`

- `Void _TryToSendSendEmojiRequest(String)`

- `Void OnBackBtnClicked()`

- `Void OnTouchBtnClicked()`

- `Void OnUpstairsBtnClicked()`

- `Void OnDownstairsBtnClicked()`

- `Void OnEmojiBtnClicked()`

- `Void OnShowAndHideBtnClicked()`

- `Vector2 get_moveDir()`

- `Void set_moveDir(Vector2)`

- `Void OnMoverStateChanged()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void <_TryToSendSendEmojiRequest>b__22_0(BuildingSendEmojiResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingCharCtrlHomeState : State, IMoveHolder, IValueMsgReceiver
{
	private const Single ARROW_HIDE_GAP; // 0x0
	public const Int32 MSG_EMOJI_LIST_BTN_CLICK; // 0x0
	private BuildingCharCtrlHomeView _homeView; // 0x50
	private BuildingCharCtrlRoomTitleView _roomTitle; // 0x58
	private RectTransform _rectTransformBack; // 0x60
	private RectTransform _rectTransformArrow; // 0x68
	private CanvasGroup _canvasGroupArrow; // 0x70
	private BuildingCharCtrlHomeStateBean m_stateBean; // 0x78
	private FadeSwitchTween m_arrowFadeTween; // 0x80
	private Int64 m_cachedNextRequestTs; // 0x88
	private Boolean m_isInited; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnPause; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__GetJoystickAxis; // 0x30
	private static DelegateBridge __Hotfix0__ShowOrHideArrow; // 0x38
	private static DelegateBridge __Hotfix0__ShowOrHideEmojiPanel; // 0x40
	private static DelegateBridge __Hotfix0__OnEmojiListBtnClick; // 0x48
	private static DelegateBridge __Hotfix0__TryToSendSendEmojiRequest; // 0x50
	private static DelegateBridge __Hotfix0_OnBackBtnClicked; // 0x58
	private static DelegateBridge __Hotfix0_OnTouchBtnClicked; // 0x60
	private static DelegateBridge __Hotfix0_OnUpstairsBtnClicked; // 0x68
	private static DelegateBridge __Hotfix0_OnDownstairsBtnClicked; // 0x70
	private static DelegateBridge __Hotfix0_OnEmojiBtnClicked; // 0x78
	private static DelegateBridge __Hotfix0_OnShowAndHideBtnClicked; // 0x80
	private static DelegateBridge __Hotfix0_get_moveDir; // 0x88
	private static DelegateBridge __Hotfix0_set_moveDir; // 0x90
	private static DelegateBridge __Hotfix0_OnMoverStateChanged; // 0x98
	private static DelegateBridge __Hotfix0_OnMessage; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public Vector2 moveDir { get; set; }

	// RVA: 0x3d2fdf0 VA: 0x7596347df0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d2fe58 VA: 0x7596347e58
	protected override Void OnEnter() { }
	// RVA: 0x3d30314 VA: 0x7596348314
	protected override Void OnResume() { }
	// RVA: 0x3d303b0 VA: 0x75963483b0
	protected override Void OnPause() { }
	// RVA: 0x3d3044c VA: 0x759634844c
	private Void Update() { }
	// RVA: 0x3d2ff94 VA: 0x7596347f94
	private Void _InitIfNot() { }
	// RVA: 0x3d30618 VA: 0x7596348618
	private Vector2 _GetJoystickAxis() { }
	// RVA: 0x3d30700 VA: 0x7596348700
	private Void _ShowOrHideArrow(Boolean isShow) { }
	// RVA: 0x3d307fc VA: 0x75963487fc
	private Void _ShowOrHideEmojiPanel() { }
	// RVA: 0x3d308b8 VA: 0x75963488b8
	private Void _OnEmojiListBtnClick(String emojiId) { }
	// RVA: 0x3d30a3c VA: 0x7596348a3c
	private Void _TryToSendSendEmojiRequest(String emojiId) { }
	// RVA: 0x3d30c00 VA: 0x7596348c00
	public Void OnBackBtnClicked() { }
	// RVA: 0x3d30d80 VA: 0x7596348d80
	public Void OnTouchBtnClicked() { }
	// RVA: 0x3d30e0c VA: 0x7596348e0c
	public Void OnUpstairsBtnClicked() { }
	// RVA: 0x3d30f2c VA: 0x7596348f2c
	public Void OnDownstairsBtnClicked() { }
	// RVA: 0x3d3104c VA: 0x759634904c
	public Void OnEmojiBtnClicked() { }
	// RVA: 0x3d310b4 VA: 0x75963490b4
	public Void OnShowAndHideBtnClicked() { }
	// RVA: 0x3d31170 VA: 0x7596349170
	public Vector2 get_moveDir() { }
	// RVA: 0x3d311d8 VA: 0x75963491d8
	public Void set_moveDir(Vector2 value) { }
	// RVA: 0x3d31258 VA: 0x7596349258
	public Void OnMoverStateChanged() { }
	// RVA: 0x3d31474 VA: 0x7596349474
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3d31548 VA: 0x7596349548
	public Void .ctor() { }
	// RVA: 0x3d316e8 VA: 0x75963496e8
	private Void <_TryToSendSendEmojiRequest>b__22_0(BuildingSendEmojiResponse response) { }
	// RVA: 0x3d31704 VA: 0x7596349704
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d3170c VA: 0x759634970c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3d31714 VA: 0x7596349714
	private Void <>xLuaBaseProxy_OnPause() { }
}
```