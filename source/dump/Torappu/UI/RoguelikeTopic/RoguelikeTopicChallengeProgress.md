# RoguelikeTopicChallengeProgress

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Text _textCompleteProgress`

- `String m_colTargetCurProgress`


## Methods

- `Void InitStyle(String)`

- `Void Render(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeProgress : MonoBehaviour, IHotfixable
{
	private Text _textCompleteProgress; // 0x18
	private String m_colTargetCurProgress; // 0x20
	private readonly String COMPLETE_PROGRESS_STYLE; // 0x28
	private static DelegateBridge __Hotfix0_InitStyle; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x264a4dc VA: 0x7594c624dc
	public Void InitStyle(String curProgressColor) { }
	// RVA: 0x264ae90 VA: 0x7594c62e90
	public Void Render(Int32 completedTaskCount, Int32 totalTaskCount) { }
	// RVA: 0x264bf20 VA: 0x7594c63f20
	public Void .ctor() { }
}
```