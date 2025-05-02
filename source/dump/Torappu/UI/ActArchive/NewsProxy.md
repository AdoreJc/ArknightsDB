# NewsProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnNewsItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class NewsProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_InitComp; // 0x8
	private static DelegateBridge __Hotfix0__OnNewsItemClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override String compType { get; }

	// RVA: 0x300ec84 VA: 0x7595626c84
	protected override String get_compType() { }
	// RVA: 0x300ed00 VA: 0x7595626d00
	protected override Void InitComp() { }
	// RVA: 0x300efb8 VA: 0x7595626fb8
	private Void _OnNewsItemClicked(ActArchiveType type, String newsId) { }
	// RVA: 0x300f0d0 VA: 0x75956270d0
	public Void .ctor() { }
}
```