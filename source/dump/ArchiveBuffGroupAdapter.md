# ArchiveBuffGroupAdapter

**Namespace:** ` `


## Fields

- `ArchiveBuffListDataBinder m_closure`

- `ArchiveBuffModel viewModel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ArchiveBuffGroupAdapter : SimpleLayoutAdapter
{
	private ArchiveBuffListDataBinder m_closure; // 0x20
	public ArchiveBuffModel viewModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x3038378 VA: 0x7595650378
	public Void .ctor(ArchiveBuffListDataBinder closure) { }
	// RVA: 0x303849c VA: 0x759565049c
	public override Int32 get_count() { }
	// RVA: 0x3038534 VA: 0x7595650534
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```