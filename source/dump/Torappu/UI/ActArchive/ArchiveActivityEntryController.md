# ArchiveActivityEntryController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveActivityEntryButtonDataBinder _entryButtonBinder`

- `ArchiveActivityEntryMusicDataBinder _entryMusicDataBinder`

- `ArchiveActivityEntryPlugin _plugin`

- `ActivityEntryAnimManager _animManager`

- `UITwoStepAnimation m_animOnEnter`


## Methods

- `Void _SetEffectsActive(Boolean)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_BeforePageExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveActivityEntryController : ActArchiveController, IHotfixable
{
	private ArchiveActivityEntryButtonDataBinder _entryButtonBinder; // 0x38
	private ArchiveActivityEntryMusicDataBinder _entryMusicDataBinder; // 0x40
	private UICommonPageEffectHolder[] _effectHolders; // 0x48
	private Canvas[] _canvases; // 0x50
	private ArchiveActivityEntryPlugin _plugin; // 0x58
	private ActivityEntryAnimManager _animManager; // 0x60
	public Action`1 onEntryCategoryClicked; // 0x68
	private UITwoStepAnimation m_animOnEnter; // 0x70
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinder; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_BeforePageExit; // 0x20
	private static DelegateBridge __Hotfix0__SetEffectsActive; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3031f8c VA: 0x7595649f8c
	public List`1 InitAndAchieveDataBinder() { }
	// RVA: 0x30321f4 VA: 0x759564a1f4
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x30322dc VA: 0x759564a2dc
	public override Void OnEnter() { }
	// RVA: 0x3032780 VA: 0x759564a780
	public override Void OnExit() { }
	// RVA: 0x30328ec VA: 0x759564a8ec
	public override Void BeforePageExit() { }
	// RVA: 0x3032578 VA: 0x759564a578
	private Void _SetEffectsActive(Boolean isEnabled) { }
	// RVA: 0x30329c4 VA: 0x759564a9c4
	public Void .ctor() { }
	// RVA: 0x3032a34 VA: 0x759564aa34
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
	// RVA: 0x3032a3c VA: 0x759564aa3c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3032a44 VA: 0x759564aa44
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x3032a4c VA: 0x759564aa4c
	private Void <>xLuaBaseProxy_BeforePageExit() { }
}
```