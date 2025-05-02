# Act24sideStageRewardDetailItem

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMeldingItemView _meldingItemPrefab`

- `RectTransform _meldingItemParent`

- `GameObject _alwaysPart`

- `GameObject _almostPart`

- `GameObject _sometimePart`

- `GameObject _usualPart`

- `GameObject _oftenPart`

- `GameObject _alreadyGetPart`

- `GameObject _threeStarGetPart`

- `Act24sideMeldingItemView m_meldingItemView`


## Methods

- `Void Render(String, Act24sideMeldingItemViewModel, DisplayDetailRewards, Boolean, Boolean)`

- `Void _RenderTag(DisplayDetailRewards, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideStageRewardDetailItem : MonoBehaviour, IHotfixable
{
	private Act24sideMeldingItemView _meldingItemPrefab; // 0x18
	private RectTransform _meldingItemParent; // 0x20
	private GameObject _alwaysPart; // 0x28
	private GameObject _almostPart; // 0x30
	private GameObject _sometimePart; // 0x38
	private GameObject _usualPart; // 0x40
	private GameObject _oftenPart; // 0x48
	private GameObject _alreadyGetPart; // 0x50
	private GameObject _threeStarGetPart; // 0x58
	private Act24sideMeldingItemView m_meldingItemView; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderTag; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32e2994 VA: 0x75958fa994
	public Void Render(String actId, Act24sideMeldingItemViewModel viewModel, DisplayDetailRewards rewardData, Boolean getFlag, Boolean completeFlag) { }
	// RVA: 0x32e2b04 VA: 0x75958fab04
	private Void _RenderTag(DisplayDetailRewards rewardData, Boolean getFlag, Boolean completeFlag) { }
	// RVA: 0x32e2cd8 VA: 0x75958facd8
	public Void .ctor() { }
}
```