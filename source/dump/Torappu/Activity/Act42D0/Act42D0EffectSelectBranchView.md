# Act42D0EffectSelectBranchView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Text _name`

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `Int32 m_cachedSequenceNum`


## Methods

- `Void Render(Act42D0EffectBranchViewModel, Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectSelectBranchView : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private Boolean m_isInited; // 0x28
	private Adapter m_adapter; // 0x30
	private ListDict`2 m_cachedViewModels; // 0x38
	private Int32 m_cachedSequenceNum; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x320e60c VA: 0x759582660c
	public Void Render(Act42D0EffectBranchViewModel viewModel, Int32 sequenceNum) { }
	// RVA: 0x320e6f8 VA: 0x75958266f8
	private Void _InitIfNot() { }
	// RVA: 0x320e8ac VA: 0x75958268ac
	public Void .ctor() { }
}
```