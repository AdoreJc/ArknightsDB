# LandmarkProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnLandmarkItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class LandmarkProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnLandmarkItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x3008e10 VA: 0x7595620e10
	protected override String get_compType() { }
	// RVA: 0x3008e8c VA: 0x7595620e8c
	protected override String GetPrefabPath() { }
	// RVA: 0x3008f14 VA: 0x7595620f14
	protected override Void InitComp() { }
	// RVA: 0x30091cc VA: 0x75956211cc
	private Void _OnLandmarkItemClicked(ActArchiveType type, String landmarkID) { }
	// RVA: 0x30092e4 VA: 0x75956212e4
	public Void .ctor() { }
}
```