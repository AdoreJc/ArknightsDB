# Act1BossRushMissionInfoHolder

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `Text _textProgress`

- `GameObject _objCanClaimAll`

- `GameObject _objCantClaimAll`

- `Action onClaimAllMissionClick`


## Methods

- `Void _RefreshView(TemplateActivityViewModel)`

- `Void OnViewModelRefresh(TemplateActivityViewModel)`

- `Void EventClaimAllMissionClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushMissionInfoHolder : MonoBehaviour, IBaseActViewBinder, IHotfixable
{
	private Text _textProgress; // 0x18
	private GameObject _objCanClaimAll; // 0x20
	private GameObject _objCantClaimAll; // 0x28
	public Action onClaimAllMissionClick; // 0x30
	private const String COLOR_PROGRESS; // 0x0
	private static DelegateBridge __Hotfix0__RefreshView; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge __Hotfix0_EventClaimAllMissionClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31949fc VA: 0x75957ac9fc
	private Void _RefreshView(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3194bcc VA: 0x75957acbcc
	public Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3194c4c VA: 0x75957acc4c
	public Void EventClaimAllMissionClick() { }
	// RVA: 0x3194cd0 VA: 0x75957accd0
	public Void .ctor() { }
}
```