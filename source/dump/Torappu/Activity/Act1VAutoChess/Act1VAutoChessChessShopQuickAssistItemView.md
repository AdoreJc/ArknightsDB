# Act1VAutoChessChessShopQuickAssistItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _imgChessLevelReplace`

- `Image _imgChessLevelNotHave`

- `UIAtlasImage _imgBackupCharPortraitReplace`

- `UIAtlasImage _imgBackupCharPortraitNotHave`

- `RectTransform _transCardHolder`

- `Act1VAutoChessShopCharChessCardView _cardViewPrefab`

- `GameObject _objFriendAliasInfo`

- `Text _txtFriendAlias`

- `GameObject _objFriendBaseInfo`

- `Text _txtFriendNickName`

- `Text _txtFriendCode`

- `TwoStateToggle _btnAssistState`

- `UIAnimationLocation _stateAnim`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `Act1VAutoChessShopCharChessCardView m_cardView`

- `Boolean m_cachedIsAssisting`

- `Boolean m_cachedCanAssistMore`

- `String m_cachedFriendUid`

- `String m_cachedChessId`

- `AssistItemInfo m_cachedAssistItemInfo`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_animSwitchTween`


## Methods

- `Void Render(Act1VAutoChessChessShopQuickAssistItemViewModel)`

- `Void _InitIfNot()`

- `Void _PlayStateChangeAnim(Boolean, Boolean)`

- `Void OnCancelClick()`

- `Void OnAssistClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopQuickAssistItemView : MonoBehaviour, IHotfixable
{
	private Image _imgChessLevelReplace; // 0x18
	private Image _imgChessLevelNotHave; // 0x20
	private UIAtlasImage _imgBackupCharPortraitReplace; // 0x28
	private UIAtlasImage _imgBackupCharPortraitNotHave; // 0x30
	private RectTransform _transCardHolder; // 0x38
	private Act1VAutoChessShopCharChessCardView _cardViewPrefab; // 0x40
	private GameObject _objFriendAliasInfo; // 0x48
	private Text _txtFriendAlias; // 0x50
	private GameObject _objFriendBaseInfo; // 0x58
	private Text _txtFriendNickName; // 0x60
	private Text _txtFriendCode; // 0x68
	private TwoStateToggle _btnAssistState; // 0x70
	private UIAnimationLocation _stateAnim; // 0x78
	private Boolean m_hasInited; // 0x88
	private UIStateFinder m_stateFinder; // 0x90
	private Act1VAutoChessShopCharChessCardView m_cardView; // 0xa0
	private Boolean m_cachedIsAssisting; // 0xa8
	private Boolean m_cachedCanAssistMore; // 0xa9
	private String m_cachedFriendUid; // 0xb0
	private String m_cachedChessId; // 0xb8
	private AssistItemInfo m_cachedAssistItemInfo; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private AnimationSwitchTween m_animSwitchTween; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__PlayStateChangeAnim; // 0x10
	private static DelegateBridge __Hotfix0_OnCancelClick; // 0x18
	private static DelegateBridge __Hotfix0_OnAssistClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x331e3ac VA: 0x75959363ac
	public Void Render(Act1VAutoChessChessShopQuickAssistItemViewModel itemViewModel) { }
	// RVA: 0x331e9e0 VA: 0x75959369e0
	private Void _InitIfNot() { }
	// RVA: 0x331ee80 VA: 0x7595936e80
	private Void _PlayStateChangeAnim(Boolean isToBorrowState, Boolean isFastMode) { }
	// RVA: 0x331ef28 VA: 0x7595936f28
	public Void OnCancelClick() { }
	// RVA: 0x331f020 VA: 0x7595937020
	public Void OnAssistClick() { }
	// RVA: 0x331f160 VA: 0x7595937160
	public Void .ctor() { }
}
```