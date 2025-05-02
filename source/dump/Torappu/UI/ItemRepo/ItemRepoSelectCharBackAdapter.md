# ItemRepoSelectCharBackAdapter

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `UIStringEvent itemEvent`

- `Boolean clickable`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoSelectCharBackAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 itemList; // 0x20
	public UIStringEvent itemEvent; // 0x28
	public Boolean clickable; // 0x30
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2d37d6c VA: 0x759534fd6c
	public override Int32 get_count() { }
	// RVA: 0x2d37dec VA: 0x759534fdec
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2d3801c VA: 0x759535001c
	public Void .ctor() { }
}
```