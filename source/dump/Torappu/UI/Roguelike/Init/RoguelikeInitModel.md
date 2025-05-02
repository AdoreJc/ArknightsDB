# RoguelikeInitModel

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `RoguelikeInitStepContext <currentContext>k__BackingField`

- `PlayerRoguelikePlayerEventType <initPhase>k__BackingField`

- `RoguelikeInitStyle <uiStyle>k__BackingField`


## Properties

- `RoguelikeInitStepContext currentContext`

- `Int32 step`

- `Int32 maxStep`

- `PlayerRoguelikePlayerEventType initPhase`

- `RoguelikeInitStyle uiStyle`


## Methods

- `RoguelikeInitStepContext get_currentContext()`

- `Void set_currentContext(RoguelikeInitStepContext)`

- `Int32 get_step()`

- `Int32 get_maxStep()`

- `PlayerRoguelikePlayerEventType get_initPhase()`

- `Void set_initPhase(PlayerRoguelikePlayerEventType)`

- `RoguelikeInitStyle get_uiStyle()`

- `Void set_uiStyle(RoguelikeInitStyle)`

- `Boolean Load(RoguelikeInitContextUser, RoguelikeInitStyle)`

- `RoguelikeInitStepContext _CheckContextSuitForEvent(PlayerRoguelikePlayerEventType, RoguelikeInitContextUser)`

- `Void _CheckCurStepContextType(PlayerRoguelikePlayerEventType, RoguelikeInitContextUser)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitModel : IHotfixable
{
	private RoguelikeInitStepContext <currentContext>k__BackingField; // 0x10
	private PlayerRoguelikePlayerEventType <initPhase>k__BackingField; // 0x18
	private RoguelikeInitStyle <uiStyle>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_currentContext; // 0x0
	private static DelegateBridge __Hotfix0_set_currentContext; // 0x8
	private static DelegateBridge __Hotfix0_get_step; // 0x10
	private static DelegateBridge __Hotfix0_get_maxStep; // 0x18
	private static DelegateBridge __Hotfix0_get_initPhase; // 0x20
	private static DelegateBridge __Hotfix0_set_initPhase; // 0x28
	private static DelegateBridge __Hotfix0_get_uiStyle; // 0x30
	private static DelegateBridge __Hotfix0_set_uiStyle; // 0x38
	private static DelegateBridge __Hotfix0_Load; // 0x40
	private static DelegateBridge __Hotfix0__CheckContextSuitForEvent; // 0x48
	private static DelegateBridge __Hotfix0__CheckCurStepContextType; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public RoguelikeInitStepContext currentContext { get; set; }
	public Int32 step { get; }
	public Int32 maxStep { get; }
	public PlayerRoguelikePlayerEventType initPhase { get; set; }
	public RoguelikeInitStyle uiStyle { get; set; }

	// RVA: 0x2b83838 VA: 0x759519b838
	public RoguelikeInitStepContext get_currentContext() { }
	// RVA: 0x2b838a0 VA: 0x759519b8a0
	private Void set_currentContext(RoguelikeInitStepContext value) { }
	// RVA: 0x2b83924 VA: 0x759519b924
	public Int32 get_step() { }
	// RVA: 0x2b83a18 VA: 0x759519ba18
	public Int32 get_maxStep() { }
	// RVA: 0x2b83b0c VA: 0x759519bb0c
	public PlayerRoguelikePlayerEventType get_initPhase() { }
	// RVA: 0x2b83b74 VA: 0x759519bb74
	private Void set_initPhase(PlayerRoguelikePlayerEventType value) { }
	// RVA: 0x2b83bf0 VA: 0x759519bbf0
	public RoguelikeInitStyle get_uiStyle() { }
	// RVA: 0x2b83c58 VA: 0x759519bc58
	private Void set_uiStyle(RoguelikeInitStyle value) { }
	// RVA: 0x2b83cdc VA: 0x759519bcdc
	public Boolean Load(RoguelikeInitContextUser user, RoguelikeInitStyle style) { }
	// RVA: 0x2b83e90 VA: 0x759519be90
	private RoguelikeInitStepContext _CheckContextSuitForEvent(PlayerRoguelikePlayerEventType type, RoguelikeInitContextUser user) { }
	// RVA: 0x VA: 0x0
	private Void _CheckCurStepContextType(PlayerRoguelikePlayerEventType type, RoguelikeInitContextUser user) { }
	// RVA: 0x2b83f90 VA: 0x759519bf90
	public Void .ctor() { }
}
```