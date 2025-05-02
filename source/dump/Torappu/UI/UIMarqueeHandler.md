# UIMarqueeHandler

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_isShowing`

- `Boolean m_isWaiting`

- `UpdateSubMsg m_cacheMsg`

- `String m_cacheSceneName`


## Methods

- `IEnumerator Show(UpdateSubMsg, Action)`

- `Void OnFinishAlert()`

- `Boolean _OpenMarqueeDialog(UpdateSubMsg)`

- `Void _TickUpdate(UpdateSubMsg)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIMarqueeHandler : IHotfixable
{
	public static readonly List`1 DONTSHOW_SCENE_LIST; // 0x0
	private const Single CONST_INIT_DURATION; // 0x0
	private Boolean m_isShowing; // 0x10
	private Boolean m_isWaiting; // 0x11
	private UpdateSubMsg m_cacheMsg; // 0x18
	private String m_cacheSceneName; // 0x20
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_OnFinishAlert; // 0x10
	private static DelegateBridge __Hotfix0__OpenMarqueeDialog; // 0x18
	private static DelegateBridge __Hotfix0__TickUpdate; // 0x20
	private static DelegateBridge __Hotfix0__IsUpdateSubMsgValid; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2104e34 VA: 0x759471ce34
	public IEnumerator Show(UpdateSubMsg msg, Action callBackAction) { }
	// RVA: 0x2104f54 VA: 0x759471cf54
	public Void OnFinishAlert() { }
	// RVA: 0x2104fcc VA: 0x759471cfcc
	private Boolean _OpenMarqueeDialog(UpdateSubMsg msg) { }
	// RVA: 0x210537c VA: 0x759471d37c
	private Void _TickUpdate(UpdateSubMsg msg) { }
	// RVA: 0x21054d8 VA: 0x759471d4d8
	private static Boolean _IsUpdateSubMsgValid(UpdateSubMsg msg) { }
	// RVA: 0x2105640 VA: 0x759471d640
	public Void .ctor() { }
	// RVA: 0x21056c0 VA: 0x759471d6c0
	private static Void .cctor() { }
}
```