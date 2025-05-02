# ArchiveChatRecordListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _panelText`

- `GameObject _panelLock`

- `GameObject _panelLockText`

- `SimpleLayoutContent _textContent`

- `SimpleLayoutContent _circleContent`

- `ScrollRect _contentRect`

- `Image _backImage`

- `Text _count`

- `Text _countAll`

- `Text _desc`

- `Text _descIndexText`

- `Text _nameText`

- `Text _subNameText`

- `Text _flavorDescText`

- `RectTransform _charIllustHolder`

- `UIAnimationLocation _animLocation`

- `ActArchiveController m_controller`

- `ActArchiveProxy m_proxy`

- `RecordItemAdapter m_itemAdapter`

- `RecordCircleAdapter m_circleAdapter`

- `Boolean m_isInited`

- `Int32 m_cachedSelectedIndex`

- `GameObject m_charIllust`

- `String m_cachedCharId`

- `UIPageFinder m_pageFinder`


## Properties

- `ActArchiveController controller`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `Void _InitIfNot()`

- `Void _ResetScrollPosition()`

- `Void _PlaySwitchAnim()`

- `Void _LoadCharIllust(RoguelikeTopicMonthSquadTeamChar)`

- `Void OnNextClicked()`

- `Void OnBackClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChatRecordListDataBinder : DataBinder`1
{
	private GameObject _panelText; // 0x20
	private GameObject _panelLock; // 0x28
	private GameObject _panelLockText; // 0x30
	private SimpleLayoutContent _textContent; // 0x38
	private SimpleLayoutContent _circleContent; // 0x40
	private ScrollRect _contentRect; // 0x48
	private Image _backImage; // 0x50
	private Text _count; // 0x58
	private Text _countAll; // 0x60
	private Text _desc; // 0x68
	private Text _descIndexText; // 0x70
	private Text _nameText; // 0x78
	private Text _subNameText; // 0x80
	private Text _flavorDescText; // 0x88
	private RectTransform _charIllustHolder; // 0x90
	private UIAnimationLocation _animLocation; // 0x98
	private ActArchiveController m_controller; // 0xa8
	private ActArchiveProxy m_proxy; // 0xb0
	private RecordItemAdapter m_itemAdapter; // 0xb8
	private RecordCircleAdapter m_circleAdapter; // 0xc0
	private Boolean m_isInited; // 0xc8
	private Int32 m_cachedSelectedIndex; // 0xcc
	private ListDict`2 m_cachedItems; // 0xd0
	private GameObject m_charIllust; // 0xd8
	private String m_cachedCharId; // 0xe0
	private UIPageFinder m_pageFinder; // 0xe8
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__ResetScrollPosition; // 0x20
	private static DelegateBridge __Hotfix0__PlaySwitchAnim; // 0x28
	private static DelegateBridge __Hotfix0__LoadCharIllust; // 0x30
	private static DelegateBridge __Hotfix0_OnNextClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private ActArchiveController controller { get; set; }

	// RVA: 0x3046868 VA: 0x759565e868
	private ActArchiveController get_controller() { }
	// RVA: 0x30468d0 VA: 0x759565e8d0
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x3046aac VA: 0x759565eaac
	public override Void OnValueChanged(ChatProperty property) { }
	// RVA: 0x304695c VA: 0x759565e95c
	private Void _InitIfNot() { }
	// RVA: 0x304734c VA: 0x759565f34c
	private Void _ResetScrollPosition() { }
	// RVA: 0x3046f68 VA: 0x759565ef68
	private Void _PlaySwitchAnim() { }
	// RVA: 0x3047060 VA: 0x759565f060
	private Void _LoadCharIllust(RoguelikeTopicMonthSquadTeamChar teamChar) { }
	// RVA: 0x3047568 VA: 0x759565f568
	public Void OnNextClicked() { }
	// RVA: 0x3047720 VA: 0x759565f720
	public Void OnBackClicked() { }
	// RVA: 0x30478d8 VA: 0x759565f8d8
	public Void .ctor() { }
}
```