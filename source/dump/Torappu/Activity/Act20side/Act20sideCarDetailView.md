# Act20sideCarDetailView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Act20sideCarBlueprintView _bluePrintCar`

- `Act20sideRecycleCompAdapter _adapter`

- `AccessPosEvent _onClickEvent`

- `Act20sideCarObject _carObject`

- `Transform _carContainer`

- `Act20sideCarOSObj _carOsObj`

- `GameObject _detailPart`

- `Text _detailText`

- `GameObject _emptyPart`

- `GameObject _notEmptyPart`

- `Image _coloredImg`

- `GameObject _applyBtn`

- `Text _compName`

- `Act20sideCarObject m_carObject`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarDetailView : DataBinder`1, IHotfixable
{
	private Act20sideCarBlueprintView _bluePrintCar; // 0x20
	private List`1 _carCompList; // 0x28
	private Act20sideRecycleCompAdapter _adapter; // 0x30
	private AccessPosEvent _onClickEvent; // 0x38
	private Act20sideCarObject _carObject; // 0x40
	private Transform _carContainer; // 0x48
	private Act20sideCarOSObj _carOsObj; // 0x50
	private GameObject _detailPart; // 0x58
	private Text _detailText; // 0x60
	private GameObject _emptyPart; // 0x68
	private GameObject _notEmptyPart; // 0x70
	private Image _coloredImg; // 0x78
	private GameObject[] _exhibitDiffObjects; // 0x80
	private GameObject[] _battleDiffObjects; // 0x88
	private GameObject _applyBtn; // 0x90
	private Text _compName; // 0x98
	private Act20sideCarObject m_carObject; // 0xa0
	private Boolean m_isInited; // 0xa8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32ee5ec VA: 0x75959065ec
	private Void _InitIfNot() { }
	// RVA: 0x32ee6d4 VA: 0x75959066d4
	public override Void OnValueChanged(Act20sideCartCompSelectProperty property) { }
	// RVA: 0x32eede4 VA: 0x7595906de4
	public Void .ctor() { }
}
```