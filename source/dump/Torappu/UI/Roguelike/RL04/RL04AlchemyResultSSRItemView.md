# RL04AlchemyResultSSRItemView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _imgSsrReward`

- `Text _txtSsrRewardName`

- `Text _txtSsrRewardDesc`

- `GameObject _objMultiChoiceClaimBtn`

- `Int32 m_index`

- `Boolean m_isMulti`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(RL04AlchemyResultSsrItemViewModel)`

- `Void OnClaimBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyResultSSRItemView : MonoBehaviour, IHotfixable
{
	private Image _imgSsrReward; // 0x18
	private Text _txtSsrRewardName; // 0x20
	private Text _txtSsrRewardDesc; // 0x28
	private GameObject _objMultiChoiceClaimBtn; // 0x30
	private Int32 m_index; // 0x38
	private Boolean m_isMulti; // 0x3c
	private UIStateFinder m_stateFinder; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClaimBtnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b0b048 VA: 0x7595123048
	public Void Render(RL04AlchemyResultSsrItemViewModel ssrRewardItemViewModel) { }
	// RVA: 0x2b0b1d4 VA: 0x75951231d4
	public Void OnClaimBtnClick() { }
	// RVA: 0x2b0b2e0 VA: 0x75951232e0
	public Void .ctor() { }
}
```