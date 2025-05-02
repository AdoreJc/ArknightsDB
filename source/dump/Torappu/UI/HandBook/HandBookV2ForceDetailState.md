# HandBookV2ForceDetailState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2ForceDetailStateBean _stateBean`

- `HandBookV2GroupDetailView _view`


## Methods

- `Void OnDetail()`

- `Void OnClick(HandBookV2MapCardView)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2ForceDetailState : PopupFadeState
{
	private HandBookV2ForceDetailStateBean _stateBean; // 0x70
	private HandBookV2GroupDetailView _view; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnDetail; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ec9848 VA: 0x75954e1848
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ec98b0 VA: 0x75954e18b0
	public Void OnDetail() { }
	// RVA: 0x2ec99bc VA: 0x75954e19bc
	public Void OnClick(HandBookV2MapCardView cardView) { }
	// RVA: 0x2ec9cd4 VA: 0x75954e1cd4
	protected override Void OnEnter() { }
	// RVA: 0x2ec9fd8 VA: 0x75954e1fd8
	protected override Void OnResume() { }
	// RVA: 0x2eca284 VA: 0x75954e2284
	public Void .ctor() { }
	// RVA: 0x2eca2f4 VA: 0x75954e22f4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2eca2fc VA: 0x75954e22fc
	private Void <>xLuaBaseProxy_OnResume() { }
}
```