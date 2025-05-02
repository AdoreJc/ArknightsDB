# FireworkCraftAvgAdapter

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `FireworkCraftState _state`

- `UIPageFinder m_pageFinder`

- `Coroutine m_coroutine`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Boolean _ExecuteWaitForCraftPageStable(Command)`

- `IEnumerator _CoroutineWaitForCraftPageStable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftAvgAdapter : ExecutorComponent
{
	private FireworkCraftState _state; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private Coroutine m_coroutine; // 0x68
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteWaitForCraftPageStable; // 0x20
	private static DelegateBridge __Hotfix0__CoroutineWaitForCraftPageStable; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2903258 VA: 0x7594f1b258
	protected override Void ForceCommandEnd() { }
	// RVA: 0x29032bc VA: 0x7594f1b2bc
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x290345c VA: 0x7594f1b45c
	private Void Start() { }
	// RVA: 0x2903518 VA: 0x7594f1b518
	private Void OnDestroy() { }
	// RVA: 0x2903624 VA: 0x7594f1b624
	private Boolean _ExecuteWaitForCraftPageStable(Command command) { }
	// RVA: 0x29036ec VA: 0x7594f1b6ec
	private IEnumerator _CoroutineWaitForCraftPageStable() { }
	// RVA: 0x29037c0 VA: 0x7594f1b7c0
	public Void .ctor() { }
}
```