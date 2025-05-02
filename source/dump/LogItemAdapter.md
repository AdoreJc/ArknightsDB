# LogItemAdapter

**Namespace:** ` `


## Fields

- `ArchiveLogDataBinder m_closure`


## Methods

- `Void set_dataSet(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LogItemAdapter : SimpleLayoutAdapter, IHotfixable
{
	private ArchiveLogDataBinder m_closure; // 0x20
	private List`1 <dataSet>k__BackingField; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x10
	private static DelegateBridge __Hotfix0_get_count; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20

	public List`1 dataSet { get; set; }
	public override Int32 count { get; }

	// RVA: 0x305add8 VA: 0x7595672dd8
	public Void .ctor(ArchiveLogDataBinder closure) { }
	// RVA: 0x305ae6c VA: 0x7595672e6c
	public List`1 get_dataSet() { }
	// RVA: 0x305aed4 VA: 0x7595672ed4
	public Void set_dataSet(List`1 value) { }
	// RVA: 0x305af58 VA: 0x7595672f58
	public override Int32 get_count() { }
	// RVA: 0x305afe4 VA: 0x7595672fe4
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```