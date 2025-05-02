# ArchiveMusicController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveMusicListDataBinder _musicListBinder`

- `Image _imgBkg`

- `Image _imgTitle`

- `Image _cdLeft`

- `Image _cdLeftLogo`

- `Image _cdRight`

- `Image _cdRightLogo`

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
public class ArchiveMusicController : ActArchiveController
{
	private ArchiveMusicListDataBinder _musicListBinder; // 0x38
	private Image _imgBkg; // 0x40
	private Image _imgTitle; // 0x48
	private Image _cdLeft; // 0x50
	private Image _cdLeftLogo; // 0x58
	private Image _cdRight; // 0x60
	private Image _cdRightLogo; // 0x68
	public Action`2 onMusicItemClicked; // 0x70
	public Action onSetHomeTheme; // 0x78
	private Handler m_handler; // 0x80
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x0
	private static DelegateBridge __Hotfix0_OnSetHomeTheme; // 0x8
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_Show; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x305dab0 VA: 0x7595675ab0
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x305db40 VA: 0x7595675b40
	public Void OnSetHomeTheme() { }
	// RVA: 0x305dbc4 VA: 0x7595675bc4
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x305dcf0 VA: 0x7595675cf0
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x305e1c4 VA: 0x75956761c4
	public override Void OnEnter() { }
	// RVA: 0x305e240 VA: 0x7595676240
	public override Void OnExit() { }
	// RVA: 0x305e2bc VA: 0x75956762bc
	public override IEnumerator Show(Boolean fastMode) { }
	// RVA: 0x305e3ac VA: 0x75956763ac
	public Void .ctor() { }
	// RVA: 0x305e41c VA: 0x759567641c
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x305e424 VA: 0x7595676424
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x305e42c VA: 0x759567642c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x305e434 VA: 0x7595676434
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x305e43c VA: 0x759567643c
	private IEnumerator <>xLuaBaseProxy_Show(Boolean P0) { }
}
```