# Act16D6Entry

**Namespace:** `Torappu.Activity.Act16D6`


## Fields

- `ActivityCommonCheckinV2Item _checkinItem`

- `Transform _itemContainer`

- `Transform _dotViewContainer`

- `Text _openTime`

- `ScrollRect _scrollRect`

- `Text _apItemTime`

- `ActivityCommonCheckinDotView _dotView`

- `Color _mainColor`

- `Color _logoColor`

- `Color _acceptableLogoColor`

- `Color _maskColor`

- `Color _rewardBgColor`

- `Color _rewardMaskColor`

- `Color _rewardDotColor`

- `Color _acceptableLightColor`

- `Sprite _decSprite`

- `Sprite _normalDot`

- `Sprite _bigDot`

- `Sprite _acceptableDot`

- `Color _outlineColor`

- `Color _notGetColor`

- `Transform _pluginContainer`

- `GameObject _pluginPrefab`

- `ActivityCommonCheckinDotView m_dotView`

- `ITemplateActivityExtraSignPlugin m_plugin`


## Methods

- `IEnumerator _RefreshHorizontal(DefaultCheckInData)`

- `Int32 _CountNormalizedPosition(Int32, Int32, Int32)`

- `Void _ApplyTimeInfo(Int64, Int64)`

- `Void _UpdateEntryInfo(Boolean)`

- `Void _EventForDotClick(Int32, Int32)`

- `IEnumerator _MoveToFocusItem(Int32, Int32)`

- `Void _TryInjectPlugin()`

- `Void _RefreshPlugin(Boolean)`

- `Void <>xLuaBaseProxy_OnEnter(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act16D6
public class Act16D6Entry : ActivityCommonCheckinEntry, IHotfixable
{
	private ActivityCommonCheckinV2Item _checkinItem; // 0x68
	private Transform _itemContainer; // 0x70
	private Transform _dotViewContainer; // 0x78
	private Text _openTime; // 0x80
	private ScrollRect _scrollRect; // 0x88
	private Text _apItemTime; // 0x90
	private Text[] _mainRewardCountdown; // 0x98
	private ActivityCommonCheckinDotView _dotView; // 0xa0
	private Color _mainColor; // 0xa8
	private Color _logoColor; // 0xb8
	private Color _acceptableLogoColor; // 0xc8
	private Color _maskColor; // 0xd8
	private Color _rewardBgColor; // 0xe8
	private Color _rewardMaskColor; // 0xf8
	private Color _rewardDotColor; // 0x108
	private Color _acceptableLightColor; // 0x118
	private Sprite _decSprite; // 0x128
	private Sprite _normalDot; // 0x130
	private Sprite _bigDot; // 0x138
	private Sprite _acceptableDot; // 0x140
	private Color _outlineColor; // 0x148
	private Color _notGetColor; // 0x158
	private Transform _pluginContainer; // 0x168
	private GameObject _pluginPrefab; // 0x170
	private ActivityCommonCheckinDotView m_dotView; // 0x178
	private List`1 m_itemList; // 0x180
	private CheckInDailyInfo[] m_ShowItemArray; // 0x188
	private ITemplateActivityExtraSignPlugin m_plugin; // 0x190
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__RefreshHorizontal; // 0x8
	private static DelegateBridge __Hotfix0__CountNormalizedPosition; // 0x10
	private static DelegateBridge __Hotfix0__ApplyTimeInfo; // 0x18
	private static DelegateBridge __Hotfix0_RefreshInfo; // 0x20
	private static DelegateBridge __Hotfix0__UpdateEntryInfo; // 0x28
	private static DelegateBridge __Hotfix0__EventForDotClick; // 0x30
	private static DelegateBridge __Hotfix0__MoveToFocusItem; // 0x38
	private static DelegateBridge __Hotfix0__TryInjectPlugin; // 0x40
	private static DelegateBridge __Hotfix0__RefreshPlugin; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x342026c VA: 0x7595a3826c
	public override Void OnEnter(String activityId) { }
	// RVA: 0x3421144 VA: 0x7595a39144
	private IEnumerator _RefreshHorizontal(DefaultCheckInData data) { }
	// RVA: 0x342123c VA: 0x7595a3923c
	private Int32 _CountNormalizedPosition(Int32 focusItem, Int32 totalCount, Int32 gap) { }
	// RVA: 0x34212fc VA: 0x7595a392fc
	private Void _ApplyTimeInfo(Int64 startTime, Int64 endTime) { }
	// RVA: 0x342165c VA: 0x7595a3965c
	protected override Void RefreshInfo() { }
	// RVA: 0x3420304 VA: 0x7595a38304
	private Void _UpdateEntryInfo(Boolean isInit) { }
	// RVA: 0x3421ac8 VA: 0x7595a39ac8
	private Void _EventForDotClick(Int32 focusItem, Int32 checkinCount) { }
	// RVA: 0x3421b8c VA: 0x7595a39b8c
	private IEnumerator _MoveToFocusItem(Int32 focusItem, Int32 checkinCount) { }
	// RVA: 0x3421058 VA: 0x7595a39058
	private Void _TryInjectPlugin() { }
	// RVA: 0x34216fc VA: 0x7595a396fc
	private Void _RefreshPlugin(Boolean isInit) { }
	// RVA: 0x3421c80 VA: 0x7595a39c80
	public Void .ctor() { }
	// RVA: 0x3421db4 VA: 0x7595a39db4
	private Void <>xLuaBaseProxy_OnEnter(String P0) { }
}
```