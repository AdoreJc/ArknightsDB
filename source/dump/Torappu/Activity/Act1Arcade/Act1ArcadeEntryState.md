# Act1ArcadeEntryState

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeEntryView _view`

- `CustomPageActivityStateEntryComp _entryComp`

- `Boolean m_isInited`

- `String m_cachedClickedEntryZoneId`

- `String m_actId`

- `Act1ArcadeStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void OnTrigEntryAnim(Boolean)`

- `Void _OnClickBack()`

- `Void _GotoOtherState()`

- `Void _OnJumpToStageSelectState(IStateBean)`

- `Void _OnJumpToBadgeBookState(IStateBean)`

- `Void _OnClickMedalEntry()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeEntryState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 MSG_ON_GAME_ENTRY_CLICK; // 0x0
	public const Int32 MSG_ON_BADGE_ENTRY_CLICK; // 0x0
	public const Int32 MSG_ON_MILE_STONE_CLICK; // 0x0
	public const Int32 MSG_ON_MEDAL_ENTRY_CLICK; // 0x0
	private Act1ArcadeEntryView _view; // 0x70
	private CustomPageActivityStateEntryComp _entryComp; // 0x78
	private Boolean m_isInited; // 0x80
	private String m_cachedClickedEntryZoneId; // 0x88
	private String m_actId; // 0x90
	private Act1ArcadeStateBean m_stateBean; // 0x98
	private static DelegateBridge __Hotfix0_OnMessage; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x20
	private static DelegateBridge __Hotfix0_OnTrigEntryAnim; // 0x28
	private static DelegateBridge __Hotfix0__OnClickBack; // 0x30
	private static DelegateBridge __Hotfix0__GotoOtherState; // 0x38
	private static DelegateBridge __Hotfix0__OnJumpToStageSelectState; // 0x40
	private static DelegateBridge __Hotfix0__OnJumpToBadgeBookState; // 0x48
	private static DelegateBridge __Hotfix0__OnClickMedalEntry; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x33feeb4 VA: 0x7595a16eb4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x33ff24c VA: 0x7595a1724c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x33ff2b4 VA: 0x7595a172b4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x33ff4a8 VA: 0x7595a174a8
	private Void _InitIfNot() { }
	// RVA: 0x33ff700 VA: 0x7595a17700
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x33ffad0 VA: 0x7595a17ad0
	public Void OnTrigEntryAnim(Boolean skipAnim) { }
	// RVA: 0x33ffc6c VA: 0x7595a17c6c
	private Void _OnClickBack() { }
	// RVA: 0x VA: 0x0
	private Void _GotoOtherState() { }
	// RVA: 0x33ffe10 VA: 0x7595a17e10
	private Void _OnJumpToStageSelectState(IStateBean stateBean) { }
	// RVA: 0x33ffef0 VA: 0x7595a17ef0
	private Void _OnJumpToBadgeBookState(IStateBean bean) { }
	// RVA: 0x33ff030 VA: 0x7595a17030
	private Void _OnClickMedalEntry() { }
	// RVA: 0x3400010 VA: 0x7595a18010
	public Void .ctor() { }
	// RVA: 0x3400168 VA: 0x7595a18168
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3400170 VA: 0x7595a18170
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
}
```