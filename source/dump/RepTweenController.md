# RepTweenController

**Namespace:** ` `


## Fields

- `Tween m_loopTween`

- `Boolean m_isInitSetEnableCall`

- `AnimationWrapper m_animWrapper`

- `String m_animKey`


## Methods

- `Void SetEnable(Boolean)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RepTweenController : IHotfixable, IDisposable
{
	private Tween m_loopTween; // 0x10
	private Boolean m_isInitSetEnableCall; // 0x18
	private AnimationWrapper m_animWrapper; // 0x20
	private String m_animKey; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetEnable; // 0x8
	private static DelegateBridge __Hotfix0_Dispose; // 0x10


	// RVA: 0x30a9e3c VA: 0x75956c1e3c
	public Void .ctor(AnimationWrapper repAnim, String animKey) { }
	// RVA: 0x30a9ef0 VA: 0x75956c1ef0
	public Void SetEnable(Boolean isEnable) { }
	// RVA: 0x30aa384 VA: 0x75956c2384
	public Void Dispose() { }
}
```