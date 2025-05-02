# HandBookV2TeamMapState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2TeamMapStateBean _stateBean`

- `String m_cacheForce`


## Methods

- `Void OnClickForce(String)`

- `Void OnClickFavorMissionList()`

- `Void <RegisterToDataListener>b__5_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2TeamMapState : State
{
	private HandBookV2TeamMapStateBean _stateBean; // 0x50
	private String m_cacheForce; // 0x58
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnClickForce; // 0x20
	private static DelegateBridge __Hotfix0_OnClickFavorMissionList; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2ecafec VA: 0x75954e2fec
	protected override Void OnEnter() { }
	// RVA: 0x2ecb080 VA: 0x75954e3080
	protected override Void OnResume() { }
	// RVA: 0x2ecb100 VA: 0x75954e3100
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ecb168 VA: 0x75954e3168
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2ecb2e0 VA: 0x75954e32e0
	public Void OnClickForce(String id) { }
	// RVA: 0x2ecb410 VA: 0x75954e3410
	public Void OnClickFavorMissionList() { }
	// RVA: 0x2ecb51c VA: 0x75954e351c
	public Void .ctor() { }
	// RVA: 0x2ecb58c VA: 0x75954e358c
	private Void <RegisterToDataListener>b__5_0(IStateBean stateBean) { }
	// RVA: 0x2ecb64c VA: 0x75954e364c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ecb654 VA: 0x75954e3654
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2ecb65c VA: 0x75954e365c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```