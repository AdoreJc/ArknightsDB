# BuildingManufactOutputCountView

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `Text _textCount`

- `Text _textLimit`

- `RectTransform _lineLayout`

- `StretchProgressBar _progress`

- `Image _virtualProgress`

- `Color _colorVirtualNormal`

- `Color _colorVirtualHilight`

- `Color _colorCountHilight`

- `GameObject _panelOverrloaded`

- `Text _textOverloaded`

- `String m_colorCountHilightCode`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `IEnumerator _UpdateLayoutCoroutine()`

- `Void _AdjustVirtualProgress(MRoomViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactOutputCountView : DataBinder`1
{
	private Text _textCount; // 0x20
	private Text _textLimit; // 0x28
	private RectTransform _lineLayout; // 0x30
	private StretchProgressBar _progress; // 0x38
	private Image _virtualProgress; // 0x40
	private Color _colorVirtualNormal; // 0x48
	private Color _colorVirtualHilight; // 0x58
	private Color _colorCountHilight; // 0x68
	private GameObject _panelOverrloaded; // 0x78
	private Text _textOverloaded; // 0x80
	private String m_colorCountHilightCode; // 0x88
	private Boolean m_isInited; // 0x90
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__UpdateLayoutCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__AdjustVirtualProgress; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3e0b8bc VA: 0x75964238bc
	protected virtual Void OnEnable() { }
	// RVA: 0x3e0b9e0 VA: 0x75964239e0
	public override Void OnValueChanged(MRoomViewPropety property) { }
	// RVA: 0x3e0bc84 VA: 0x7596423c84
	private Void _InitIfNot() { }
	// RVA: 0x3e0b934 VA: 0x7596423934
	private IEnumerator _UpdateLayoutCoroutine() { }
	// RVA: 0x3e0bd70 VA: 0x7596423d70
	private Void _AdjustVirtualProgress(MRoomViewModel viewModel) { }
	// RVA: 0x3e0bf2c VA: 0x7596423f2c
	public Void .ctor() { }
}
```