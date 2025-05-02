# ItemRepoItemCommonAdapter

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Single scale`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoItemCommonAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 itemList; // 0x20
	public Single scale; // 0x28
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2d354ec VA: 0x759534d4ec
	public override Int32 get_count() { }
	// RVA: 0x2d3556c VA: 0x759534d56c
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2d358e8 VA: 0x759534d8e8
	public Void .ctor() { }
}
```