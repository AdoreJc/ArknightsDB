# BuildingUIFloatRoomDetailView

**Namespace:** `Torappu.Building.UI`


## Fields

- `Text _textName`

- `SimpleLayoutContent _levelInfoContent`

- `Text _textDesc`

- `UIAnimationLocation _showAnim`

- `Image _panelBlack`

- `SimpleLayoutContent _levelPanel`

- `Boolean m_isInited`

- `Boolean m_isShowing`

- `FloatRoomDetailModel m_viewModel`

- `DetailInfoAdapter m_infoAdapter`

- `Tween m_tweenCache`

- `UIBuildingLevelPanelAdapter m_levelAdapter`

- `Action requestToClose`


## Methods

- `Void EventOnBlankClicked()`

- `Void _InitIfNot()`

- `Void _UpdateShowEffect()`

- `Void _UpdateContent()`

- `Void <_UpdateContent>b__19_0(LevelInfoItem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingUIFloatRoomDetailView : DataBinder`1
{
	private Text _textName; // 0x20
	private SimpleLayoutContent _levelInfoContent; // 0x28
	private Text _textDesc; // 0x30
	private UIAnimationLocation _showAnim; // 0x38
	private Image _panelBlack; // 0x48
	private SimpleLayoutContent _levelPanel; // 0x50
	private Boolean m_isInited; // 0x58
	private Boolean m_isShowing; // 0x59
	private FloatRoomDetailModel m_viewModel; // 0x60
	private DetailInfoAdapter m_infoAdapter; // 0x68
	private List`1 m_detailList; // 0x70
	private Tween m_tweenCache; // 0x78
	private UIBuildingLevelPanelAdapter m_levelAdapter; // 0x80
	public Action requestToClose; // 0x88
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBlankClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__UpdateShowEffect; // 0x18
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3d39d70 VA: 0x7596351d70
	public override Void OnValueChanged(FloatRoomDetailViewProperty property) { }
	// RVA: 0x3d3a45c VA: 0x759635245c
	public Void EventOnBlankClicked() { }
	// RVA: 0x3d3a1fc VA: 0x75963521fc
	private Void _InitIfNot() { }
	// RVA: 0x3d39f24 VA: 0x7596351f24
	private Void _UpdateShowEffect() { }
	// RVA: 0x3d3a2e4 VA: 0x75963522e4
	private Void _UpdateContent() { }
	// RVA: 0x3d3a574 VA: 0x7596352574
	public Void .ctor() { }
	// RVA: 0x3d3a694 VA: 0x7596352694
	private Void <_UpdateContent>b__19_0(LevelInfoItem infoItem) { }
}
```