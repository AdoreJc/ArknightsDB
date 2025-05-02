# ItemRepoChooseCharAdapter

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `AbstractViewBuilder viewBuilder`

- `Boolean clickable`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoChooseCharAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 charDatas; // 0x20
	public AbstractViewBuilder viewBuilder; // 0x28
	public Boolean clickable; // 0x30
	public Action`1 onItemClick; // 0x38
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2d31864 VA: 0x7595349864
	public override Int32 get_count() { }
	// RVA: 0x2d318e4 VA: 0x75953498e4
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2d31b3c VA: 0x7595349b3c
	public Void .ctor() { }
}
```