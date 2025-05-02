# CampaignFastBattleConfirmView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Text _textCount`

- `Text _textShard`

- `GameObject _objAPNote`

- `Slider _slideShardFrom`

- `Slider _slideShardTo`

- `GameObject _litPrgShardFrom`

- `Text _textShardFrom`

- `Text _textShardTo`

- `Text _textConfirm`

- `SimpleLayoutContent _layoutCostTkt`

- `InitOptions m_initOptions`

- `FastCampaignConfirmViewModel m_viewModel`

- `TktAdapter m_tktAdapter`

- `Boolean m_isInited`


## Methods

- `Void Init(InitOptions)`

- `Void Render(FastCampaignConfirmViewModel)`

- `Void EventOnStartClicked()`

- `Void EventOnCancelClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignFastBattleConfirmView : MonoBehaviour, IHotfixable
{
	private const String TARGET_SHARD_FMT; // 0x0
	private const Single HIDE_LIT_THRESHOLD; // 0x0
	private Text _textCount; // 0x18
	private Text _textShard; // 0x20
	private GameObject _objAPNote; // 0x28
	private Slider _slideShardFrom; // 0x30
	private Slider _slideShardTo; // 0x38
	private GameObject _litPrgShardFrom; // 0x40
	private Text _textShardFrom; // 0x48
	private Text _textShardTo; // 0x50
	private Text _textConfirm; // 0x58
	private SimpleLayoutContent _layoutCostTkt; // 0x60
	private InitOptions m_initOptions; // 0x68
	private FastCampaignConfirmViewModel m_viewModel; // 0x78
	private TktAdapter m_tktAdapter; // 0x80
	private Boolean m_isInited; // 0x88
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_EventOnStartClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2ddb704 VA: 0x75953f3704
	public Void Init(InitOptions options) { }
	// RVA: 0x2ddb8a0 VA: 0x75953f38a0
	public Void Render(FastCampaignConfirmViewModel viewModel) { }
	// RVA: 0x2ddbd4c VA: 0x75953f3d4c
	public Void EventOnStartClicked() { }
	// RVA: 0x2ddbdd0 VA: 0x75953f3dd0
	public Void EventOnCancelClicked() { }
	// RVA: 0x2ddbe54 VA: 0x75953f3e54
	public Void .ctor() { }
}
```