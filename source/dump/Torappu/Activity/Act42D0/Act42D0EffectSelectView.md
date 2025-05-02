# Act42D0EffectSelectView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `ScrollRect _scrollRect`

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `Int32 m_cachedSequenceNum`


## Methods

- `Void Render(Act42D0EffectViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectSelectView : MonoBehaviour, IHotfixable
{
	private ScrollRect _scrollRect; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private Boolean m_isInited; // 0x28
	private Adapter m_adapter; // 0x30
	private ListDict`2 m_cachedViewModels; // 0x38
	private Int32 m_cachedSequenceNum; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x320ff3c VA: 0x7595827f3c
	public Void Render(Act42D0EffectViewModel viewModel) { }
	// RVA: 0x3210030 VA: 0x7595828030
	private Void _InitIfNot() { }
	// RVA: 0x32101e4 VA: 0x75958281e4
	public Void .ctor() { }
}
```