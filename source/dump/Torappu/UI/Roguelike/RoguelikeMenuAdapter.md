# RoguelikeMenuAdapter

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Type <adapterType>k__BackingField`


## Properties

- `Type adapterType`


## Methods

- `Type get_adapterType()`

- `Void set_adapterType(Type)`

- `Void NotifyAdapterChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuAdapter : IHotfixable
{
	private Type <adapterType>k__BackingField; // 0x10
	public Action`1 observer; // 0x18
	private static DelegateBridge __Hotfix0_get_adapterType; // 0x0
	private static DelegateBridge __Hotfix0_set_adapterType; // 0x8
	private static DelegateBridge __Hotfix0_get_showBottomBar; // 0x10
	private static DelegateBridge __Hotfix0_get_showStatusBar; // 0x18
	private static DelegateBridge __Hotfix0_get_buttonPrefab; // 0x20
	private static DelegateBridge __Hotfix0_get_buttonInput; // 0x28
	private static DelegateBridge __Hotfix0_get_charMenuObjectStatus; // 0x30
	private static DelegateBridge __Hotfix0_get_squadMenuObjectStatus; // 0x38
	private static DelegateBridge __Hotfix0_get_totemMenuObjectStatus; // 0x40
	private static DelegateBridge __Hotfix0_NotifyAdapterChanged; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Type adapterType { get; set; }
	public virtual Boolean showBottomBar { get; }
	public virtual Boolean showStatusBar { get; }
	public virtual RoguelikeMenuButtonPlugin buttonPrefab { get; }
	public virtual Input buttonInput { get; }
	public virtual RoguelikeMenuCharObjectStatus charMenuObjectStatus { get; }
	public virtual RoguelikeMenuSquadObjectStatus squadMenuObjectStatus { get; }
	public virtual RoguelikeMenuTotemObjectStatus totemMenuObjectStatus { get; }

	// RVA: 0x2a693b8 VA: 0x75950813b8
	public Type get_adapterType() { }
	// RVA: 0x2a77e78 VA: 0x759508fe78
	public Void set_adapterType(Type value) { }
	// RVA: 0x2a79920 VA: 0x7595091920
	public virtual Boolean get_showBottomBar() { }
	// RVA: 0x2a79984 VA: 0x7595091984
	public virtual Boolean get_showStatusBar() { }
	// RVA: 0x2a799e8 VA: 0x75950919e8
	public virtual RoguelikeMenuButtonPlugin get_buttonPrefab() { }
	// RVA: 0x2a79a4c VA: 0x7595091a4c
	public virtual Input get_buttonInput() { }
	// RVA: 0x2a79ab0 VA: 0x7595091ab0
	public virtual RoguelikeMenuCharObjectStatus get_charMenuObjectStatus() { }
	// RVA: 0x2a79b18 VA: 0x7595091b18
	public virtual RoguelikeMenuSquadObjectStatus get_squadMenuObjectStatus() { }
	// RVA: 0x2a79b7c VA: 0x7595091b7c
	public virtual RoguelikeMenuTotemObjectStatus get_totemMenuObjectStatus() { }
	// RVA: 0x2a79be0 VA: 0x7595091be0
	public Void NotifyAdapterChanged(Boolean fastMode) { }
	// RVA: 0x2a780c8 VA: 0x75950900c8
	public Void .ctor() { }
}
```