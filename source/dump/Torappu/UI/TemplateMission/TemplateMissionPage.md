# TemplateMissionPage

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `TemplateMissionInputParam m_inputParam`


## Properties

- `TemplateMissionInputParam inputParam`


## Methods

- `TemplateMissionInputParam get_inputParam()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionPage : StateEnginePage, IHotfixable
{
	private TemplateMissionInputParam m_inputParam; // 0xe8
	private static DelegateBridge __Hotfix0_get_inputParam; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public TemplateMissionInputParam inputParam { get; }

	// RVA: 0x236bdd0 VA: 0x7594983dd0
	public TemplateMissionInputParam get_inputParam() { }
	// RVA: 0x236be38 VA: 0x7594983e38
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x236bf00 VA: 0x7594983f00
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x236bfd4 VA: 0x7594983fd4
	public Void .ctor() { }
	// RVA: 0x236c044 VA: 0x7594984044
	private IEnumerator <>n__0() { }
	// RVA: 0x236c04c VA: 0x759498404c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x236c054 VA: 0x7594984054
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```