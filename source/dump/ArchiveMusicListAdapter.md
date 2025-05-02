# ArchiveMusicListAdapter

**Namespace:** ` `


## Fields

- `ArchiveMusicListDataBinder m_closure`


## Methods

- `Void set_dataSet(ListDict`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ArchiveMusicListAdapter : SimpleLayoutAdapter, IHotfixable
{
	private ArchiveMusicListDataBinder m_closure; // 0x20
	private ListDict`2 <dataSet>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20

	public ListDict`2 dataSet { get; set; }
	public override Int32 count { get; }

	// RVA: 0x3060768 VA: 0x7595678768
	public ListDict`2 get_dataSet() { }
	// RVA: 0x305e910 VA: 0x7595676910
	public Void set_dataSet(ListDict`2 value) { }
	// RVA: 0x30607d0 VA: 0x75956787d0
	public override Int32 get_count() { }
	// RVA: 0x305ecac VA: 0x7595676cac
	public Void .ctor(ArchiveMusicListDataBinder closure) { }
	// RVA: 0x3060854 VA: 0x7595678854
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```