# UICooperateTaskTowerPanel

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
public class UICooperateTaskTowerPanel : UICooperateTaskPanel
{
	private const String POINT; // 0x0
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

	// RVA: 0x20d99dc VA: 0x75946f19dc
	public override CoopStageType get_type() { }
	// RVA: 0x20d9a44 VA: 0x75946f1a44
	public override Void LoadDataFromBuff(ObjectPtr`1 buff) { }
	// RVA: 0x20d9d20 VA: 0x75946f1d20
	public override Void GetProgerss(Int32 curScore) { }
	// RVA: 0x20d9e24 VA: 0x75946f1e24
	public override Void UpdatePanelFixed() { }
	// RVA: 0x20d9f3c VA: 0x75946f1f3c
	public override Void UpdatePanel() { }
	// RVA: 0x20da1c0 VA: 0x75946f21c0
	public Void .ctor() { }
	// RVA: 0x20da22c VA: 0x75946f222c
	private CoopStageType <>xLuaBaseProxy_get_type() { }
	// RVA: 0x20da230 VA: 0x75946f2230
	private Void <>xLuaBaseProxy_LoadDataFromBuff(ObjectPtr`1 P0) { }
	// RVA: 0x20da234 VA: 0x75946f2234
	private Void <>xLuaBaseProxy_GetProgerss(Int32 P0) { }
	// RVA: 0x20da238 VA: 0x75946f2238
	private Void <>xLuaBaseProxy_UpdatePanelFixed() { }
	// RVA: 0x20da23c VA: 0x75946f223c
	private Void <>xLuaBaseProxy_UpdatePanel() { }
}
```