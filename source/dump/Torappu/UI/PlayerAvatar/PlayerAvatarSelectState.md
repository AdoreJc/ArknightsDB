# PlayerAvatarSelectState

**Namespace:** `Torappu.UI.PlayerAvatar`


## Fields

- `PlayerAvatarGroupListView _listView`

- `PlayerAvatarSelectStateBean _stateBean`

- `RectTransform _btnBack`

- `Text _levelText`

- `RectTransform _avatarContainer`

- `Text _descText`

- `Boolean m_isInited`

- `PlayerAvatarView m_displayAvatar`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateAvatarIconAndDesc(PlayerAvatarItemViewModel)`

- `Void OnClickAvatarEvent(PlayerAvatarItemViewModel)`

- `Void OnClickSendNewAvatar()`

- `Void ClosePage()`

- `Void <_InitIfNot>b__9_0()`

- `Void <OnClickSendNewAvatar>b__13_0(ChangeAvatarResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.PlayerAvatar
public class PlayerAvatarSelectState : PopupFloatState
{
	private PlayerAvatarGroupListView _listView; // 0x70
	private PlayerAvatarSelectStateBean _stateBean; // 0x78
	private RectTransform _btnBack; // 0x80
	private Text _levelText; // 0x88
	private RectTransform _avatarContainer; // 0x90
	private Text _descText; // 0x98
	private Boolean m_isInited; // 0xa0
	private PlayerAvatarView m_displayAvatar; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__UpdateAvatarIconAndDesc; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnClickAvatarEvent; // 0x20
	private static DelegateBridge __Hotfix0_OnClickSendNewAvatar; // 0x28
	private static DelegateBridge __Hotfix0_ClosePage; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2723b50 VA: 0x7594d3bb50
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2723bb8 VA: 0x7594d3bbb8
	private Void _InitIfNot() { }
	// RVA: 0x2723d3c VA: 0x7594d3bd3c
	private Void _UpdateAvatarIconAndDesc(PlayerAvatarItemViewModel viewModel) { }
	// RVA: 0x2724058 VA: 0x7594d3c058
	protected override Void OnEnter() { }
	// RVA: 0x27248fc VA: 0x7594d3c8fc
	public Void OnClickAvatarEvent(PlayerAvatarItemViewModel viewModel) { }
	// RVA: 0x2724a50 VA: 0x7594d3ca50
	public Void OnClickSendNewAvatar() { }
	// RVA: 0x2724c9c VA: 0x7594d3cc9c
	public Void ClosePage() { }
	// RVA: 0x2724d18 VA: 0x7594d3cd18
	public Void .ctor() { }
	// RVA: 0x2724d88 VA: 0x7594d3cd88
	private Void <_InitIfNot>b__9_0() { }
	// RVA: 0x2724da8 VA: 0x7594d3cda8
	private Void <OnClickSendNewAvatar>b__13_0(ChangeAvatarResponse response) { }
	// RVA: 0x2724dac VA: 0x7594d3cdac
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```