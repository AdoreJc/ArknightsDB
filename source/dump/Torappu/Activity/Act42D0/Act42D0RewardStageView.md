# Act42D0RewardStageView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `Int32 m_maxCount`

- `Adapter m_adapter`


## Methods

- `Void Render(ListDict`2, Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0RewardStageView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Boolean m_isInited; // 0x20
	private ListDict`2 m_cachedViewModels; // 0x28
	private Int32 m_maxCount; // 0x30
	private Adapter m_adapter; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x321f4ec VA: 0x75958374ec
	public Void Render(ListDict`2 stages, Int32 maxCount) { }
	// RVA: 0x321f59c VA: 0x759583759c
	private Void _InitIfNot() { }
	// RVA: 0x321f750 VA: 0x7595837750
	public Void .ctor() { }
}
```