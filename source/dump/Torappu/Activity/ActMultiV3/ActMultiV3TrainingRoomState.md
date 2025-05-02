# ActMultiV3TrainingRoomState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `RectTransform _topMenuContainer`

- `ActMultiV3TrainingRoomView _view`

- `Boolean m_inited`

- `String m_actId`

- `ActMultiV3TrainingRoomProperty m_property`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnModeBtnClicked(Int64)`

- `Void _EventOnBtnBack()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3TrainingRoomState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 MSG_BTN_CLICKED; // 0x0
	private RectTransform _topMenuContainer; // 0x70
	private ActMultiV3TrainingRoomView _view; // 0x78
	private Boolean m_inited; // 0x80
	private String m_actId; // 0x88
	private ActMultiV3TrainingRoomProperty m_property; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OnModeBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3153424 VA: 0x759576b424
	private Void _InitIfNot() { }
	// RVA: 0x31535b4 VA: 0x759576b5b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3153618 VA: 0x759576b618
	protected override Void OnEnter() { }
	// RVA: 0x3153f60 VA: 0x759576bf60
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3154030 VA: 0x759576c030
	private Void _OnModeBtnClicked(Int64 msg) { }
	// RVA: 0x3154194 VA: 0x759576c194
	private Void _EventOnBtnBack() { }
	// RVA: 0x31542e4 VA: 0x759576c2e4
	public Void .ctor() { }
	// RVA: 0x31543fc VA: 0x759576c3fc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```