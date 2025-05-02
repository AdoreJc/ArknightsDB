# HandBookV2FavorMissionState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2FavorMissionStateBean _stateBean`

- `Boolean m_needRefresh`


## Methods

- `Void OnCollectionRequest(String)`

- `Void <OnCollectionRequest>b__5_0(ReceiveTeamCollectionRewardResponse)`

- `Void <>xLuaBaseProxy_OnPopup()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2FavorMissionState : PopupFloatState
{
	private HandBookV2FavorMissionStateBean _stateBean; // 0x70
	private Boolean m_needRefresh; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnPopup; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnCollectionRequest; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2ec9264 VA: 0x75954e1264
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ec92cc VA: 0x75954e12cc
	protected override Void OnPopup() { }
	// RVA: 0x2ec9408 VA: 0x75954e1408
	protected override Void OnResume() { }
	// RVA: 0x2ec9550 VA: 0x75954e1550
	public Void OnCollectionRequest(String id) { }
	// RVA: 0x2ec973c VA: 0x75954e173c
	public Void .ctor() { }
	// RVA: 0x2ec97ac VA: 0x75954e17ac
	private Void <OnCollectionRequest>b__5_0(ReceiveTeamCollectionRewardResponse response) { }
	// RVA: 0x2ec9838 VA: 0x75954e1838
	private Void <>xLuaBaseProxy_OnPopup() { }
	// RVA: 0x2ec9840 VA: 0x75954e1840
	private Void <>xLuaBaseProxy_OnResume() { }
}
```