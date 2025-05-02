# BuildingTradingStatusView

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `Text _textManpowerCost`

- `SimpleLayoutContent _mpBuffLayout`

- `ThreeStateToggle _toggleManpowerCost`

- `Text _textSpeedEmpty`

- `SimpleLayoutContent _speedBuffLayout`

- `ThreeStateToggle _toggleOrderSpeed`

- `Image _imageOrderType`

- `GameObject _panelStrategyDisable`

- `Button _stgButton`

- `Text _textStrategyUnlock`

- `Color _colorBuff`

- `Color _colorDebuff`

- `Color _bkgColorBuff`

- `Color _textColorBuff`

- `BuffStruct m_buffCache`

- `Boolean m_isInited`

- `String m_buffColorCode`

- `String m_debuffColorCode`

- `OrderType m_orderTypeCache`

- `Boolean m_isStrategryUnlockedCache`

- `ListAdapter m_mpBuffAdapter`

- `ListAdapter m_speedBuffAdapter`


## Methods

- `Void OnEnable()`

- `Void _RenderBuff(TRoomViewModel)`

- `Void _RenderNegotiation(TRoomViewModel)`

- `String _PickColorCode(Int32)`

- `IEnumerator _UpdateAutoLayouts()`

- `Void _FormatBuffedValues(Single, Single, SimpleLayoutContent, ref, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingStatusView : DataBinder`1
{
	private Text _textManpowerCost; // 0x20
	private SimpleLayoutContent _mpBuffLayout; // 0x28
	private ThreeStateToggle _toggleManpowerCost; // 0x30
	private Text _textSpeedEmpty; // 0x38
	private SimpleLayoutContent _speedBuffLayout; // 0x40
	private ThreeStateToggle _toggleOrderSpeed; // 0x48
	private Image _imageOrderType; // 0x50
	private GameObject _panelStrategyDisable; // 0x58
	private Button _stgButton; // 0x60
	private Text _textStrategyUnlock; // 0x68
	private RectTransform[] _autoLayouts; // 0x70
	private Color _colorBuff; // 0x78
	private Color _colorDebuff; // 0x88
	private OrderTypeImage[] _orderTypeImages; // 0x98
	private Color _bkgColorBuff; // 0xa0
	private Color _textColorBuff; // 0xb0
	private BuffStruct m_buffCache; // 0xc0
	private Boolean m_isInited; // 0xd4
	private String m_buffColorCode; // 0xd8
	private String m_debuffColorCode; // 0xe0
	private OrderType m_orderTypeCache; // 0xe8
	private Boolean m_isStrategryUnlockedCache; // 0xec
	private ListAdapter m_mpBuffAdapter; // 0xf0
	private ListAdapter m_speedBuffAdapter; // 0xf8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__RenderBuff; // 0x10
	private static DelegateBridge __Hotfix0__RenderNegotiation; // 0x18
	private static DelegateBridge __Hotfix0__PickColorCode; // 0x20
	private static DelegateBridge __Hotfix0__UpdateToggleByBuff; // 0x28
	private static DelegateBridge __Hotfix0__UpdateAutoLayouts; // 0x30
	private static DelegateBridge __Hotfix0__FormatBuffedValues; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3d8b64c VA: 0x75963a364c
	private Void OnEnable() { }
	// RVA: 0x3d8b770 VA: 0x75963a3770
	public override Void OnValueChanged(TRoomViewProperty property) { }
	// RVA: 0x3d8b85c VA: 0x75963a385c
	private Void _RenderBuff(TRoomViewModel viewModel) { }
	// RVA: 0x3d8ba9c VA: 0x75963a3a9c
	private Void _RenderNegotiation(TRoomViewModel viewModel) { }
	// RVA: 0x3d8c0ec VA: 0x75963a40ec
	private String _PickColorCode(Int32 sign) { }
	// RVA: 0x3d8bfd8 VA: 0x75963a3fd8
	private static Void _UpdateToggleByBuff(ThreeStateToggle toggle, Single buffVal, Int32 sign) { }
	// RVA: 0x3d8b6c4 VA: 0x75963a36c4
	private IEnumerator _UpdateAutoLayouts() { }
	// RVA: 0x3d8bd40 VA: 0x75963a3d40
	private Void _FormatBuffedValues(Single baseBuff, Single spcBuff, SimpleLayoutContent layout, ref ListAdapter refAdatper, Boolean usePercentFormat) { }
	// RVA: 0x3d8c270 VA: 0x75963a4270
	public Void .ctor() { }
}
```