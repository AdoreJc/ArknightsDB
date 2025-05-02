# SpCharMissionObjView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single _itemCardScale`

- `Image _imageCond`

- `Text _textCond`

- `RectTransform _rewardsContainer`

- `RectTransform _rewardPlaceHolder`

- `RectTransform _panelRewards`

- `RectTransform _panelConfirm`

- `RectTransform _panelComplete`

- `SpCharMissionObjViewModel m_cacheModel`


## Methods

- `Void set_onGetRewardClicked(Action`1)`

- `Void Render(SpCharMissionObjViewModel)`

- `Void EventOnGetRewardClicked()`

- `Void _EventOnItemClicked(Int32)`

- `Sprite _GetSprite(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class SpCharMissionObjView : MonoBehaviour, IHotfixable
{
	private List`1 _spriteDatas; // 0x18
	private Single _itemCardScale; // 0x20
	private Image _imageCond; // 0x28
	private Text _textCond; // 0x30
	private RectTransform _rewardsContainer; // 0x38
	private RectTransform _rewardPlaceHolder; // 0x40
	private RectTransform _panelRewards; // 0x48
	private RectTransform _panelConfirm; // 0x50
	private RectTransform _panelComplete; // 0x58
	private SpCharMissionObjViewModel m_cacheModel; // 0x60
	private List`1 m_uiItemCards; // 0x68
	private Action`1 <onGetRewardClicked>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onGetRewardClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onGetRewardClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnGetRewardClicked; // 0x18
	private static DelegateBridge __Hotfix0__EventOnItemClicked; // 0x20
	private static DelegateBridge __Hotfix0__GetSprite; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Action`1 onGetRewardClicked { get; set; }

	// RVA: 0x2d8c370 VA: 0x75953a4370
	public Action`1 get_onGetRewardClicked() { }
	// RVA: 0x2d8bd3c VA: 0x75953a3d3c
	public Void set_onGetRewardClicked(Action`1 value) { }
	// RVA: 0x2d8bdc0 VA: 0x75953a3dc0
	public Void Render(SpCharMissionObjViewModel viewModel) { }
	// RVA: 0x2d8c520 VA: 0x75953a4520
	public Void EventOnGetRewardClicked() { }
	// RVA: 0x2d8c5c0 VA: 0x75953a45c0
	private Void _EventOnItemClicked(Int32 index) { }
	// RVA: 0x2d8c3d8 VA: 0x75953a43d8
	private Sprite _GetSprite(String id) { }
	// RVA: 0x2d8c69c VA: 0x75953a469c
	public Void .ctor() { }
}
```