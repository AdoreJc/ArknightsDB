# Act1LockAVGAdapter

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Act1LockMapPage m_cachedPage`


## Methods

- `Boolean _ExecuteEnsureMapStatus(Command)`

- `Void InitAvgAdapter(Act1LockMapPage)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockAVGAdapter : ExecutorComponent
{
	private Act1LockMapPage m_cachedPage; // 0x50
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x8
	private static DelegateBridge __Hotfix0__ExecuteEnsureMapStatus; // 0x10
	private static DelegateBridge __Hotfix0_InitAvgAdapter; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x339a058 VA: 0x75959b2058
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x339a1f8 VA: 0x75959b21f8
	protected override Void ForceCommandEnd() { }
	// RVA: 0x339a25c VA: 0x75959b225c
	private Boolean _ExecuteEnsureMapStatus(Command command) { }
	// RVA: 0x339a4c4 VA: 0x75959b24c4
	public Void InitAvgAdapter(Act1LockMapPage mapPage) { }
	// RVA: 0x339a5a8 VA: 0x75959b25a8
	private Void OnDestroy() { }
	// RVA: 0x339a664 VA: 0x75959b2664
	public Void .ctor() { }
}
```