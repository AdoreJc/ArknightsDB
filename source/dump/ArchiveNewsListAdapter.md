# ArchiveNewsListAdapter

**Namespace:** ` `


## Fields

- `ArchiveNewsListDataBinder m_closure`


## Methods

- `Void set_dataSet(ListDict`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ArchiveNewsListAdapter : SimpleLayoutAdapter, IHotfixable
{
	private ArchiveNewsListDataBinder m_closure; // 0x20
	private ListDict`2 <dataSet>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20

	public ListDict`2 dataSet { get; set; }
	public override Int32 count { get; }

	// RVA: 0x3065380 VA: 0x759567d380
	public ListDict`2 get_dataSet() { }
	// RVA: 0x30648d4 VA: 0x759567c8d4
	public Void set_dataSet(ListDict`2 value) { }
	// RVA: 0x30653e8 VA: 0x759567d3e8
	public override Int32 get_count() { }
	// RVA: 0x3064cf4 VA: 0x759567ccf4
	public Void .ctor(ArchiveNewsListDataBinder closure) { }
	// RVA: 0x306546c VA: 0x759567d46c
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```