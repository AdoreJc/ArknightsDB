# ActivityEntryProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void BindEffectToPage(UICommonPageEffectHolder)`

- `Void BindCanvasToPage(Canvas)`

- `Void _onEntryItemClicked(ActArchiveType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ActivityEntryProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_BindEffectToPage; // 0x8
	private static DelegateBridge __Hotfix0_BindCanvasToPage; // 0x10
	private static DelegateBridge __Hotfix0_InitComp; // 0x18
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x20
	private static DelegateBridge __Hotfix0__onEntryItemClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override String compType { get; }

	// RVA: 0x300a230 VA: 0x7595622230
	protected override String get_compType() { }
	// RVA: 0x300a2ac VA: 0x75956222ac
	public Void BindEffectToPage(UICommonPageEffectHolder effectHolder) { }
	// RVA: 0x300a394 VA: 0x7595622394
	public Void BindCanvasToPage(Canvas canvas) { }
	// RVA: 0x300a430 VA: 0x7595622430
	protected override Void InitComp() { }
	// RVA: 0x300a6e8 VA: 0x75956226e8
	protected override String GetPrefabPath() { }
	// RVA: 0x300a770 VA: 0x7595622770
	private Void _onEntryItemClicked(ActArchiveType archiveItemType) { }
	// RVA: 0x300aa24 VA: 0x7595622a24
	public Void .ctor() { }
}
```