# Act5D1RuneMissionItem

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Sprite _uncomplete`

- `Sprite _completed`

- `Sprite _goted`

- `Image _bg`

- `Text _missionDesc`

- `GameObject _runeBtn`

- `Transform _itemIconRoot`

- `Text _prgText`

- `Slider _prg`

- `GameObject _btn`

- `GameObject _gotFlag`

- `UIChildrenColorGraphic _colorChanger`

- `MissionData m_mission`

- `Act5D1RuneMissionPanel m_owner`

- `Boolean m_cannotFlag`

- `Boolean m_hasGot`


## Methods

- `Void SynMission(MissionData, Act5D1RuneMissionPanel)`

- `Void HandleGetReward()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void ShowRuneDetail()`

- `Void OnEnable()`

- `Void <HandleGetReward>b__20_0(ActivityConfirmMissionResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
internal class Act5D1RuneMissionItem : MonoBehaviour, IHotfixable
{
	private Sprite _uncomplete; // 0x18
	private Sprite _completed; // 0x20
	private Sprite _goted; // 0x28
	private Image _bg; // 0x30
	private Text _missionDesc; // 0x38
	private GameObject _runeBtn; // 0x40
	private Transform _itemIconRoot; // 0x48
	private Text _prgText; // 0x50
	private Slider _prg; // 0x58
	private GameObject _btn; // 0x60
	private GameObject _gotFlag; // 0x68
	private UIChildrenColorGraphic _colorChanger; // 0x70
	private MissionData m_mission; // 0x78
	private UIItemCard[] m_rewardIcon; // 0x80
	private Act5D1RuneMissionPanel m_owner; // 0x88
	private String[] m_runes; // 0x90
	private Boolean m_cannotFlag; // 0x98
	private Boolean m_hasGot; // 0x99
	private static DelegateBridge __Hotfix0_SynMission; // 0x0
	private static DelegateBridge __Hotfix0_GetMissionStatus; // 0x8
	private static DelegateBridge __Hotfix0_HandleGetReward; // 0x10
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_ShowRuneDetail; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31d1d04 VA: 0x75957e9d04
	public Void SynMission(MissionData mission, Act5D1RuneMissionPanel owner) { }
	// RVA: 0x31d27c8 VA: 0x75957ea7c8
	public static MissionHoldingState GetMissionStatus(String missionId, out Int32 v, out Int32 t) { }
	// RVA: 0x31d29b8 VA: 0x75957ea9b8
	public Void HandleGetReward() { }
	// RVA: 0x31d2be4 VA: 0x75957eabe4
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x31d2ccc VA: 0x75957eaccc
	public Void ShowRuneDetail() { }
	// RVA: 0x31d30bc VA: 0x75957eb0bc
	private Void OnEnable() { }
	// RVA: 0x31d3194 VA: 0x75957eb194
	public Void .ctor() { }
	// RVA: 0x31d3240 VA: 0x75957eb240
	private Void <HandleGetReward>b__20_0(ActivityConfirmMissionResponse response) { }
}
```