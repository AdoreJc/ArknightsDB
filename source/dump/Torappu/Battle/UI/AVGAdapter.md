# AVGAdapter

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _mask`


## Properties

- `Boolean maskOn`


## Methods

- `Boolean get_maskOn()`

- `Void set_maskOn(Boolean)`

- `Void _OnStoryBegin(Object)`

- `Void _OnStoryEnd(Object)`

- `Boolean _ExecutePause(Command)`

- `Boolean _ExecuteBattleDelay(Command)`

- `Boolean _ExecuteUnlockFunction(Command)`

- `Boolean _ExecuteLockFunction(Command)`

- `Boolean _ExecuteEnsureMinCost(Command)`

- `Boolean _ExecuteEnsureMinSp(Command)`

- `Boolean _ExecuteSwitchToDefaultUIState(Command)`

- `Void Start()`

- `Void OnDestroy()`

- `Boolean _BattleNotPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AVGAdapter : ExecutorComponent
{
	private Image _mask; // 0x50
	private static DelegateBridge __Hotfix0_get_maskOn; // 0x0
	private static DelegateBridge __Hotfix0_set_maskOn; // 0x8
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x10
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x18
	private static DelegateBridge __Hotfix0__OnStoryBegin; // 0x20
	private static DelegateBridge __Hotfix0__OnStoryEnd; // 0x28
	private static DelegateBridge __Hotfix0__ExecutePause; // 0x30
	private static DelegateBridge __Hotfix0__ExecuteBattleDelay; // 0x38
	private static DelegateBridge __Hotfix0__ExecuteUnlockFunction; // 0x40
	private static DelegateBridge __Hotfix0__ExecuteLockFunction; // 0x48
	private static DelegateBridge __Hotfix0__ExecuteEnsureMinCost; // 0x50
	private static DelegateBridge __Hotfix0__ExecuteEnsureMinSp; // 0x58
	private static DelegateBridge __Hotfix0__ExecuteSwitchToDefaultUIState; // 0x60
	private static DelegateBridge __Hotfix0_Start; // 0x68
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x70
	private static DelegateBridge __Hotfix0__BattleNotPause; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Boolean maskOn { get; set; }

	// RVA: 0x2078930 VA: 0x7594690930
	public Boolean get_maskOn() { }
	// RVA: 0x20789a4 VA: 0x75946909a4
	private Void set_maskOn(Boolean value) { }
	// RVA: 0x2078a30 VA: 0x7594690a30
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x2078e04 VA: 0x7594690e04
	protected override Void ForceCommandEnd() { }
	// RVA: 0x2078e68 VA: 0x7594690e68
	private Void _OnStoryBegin(Object arg) { }
	// RVA: 0x207900c VA: 0x759469100c
	private Void _OnStoryEnd(Object arg) { }
	// RVA: 0x2079108 VA: 0x7594691108
	private Boolean _ExecutePause(Command command) { }
	// RVA: 0x2079250 VA: 0x7594691250
	private Boolean _ExecuteBattleDelay(Command command) { }
	// RVA: 0x20793c8 VA: 0x75946913c8
	private Boolean _ExecuteUnlockFunction(Command command) { }
	// RVA: 0x20794c0 VA: 0x75946914c0
	private Boolean _ExecuteLockFunction(Command command) { }
	// RVA: 0x20795b8 VA: 0x75946915b8
	private Boolean _ExecuteEnsureMinCost(Command command) { }
	// RVA: 0x2079698 VA: 0x7594691698
	private Boolean _ExecuteEnsureMinSp(Command command) { }
	// RVA: 0x207980c VA: 0x759469180c
	private Boolean _ExecuteSwitchToDefaultUIState(Command command) { }
	// RVA: 0x20798d8 VA: 0x75946918d8
	private Void Start() { }
	// RVA: 0x2079aa8 VA: 0x7594691aa8
	private Void OnDestroy() { }
	// RVA: 0x2079c70 VA: 0x7594691c70
	private Boolean _BattleNotPause() { }
	// RVA: 0x2079d08 VA: 0x7594691d08
	public Void .ctor() { }
}
```