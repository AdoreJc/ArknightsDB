# BuildingFloatPrivateStationView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `UIAnimationLocation _showAnim`

- `Image _panelBlank`

- `Text _txtChar`

- `UIAtlasImage _imgChar`

- `GameObject _panelFavor`

- `Text _txtFavor`

- `GameObject _panelChar`

- `Text _txtCharNum`

- `TwoStateToggle _recallStateToggle`

- `FloatStationViewModel m_viewModel`

- `Int32 m_charInstId`

- `Boolean m_isShow`

- `Tween m_tweenCache`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateShowEffect(Boolean, Boolean)`

- `Void _UpdateContent(RoomSlotModel)`

- `Void OnRecallBtnClicked()`

- `Void OnCharClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatPrivateStationView : AbstractBuildingUIFloatStationView
{
	private UIAnimationLocation _showAnim; // 0x28
	private Image _panelBlank; // 0x38
	private Text _txtChar; // 0x40
	private UIAtlasImage _imgChar; // 0x48
	private GameObject _panelFavor; // 0x50
	private Text _txtFavor; // 0x58
	private GameObject _panelChar; // 0x60
	private Text _txtCharNum; // 0x68
	private TwoStateToggle _recallStateToggle; // 0x70
	private FloatStationViewModel m_viewModel; // 0x78
	private Int32 m_charInstId; // 0x80
	private Boolean m_isShow; // 0x84
	private Tween m_tweenCache; // 0x88
	private Boolean m_isInited; // 0x90
	private UIStateFinder m_stateFinder; // 0x98
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__UpdateShowEffect; // 0x10
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x18
	private static DelegateBridge __Hotfix0_OnRecallBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0_OnCharClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3e2d5b4 VA: 0x75964455b4
	public override Void OnValueChanged(FloatStationViewProperty property) { }
	// RVA: 0x3e2d6ec VA: 0x75964456ec
	private Void _InitIfNot() { }
	// RVA: 0x3e2d780 VA: 0x7596445780
	private Void _UpdateShowEffect(Boolean isInited, Boolean isShow) { }
	// RVA: 0x3e2db44 VA: 0x7596445b44
	private Void _UpdateContent(RoomSlotModel slotModel) { }
	// RVA: 0x3e2df8c VA: 0x7596445f8c
	public Void OnRecallBtnClicked() { }
	// RVA: 0x3e2e150 VA: 0x7596446150
	public Void OnCharClicked() { }
	// RVA: 0x3e2e338 VA: 0x7596446338
	public Void .ctor() { }
}
```