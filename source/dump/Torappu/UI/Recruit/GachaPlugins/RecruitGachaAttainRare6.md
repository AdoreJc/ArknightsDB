# RecruitGachaAttainRare6

**Namespace:** `Torappu.UI.Recruit.GachaPlugins`


## Fields

- `GameObject _panelSecure6`

- `PlayerParam m_playerParam`

- `String m_cachedPoolId`

- `Boolean m_hasInited`


## Methods

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void _Render()`

- `Void _InitIfNot(String)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit.GachaPlugins
public class RecruitGachaAttainRare6 : RecruitGachaItemPlugin, IPlayerDataListener, IHotfixable
{
	private GameObject _panelSecure6; // 0x18
	private PlayerParam m_playerParam; // 0x20
	private String m_cachedPoolId; // 0x28
	private Boolean m_hasInited; // 0x30
	private static DelegateBridge __Hotfix0_OnRefreshData; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x27212f0 VA: 0x7594d392f0
	protected override Void OnRefreshData(RecruitGachaItemViewBase host) { }
	// RVA: 0x2721478 VA: 0x7594d39478
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x2721570 VA: 0x7594d39570
	public Void OnPlayerDataChanged() { }
	// RVA: 0x27215d8 VA: 0x7594d395d8
	private Void _Render() { }
	// RVA: 0x2721388 VA: 0x7594d39388
	private Void _InitIfNot(String gachaPoolId) { }
	// RVA: 0x2721a90 VA: 0x7594d39a90
	private Void OnDestroy() { }
	// RVA: 0x2721afc VA: 0x7594d39afc
	public Void .ctor() { }
}
```