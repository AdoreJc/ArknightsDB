# SandboxLevelProgressHelper

**Namespace:** ` `


## Methods

- `Single GetCompleteProgress()`

- `Boolean _CheckIdInCount(String)`

- `FP _GetProgressByUnitId(Func`2)`

- `Boolean IsLevelUnlockConditionComplete()`

- `Boolean _IsUnitIdAllDead(Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxLevelProgressHelper : IHotfixable
{
	private ListDict`2 m_entityStatusCache; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetCompleteProgress; // 0x8
	private static DelegateBridge __Hotfix0__CheckIdInCount; // 0x10
	private static DelegateBridge __Hotfix0__GetProgressByUnitId; // 0x18
	private static DelegateBridge __Hotfix0_IsLevelUnlockConditionComplete; // 0x20
	private static DelegateBridge __Hotfix0__IsUnitIdAllDead; // 0x28


	// RVA: 0x1df2168 VA: 0x759440a168
	public Void .ctor() { }
	// RVA: 0x1df222c VA: 0x759440a22c
	public Single GetCompleteProgress() { }
	// RVA: 0x1df2cc8 VA: 0x759440acc8
	private Boolean _CheckIdInCount(String id) { }
	// RVA: 0x1df2440 VA: 0x759440a440
	private FP _GetProgressByUnitId(Func`2 isMatched) { }
	// RVA: 0x1df2e20 VA: 0x759440ae20
	public Boolean IsLevelUnlockConditionComplete() { }
	// RVA: 0x1df30b0 VA: 0x759440b0b0
	private Boolean _IsUnitIdAllDead(Func`2 isMatched) { }
}
```