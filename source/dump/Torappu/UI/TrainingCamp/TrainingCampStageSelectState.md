# TrainingCampStageSelectState

**Namespace:** `Torappu.UI.TrainingCamp`


## Fields

- `TrainingCampStageSelectView _view`

- `Boolean m_isInited`

- `TrainingCampStageSelectStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void OnOpenEnemy()`

- `Void StartBattle()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void <RegisterToDataListener>b__9_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TrainingCamp
public class TrainingCampStageSelectState : State, IValueMsgReceiver
{
	public const Int32 MSG_SELECT_STAGE; // 0x0
	private TrainingCampStageSelectView _view; // 0x50
	private Boolean m_isInited; // 0x58
	private TrainingCampStageSelectStateBean m_stateBean; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnOpenEnemy; // 0x20
	private static DelegateBridge __Hotfix0_StartBattle; // 0x28
	private static DelegateBridge __Hotfix0_OnMessage; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x234a3a4 VA: 0x75949623a4
	private Void _InitIfNot() { }
	// RVA: 0x234a53c VA: 0x759496253c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x234a5a4 VA: 0x75949625a4
	protected override Void OnEnter() { }
	// RVA: 0x234b0f0 VA: 0x75949630f0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x234b268 VA: 0x7594963268
	public Void OnOpenEnemy() { }
	// RVA: 0x234b374 VA: 0x7594963374
	public Void StartBattle() { }
	// RVA: 0x234bc0c VA: 0x7594963c0c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x234bd18 VA: 0x7594963d18
	public Void .ctor() { }
	// RVA: 0x234bd88 VA: 0x7594963d88
	private Void <RegisterToDataListener>b__9_0(IStateBean stateBean) { }
	// RVA: 0x234bf24 VA: 0x7594963f24
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x234bf2c VA: 0x7594963f2c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```