# BuildingSMRoomInfoItem

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `GameObject _panelActive`

- `GameObject _panelInactive`

- `Text _textName`

- `Text _textCurAp`

- `Text _textMaxAp`

- `Text _textRemainTime`

- `UIAutoSlideRect _autoSlideRect`

- `CountDownTask m_mpCountDown`

- `CountDownTask m_workTimeCountDown`

- `StationCharStructModel m_cachedModel`

- `Boolean m_isInited`


## Methods

- `Void Render(StationCharStructModel)`

- `Void _UpdateManpower()`

- `Void _UpdateWorkTimeCountDown()`

- `Void _OnWorkTimeUpdate(TickValue)`

- `IEnumerator _TryEnableAutoSlide()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingSMRoomInfoItem : MonoBehaviour
{
	private GameObject _panelActive; // 0x18
	private GameObject _panelInactive; // 0x20
	private Text _textName; // 0x28
	private Text _textCurAp; // 0x30
	private Text _textMaxAp; // 0x38
	private Text _textRemainTime; // 0x40
	private UIAutoSlideRect _autoSlideRect; // 0x48
	private CountDownTask m_mpCountDown; // 0x50
	private CountDownTask m_workTimeCountDown; // 0x58
	private StationCharStructModel m_cachedModel; // 0x60
	private Boolean m_isInited; // 0xd8


	// RVA: 0x3dadd84 VA: 0x75963c5d84
	public Void Render(StationCharStructModel charModel) { }
	// RVA: 0x3dadef4 VA: 0x75963c5ef4
	private Void _UpdateManpower() { }
	// RVA: 0x3dae150 VA: 0x75963c6150
	private Void _UpdateWorkTimeCountDown() { }
	// RVA: 0x3dae3c4 VA: 0x75963c63c4
	private Void _OnWorkTimeUpdate(TickValue value) { }
	// RVA: 0x3dae350 VA: 0x75963c6350
	private IEnumerator _TryEnableAutoSlide() { }
	// RVA: 0x3dae51c VA: 0x75963c651c
	private Void Update() { }
	// RVA: 0x3dae550 VA: 0x75963c6550
	public Void .ctor() { }
}
```