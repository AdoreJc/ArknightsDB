# MatAdapter

**Namespace:** ` `


## Fields

- `SandboxV2WorkbenchMakeDialog m_closure`


## Methods

- `Void _ItemClickEvent(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MatAdapter : SimpleLayoutAdapter
{
	private SandboxV2WorkbenchMakeDialog m_closure; // 0x20
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0__ItemClickEvent; // 0x18

	public override Int32 count { get; }

	// RVA: 0x24f5750 VA: 0x7594b0d750
	public override Int32 get_count() { }
	// RVA: 0x24f15a0 VA: 0x7594b095a0
	public Void .ctor(SandboxV2WorkbenchMakeDialog closure) { }
	// RVA: 0x24f5830 VA: 0x7594b0d830
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x24f5b1c VA: 0x7594b0db1c
	private Void _ItemClickEvent(Int32 position) { }
}
```