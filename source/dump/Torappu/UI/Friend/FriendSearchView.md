# FriendSearchView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Transform _searchContain`

- `FriendListSearchItem _searchItem`

- `FriendSearchState _state`

- `FriendSearchGridAdapter _adapter`

- `LoopScrollRect _scrollRect`

- `InputField _inputField`

- `GameObject _noResultTab`

- `Int32 m_count`


## Methods

- `Void DealWithDrag(Vector2)`

- `Void CleanView()`

- `Void OnSearchRequest()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendSearchView : DataBinder`1
{
	private Transform _searchContain; // 0x20
	private FriendListSearchItem _searchItem; // 0x28
	private FriendSearchState _state; // 0x30
	private FriendSearchGridAdapter _adapter; // 0x38
	private LoopScrollRect _scrollRect; // 0x40
	private InputField _inputField; // 0x48
	private GameObject _noResultTab; // 0x50
	private Int32 m_count; // 0x58
	private static DelegateBridge __Hotfix0_DealWithDrag; // 0x0
	private static DelegateBridge __Hotfix0_CleanView; // 0x8
	private static DelegateBridge __Hotfix0_OnSearchRequest; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28cfb58 VA: 0x7594ee7b58
	public Void DealWithDrag(Vector2 offset) { }
	// RVA: 0x28cfc50 VA: 0x7594ee7c50
	public Void CleanView() { }
	// RVA: 0x28cfd48 VA: 0x7594ee7d48
	public Void OnSearchRequest() { }
	// RVA: 0x28cfdc8 VA: 0x7594ee7dc8
	public override Void OnValueChanged(FriendListProperty property) { }
	// RVA: 0x28d019c VA: 0x7594ee819c
	public Void .ctor() { }
}
```