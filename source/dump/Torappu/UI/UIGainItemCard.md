# UIGainItemCard

**Namespace:** `Torappu.UI`


## Fields

- `UIItemCard _internalPrefab`

- `RectTransform _effectHolder`

- `Single _delayForInternalCard`

- `UIItemCard m_internalCard`

- `Coroutine m_coroutine`

- `Action m_onFinished`

- `Boolean m_isShowEffect`

- `Boolean m_hasInited`


## Methods

- `Void Render(Options, UIGainItemFloatPanel, Action)`

- `Void HideEffect(UIGainItemFloatPanel)`

- `Void ForceToEnd(UIGainItemFloatPanel)`

- `Void _InitIfNot()`

- `IEnumerator _DoRenderCoroutine(Single, Boolean)`

- `Void _ResetAll(UIGainItemFloatPanel)`

- `Void _FinishMe()`

- `Void _StopCoroutine(UIGainItemFloatPanel)`

- `Void <Render>b__9_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIGainItemCard : MonoBehaviour, IHotfixable
{
	private UIItemCard _internalPrefab; // 0x18
	private RectTransform _effectHolder; // 0x20
	private Single _delayForInternalCard; // 0x28
	private UIItemCard m_internalCard; // 0x30
	private Coroutine m_coroutine; // 0x38
	private Action m_onFinished; // 0x40
	private Boolean m_isShowEffect; // 0x48
	private Boolean m_hasInited; // 0x49
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_HideEffect; // 0x8
	private static DelegateBridge __Hotfix0_ForceToEnd; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__DoRenderCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__ResetAll; // 0x28
	private static DelegateBridge __Hotfix0__FinishMe; // 0x30
	private static DelegateBridge __Hotfix0__StopCoroutine; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x221d6e0 VA: 0x75948356e0
	public Void Render(Options options, UIGainItemFloatPanel closure, Action onFinished) { }
	// RVA: 0x221dc6c VA: 0x7594835c6c
	public Void HideEffect(UIGainItemFloatPanel closure) { }
	// RVA: 0x221ddbc VA: 0x7594835dbc
	public Void ForceToEnd(UIGainItemFloatPanel closure) { }
	// RVA: 0x221d9dc VA: 0x75948359dc
	private Void _InitIfNot() { }
	// RVA: 0x221db8c VA: 0x7594835b8c
	private IEnumerator _DoRenderCoroutine(Single delay, Boolean showEffect) { }
	// RVA: 0x221dadc VA: 0x7594835adc
	private Void _ResetAll(UIGainItemFloatPanel closure) { }
	// RVA: 0x221de80 VA: 0x7594835e80
	private Void _FinishMe() { }
	// RVA: 0x221dd0c VA: 0x7594835d0c
	private Void _StopCoroutine(UIGainItemFloatPanel closure) { }
	// RVA: 0x221df3c VA: 0x7594835f3c
	public Void .ctor() { }
	// RVA: 0x221dfb8 VA: 0x7594835fb8
	private Void <Render>b__9_0(Int32 _) { }
}
```