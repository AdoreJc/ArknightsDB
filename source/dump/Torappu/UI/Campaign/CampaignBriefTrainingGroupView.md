# CampaignBriefTrainingGroupView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Image _imageDashLine`

- `Image _imageDashLineAllOpen`

- `RectTransform _panelCurrent`

- `RectTransform _panelCurrentAllOpen`

- `RectTransform _panelNext`

- `RectTransform _panelNextAllOpen`

- `Text _textRemainTime`

- `SimpleLayoutContent _stageInfoContent`

- `Boolean m_inited`

- `StageInfoAdapter m_stageInfoAdapter`


## Methods

- `Void Render(CampaignBriefTrainingViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignBriefTrainingGroupView : MonoBehaviour, IHotfixable
{
	private Image _imageDashLine; // 0x18
	private Image _imageDashLineAllOpen; // 0x20
	private RectTransform _panelCurrent; // 0x28
	private RectTransform _panelCurrentAllOpen; // 0x30
	private RectTransform _panelNext; // 0x38
	private RectTransform _panelNextAllOpen; // 0x40
	private Text _textRemainTime; // 0x48
	private SimpleLayoutContent _stageInfoContent; // 0x50
	private Boolean m_inited; // 0x58
	private StageInfoAdapter m_stageInfoAdapter; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2dc662c VA: 0x75953de62c
	public Void Render(CampaignBriefTrainingViewModel viewModel) { }
	// RVA: 0x2dc6894 VA: 0x75953de894
	private Void _InitIfNot() { }
	// RVA: 0x2dc69ac VA: 0x75953de9ac
	public Void .ctor() { }
}
```