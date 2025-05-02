# UICooperateStageWaveStartPanel

**Namespace:** ` `


## Fields

- `Text _basicTaskInfo`

- `Text _advancedTaskInfo`

- `Text _taskName`

- `Text _stageCnt`

- `GameObject _advanceField`

- `Text _defenceMaxWave`

- `Text _defenceCurWave`

- `Text _defenceFirstMaxWave`

- `Text _defenceTarget`

- `Text _defenceFirstCurWave`

- `Text _defenceLastWaveInfo`

- `UIAnimationLocation _normalWaveStart`

- `UIAnimationLocation _normalTrainWaveStart`

- `UIAnimationLocation _footballWaveStart`

- `UIAnimationLocation _footballTrainWaveStart`

- `UIAnimationLocation _defenceWaveStart`

- `UIAnimationLocation _defenceTrainWaveStart`

- `UIAnimationLocation _defenceWaveNoraml`

- `UIAnimationLocation _defenceWaveLast`

- `FP m_passedTime`

- `Tween m_tween`

- `String m_stageId`

- `String m_actId`


## Methods

- `Void OnInit()`

- `Void OnFixedUpdate(FP)`

- `Void ShowStartPanel(Vector3)`

- `Void _SetTaskInfo(String, String, String, Int32)`

- `Void _SetWaveInfo(Int32, Int32)`

- `Void _SetFirstWaveInfo(Int32, Int32, CooperateGameMode)`

- `Void _SetLastWaveInfo()`

- `Void _SetTaskNormal(CooperateGameMode, UIAnimationLocation)`

- `BasicTaskInfo _GetWaveInfo(CooperateGameMode)`

- `String _GetTargetInfo()`

- `Void _HideAllPerform(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UICooperateStageWaveStartPanel : MonoBehaviour
{
	private Text _basicTaskInfo; // 0x18
	private Text _advancedTaskInfo; // 0x20
	private Text _taskName; // 0x28
	private Text _stageCnt; // 0x30
	private GameObject _advanceField; // 0x38
	private Text _defenceMaxWave; // 0x40
	private Text _defenceCurWave; // 0x48
	private Text _defenceFirstMaxWave; // 0x50
	private Text _defenceTarget; // 0x58
	private Text _defenceFirstCurWave; // 0x60
	private Text _defenceLastWaveInfo; // 0x68
	private UIAnimationLocation _normalWaveStart; // 0x70
	private UIAnimationLocation _normalTrainWaveStart; // 0x80
	private UIAnimationLocation _footballWaveStart; // 0x90
	private UIAnimationLocation _footballTrainWaveStart; // 0xa0
	private UIAnimationLocation _defenceWaveStart; // 0xb0
	private UIAnimationLocation _defenceTrainWaveStart; // 0xc0
	private UIAnimationLocation _defenceWaveNoraml; // 0xd0
	private UIAnimationLocation _defenceWaveLast; // 0xe0
	private FP m_passedTime; // 0xf0
	private Tween m_tween; // 0xf8
	private String m_stageId; // 0x100
	private String m_actId; // 0x108


	// RVA: 0x1b2a518 VA: 0x7594142518
	public Void OnInit() { }
	// RVA: 0x1b2a664 VA: 0x7594142664
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x1b2a700 VA: 0x7594142700
	public Void ShowStartPanel(Vector3 originLocalPosition) { }
	// RVA: 0x1b2ae1c VA: 0x7594142e1c
	private Void _SetTaskInfo(String basicInfo, String advancedInfo, String taskName, Int32 stage) { }
	// RVA: 0x1b2b08c VA: 0x759414308c
	private Void _SetWaveInfo(Int32 curWave, Int32 waveCnt) { }
	// RVA: 0x1b2af30 VA: 0x7594142f30
	private Void _SetFirstWaveInfo(Int32 curWave, Int32 waveCnt, CooperateGameMode gameMode) { }
	// RVA: 0x1b2b014 VA: 0x7594143014
	private Void _SetLastWaveInfo() { }
	// RVA: 0x1b2b148 VA: 0x7594143148
	private Void _SetTaskNormal(CooperateGameMode gameMode, UIAnimationLocation anim) { }
	// RVA: 0x1b2ac00 VA: 0x7594142c00
	private BasicTaskInfo _GetWaveInfo(CooperateGameMode gameMode) { }
	// RVA: 0x1b2b2f4 VA: 0x75941432f4
	private String _GetTargetInfo() { }
	// RVA: 0x1b2b408 VA: 0x7594143408
	private Void _HideAllPerform(Object arg) { }
	// RVA: 0x1b2b488 VA: 0x7594143488
	public Void .ctor() { }
}
```