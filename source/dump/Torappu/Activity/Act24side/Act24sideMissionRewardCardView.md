# Act24sideMissionRewardCardView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Single _effectScale`

- `RectTransform _effectHolder`

- `Single _delayForInternalCard`

- `Act24sideMeldingItemView _actItemViewPrefab`

- `UIItemCard m_internalCard`

- `Act24sideMeldingItemView m_actItem`

- `Coroutine m_coroutine`

- `Action m_onFinished`

- `Boolean m_isShowEffect`

- `Boolean m_hasInited`


## Methods

- `Void Render(Options, Act24sideMissionRewardView, Action)`

- `Void Render(OptionsAct, Act24sideMissionRewardView, Action)`

- `Void HideEffect(Act24sideMissionRewardView)`

- `Void ForceToEnd(Act24sideMissionRewardView)`

- `Void _InitIfNot()`

- `IEnumerator _DoRenderCoroutine(Single, Boolean)`

- `Void _ResetAll(Act24sideMissionRewardView)`

- `Void _FinishMe()`

- `Void _StopCoroutine(Act24sideMissionRewardView)`

- `Void <Render>b__12_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionRewardCardView : MonoBehaviour, IHotfixable
{
	private Single _effectScale; // 0x18
	private RectTransform _effectHolder; // 0x20
	private Single _delayForInternalCard; // 0x28
	private Act24sideMeldingItemView _actItemViewPrefab; // 0x30
	private UIItemCard m_internalCard; // 0x38
	private Act24sideMeldingItemView m_actItem; // 0x40
	private Coroutine m_coroutine; // 0x48
	private Action m_onFinished; // 0x50
	private Boolean m_isShowEffect; // 0x58
	private Boolean m_hasInited; // 0x59
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix1_Render; // 0x8
	private static DelegateBridge __Hotfix0_HideEffect; // 0x10
	private static DelegateBridge __Hotfix0_ForceToEnd; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__DoRenderCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__ResetAll; // 0x30
	private static DelegateBridge __Hotfix0__FinishMe; // 0x38
	private static DelegateBridge __Hotfix0__StopCoroutine; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x32b8368 VA: 0x75958d0368
	public Void Render(Options options, Act24sideMissionRewardView closure, Action onFinished) { }
	// RVA: 0x32b8a0c VA: 0x75958d0a0c
	public Void Render(OptionsAct options, Act24sideMissionRewardView closure, Action onFinished) { }
	// RVA: 0x32b8c30 VA: 0x75958d0c30
	public Void HideEffect(Act24sideMissionRewardView closure) { }
	// RVA: 0x32b8d80 VA: 0x75958d0d80
	public Void ForceToEnd(Act24sideMissionRewardView closure) { }
	// RVA: 0x32b8694 VA: 0x75958d0694
	private Void _InitIfNot() { }
	// RVA: 0x32b892c VA: 0x75958d092c
	private IEnumerator _DoRenderCoroutine(Single delay, Boolean showEffect) { }
	// RVA: 0x32b887c VA: 0x75958d087c
	private Void _ResetAll(Act24sideMissionRewardView closure) { }
	// RVA: 0x32b8ec4 VA: 0x75958d0ec4
	private Void _FinishMe() { }
	// RVA: 0x32b8cd0 VA: 0x75958d0cd0
	private Void _StopCoroutine(Act24sideMissionRewardView closure) { }
	// RVA: 0x32b8f80 VA: 0x75958d0f80
	public Void .ctor() { }
	// RVA: 0x32b8ffc VA: 0x75958d0ffc
	private Void <Render>b__12_0(Int32 _) { }
}
```