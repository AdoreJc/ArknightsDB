# BuildingMessageLeaveBoardVisitorItemHolderView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `BuildingMessageLeaveBoardVisitorItemView _visitorItemPrefab`

- `BuildingMessageLeaveBoardVisitorItemView m_visitorItem`


## Methods

- `Void _LoadPrefabIfNot()`

- `Void Render(IMessageBoardVisitorData, Int64, Action`1)`

- `Void Hide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMessageLeaveBoardVisitorItemHolderView : MonoBehaviour, IHotfixable
{
	private BuildingMessageLeaveBoardVisitorItemView _visitorItemPrefab; // 0x18
	private BuildingMessageLeaveBoardVisitorItemView m_visitorItem; // 0x20
	private static DelegateBridge __Hotfix0__LoadPrefabIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_Hide; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3dc8734 VA: 0x75963e0734
	private Void _LoadPrefabIfNot() { }
	// RVA: 0x3dc884c VA: 0x75963e084c
	public Void Render(IMessageBoardVisitorData visitorData, Int64 lastVisitBoardTs, Action`1 onClickAvatar) { }
	// RVA: 0x3dc8c10 VA: 0x75963e0c10
	public Void Hide() { }
	// RVA: 0x3dc8cd8 VA: 0x75963e0cd8
	public Void .ctor() { }
}
```