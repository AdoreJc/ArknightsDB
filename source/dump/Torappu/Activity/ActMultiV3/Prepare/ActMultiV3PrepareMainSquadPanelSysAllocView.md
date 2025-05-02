# ActMultiV3PrepareMainSquadPanelSysAllocView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `CanvasGroup _canvasGrp`

- `UIAnimationLocation _entryAnim`

- `SimpleLayoutContent _cardListContent`

- `Adapter m_adapter`

- `Coroutine m_switchCoroutine`

- `FadeSwitchTween m_switch`


## Methods

- `Void Show(SysAllocModel)`

- `Void Hide()`

- `Void OnDestroy()`

- `Void _ClearCoroutine()`

- `Void Reset(Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSquadPanelSysAllocView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasGrp; // 0x18
	private UIAnimationLocation _entryAnim; // 0x20
	private SimpleLayoutContent _cardListContent; // 0x30
	private Adapter m_adapter; // 0x38
	private Coroutine m_switchCoroutine; // 0x40
	private FadeSwitchTween m_switch; // 0x48
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0__ClearCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3171064 VA: 0x7595789064
	public Void Show(SysAllocModel model) { }
	// RVA: 0x31711ac VA: 0x75957891ac
	public Void Hide() { }
	// RVA: 0x3176638 VA: 0x759578e638
	private Void OnDestroy() { }
	// RVA: 0x31766a0 VA: 0x759578e6a0
	private Void _ClearCoroutine() { }
	// RVA: 0x316f9a8 VA: 0x75957879a8
	public Void Reset(Boolean v) { }
	// RVA: 0x3176520 VA: 0x759578e520
	private Void _InitIfNot() { }
	// RVA: 0x3176808 VA: 0x759578e808
	public Void .ctor() { }
}
```