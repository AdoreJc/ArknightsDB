# CampaignDisplayBattleLogViewController

**Namespace:** `Torappu.UI.BattleFinish.Campaign`


## Fields

- `UIBlurFloatPanel _backImage`

- `CampaignSaveBattleLogPanel _logPanel`

- `Action m_callback`


## Methods

- `Void OnConfirmBtnClicked()`

- `Void _Show(BattleLog, Action)`

- `IEnumerator _HideAndDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish.Campaign
public class CampaignDisplayBattleLogViewController : MonoBehaviour
{
	private UIBlurFloatPanel _backImage; // 0x18
	private CampaignSaveBattleLogPanel _logPanel; // 0x20
	private Action m_callback; // 0x28


	// RVA: 0x2e9652c VA: 0x75954ae52c
	public Void OnConfirmBtnClicked() { }
	// RVA: 0x2e96634 VA: 0x75954ae634
	private Void _Show(BattleLog newLog, Action callback) { }
	// RVA: 0x2e965c0 VA: 0x75954ae5c0
	private IEnumerator _HideAndDestroy() { }
	// RVA: 0x2e96a24 VA: 0x75954aea24
	public static Void OpenCampaignDisplayBattleLogPanel(CampaignDisplayBattleLogViewController prefab, Transform parent, Action onFinished) { }
	// RVA: 0x2e96bd8 VA: 0x75954aebd8
	public Void .ctor() { }
}
```