# StoryProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnStoryItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class StoryProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_InitComp; // 0x8
	private static DelegateBridge __Hotfix0__OnStoryItemClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override String compType { get; }

	// RVA: 0x300e23c VA: 0x759562623c
	protected override String get_compType() { }
	// RVA: 0x300e2b8 VA: 0x75956262b8
	protected override Void InitComp() { }
	// RVA: 0x300e570 VA: 0x7595626570
	private Void _OnStoryItemClicked(ActArchiveType type, String storyId) { }
	// RVA: 0x300e688 VA: 0x7595626688
	public Void .ctor() { }
}
```