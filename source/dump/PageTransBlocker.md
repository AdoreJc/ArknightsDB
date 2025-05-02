# PageTransBlocker

**Namespace:** ` `


## Fields

- `RefCountReference m_ref1`

- `UIBlockHandler m_blocker1`

- `RefCountReference m_ref2`

- `UIBlockHandler m_blocker2`


## Methods

- `Void BlockPages(UIPage, UIPage)`

- `Void ReleaseBlocks()`

- `Void _Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PageTransBlocker : IHotfixable
{
	private RefCountReference m_ref1; // 0x10
	private UIBlockHandler m_blocker1; // 0x18
	private RefCountReference m_ref2; // 0x20
	private UIBlockHandler m_blocker2; // 0x28
	private static DelegateBridge __Hotfix0_BlockPages; // 0x0
	private static DelegateBridge __Hotfix0_ReleaseBlocks; // 0x8
	private static DelegateBridge __Hotfix0__Reset; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x214a7a4 VA: 0x75947627a4
	public Void BlockPages(UIPage page1, UIPage page2) { }
	// RVA: 0x214aa48 VA: 0x7594762a48
	public Void ReleaseBlocks() { }
	// RVA: 0x214a910 VA: 0x7594762910
	private Void _Reset() { }
	// RVA: 0x214a518 VA: 0x7594762518
	public Void .ctor() { }
}
```