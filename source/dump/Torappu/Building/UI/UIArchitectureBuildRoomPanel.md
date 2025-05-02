# UIArchitectureBuildRoomPanel

**Namespace:** `Torappu.Building.UI`


## Fields

- `RectTransform _infoRoot`

- `GameObject _infoProto`

- `Text _nameLabel`

- `Text _countLabel`

- `GameObject _descPanel`

- `Text _descPanelNameLabel`

- `Text _descPanelDescLabel`

- `Image _nameIcon`

- `Image _panelBG`

- `Image _selectedFrame`

- `Image _unselectedFrame`

- `UIBuildCostScrollAdapter _costAdapter`

- `GameObject _conditionPanel`

- `RectTransform _conditionItemRoot`

- `GameObject _conditionItemProto`

- `Int32 m_infoFrameDelay`

- `Boolean m_selected`


## Methods

- `Void Setup(Argument)`

- `Void Select()`

- `Void Unselect()`

- `Void OnDescButtonPressed()`

- `Void OnDescBGPressed()`

- `Void NotifyPlayerDataChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIArchitectureBuildRoomPanel : MonoBehaviour
{
	private RectTransform _infoRoot; // 0x18
	private GameObject _infoProto; // 0x20
	private Text _nameLabel; // 0x28
	private Text _countLabel; // 0x30
	private GameObject _descPanel; // 0x38
	private Text _descPanelNameLabel; // 0x40
	private Text _descPanelDescLabel; // 0x48
	private Image _nameIcon; // 0x50
	private Image _panelBG; // 0x58
	private Image _selectedFrame; // 0x60
	private Image _unselectedFrame; // 0x68
	private UIBuildCostScrollAdapter _costAdapter; // 0x70
	private GameObject _conditionPanel; // 0x78
	private RectTransform _conditionItemRoot; // 0x80
	private GameObject _conditionItemProto; // 0x88
	private Int32 m_infoFrameDelay; // 0x90
	private Boolean m_selected; // 0x94


	// RVA: 0x3d44410 VA: 0x759635c410
	public Void Setup(Argument arg) { }
	// RVA: 0x3d44f08 VA: 0x759635cf08
	public Void Select() { }
	// RVA: 0x3d44fdc VA: 0x759635cfdc
	public Void Unselect() { }
	// RVA: 0x3d450bc VA: 0x759635d0bc
	public Void OnDescButtonPressed() { }
	// RVA: 0x3d450d8 VA: 0x759635d0d8
	public Void OnDescBGPressed() { }
	// RVA: 0x3d450e8 VA: 0x759635d0e8
	public Void NotifyPlayerDataChanged() { }
	// RVA: 0x3d4522c VA: 0x759635d22c
	public Void .ctor() { }
}
```