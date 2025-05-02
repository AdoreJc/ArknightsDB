# ActArchiveCompDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `RectTransform _compHolder`

- `RectTransform _topHolder`

- `State _state`

- `ActArchiveType m_selectedComp`

- `Boolean m_isTransitting`

- `Boolean m_isInited`


## Properties

- `ActArchiveInfo _archiveInfo`


## Methods

- `ActArchiveInfo get__archiveInfo()`

- `Void _InitIfNot()`

- `Boolean _GetProxyByArchiveType(ActArchiveType, out)`

- `Boolean _LockTransition()`

- `Void _UnlockTransition()`

- `IEnumerator Show(Boolean)`

- `Void NotifyBeforePageHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ActArchiveCompDataBinder : DataBinder`1, IHotfixable
{
	private static readonly Dictionary`2 PROXY_TYPE_DICT; // 0x0
	private RectTransform _compHolder; // 0x20
	private RectTransform _topHolder; // 0x28
	private State _state; // 0x30
	public List`1 _supportedTypes; // 0x38
	private Dictionary`2 m_proxies; // 0x40
	private ActArchiveType m_selectedComp; // 0x48
	private Boolean m_isTransitting; // 0x4c
	private Boolean m_isInited; // 0x4d
	private static DelegateBridge __Hotfix0_get__archiveInfo; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__GetProxyByArchiveType; // 0x18
	private static DelegateBridge __Hotfix0__LockTransition; // 0x20
	private static DelegateBridge __Hotfix0__UnlockTransition; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_Show; // 0x38
	private static DelegateBridge __Hotfix0_NotifyBeforePageHide; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private ActArchiveInfo _archiveInfo { get; }

	// RVA: 0x30051dc VA: 0x759561d1dc
	private ActArchiveInfo get__archiveInfo() { }
	// RVA: 0x3005314 VA: 0x759561d314
	private Void _InitIfNot() { }
	// RVA: 0x300560c VA: 0x759561d60c
	private Boolean _GetProxyByArchiveType(ActArchiveType archiveType, out ActArchiveProxy proxy) { }
	// RVA: 0x3005ab4 VA: 0x759561dab4
	private Boolean _LockTransition() { }
	// RVA: 0x3005b40 VA: 0x759561db40
	private Void _UnlockTransition() { }
	// RVA: 0x3005bb8 VA: 0x759561dbb8
	public override Void OnValueChanged(IntProperty property) { }
	// RVA: 0x3005cd4 VA: 0x759561dcd4
	public IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x3005dd4 VA: 0x759561ddd4
	public Void NotifyBeforePageHide(Boolean isIntoStack) { }
	// RVA: 0x3005ea4 VA: 0x759561dea4
	public Void .ctor() { }
	// RVA: 0x3005f98 VA: 0x759561df98
	private static Void .cctor() { }
}
```