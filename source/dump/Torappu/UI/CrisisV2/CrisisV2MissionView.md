# CrisisV2MissionView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `GameObject _claimAllBtnGo`

- `SimpleLayoutContent _missionContent`

- `ScrollRect _missionRect`

- `CrisisV2MissionViewModel m_viewModel`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `UIStateFinder m_stateFinder`

- `Int32 m_cachedSequenceNum`


## Methods

- `Void _InitIfNot()`

- `Void OnClaimAllClicked()`

- `Void OnCloseSelfClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MissionView : DataBinder`1, IHotfixable
{
	private GameObject _claimAllBtnGo; // 0x20
	private SimpleLayoutContent _missionContent; // 0x28
	private ScrollRect _missionRect; // 0x30
	private CrisisV2MissionViewModel m_viewModel; // 0x38
	private Boolean m_hasInited; // 0x40
	private Adapter m_adapter; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private Int32 m_cachedSequenceNum; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnClaimAllClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnCloseSelfClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2bfcae8 VA: 0x7595214ae8
	private Void _InitIfNot() { }
	// RVA: 0x2bfcd2c VA: 0x7595214d2c
	public override Void OnValueChanged(CrisisV2MissionProperty property) { }
	// RVA: 0x2bfce44 VA: 0x7595214e44
	public Void OnClaimAllClicked() { }
	// RVA: 0x2bfcee8 VA: 0x7595214ee8
	public Void OnCloseSelfClicked() { }
	// RVA: 0x2bfcf8c VA: 0x7595214f8c
	public Void .ctor() { }
}
```