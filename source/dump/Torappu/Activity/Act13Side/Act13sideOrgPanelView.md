# Act13sideOrgPanelView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `String _orgId`

- `Image _imgOrgLogo`

- `Image _imgOrgTitle`

- `Image _imgEmoji`

- `Text _textPrestige`

- `Text _textArchiveCount`

- `Text _textNewsCount`

- `Text _textAvgCount`

- `Transform _prestigeProgressContaniner`

- `Act13sidePrestigeProgressView _progressViewTemplate`

- `GameObject _activePartGo`

- `GameObject _lockPartGo`

- `Text _textUnlockTime`

- `String m_actId`

- `OrgData m_orgData`

- `Act13sidePrestigeProgressView m_progressView`

- `Single m_progressVal`

- `PrestigeRank m_currentRank`


## Methods

- `Void set_onRewardClick(Action`2)`

- `Void Render(String, Boolean)`

- `Tweener PlaySliderAnim()`

- `Void OnBtnRewardClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideOrgPanelView : MonoBehaviour, IHotfixable
{
	private String _orgId; // 0x18
	private Image _imgOrgLogo; // 0x20
	private Image _imgOrgTitle; // 0x28
	private Image _imgEmoji; // 0x30
	private Text _textPrestige; // 0x38
	private Text _textArchiveCount; // 0x40
	private Text _textNewsCount; // 0x48
	private Text _textAvgCount; // 0x50
	private Transform _prestigeProgressContaniner; // 0x58
	private Act13sidePrestigeProgressView _progressViewTemplate; // 0x60
	private GameObject _activePartGo; // 0x68
	private GameObject _lockPartGo; // 0x70
	private Text _textUnlockTime; // 0x78
	private String m_actId; // 0x80
	private OrgData m_orgData; // 0x88
	private Act13sidePrestigeProgressView m_progressView; // 0x90
	private Single m_progressVal; // 0x98
	private PrestigeRank m_currentRank; // 0x9c
	private Action`2 <onRewardClick>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_onRewardClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onRewardClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_PlaySliderAnim; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnRewardClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`2 onRewardClick { get; set; }

	// RVA: 0x34431a0 VA: 0x7595a5b1a0
	private Action`2 get_onRewardClick() { }
	// RVA: 0x343610c VA: 0x7595a4e10c
	public Void set_onRewardClick(Action`2 value) { }
	// RVA: 0x3436190 VA: 0x7595a4e190
	public Void Render(String actId, Boolean needSliderAnim) { }
	// RVA: 0x3435fd8 VA: 0x7595a4dfd8
	public Tweener PlaySliderAnim() { }
	// RVA: 0x34433b0 VA: 0x7595a5b3b0
	public Void OnBtnRewardClick() { }
	// RVA: 0x3443454 VA: 0x7595a5b454
	public Void .ctor() { }
}
```