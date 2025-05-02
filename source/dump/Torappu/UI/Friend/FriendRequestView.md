# FriendRequestView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendRequestGridAdapter _adapter`

- `LoopVerticalScrollRect _scrollRect`

- `FriendRequestState _state`

- `GameObject _noRequestTab`

- `Int32 m_count`


## Methods

- `Void DealWithDrag(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendRequestView : DataBinder`1
{
	private FriendRequestGridAdapter _adapter; // 0x20
	private LoopVerticalScrollRect _scrollRect; // 0x28
	private FriendRequestState _state; // 0x30
	private GameObject _noRequestTab; // 0x38
	private List`1 m_requestItemList; // 0x40
	private Int32 m_count; // 0x48
	private static DelegateBridge __Hotfix0_DealWithDrag; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28cf238 VA: 0x7594ee7238
	public Void DealWithDrag(Vector2 offset) { }
	// RVA: 0x28cf330 VA: 0x7594ee7330
	public override Void OnValueChanged(FriendListProperty property) { }
	// RVA: 0x28cf744 VA: 0x7594ee7744
	public Void .ctor() { }
}
```