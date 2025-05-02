# ArchiveStoryListAdapter

**Namespace:** ` `


## Fields

- `ArchiveStoryListDataBinder m_closure`


## Methods

- `Void set_dataSet(ListDict`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ArchiveStoryListAdapter : SimpleLayoutAdapter, IHotfixable
{
	private ArchiveStoryListDataBinder m_closure; // 0x20
	private ListDict`2 <dataSet>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20

	public ListDict`2 dataSet { get; set; }
	public override Int32 count { get; }

	// RVA: 0x3080cc0 VA: 0x7595698cc0
	public ListDict`2 get_dataSet() { }
	// RVA: 0x3080224 VA: 0x7595698224
	public Void set_dataSet(ListDict`2 value) { }
	// RVA: 0x3080d28 VA: 0x7595698d28
	public override Int32 get_count() { }
	// RVA: 0x3080918 VA: 0x7595698918
	public Void .ctor(ArchiveStoryListDataBinder closure) { }
	// RVA: 0x3080dac VA: 0x7595698dac
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```