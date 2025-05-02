# CharacterInfoSubProfessionDetailState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoSubProfessionDetailStateBean m_stateBean`

- `CharacterInfoDetailSubProfessionView _view`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void OpenPage()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSubProfessionDetailState : PopupFloatState
{
	private CharacterInfoSubProfessionDetailStateBean m_stateBean; // 0x70
	private CharacterInfoDetailSubProfessionView _view; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_OpenPage; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d4bf4c VA: 0x7595363f4c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d4bfb4 VA: 0x7595363fb4
	protected override Void OnEnter() { }
	// RVA: 0x2d4c048 VA: 0x7595364048
	private Void _InitIfNot() { }
	// RVA: 0x2d4c148 VA: 0x7595364148
	protected override Void OnResume() { }
	// RVA: 0x2d4c434 VA: 0x7595364434
	public Void OpenPage() { }
	// RVA: 0x2d4c51c VA: 0x759536451c
	public Void .ctor() { }
	// RVA: 0x2d4c5c8 VA: 0x75953645c8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d4c5d0 VA: 0x75953645d0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```