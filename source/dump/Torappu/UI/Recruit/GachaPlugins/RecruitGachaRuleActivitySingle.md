# RecruitGachaRuleActivitySingle

**Namespace:** `Torappu.UI.Recruit.GachaPlugins`


## Fields

- `Text _txtCountdownCaption`

- `Text _txtCountdown`

- `GameObject _panelCountdownTips`

- `Image _imgCharAvatar`

- `GameObject _panelGuarantee`

- `String m_cachedCharId`


## Methods

- `CharUISkinStruct _GetSkinStruct(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit.GachaPlugins
public class RecruitGachaRuleActivitySingle : RecruitGachaItemPlugin
{
	private Text _txtCountdownCaption; // 0x18
	private Text _txtCountdown; // 0x20
	private GameObject _panelCountdownTips; // 0x28
	private Image _imgCharAvatar; // 0x30
	private GameObject _panelGuarantee; // 0x38
	private String m_cachedCharId; // 0x40
	private static DelegateBridge __Hotfix0_OnRefreshData; // 0x0
	private static DelegateBridge __Hotfix0__GetSkinStruct; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x27229c8 VA: 0x7594d3a9c8
	protected override Void OnRefreshData(RecruitGachaItemViewBase host) { }
	// RVA: 0x2722ce4 VA: 0x7594d3ace4
	private CharUISkinStruct _GetSkinStruct(String charId) { }
	// RVA: 0x2722e68 VA: 0x7594d3ae68
	public Void .ctor() { }
}
```