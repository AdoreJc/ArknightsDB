# Rl03OuterBuffSummaryRawTextView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


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
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffSummaryRawTextView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Boolean m_isInited; // 0x20
	private RawTextAdapter m_adapter; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26ae5f4 VA: 0x7594cc65f4
	public Void Render(String topicId, List`1 viewModels, Boolean firstLineHasBack) { }
	// RVA: 0x26ae6d4 VA: 0x7594cc66d4
	private Void _InitIfNot() { }
	// RVA: 0x26ae860 VA: 0x7594cc6860
	public Void .ctor() { }
}
```