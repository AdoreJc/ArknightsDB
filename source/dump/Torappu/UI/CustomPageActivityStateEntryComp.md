# CustomPageActivityStateEntryComp

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_isAnimPlaying`

- `Int32 m_runningAnimCount`

- `State m_parentState`

- `UIPageFinder m_pageFinder`


## Properties

- `State parentState`

- `EntryCompStatus curStatus`


## Methods

- `State get_parentState()`

- `EntryCompStatus get_curStatus()`

- `Void OnRender(Boolean)`

- `Void _SampleAllAnimClipAtBegin()`

- `Void _PlayWithAnim(Boolean)`

- `IEnumerator _PlayTargetAnim(Boolean, EntryAnim)`

- `Void _CheckAllFinish()`

- `Void _DescreasePlayingCount()`

- `Void <_PlayTargetAnim>b__15_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CustomPageActivityStateEntryComp : MonoBehaviour
{
	private List`1 _animList; // 0x18
	private List`1 _onAnimEndList; // 0x20
	private Boolean m_isAnimPlaying; // 0x28
	private Int32 m_runningAnimCount; // 0x2c
	private State m_parentState; // 0x30
	private UIPageFinder m_pageFinder; // 0x38

	private State parentState { get; }
	public EntryCompStatus curStatus { get; }

	// RVA: 0x226b568 VA: 0x7594883568
	private State get_parentState() { }
	// RVA: 0x226b610 VA: 0x7594883610
	public EntryCompStatus get_curStatus() { }
	// RVA: 0x226b624 VA: 0x7594883624
	public Void OnRender(Boolean skipAnim) { }
	// RVA: 0x226b6c4 VA: 0x75948836c4
	private Void _SampleAllAnimClipAtBegin() { }
	// RVA: 0x226b79c VA: 0x759488379c
	private Void _PlayWithAnim(Boolean isSkip) { }
	// RVA: 0x226b9ec VA: 0x75948839ec
	private IEnumerator _PlayTargetAnim(Boolean isSkip, EntryAnim anim) { }
	// RVA: 0x226b938 VA: 0x7594883938
	private Void _CheckAllFinish() { }
	// RVA: 0x226bab0 VA: 0x7594883ab0
	private Void _DescreasePlayingCount() { }
	// RVA: 0x226bac0 VA: 0x7594883ac0
	public Void .ctor() { }
	// RVA: 0x226bac8 VA: 0x7594883ac8
	private Void <_PlayTargetAnim>b__15_0() { }
}
```