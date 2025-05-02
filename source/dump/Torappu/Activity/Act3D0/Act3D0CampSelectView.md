# Act3D0CampSelectView

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Act3D0CampDetailView _detailView`

- `GameObject _selectView`

- `Act3D0CampSelectResultView _resultView`

- `FadeSwitchTween m_selectViewTween`

- `Act3D0CampGroupViewModel m_campGroupModel`

- `Action onCampResultConfirmed`


## Methods

- `Void Render(String)`

- `Void ShowSelectResult()`

- `IEnumerator _SelectResultEffectCoroutine()`

- `Void _TriggerCampBGMPreview(String)`

- `Void EventOnCampButtonClicked(String)`

- `Void <Render>b__8_0(String)`

- `Void <Render>b__8_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0CampSelectView : MonoBehaviour, IHotfixable
{
	private const String CAMP_BGM_PREVIEW_SUFFIX; // 0x0
	private Act3D0CampDetailView _detailView; // 0x18
	private GameObject _selectView; // 0x20
	private Act3D0CampSelectResultView _resultView; // 0x28
	private FadeSwitchTween m_selectViewTween; // 0x30
	private Act3D0CampGroupViewModel m_campGroupModel; // 0x38
	public Action`1 onCampSelected; // 0x40
	public Action onCampResultConfirmed; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ShowSelectResult; // 0x8
	private static DelegateBridge __Hotfix0__SelectResultEffectCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__TriggerCampBGMPreview; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCampButtonClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x322cdb0 VA: 0x7595844db0
	public Void Render(String actId) { }
	// RVA: 0x322cd38 VA: 0x7595844d38
	public Void ShowSelectResult() { }
	// RVA: 0x3237b8c VA: 0x759584fb8c
	private IEnumerator _SelectResultEffectCoroutine() { }
	// RVA: 0x3237c60 VA: 0x759584fc60
	private Void _TriggerCampBGMPreview(String campId) { }
	// RVA: 0x3237dbc VA: 0x759584fdbc
	public Void EventOnCampButtonClicked(String campId) { }
	// RVA: 0x3237e94 VA: 0x759584fe94
	public Void .ctor() { }
	// RVA: 0x3237f04 VA: 0x759584ff04
	private Void <Render>b__8_0(String selectedCamp) { }
	// RVA: 0x3237f20 VA: 0x759584ff20
	private Void <Render>b__8_2() { }
}
```