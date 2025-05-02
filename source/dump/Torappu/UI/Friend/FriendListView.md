# FriendListView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendListRepoGridAdapter _adapter`

- `FriendListState _state`

- `LoopVerticalScrollRect _scrollRect`

- `RectMask2D _mask`

- `GameObject _noFriendTab`

- `Int32 m_count`


## Methods

- `Void DealWithDrag(Vector2)`

- `Void HideViewList(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendListView : DataBinder`1
{
	private FriendListRepoGridAdapter _adapter; // 0x20
	private FriendListState _state; // 0x28
	private LoopVerticalScrollRect _scrollRect; // 0x30
	private RectMask2D _mask; // 0x38
	private GameObject _noFriendTab; // 0x40
	private Int32 m_count; // 0x48
	private static DelegateBridge __Hotfix0_DealWithDrag; // 0x0
	private static DelegateBridge __Hotfix0_HideViewList; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28cea64 VA: 0x7594ee6a64
	public Void DealWithDrag(Vector2 offset) { }
	// RVA: 0x28cc90c VA: 0x7594ee490c
	public Void HideViewList(Int32 index) { }
	// RVA: 0x28ceb5c VA: 0x7594ee6b5c
	public override Void OnValueChanged(FriendListProperty property) { }
	// RVA: 0x28ceeb4 VA: 0x7594ee6eb4
	public Void .ctor() { }
}
```