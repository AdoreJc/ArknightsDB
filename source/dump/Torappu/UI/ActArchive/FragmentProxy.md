# FragmentProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnItemClicked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class FragmentProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x3012c50 VA: 0x759562ac50
	protected override String get_compType() { }
	// RVA: 0x3012ccc VA: 0x759562accc
	protected override String GetPrefabPath() { }
	// RVA: 0x3012d54 VA: 0x759562ad54
	protected override Void InitComp() { }
	// RVA: 0x3012f98 VA: 0x759562af98
	private Void _OnItemClicked(String id) { }
	// RVA: 0x301308c VA: 0x759562b08c
	public Void .ctor() { }
}
```