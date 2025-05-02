# RoguelikeTopicEndingBpAndGpView

**Namespace:** `Torappu.UI.RoguelikeTopic.Ending`


## Fields

- `RectTransform _bpRoot`

- `RoguelikeTopicEndingBPStatusView _bpStatusPrefab`

- `RoguelikeTopicEndingGpView _gpView`

- `RoguelikeTopicEndingBPStatusView m_bpStatus`

- `Coroutine m_bpCoroutine`


## Methods

- `Void Flush(Model)`

- `IEnumerator _TweenBp(Model)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Ending
public class RoguelikeTopicEndingBpAndGpView : MonoBehaviour, IHotfixable
{
	private RectTransform _bpRoot; // 0x18
	private RoguelikeTopicEndingBPStatusView _bpStatusPrefab; // 0x20
	private RoguelikeTopicEndingGpView _gpView; // 0x28
	private RoguelikeTopicEndingBPStatusView m_bpStatus; // 0x30
	private Coroutine m_bpCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_Flush; // 0x0
	private static DelegateBridge __Hotfix0__TweenBp; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26da360 VA: 0x7594cf2360
	public Void Flush(Model model) { }
	// RVA: 0x26dacd4 VA: 0x7594cf2cd4
	private IEnumerator _TweenBp(Model model) { }
	// RVA: 0x26db11c VA: 0x7594cf311c
	public Void .ctor() { }
}
```