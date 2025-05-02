# DynamicStoryProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnStoryItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class DynamicStoryProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnStoryItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x300e718 VA: 0x7595626718
	protected override String get_compType() { }
	// RVA: 0x300e794 VA: 0x7595626794
	protected override String GetPrefabPath() { }
	// RVA: 0x300e81c VA: 0x759562681c
	protected override Void InitComp() { }
	// RVA: 0x300ead4 VA: 0x7595626ad4
	private Void _OnStoryItemClicked(ActArchiveType type, String storyId) { }
	// RVA: 0x300ebf4 VA: 0x7595626bf4
	public Void .ctor() { }
}
```