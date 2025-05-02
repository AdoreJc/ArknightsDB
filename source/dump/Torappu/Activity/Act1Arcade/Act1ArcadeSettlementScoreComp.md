# Act1ArcadeSettlementScoreComp

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Text _textScore`

- `Int32 m_scoreShow`

- `Tween m_tween`


## Methods

- `Void RenderAndPlay(Int32, Int32, Single, Single, String)`

- `IEnumerator _PlayAudio(String, Single)`

- `Int32 _TweenScoreGetter()`

- `Void _TweenScoreSetter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementScoreComp : MonoBehaviour, IHotfixable
{
	private Text _textScore; // 0x18
	private Int32 m_scoreShow; // 0x20
	private Tween m_tween; // 0x28
	private static DelegateBridge __Hotfix0_RenderAndPlay; // 0x0
	private static DelegateBridge __Hotfix0__PlayAudio; // 0x8
	private static DelegateBridge __Hotfix0__TweenScoreGetter; // 0x10
	private static DelegateBridge __Hotfix0__TweenScoreSetter; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x340706c VA: 0x7595a1f06c
	public Void RenderAndPlay(Int32 startNum, Int32 targetNum, Single duration, Single delay, String audioSignal) { }
	// RVA: 0x34073d0 VA: 0x7595a1f3d0
	private IEnumerator _PlayAudio(String audioSignal, Single delay) { }
	// RVA: 0x34074d0 VA: 0x7595a1f4d0
	private Int32 _TweenScoreGetter() { }
	// RVA: 0x34072cc VA: 0x7595a1f2cc
	private Void _TweenScoreSetter(Int32 newScore) { }
	// RVA: 0x3407538 VA: 0x7595a1f538
	public Void .ctor() { }
}
```