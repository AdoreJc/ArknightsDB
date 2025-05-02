# SandboxV2TopBarMaterialAdapter

**Namespace:** ` `


## Fields

- `String topicId`


## Methods

- `Void set_dataSet(ListDict`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxV2TopBarMaterialAdapter : SimpleLayoutAdapter
{
	private ListDict`2 <dataSet>k__BackingField; // 0x20
	public String topicId; // 0x28
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge __Hotfix0_RenderView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public ListDict`2 dataSet { get; set; }
	public override Int32 count { get; }

	// RVA: 0x254e464 VA: 0x7594b66464
	public ListDict`2 get_dataSet() { }
	// RVA: 0x254d2cc VA: 0x7594b652cc
	public Void set_dataSet(ListDict`2 value) { }
	// RVA: 0x254e4cc VA: 0x7594b664cc
	public override Int32 get_count() { }
	// RVA: 0x254e550 VA: 0x7594b66550
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x254d77c VA: 0x7594b6577c
	public Void .ctor() { }
}
```