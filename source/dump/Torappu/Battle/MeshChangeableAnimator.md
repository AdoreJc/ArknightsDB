# MeshChangeableAnimator

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean activeObjInsteadEnableRender`


## Methods

- `Void EnableAllRenderers(Boolean)`

- `Void EnableRenderer(Int32, Boolean)`

- `Void EnableRendererByName(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MeshChangeableAnimator : MeshAnimator
{
	private Renderer[] _changeableRenders; // 0x168
	private Boolean activeObjInsteadEnableRender; // 0x170
	private static DelegateBridge __Hotfix0_EnableAllRenderers; // 0x0
	private static DelegateBridge __Hotfix0_EnableRenderer; // 0x8
	private static DelegateBridge __Hotfix0_EnableRendererByName; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f55ca4 VA: 0x759656dca4
	public Void EnableAllRenderers(Boolean enable) { }
	// RVA: 0x3f55ddc VA: 0x759656dddc
	public Void EnableRenderer(Int32 index, Boolean enable) { }
	// RVA: 0x3f55eec VA: 0x759656deec
	public Void EnableRendererByName(String name, Boolean enable) { }
	// RVA: 0x3f56034 VA: 0x759656e034
	public Void .ctor() { }
}
```