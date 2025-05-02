# UIAnimationSequence

**Namespace:** `Torappu.UI`


## Fields

- `Int32 m_animIndex`

- `Boolean m_isPlaying`

- `Action m_onEnd`


## Methods

- `Void MoveToEnd()`

- `Boolean StartSequence(Action)`

- `Void _IterateAnimList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAnimationSequence
{
	private UIAnimationSet[] m_sequence; // 0x10
	private Int32 m_animIndex; // 0x18
	private Boolean m_isPlaying; // 0x1c
	private Action m_onEnd; // 0x20


	// RVA: 0x2175e8c VA: 0x759478de8c
	public Void MoveToEnd() { }
	// RVA: 0x2175fa0 VA: 0x759478dfa0
	public Boolean StartSequence(Action endcallback) { }
	// RVA: 0x2175fe8 VA: 0x759478dfe8
	private Void _IterateAnimList() { }
	// RVA: 0x21762e8 VA: 0x759478e2e8
	public Void .ctor() { }
}
```