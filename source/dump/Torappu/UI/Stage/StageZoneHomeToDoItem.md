# StageZoneHomeToDoItem

**Namespace:** `Torappu.UI.Stage`


## Fields

- `CanvasGroup _alphaHandler`

- `Image _mainImage`

- `Transform _pluginHolder`

- `UIColorGraphic _clickHotspot`

- `GameObject _panelEndTime`

- `Text _textEndTime`

- `Image _imgEndTimeBkg`

- `ZoneHomeToDoItemModel m_viewModel`

- `StageZoneHomeToDoItemPlugin m_cachedPlugin`

- `CountDownTask m_endTimeCountDown`


## Properties

- `CanvasGroup alphaHandler`


## Methods

- `CanvasGroup get_alphaHandler()`

- `Void set_onClick(Action`1)`

- `Void Render(ZoneHomeToDoItemModel)`

- `Void _UpdatePlugin(ZoneHomeToDoItemModel)`

- `Void _UpdateEndTime(Int64)`

- `Void _TickEndTimeDisplay(TickValue)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeToDoItem : MonoBehaviour, IHotfixable
{
	private const String COLOR_GROUP_PLUGIN; // 0x0
	private CanvasGroup _alphaHandler; // 0x18
	private Image _mainImage; // 0x20
	private List`1 _plugins; // 0x28
	private Transform _pluginHolder; // 0x30
	private UIColorGraphic _clickHotspot; // 0x38
	private GameObject _panelEndTime; // 0x40
	private Text _textEndTime; // 0x48
	private EndTimeCountDownBgStyle[] _endTimeStyles; // 0x50
	private Image _imgEndTimeBkg; // 0x58
	private Action`1 <onClick>k__BackingField; // 0x60
	private ZoneHomeToDoItemModel m_viewModel; // 0x68
	private StageZoneHomeToDoItemPlugin m_cachedPlugin; // 0x70
	private CountDownTask m_endTimeCountDown; // 0x78
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x0
	private static DelegateBridge __Hotfix0_get_onClick; // 0x8
	private static DelegateBridge __Hotfix0_set_onClick; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__UpdatePlugin; // 0x20
	private static DelegateBridge __Hotfix0__UpdateEndTime; // 0x28
	private static DelegateBridge __Hotfix0__TickEndTimeDisplay; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public CanvasGroup alphaHandler { get; }
	protected Action`1 onClick { get; set; }

	// RVA: 0x2f048c0 VA: 0x759551c8c0
	public CanvasGroup get_alphaHandler() { }
	// RVA: 0x2f04928 VA: 0x759551c928
	protected Action`1 get_onClick() { }
	// RVA: 0x2f04990 VA: 0x759551c990
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2f04a14 VA: 0x759551ca14
	public Void Render(ZoneHomeToDoItemModel viewModel) { }
	// RVA: 0x2f04ab8 VA: 0x759551cab8
	private Void _UpdatePlugin(ZoneHomeToDoItemModel viewModel) { }
	// RVA: 0x2f04e70 VA: 0x759551ce70
	private Void _UpdateEndTime(Int64 endTs) { }
	// RVA: 0x2f0505c VA: 0x759551d05c
	private Void _TickEndTimeDisplay(TickValue value) { }
	// RVA: 0x2f05274 VA: 0x759551d274
	public Void EventOnClicked() { }
	// RVA: 0x2f05314 VA: 0x759551d314
	protected virtual Void Update() { }
	// RVA: 0x2f05390 VA: 0x759551d390
	public Void .ctor() { }
}
```