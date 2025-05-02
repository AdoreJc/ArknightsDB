# BuildingUIFloatStationItem

**Namespace:** `Torappu.Building.UI`


## Fields

- `GameObject _panelActive`

- `GameObject _panelEmpty`

- `BuildingCharAvatar _avatarPrefab`

- `RectTransform _avatarContainer`

- `Text _textName`

- `Text _textAp`

- `Text _textMaxAp`

- `FillProgressBar _apProgress`

- `Text _textStatus`

- `Text _textTime`

- `RectTransform _lineAp`

- `Text _textStation`

- `GameObject _dormLockFrame`

- `GameObject _dormLockIcon`

- `Int32 m_index`

- `BuildingCharModel m_charModel`

- `BuildingCharAvatar m_avatarView`

- `CountDownTask m_apCountDown`

- `CountDownTask m_workFinishCountDown`

- `Boolean m_isInited`


## Properties

- `String stationText`


## Methods

- `Void _Init()`

- `String get_stationText()`

- `Void set_stationText(String)`

- `Void Render(BuildingCharModel, Int32)`

- `Void _OnAvatarClicked()`

- `Void Start()`

- `Void Update()`

- `Void _UpdateWorkTime(TickValue)`

- `Void EventOnRemoveBtnClicked()`

- `Void EventOnPanelClicked()`

- `Void _OnCharItemClicked()`

- `Void _RenderActive()`

- `Void _UpdateAp()`

- `Void _UpdateWorkFinish()`

- `Void <_Init>b__20_0(BuildingCharModel, Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingUIFloatStationItem : MonoBehaviour, IHotfixable
{
	private GameObject _panelActive; // 0x18
	private GameObject _panelEmpty; // 0x20
	private BuildingCharAvatar _avatarPrefab; // 0x28
	private RectTransform _avatarContainer; // 0x30
	private Text _textName; // 0x38
	private Text _textAp; // 0x40
	private Text _textMaxAp; // 0x48
	private FillProgressBar _apProgress; // 0x50
	private Text _textStatus; // 0x58
	private Text _textTime; // 0x60
	private RectTransform _lineAp; // 0x68
	private Text _textStation; // 0x70
	private GameObject _dormLockFrame; // 0x78
	private GameObject _dormLockIcon; // 0x80
	private Int32 m_index; // 0x88
	private BuildingCharModel m_charModel; // 0x90
	private BuildingCharAvatar m_avatarView; // 0x100
	private CountDownTask m_apCountDown; // 0x108
	private CountDownTask m_workFinishCountDown; // 0x110
	private Boolean m_isInited; // 0x118
	public Action`2 onItemClicked; // 0x120
	public Action`2 onRemoveClicked; // 0x128
	private static DelegateBridge __Hotfix0__Init; // 0x0
	private static DelegateBridge __Hotfix0_get_stationText; // 0x8
	private static DelegateBridge __Hotfix0_set_stationText; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__OnAvatarClicked; // 0x20
	private static DelegateBridge __Hotfix0_Start; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge __Hotfix0__UpdateWorkTime; // 0x38
	private static DelegateBridge __Hotfix0_EventOnRemoveBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnPanelClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnCharItemClicked; // 0x50
	private static DelegateBridge __Hotfix0__RenderActive; // 0x58
	private static DelegateBridge __Hotfix0__UpdateAp; // 0x60
	private static DelegateBridge __Hotfix0__UpdateWorkFinish; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String stationText { get; set; }

	// RVA: 0x3d3a9d4 VA: 0x75963529d4
	private Void _Init() { }
	// RVA: 0x3d3ab24 VA: 0x7596352b24
	public String get_stationText() { }
	// RVA: 0x3d3aba0 VA: 0x7596352ba0
	public Void set_stationText(String value) { }
	// RVA: 0x3d3ac34 VA: 0x7596352c34
	public Void Render(BuildingCharModel charModel, Int32 index) { }
	// RVA: 0x3d3b470 VA: 0x7596353470
	private Void _OnAvatarClicked() { }
	// RVA: 0x3d3b534 VA: 0x7596353534
	private Void Start() { }
	// RVA: 0x3d3b5c8 VA: 0x75963535c8
	private Void Update() { }
	// RVA: 0x3d3b654 VA: 0x7596353654
	private Void _UpdateWorkTime(TickValue tick) { }
	// RVA: 0x3d3b7bc VA: 0x75963537bc
	public Void EventOnRemoveBtnClicked() { }
	// RVA: 0x3d3b88c VA: 0x759635388c
	public Void EventOnPanelClicked() { }
	// RVA: 0x3d3b90c VA: 0x759635390c
	private Void _OnCharItemClicked() { }
	// RVA: 0x3d3ae20 VA: 0x7596352e20
	private Void _RenderActive() { }
	// RVA: 0x3d3af3c VA: 0x7596352f3c
	private Void _UpdateAp() { }
	// RVA: 0x3d3b218 VA: 0x7596353218
	private Void _UpdateWorkFinish() { }
	// RVA: 0x3d3b9d0 VA: 0x75963539d0
	public Void .ctor() { }
	// RVA: 0x3d3ba8c VA: 0x7596353a8c
	private Void <_Init>b__20_0(BuildingCharModel _1, Object _2) { }
}
```