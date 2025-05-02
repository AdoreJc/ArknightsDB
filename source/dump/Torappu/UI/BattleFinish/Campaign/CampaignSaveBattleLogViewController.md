# CampaignSaveBattleLogViewController

**Namespace:** `Torappu.UI.BattleFinish.Campaign`


## Fields

- `UIBlurFloatPanel _backImage`

- `CampaignSaveBattleLogPanel _newLogPanel`

- `CampaignSaveBattleLogPanel _oldLogPanel`

- `Coroutine m_coroutine`


## Methods

- `Void OnConfirmBtnClicked()`

- `Void _Show(BattleLog, BattleLog, Action`1)`

- `IEnumerator _HideAndDestroy()`

- `Void _ChooseDefaultLogSmartly(BattleLog, BattleLog)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish.Campaign
public class CampaignSaveBattleLogViewController : MonoBehaviour, IHotfixable
{
	private UIBlurFloatPanel _backImage; // 0x18
	private CampaignSaveBattleLogPanel _newLogPanel; // 0x20
	private CampaignSaveBattleLogPanel _oldLogPanel; // 0x28
	private Action`1 m_callback; // 0x30
	private Coroutine m_coroutine; // 0x38
	private static DelegateBridge __Hotfix0_OnConfirmBtnClicked; // 0x0
	private static DelegateBridge __Hotfix0__Show; // 0x8
	private static DelegateBridge __Hotfix0__HideAndDestroy; // 0x10
	private static DelegateBridge __Hotfix0__ChooseDefaultLogSmartly; // 0x18
	private static DelegateBridge __Hotfix0_OpenCampaignSaveBattleLogPanel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2e97a00 VA: 0x75954afa00
	public Void OnConfirmBtnClicked() { }
	// RVA: 0x2e97bb4 VA: 0x75954afbb4
	private Void _Show(BattleLog newLog, BattleLog oldLog, Action`1 callback) { }
	// RVA: 0x2e97b08 VA: 0x75954afb08
	private IEnumerator _HideAndDestroy() { }
	// RVA: 0x2e97d30 VA: 0x75954afd30
	private Void _ChooseDefaultLogSmartly(BattleLog newLog, BattleLog oldLog) { }
	// RVA: 0x2e97e50 VA: 0x75954afe50
	public static Boolean OpenCampaignSaveBattleLogPanel(CampaignSaveBattleLogViewController prefab, Transform parent, Action`1 onFinished) { }
	// RVA: 0x2e98138 VA: 0x75954b0138
	public Void .ctor() { }
}
```