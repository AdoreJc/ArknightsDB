# CharacterPanel

**Namespace:** `Torappu.AVG`


## Fields

- `AVGCharacterSlot _middleSlot`

- `AVGCharacterSlot _leftSlot`

- `AVGCharacterSlot _rightSlot`

- `Color _focusColor`

- `Color _unfocusColor`


## Methods

- `AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector()`

- `Boolean _ExecuteCharacter(Command)`

- `Vector2 _GenPosition(ECharSlot, String)`

- `Void _ProcessSlotWithParam(Command, String, ECharSlot, Int32, Single, ECharTransType, String, String, String, String, String)`

- `Void _ProcessSlot(ECharSlot, CharSlotParam)`

- `Single _ProcessDurationWithTransType(Single, ECharTransType)`

- `Boolean _ExecuteCharacterAction(Command)`

- `Boolean _ExecuteCharacterMove(Command)`

- `Boolean _ExecuteCharacterJump(Command)`

- `Boolean _ExecuteCharacterShake(Command)`

- `Boolean _ExecuteCharacterZoom(Command)`

- `Boolean _ExecuteCharacterExit(Command)`

- `Vector2 _GenExitPosition(String, String)`

- `Boolean _AddFinishCommand(Boolean, Tween)`

- `Single CalculateFadetime(Single)`

- `Boolean NeedSkipAnimation(Single)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnStoryEnd(Story)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class CharacterPanel : ExecutorComponent, IContainsResRefs, IFadeTimeRatio
{
	private const Single HORIZONTAL_OUTSCREEN_DELTA; // 0x0
	private const Single VERTICAL_OUTSCREEN_DELTA; // 0x0
	private const Single LEFT_CHAR_HORIZONAL_DELTA; // 0x0
	private const String PARAM_NAME_ENTER_1; // 0x0
	private const String PARAM_NAME_ENTER_2; // 0x0
	private const String PARAM_NAME_BSTART_1; // 0x0
	private const String PARAM_NAME_BSTART_2; // 0x0
	private const String PARAM_NAME_BEND_1; // 0x0
	private const String PARAM_NAME_BEND_2; // 0x0
	private const String PARAM_NAME_XPOS_1; // 0x0
	private const String PARAM_NAME_YPOS_1; // 0x0
	private const String PARAM_NAME_XPOS_2; // 0x0
	private const String PARAM_NAME_YPOS_2; // 0x0
	private const Single DEFAULT_FADE_TIME; // 0x0
	private AVGCharacterSlot _middleSlot; // 0x50
	private AVGCharacterSlot _leftSlot; // 0x58
	private AVGCharacterSlot _rightSlot; // 0x60
	private Color _focusColor; // 0x68
	private Color _unfocusColor; // 0x78
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0x10
	private static DelegateBridge __Hotfix0__ExecuteCharacter; // 0x18
	private static DelegateBridge __Hotfix0__GenPosition; // 0x20
	private static DelegateBridge __Hotfix0__ProcessSlotWithParam; // 0x28
	private static DelegateBridge __Hotfix0__ProcessSlot; // 0x30
	private static DelegateBridge __Hotfix0__ProcessDurationWithTransType; // 0x38
	private static DelegateBridge __Hotfix0__ExecuteCharacterAction; // 0x40
	private static DelegateBridge __Hotfix0__ExecuteCharacterMove; // 0x48
	private static DelegateBridge __Hotfix0__ExecuteCharacterJump; // 0x50
	private static DelegateBridge __Hotfix0__ExecuteCharacterShake; // 0x58
	private static DelegateBridge __Hotfix0__ExecuteCharacterZoom; // 0x60
	private static DelegateBridge __Hotfix0__ExecuteCharacterExit; // 0x68
	private static DelegateBridge __Hotfix0__GenExitPosition; // 0x70
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x78
	private static DelegateBridge __Hotfix0_OnStoryEnd; // 0x80
	private static DelegateBridge __Hotfix0__AddFinishCommand; // 0x88
	private static DelegateBridge __Hotfix0_CalculateFadetime; // 0x90
	private static DelegateBridge __Hotfix0_NeedSkipAnimation; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x3e7b5a8 VA: 0x75964935a8
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e7b74c VA: 0x759649374c
	public override Void OnReset() { }
	// RVA: 0x3e7b7ec VA: 0x75964937ec
	public AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e7b880 VA: 0x7596493880
	private Boolean _ExecuteCharacter(Command command) { }
	// RVA: 0x3e7c49c VA: 0x759649449c
	private Vector2 _GenPosition(ECharSlot slot, String enter) { }
	// RVA: 0x3e7bed8 VA: 0x7596493ed8
	private Void _ProcessSlotWithParam(Command command, String name, ECharSlot slot, Int32 focus, Single duration, ECharTransType transType, String nEnter, String nStart, String nEnd, String nPosx, String nPosy) { }
	// RVA: 0x3e7c700 VA: 0x7596494700
	private Void _ProcessSlot(ECharSlot slot, CharSlotParam param) { }
	// RVA: 0x3e7c9c8 VA: 0x75964949c8
	private Single _ProcessDurationWithTransType(Single duration, ECharTransType tType) { }
	// RVA: 0x3e7ca60 VA: 0x7596494a60
	private Boolean _ExecuteCharacterAction(Command command) { }
	// RVA: 0x3e7cd34 VA: 0x7596494d34
	private Boolean _ExecuteCharacterMove(Command command) { }
	// RVA: 0x3e7d0c4 VA: 0x75964950c4
	private Boolean _ExecuteCharacterJump(Command command) { }
	// RVA: 0x3e7dcf8 VA: 0x7596495cf8
	private Boolean _ExecuteCharacterShake(Command command) { }
	// RVA: 0x3e7d918 VA: 0x7596495918
	private Boolean _ExecuteCharacterZoom(Command command) { }
	// RVA: 0x3e7d568 VA: 0x7596495568
	private Boolean _ExecuteCharacterExit(Command command) { }
	// RVA: 0x3e7e2f8 VA: 0x75964962f8
	private Vector2 _GenExitPosition(String slot, String direction) { }
	// RVA: 0x3e7e52c VA: 0x759649652c
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e7e590 VA: 0x7596496590
	public override Void OnStoryEnd(Story story) { }
	// RVA: 0x3e7e150 VA: 0x7596496150
	private Boolean _AddFinishCommand(Boolean block, Tween tween) { }
	// RVA: 0x3e7be30 VA: 0x7596493e30
	public Single CalculateFadetime(Single initialFadetime) { }
	// RVA: 0x3e7e254 VA: 0x7596496254
	public Boolean NeedSkipAnimation(Single fadetime) { }
	// RVA: 0x3e7e654 VA: 0x7596496654
	public Void .ctor() { }
	// RVA: 0x3e7e6d8 VA: 0x75964966d8
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e7e6e0 VA: 0x75964966e0
	private Void <>xLuaBaseProxy_OnStoryEnd(Story P0) { }
}
```