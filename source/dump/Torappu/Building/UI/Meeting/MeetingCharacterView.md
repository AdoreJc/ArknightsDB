# MeetingCharacterView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `GameObject _emptyPanel`

- `GameObject _stationPanel`

- `UIAtlasImage _imgPortrait`

- `Text _name`

- `BuildingBuffDescView _buffView`

- `BuildingCharMPStateBar _mpStateBarPrefab`

- `Transform _mpStateBarContainer`

- `Text _apLabel`

- `Text _maxApLabel`

- `Image _gaugeBackground`

- `UIAutoSlideRect _autoSlideRect`

- `BuildingCharMPStateBar m_mpBar`

- `BuildingCharModel m_charModel`

- `CountDownTask m_mpCountDown`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void UpdateTime(Single)`

- `IEnumerator _LayoutSetupCoroutine()`

- `Void Setup(IMeetingStationaryCharacter)`

- `Void _UpdateManpower()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingCharacterView : MonoBehaviour, ITimeWatcher, IHotfixable
{
	private const String NORMAL_COLOR; // 0x0
	private const String BURNOUT_COLOR; // 0x0
	private GameObject _emptyPanel; // 0x18
	private GameObject _stationPanel; // 0x20
	private UIAtlasImage _imgPortrait; // 0x28
	private Text _name; // 0x30
	private BuildingBuffDescView _buffView; // 0x38
	private BuildingCharMPStateBar _mpStateBarPrefab; // 0x40
	private Transform _mpStateBarContainer; // 0x48
	private Text _apLabel; // 0x50
	private Text _maxApLabel; // 0x58
	private Image _gaugeBackground; // 0x60
	private UIAutoSlideRect _autoSlideRect; // 0x68
	private BuildingCharMPStateBar m_mpBar; // 0x70
	private BuildingCharModel m_charModel; // 0x78
	private CountDownTask m_mpCountDown; // 0xe8
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x10
	private static DelegateBridge __Hotfix0__LayoutSetupCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_Setup; // 0x20
	private static DelegateBridge __Hotfix0__UpdateManpower; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3df44f4 VA: 0x759640c4f4
	private Void Start() { }
	// RVA: 0x3df4564 VA: 0x759640c564
	private Void OnDestroy() { }
	// RVA: 0x3df45d4 VA: 0x759640c5d4
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x3df4668 VA: 0x759640c668
	private IEnumerator _LayoutSetupCoroutine() { }
	// RVA: 0x3defda4 VA: 0x7596407da4
	public Void Setup(IMeetingStationaryCharacter character) { }
	// RVA: 0x3df473c VA: 0x759640c73c
	private Void _UpdateManpower() { }
	// RVA: 0x3df4c40 VA: 0x759640cc40
	public Void .ctor() { }
}
```