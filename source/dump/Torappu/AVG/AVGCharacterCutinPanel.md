# AVGCharacterCutinPanel

**Namespace:** `Torappu.AVG`


## Fields

- `GameObjectPoolComponent _slotPool`

- `Transform _cutinContainer`

- `CutinController m_cutinController`

- `Boolean m_Inited`


## Methods

- `AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector()`

- `Boolean _ExecuteCharacterCutin(Command)`

- `Void _Reset()`

- `Boolean _ExecuteInterlude(Command)`

- `Void _InitCutinIfNot()`

- `CutinParam _GenCutinParamWithCommand(Command)`

- `Vector2 _ParseVector(String)`

- `ParamType _GenCutinType(String)`

- `Void <_ExecuteInterlude>b__15_0()`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCharacterCutinPanel : ExecutorComponent, IContainsResRefs
{
	private GameObjectPoolComponent _slotPool; // 0x50
	private Transform _cutinContainer; // 0x58
	private Dictionary`2 _slots; // 0x60
	private CutinController m_cutinController; // 0x68
	private Boolean m_Inited; // 0x70
	private const String CUTIN_ELEMENT_TYPE_CHAR; // 0x0
	private const String CUTIN_ELEMENT_TYPE_BG; // 0x0
	private const String CUTIN_ELEMENT_TYPE_CHARACTER; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0x10
	private static DelegateBridge __Hotfix0__ExecuteCharacterCutin; // 0x18
	private static DelegateBridge __Hotfix0__Reset; // 0x20
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteInterlude; // 0x30
	private static DelegateBridge __Hotfix0__InitCutinIfNot; // 0x38
	private static DelegateBridge __Hotfix0__GenCutinParamWithCommand; // 0x40
	private static DelegateBridge __Hotfix0__ParseVector; // 0x48
	private static DelegateBridge __Hotfix0__GenCutinType; // 0x50
	private static DelegateBridge __Hotfix0__GetMaskPathFromId; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x3e678f0 VA: 0x759647f8f0
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e67a8c VA: 0x759647fa8c
	public override Void OnReset() { }
	// RVA: 0x3e67c70 VA: 0x759647fc70
	public AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e67d04 VA: 0x759647fd04
	private Boolean _ExecuteCharacterCutin(Command command) { }
	// RVA: 0x3e67afc VA: 0x759647fafc
	private Void _Reset() { }
	// RVA: 0x3e68560 VA: 0x7596480560
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e685c4 VA: 0x75964805c4
	private Boolean _ExecuteInterlude(Command command) { }
	// RVA: 0x3e682bc VA: 0x75964802bc
	private Void _InitCutinIfNot() { }
	// RVA: 0x3e68898 VA: 0x7596480898
	private CutinParam _GenCutinParamWithCommand(Command command) { }
	// RVA: 0x3e69358 VA: 0x7596481358
	private Vector2 _ParseVector(String rawVector) { }
	// RVA: 0x3e69234 VA: 0x7596481234
	private ParamType _GenCutinType(String param) { }
	// RVA: 0x3e694bc VA: 0x75964814bc
	private static String _GetMaskPathFromId(String maskId) { }
	// RVA: 0x3e69528 VA: 0x7596481528
	public Void .ctor() { }
	// RVA: 0x3e695e8 VA: 0x75964815e8
	private Void <_ExecuteInterlude>b__15_0() { }
	// RVA: 0x3e695ec VA: 0x75964815ec
	private Void <>xLuaBaseProxy_OnReset() { }
}
```