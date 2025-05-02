# NameCardState

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Transform _cardContainer`

- `NameCardV2ChangeSkinButtonView _changeSkinButtonView`

- `NameCardV2EditButtonView _editButtonView`

- `FriendStateControl _stateControl`

- `NameCardV2StateBean m_stateBean`

- `NameCardV2View m_nameCardView`

- `Boolean m_hasNameCardInited`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OpenAvatarPage()`

- `Void _OpenMedalSettings()`

- `Void _SwitchOperatorCountStyle(String)`

- `Void _SwitchAssistModuleStyle(String)`

- `Void _SwitchEquipModuleStyle(String)`

- `Void _ToChangeSkin()`

- `Void _OpenAssistState()`

- `Void _OnStartChangeResume()`

- `Void _OnEditResumeFinished(Boolean)`

- `Void _CrossAppShare(String, Int32, Boolean)`

- `Void _ExtendNameCard(Boolean)`

- `Void _OpenNameCardEditState()`

- `Boolean _IsStateStable()`

- `Void _InitNameCardIfNot()`

- `Void OpenLarge()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardState : State, IValueMsgReceiver
{
	public const Int32 OPEN_AVATAR_PAGE; // 0x0
	public const Int32 OPEN_FRIEND_MEDAL_STATE; // 0x0
	public const Int32 SWITCH_OPERATOR_COUNT_STYLE; // 0x0
	public const Int32 SWITCH_ASSIST_MODULE_STYLE; // 0x0
	public const Int32 OPEN_ASSIST_STATE; // 0x0
	public const Int32 START_CHANGE_RESUME; // 0x0
	public const Int32 CROSS_APP_SHARE; // 0x0
	public const Int32 CROSS_APP_SHARE_SIMPLE; // 0x0
	public const Int32 EXTEND_NAMECARD; // 0x0
	public const Int32 OPEN_EDIT_STATE; // 0x0
	public const Int32 SWITCH_EQUIP_MODULE_STYLE; // 0x0
	public const Int32 TO_SKIN_CHANGE; // 0x0
	private Transform _cardContainer; // 0x50
	private NameCardV2ChangeSkinButtonView _changeSkinButtonView; // 0x58
	private NameCardV2EditButtonView _editButtonView; // 0x60
	private FriendStateControl _stateControl; // 0x68
	private NameCardV2StateBean m_stateBean; // 0x70
	private NameCardV2View m_nameCardView; // 0x78
	private Boolean m_hasNameCardInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OpenAvatarPage; // 0x20
	private static DelegateBridge __Hotfix0__OpenMedalSettings; // 0x28
	private static DelegateBridge __Hotfix0__SwitchOperatorCountStyle; // 0x30
	private static DelegateBridge __Hotfix0__SwitchAssistModuleStyle; // 0x38
	private static DelegateBridge __Hotfix0__SwitchEquipModuleStyle; // 0x40
	private static DelegateBridge __Hotfix0__ToChangeSkin; // 0x48
	private static DelegateBridge __Hotfix0__OpenAssistState; // 0x50
	private static DelegateBridge __Hotfix0__OnStartChangeResume; // 0x58
	private static DelegateBridge __Hotfix0__OnEditResumeFinished; // 0x60
	private static DelegateBridge __Hotfix0__CrossAppShare; // 0x68
	private static DelegateBridge __Hotfix0__ExtendNameCard; // 0x70
	private static DelegateBridge __Hotfix0__OpenNameCardEditState; // 0x78
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x80
	private static DelegateBridge __Hotfix0__InitNameCardIfNot; // 0x88
	private static DelegateBridge __Hotfix0_OpenLarge; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x28b9f60 VA: 0x7594ed1f60
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28b9fc8 VA: 0x7594ed1fc8
	protected override Void OnEnter() { }
	// RVA: 0x28ba250 VA: 0x7594ed2250
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x28ba35c VA: 0x7594ed235c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x28ba570 VA: 0x7594ed2570
	private Void _OpenAvatarPage() { }
	// RVA: 0x28ba608 VA: 0x7594ed2608
	private Void _OpenMedalSettings() { }
	// RVA: 0x28ba720 VA: 0x7594ed2720
	private Void _SwitchOperatorCountStyle(String moduleId) { }
	// RVA: 0x28ba814 VA: 0x7594ed2814
	private Void _SwitchAssistModuleStyle(String moduleId) { }
	// RVA: 0x28bb128 VA: 0x7594ed3128
	private Void _SwitchEquipModuleStyle(String moduleId) { }
	// RVA: 0x28bb21c VA: 0x7594ed321c
	private Void _ToChangeSkin() { }
	// RVA: 0x28ba908 VA: 0x7594ed2908
	private Void _OpenAssistState() { }
	// RVA: 0x28ba990 VA: 0x7594ed2990
	private Void _OnStartChangeResume() { }
	// RVA: 0x28bb764 VA: 0x7594ed3764
	private Void _OnEditResumeFinished(Boolean isConfirmed) { }
	// RVA: 0x28bab2c VA: 0x7594ed2b2c
	private Void _CrossAppShare(String skinId, Int32 skinTmpl, Boolean isDetail) { }
	// RVA: 0x28bae14 VA: 0x7594ed2e14
	private Void _ExtendNameCard(Boolean isExtend) { }
	// RVA: 0x28bb058 VA: 0x7594ed3058
	private Void _OpenNameCardEditState() { }
	// RVA: 0x28bb32c VA: 0x7594ed332c
	private Boolean _IsStateStable() { }
	// RVA: 0x28ba04c VA: 0x7594ed204c
	private Void _InitNameCardIfNot() { }
	// RVA: 0x28bba28 VA: 0x7594ed3a28
	public Void OpenLarge() { }
	// RVA: 0x28bbb08 VA: 0x7594ed3b08
	public Void .ctor() { }
	// RVA: 0x28bbc60 VA: 0x7594ed3c60
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x28bbc68 VA: 0x7594ed3c68
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
}
```