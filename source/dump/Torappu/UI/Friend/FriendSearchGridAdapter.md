# FriendSearchGridAdapter

**Namespace:** `Torappu.UI.Friend`


## Fields

- `GameObject _friendItem`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendSearchGridAdapter : RecycleLoopScrollAdapter`2
{
	public Action`1 DealAction; // 0x68
	private GameObject _friendItem; // 0x70
	private static DelegateBridge __Hotfix0_UpdateView; // 0x0
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x8
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28cf830 VA: 0x7594ee7830
	public override Void UpdateView(Int32 position, GameObject view, FriendListSearchItemHolder holder, KeyValuePair`2 data) { }
	// RVA: 0x28cf96c VA: 0x7594ee796c
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x28cf9d8 VA: 0x7594ee79d8
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x28cfac8 VA: 0x7594ee7ac8
	public Void .ctor() { }
}
```