# StagePreviewCampaignSummaryInfoView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Text _campaignBreakProgText`

- `RectTransform _highlight`

- `EasyInstancePool _breakRewardTogglePool`


## Methods

- `Void Render(CampaignStateViewModel)`

- `Void _RenderHighlightAndTrackPoint(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class StagePreviewCampaignSummaryInfoView : MonoBehaviour, IHotfixable
{
	private Text _campaignBreakProgText; // 0x18
	private RectTransform _highlight; // 0x20
	private EasyInstancePool _breakRewardTogglePool; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderHighlightAndTrackPoint; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2e4a56c VA: 0x759546256c
	public Void Render(CampaignStateViewModel campModel) { }
	// RVA: 0x2e4a80c VA: 0x759546280c
	private Void _RenderHighlightAndTrackPoint(Boolean hasUnconfirmed) { }
	// RVA: 0x2e4a8a0 VA: 0x75954628a0
	public Void .ctor() { }
}
```