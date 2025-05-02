# AVGCgItemPanel

**Namespace:** `Torappu.AVG`


## Methods

- `AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector()`

- `SlotParam _GenSlotParam(Command)`

- `Boolean _ExecuteShowCgItem(Command)`

- `Void _BindSlotPostDisplayItem(String, SlotInUseItem)`

- `Boolean _ExecuteHideCgItem(Command)`

- `Void _ClearItemByKey(Command, String)`

- `Void _ClearAllItems(Command)`

- `Void _ShowItem(Command)`

- `SlotInUseItem _GetItemFromDict(String)`

- `Void _AddItemToDict(String, SlotInUseItem)`

- `Void _RemoveItemFromDict(String)`

- `SlotStyle _FindSlotStyle(String)`

- `Sprite _LoadSprite(String)`

- `Void _Reset()`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCgItemPanel : ExecutorComponent, IContainsResRefs
{
	private SlotStyle[] _slotStyles; // 0x50
	private Dictionary`2 m_slotsInUseDict; // 0x58
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x10
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0x18
	private static DelegateBridge __Hotfix0__GenSlotParam; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteShowCgItem; // 0x28
	private static DelegateBridge __Hotfix0__BindSlotPostDisplayItem; // 0x30
	private static DelegateBridge __Hotfix0__ExecuteHideCgItem; // 0x38
	private static DelegateBridge __Hotfix0__ClearItemByKey; // 0x40
	private static DelegateBridge __Hotfix0__ClearAllItems; // 0x48
	private static DelegateBridge __Hotfix0__ShowItem; // 0x50
	private static DelegateBridge __Hotfix0__GetItemFromDict; // 0x58
	private static DelegateBridge __Hotfix0__AddItemToDict; // 0x60
	private static DelegateBridge __Hotfix0__RemoveItemFromDict; // 0x68
	private static DelegateBridge __Hotfix0__FindSlotStyle; // 0x70
	private static DelegateBridge __Hotfix0__LoadSprite; // 0x78
	private static DelegateBridge __Hotfix0__Reset; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x3e65d7c VA: 0x759647dd7c
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e65f18 VA: 0x759647df18
	public override Void OnReset() { }
	// RVA: 0x3e66174 VA: 0x759647e174
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e661d8 VA: 0x759647e1d8
	public AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e6626c VA: 0x759647e26c
	private SlotParam _GenSlotParam(Command command) { }
	// RVA: 0x3e664b8 VA: 0x759647e4b8
	private Boolean _ExecuteShowCgItem(Command command) { }
	// RVA: 0x3e66a70 VA: 0x759647ea70
	private Void _BindSlotPostDisplayItem(String key, SlotInUseItem item) { }
	// RVA: 0x3e66bcc VA: 0x759647ebcc
	private Boolean _ExecuteHideCgItem(Command command) { }
	// RVA: 0x3e66fa8 VA: 0x759647efa8
	private Void _ClearItemByKey(Command command, String key) { }
	// RVA: 0x3e66cf8 VA: 0x759647ecf8
	private Void _ClearAllItems(Command command) { }
	// RVA: 0x3e666ec VA: 0x759647e6ec
	private Void _ShowItem(Command command) { }
	// RVA: 0x3e6659c VA: 0x759647e59c
	private SlotInUseItem _GetItemFromDict(String key) { }
	// RVA: 0x3e67380 VA: 0x759647f380
	private Void _AddItemToDict(String key, SlotInUseItem item) { }
	// RVA: 0x3e672c0 VA: 0x759647f2c0
	private Void _RemoveItemFromDict(String key) { }
	// RVA: 0x3e6716c VA: 0x759647f16c
	private SlotStyle _FindSlotStyle(String style) { }
	// RVA: 0x3e674a8 VA: 0x759647f4a8
	private Sprite _LoadSprite(String key) { }
	// RVA: 0x3e65f88 VA: 0x759647df88
	private Void _Reset() { }
	// RVA: 0x3e676b8 VA: 0x759647f6b8
	public Void .ctor() { }
	// RVA: 0x3e67778 VA: 0x759647f778
	private Void <>xLuaBaseProxy_OnReset() { }
}
```