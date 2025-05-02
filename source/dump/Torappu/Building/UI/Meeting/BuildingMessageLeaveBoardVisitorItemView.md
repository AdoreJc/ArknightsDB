# BuildingMessageLeaveBoardVisitorItemView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `RectTransform _avatarContainer`

- `GameObject _avatarBorder`

- `Text _textVisitorLevel`

- `GameObject _visitorLevelHolder`

- `Text _textVisitorName`

- `GameObject _emojiHolder`

- `Image _emoji`

- `CanvasGroup _emojiCanvasGroup`

- `Button _btnPlayerInfo`

- `GameObject _panelNewVisitor`

- `UIAnimationLocation _animNewVisitor`

- `UIColorGraphic _headIconColorGraphic`

- `UIPageFinder m_pageFinder`

- `Tween m_newVisitorTween`

- `PayloadMessageBoardThisWeekVisitor m_thisWeekVisitor`

- `Sequence m_fadeSequence`

- `PlayerAvatarView m_avatarView`


## Methods

- `Void _RenderThisWeekVisitor(PayloadMessageBoardThisWeekVisitor, Int64, Action`1)`

- `Void _RenderLastWeekVisitor(PayloadMessageBoardLastWeekVisitor)`

- `Void _RenderEmoji(String)`

- `Void _RenderOtherWeekVisitor(PayloadOthersMessageBoardThisWeekVisitor)`

- `Void Render(IMessageBoardVisitorData, Int64, Action`1)`

- `Void _KillPrefAnim()`

- `Void _CheckAndPlayNewVisitorAnim(PayloadMessageBoardThisWeekVisitor, Int64)`

- `Void _PlayNewVisitorAnim()`

- `Void _RendBasicInfo(Boolean, IMessageBoardVisitorData, Boolean)`

- `Void _OnAnimEnd()`

- `Void EventOnClickAvatar()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMessageLeaveBoardVisitorItemView : MonoBehaviour, IHotfixable
{
	public const Single EMOJI_FADE_DELAY; // 0x0
	private const Single EMOJI_FADE_KEEP; // 0x0
	private const Single EMOJI_FADE_DURATION; // 0x0
	private RectTransform _avatarContainer; // 0x18
	private GameObject _avatarBorder; // 0x20
	private Text _textVisitorLevel; // 0x28
	private GameObject _visitorLevelHolder; // 0x30
	private Text _textVisitorName; // 0x38
	private GameObject _emojiHolder; // 0x40
	private Image _emoji; // 0x48
	private CanvasGroup _emojiCanvasGroup; // 0x50
	private Button _btnPlayerInfo; // 0x58
	private GameObject _panelNewVisitor; // 0x60
	private UIAnimationLocation _animNewVisitor; // 0x68
	private UIColorGraphic _headIconColorGraphic; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private Tween m_newVisitorTween; // 0x90
	private PayloadMessageBoardThisWeekVisitor m_thisWeekVisitor; // 0x98
	private Action`1 m_onClickAvatar; // 0xa0
	private Sequence m_fadeSequence; // 0xa8
	private PlayerAvatarView m_avatarView; // 0xb0
	private static DelegateBridge __Hotfix0__RenderThisWeekVisitor; // 0x0
	private static DelegateBridge __Hotfix0__RenderLastWeekVisitor; // 0x8
	private static DelegateBridge __Hotfix0__RenderEmoji; // 0x10
	private static DelegateBridge __Hotfix0__RenderOtherWeekVisitor; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__KillPrefAnim; // 0x28
	private static DelegateBridge __Hotfix0__CheckAndPlayNewVisitorAnim; // 0x30
	private static DelegateBridge __Hotfix0__PlayNewVisitorAnim; // 0x38
	private static DelegateBridge __Hotfix0__RendBasicInfo; // 0x40
	private static DelegateBridge __Hotfix0__OnAnimEnd; // 0x48
	private static DelegateBridge __Hotfix0_EventOnClickAvatar; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3dc8d48 VA: 0x75963e0d48
	private Void _RenderThisWeekVisitor(PayloadMessageBoardThisWeekVisitor thisWeekVisitor, Int64 lastVisitBoardTs, Action`1 onClickAvatar) { }
	// RVA: 0x3dc94a8 VA: 0x75963e14a8
	private Void _RenderLastWeekVisitor(PayloadMessageBoardLastWeekVisitor lastWeekVisitor) { }
	// RVA: 0x3dc91a8 VA: 0x75963e11a8
	private Void _RenderEmoji(String emojiName) { }
	// RVA: 0x3dc9604 VA: 0x75963e1604
	private Void _RenderOtherWeekVisitor(PayloadOthersMessageBoardThisWeekVisitor otherBoardVisitor) { }
	// RVA: 0x3dc8950 VA: 0x75963e0950
	public Void Render(IMessageBoardVisitorData visitorData, Int64 lastVisitBoardTs, Action`1 onClickAvatar) { }
	// RVA: 0x3dc9574 VA: 0x75963e1574
	private Void _KillPrefAnim() { }
	// RVA: 0x3dc90ec VA: 0x75963e10ec
	private Void _CheckAndPlayNewVisitorAnim(PayloadMessageBoardThisWeekVisitor thisWeekVisitor, Int64 lastVisitBoardTs) { }
	// RVA: 0x3dc975c VA: 0x75963e175c
	private Void _PlayNewVisitorAnim() { }
	// RVA: 0x3dc8ea0 VA: 0x75963e0ea0
	private Void _RendBasicInfo(Boolean showAdditionalInfo, IMessageBoardVisitorData visitorData, Boolean forceUseStaticAvatar) { }
	// RVA: 0x3dc98c0 VA: 0x75963e18c0
	private Void _OnAnimEnd() { }
	// RVA: 0x3dc9930 VA: 0x75963e1930
	public Void EventOnClickAvatar() { }
	// RVA: 0x3dc99bc VA: 0x75963e19bc
	public Void .ctor() { }
}
```