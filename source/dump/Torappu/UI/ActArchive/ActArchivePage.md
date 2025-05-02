# ActArchivePage

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ActArchiveStateBean _stateBean`

- `ActArchiveParam m_param`

- `DataBundle m_savedInst`


## Methods

- `IEnumerator _JumpToDetailState(DataBundle)`

- `IEnumerator _RouteToEntryCoroutine(Boolean)`

- `IEnumerator _ClearStateAfterHide()`

- `IEnumerator <>n__0()`

- `IEnumerator <>n__1(Boolean)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ActArchivePage : StateEnginePage
{
	private ActArchiveStateBean _stateBean; // 0xe8
	private ActArchiveParam m_param; // 0xf0
	private DataBundle m_savedInst; // 0xf8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnStart; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x18
	private static DelegateBridge __Hotfix0__JumpToDetailState; // 0x20
	private static DelegateBridge __Hotfix0__RouteToEntryCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__ClearStateAfterHide; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3006710 VA: 0x759561e710
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x30067d4 VA: 0x759561e7d4
	protected override Void OnStart() { }
	// RVA: 0x3006a94 VA: 0x759561ea94
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x3006b68 VA: 0x759561eb68
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x3006c58 VA: 0x759561ec58
	private IEnumerator _JumpToDetailState(DataBundle param) { }
	// RVA: 0x3006d50 VA: 0x759561ed50
	private IEnumerator _RouteToEntryCoroutine(Boolean useFastMode) { }
	// RVA: 0x3006e40 VA: 0x759561ee40
	private IEnumerator _ClearStateAfterHide() { }
	// RVA: 0x3006f14 VA: 0x759561ef14
	public Void .ctor() { }
	// RVA: 0x3006f84 VA: 0x759561ef84
	private IEnumerator <>n__0() { }
	// RVA: 0x3006f8c VA: 0x759561ef8c
	private IEnumerator <>n__1(Boolean isIntoStack) { }
	// RVA: 0x3006f98 VA: 0x759561ef98
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x3006fa0 VA: 0x759561efa0
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x3006fa8 VA: 0x759561efa8
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x3006fb0 VA: 0x759561efb0
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```