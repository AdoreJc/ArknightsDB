# BuildingFloatTrainingView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `GameObject _empty`

- `GameObject _onTraining`

- `Image _skillSprite`

- `Image _startIcon`

- `Image _targetIcon`

- `FillProgressBar _stateProgress`

- `Text _stateText`

- `Text _nameText`

- `Text _remainTimeText`

- `GameObject _finishPart`

- `CountDownTask m_trainingCountDown`

- `LevelUpSnapshot m_trainSnapshot`


## Methods

- `Void Update()`

- `Void _UpdateTrainingStatusWhenTraining()`

- `Void _RenderCountDownValue()`

- `Void InitData()`

- `Void <_UpdateTrainingStatusWhenTraining>b__14_0(TickValue)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatTrainingView : MonoBehaviour
{
	private GameObject _empty; // 0x18
	private GameObject _onTraining; // 0x20
	private Image _skillSprite; // 0x28
	private Image _startIcon; // 0x30
	private Image _targetIcon; // 0x38
	private FillProgressBar _stateProgress; // 0x40
	private Text _stateText; // 0x48
	private Text _nameText; // 0x50
	private Text _remainTimeText; // 0x58
	private GameObject _finishPart; // 0x60
	private CountDownTask m_trainingCountDown; // 0x68
	private LevelUpSnapshot m_trainSnapshot; // 0x70
	private const String NAME_FORMAT; // 0x0


	// RVA: 0x3e2f374 VA: 0x7596447374
	private Void Update() { }
	// RVA: 0x3e2f388 VA: 0x7596447388
	private Void _UpdateTrainingStatusWhenTraining() { }
	// RVA: 0x3e2f6e8 VA: 0x75964476e8
	private Void _RenderCountDownValue() { }
	// RVA: 0x3e2493c VA: 0x759643c93c
	public Void InitData() { }
	// RVA: 0x3e2f948 VA: 0x7596447948
	public Void .ctor() { }
	// RVA: 0x3e2f9b8 VA: 0x75964479b8
	private Void <_UpdateTrainingStatusWhenTraining>b__14_0(TickValue _) { }
}
```