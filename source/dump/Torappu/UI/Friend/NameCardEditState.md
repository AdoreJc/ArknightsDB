# NameCardEditState

**Namespace:** `Torappu.UI.Friend`


## Fields

- `RectTransform _backRect`

- `RectTransform _nameCardContainer`

- `Single _nameCardScale`

- `RectTransform _moduleListContainer`

- `FriendStateControl _stateControl`

- `NameCardV2BirthButtonView _birthButtonView`

- `NameCardV2EditOpenModuleContainerBtnView _openModuleContainerBtnView`

- `UIAnimationLocation _containerShowAnim`

- `Single _duration`

- `NameCardV2EditStateBean m_stateBean`

- `Boolean m_hasInited`

- `AnimationSwitchTween m_tween`

- `NameCardV2View m_nameCard`

- `NameCardV2ModuleContainerView m_moduleList`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _SelectModule(String)`

- `Void _UnselectModule(String)`

- `Void _CloseModuleContainer()`

- `Void _SwitchDateMode()`

- `Void _SetBirth()`

- `Void _OpenModuleContainer()`

- `Void CloseState()`

- `Void CloseModuleContainer()`

- `Void <CloseState>b__31_0(EditNameCardResponse)`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardEditState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 SELECT_MODULE; // 0x0
	public const Int32 UNSELECT_MODULE; // 0x0
	public const Int32 CLOSE_MODULE_CONTAINER; // 0x0
	public const Int32 SWITCH_DATE_MODE; // 0x0
	public const Int32 SET_BIRTH; // 0x0
	public const Int32 OPEN_MODULE_CONTAINER; // 0x0
	private RectTransform _backRect; // 0x70
	private RectTransform _nameCardContainer; // 0x78
	private Single _nameCardScale; // 0x80
	private RectTransform _moduleListContainer; // 0x88
	private FriendStateControl _stateControl; // 0x90
	private NameCardV2BirthButtonView _birthButtonView; // 0x98
	private NameCardV2EditOpenModuleContainerBtnView _openModuleContainerBtnView; // 0xa0
	private UIAnimationLocation _containerShowAnim; // 0xa8
	private Single _duration; // 0xb8
	private NameCardV2EditStateBean m_stateBean; // 0xc0
	private Boolean m_hasInited; // 0xc8
	private AnimationSwitchTween m_tween; // 0xd0
	private NameCardV2View m_nameCard; // 0xd8
	private NameCardV2ModuleContainerView m_moduleList; // 0xe0
	private List`1 m_cachedSelectedModuleList; // 0xe8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__SelectModule; // 0x20
	private static DelegateBridge __Hotfix0__UnselectModule; // 0x28
	private static DelegateBridge __Hotfix0__CloseModuleContainer; // 0x30
	private static DelegateBridge __Hotfix0__SwitchDateMode; // 0x38
	private static DelegateBridge __Hotfix0__SetBirth; // 0x40
	private static DelegateBridge __Hotfix0__OpenModuleContainer; // 0x48
	private static DelegateBridge __Hotfix0_CloseState; // 0x50
	private static DelegateBridge __Hotfix0_CloseModuleContainer; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x28b64c8 VA: 0x7594ece4c8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28b6530 VA: 0x7594ece530
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x28b66a0 VA: 0x7594ece6a0
	private Void _InitIfNot() { }
	// RVA: 0x28b6fac VA: 0x7594ecefac
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x28b70ec VA: 0x7594ecf0ec
	private Void _SelectModule(String moduleId) { }
	// RVA: 0x28b7224 VA: 0x7594ecf224
	private Void _UnselectModule(String moduleId) { }
	// RVA: 0x28b7304 VA: 0x7594ecf304
	private Void _CloseModuleContainer() { }
	// RVA: 0x28b7410 VA: 0x7594ecf410
	private Void _SwitchDateMode() { }
	// RVA: 0x28b765c VA: 0x7594ecf65c
	private Void _SetBirth() { }
	// RVA: 0x28b7814 VA: 0x7594ecf814
	private Void _OpenModuleContainer() { }
	// RVA: 0x28b7ca4 VA: 0x7594ecfca4
	public Void CloseState() { }
	// RVA: 0x28b7f54 VA: 0x7594ecff54
	public Void CloseModuleContainer() { }
	// RVA: 0x28b7fbc VA: 0x7594ecffbc
	public Void .ctor() { }
	// RVA: 0x28b8124 VA: 0x7594ed0124
	private Void <CloseState>b__31_0(EditNameCardResponse response) { }
	// RVA: 0x28b8134 VA: 0x7594ed0134
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
}
```