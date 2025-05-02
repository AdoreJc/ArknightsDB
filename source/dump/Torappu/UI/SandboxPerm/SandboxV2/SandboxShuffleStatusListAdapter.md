# SandboxShuffleStatusListAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2CharFilter charSelectFilter`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxShuffleStatusListAdapter : SimpleLayoutAdapter
{
	private List`1 CHAR_STATUS_ORDER_LIST; // 0x20
	public SandboxV2CharFilter charSelectFilter; // 0x28
	public Action`1 onStatusFilterClick; // 0x30
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x24852cc VA: 0x7594a9d2cc
	public override Int32 get_count() { }
	// RVA: 0x248534c VA: 0x7594a9d34c
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2484718 VA: 0x7594a9c718
	public Void .ctor() { }
}
```