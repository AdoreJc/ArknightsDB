# StartMissionTaskStart

**Namespace:** `Torappu.UI.Mission`


## Fields

- `MissionProgressBar _progressState`

- `Text _missionCurValueLabel`

- `Text _missionTargetValueLabel`

- `GameObject _finished`

- `GameObject _unfinished`

- `GameObject _confirmed`

- `Button _hotSpot`

- `MissionRewardPreviewItem _rewardItem`

- `Single _maxProgressBarAndNumberLength`

- `Single _progressBarAndNumberPadding`

- `Single m_maxProgressBarLength`

- `Boolean m_maxLengthFetched`

- `MissionViewModel m_dataCache`


## Properties

- `String taskId`


## Methods

- `String get_taskId()`

- `Void ApplyMission()`

- `Void _FetchMaxLength()`

- `IEnumerator _UpdateProgressBarLengthCoroutine()`

- `Void _UpdateProgressBarLength()`

- `Void ApplyData(MissionViewModel, Transform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class StartMissionTaskStart : MonoBehaviour
{
	private MissionProgressBar _progressState; // 0x18
	private Text _missionCurValueLabel; // 0x20
	private Text _missionTargetValueLabel; // 0x28
	private GameObject _finished; // 0x30
	private GameObject _unfinished; // 0x38
	private GameObject _confirmed; // 0x40
	private Text[] _descriptiontexts; // 0x48
	private Text[] _rewardtexts; // 0x50
	private Button _hotSpot; // 0x58
	private MissionRewardPreviewItem _rewardItem; // 0x60
	private Single _maxProgressBarAndNumberLength; // 0x68
	private Single _progressBarAndNumberPadding; // 0x6c
	private Text[] _progressBarRightTexts; // 0x70
	private Single m_maxProgressBarLength; // 0x78
	private Boolean m_maxLengthFetched; // 0x7c
	private MissionViewModel m_dataCache; // 0x80

	public String taskId { get; }

	// RVA: 0x2745ac4 VA: 0x7594d5dac4
	public String get_taskId() { }
	// RVA: 0x27464e0 VA: 0x7594d5e4e0
	public Void ApplyMission() { }
	// RVA: 0x274650c VA: 0x7594d5e50c
	private Void _FetchMaxLength() { }
	// RVA: 0x2746578 VA: 0x7594d5e578
	private IEnumerator _UpdateProgressBarLengthCoroutine() { }
	// RVA: 0x2746614 VA: 0x7594d5e614
	private Void _UpdateProgressBarLength() { }
	// RVA: 0x2745728 VA: 0x7594d5d728
	public Void ApplyData(MissionViewModel missionData, Transform maskContainer) { }
	// RVA: 0x2746738 VA: 0x7594d5e738
	public Void .ctor() { }
}
```