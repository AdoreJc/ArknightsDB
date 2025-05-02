# RecruitGachaRuleDouble

**Namespace:** `Torappu.UI.Recruit.GachaPlugins`


## Fields

- `Text _txtCountCaption`

- `Text _txtShowCount`

- `GameObject _panelShowCount`

- `Image _imgCharAvatar`

- `GameObject _panelGuarantee`

- `GameObject _firstGuranteeGO`

- `GameObject _secondGuranteeGO`

- `String m_cacheCharId`


## Methods

- `Boolean _IsRuleValid(GachaRuleType)`

- `Void _RenderGuaranteePart(PlayerDoubleGacha)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit.GachaPlugins
public class RecruitGachaRuleDouble : RecruitGachaItemPlugin
{
	private Text _txtCountCaption; // 0x18
	private Text _txtShowCount; // 0x20
	private GameObject _panelShowCount; // 0x28
	private Image _imgCharAvatar; // 0x30
	private GameObject _panelGuarantee; // 0x38
	private GameObject _firstGuranteeGO; // 0x40
	private GameObject _secondGuranteeGO; // 0x48
	private String m_cacheCharId; // 0x50
	private static DelegateBridge __Hotfix0_OnRefreshData; // 0x0
	private static DelegateBridge __Hotfix0__IsRuleValid; // 0x8
	private static DelegateBridge __Hotfix0__RenderGuaranteePart; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2722f10 VA: 0x7594d3af10
	protected override Void OnRefreshData(RecruitGachaItemViewBase host) { }
	// RVA: 0x27230e8 VA: 0x7594d3b0e8
	private Boolean _IsRuleValid(GachaRuleType gachaRuleType) { }
	// RVA: 0x272316c VA: 0x7594d3b16c
	private Void _RenderGuaranteePart(PlayerDoubleGacha playerDoubleParam) { }
	// RVA: 0x2723348 VA: 0x7594d3b348
	public Void .ctor() { }
}
```