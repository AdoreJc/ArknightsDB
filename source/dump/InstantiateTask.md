# InstantiateTask

**Namespace:** ` `


## Fields

- `GameObject m_inst`

- `Handler m_handler`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class InstantiateTask : AsyncTaskBase
{
	private GameObject m_inst; // 0x20
	private Handler m_handler; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_WorkOnce; // 0x8
	private static DelegateBridge __Hotfix0_OnDisposed; // 0x10


	// RVA: 0x372af80 VA: 0x7595d42f80
	public Void .ctor(Handler handler) { }
	// RVA: 0x372b08c VA: 0x7595d4308c
	public override Boolean WorkOnce(out UInt32 cost) { }
	// RVA: 0x372b194 VA: 0x7595d43194
	protected override Void OnDisposed() { }
}
```