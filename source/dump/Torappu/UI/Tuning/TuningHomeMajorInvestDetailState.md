# TuningHomeMajorInvestDetailState

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningHomeMajorInvestDetailView _detailView`

- `TuningHomeMajorInvestDetailStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void _OnBackClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeMajorInvestDetailState : PopupFloatState, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_BACK_BTN_CLICKED; // 0x0
	private TuningHomeMajorInvestDetailView _detailView; // 0x70
	private TuningHomeMajorInvestDetailStateBean m_stateBean; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnBackClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x232c7b8 VA: 0x75949447b8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x232c820 VA: 0x7594944820
	protected override Void OnEnter() { }
	// RVA: 0x232cf44 VA: 0x7594944f44
	protected override Void OnResume() { }
	// RVA: 0x232d2ec VA: 0x75949452ec
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x232c97c VA: 0x759494497c
	private Void _InitIfNot() { }
	// RVA: 0x232d390 VA: 0x7594945390
	private Void _OnBackClicked() { }
	// RVA: 0x232d4a4 VA: 0x75949454a4
	public Void .ctor() { }
	// RVA: 0x232d5fc VA: 0x75949455fc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x232d604 VA: 0x7594945604
	private Void <>xLuaBaseProxy_OnResume() { }
}
```