# HomeMailArchiveDetailState

**Namespace:** `Torappu.UI.Home`


## Fields

- `RectTransform _bactRect`

- `HomeMailArchiveDetailView _view`

- `Boolean m_hasInited`

- `HomeMailArchiveDetailStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void EventOnBackClicked()`

- `Void _InitIfNot()`

- `Void _OnCloseImpl()`

- `Void _OnPrevClick()`

- `Void _OnNextClick()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveDetailState : PopupFloatState, IValueMsgReceiver, IHotfixable
{
	private RectTransform _bactRect; // 0x70
	private HomeMailArchiveDetailView _view; // 0x78
	private Boolean m_hasInited; // 0x80
	private HomeMailArchiveDetailStateBean m_stateBean; // 0x88
	public const Int32 ON_PREV_CLICK; // 0x0
	public const Int32 ON_NEXT_CLICK; // 0x0
	public const Int32 ON_CLOSE_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnCloseImpl; // 0x28
	private static DelegateBridge __Hotfix0__OnPrevClick; // 0x30
	private static DelegateBridge __Hotfix0__OnNextClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x27f2d20 VA: 0x7594e0ad20
	protected override Void OnEnter() { }
	// RVA: 0x27f2f3c VA: 0x7594e0af3c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27f2fa4 VA: 0x7594e0afa4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x27f3418 VA: 0x7594e0b418
	public Void EventOnBackClicked() { }
	// RVA: 0x27f2e00 VA: 0x7594e0ae00
	private Void _InitIfNot() { }
	// RVA: 0x27f32d4 VA: 0x7594e0b2d4
	private Void _OnCloseImpl() { }
	// RVA: 0x27f3084 VA: 0x7594e0b084
	private Void _OnPrevClick() { }
	// RVA: 0x27f31a0 VA: 0x7594e0b1a0
	private Void _OnNextClick() { }
	// RVA: 0x27f3480 VA: 0x7594e0b480
	public Void .ctor() { }
	// RVA: 0x27f35dc VA: 0x7594e0b5dc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```