# BuildingToDoNotifyItemNormalView

**Namespace:** `Torappu.Building.UI.ToDoNotify`


## Fields

- `Image _icon`

- `Text _textDesc`

- `Text _textCount`

- `Color _colorEmer`

- `Color _colorNormal`

- `Image _bkgCount`

- `CanvasGroup _effectCanvasGroup`

- `Text _textClick`

- `GameObject _panelCount`

- `GameObject _panelClick`

- `UIColorGraphic _graphic`

- `Color _colorUnselected`


## Methods

- `Sprite _FindIcon(BuildingToDoType)`

- `Void <>xLuaBaseProxy_Render(BuildingToDoCategory, BuildingToDoNotifyItemModel, Boolean, ItemClickStatusData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.ToDoNotify
public class BuildingToDoNotifyItemNormalView : BuildingToDoNotifyItemBase
{
	private Config[] _configs; // 0x58
	private Image _icon; // 0x60
	private Text _textDesc; // 0x68
	private Text _textCount; // 0x70
	private Color _colorEmer; // 0x78
	private Color _colorNormal; // 0x88
	private Image _bkgCount; // 0x98
	private CanvasGroup _effectCanvasGroup; // 0xa0
	private Text _textClick; // 0xa8
	private GameObject _panelCount; // 0xb0
	private GameObject _panelClick; // 0xb8
	private UIColorGraphic _graphic; // 0xc0
	private Color _colorUnselected; // 0xc8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__FindIcon; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3d8e50c VA: 0x75963a650c
	public override Void Render(BuildingToDoCategory category, BuildingToDoNotifyItemModel itemModel, Boolean isSelected, ItemClickStatusData itemClickStatusData) { }
	// RVA: 0x3d8e804 VA: 0x75963a6804
	private Sprite _FindIcon(BuildingToDoType type) { }
	// RVA: 0x3d8e9cc VA: 0x75963a69cc
	public Void .ctor() { }
	// RVA: 0x3d8ea38 VA: 0x75963a6a38
	private Void <>xLuaBaseProxy_Render(BuildingToDoCategory P0, BuildingToDoNotifyItemModel P1, Boolean P2, ItemClickStatusData P3) { }
}
```