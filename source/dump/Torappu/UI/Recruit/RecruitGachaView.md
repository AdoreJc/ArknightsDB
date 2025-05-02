# RecruitGachaView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RectTransform _mask`

- `RectTransform _deltaPos`

- `ScrollViewPager _pageContainer`

- `CanvasGroup _hiringState`

- `Transform _container`

- `UIStringEvent _onGacha`

- `UIStringEvent _onTenGacha`

- `UIStringEvent _onRecruitFree`

- `UIStringBoolEvent _onDetailGacha`

- `GameObject _leftBtn`

- `GameObject _rightBtn`

- `RecruitBuildConfigHiringBar _hiringBar`

- `RefCountReference m_buildingRef`

- `Boolean m_buildingContextInit`

- `Boolean nextFrameRefresh`


## Properties

- `Boolean isCurrentNormalPage`


## Methods

- `Boolean get_isCurrentNormalPage()`

- `Void RefreshGachaTkState()`

- `Int32 _JudgeNewBeeOpenState(Int32)`

- `Boolean _CompareNewbeeClientAndNormalClient(NewbeeGachaPoolClientData, GachaPoolClientData)`

- `Int32 _MergeSortAndRender(String)`

- `Void InitData(Boolean, String)`

- `Void _PlayPoolInitEffect(Int32)`

- `Void ToLeftPage()`

- `Void ToRightPage()`

- `Void SwitchPage(Boolean)`

- `Void SwitchToPage(Boolean, String)`

- `Void OnClear()`

- `Void _InitPage(GachaPoolClientData)`

- `Void _InitClassicPage(GachaPoolClientData)`

- `Void _InitSpecialPage(GachaPoolClientData)`

- `Void _InitNewbeePage(NewbeeGachaPoolClientData)`

- `Void _RefreshHiringStateFade(Int32)`

- `Void _RefreshHiringState(Int32, Boolean)`

- `Int32 _CalcGachaIndex(String)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitGachaView : MonoBehaviour, IHotfixable
{
	private const Int32 NORMAL_PAGE_INDEX; // 0x0
	private const Int32 ADVANCED_PAGE_OFFSET; // 0x0
	private RectTransform _mask; // 0x18
	private RectTransform _deltaPos; // 0x20
	private ScrollViewPager _pageContainer; // 0x28
	private CanvasGroup _hiringState; // 0x30
	private List`1 m_pageList; // 0x38
	private Transform _container; // 0x40
	private UIStringEvent _onGacha; // 0x48
	private UIStringEvent _onTenGacha; // 0x50
	private UIStringEvent _onRecruitFree; // 0x58
	private UIStringBoolEvent _onDetailGacha; // 0x60
	private GameObject _leftBtn; // 0x68
	private GameObject _rightBtn; // 0x70
	private RecruitBuildConfigHiringBar _hiringBar; // 0x78
	private RefCountReference m_buildingRef; // 0x80
	private Boolean m_buildingContextInit; // 0x88
	private const Single FADETIME; // 0x0
	private Boolean nextFrameRefresh; // 0x89
	private static DelegateBridge __Hotfix0_get_isCurrentNormalPage; // 0x0
	private static DelegateBridge __Hotfix0_RefreshGachaTkState; // 0x8
	private static DelegateBridge __Hotfix0__JudgeNewBeeOpenState; // 0x10
	private static DelegateBridge __Hotfix0__CompareNewbeeClientAndNormalClient; // 0x18
	private static DelegateBridge __Hotfix0__MergeSortAndRender; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x28
	private static DelegateBridge __Hotfix0__PlayPoolInitEffect; // 0x30
	private static DelegateBridge __Hotfix0_ToLeftPage; // 0x38
	private static DelegateBridge __Hotfix0_ToRightPage; // 0x40
	private static DelegateBridge __Hotfix0_SwitchPage; // 0x48
	private static DelegateBridge __Hotfix0_SwitchToPage; // 0x50
	private static DelegateBridge __Hotfix0_OnClear; // 0x58
	private static DelegateBridge __Hotfix0__InitPage; // 0x60
	private static DelegateBridge __Hotfix0__InitClassicPage; // 0x68
	private static DelegateBridge __Hotfix0__InitSpecialPage; // 0x70
	private static DelegateBridge __Hotfix0__InitNewbeePage; // 0x78
	private static DelegateBridge __Hotfix0__RefreshHiringStateFade; // 0x80
	private static DelegateBridge __Hotfix0__RefreshHiringState; // 0x88
	private static DelegateBridge __Hotfix0__CalcGachaIndex; // 0x90
	private static DelegateBridge __Hotfix0_Update; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public Boolean isCurrentNormalPage { get; }

	// RVA: 0x27194d0 VA: 0x7594d314d0
	public Boolean get_isCurrentNormalPage() { }
	// RVA: 0x2719550 VA: 0x7594d31550
	public Void RefreshGachaTkState() { }
	// RVA: 0x2719610 VA: 0x7594d31610
	private Int32 _JudgeNewBeeOpenState(Int32 index) { }
	// RVA: 0x271970c VA: 0x7594d3170c
	private Boolean _CompareNewbeeClientAndNormalClient(NewbeeGachaPoolClientData newbeePoolData, GachaPoolClientData normalGachaPoolData) { }
	// RVA: 0x27197b0 VA: 0x7594d317b0
	private Int32 _MergeSortAndRender(String initGachaPool) { }
	// RVA: 0x271a004 VA: 0x7594d32004
	public Void InitData(Boolean isNormal, String initGachaPoolId) { }
	// RVA: 0x271a498 VA: 0x7594d32498
	private Void _PlayPoolInitEffect(Int32 pageIndex) { }
	// RVA: 0x271a594 VA: 0x7594d32594
	public Void ToLeftPage() { }
	// RVA: 0x271a640 VA: 0x7594d32640
	public Void ToRightPage() { }
	// RVA: 0x271a704 VA: 0x7594d32704
	public Void SwitchPage(Boolean isNormal) { }
	// RVA: 0x271a794 VA: 0x7594d32794
	public Void SwitchToPage(Boolean isNormal, String gachaPoolId) { }
	// RVA: 0x271a9e4 VA: 0x7594d329e4
	public Void OnClear() { }
	// RVA: 0x2719d98 VA: 0x7594d31d98
	private Void _InitPage(GachaPoolClientData data) { }
	// RVA: 0x271aa78 VA: 0x7594d32a78
	private Void _InitClassicPage(GachaPoolClientData data) { }
	// RVA: 0x271ac88 VA: 0x7594d32c88
	private Void _InitSpecialPage(GachaPoolClientData data) { }
	// RVA: 0x2719b78 VA: 0x7594d31b78
	private Void _InitNewbeePage(NewbeeGachaPoolClientData data) { }
	// RVA: 0x271ae9c VA: 0x7594d32e9c
	public Void _RefreshHiringStateFade(Int32 pageIndex) { }
	// RVA: 0x271a30c VA: 0x7594d3230c
	private Void _RefreshHiringState(Int32 pageIndex, Boolean isFast) { }
	// RVA: 0x271a888 VA: 0x7594d32888
	private Int32 _CalcGachaIndex(String gachaPoolId) { }
	// RVA: 0x271af20 VA: 0x7594d32f20
	private Void Update() { }
	// RVA: 0x271b09c VA: 0x7594d3309c
	public Void .ctor() { }
}
```