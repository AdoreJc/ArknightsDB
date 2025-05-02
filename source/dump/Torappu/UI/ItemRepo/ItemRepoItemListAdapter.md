# ItemRepoItemListAdapter

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Single scale`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoItemListAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 viewModelList; // 0x20
	public Single scale; // 0x28
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2d35980 VA: 0x759534d980
	public override Int32 get_count() { }
	// RVA: 0x2d35a00 VA: 0x759534da00
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2d35c58 VA: 0x759534dc58
	public Void .ctor() { }
}
```