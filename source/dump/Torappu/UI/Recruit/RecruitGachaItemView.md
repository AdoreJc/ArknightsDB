# RecruitGachaItemView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _recruitName`

- `Text _recruitDetail`

- `Text _recruitSummary`

- `Text _singlePrice`

- `Text _multiPrice`

- `GameObject _diamondShObj`

- `GameObject _gachaObj`

- `GameObject _diamondShTenObj`

- `GameObject _gachaTenObj`

- `GameObject _protectPart`

- `GameObject _singleTktObj`

- `GameObject _singleTktTenObj`

- `Text _remainTimes`

- `Transform _forwardPlugin`

- `Boolean isLimitPool`

- `GameObject _limitPoolPart`

- `GameObject _limitFreeGachaObj`

- `GameObject _limitTenGachaObj`

- `GameObject _limitExpirePart`

- `GameObject _limitFreshPart`

- `GameObject _limitFreshPartBottom`

- `GameObject _limitFreeIconObj`

- `GameObject _limitFreeLightObj`

- `Text _limitFreeGachaCnt`

- `Text _limitTenGachaCnt`

- `Text _shardCount`

- `Text _limitFreeRecruitCnt`

- `Color _limitFreeRecruitedColor`

- `Color _refreshColorBottom`

- `Image _limitCDAboveBg`

- `Image _limitCDBottomBg`

- `Image _limitCDLeftBg`

- `Image _limitCDRightBg`

- `Image _shardIcon`

- `Image _limitFreeCountBg`

- `Image _limitFreeCharBorderImg`

- `Image _limitFreeCharImg`

- `UIItemTimeCountDown _ExpireCountDown`

- `UIItemTimeCountDown _RefreshCountDown`

- `UIItemTimeCountDown _refreshCountDownBottom`

- `ThreeStateToggle _limitFreeRecruitStateToggle`

- `GachaPoolClientData m_data`

- `RecruitGachaCostAddition m_costAddition`

- `LimitPoolParam m_limitParam`

- `UIItemTimeCountDown m_activeCountDown`


## Properties

- `Boolean LimitPool`


## Methods

- `Boolean get_LimitPool()`

- `Void set_LimitPool(Boolean)`

- `Int64 _GetRemainTimeToNextDay()`

- `Void _OnExpireTimeExceed()`

- `Void _OnRefreshTimeExceed()`

- `Void _PickActiveRefreshCountDown()`

- `Void ApplyData(Int32, GachaPoolClientData)`

- `Void OnEPGSShop()`

- `Void _UpdateCostAdditionStatus(Param)`

- `Transform _GetForwardPluginContainer()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitGachaItemView : RecruitGachaItemViewBase
{
	protected Text _recruitName; // 0x60
	protected Text _recruitDetail; // 0x68
	protected Text _recruitSummary; // 0x70
	protected Text _singlePrice; // 0x78
	protected Text _multiPrice; // 0x80
	protected GameObject _diamondShObj; // 0x88
	protected GameObject _gachaObj; // 0x90
	protected GameObject _diamondShTenObj; // 0x98
	protected GameObject _gachaTenObj; // 0xa0
	protected GameObject _protectPart; // 0xa8
	private GameObject _singleTktObj; // 0xb0
	private GameObject _singleTktTenObj; // 0xb8
	protected Text _remainTimes; // 0xc0
	private Transform _forwardPlugin; // 0xc8
	public Boolean isLimitPool; // 0xd0
	public GameObject _limitPoolPart; // 0xd8
	public GameObject _limitFreeGachaObj; // 0xe0
	public GameObject _limitTenGachaObj; // 0xe8
	public GameObject _limitExpirePart; // 0xf0
	public GameObject _limitFreshPart; // 0xf8
	public GameObject _limitFreshPartBottom; // 0x100
	public GameObject _limitFreeIconObj; // 0x108
	public GameObject _limitFreeLightObj; // 0x110
	public Text _limitFreeGachaCnt; // 0x118
	public Text _limitTenGachaCnt; // 0x120
	public Text _shardCount; // 0x128
	public Text _limitFreeRecruitCnt; // 0x130
	public Color _limitFreeRecruitedColor; // 0x138
	public Color _refreshColorBottom; // 0x148
	public Image _limitCDAboveBg; // 0x158
	public Image _limitCDBottomBg; // 0x160
	public Image _limitCDLeftBg; // 0x168
	public Image _limitCDRightBg; // 0x170
	public Image _shardIcon; // 0x178
	public Image _limitFreeCountBg; // 0x180
	public Image _limitFreeCharBorderImg; // 0x188
	public Image _limitFreeCharImg; // 0x190
	public UIItemTimeCountDown _ExpireCountDown; // 0x198
	public UIItemTimeCountDown _RefreshCountDown; // 0x1a0
	public UIItemTimeCountDown _refreshCountDownBottom; // 0x1a8
	public ThreeStateToggle _limitFreeRecruitStateToggle; // 0x1b0
	private GachaPoolClientData m_data; // 0x1b8
	private RecruitGachaCostAddition m_costAddition; // 0x1c0
	private LimitPoolParam m_limitParam; // 0x1c8
	private UIItemTimeCountDown m_activeCountDown; // 0x1d0
	private static DelegateBridge __Hotfix0_get_LimitPool; // 0x0
	private static DelegateBridge __Hotfix0_set_LimitPool; // 0x8
	private static DelegateBridge __Hotfix0_get_gachaPoolId; // 0x10
	private static DelegateBridge __Hotfix0_OnRefreshData; // 0x18
	private static DelegateBridge __Hotfix0__GetRemainTimeToNextDay; // 0x20
	private static DelegateBridge __Hotfix0__OnExpireTimeExceed; // 0x28
	private static DelegateBridge __Hotfix0__OnRefreshTimeExceed; // 0x30
	private static DelegateBridge __Hotfix0__PickActiveRefreshCountDown; // 0x38
	private static DelegateBridge __Hotfix0_ApplyData; // 0x40
	private static DelegateBridge __Hotfix0_OnEPGSShop; // 0x48
	private static DelegateBridge __Hotfix0__UpdateCostAdditionStatus; // 0x50
	private static DelegateBridge __Hotfix0__GetForwardPluginContainer; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Boolean LimitPool { get; set; }
	public override String gachaPoolId { get; }

	// RVA: 0x2715c54 VA: 0x7594d2dc54
	private Boolean get_LimitPool() { }
	// RVA: 0x2715cbc VA: 0x7594d2dcbc
	private Void set_LimitPool(Boolean value) { }
	// RVA: 0x2715d3c VA: 0x7594d2dd3c
	public override String get_gachaPoolId() { }
	// RVA: 0x2715dd0 VA: 0x7594d2ddd0
	protected override Void OnRefreshData() { }
	// RVA: 0x2716a08 VA: 0x7594d2ea08
	private Int64 _GetRemainTimeToNextDay() { }
	// RVA: 0x2716984 VA: 0x7594d2e984
	private Void _OnExpireTimeExceed() { }
	// RVA: 0x2716b6c VA: 0x7594d2eb6c
	private Void _OnRefreshTimeExceed() { }
	// RVA: 0x2716ca0 VA: 0x7594d2eca0
	private Void _PickActiveRefreshCountDown() { }
	// RVA: 0x2716d30 VA: 0x7594d2ed30
	public Void ApplyData(Int32 index, GachaPoolClientData data) { }
	// RVA: 0x27175b8 VA: 0x7594d2f5b8
	public Void OnEPGSShop() { }
	// RVA: 0x271674c VA: 0x7594d2e74c
	private Void _UpdateCostAdditionStatus(Param additionParam) { }
	// RVA: 0x2717698 VA: 0x7594d2f698
	private Transform _GetForwardPluginContainer() { }
	// RVA: 0x271780c VA: 0x7594d2f80c
	public Void .ctor() { }
}
```