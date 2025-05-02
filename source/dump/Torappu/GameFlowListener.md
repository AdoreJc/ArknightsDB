# GameFlowListener

**Namespace:** `Torappu`


## Fields

- `Boolean m_listenersRegistered`

- `RedirectBundle m_redirectBundle`


## Properties

- `IEnumerator configCollectCoroutine`

- `IEnumerator initialCoroutine`

- `RedirectBundle redirectBundle`


## Methods

- `IEnumerator get_configCollectCoroutine()`

- `IEnumerator get_initialCoroutine()`

- `Boolean _RegisterInitListener(IEnumerator)`

- `RedirectBundle get_redirectBundle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GameFlowListener : SingletonMonoBehaviour`1
{
	private const Int32 REGISTER_WAIT_CYCLES; // 0x0
	private Boolean m_listenersRegistered; // 0x18
	private List`1 m_initListeners; // 0x20
	private RedirectBundle m_redirectBundle; // 0x28
	private static DelegateBridge __Hotfix0_RegisterInitListener; // 0x0
	private static DelegateBridge __Hotfix0_RedirectScene; // 0x8
	private static DelegateBridge __Hotfix1_RedirectScene; // 0x10
	private static DelegateBridge __Hotfix0_get_configCollectCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_get_initialCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__RegisterInitListener; // 0x28
	private static DelegateBridge __Hotfix0_get_redirectBundle; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public IEnumerator configCollectCoroutine { get; }
	public IEnumerator initialCoroutine { get; }
	public RedirectBundle redirectBundle { get; }

	// RVA: 0x2f33a9c VA: 0x759554ba9c
	public static Boolean RegisterInitListener(IEnumerator listener) { }
	// RVA: 0x2f33c60 VA: 0x759554bc60
	public static Void RedirectScene(String sceneName, Options options) { }
	// RVA: 0x2f33d94 VA: 0x759554bd94
	public static Void RedirectScene(String sceneName) { }
	// RVA: 0x2f31c80 VA: 0x7595549c80
	public IEnumerator get_configCollectCoroutine() { }
	// RVA: 0x2f31d2c VA: 0x7595549d2c
	public IEnumerator get_initialCoroutine() { }
	// RVA: 0x2f33b28 VA: 0x759554bb28
	private Boolean _RegisterInitListener(IEnumerator listener) { }
	// RVA: 0x2f31dd8 VA: 0x7595549dd8
	public RedirectBundle get_redirectBundle() { }
	// RVA: 0x2f33e6c VA: 0x759554be6c
	public Void .ctor() { }
}
```