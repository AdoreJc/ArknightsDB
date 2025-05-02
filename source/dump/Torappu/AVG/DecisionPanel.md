# DecisionPanel

**Namespace:** `Torappu.AVG`


## Fields

- `Command m_command`

- `DesicionCommandPrecidator m_decisionCommandPredicator`


## Methods

- `Void OnOptionButtonPressed(Int32)`

- `Void _SetOptionButtonSelect(Int32, Boolean)`

- `Boolean _ExecuteDecision(Command)`

- `Boolean _ExecutePredicate(Command)`

- `Void _SetupOptionText(String[])`

- `Int32 _GetOptionValue(String, Int32)`

- `Void Awake()`

- `ICommandExecutor <>xLuaBaseProxy_GenerateExecutorWrapper(WrapperOptions)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class DecisionPanel : ExecutorComponent
{
	private const String PARAM_NAME_OPTIONS; // 0x0
	private const String PARAM_NAME_VALUES; // 0x0
	private const String PARAM_NAME_REFERENCES; // 0x0
	private const String COMMAND_NAME_DECISION; // 0x0
	private const String COMMAND_NAME_PREDICATE; // 0x0
	private GameObject[] _optionRoots; // 0x50
	private Text[] m_optionTexts; // 0x58
	private Button[] m_optionButtons; // 0x60
	private Command m_command; // 0x68
	private DesicionCommandPrecidator m_decisionCommandPredicator; // 0x70
	private static DelegateBridge __Hotfix0_GenerateExecutorWrapper; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0_OnReset; // 0x10
	private static DelegateBridge __Hotfix0_OnOptionButtonPressed; // 0x18
	private static DelegateBridge __Hotfix0__SetOptionButtonSelect; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteDecision; // 0x28
	private static DelegateBridge __Hotfix0__ExecutePredicate; // 0x30
	private static DelegateBridge __Hotfix0__SetupOptionText; // 0x38
	private static DelegateBridge __Hotfix0__GetOptionValue; // 0x40
	private static DelegateBridge __Hotfix0__GetReferenceValue; // 0x48
	private static DelegateBridge __Hotfix0_OnFinish; // 0x50
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x58
	private static DelegateBridge __Hotfix0_Awake; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x3e82040 VA: 0x759649a040
	protected override ICommandExecutor GenerateExecutorWrapper(WrapperOptions options) { }
	// RVA: 0x3e82248 VA: 0x759649a248
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e823ec VA: 0x759649a3ec
	public override Void OnReset() { }
	// RVA: 0x3e8246c VA: 0x759649a46c
	public Void OnOptionButtonPressed(Int32 index) { }
	// RVA: 0x3e824f0 VA: 0x759649a4f0
	private Void _SetOptionButtonSelect(Int32 index, Boolean needFinishCommand) { }
	// RVA: 0x3e82770 VA: 0x759649a770
	private Boolean _ExecuteDecision(Command command) { }
	// RVA: 0x3e82c74 VA: 0x759649ac74
	private Boolean _ExecutePredicate(Command command) { }
	// RVA: 0x3e82a60 VA: 0x759649aa60
	private Void _SetupOptionText(String[] optionString) { }
	// RVA: 0x3e82624 VA: 0x759649a624
	private Int32 _GetOptionValue(String valueString, Int32 index) { }
	// RVA: 0x3e82da4 VA: 0x759649ada4
	private Int32[] _GetReferenceValue(String valueString) { }
	// RVA: 0x3e82ef8 VA: 0x759649aef8
	protected override Void OnFinish() { }
	// RVA: 0x3e82f94 VA: 0x759649af94
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e82ff8 VA: 0x759649aff8
	private Void Awake() { }
	// RVA: 0x3e83228 VA: 0x759649b228
	public Void .ctor() { }
	// RVA: 0x3e832e0 VA: 0x759649b2e0
	private ICommandExecutor <>xLuaBaseProxy_GenerateExecutorWrapper(WrapperOptions P0) { }
	// RVA: 0x3e83308 VA: 0x759649b308
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e83310 VA: 0x759649b310
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```