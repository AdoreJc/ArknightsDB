# Act5D1RuneSelectState

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Text _point1`

- `Text _point2`

- `Act5D1ResourceBar _resourceBar`

- `SimpleLayoutContent _viewContainer`

- `Act5D1RuneStageStateBean _stateBean`

- `ScrollRectSoftMask _softMask`

- `Adapter m_adapter`

- `Boolean m_isInit`

- `String m_stageId`

- `String m_runeId`


## Methods

- `Void _InitIfNot()`

- `Void OnClick(String)`

- `Void <RegisterToDataListener>b__12_0(IStateBean)`

- `Void <OnResume>b__13_0()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneSelectState : PopupFloatState
{
	private Text _point1; // 0x70
	private Text _point2; // 0x78
	private Act5D1ResourceBar _resourceBar; // 0x80
	private SimpleLayoutContent _viewContainer; // 0x88
	private Act5D1RuneStageStateBean _stateBean; // 0x90
	private ScrollRectSoftMask _softMask; // 0x98
	private Adapter m_adapter; // 0xa0
	private Boolean m_isInit; // 0xa8
	private String m_stageId; // 0xb0
	private String m_runeId; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31ce534 VA: 0x75957e6534
	private Void _InitIfNot() { }
	// RVA: 0x31ce744 VA: 0x75957e6744
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x31ce8bc VA: 0x75957e68bc
	protected override Void OnResume() { }
	// RVA: 0x31ce9ac VA: 0x75957e69ac
	protected override Void OnEnter() { }
	// RVA: 0x31cea2c VA: 0x75957e6a2c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31cea94 VA: 0x75957e6a94
	public Void OnClick(String runeId) { }
	// RVA: 0x31cef20 VA: 0x75957e6f20
	public Void .ctor() { }
	// RVA: 0x31cef90 VA: 0x75957e6f90
	private Void <RegisterToDataListener>b__12_0(IStateBean stateBean) { }
	// RVA: 0x31cf038 VA: 0x75957e7038
	private Void <OnResume>b__13_0() { }
	// RVA: 0x31cf104 VA: 0x75957e7104
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x31cf10c VA: 0x75957e710c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x31cf114 VA: 0x75957e7114
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```