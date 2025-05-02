# CircleAdapter

**Namespace:** ` `


## Fields

- `ArchiveEndbookListDataBinder m_closure`

- `Int32 circleCount`

- `Int32 selectedIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CircleAdapter : SimpleLayoutAdapter
{
	private ArchiveEndbookListDataBinder m_closure; // 0x20
	public Int32 circleCount; // 0x28
	public Int32 selectedIndex; // 0x2c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x3050efc VA: 0x7595668efc
	public Void .ctor(ArchiveEndbookListDataBinder closure) { }
	// RVA: 0x30512fc VA: 0x75956692fc
	public override Int32 get_count() { }
	// RVA: 0x3051364 VA: 0x7595669364
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```