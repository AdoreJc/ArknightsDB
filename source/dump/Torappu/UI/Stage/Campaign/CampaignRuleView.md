# CampaignRuleView

**Namespace:** `Torappu.UI.Stage.Campaign`


## Fields

- `Text _textCode`

- `Text _textName`

- `Text _textStageType`

- `Text _textTip`

- `CampaignLadderItemView _killCntItem`

- `CampaignLadderItemView _apRetItem`

- `CampaignLadderItemView _goldItem`

- `Boolean m_hasInited`

- `LadderItem m_killCntLadder`

- `LadderItem m_apRetLadder`

- `LadderItem m_diamondGainLadder`


## Methods

- `Void RenderView(String, CampaignStageType)`

- `Void _UpdateCodeAndName(String, CampaignStageType)`

- `Void _UpdateLadderList(String, CampaignStageType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.Campaign
public class CampaignRuleView : MonoBehaviour, IHotfixable
{
	private Text _textCode; // 0x18
	private Text _textName; // 0x20
	private Text _textStageType; // 0x28
	private Text _textTip; // 0x30
	private CampaignLadderItemView _killCntItem; // 0x38
	private CampaignLadderItemView _apRetItem; // 0x40
	private CampaignLadderItemView _goldItem; // 0x48
	private Boolean m_hasInited; // 0x50
	private LadderItem m_killCntLadder; // 0x58
	private LadderItem m_apRetLadder; // 0x60
	private LadderItem m_diamondGainLadder; // 0x68
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0__UpdateCodeAndName; // 0x8
	private static DelegateBridge __Hotfix0__UpdateLadderList; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fe205c VA: 0x75955fa05c
	public Void RenderView(String stageId, CampaignStageType stageType) { }
	// RVA: 0x2fe20f8 VA: 0x75955fa0f8
	private Void _UpdateCodeAndName(String stageId, CampaignStageType stageType) { }
	// RVA: 0x2fe2394 VA: 0x75955fa394
	private Void _UpdateLadderList(String stageId, CampaignStageType stageType) { }
	// RVA: 0x2fe2838 VA: 0x75955fa838
	public Void .ctor() { }
}
```