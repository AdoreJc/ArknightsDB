# TuningPlayState

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `RectTransform _topMenuContainer`

- `TuningPlayView _playView`

- `TuningPlayMenuView _menuView`

- `TuningPlayStateBean m_stateBean`

- `Boolean m_isInited`

- `String m_actId`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void _PlayCurMusic(Boolean)`

- `Void _TransToMusicHandBook()`

- `Void _OpenOrche()`

- `Void _CloseOrche()`

- `Void _SelectOrche(String)`

- `Void _OnBackBtnPressed()`

- `Void _OnTransToHandBookState(IStateBean)`

- `Void _OnTransToProductState(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningPlayState : PopupFadeState, IHotfixable, IValueMsgReceiver
{
	private RectTransform _topMenuContainer; // 0x70
	private TuningPlayView _playView; // 0x78
	private TuningPlayMenuView _menuView; // 0x80
	private TuningPlayStateBean m_stateBean; // 0x88
	private Boolean m_isInited; // 0x90
	private String m_actId; // 0x98
	public const Int32 TRANS_TO_MUSIC_HAND_BOOK; // 0x0
	public const Int32 OPEN_ORCHE; // 0x0
	public const Int32 CLOSE_ORCHE; // 0x0
	public const Int32 BACK_TO_PRODUCT; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__PlayCurMusic; // 0x30
	private static DelegateBridge __Hotfix0__TransToMusicHandBook; // 0x38
	private static DelegateBridge __Hotfix0__OpenOrche; // 0x40
	private static DelegateBridge __Hotfix0__CloseOrche; // 0x48
	private static DelegateBridge __Hotfix0__SelectOrche; // 0x50
	private static DelegateBridge __Hotfix0__OnBackBtnPressed; // 0x58
	private static DelegateBridge __Hotfix0__OnTransToHandBookState; // 0x60
	private static DelegateBridge __Hotfix0__OnTransToProductState; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x232faf0 VA: 0x7594947af0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x232fb58 VA: 0x7594947b58
	protected override Void OnEnter() { }
	// RVA: 0x23300c4 VA: 0x75949480c4
	protected override Void OnResume() { }
	// RVA: 0x23302cc VA: 0x75949482cc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x23304c0 VA: 0x75949484c0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x232fc84 VA: 0x7594947c84
	private Void _InitIfNot() { }
	// RVA: 0x232ff04 VA: 0x7594947f04
	private Void _PlayCurMusic(Boolean isMainMusicFromStart) { }
	// RVA: 0x23305c8 VA: 0x75949485c8
	private Void _TransToMusicHandBook() { }
	// RVA: 0x2330750 VA: 0x7594948750
	private Void _OpenOrche() { }
	// RVA: 0x233086c VA: 0x759494886c
	private Void _CloseOrche() { }
	// RVA: 0x2330e7c VA: 0x7594948e7c
	private Void _SelectOrche(String orcheId) { }
	// RVA: 0x2330988 VA: 0x7594948988
	private Void _OnBackBtnPressed() { }
	// RVA: 0x2331070 VA: 0x7594949070
	private Void _OnTransToHandBookState(IStateBean stateBean) { }
	// RVA: 0x23311f8 VA: 0x75949491f8
	private Void _OnTransToProductState(IStateBean stateBean) { }
	// RVA: 0x23312d8 VA: 0x75949492d8
	public Void .ctor() { }
	// RVA: 0x2331430 VA: 0x7594949430
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2331438 VA: 0x7594949438
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2331440 VA: 0x7594949440
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```