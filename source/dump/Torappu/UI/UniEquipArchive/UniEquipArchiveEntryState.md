# UniEquipArchiveEntryState

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `UniEquipArchiveEntryView _view`

- `Boolean m_isInited`

- `UniEquipArchiveEntryStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnOpenCharState()`

- `Void _OnOpenModuleState()`

- `Void _OnNewEditionItemClick(String)`

- `Void _OnNewEditionItemCharPartClick(String)`

- `Void _OnSwitchInfoBtnClick()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveEntryState : PopupFadeState, IValueMsgReceiver
{
	private UniEquipArchiveEntryView _view; // 0x70
	private Boolean m_isInited; // 0x78
	private UniEquipArchiveEntryStateBean m_stateBean; // 0x80
	public const Int32 ON_OPEN_CHAR_CLICK; // 0x0
	public const Int32 ON_OPEN_MODULE_CLICK; // 0x0
	public const Int32 ON_NEW_EDITION_ITEM_CLICK; // 0x0
	public const Int32 ON_NEW_EDITION_ITEM_CHAR_PART_CLICK; // 0x0
	public const Int32 ON_SWITCH_INFO_BTN_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__OnOpenCharState; // 0x28
	private static DelegateBridge __Hotfix0__OnOpenModuleState; // 0x30
	private static DelegateBridge __Hotfix0__OnNewEditionItemClick; // 0x38
	private static DelegateBridge __Hotfix0__OnNewEditionItemCharPartClick; // 0x40
	private static DelegateBridge __Hotfix0__OnSwitchInfoBtnClick; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x22e6edc VA: 0x75948feedc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22e6f44 VA: 0x75948fef44
	private Void _InitIfNot() { }
	// RVA: 0x22e6ff4 VA: 0x75948feff4
	protected override Void OnEnter() { }
	// RVA: 0x22e7124 VA: 0x75948ff124
	protected override Void OnResume() { }
	// RVA: 0x22e71f8 VA: 0x75948ff1f8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x22e7320 VA: 0x75948ff320
	private Void _OnOpenCharState() { }
	// RVA: 0x22e7464 VA: 0x75948ff464
	private Void _OnOpenModuleState() { }
	// RVA: 0x22e75b0 VA: 0x75948ff5b0
	private Void _OnNewEditionItemClick(String uniEquipId) { }
	// RVA: 0x22e7774 VA: 0x75948ff774
	private Void _OnNewEditionItemCharPartClick(String uniEquipId) { }
	// RVA: 0x22e7884 VA: 0x75948ff884
	private Void _OnSwitchInfoBtnClick() { }
	// RVA: 0x22e7cd0 VA: 0x75948ffcd0
	public Void .ctor() { }
	// RVA: 0x22e7e2c VA: 0x75948ffe2c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22e7e34 VA: 0x75948ffe34
	private Void <>xLuaBaseProxy_OnResume() { }
}
```