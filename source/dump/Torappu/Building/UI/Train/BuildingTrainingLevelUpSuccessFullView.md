# BuildingTrainingLevelUpSuccessFullView

**Namespace:** `Torappu.Building.UI.Train`


## Fields

- `Transform _charaIllustContainer`

- `Image _skillIconImage`

- `Text _skillNameText`

- `Text _skillLevelupHintText`

- `Text _skillLevelupMiniHintText`

- `GameObject _levelRootPanel`

- `Single _phaseHiddenDuration`

- `Single _phaseMotionDuration`

- `Single _sfxPositionIntro`

- `Single _sfxPositionFlash`

- `String _miniHintPrefix`

- `GameObject _confirmButtonPanel`

- `Option m_opt`

- `Action m_onConfirm`

- `Coroutine m_motionCoroutine`


## Methods

- `Void Setup(Option)`

- `IEnumerator _MotionCoroutine()`

- `Void StopMotion()`

- `Void PlayMotion()`

- `Void HideLevelEffect()`

- `Void OnConfirmButtonClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Train
public class BuildingTrainingLevelUpSuccessFullView : MonoBehaviour
{
	private Transform _charaIllustContainer; // 0x18
	private Image _skillIconImage; // 0x20
	private Text _skillNameText; // 0x28
	private Text _skillLevelupHintText; // 0x30
	private Text _skillLevelupMiniHintText; // 0x38
	private GameObject[] _levelPanels; // 0x40
	private GameObject[] _baseLevelPanel; // 0x48
	private GameObject _levelRootPanel; // 0x50
	private Single _phaseHiddenDuration; // 0x58
	private Single _phaseMotionDuration; // 0x5c
	private Single _sfxPositionIntro; // 0x60
	private Single _sfxPositionFlash; // 0x64
	private String _miniHintPrefix; // 0x68
	private String[] _miniHintNumber; // 0x70
	private GameObject _confirmButtonPanel; // 0x78
	private Option m_opt; // 0x80
	private Action m_onConfirm; // 0x88
	private Coroutine m_motionCoroutine; // 0x90


	// RVA: 0x3d74e2c VA: 0x759638ce2c
	public Void Setup(Option option) { }
	// RVA: 0x3d7c2b0 VA: 0x75963942b0
	private IEnumerator _MotionCoroutine() { }
	// RVA: 0x3d7c34c VA: 0x759639434c
	public Void StopMotion() { }
	// RVA: 0x3d752ec VA: 0x759638d2ec
	public Void PlayMotion() { }
	// RVA: 0x3d74858 VA: 0x759638c858
	public Void HideLevelEffect() { }
	// RVA: 0x3d7c390 VA: 0x7596394390
	public Void OnConfirmButtonClick() { }
	// RVA: 0x3d7c3b4 VA: 0x75963943b4
	public Void .ctor() { }
}
```