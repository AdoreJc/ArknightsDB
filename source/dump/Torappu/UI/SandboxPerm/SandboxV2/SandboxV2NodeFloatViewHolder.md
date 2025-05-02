# SandboxV2NodeFloatViewHolder

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2NodeFloatView _floatViewPrefab`

- `UIPageFinder m_pageFinder`

- `SandboxV2DungeonViewModel m_cachedDungeonViewModel`


## Methods

- `Void Render(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`

- `Void OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodeFloatViewHolder : MonoBehaviour, ISandboxV2OrderedView, IHotfixable
{
	private const UInt32 PER_OBJ_COST; // 0x0
	private SandboxV2NodeFloatView _floatViewPrefab; // 0x18
	private UIPageFinder m_pageFinder; // 0x20
	private AsyncDataViewHandler`2 m_viewHandler; // 0x30
	private SandboxV2DungeonViewModel m_cachedDungeonViewModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2563fc4 VA: 0x7594b7bfc4
	public Void Render(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x256422c VA: 0x7594b7c22c
	public Void OnRecycle() { }
	// RVA: 0x25642f4 VA: 0x7594b7c2f4
	public Void .ctor() { }
}
```