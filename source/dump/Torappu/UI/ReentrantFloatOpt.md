# ReentrantFloatOpt

**Namespace:** `Torappu.UI`


## Fields

- `Builder m_builder`

- `Int32 m_showCnt`

- `Int32 m_effectCnt`


## Properties

- `Boolean isShown`


## Methods

- `IEnumerator ShowCoroutine()`

- `IEnumerator HideCoroutine()`

- `IEnumerator _WaitForEffectsFinish()`

- `Boolean _CheckIfEffectStable()`

- `Boolean get_isShown()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ReentrantFloatOpt : IHotfixable
{
	private Builder m_builder; // 0x10
	private Int32 m_showCnt; // 0x30
	private Int32 m_effectCnt; // 0x34
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__WaitForEffectsFinish; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfEffectStable; // 0x20
	private static DelegateBridge __Hotfix0_get_isShown; // 0x28

	public Boolean isShown { get; }

	// RVA: 0x21e4d58 VA: 0x75947fcd58
	private Void .ctor(Builder builder) { }
	// RVA: 0x21e4df4 VA: 0x75947fcdf4
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x21e4ec8 VA: 0x75947fcec8
	public IEnumerator HideCoroutine() { }
	// RVA: 0x21e4f9c VA: 0x75947fcf9c
	private IEnumerator _WaitForEffectsFinish() { }
	// RVA: 0x21e5070 VA: 0x75947fd070
	private Boolean _CheckIfEffectStable() { }
	// RVA: 0x21e50e0 VA: 0x75947fd0e0
	public Boolean get_isShown() { }
}
```