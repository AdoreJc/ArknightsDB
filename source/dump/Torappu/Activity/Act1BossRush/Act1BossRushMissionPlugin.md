# Act1BossRushMissionPlugin

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `GameObject _objRewardsBgDec`

- `UIAtlasImage _imgRewardsBg1`

- `UIAtlasImage _imgRewardsBg2`

- `Color _availRewardBgColor`

- `Color _notAvailRewardBgColor`

- `GameObject _objRewardAdapter`

- `GameObject _objRelicParent`

- `GameObject _objRelicNormalBg`

- `GameObject _objRelicActiveBg`

- `Image _relicIcon`

- `Text _textRelicName`

- `Color _availRelicColor`

- `Color _notAvailRelicColor`

- `Text _textMissionDesc`

- `Color _availMissionColor`

- `Color _notAvailMissionColor`

- `Text _textProgressDetail`

- `TemplateMissionViewModel m_cacheViewModel`


## Methods

- `Void ApplyDataBundle(TemplateMissionViewModel)`

- `Void RenderCoro(Action)`

- `Boolean IsAvailClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushMissionPlugin : MonoBehaviour, TemplateActivityMissionPlugin, IHotfixable
{
	private GameObject _objRewardsBgDec; // 0x18
	private UIAtlasImage _imgRewardsBg1; // 0x20
	private UIAtlasImage _imgRewardsBg2; // 0x28
	private Color _availRewardBgColor; // 0x30
	private Color _notAvailRewardBgColor; // 0x40
	private GameObject _objRewardAdapter; // 0x50
	private GameObject _objRelicParent; // 0x58
	private GameObject _objRelicNormalBg; // 0x60
	private GameObject _objRelicActiveBg; // 0x68
	private Image _relicIcon; // 0x70
	private Text _textRelicName; // 0x78
	private Color _availRelicColor; // 0x80
	private Color _notAvailRelicColor; // 0x90
	private Text _textMissionDesc; // 0xa0
	private Color _availMissionColor; // 0xa8
	private Color _notAvailMissionColor; // 0xb8
	private Text _textProgressDetail; // 0xc8
	private const String COLOR_PROGRESS_AVAIL; // 0x0
	private const String COLOR_PROGRESS_NOT_AVAIL; // 0x0
	private TemplateMissionViewModel m_cacheViewModel; // 0xd0
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x0
	private static DelegateBridge __Hotfix0_RenderCoro; // 0x8
	private static DelegateBridge __Hotfix0_IsAvailClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3194d40 VA: 0x75957acd40
	public Void ApplyDataBundle(TemplateMissionViewModel missionData) { }
	// RVA: 0x3194dc4 VA: 0x75957acdc4
	public Void RenderCoro(Action commonRender) { }
	// RVA: 0x3195298 VA: 0x75957ad298
	public Boolean IsAvailClick() { }
	// RVA: 0x3195300 VA: 0x75957ad300
	public Void .ctor() { }
}
```