# Act42D0EffectSelectGroupView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `UIPageFinder m_pageFinder`

- `Int32 m_cachedSequenceNum`


## Methods

- `Void Render(Act42D0EffectGroupViewModel, Int32)`

- `Void _InitIfNot()`

- `Void OnClearEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectSelectGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Boolean m_isInited; // 0x20
	private Adapter m_adapter; // 0x28
	private List`1 m_cachedViewModels; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private Int32 m_cachedSequenceNum; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClearEffect; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x320ebd0 VA: 0x7595826bd0
	public Void Render(Act42D0EffectGroupViewModel viewModel, Int32 sequenceNum) { }
	// RVA: 0x320ec94 VA: 0x7595826c94
	private Void _InitIfNot() { }
	// RVA: 0x320ee48 VA: 0x7595826e48
	public Void OnClearEffect() { }
	// RVA: 0x320ef08 VA: 0x7595826f08
	public Void .ctor() { }
}
```