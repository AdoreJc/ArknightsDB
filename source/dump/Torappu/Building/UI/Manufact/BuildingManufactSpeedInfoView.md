# BuildingManufactSpeedInfoView

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `Text _textManpowerCost`

- `SimpleLayoutContent _mpBuffLayout`

- `Text _textSpeed`

- `SimpleLayoutContent _speedBuffLayout`

- `Text _textSavedTime`

- `GameObject _iconSpeedUp`

- `GameObject _iconTimeDown`

- `GameObject _iconMpDown`

- `Color _bkgBuffColor`

- `Color _textBuffColor`

- `CountDownTask m_countDown`

- `ManufactInfoViewModel m_infoCache`

- `String m_colorBuffedCode`

- `ListAdapter m_speedBuffAdapter`

- `ListAdapter m_mpBuffAdapter`


## Methods

- `IEnumerator _UpdateAutoLayoutsCoroutine()`

- `Void _UpdateSavedTime(MRoomViewModel, ManufactSnapshot)`

- `Void _UpdateSecond(TickValue)`

- `Void _FormatBuffedValues(Single, Single, SimpleLayoutContent, ref, Boolean)`

- `Void OnEnable()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactSpeedInfoView : DataBinder`1
{
	private const String INVALID_TIME; // 0x0
	private Text _textManpowerCost; // 0x20
	private SimpleLayoutContent _mpBuffLayout; // 0x28
	private Text _textSpeed; // 0x30
	private SimpleLayoutContent _speedBuffLayout; // 0x38
	private Text _textSavedTime; // 0x40
	private GameObject _iconSpeedUp; // 0x48
	private GameObject _iconTimeDown; // 0x50
	private GameObject _iconMpDown; // 0x58
	private RectTransform[] _autoLayouts; // 0x60
	private Color _bkgBuffColor; // 0x68
	private Color _textBuffColor; // 0x78
	private CountDownTask m_countDown; // 0x88
	private ManufactInfoViewModel m_infoCache; // 0x90
	private String m_colorBuffedCode; // 0x98
	private ListAdapter m_speedBuffAdapter; // 0xa0
	private ListAdapter m_mpBuffAdapter; // 0xa8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__UpdateAutoLayoutsCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__UpdateSavedTime; // 0x10
	private static DelegateBridge __Hotfix0__UpdateSecond; // 0x18
	private static DelegateBridge __Hotfix0__FormatBuffedValues; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3e0db2c VA: 0x7596425b2c
	public override Void OnValueChanged(MRoomViewPropety property) { }
	// RVA: 0x3e0e2a8 VA: 0x75964262a8
	private IEnumerator _UpdateAutoLayoutsCoroutine() { }
	// RVA: 0x3e0e0d4 VA: 0x75964260d4
	private Void _UpdateSavedTime(MRoomViewModel viewModel, ManufactSnapshot snapshot) { }
	// RVA: 0x3e0e354 VA: 0x7596426354
	private Void _UpdateSecond(TickValue tickValue) { }
	// RVA: 0x3e0de3c VA: 0x7596425e3c
	private Void _FormatBuffedValues(Single baseBuff, Single specBuff, SimpleLayoutContent layout, ref ListAdapter refAdatper, Boolean usePercentFormat) { }
	// RVA: 0x3e0e4d8 VA: 0x75964264d8
	private Void OnEnable() { }
	// RVA: 0x3e0e550 VA: 0x7596426550
	private Void Update() { }
	// RVA: 0x3e0e5cc VA: 0x75964265cc
	public Void .ctor() { }
}
```