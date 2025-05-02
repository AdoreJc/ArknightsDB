# UICooperateTaskKillPanel

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
public class UICooperateTaskKillPanel : UICooperateTaskPanel
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

	// RVA: 0x20d6350 VA: 0x75946ee350
	public override CoopStageType get_type() { }
	// RVA: 0x20d63b8 VA: 0x75946ee3b8
	public override Void LoadDataFromBuff(ObjectPtr`1 buff) { }
	// RVA: 0x20d6694 VA: 0x75946ee694
	public override Void GetProgerss(Int32 curScore) { }
	// RVA: 0x20d6798 VA: 0x75946ee798
	public override Void UpdatePanelFixed() { }
	// RVA: 0x20d68b0 VA: 0x75946ee8b0
	public override Void UpdatePanel() { }
	// RVA: 0x20d6b34 VA: 0x75946eeb34
	public Void .ctor() { }
	// RVA: 0x20d6ba0 VA: 0x75946eeba0
	private CoopStageType <>xLuaBaseProxy_get_type() { }
	// RVA: 0x20d6ba4 VA: 0x75946eeba4
	private Void <>xLuaBaseProxy_LoadDataFromBuff(ObjectPtr`1 P0) { }
	// RVA: 0x20d6ba8 VA: 0x75946eeba8
	private Void <>xLuaBaseProxy_GetProgerss(Int32 P0) { }
	// RVA: 0x20d6bac VA: 0x75946eebac
	private Void <>xLuaBaseProxy_UpdatePanelFixed() { }
	// RVA: 0x20d6bb0 VA: 0x75946eebb0
	private Void <>xLuaBaseProxy_UpdatePanel() { }
}
```