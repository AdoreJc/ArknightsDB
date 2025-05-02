# ArchiveBuffItemAdapter

**Namespace:** ` `


## Fields

- `ArchiveBuffListGroupView m_closure`

- `ArchiveBuffGroupModel viewModel`

- `String selectedBuffId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ArchiveBuffItemAdapter : SimpleLayoutAdapter
{
	private ArchiveBuffListGroupView m_closure; // 0x20
	public ArchiveBuffGroupModel viewModel; // 0x28
	public String selectedBuffId; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x3038b28 VA: 0x7595650b28
	public Void .ctor(ArchiveBuffListGroupView closure) { }
	// RVA: 0x3038c34 VA: 0x7595650c34
	public override Int32 get_count() { }
	// RVA: 0x3038ccc VA: 0x7595650ccc
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```