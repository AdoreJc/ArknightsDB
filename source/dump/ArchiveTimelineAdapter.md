# ArchiveTimelineAdapter

**Namespace:** ` `


## Fields

- `ArchiveTimelineDataBinder m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ArchiveTimelineAdapter : SimpleLayoutAdapter, IHotfixable
{
	private ArchiveTimelineDataBinder m_closure; // 0x20
	public ListDict`2 timelineItemList; // 0x28
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x3085058 VA: 0x759569d058
	public override Int32 get_count() { }
	// RVA: 0x3084d54 VA: 0x759569cd54
	public Void .ctor(ArchiveTimelineDataBinder closure) { }
	// RVA: 0x30850d8 VA: 0x759569d0d8
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```