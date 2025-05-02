# RoguelikeTopicChallengeEndingTaskView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Slider _progressSlider`

- `Text _taskDescText`

- `GameObject _incompletePanel`

- `GameObject _completePanel`


## Methods

- `Void Render(String, Single, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeEndingTaskView : MonoBehaviour, IHotfixable
{
	private Slider _progressSlider; // 0x18
	private Text _taskDescText; // 0x20
	private GameObject _incompletePanel; // 0x28
	private GameObject _completePanel; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x26466c0 VA: 0x7594c5e6c0
	public Void Render(String taskDesc, Single progress, Boolean complete) { }
	// RVA: 0x2646ce0 VA: 0x7594c5ece0
	public Void .ctor() { }
}
```