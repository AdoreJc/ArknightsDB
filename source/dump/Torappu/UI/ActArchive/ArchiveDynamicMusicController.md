# ArchiveDynamicMusicController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveMusicListDataBinder _musicListBinder`

- `Action onSetHomeTheme`

- `Handler m_handler`


## Methods

- `Void OnSetHomeTheme()`

- `Void <>xLuaBaseProxy_OnItemClick(String)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `IEnumerator <>xLuaBaseProxy_Show(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDynamicMusicController : ActArchiveController
{
	private ArchiveMusicListDataBinder _musicListBinder; // 0x38
	public Action`2 onMusicItemClicked; // 0x40
	public Action onSetHomeTheme; // 0x48
	private Handler m_handler; // 0x50
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x0
	private static DelegateBridge __Hotfix0_OnSetHomeTheme; // 0x8
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_Show; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x305ca20 VA: 0x7595674a20
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x305cab0 VA: 0x7595674ab0
	public Void OnSetHomeTheme() { }
	// RVA: 0x305cb34 VA: 0x7595674b34
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x305ccec VA: 0x7595674cec
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x305ce40 VA: 0x7595674e40
	public override Void OnEnter() { }
	// RVA: 0x305cfb8 VA: 0x7595674fb8
	public override Void OnExit() { }
	// RVA: 0x305d0dc VA: 0x75956750dc
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x305d1cc VA: 0x75956751cc
	public Void .ctor() { }
	// RVA: 0x305d23c VA: 0x759567523c
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x305d244 VA: 0x7595675244
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x305d24c VA: 0x759567524c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x305d254 VA: 0x7595675254
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x305d25c VA: 0x759567525c
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```