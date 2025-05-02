# RoguelikeCommonOuterBuffSummaryRawTextView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `RawTextAdapter m_adapter`


## Methods

- `Void Render(String, List`1, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffSummaryRawTextView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Boolean m_isInited; // 0x20
	private RawTextAdapter m_adapter; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26651c8 VA: 0x7594c7d1c8
	public Void Render(String topicId, List`1 viewModels, Boolean firstLineHasBack) { }
	// RVA: 0x26652a8 VA: 0x7594c7d2a8
	private Void _InitIfNot() { }
	// RVA: 0x2665434 VA: 0x7594c7d434
	public Void .ctor() { }
}
```