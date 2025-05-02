# BuildingUIFloatStationView

**Namespace:** `Torappu.Building.UI`


## Fields

- `SimpleLayoutContent _charContent`

- `SimpleLayoutContent _iconContent`

- `Text _textStationNum`

- `Text _textMaxStationNum`

- `RectTransform _lineStationedNum`

- `Sprite _stationIcon`

- `UIAnimationLocation _showAnim`

- `Image _panelBlank`

- `ScrollRect _stationScroll`

- `ScrollRectSoftMask _stationScrollMask`

- `Boolean m_isInited`

- `Boolean m_isShowing`

- `Int32 m_stationedCharNum`

- `FloatStationViewModel m_viewModel`

- `StationAdapter m_stationAdapter`

- `IconAdapter m_iconAdapter`

- `Tween m_tweenCache`


## Methods

- `Void EventOnClearStationClicked()`

- `Void _OnStationSlotClicked(BuildingCharModel, Int32)`

- `Void _OnRemoveCharClicked(BuildingCharModel, Int32)`

- `Void _InitIfNot()`

- `Void _UpdateShowEffect()`

- `Void _UpdateContent()`

- `IEnumerator _UpdateAutoLayoutCoroutine(RectTransform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingUIFloatStationView : AbstractBuildingUIFloatStationView
{
	private const String ICON_NAME; // 0x0
	private SimpleLayoutContent _charContent; // 0x28
	private SimpleLayoutContent _iconContent; // 0x30
	private Text _textStationNum; // 0x38
	private Text _textMaxStationNum; // 0x40
	private RectTransform _lineStationedNum; // 0x48
	private Sprite _stationIcon; // 0x50
	private UIAnimationLocation _showAnim; // 0x58
	private Image _panelBlank; // 0x68
	private ScrollRect _stationScroll; // 0x70
	private ScrollRectSoftMask _stationScrollMask; // 0x78
	private Boolean m_isInited; // 0x80
	private Boolean m_isShowing; // 0x81
	private Int32 m_stationedCharNum; // 0x84
	private FloatStationViewModel m_viewModel; // 0x88
	private StationAdapter m_stationAdapter; // 0x90
	private IconAdapter m_iconAdapter; // 0x98
	private Tween m_tweenCache; // 0xa0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClearStationClicked; // 0x8
	private static DelegateBridge __Hotfix0__OnStationSlotClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnRemoveCharClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__UpdateShowEffect; // 0x28
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x30
	private static DelegateBridge __Hotfix0__UpdateAutoLayoutCoroutine; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3d3bba4 VA: 0x7596353ba4
	public override Void OnValueChanged(FloatStationViewProperty property) { }
	// RVA: 0x3d3c3a0 VA: 0x75963543a0
	public Void EventOnClearStationClicked() { }
	// RVA: 0x3d3c434 VA: 0x7596354434
	private Void _OnStationSlotClicked(BuildingCharModel charModel, Int32 index) { }
	// RVA: 0x3d3c4fc VA: 0x75963544fc
	private Void _OnRemoveCharClicked(BuildingCharModel charModel, Int32 index) { }
	// RVA: 0x3d3c0a4 VA: 0x75963540a4
	private Void _InitIfNot() { }
	// RVA: 0x3d3bd70 VA: 0x7596353d70
	private Void _UpdateShowEffect() { }
	// RVA: 0x3d3c1f4 VA: 0x75963541f4
	private Void _UpdateContent() { }
	// RVA: 0x3d3c724 VA: 0x7596354724
	private IEnumerator _UpdateAutoLayoutCoroutine(RectTransform layout) { }
	// RVA: 0x3d3c80c VA: 0x759635480c
	public Void .ctor() { }
}
```