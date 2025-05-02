# MeetingPeerSendClueView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Text _nickNameLabel`

- `Text _numberLabel`

- `Text _nameWithNumberLabel`

- `Text _levelLabel`

- `Text _commentLabel`

- `Text _lastLoginLabel`

- `Text _onlineLabel`

- `GameObject _onlinePanel`

- `GameObject _lastLoginPanel`

- `Text _socialCreditValueLabel`

- `Image _iconImage`

- `Transform _avatarContainer`

- `TwoStateToggle _nameCardBgToggle`

- `Image _imageBG`

- `IPeer m_peer`

- `IMeetingSession m_session`

- `Sprite m_originIcon`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`


## Methods

- `Void add_onSendCluePressed(Action`1)`

- `Void remove_onSendCluePressed(Action`1)`

- `Void _InitIfNot()`

- `Void Setup(MeetingPeerConfig)`

- `Void _RenderNameCardSkin(PlayerNameCardSkin)`

- `Void _UpdateOwningPanel(Int32)`

- `Void _RenderAvatarView(MeetingPeerConfig)`

- `Void OnSendCluePressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingPeerSendClueView : UIStylerApplier`1, IHotfixable
{
	private const String PLAYER_NUMBER_COLOR; // 0x0
	private Text _nickNameLabel; // 0x20
	private Text _numberLabel; // 0x28
	private Text _nameWithNumberLabel; // 0x30
	private Text _levelLabel; // 0x38
	private Text _commentLabel; // 0x40
	private Text _lastLoginLabel; // 0x48
	private Text _onlineLabel; // 0x50
	private GameObject _onlinePanel; // 0x58
	private GameObject _lastLoginPanel; // 0x60
	private Text _socialCreditValueLabel; // 0x68
	private Image _iconImage; // 0x70
	private MeetingPeerClueOwnView[] _owningPanels; // 0x78
	private Transform _avatarContainer; // 0x80
	private TwoStateToggle _nameCardBgToggle; // 0x88
	private Image _imageBG; // 0x90
	private IPeer m_peer; // 0x98
	private IMeetingSession m_session; // 0xa0
	private Sprite m_originIcon; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private Action`1 onSendCluePressed; // 0xc0
	private Boolean m_isInited; // 0xc8
	private static DelegateBridge __Hotfix0_add_onSendCluePressed; // 0x0
	private static DelegateBridge __Hotfix0_remove_onSendCluePressed; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Setup; // 0x18
	private static DelegateBridge __Hotfix0__RenderNameCardSkin; // 0x20
	private static DelegateBridge __Hotfix0__UpdateOwningPanel; // 0x28
	private static DelegateBridge __Hotfix0__RenderAvatarView; // 0x30
	private static DelegateBridge __Hotfix0_OnSendCluePressed; // 0x38
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3dfdee0 VA: 0x7596415ee0
	public Void add_onSendCluePressed(Action`1 value) { }
	// RVA: 0x3dfdfd4 VA: 0x7596415fd4
	public Void remove_onSendCluePressed(Action`1 value) { }
	// RVA: 0x3dfe0c8 VA: 0x75964160c8
	private Void _InitIfNot() { }
	// RVA: 0x3dfe19c VA: 0x759641619c
	public Void Setup(MeetingPeerConfig config) { }
	// RVA: 0x3dfeaa8 VA: 0x7596416aa8
	private Void _RenderNameCardSkin(PlayerNameCardSkin nameCardSkin) { }
	// RVA: 0x3dfec38 VA: 0x7596416c38
	private Void _UpdateOwningPanel(Int32 selectedClueCategory) { }
	// RVA: 0x3dff204 VA: 0x7596417204
	private Void _RenderAvatarView(MeetingPeerConfig config) { }
	// RVA: 0x3dff414 VA: 0x7596417414
	public Void OnSendCluePressed() { }
	// RVA: 0x3dff49c VA: 0x759641749c
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x3dff588 VA: 0x7596417588
	public Void .ctor() { }
}
```