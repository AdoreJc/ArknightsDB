# UIArchitectureCleanView

**Namespace:** `Torappu.Building.UI`


## Fields

- `RectTransform _listRoom`

- `GameObject _itemCardProto`

- `GameObject _conditionPanelConnect`

- `GameObject _conditionPanelControlLevel`

- `UIComplexRoomLevelView _conditionlevelView`

- `Text _textLaborFrom`

- `Text _textLaborTo`

- `Int32 m_costLabor`

- `Int32 m_provideLabor`

- `BuildingLaborViewModel m_laborModel`


## Methods

- `Void _UpdateLabor()`

- `Void <_UpdateLabor>b__18_0(BuildingLaborViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIArchitectureCleanView : UIArchitectureBaseView`1
{
	private RectTransform _listRoom; // 0x48
	private GameObject _itemCardProto; // 0x50
	private GameObject _conditionPanelConnect; // 0x58
	private GameObject _conditionPanelControlLevel; // 0x60
	private UIComplexRoomLevelView _conditionlevelView; // 0x68
	private GameObject[] _mainViewGameObjects; // 0x70
	private GameObject[] _lockedViewGameObjects; // 0x78
	private Text _textLaborFrom; // 0x80
	private Text _textLaborTo; // 0x88
	private List`1 m_costCards; // 0x90
	private List`1 m_costModels; // 0x98
	private Int32 m_costLabor; // 0xa0
	private Int32 m_provideLabor; // 0xa4
	private BuildingLaborViewModel m_laborModel; // 0xa8
	private static DelegateBridge __Hotfix0_DoSetup; // 0x0
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__UpdateLabor; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3d482bc VA: 0x75963602bc
	protected override Void DoSetup(Argument arg) { }
	// RVA: 0x3d48dc8 VA: 0x7596360dc8
	protected override Void OnPlayerDataChanged(Object _) { }
	// RVA: 0x3d48fe4 VA: 0x7596360fe4
	protected virtual Void Update() { }
	// RVA: 0x3d48b6c VA: 0x7596360b6c
	private Void _UpdateLabor() { }
	// RVA: 0x3d49060 VA: 0x7596361060
	public Void .ctor() { }
	// RVA: 0x3d49144 VA: 0x7596361144
	private Void <_UpdateLabor>b__18_0(BuildingLaborViewModel _) { }
}
```