# CrisisV2MapAVGAdapter

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Int32 m_lastFocusSequenceId`

- `Int32 m_lastSwitchSequenceId`

- `Int32 m_lastHidePreviewSequenceId`


## Methods

- `Void set_onSlotFocus(Func`2)`

- `Void set_onMapSwitch(Func`2)`

- `Void set_onHidePreview(Func`1)`

- `Void OnMapFocusComplete(Int32)`

- `Void OnMapSwitchComplete(Int32)`

- `Void OnHidePreviewComplete(Int32)`

- `Boolean _OnFocusToSlot(Command)`

- `Boolean _OnMapSwitch(Command)`

- `Boolean _OnHidePreview(Command)`

- `Void OnEnable()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapAVGAdapter : ExecutorComponent, IHotfixable
{
	private const String PARAM_SLOT_TYPE; // 0x0
	private const String PARAM_MAP_TYPE; // 0x0
	private Func`2 <onSlotFocus>k__BackingField; // 0x50
	private Func`2 <onMapSwitch>k__BackingField; // 0x58
	private Func`1 <onHidePreview>k__BackingField; // 0x60
	private Int32 m_lastFocusSequenceId; // 0x68
	private Int32 m_lastSwitchSequenceId; // 0x6c
	private Int32 m_lastHidePreviewSequenceId; // 0x70
	private static DelegateBridge __Hotfix0_get_onSlotFocus; // 0x0
	private static DelegateBridge __Hotfix0_set_onSlotFocus; // 0x8
	private static DelegateBridge __Hotfix0_get_onMapSwitch; // 0x10
	private static DelegateBridge __Hotfix0_set_onMapSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_onHidePreview; // 0x20
	private static DelegateBridge __Hotfix0_set_onHidePreview; // 0x28
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x30
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x38
	private static DelegateBridge __Hotfix0_OnMapFocusComplete; // 0x40
	private static DelegateBridge __Hotfix0_OnMapSwitchComplete; // 0x48
	private static DelegateBridge __Hotfix0_OnHidePreviewComplete; // 0x50
	private static DelegateBridge __Hotfix0__OnFocusToSlot; // 0x58
	private static DelegateBridge __Hotfix0__OnMapSwitch; // 0x60
	private static DelegateBridge __Hotfix0__OnHidePreview; // 0x68
	private static DelegateBridge __Hotfix0_OnEnable; // 0x70
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	private Func`2 onSlotFocus { get; set; }
	private Func`2 onMapSwitch { get; set; }
	private Func`1 onHidePreview { get; set; }

	// RVA: 0x2c01000 VA: 0x7595219000
	private Func`2 get_onSlotFocus() { }
	// RVA: 0x2c01068 VA: 0x7595219068
	public Void set_onSlotFocus(Func`2 value) { }
	// RVA: 0x2c010ec VA: 0x75952190ec
	private Func`2 get_onMapSwitch() { }
	// RVA: 0x2c01154 VA: 0x7595219154
	public Void set_onMapSwitch(Func`2 value) { }
	// RVA: 0x2c011d8 VA: 0x75952191d8
	private Func`1 get_onHidePreview() { }
	// RVA: 0x2c01240 VA: 0x7595219240
	public Void set_onHidePreview(Func`1 value) { }
	// RVA: 0x2c012c4 VA: 0x75952192c4
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x2c01528 VA: 0x7595219528
	protected override Void ForceCommandEnd() { }
	// RVA: 0x2c0158c VA: 0x759521958c
	public Void OnMapFocusComplete(Int32 seqNum) { }
	// RVA: 0x2c01678 VA: 0x7595219678
	public Void OnMapSwitchComplete(Int32 seqNum) { }
	// RVA: 0x2c01764 VA: 0x7595219764
	public Void OnHidePreviewComplete(Int32 seqNum) { }
	// RVA: 0x2c01850 VA: 0x7595219850
	private Boolean _OnFocusToSlot(Command command) { }
	// RVA: 0x2c0195c VA: 0x759521995c
	private Boolean _OnMapSwitch(Command command) { }
	// RVA: 0x2c01a78 VA: 0x7595219a78
	private Boolean _OnHidePreview(Command command) { }
	// RVA: 0x2c01b30 VA: 0x7595219b30
	private Void OnEnable() { }
	// RVA: 0x2c01bec VA: 0x7595219bec
	private Void OnDestroy() { }
	// RVA: 0x2c01ca8 VA: 0x7595219ca8
	public Void .ctor() { }
}
```