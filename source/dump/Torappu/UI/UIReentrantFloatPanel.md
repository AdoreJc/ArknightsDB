# UIReentrantFloatPanel

**Namespace:** `Torappu.UI`


## Fields

- `ReentrantFloatOpt m_internalOpt`


## Properties

- `ReentrantFloatOpt reentrant`

- `Boolean isShown`


## Methods

- `ReentrantFloatOpt get_reentrant()`

- `Void _EnableGameObject()`

- `Void _DisableGameObject()`

- `Boolean get_isShown()`

- `Void Show()`

- `IEnumerator ShowCoroutine()`

- `Void Hide()`

- `IEnumerator HideCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIReentrantFloatPanel : MonoBehaviour, IHotfixable
{
	private ReentrantFloatOpt m_internalOpt; // 0x18
	private static DelegateBridge __Hotfix0_get_reentrant; // 0x0
	private static DelegateBridge __Hotfix0_ShowEffect; // 0x8
	private static DelegateBridge __Hotfix0_HideEffect; // 0x10
	private static DelegateBridge __Hotfix0_Start; // 0x18
	private static DelegateBridge __Hotfix0__EnableGameObject; // 0x20
	private static DelegateBridge __Hotfix0__DisableGameObject; // 0x28
	private static DelegateBridge __Hotfix0_get_isShown; // 0x30
	private static DelegateBridge __Hotfix0_Show; // 0x38
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x40
	private static DelegateBridge __Hotfix0_Hide; // 0x48
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected ReentrantFloatOpt reentrant { get; }
	public Boolean isShown { get; }

	// RVA: 0x21e5564 VA: 0x75947fd564
	protected ReentrantFloatOpt get_reentrant() { }
	// RVA: 0x21e573c VA: 0x75947fd73c
	protected virtual IEnumerator ShowEffect() { }
	// RVA: 0x21e5800 VA: 0x75947fd800
	protected virtual IEnumerator HideEffect() { }
	// RVA: 0x21e58c4 VA: 0x75947fd8c4
	protected virtual Void Start() { }
	// RVA: 0x21e5a0c VA: 0x75947fda0c
	private Void _EnableGameObject() { }
	// RVA: 0x21e5950 VA: 0x75947fd950
	private Void _DisableGameObject() { }
	// RVA: 0x21e5a84 VA: 0x75947fda84
	public Boolean get_isShown() { }
	// RVA: 0x21e5af8 VA: 0x75947fdaf8
	public Void Show() { }
	// RVA: 0x21e5ba0 VA: 0x75947fdba0
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x21e5c14 VA: 0x75947fdc14
	public Void Hide() { }
	// RVA: 0x21e5cbc VA: 0x75947fdcbc
	public IEnumerator HideCoroutine() { }
	// RVA: 0x21e5d30 VA: 0x75947fdd30
	public Void .ctor() { }
}
```