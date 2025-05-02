# SkinShopListAdapter

**Namespace:** `Torappu.UI.Shop`


## Fields

- `GameObject _skinShopItem`

- `UIStringEvent _stringEvent`

- `Boolean initFlag`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SkinShopListAdapter : RecycleLoopScrollAdapter
{
	private GameObject _skinShopItem; // 0x58
	private UIStringEvent _stringEvent; // 0x60
	public List`1 list; // 0x68
	public Boolean initFlag; // 0x70
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x0
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 totalCount { get; }

	// RVA: 0x246a684 VA: 0x7594a82684
	public override Int32 get_totalCount() { }
	// RVA: 0x246a71c VA: 0x7594a8271c
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x246a80c VA: 0x7594a8280c
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x246ab38 VA: 0x7594a82b38
	public Void .ctor() { }
}
```