# UniEquipUnlockMissionItemView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `GameObject _progressMissionTitle`

- `GameObject _accomplishedMissionTitle`

- `GameObject _panelStageBtn`

- `GameObject _panelStageUnlock`

- `GameObject _panelStageLocked`

- `Text _missionDescText`

- `Color _missionNormalColor`

- `Color _accomplishedColor`

- `StageData m_missionStageData`

- `Boolean m_stageUnlock`


## Methods

- `Void Render(UniEquipMissionData)`

- `Void OnMissionClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipUnlockMissionItemView : MonoBehaviour, IHotfixable
{
	private const String PROGRESS_COLOR; // 0x0
	private GameObject _progressMissionTitle; // 0x18
	private GameObject _accomplishedMissionTitle; // 0x20
	private GameObject _panelStageBtn; // 0x28
	private GameObject _panelStageUnlock; // 0x30
	private GameObject _panelStageLocked; // 0x38
	private Text _missionDescText; // 0x40
	private Color _missionNormalColor; // 0x48
	private Color _accomplishedColor; // 0x58
	private StageData m_missionStageData; // 0x68
	private Boolean m_stageUnlock; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnMissionClick; // 0x8
	private static DelegateBridge __Hotfix0__GetDescText; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x230f65c VA: 0x759492765c
	public Void Render(UniEquipMissionData missionData) { }
	// RVA: 0x230f9cc VA: 0x75949279cc
	public Void OnMissionClick() { }
	// RVA: 0x230f898 VA: 0x7594927898
	private static String _GetDescText(String missionDesc, PlayerEquipMission equipMission, Boolean isAccomplished) { }
	// RVA: 0x230fae0 VA: 0x7594927ae0
	public Void .ctor() { }
}
```