# AVGShowItemPanel

**Namespace:** `Torappu.AVG`


## Fields

- `AVGShowItemSlot _slotInUse`


## Methods

- `AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector()`

- `Boolean _ExecuteShowItem(Command)`

- `Boolean _ExecuteHideItem(Command)`

- `Void _ShowItem(Command)`

- `SlotStyle _FindSlotStyle(String)`

- `Sprite _LoadSprite(String)`

- `Void _Reset()`

- `Void <_ExecuteHideItem>b__7_0()`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGShowItemPanel : ExecutorComponent, IContainsResRefs
{
	private SlotStyle[] _slotStyles; // 0x50
	private AVGShowItemSlot _slotInUse; // 0x58
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0x10
	private static DelegateBridge __Hotfix0__ExecuteShowItem; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteHideItem; // 0x20
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x28
	private static DelegateBridge __Hotfix0__ShowItem; // 0x30
	private static DelegateBridge __Hotfix0__FindSlotStyle; // 0x38
	private static DelegateBridge __Hotfix0__LoadSprite; // 0x40
	private static DelegateBridge __Hotfix0__Reset; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x3e731d0 VA: 0x759648b1d0
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e73374 VA: 0x759648b374
	public override Void OnReset() { }
	// RVA: 0x3e734d8 VA: 0x759648b4d8
	public AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e7356c VA: 0x759648b56c
	private Boolean _ExecuteShowItem(Command command) { }
	// RVA: 0x3e739bc VA: 0x759648b9bc
	private Boolean _ExecuteHideItem(Command command) { }
	// RVA: 0x3e73ae8 VA: 0x759648bae8
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e736fc VA: 0x759648b6fc
	private Void _ShowItem(Command command) { }
	// RVA: 0x3e73b4c VA: 0x759648bb4c
	private SlotStyle _FindSlotStyle(String style) { }
	// RVA: 0x3e73ca0 VA: 0x759648bca0
	private Sprite _LoadSprite(String key) { }
	// RVA: 0x3e733e8 VA: 0x759648b3e8
	private Void _Reset() { }
	// RVA: 0x3e73dd4 VA: 0x759648bdd4
	public Void .ctor() { }
	// RVA: 0x3e73e44 VA: 0x759648be44
	private Void <_ExecuteHideItem>b__7_0() { }
	// RVA: 0x3e73e60 VA: 0x759648be60
	private Void <>xLuaBaseProxy_OnReset() { }
}
```