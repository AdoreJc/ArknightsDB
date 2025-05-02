# CarvingMainPage

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMainController _controller`

- `String m_actId`


## Properties

- `String activityId`

- `CarvingMainController controller`


## Methods

- `String get_activityId()`

- `CarvingMainController get_controller()`

- `IEnumerator _InitStateEngine(GameState)`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainPage : StateEnginePage, IHotfixable
{
	private CarvingMainController _controller; // 0xe8
	private String m_actId; // 0xf0
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_get_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x18
	private static DelegateBridge __Hotfix0__InitStateEngine; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String activityId { get; }
	public CarvingMainController controller { get; }

	// RVA: 0x2dabfa0 VA: 0x75953c3fa0
	public String get_activityId() { }
	// RVA: 0x2dabde8 VA: 0x75953c3de8
	public CarvingMainController get_controller() { }
	// RVA: 0x2db37b4 VA: 0x75953cb7b4
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2db387c VA: 0x75953cb87c
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2db3950 VA: 0x75953cb950
	private IEnumerator _InitStateEngine(GameState state) { }
	// RVA: 0x2db3a3c VA: 0x75953cba3c
	public Void .ctor() { }
	// RVA: 0x2db3aac VA: 0x75953cbaac
	private IEnumerator <>n__0() { }
	// RVA: 0x2db3ab4 VA: 0x75953cbab4
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2db3abc VA: 0x75953cbabc
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```