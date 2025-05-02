# ScrollEffectTrigger

**Namespace:** ` `


## Fields

- `Boolean m_isValid`

- `ScrollEffectConfig m_config`

- `Int32 m_lastFocusIndex`

- `Single m_curTime`

- `Single m_lastScrollTime`

- `Boolean m_hasScrolled`


## Methods

- `Void NotifyScrolling(Single, Single)`

- `Void MarkHasScrolled()`

- `Void NotifyAlignFinish()`

- `Void Reset(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ScrollEffectTrigger : IHotfixable
{
	private const Single DFT_MIN_INTERVAL; // 0x0
	private Boolean m_isValid; // 0x10
	private ScrollEffectConfig m_config; // 0x18
	private Int32 m_lastFocusIndex; // 0x30
	private Single m_curTime; // 0x34
	private Single m_lastScrollTime; // 0x38
	private Boolean m_hasScrolled; // 0x3c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_NotifyScrolling; // 0x8
	private static DelegateBridge __Hotfix0_MarkHasScrolled; // 0x10
	private static DelegateBridge __Hotfix0_NotifyAlignFinish; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20


	// RVA: 0x2201ce8 VA: 0x7594819ce8
	public Void .ctor(ScrollEffectConfig config) { }
	// RVA: 0x2201de8 VA: 0x7594819de8
	public Void NotifyScrolling(Single curIndex, Single deltaTime) { }
	// RVA: 0x2202038 VA: 0x759481a038
	public Void MarkHasScrolled() { }
	// RVA: 0x22020ac VA: 0x759481a0ac
	public Void NotifyAlignFinish() { }
	// RVA: 0x2202140 VA: 0x759481a140
	public Void Reset(Int32 curIndex) { }
}
```