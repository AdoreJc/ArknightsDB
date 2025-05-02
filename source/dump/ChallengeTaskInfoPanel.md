# ChallengeTaskInfoPanel

**Namespace:** ` `


## Fields

- `GameObject _normalPanel`

- `GameObject _exploringPanel`

- `Text _currProgressText`

- `Text _totalProgressText`


## Methods

- `Void Render(RoguelikeTopicChallengeModel, RoguelikeTopicTaskInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ChallengeTaskInfoPanel : IHotfixable
{
	private const String TASK_TOTAL_PROGRESS_STYLE; // 0x0
	private GameObject _normalPanel; // 0x10
	private GameObject _exploringPanel; // 0x18
	private Text _currProgressText; // 0x20
	private Text _totalProgressText; // 0x28
	private Text[] _taskTexts; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x267df90 VA: 0x7594c95f90
	public Void Render(RoguelikeTopicChallengeModel challengeModel, RoguelikeTopicTaskInfo taskInfo) { }
	// RVA: 0x267e6bc VA: 0x7594c966bc
	public Void .ctor() { }
}
```