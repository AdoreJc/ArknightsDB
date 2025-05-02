# UICooperateTaskTargetPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Int32 m_totalCnt`

- `Int32 m_basicTotalCnt`

- `Int32 m_curCnt`

- `Int32 m_cachedCurCnt`

- `FP m_basicAccomplish`


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
public class UICooperateTaskTargetPanel : UICooperateTaskPanel
{
	private Int32 m_totalCnt; // 0x70
	private Int32 m_basicTotalCnt; // 0x74
	private Int32 m_curCnt; // 0x78
	private Int32 m_cachedCurCnt; // 0x7c
	private FP m_basicAccomplish; // 0x80
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_LoadDataFromBuff; // 0x8
	private static DelegateBridge __Hotfix0_GetProgerss; // 0x10
	private static DelegateBridge __Hotfix0_UpdatePanelFixed; // 0x18
	private static DelegateBridge __Hotfix0_UpdatePanel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override CoopStageType type { get; }

	// RVA: 0x20d9080 VA: 0x75946f1080
	public override CoopStageType get_type() { }
	// RVA: 0x20d90e8 VA: 0x75946f10e8
	public override Void LoadDataFromBuff(ObjectPtr`1 buff) { }
	// RVA: 0x20d94bc VA: 0x75946f14bc
	public override Void GetProgerss(Int32 curScore) { }
	// RVA: 0x20d95c0 VA: 0x75946f15c0
	public override Void UpdatePanelFixed() { }
	// RVA: 0x20d96d8 VA: 0x75946f16d8
	public override Void UpdatePanel() { }
	// RVA: 0x20d995c VA: 0x75946f195c
	public Void .ctor() { }
	// RVA: 0x20d99c8 VA: 0x75946f19c8
	private CoopStageType <>xLuaBaseProxy_get_type() { }
	// RVA: 0x20d99cc VA: 0x75946f19cc
	private Void <>xLuaBaseProxy_LoadDataFromBuff(ObjectPtr`1 P0) { }
	// RVA: 0x20d99d0 VA: 0x75946f19d0
	private Void <>xLuaBaseProxy_GetProgerss(Int32 P0) { }
	// RVA: 0x20d99d4 VA: 0x75946f19d4
	private Void <>xLuaBaseProxy_UpdatePanelFixed() { }
	// RVA: 0x20d99d8 VA: 0x75946f19d8
	private Void <>xLuaBaseProxy_UpdatePanel() { }
}
```