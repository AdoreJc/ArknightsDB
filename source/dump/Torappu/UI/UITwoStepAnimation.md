# UITwoStepAnimation

**Namespace:** `Torappu.UI`


## Methods

- `Void PlayLoopAnim(PlayOptions)`

- `Void PlayEnterAnim(PlayOptions, Action)`

- `Void PrepareEnterAnim()`

- `Void _SampleAnimsAtEnd(IList`1, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UITwoStepAnimation : IHotfixable
{
	private IList`1 m_enterList; // 0x10
	private IList`1 m_loopList; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_PlayLoopAnim; // 0x8
	private static DelegateBridge __Hotfix0_PlayEnterAnim; // 0x10
	private static DelegateBridge __Hotfix0_PrepareEnterAnim; // 0x18
	private static DelegateBridge __Hotfix0__SampleAnimsAtEnd; // 0x20


	// RVA: 0x2176458 VA: 0x759478e458
	public Void .ctor(IList`1 enterList, IList`1 loopList) { }
	// RVA: 0x2176504 VA: 0x759478e504
	public Void PlayLoopAnim(PlayOptions options) { }
	// RVA: 0x217682c VA: 0x759478e82c
	public Void PlayEnterAnim(PlayOptions options, Action completeCallback) { }
	// RVA: 0x2176d0c VA: 0x759478ed0c
	public Void PrepareEnterAnim() { }
	// RVA: 0x2176b90 VA: 0x759478eb90
	private Void _SampleAnimsAtEnd(IList`1 anims, Boolean isReversed) { }
}
```