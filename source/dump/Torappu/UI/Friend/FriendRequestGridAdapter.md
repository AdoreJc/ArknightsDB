# FriendRequestGridAdapter

**Namespace:** `Torappu.UI.Friend`


## Fields

- `GameObject _friendRequestItem`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendRequestGridAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _friendRequestItem; // 0x68
	public Action`2 DealAction; // 0x70
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28cef4c VA: 0x7594ee6f4c
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x28cf03c VA: 0x7594ee703c
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x28cf0a8 VA: 0x7594ee70a8
	public override Void UpdateView(Int32 position, GameObject view, FriendListRequestItemHolder holder, FriendData data) { }
	// RVA: 0x28cf1a8 VA: 0x7594ee71a8
	public Void .ctor() { }
}
```