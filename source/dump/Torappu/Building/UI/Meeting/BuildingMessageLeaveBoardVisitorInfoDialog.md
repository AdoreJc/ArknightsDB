# BuildingMessageLeaveBoardVisitorInfoDialog

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `CanvasGroup _canvasGroup`

- `BuildingNameCardView _nameCardItemView`

- `GameObject _panelTimeToday`

- `GameObject _panelTimeYesterday`

- `GameObject _panelTimePref`

- `Text _textDate`

- `GameObject _panelInfoShare`

- `Image _shareProgress`

- `GameObject _panelRecentVisit`

- `Text _visitCount`

- `PayloadMessageBoardThisWeekVisitor m_visitorData`

- `String m_cachedUid`

- `GetOtherPlayerNameCardResponse m_cachedResponse`

- `Boolean m_enalbeClick`

- `Tween m_fadeTween`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `IEnumerator _PlayFadeInOut(Boolean, Action)`

- `Void _HideView()`

- `Void EventOnClickBG()`

- `Void EventOnClickDetailInfo()`

- `Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse)`

- `Void EventOnClickVisitMessageBoard()`

- `Void _RenderTimeShow(PayloadMessageBoardThisWeekVisitor)`

- `Boolean <_PlayFadeInOut>b__21_0()`

- `Void <EventOnClickDetailInfo>b__24_0(GetOtherPlayerNameCardResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMessageLeaveBoardVisitorInfoDialog : UICompDialog`1, IHotfixable
{
	private const String NAMECARD_REQUEST_SRC; // 0x0
	private const Single FADE_DURATION; // 0x0
	private CanvasGroup _canvasGroup; // 0x48
	private BuildingNameCardView _nameCardItemView; // 0x50
	private GameObject _panelTimeToday; // 0x58
	private GameObject _panelTimeYesterday; // 0x60
	private GameObject _panelTimePref; // 0x68
	private Text _textDate; // 0x70
	private GameObject _panelInfoShare; // 0x78
	private Image _shareProgress; // 0x80
	private GameObject _panelRecentVisit; // 0x88
	private Text _visitCount; // 0x90
	private PayloadMessageBoardThisWeekVisitor m_visitorData; // 0x98
	private String m_cachedUid; // 0xa0
	private GetOtherPlayerNameCardResponse m_cachedResponse; // 0xa8
	private Boolean m_enalbeClick; // 0xb0
	private Tween m_fadeTween; // 0xb8
	private Boolean m_isInited; // 0xc0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__PlayFadeInOut; // 0x10
	private static DelegateBridge __Hotfix0__HideView; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClickBG; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClickDetailInfo; // 0x28
	private static DelegateBridge __Hotfix0__OpenFriendNameCard; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClickVisitMessageBoard; // 0x38
	private static DelegateBridge __Hotfix0__RenderTimeShow; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3dc610c VA: 0x75963de10c
	private Void _InitIfNot() { }
	// RVA: 0x3dc6230 VA: 0x75963de230
	protected override Void OnRender(Input input) { }
	// RVA: 0x3dc66e8 VA: 0x75963de6e8
	private IEnumerator _PlayFadeInOut(Boolean isIn, Action callback) { }
	// RVA: 0x3dc67f0 VA: 0x75963de7f0
	private Void _HideView() { }
	// RVA: 0x3dc6868 VA: 0x75963de868
	public Void EventOnClickBG() { }
	// RVA: 0x3dc6948 VA: 0x75963de948
	public Void EventOnClickDetailInfo() { }
	// RVA: 0x3dc6ba4 VA: 0x75963deba4
	private Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse response) { }
	// RVA: 0x3dc6cb8 VA: 0x75963decb8
	public Void EventOnClickVisitMessageBoard() { }
	// RVA: 0x3dc645c VA: 0x75963de45c
	private Void _RenderTimeShow(PayloadMessageBoardThisWeekVisitor visitorData) { }
	// RVA: 0x3dc6efc VA: 0x75963deefc
	public Void .ctor() { }
	// RVA: 0x3dc6f8c VA: 0x75963def8c
	private Boolean <_PlayFadeInOut>b__21_0() { }
	// RVA: 0x3dc6fa0 VA: 0x75963defa0
	private Void <EventOnClickDetailInfo>b__24_0(GetOtherPlayerNameCardResponse response) { }
}
```