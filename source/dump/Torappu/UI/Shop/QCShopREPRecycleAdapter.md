# QCShopREPRecycleAdapter

**Namespace:** `Torappu.UI.Shop`


## Fields

- `GameObject _itemObj`

- `SpriteHub priceHub`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopREPRecycleAdapter : RecycleLoopScrollAdapter
{
	public List`1 viewModelList; // 0x58
	private GameObject _itemObj; // 0x60
	public SpriteHub priceHub; // 0x68
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 totalCount { get; }

	// RVA: 0x2458dd8 VA: 0x7594a70dd8
	public override Int32 get_totalCount() { }
	// RVA: 0x2458e58 VA: 0x7594a70e58
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x2458f94 VA: 0x7594a70f94
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x2459084 VA: 0x7594a71084
	public Void .ctor() { }
}
```