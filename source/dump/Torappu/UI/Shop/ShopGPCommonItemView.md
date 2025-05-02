# ShopGPCommonItemView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _displayName`

- `Text _endTimeText`

- `GameObject _soldOutPart`

- `CanvasGroup _soldOutCanvas`

- `Text _offsetPercent`

- `GameObject _offsetPart`

- `GameObject _diamondPart`

- `GameObject _cashPart`

- `GameObject _freePart`

- `Text _diamondPrice`

- `Text _diamondOriginPrice`

- `GameObject _diamondOffsetPart`

- `Text _cashPrice`

- `Text _cashCurrency`

- `Text _cashOriginPrice`

- `GameObject _cashOffsetPart`

- `GameObject _panelCheckIn`

- `Text _textCheckInProgress`

- `GameObject _lockedPart`

- `Text _lockedText`

- `Image _spriteImage`

- `GameObject _trackPointPrefab`

- `RectTransform _trackPointContainer`

- `GameObject _remainCountPart`

- `Text _remainCount`

- `ShopGPCommonItemViewModel m_cacheViewModel`

- `GameObject m_trackPointInst`

- `Int64 m_cacheEndTime`


## Methods

- `Void _ApplyNormalPart(NormalGPItem, ShopCashInfo)`

- `Void _ApplyData(ShopGPChooseItemViewModel)`

- `Void _ApplyData(ShopGPCondTrigItemViewModel)`

- `Void _ApplyData(ShopGPPeriodItemViewModel)`

- `Void _ApplyData(ShopGPOnceItemViewModel)`

- `Void _ApplyData(ShopGPLevelItemViewModel)`

- `Void _OpenDetailEvent()`

- `Void _UpdateRemainCountInfo(ShopGPCommonItemViewModel)`

- `Void _UpdateTrackPoint(ShopGPCommonItemViewModel)`

- `Void EnterDetailEvent()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPCommonItemView : MonoBehaviour, IHotfixable
{
	protected Text _displayName; // 0x18
	protected Text _endTimeText; // 0x20
	protected GameObject _soldOutPart; // 0x28
	protected CanvasGroup _soldOutCanvas; // 0x30
	protected Text _offsetPercent; // 0x38
	protected GameObject _offsetPart; // 0x40
	protected GameObject _diamondPart; // 0x48
	protected GameObject _cashPart; // 0x50
	protected GameObject _freePart; // 0x58
	protected Text _diamondPrice; // 0x60
	protected Text _diamondOriginPrice; // 0x68
	protected GameObject _diamondOffsetPart; // 0x70
	protected Text _cashPrice; // 0x78
	protected Text _cashCurrency; // 0x80
	protected Text _cashOriginPrice; // 0x88
	protected GameObject _cashOffsetPart; // 0x90
	private GameObject _panelCheckIn; // 0x98
	private Text _textCheckInProgress; // 0xa0
	private GameObject _lockedPart; // 0xa8
	private Text _lockedText; // 0xb0
	private Image _spriteImage; // 0xb8
	private GameObject _trackPointPrefab; // 0xc0
	private RectTransform _trackPointContainer; // 0xc8
	private GameObject _remainCountPart; // 0xd0
	private Text _remainCount; // 0xd8
	private ShopGPCommonItemViewModel m_cacheViewModel; // 0xe0
	private GameObject m_trackPointInst; // 0xe8
	private Int64 m_cacheEndTime; // 0xf0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__ApplyNormalPart; // 0x8
	private static DelegateBridge __Hotfix0__ApplyData; // 0x10
	private static DelegateBridge __Hotfix1__ApplyData; // 0x18
	private static DelegateBridge __Hotfix2__ApplyData; // 0x20
	private static DelegateBridge __Hotfix3__ApplyData; // 0x28
	private static DelegateBridge __Hotfix4__ApplyData; // 0x30
	private static DelegateBridge __Hotfix0__OpenDetailEvent; // 0x38
	private static DelegateBridge __Hotfix0__UpdateRemainCountInfo; // 0x40
	private static DelegateBridge __Hotfix0__UpdateTrackPoint; // 0x48
	private static DelegateBridge __Hotfix0_EnterDetailEvent; // 0x50
	private static DelegateBridge __Hotfix0_OnClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x24421dc VA: 0x7594a5a1dc
	public virtual Void ApplyData(ShopGPCommonItemViewModel commonViewModel) { }
	// RVA: 0x2443598 VA: 0x7594a5b598
	private Void _ApplyNormalPart(NormalGPItem obj, ShopCashInfo cashInfo) { }
	// RVA: 0x2442cac VA: 0x7594a5acac
	private Void _ApplyData(ShopGPChooseItemViewModel chooseViewModel) { }
	// RVA: 0x2442f20 VA: 0x7594a5af20
	private Void _ApplyData(ShopGPCondTrigItemViewModel viewModel) { }
	// RVA: 0x2442588 VA: 0x7594a5a588
	private Void _ApplyData(ShopGPPeriodItemViewModel periodViewModel) { }
	// RVA: 0x24427f8 VA: 0x7594a5a7f8
	private Void _ApplyData(ShopGPOnceItemViewModel onceViewModel) { }
	// RVA: 0x2442a70 VA: 0x7594a5aa70
	private Void _ApplyData(ShopGPLevelItemViewModel levelViewModel) { }
	// RVA: 0x244392c VA: 0x7594a5b92c
	private Void _OpenDetailEvent() { }
	// RVA: 0x2443478 VA: 0x7594a5b478
	private Void _UpdateRemainCountInfo(ShopGPCommonItemViewModel commonViewModel) { }
	// RVA: 0x2443240 VA: 0x7594a5b240
	private Void _UpdateTrackPoint(ShopGPCommonItemViewModel commonViewModel) { }
	// RVA: 0x2443ac0 VA: 0x7594a5bac0
	public Void EnterDetailEvent() { }
	// RVA: 0x2443b28 VA: 0x7594a5bb28
	public Void OnClick() { }
	// RVA: 0x2443bb8 VA: 0x7594a5bbb8
	public Void .ctor() { }
}
```