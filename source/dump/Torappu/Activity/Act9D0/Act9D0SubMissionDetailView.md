# Act9D0SubMissionDetailView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Image _icon`

- `GameObject _ableToGet`

- `GameObject _alreadyGet`

- `Slider _slider`

- `Text _schedule`

- `Text _titleText`

- `Text _contentText`

- `Transform _cardContainer`

- `Single _scaleFactor`


## Methods

- `Void Render(SubMissionViewModel)`

- `Void _RenderMissionRewards(SubMissionViewModel)`

- `UIItemCard _CreateItemCard()`

- `Void _OnRewardItemClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0SubMissionDetailView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private GameObject _ableToGet; // 0x20
	private GameObject _alreadyGet; // 0x28
	private Slider _slider; // 0x30
	private Text _schedule; // 0x38
	private Text _titleText; // 0x40
	private Text _contentText; // 0x48
	private List`1 _iconList; // 0x50
	private Transform _cardContainer; // 0x58
	private Single _scaleFactor; // 0x60
	private List`1 m_itemCardList; // 0x68
	private List`1 m_rewardList; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderMissionRewards; // 0x8
	private static DelegateBridge __Hotfix0__CreateItemCard; // 0x10
	private static DelegateBridge __Hotfix0__OnRewardItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31aad10 VA: 0x75957c2d10
	public Void Render(SubMissionViewModel viewModel) { }
	// RVA: 0x31aafe8 VA: 0x75957c2fe8
	private Void _RenderMissionRewards(SubMissionViewModel viewModel) { }
	// RVA: 0x31ab3f8 VA: 0x75957c33f8
	private UIItemCard _CreateItemCard() { }
	// RVA: 0x31ab5b0 VA: 0x75957c35b0
	private Void _OnRewardItemClicked(Int32 index) { }
	// RVA: 0x31ab6fc VA: 0x75957c36fc
	public Void .ctor() { }
}
```