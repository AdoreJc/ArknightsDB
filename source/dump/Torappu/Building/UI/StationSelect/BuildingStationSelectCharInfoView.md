# BuildingStationSelectCharInfoView

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `GameObject _panelActive`

- `Text _textName`

- `Text _textAp`

- `Text _textApLimit`

- `RectTransform _manpowerBarContainer`

- `RectTransform _autoLayoutAp`

- `StationCharViewModel m_selectedChar`

- `BuildingCharModel m_buildingCharCache`

- `BuildingCharMPStateBar m_manpowerBar`

- `Boolean m_isInited`

- `CountDownTask m_workTimeCountDown`

- `BuildingCharMPHelper m_mpHelper`


## Methods

- `Void _RenderActive()`

- `IEnumerator _UpdateAutoLayoutsCoroutine()`

- `Void _OnManpowerChanged()`

- `Void OnEnable()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectCharInfoView : DataBinder`1
{
	private GameObject _panelActive; // 0x20
	private Text _textName; // 0x28
	private Text _textAp; // 0x30
	private Text _textApLimit; // 0x38
	private RectTransform _manpowerBarContainer; // 0x40
	private RectTransform _autoLayoutAp; // 0x48
	private StationCharViewModel m_selectedChar; // 0x50
	private BuildingCharModel m_buildingCharCache; // 0x58
	private BuildingCharMPStateBar m_manpowerBar; // 0xc8
	private Boolean m_isInited; // 0xd0
	private CountDownTask m_workTimeCountDown; // 0xd8
	private BuildingCharMPHelper m_mpHelper; // 0xe0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderActive; // 0x8
	private static DelegateBridge __Hotfix0__UpdateAutoLayoutsCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__OnManpowerChanged; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3d9b658 VA: 0x75963b3658
	public override Void OnValueChanged(StationCharGroupProperty property) { }
	// RVA: 0x3d9b878 VA: 0x75963b3878
	private Void _RenderActive() { }
	// RVA: 0x3d9bd20 VA: 0x75963b3d20
	private IEnumerator _UpdateAutoLayoutsCoroutine() { }
	// RVA: 0x3d9ba48 VA: 0x75963b3a48
	private Void _OnManpowerChanged() { }
	// RVA: 0x3d9bdf4 VA: 0x75963b3df4
	private Void OnEnable() { }
	// RVA: 0x3d9be6c VA: 0x75963b3e6c
	private Void Update() { }
	// RVA: 0x3d9bef8 VA: 0x75963b3ef8
	public Void .ctor() { }
}
```