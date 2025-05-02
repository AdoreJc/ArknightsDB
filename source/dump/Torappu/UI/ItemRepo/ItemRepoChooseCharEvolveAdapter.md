# ItemRepoChooseCharEvolveAdapter

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `CharClickEvent itemEvent`

- `Boolean clickable`

- `CharCardType charCardType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoChooseCharEvolveAdapter : SimpleLayoutAdapter, IHotfixable
{
	public List`1 itemList; // 0x20
	public CharClickEvent itemEvent; // 0x28
	public Boolean clickable; // 0x30
	public CharCardType charCardType; // 0x34
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2d32ca0 VA: 0x759534aca0
	public override Int32 get_count() { }
	// RVA: 0x2d32d20 VA: 0x759534ad20
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2d33324 VA: 0x759534b324
	public Void .ctor() { }
}
```