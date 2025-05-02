# UIArchitectureLevelupView

**Namespace:** `Torappu.Building.UI`


## Fields

- `RectTransform _infoRoot`

- `GameObject _infoProto`

- `Text _nameLabel`

- `Image _nameIcon`

- `Image _levelImage0`

- `Image _levelImage1`

- `UIBuildCostScrollAdapter _costAdapter`

- `GameObject _conditionPanel`

- `RectTransform _conditionItemRoot`

- `GameObject _conditionItemProto`

- `Image _panelBG`

- `SimpleLayoutContent _level0Panel`

- `SimpleLayoutContent _level1Panel`

- `UIRoomTypeColorMap _roomTypeLevelMap`

- `RectTransform _costItemLayout`

- `GameObject _panelTip`

- `UIBuildingLevelPanelAdapter _adapter0`

- `UIBuildingLevelPanelAdapter _adapter1`


## Methods

- `Void _UpdateRoomLevelPanel(RoomType, Int32, Int32)`

- `Void <OnAwake>b__19_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIArchitectureLevelupView : UIArchitectureBaseView`1
{
	private RectTransform _infoRoot; // 0x48
	private GameObject _infoProto; // 0x50
	private Text _nameLabel; // 0x58
	private Image _nameIcon; // 0x60
	private Image _levelImage0; // 0x68
	private Image _levelImage1; // 0x70
	private UIBuildCostScrollAdapter _costAdapter; // 0x78
	private GameObject _conditionPanel; // 0x80
	private RectTransform _conditionItemRoot; // 0x88
	private GameObject _conditionItemProto; // 0x90
	private Image _panelBG; // 0x98
	private SimpleLayoutContent _level0Panel; // 0xa0
	private SimpleLayoutContent _level1Panel; // 0xa8
	private UIRoomTypeColorMap _roomTypeLevelMap; // 0xb0
	private RectTransform _costItemLayout; // 0xb8
	private GameObject _panelTip; // 0xc0
	private UIBuildingLevelPanelAdapter _adapter0; // 0xc8
	private UIBuildingLevelPanelAdapter _adapter1; // 0xd0
	private static DelegateBridge __Hotfix0_OnAwake; // 0x0
	private static DelegateBridge __Hotfix0__UpdateRoomLevelPanel; // 0x8
	private static DelegateBridge __Hotfix0_DoSetup; // 0x10
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3d493e0 VA: 0x75963613e0
	protected override Void OnAwake() { }
	// RVA: 0x3d494c4 VA: 0x75963614c4
	private Void _UpdateRoomLevelPanel(RoomType roomType, Int32 level0, Int32 level1) { }
	// RVA: 0x3d496e4 VA: 0x75963616e4
	protected override Void DoSetup(Argument arg) { }
	// RVA: 0x3d4a3bc VA: 0x75963623bc
	protected override Void OnPlayerDataChanged(Object _) { }
	// RVA: 0x3d4a56c VA: 0x759636256c
	public Void .ctor() { }
	// RVA: 0x3d4a6e4 VA: 0x75963626e4
	private Void <OnAwake>b__19_0() { }
}
```