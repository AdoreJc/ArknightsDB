# ItemListAdapter

**Namespace:** ` `


## Fields

- `ArchiveLogDataBinder m_closure`


## Methods

- `Void set_dataSet(ListDict`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ItemListAdapter : SimpleLayoutAdapter, IHotfixable
{
	private ArchiveLogDataBinder m_closure; // 0x20
	private ListDict`2 <dataSet>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20

	public ListDict`2 dataSet { get; set; }
	public override Int32 count { get; }

	// RVA: 0x3059a7c VA: 0x7595671a7c
	public ListDict`2 get_dataSet() { }
	// RVA: 0x3059880 VA: 0x7595671880
	public Void set_dataSet(ListDict`2 value) { }
	// RVA: 0x3059ae4 VA: 0x7595671ae4
	public override Int32 get_count() { }
	// RVA: 0x3059904 VA: 0x7595671904
	public Void .ctor(ArchiveLogDataBinder closure) { }
	// RVA: 0x3059b68 VA: 0x7595671b68
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```