# NameCardSkinListItemView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `UIStyleProvider _styleProvider`

- `Image _bgImg`

- `Text _playerNameText`

- `Text _playerIdText`

- `Transform _avatarContainer`

- `Single _avatarScale`

- `GameObject _selectedFrame`

- `GameObject _newSkinTrackPoint`

- `GameObject _hasSubSkinBtn`

- `UIAnimationLocation _subSkinSelectAnim`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `PlayerAvatarView m_avatarView`

- `AnimationSwitchTween m_subSkinSelectTween`

- `Boolean m_cachedIsSubSkinList`

- `Boolean m_cachedIsSelected`

- `NameCardSkinListItemViewModel m_cachedModel`


## Methods

- `Void _InitIfNot(Boolean)`

- `Void Render(NameCardSkinListItemViewModel, Boolean, Boolean, Boolean)`

- `Void OnSkinSelectClick()`

- `Void OnToChangeSubSkinClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardSkinListItemView : UIStylerApplier`1, IHotfixable
{
	private const String PLAYER_NAME_FORMAT; // 0x0
	private UIStyleProvider _styleProvider; // 0x20
	private Image _bgImg; // 0x28
	private Text _playerNameText; // 0x30
	private Text _playerIdText; // 0x38
	private Transform _avatarContainer; // 0x40
	private Single _avatarScale; // 0x48
	private GameObject _selectedFrame; // 0x50
	private GameObject _newSkinTrackPoint; // 0x58
	private GameObject _hasSubSkinBtn; // 0x60
	private UIAnimationLocation _subSkinSelectAnim; // 0x68
	private Boolean m_hasInited; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private UIStateFinder m_stateFinder; // 0x90
	private PlayerAvatarView m_avatarView; // 0xa0
	private AnimationSwitchTween m_subSkinSelectTween; // 0xa8
	private Boolean m_cachedIsSubSkinList; // 0xb0
	private Boolean m_cachedIsSelected; // 0xb1
	private NameCardSkinListItemViewModel m_cachedModel; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnSkinSelectClick; // 0x10
	private static DelegateBridge __Hotfix0_OnToChangeSubSkinClick; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfNameCardSkinUnlocked; // 0x20
	private static DelegateBridge __Hotfix0__ConsumeNameCardSkinTrack; // 0x28
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x28dd950 VA: 0x7594ef5950
	private Void _InitIfNot(Boolean isSubSkinSelected) { }
	// RVA: 0x28dd62c VA: 0x7594ef562c
	public Void Render(NameCardSkinListItemViewModel model, Boolean isSubSkinList, Boolean isSelected, Boolean subSkinFastMode) { }
	// RVA: 0x28ddbec VA: 0x7594ef5bec
	public Void OnSkinSelectClick() { }
	// RVA: 0x28dded0 VA: 0x7594ef5ed0
	public Void OnToChangeSubSkinClick() { }
	// RVA: 0x28ddb24 VA: 0x7594ef5b24
	private static Boolean _CheckIfNameCardSkinUnlocked(String skinId) { }
	// RVA: 0x28dde0c VA: 0x7594ef5e0c
	private static Void _ConsumeNameCardSkinTrack(String skinId) { }
	// RVA: 0x28ddfe0 VA: 0x7594ef5fe0
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28de150 VA: 0x7594ef6150
	public Void .ctor() { }
}
```