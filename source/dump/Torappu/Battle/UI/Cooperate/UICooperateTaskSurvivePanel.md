# UICooperateTaskSurvivePanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `FP m_basicAccomplish`

- `FP m_advanceTime`

- `FP m_basicTime`

- `FP m_passTime`

- `FP m_remainingTime`


## Methods

- `CoopStageType <>xLuaBaseProxy_get_type()`

- `Void <>xLuaBaseProxy_LoadDataFromBuff(ObjectPtr`1)`

- `Void <>xLuaBaseProxy_GetProgerss(Int32)`

- `Void <>xLuaBaseProxy_UpdatePanelFixed()`

- `Void <>xLuaBaseProxy_UpdatePanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateTaskSurvivePanel : UICooperateTaskPanel
{
	private FP m_basicAccomplish; // 0x70
	private FP m_advanceTime; // 0x78
	private FP m_basicTime; // 0x80
	private FP m_passTime; // 0x88
	private FP m_remainingTime; // 0x90
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_LoadDataFromBuff; // 0x8
	private static DelegateBridge __Hotfix0_GetProgerss; // 0x10
	private static DelegateBridge __Hotfix0_UpdatePanelFixed; // 0x18
	private static DelegateBridge __Hotfix0_UpdatePanel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override CoopStageType type { get; }

	// RVA: 0x20d8400 VA: 0x75946f0400
	public override CoopStageType get_type() { }
	// RVA: 0x20d8468 VA: 0x75946f0468
	public override Void LoadDataFromBuff(ObjectPtr`1 buff) { }
	// RVA: 0x20d879c VA: 0x75946f079c
	public override Void GetProgerss(Int32 curScore) { }
	// RVA: 0x20d8a20 VA: 0x75946f0a20
	public override Void UpdatePanelFixed() { }
	// RVA: 0x20d8b78 VA: 0x75946f0b78
	public override Void UpdatePanel() { }
	// RVA: 0x20d9000 VA: 0x75946f1000
	public Void .ctor() { }
	// RVA: 0x20d906c VA: 0x75946f106c
	private CoopStageType <>xLuaBaseProxy_get_type() { }
	// RVA: 0x20d9070 VA: 0x75946f1070
	private Void <>xLuaBaseProxy_LoadDataFromBuff(ObjectPtr`1 P0) { }
	// RVA: 0x20d9074 VA: 0x75946f1074
	private Void <>xLuaBaseProxy_GetProgerss(Int32 P0) { }
	// RVA: 0x20d9078 VA: 0x75946f1078
	private Void <>xLuaBaseProxy_UpdatePanelFixed() { }
	// RVA: 0x20d907c VA: 0x75946f107c
	private Void <>xLuaBaseProxy_UpdatePanel() { }
}
```