# BackPressManager

**Namespace:** `Torappu.UI`


## Fields

- `Single m_lastEventTime`

- `PostHandler m_postHandler`


## Methods

- `Void _OnSceneChanged(String, String)`

- `Void _OnBackPress()`

- `Void TriggerBackPress()`

- `Void _Clear()`

- `Void _TryTriggerBackPress()`

- `Void _TryTriggerPostHandler()`

- `Void ListenerOnlyRegister(UIBackPressListener)`

- `Void ListenerOnlyUnregister(UIBackPressListener)`

- `Void Tick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class BackPressManager : Singleton`1, IHotfixable, IDisposable
{
	private const Single FAST_THRESHOLD; // 0x0
	private Single m_lastEventTime; // 0x10
	private List`1 m_listeners; // 0x18
	private PostHandler m_postHandler; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Dispose; // 0x8
	private static DelegateBridge __Hotfix0__OnSceneChanged; // 0x10
	private static DelegateBridge __Hotfix0__OnBackPress; // 0x18
	private static DelegateBridge __Hotfix0_BindListener; // 0x20
	private static DelegateBridge __Hotfix1_BindListener; // 0x28
	private static DelegateBridge __Hotfix0_SetPostHandler; // 0x30
	private static DelegateBridge __Hotfix0_TriggerBackPress; // 0x38
	private static DelegateBridge __Hotfix0__Clear; // 0x40
	private static DelegateBridge __Hotfix0__TryTriggerBackPress; // 0x48
	private static DelegateBridge __Hotfix0__TryTriggerPostHandler; // 0x50
	private static DelegateBridge __Hotfix0_ListenerOnlyRegister; // 0x58
	private static DelegateBridge __Hotfix0_ListenerOnlyUnregister; // 0x60
	private static DelegateBridge __Hotfix0_Tick; // 0x68
	private static DelegateBridge __Hotfix0__MergePath; // 0x70
	private static DelegateBridge __Hotfix0__IsBackPressEnabled; // 0x78


	// RVA: 0x210d354 VA: 0x7594725354
	protected Void .ctor() { }
	// RVA: 0x210d498 VA: 0x7594725498
	public virtual Void Dispose() { }
	// RVA: 0x210d604 VA: 0x7594725604
	private Void _OnSceneChanged(String fromSceneName, String toSceneName) { }
	// RVA: 0x210d688 VA: 0x7594725688
	private Void _OnBackPress() { }
	// RVA: 0x20fdaa4 VA: 0x7594715aa4
	public static Void BindListener(RectTransform rectTrans, BackPressOptions options) { }
	// RVA: 0x210d994 VA: 0x7594725994
	public static Void BindListener(MonoBehaviour root, BackPressOptions options, String[] names) { }
	// RVA: 0x210db78 VA: 0x7594725b78
	public static Void SetPostHandler(PostHandler postHandler) { }
	// RVA: 0x210dc1c VA: 0x7594725c1c
	public Void TriggerBackPress() { }
	// RVA: 0x210d558 VA: 0x7594725558
	private Void _Clear() { }
	// RVA: 0x210dc84 VA: 0x7594725c84
	private Void _TryTriggerBackPress() { }
	// RVA: 0x210d8b0 VA: 0x75947258b0
	private Void _TryTriggerPostHandler() { }
	// RVA: 0x210dd18 VA: 0x7594725d18
	public Void ListenerOnlyRegister(UIBackPressListener listener) { }
	// RVA: 0x210de88 VA: 0x7594725e88
	public Void ListenerOnlyUnregister(UIBackPressListener listener) { }
	// RVA: 0x210df70 VA: 0x7594725f70
	public Void Tick() { }
	// RVA: 0x210dff4 VA: 0x7594725ff4
	private static String _MergePath(String[] names) { }
	// RVA: 0x210d82c VA: 0x759472582c
	private static Boolean _IsBackPressEnabled() { }
}
```