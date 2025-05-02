# OpenServerMissionItemView

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `Text _missionDetail`

- `Text _itemName`

- `Image _itemIcon`

- `Text _itemCount`

- `Text _missionState`

- `RectTransform _length`

- `GameObject _finishPart`

- `GameObject _unfinishPart`

- `CanvasGroup _rightCanvasGroup`

- `GameObject _alreadyGetPart`

- `Animator _onFinish`

- `String m_missionID`


## Methods

- `Void Initialize(String, MissionData, MissionPlayerState)`

- `Void OnAnimatorStart()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerMissionItemView : MonoBehaviour
{
	private Text _missionDetail; // 0x18
	private Text _itemName; // 0x20
	private Image _itemIcon; // 0x28
	private Text _itemCount; // 0x30
	private Text _missionState; // 0x38
	private RectTransform _length; // 0x40
	private GameObject _finishPart; // 0x48
	private GameObject _unfinishPart; // 0x50
	private CanvasGroup _rightCanvasGroup; // 0x58
	private GameObject _alreadyGetPart; // 0x60
	private Animator _onFinish; // 0x68
	public Action`1 onGetMission; // 0x70
	private String m_missionID; // 0x78
	private const String MISSION_COMPLETE_ANIMATOR; // 0x0


	// RVA: 0x285234c VA: 0x7594e6a34c
	public Void Initialize(String missionID, MissionData missionData, MissionPlayerState missionState) { }
	// RVA: 0x28527ac VA: 0x7594e6a7ac
	public Void OnAnimatorStart() { }
	// RVA: 0x2852804 VA: 0x7594e6a804
	public Void OnClick() { }
	// RVA: 0x2852824 VA: 0x7594e6a824
	public Void .ctor() { }
}
```