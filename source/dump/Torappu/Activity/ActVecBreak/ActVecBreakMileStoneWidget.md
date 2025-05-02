# ActVecBreakMileStoneWidget

**Namespace:** `Torappu.Activity.ActVecBreak`


## Fields

- `Text _progressTextCurrent`

- `Text _progressTextTotal`

- `Slider _progressBar`

- `Text _curLevelText`

- `GameObject _isMaxTag`

- `Text _skinRewardInfo`

- `Text _skinName`

- `Text _skinCharName`

- `Text _avatarRewardInfo`

- `Text _avatarName`

- `Image _imgMilestoneAvatar`

- `UIItemViewModel m_avatarItemViewModel`


## Methods

- `Void _TryLoadAvatar(TemplateActivityMilestoneGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActVecBreak
public class ActVecBreakMileStoneWidget : TemplateActivityMilestoneWidget
{
	private Text _progressTextCurrent; // 0x18
	private Text _progressTextTotal; // 0x20
	private Slider _progressBar; // 0x28
	private Text _curLevelText; // 0x30
	private GameObject _isMaxTag; // 0x38
	private Text _skinRewardInfo; // 0x40
	private Text _skinName; // 0x48
	private Text _skinCharName; // 0x50
	private Text _avatarRewardInfo; // 0x58
	private Text _avatarName; // 0x60
	private Image _imgMilestoneAvatar; // 0x68
	private UIItemViewModel m_avatarItemViewModel; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__TryLoadAvatar; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30d7e1c VA: 0x75956efe1c
	public override Void Render(TemplateActivityMilestoneGroupViewModel milestoneViewModel) { }
	// RVA: 0x30d84a4 VA: 0x75956f04a4
	private Void _TryLoadAvatar(TemplateActivityMilestoneGroupViewModel mileStoneViewModel) { }
	// RVA: 0x30d869c VA: 0x75956f069c
	public Void .ctor() { }
}
```