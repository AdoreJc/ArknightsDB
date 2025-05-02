# RecruitNewbeeGachaItemView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _remainCount`

- `CanvasGroup _alphaGachaPart`

- `CanvasGroup _alphaTenGachaPart`

- `GameObject _lockedGachaIcon`

- `GameObject _lockedTenGachaIcon`

- `Single _gachaAlpha`

- `NewbeeGachaPoolClientData m_data`


## Methods

- `Void OnRecruitOnce()`

- `Void OnRecruitTen()`

- `Void ApplyData(Int32, NewbeeGachaPoolClientData)`

- `String <>xLuaBaseProxy_get_gachaPoolId()`

- `Void <>xLuaBaseProxy_OnRefreshData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitNewbeeGachaItemView : RecruitGachaItemView
{
	private Text _remainCount; // 0x1d8
	private CanvasGroup _alphaGachaPart; // 0x1e0
	private CanvasGroup _alphaTenGachaPart; // 0x1e8
	private GameObject _lockedGachaIcon; // 0x1f0
	private GameObject _lockedTenGachaIcon; // 0x1f8
	private Single _gachaAlpha; // 0x200
	private NewbeeGachaPoolClientData m_data; // 0x208
	private static DelegateBridge __Hotfix0_get_gachaPoolId; // 0x0
	private static DelegateBridge __Hotfix0_OnRecruitOnce; // 0x8
	private static DelegateBridge __Hotfix0_OnRecruitTen; // 0x10
	private static DelegateBridge __Hotfix0_ApplyData; // 0x18
	private static DelegateBridge __Hotfix0_OnRefreshData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override String gachaPoolId { get; }

	// RVA: 0x271c228 VA: 0x7594d34228
	public override String get_gachaPoolId() { }
	// RVA: 0x271c2bc VA: 0x7594d342bc
	public Void OnRecruitOnce() { }
	// RVA: 0x271c35c VA: 0x7594d3435c
	public Void OnRecruitTen() { }
	// RVA: 0x271c44c VA: 0x7594d3444c
	public Void ApplyData(Int32 index, NewbeeGachaPoolClientData data) { }
	// RVA: 0x271c694 VA: 0x7594d34694
	protected override Void OnRefreshData() { }
	// RVA: 0x271c85c VA: 0x7594d3485c
	public Void .ctor() { }
	// RVA: 0x271c8d8 VA: 0x7594d348d8
	private String <>xLuaBaseProxy_get_gachaPoolId() { }
	// RVA: 0x271c8e0 VA: 0x7594d348e0
	private Void <>xLuaBaseProxy_OnRefreshData() { }
}
```