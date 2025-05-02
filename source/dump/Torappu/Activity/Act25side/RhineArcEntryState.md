# RhineArcEntryState

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `RhineArcEntryStateBean _stateBean`

- `String m_actId`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _ClickItem(Act25SideArchiveItemType, String)`

- `Void _OnClickPicItemBtn(String)`

- `Void _OnClickStoryItemBtn(String)`

- `Void _OnClickKeyItem(String, String)`

- `Void OnClickPicArchive()`

- `Void OnClickStoryArchive()`

- `Void OnClickRhineBattlePerformance()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class RhineArcEntryState : State, IValueMsgReceiver
{
	private RhineArcEntryStateBean _stateBean; // 0x50
	public const Int32 MSG_ITEM_CLICK; // 0x0
	private String m_actId; // 0x58
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__ClickItem; // 0x20
	private static DelegateBridge __Hotfix0__OnClickPicItemBtn; // 0x28
	private static DelegateBridge __Hotfix0__OnClickStoryItemBtn; // 0x30
	private static DelegateBridge __Hotfix0__OnClickKeyItem; // 0x38
	private static DelegateBridge __Hotfix0_OnClickPicArchive; // 0x40
	private static DelegateBridge __Hotfix0_OnClickStoryArchive; // 0x48
	private static DelegateBridge __Hotfix0_OnClickRhineBattlePerformance; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3273ae0 VA: 0x759588bae0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3273b48 VA: 0x759588bb48
	protected override Void OnEnter() { }
	// RVA: 0x3273c68 VA: 0x759588bc68
	protected override Void OnResume() { }
	// RVA: 0x3273ce0 VA: 0x759588bce0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3273ef4 VA: 0x759588bef4
	private Void _ClickItem(Act25SideArchiveItemType type, String itemId) { }
	// RVA: 0x3273fcc VA: 0x759588bfcc
	private Void _OnClickPicItemBtn(String itemId) { }
	// RVA: 0x3274180 VA: 0x759588c180
	private Void _OnClickStoryItemBtn(String itemId) { }
	// RVA: 0x3273e04 VA: 0x759588be04
	private Void _OnClickKeyItem(String itemId, String toast) { }
	// RVA: 0x32744c8 VA: 0x759588c4c8
	public Void OnClickPicArchive() { }
	// RVA: 0x32746e4 VA: 0x759588c6e4
	public Void OnClickStoryArchive() { }
	// RVA: 0x3274334 VA: 0x759588c334
	public Void OnClickRhineBattlePerformance() { }
	// RVA: 0x3274900 VA: 0x759588c900
	public Void .ctor() { }
	// RVA: 0x3274970 VA: 0x759588c970
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3274978 VA: 0x759588c978
	private Void <>xLuaBaseProxy_OnResume() { }
}
```