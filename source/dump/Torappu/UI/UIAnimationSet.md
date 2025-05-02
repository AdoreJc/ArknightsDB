# UIAnimationSet

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_isPlaying`

- `Action m_onEnd`


## Methods

- `Boolean PlayAll(Action)`

- `Void MoveToEnd()`

- `Void _OnAllAnimEnd()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAnimationSet : IHotfixable
{
	private UIAnimation[] m_parallels; // 0x10
	private Boolean m_isPlaying; // 0x18
	private Action m_onEnd; // 0x20
	private static DelegateBridge __Hotfix0_PlayAll; // 0x0
	private static DelegateBridge __Hotfix0_MoveToEnd; // 0x8
	private static DelegateBridge __Hotfix0__OnAllAnimEnd; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x21760e0 VA: 0x759478e0e0
	public Boolean PlayAll(Action endcallback) { }
	// RVA: 0x2175ee8 VA: 0x759478dee8
	public Void MoveToEnd() { }
	// RVA: 0x21762f0 VA: 0x759478e2f0
	private Void _OnAllAnimEnd() { }
	// RVA: 0x21763e8 VA: 0x759478e3e8
	public Void .ctor() { }
}
```