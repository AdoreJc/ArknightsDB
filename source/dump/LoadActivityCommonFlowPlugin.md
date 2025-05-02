# LoadActivityCommonFlowPlugin

**Namespace:** ` `


## Fields

- `StageActivityLoader closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LoadActivityCommonFlowPlugin : IHotfixable
{
	protected StageActivityLoader closure; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OverrideBeforeTransition; // 0x8
	private static DelegateBridge __Hotfix0_OverrideAfterTransition; // 0x10


	// RVA: 0x2f84ef8 VA: 0x759559cef8
	public Void .ctor(StageActivityLoader closure) { }
	// RVA: 0x2f85c24 VA: 0x759559dc24
	public virtual IEnumerator OverrideBeforeTransition() { }
	// RVA: 0x2f85c88 VA: 0x759559dc88
	public virtual Void OverrideAfterTransition() { }
}
```