# BuildingTrainingTrainerStatusView

**Namespace:** `Torappu.Building.UI.Train`


## Fields

- `UIAtlasImage _trainerPortrait`

- `RectTransform _mpContainer`

- `BuildingCharMPStateBar _mpBarPrefab`

- `BuildingBuffDescView _buffView`

- `RectTransform _panelMpLayout`

- `Text _textCurAp`

- `Text _textMaxAp`

- `Color _colorMpNormal`

- `Color _colorMpTired`

- `Image _bkgMp`

- `GameObject _panelTired`

- `Boolean m_isInited`

- `BuildingCharModel m_cachedTrainer`

- `BuildingCharMPHelper m_mpHelper`

- `BuildingCharMPStateBar m_mpBar`


## Methods

- `Void InitData(RoomSlotModel)`

- `Void Update()`

- `Void OnEnable()`

- `Void _Init()`

- `Void _OnManpowerChanged()`

- `IEnumerator _UpdateAutoLayoutCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Train
public class BuildingTrainingTrainerStatusView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _trainerPortrait; // 0x18
	private RectTransform _mpContainer; // 0x20
	private BuildingCharMPStateBar _mpBarPrefab; // 0x28
	private BuildingBuffDescView _buffView; // 0x30
	private RectTransform _panelMpLayout; // 0x38
	private Text _textCurAp; // 0x40
	private Text _textMaxAp; // 0x48
	private Color _colorMpNormal; // 0x50
	private Color _colorMpTired; // 0x60
	private Image _bkgMp; // 0x70
	private GameObject _panelTired; // 0x78
	private Boolean m_isInited; // 0x80
	private BuildingCharModel m_cachedTrainer; // 0x88
	private BuildingCharMPHelper m_mpHelper; // 0xf8
	private BuildingCharMPStateBar m_mpBar; // 0x100
	private List`1 m_buffs; // 0x108
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0__Init; // 0x18
	private static DelegateBridge __Hotfix0__OnManpowerChanged; // 0x20
	private static DelegateBridge __Hotfix0__UpdateAutoLayoutCoroutine; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3d7ab90 VA: 0x7596392b90
	public Void InitData(RoomSlotModel trainingSlot) { }
	// RVA: 0x3d7d514 VA: 0x7596395514
	private Void Update() { }
	// RVA: 0x3d7d588 VA: 0x7596395588
	private Void OnEnable() { }
	// RVA: 0x3d7d1b0 VA: 0x75963951b0
	private Void _Init() { }
	// RVA: 0x3d7d2dc VA: 0x75963952dc
	private Void _OnManpowerChanged() { }
	// RVA: 0x3d7d600 VA: 0x7596395600
	private IEnumerator _UpdateAutoLayoutCoroutine() { }
	// RVA: 0x3d7d6d4 VA: 0x75963956d4
	public Void .ctor() { }
}
```