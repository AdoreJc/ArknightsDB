# Act29signCheckinListView

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `Transform _dotViewContainer`

- `Text _openTime`

- `LoopHorizontalScrollRect _scrollRect`

- `Text _apItemTime`

- `ActivityCommonCheckinDotView _dotView`

- `Act29signCheckinItemAdapter _adapter`

- `Image _moonCakeImg`

- `Image _furnitureImg`

- `Color _mainColor`

- `Color _logoColor`

- `Color _acceptableLogoColor`

- `Color _maskColor`

- `Color _rewardBgColor`

- `Color _rewardMaskColor`

- `Color _rewardDotColor`

- `Color _acceptableLightColor`

- `Sprite _decSprite`

- `Color _numIconColor`

- `Color _progressTextColor`

- `Sprite _normalDot`

- `Sprite _bigDot`

- `Sprite _acceptableDot`

- `Color _outlineColor`

- `Color _notGetColor`

- `Act29signCheckinListViewModel m_viewModel`

- `ActivityCommonCheckinViewModel m_outerViewModel`

- `Boolean m_hasInited`

- `ActivityCommonCheckinDotView m_dotView`


## Methods

- `Int32 _CountNormalizedPosition(Int32, Int32, Int32)`

- `Void _UpdateEntryInfo(Boolean)`

- `Void _InitOrUpdateCheckinItems(Boolean)`

- `Void _EventForDotClick(Int32, Int32)`

- `IEnumerator _MoveToFocusItem(Int32, Int32)`

- `Void _InitIfNot(ActivityCommonCheckinViewModel)`

- `Void EventOnCloseBtnClick()`

- `Void EventOnNormalItemClicked(Int32)`

- `Void EventOnSpecialItemClicked()`

- `Single <_MoveToFocusItem>b__34_0()`

- `Void <_MoveToFocusItem>b__34_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signCheckinListView : ActivityCheckinEntryView
{
	private Transform _dotViewContainer; // 0x50
	private Text _openTime; // 0x58
	private LoopHorizontalScrollRect _scrollRect; // 0x60
	private Text _apItemTime; // 0x68
	private Text[] _mainRewardCountdown; // 0x70
	private ActivityCommonCheckinDotView _dotView; // 0x78
	private Act29signCheckinItemAdapter _adapter; // 0x80
	private Image _moonCakeImg; // 0x88
	private Image _furnitureImg; // 0x90
	private Color _mainColor; // 0x98
	private Color _logoColor; // 0xa8
	private Color _acceptableLogoColor; // 0xb8
	private Color _maskColor; // 0xc8
	private Color _rewardBgColor; // 0xd8
	private Color _rewardMaskColor; // 0xe8
	private Color _rewardDotColor; // 0xf8
	private Color _acceptableLightColor; // 0x108
	private Sprite _decSprite; // 0x118
	private Color _numIconColor; // 0x120
	private Color _progressTextColor; // 0x130
	private Sprite _normalDot; // 0x140
	private Sprite _bigDot; // 0x148
	private Sprite _acceptableDot; // 0x150
	private Color _outlineColor; // 0x158
	private Color _notGetColor; // 0x168
	private Act29signCheckinListViewModel m_viewModel; // 0x178
	private ActivityCommonCheckinViewModel m_outerViewModel; // 0x180
	private Boolean m_hasInited; // 0x188
	private ActivityCommonCheckinDotView m_dotView; // 0x190
	private CheckInDailyInfo[] m_ShowItemArray; // 0x198
	private static DelegateBridge __Hotfix0__CountNormalizedPosition; // 0x0
	private static DelegateBridge __Hotfix0__UpdateEntryInfo; // 0x8
	private static DelegateBridge __Hotfix0__InitOrUpdateCheckinItems; // 0x10
	private static DelegateBridge __Hotfix0__EventForDotClick; // 0x18
	private static DelegateBridge __Hotfix0__MoveToFocusItem; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_RenderView; // 0x30
	private static DelegateBridge __Hotfix0_GetViewType; // 0x38
	private static DelegateBridge __Hotfix0_EventOnCloseBtnClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnNormalItemClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnSpecialItemClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3260a48 VA: 0x7595878a48
	private Int32 _CountNormalizedPosition(Int32 focusItem, Int32 totalCount, Int32 gap) { }
	// RVA: 0x3260b08 VA: 0x7595878b08
	private Void _UpdateEntryInfo(Boolean isInit) { }
	// RVA: 0x326126c VA: 0x759587926c
	private Void _InitOrUpdateCheckinItems(Boolean isInit) { }
	// RVA: 0x3261410 VA: 0x7595879410
	private Void _EventForDotClick(Int32 focusItem, Int32 checkinCount) { }
	// RVA: 0x32614d4 VA: 0x75958794d4
	private IEnumerator _MoveToFocusItem(Int32 focusItem, Int32 checkinCount) { }
	// RVA: 0x32615c8 VA: 0x75958795c8
	private Void _InitIfNot(ActivityCommonCheckinViewModel outerViewModel) { }
	// RVA: 0x3261808 VA: 0x7595879808
	public override Void RenderView(ActivityCommonCheckinViewModel outerViewModel) { }
	// RVA: 0x32618d8 VA: 0x75958798d8
	public override CheckinViewType GetViewType() { }
	// RVA: 0x3261940 VA: 0x7595879940
	public Void EventOnCloseBtnClick() { }
	// RVA: 0x32619ac VA: 0x75958799ac
	public Void EventOnNormalItemClicked(Int32 index) { }
	// RVA: 0x3261a74 VA: 0x7595879a74
	public Void EventOnSpecialItemClicked() { }
	// RVA: 0x3261b20 VA: 0x7595879b20
	public Void .ctor() { }
	// RVA: 0x3261c08 VA: 0x7595879c08
	private Single <_MoveToFocusItem>b__34_0() { }
	// RVA: 0x3261c24 VA: 0x7595879c24
	private Void <_MoveToFocusItem>b__34_1(Single val) { }
}
```