# StageZoneHomeEntryItem

**Namespace:** `Torappu.UI.Stage`


## Fields

- `CanvasGroup _alphaHandler`

- `Image _mainImage`

- `Image _funcIcon`

- `Transform _pluginHolder`

- `UIColorGraphic _clickHotspot`

- `Button _clickButton`

- `GameObject _panelEndTime`

- `Text _textEndTime`

- `StageZoneHomeEntryMedalView _medalPrefab`

- `RectTransform _medalContainer`

- `GameObject _panelLockInfo`

- `Text _textLock`

- `ZoneHomeEntryItemModel m_cachedModel`

- `StageZoneHomeEntryItemPlugin m_cachedPlugin`

- `StageZoneHomeEntryMedalView m_medalView`

- `HomeEntryLayoutLevel m_layoutLevel`

- `ZoneHomeEntryLockInfo m_cachedLockInfo`

- `CountDownTask m_endTimeCountDown`


## Methods

- `Void set_onClick(Action`1)`

- `Void _UpdatePlugin(ZoneHomeEntryItemModel)`

- `Void _UpdateMedalInfo(ZoneHomeEntryMedalStatus)`

- `Void _UpdateLockInfo(ZoneHomeEntryLockInfo)`

- `Void _UpdateEndTime(Int64)`

- `Void _TickEndTimeDisplay(TickValue)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeEntryItem : StageZoneHomeEntryItemBase
{
	private const String COLOR_GROUP_PLUGIN; // 0x0
	private CanvasGroup _alphaHandler; // 0x20
	private Image _mainImage; // 0x28
	private Image _funcIcon; // 0x30
	private List`1 _plugins; // 0x38
	private Transform _pluginHolder; // 0x40
	private UIColorGraphic _clickHotspot; // 0x48
	private Button _clickButton; // 0x50
	private GameObject _panelEndTime; // 0x58
	private Text _textEndTime; // 0x60
	private StageZoneHomeEntryMedalView _medalPrefab; // 0x68
	private RectTransform _medalContainer; // 0x70
	private GameObject _panelLockInfo; // 0x78
	private Text _textLock; // 0x80
	private ZoneHomeEntryItemModel m_cachedModel; // 0x88
	private StageZoneHomeEntryItemPlugin m_cachedPlugin; // 0x90
	private StageZoneHomeEntryMedalView m_medalView; // 0x98
	private HomeEntryLayoutLevel m_layoutLevel; // 0xa0
	private ZoneHomeEntryLockInfo m_cachedLockInfo; // 0xa8
	private CountDownTask m_endTimeCountDown; // 0xc0
	private Action`1 <onClick>k__BackingField; // 0xc8
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x0
	private static DelegateBridge __Hotfix0_get_onClick; // 0x8
	private static DelegateBridge __Hotfix0_set_onClick; // 0x10
	private static DelegateBridge __Hotfix0_OnRender; // 0x18
	private static DelegateBridge __Hotfix0__UpdatePlugin; // 0x20
	private static DelegateBridge __Hotfix0__UpdateMedalInfo; // 0x28
	private static DelegateBridge __Hotfix0__UpdateLockInfo; // 0x30
	private static DelegateBridge __Hotfix0_UpdateEndTimeStatus; // 0x38
	private static DelegateBridge __Hotfix0__UpdateEndTime; // 0x40
	private static DelegateBridge __Hotfix0__TickEndTimeDisplay; // 0x48
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x50
	private static DelegateBridge __Hotfix0_Update; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override CanvasGroup alphaHandler { get; }
	protected Action`1 onClick { get; set; }

	// RVA: 0x2efc518 VA: 0x7595514518
	public override CanvasGroup get_alphaHandler() { }
	// RVA: 0x2efc580 VA: 0x7595514580
	protected Action`1 get_onClick() { }
	// RVA: 0x2efc5e8 VA: 0x75955145e8
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2efc66c VA: 0x759551466c
	protected override Void OnRender(ZoneHomeEntryItemModel viewModel, HomeEntryLayoutLevel layoutLevel) { }
	// RVA: 0x2efc790 VA: 0x7595514790
	private Void _UpdatePlugin(ZoneHomeEntryItemModel viewModel) { }
	// RVA: 0x2efcaac VA: 0x7595514aac
	private Void _UpdateMedalInfo(ZoneHomeEntryMedalStatus medalConfig) { }
	// RVA: 0x2efcc48 VA: 0x7595514c48
	private Void _UpdateLockInfo(ZoneHomeEntryLockInfo lockInfo) { }
	// RVA: 0x2efd0dc VA: 0x75955150dc
	public static Void UpdateEndTimeStatus(Int64 endTs, GameObject panelEndTime, ref CountDownTask refCountDown, Action`1 onTimeTick) { }
	// RVA: 0x2efcddc VA: 0x7595514ddc
	private Void _UpdateEndTime(Int64 endTs) { }
	// RVA: 0x2efd2f4 VA: 0x75955152f4
	private Void _TickEndTimeDisplay(TickValue value) { }
	// RVA: 0x2efd3f4 VA: 0x75955153f4
	public Void EventOnClicked() { }
	// RVA: 0x2efd494 VA: 0x7595515494
	protected virtual Void Update() { }
	// RVA: 0x2efd510 VA: 0x7595515510
	public Void .ctor() { }
}
```