# Act1VAutoChessEntryPage

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessEntryController _controller`

- `Params m_param`

- `DataBundle m_savedInst`


## Properties

- `String actId`

- `Act1VAutoChessEntryController controller`

- `Boolean isShowAnimAllFinished`


## Methods

- `String get_actId()`

- `Act1VAutoChessEntryController get_controller()`

- `Boolean get_isShowAnimAllFinished()`

- `Void _TriggerBGMSignal()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryPage : StateEnginePage
{
	private Act1VAutoChessEntryController _controller; // 0xe8
	private Params m_param; // 0xf0
	private DataBundle m_savedInst; // 0xf8
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_controller; // 0x8
	private static DelegateBridge __Hotfix0_get_isShowAnimAllFinished; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_OnStart; // 0x20
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x28
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x30
	private static DelegateBridge __Hotfix0__TriggerBGMSignal; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String actId { get; }
	public Act1VAutoChessEntryController controller { get; }
	public Boolean isShowAnimAllFinished { get; }

	// RVA: 0x3337130 VA: 0x759594f130
	public String get_actId() { }
	// RVA: 0x333a7b0 VA: 0x75959527b0
	public Act1VAutoChessEntryController get_controller() { }
	// RVA: 0x333a818 VA: 0x7595952818
	public Boolean get_isShowAnimAllFinished() { }
	// RVA: 0x333a8d8 VA: 0x75959528d8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x333a99c VA: 0x759595299c
	protected override Void OnStart() { }
	// RVA: 0x333abf8 VA: 0x7595952bf8
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x333ace8 VA: 0x7595952ce8
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x333aa64 VA: 0x7595952a64
	private Void _TriggerBGMSignal() { }
	// RVA: 0x333add8 VA: 0x7595952dd8
	public Void .ctor() { }
	// RVA: 0x333ae48 VA: 0x7595952e48
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x333ae50 VA: 0x7595952e50
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x333ae58 VA: 0x7595952e58
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x333ae64 VA: 0x7595952e64
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```