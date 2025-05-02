# BattleStoryTree

**Namespace:** `Torappu.Battle.Dialog`


## Fields

- `Story story`


## Methods

- `Void Init()`

- `Void Attach(Dictionary`2)`

- `Void Detach(Dictionary`2)`

- `Void DetachExcutors()`

- `Void RunStory(Story)`

- `Void Reset()`

- `Void _ConstructJumpToDic()`

- `Boolean TryGetNext(Int32, out, out, Int32)`

- `Boolean ExcuteCommand(Command)`

- `Boolean CheckCondnByPred(String)`

- `Boolean _DoCheckCond(String, Func`2)`

- `Boolean <CheckCondnByPred>b__20_0(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class BattleStoryTree : IHotfixable
{
	public Story story; // 0x10
	private Dictionary`2 m_optionJumpCommandDic; // 0x18
	private Dictionary`2 m_optionCond; // 0x20
	private Dictionary`2 m_executors; // 0x28
	private List`1 m_executerCache; // 0x30
	private const String LOGIC_EXPRESION_PATTERN; // 0x0
	private static DelegateBridge __Hotfix0_get_jumpToDic; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Attach; // 0x10
	private static DelegateBridge __Hotfix0_Detach; // 0x18
	private static DelegateBridge __Hotfix0_DetachExcutors; // 0x20
	private static DelegateBridge __Hotfix0_RunStory; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x30
	private static DelegateBridge __Hotfix0__ConstructJumpToDic; // 0x38
	private static DelegateBridge __Hotfix0_TryGetNext; // 0x40
	private static DelegateBridge __Hotfix0_ConstructOptionsFromCommand; // 0x48
	private static DelegateBridge __Hotfix0_ExcuteCommand; // 0x50
	private static DelegateBridge __Hotfix0_CheckCondnByPred; // 0x58
	private static DelegateBridge __Hotfix0__DoCheckCond; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private Dictionary`2 jumpToDic { get; }

	// RVA: 0x1d15c5c VA: 0x759432dc5c
	private Dictionary`2 get_jumpToDic() { }
	// RVA: 0x1d15cc4 VA: 0x759432dcc4
	public Void Init() { }
	// RVA: 0x1d15dec VA: 0x759432ddec
	public Void Attach(Dictionary`2 executors) { }
	// RVA: 0x1d16178 VA: 0x759432e178
	public Void Detach(Dictionary`2 executors) { }
	// RVA: 0x1d16364 VA: 0x759432e364
	public Void DetachExcutors() { }
	// RVA: 0x1d163ec VA: 0x759432e3ec
	public Void RunStory(Story story) { }
	// RVA: 0x1d15d2c VA: 0x759432dd2c
	public Void Reset() { }
	// RVA: 0x1d16480 VA: 0x759432e480
	private Void _ConstructJumpToDic() { }
	// RVA: 0x1d16910 VA: 0x759432e910
	public Boolean TryGetNext(Int32 currentCommandIndex, out Int32 commandIndex, out Command command, Int32 decision) { }
	// RVA: 0x1d16bec VA: 0x759432ebec
	public List`1 ConstructOptionsFromCommand(Command command) { }
	// RVA: 0x1d17034 VA: 0x759432f034
	public Boolean ExcuteCommand(Command command) { }
	// RVA: 0x1d16f40 VA: 0x759432ef40
	public Boolean CheckCondnByPred(String commandConditionSource) { }
	// RVA: 0x1d172d4 VA: 0x759432f2d4
	public Boolean _DoCheckCond(String lamda, Func`2 validate) { }
	// RVA: 0x1d17570 VA: 0x759432f570
	public Void .ctor() { }
	// RVA: 0x1d17794 VA: 0x759432f794
	private Boolean <CheckCondnByPred>b__20_0(String conditionRef) { }
}
```