# RoguelikeFriendAssistDetailView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _avatarContainer`

- `UIColorGraphic _avatarColorGraphic`

- `Text _textPlayerLv`

- `Text _textPlayerName`

- `Text _textPlayerNameNum`

- `Image _imgProfession`

- `Image _imgRarity`

- `Text _textCharName`

- `Image _imgRecruitElite`

- `Image _imgOrigElite`

- `Text _textRecruitLv`

- `Text _textOrigLv`

- `Text _textPopulation`

- `Color _colorEliteLimit`

- `Color _colorEliteNormal`

- `TwoStateToggle _toggleOnlineState`

- `Text _textLoginTime`

- `GameObject _requestFriendGo`

- `TwoStateToggle _toggleRequestFriend`

- `RectTransform _illustParent`

- `RoguelikePopBarView _popBarView`

- `Boolean m_inited`

- `PlayerAvatarView m_avatarView`

- `UICharacterIllust m_cacheIllustView`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `String m_cachedUid`


## Methods

- `Void ToggleRequestFriend()`

- `Void OnFriendAvatarClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFriendAssistDetailView : DataBinder`1
{
	private RectTransform _avatarContainer; // 0x20
	private UIColorGraphic _avatarColorGraphic; // 0x28
	private Text _textPlayerLv; // 0x30
	private Text _textPlayerName; // 0x38
	private Text _textPlayerNameNum; // 0x40
	private Image _imgProfession; // 0x48
	private Image _imgRarity; // 0x50
	private Text _textCharName; // 0x58
	private Image _imgRecruitElite; // 0x60
	private Image _imgOrigElite; // 0x68
	private Text _textRecruitLv; // 0x70
	private Text _textOrigLv; // 0x78
	private Text _textPopulation; // 0x80
	private Color _colorEliteLimit; // 0x88
	private Color _colorEliteNormal; // 0x98
	private TwoStateToggle _toggleOnlineState; // 0xa8
	private Text _textLoginTime; // 0xb0
	private GameObject _requestFriendGo; // 0xb8
	private TwoStateToggle _toggleRequestFriend; // 0xc0
	private RectTransform _illustParent; // 0xc8
	private RoguelikePopBarView _popBarView; // 0xd0
	private Boolean m_inited; // 0xd8
	private PlayerAvatarView m_avatarView; // 0xe0
	private UICharacterIllust m_cacheIllustView; // 0xe8
	private UIPageFinder m_pageFinder; // 0xf0
	private UIStateFinder m_stateFinder; // 0x100
	private String m_cachedUid; // 0x110
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_ToggleRequestFriend; // 0x8
	private static DelegateBridge __Hotfix0_OnFriendAvatarClick; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2a3816c VA: 0x759505016c
	public override Void OnValueChanged(RoguelikeFriendAssistDetailProp property) { }
	// RVA: 0x2a37de8 VA: 0x759504fde8
	public Void ToggleRequestFriend() { }
	// RVA: 0x2a38a50 VA: 0x7595050a50
	public Void OnFriendAvatarClick() { }
	// RVA: 0x2a38928 VA: 0x7595050928
	private Void _InitIfNot() { }
	// RVA: 0x2a38b40 VA: 0x7595050b40
	public Void .ctor() { }
}
```