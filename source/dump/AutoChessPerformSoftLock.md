# AutoChessPerformSoftLock

**Namespace:** ` `


## Fields

- `Boolean m_internalLock`

- `Boolean m_inited`


## Methods

- `IEnumerator LockForTrans()`

- `Single GetSoftLockTime()`

- `Void _OnTransFinish(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessPerformSoftLock : IHotfixable
{
	private Boolean m_internalLock; // 0x10
	private Boolean m_inited; // 0x11
	private const Single MAX_WAIT_TIME_LONG; // 0x0
	private const Single MAX_WAIT_TIME_MID; // 0x0
	private static DelegateBridge __Hotfix0_LockForTrans; // 0x0
	private static DelegateBridge __Hotfix0_GetSoftLockTime; // 0x8
	private static DelegateBridge __Hotfix0__OnTransFinish; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1cab6c8 VA: 0x75942c36c8
	public IEnumerator LockForTrans() { }
	// RVA: 0x1cab79c VA: 0x75942c379c
	private Single GetSoftLockTime() { }
	// RVA: 0x1cab840 VA: 0x75942c3840
	private Void _OnTransFinish(Object arg) { }
	// RVA: 0x1cab658 VA: 0x75942c3658
	public Void .ctor() { }
}
```