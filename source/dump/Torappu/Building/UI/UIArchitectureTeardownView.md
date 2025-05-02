# UIArchitectureTeardownView

**Namespace:** `Torappu.Building.UI`


## Fields

- `RectTransform _infoRoot`

- `GameObject _infoProto`

- `Text _nameLabel`

- `Image _nameIcon`

- `Image _levelImage0`

- `Image _levelImage1`

- `SimpleLayoutContent _level0Panel`

- `SimpleLayoutContent _level1Panel`

- `GameObject _zeroLevelIcon`

- `UIRoomTypeColorMap _roomTypeLevelMap`

- `UIBuildCostScrollAdapter _returnAdapter`

- `RectTransform _returnItemLayout`

- `GameObject _panelTip`

- `UIBuildingLevelPanelAdapter _adapter0`

- `UIBuildingLevelPanelAdapter _adapter1`


## Methods

- `Void _UpdateRoomLevelPanel(RoomType, Int32, Int32)`

- `Void <OnAwake>b__16_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIArchitectureTeardownView : UIArchitectureBaseView`1
{
	private RectTransform _infoRoot; // 0x48
	private GameObject _infoProto; // 0x50
	private Text _nameLabel; // 0x58
	private Image _nameIcon; // 0x60
	private Image _levelImage0; // 0x68
	private Image _levelImage1; // 0x70
	private SimpleLayoutContent _level0Panel; // 0x78
	private SimpleLayoutContent _level1Panel; // 0x80
	private GameObject _zeroLevelIcon; // 0x88
	private UIRoomTypeColorMap _roomTypeLevelMap; // 0x90
	private UIBuildCostScrollAdapter _returnAdapter; // 0x98
	private RectTransform _returnItemLayout; // 0xa0
	private GameObject _panelTip; // 0xa8
	private UIBuildingLevelPanelAdapter _adapter0; // 0xb0
	private UIBuildingLevelPanelAdapter _adapter1; // 0xb8
	private static DelegateBridge __Hotfix0_OnAwake; // 0x0
	private static DelegateBridge __Hotfix0__UpdateRoomLevelPanel; // 0x8
	private static DelegateBridge __Hotfix0_DoSetup; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d4bc78 VA: 0x7596363c78
	protected override Void OnAwake() { }
	// RVA: 0x3d4bd5c VA: 0x7596363d5c
	private Void _UpdateRoomLevelPanel(RoomType roomType, Int32 level0, Int32 level1) { }
	// RVA: 0x3d4bf7c VA: 0x7596363f7c
	protected override Void DoSetup(Argument arg) { }
	// RVA: 0x3d4c54c VA: 0x759636454c
	public Void .ctor() { }
	// RVA: 0x3d4c63c VA: 0x759636463c
	private Void <OnAwake>b__16_0() { }
}
```