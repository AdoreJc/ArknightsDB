# CharacterEvolveDetailView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _detailButton`

- `CharacterEvolveDetailNewAttackRangeView _newAttackRange`

- `CharacterEvolveDetailNormalText _normalText`

- `CharacterEvolveDetailSingleLineText _singleLineText`

- `CharacterEvolveDetailNewSkillView _skillView`

- `GameObject _closeButton`


## Methods

- `Void OnBack()`

- `Void OnClick()`

- `IEnumerator _BackAnim()`

- `IEnumerator _EffectAnim()`

- `Void Render(CharacterInfoEvolveInfoViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterEvolveDetailView : MonoBehaviour, IHotfixable
{
	private GameObject _detailButton; // 0x18
	private CharacterEvolveDetailNewAttackRangeView _newAttackRange; // 0x20
	private CharacterEvolveDetailNormalText _normalText; // 0x28
	private CharacterEvolveDetailSingleLineText _singleLineText; // 0x30
	private CharacterEvolveDetailNewSkillView _skillView; // 0x38
	private GameObject _closeButton; // 0x40
	private List`1 m_detailList; // 0x48
	private static DelegateBridge __Hotfix0_OnBack; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0__BackAnim; // 0x10
	private static DelegateBridge __Hotfix0__EffectAnim; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d6f2a8 VA: 0x75953872a8
	public Void OnBack() { }
	// RVA: 0x2d6f3dc VA: 0x75953873dc
	public Void OnClick() { }
	// RVA: 0x2d6f330 VA: 0x7595387330
	private IEnumerator _BackAnim() { }
	// RVA: 0x2d6f464 VA: 0x7595387464
	private IEnumerator _EffectAnim() { }
	// RVA: 0x2d6f560 VA: 0x7595387560
	public Void Render(CharacterInfoEvolveInfoViewModel viewModel) { }
	// RVA: 0x2d6fe1c VA: 0x7595387e1c
	public Void .ctor() { }
}
```