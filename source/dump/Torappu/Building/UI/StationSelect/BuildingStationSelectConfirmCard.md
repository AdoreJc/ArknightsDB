# BuildingStationSelectConfirmCard

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `GameObject _panelInfo`

- `GameObject _panelEmpty`

- `Text _textName`

- `UIAtlasImage _portrait`

- `SimpleLayoutContent _buffIconLayout`

- `RectTransform _manpowerBarContainer`

- `GameObject _maskOnWork`

- `GameObject _maskOffWork`

- `GameObject _maskAssist`

- `GameObject _buffPanel`

- `Button _hotzone`

- `GameObject _assitIcon`

- `Text _assistRoomCode`

- `StationCharViewModel m_viewModel`

- `ViewCache m_viewCache`

- `Boolean m_isInited`

- `BuildingCharMPStateBar m_mpBar`

- `BuildingCharMPHelper m_mpHelper`

- `BuffIconAdapter m_buffAdapter`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void Render(ChangedCharCardViewModel)`

- `Void UpdateTime(Single)`

- `Void _OnManpowerChanged()`

- `Void _RenderCharInfo(ChangedCharCardViewModel)`

- `Void _Init(StationCharViewModel)`

- `Void _RenderAssistPanel(ChangedCharCardViewModel)`

- `Void _RenderMP()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectConfirmCard : MonoBehaviour, ITimeWatcher
{
	private GameObject _panelInfo; // 0x18
	private GameObject _panelEmpty; // 0x20
	private Text _textName; // 0x28
	private UIAtlasImage _portrait; // 0x30
	private SimpleLayoutContent _buffIconLayout; // 0x38
	private RectTransform _manpowerBarContainer; // 0x40
	private GameObject _maskOnWork; // 0x48
	private GameObject _maskOffWork; // 0x50
	private GameObject _maskAssist; // 0x58
	private GameObject _buffPanel; // 0x60
	private Button _hotzone; // 0x68
	private GameObject _assitIcon; // 0x70
	private Text _assistRoomCode; // 0x78
	private StationCharViewModel m_viewModel; // 0x80
	private ViewCache m_viewCache; // 0x88
	private Boolean m_isInited; // 0x100
	private BuildingCharMPStateBar m_mpBar; // 0x108
	private BuildingCharMPHelper m_mpHelper; // 0x110
	private BuffIconAdapter m_buffAdapter; // 0x118


	// RVA: 0x3d9ca50 VA: 0x75963b4a50
	private Void Start() { }
	// RVA: 0x3d9ca5c VA: 0x75963b4a5c
	private Void OnDestroy() { }
	// RVA: 0x3d9ca68 VA: 0x75963b4a68
	public Void Render(ChangedCharCardViewModel statusModel) { }
	// RVA: 0x3d9cde4 VA: 0x75963b4de4
	public Void UpdateTime(Single delta) { }
	// RVA: 0x3d9ce24 VA: 0x75963b4e24
	private Void _OnManpowerChanged() { }
	// RVA: 0x3d9cad0 VA: 0x75963b4ad0
	private Void _RenderCharInfo(ChangedCharCardViewModel statusModel) { }
	// RVA: 0x3d9d07c VA: 0x75963b507c
	private Void _Init(StationCharViewModel viewModel) { }
	// RVA: 0x3d9d228 VA: 0x75963b5228
	private Void _RenderAssistPanel(ChangedCharCardViewModel statusModel) { }
	// RVA: 0x3d9ce28 VA: 0x75963b4e28
	private Void _RenderMP() { }
	// RVA: 0x3d9d3e0 VA: 0x75963b53e0
	public Void .ctor() { }
}
```