# SiracusaMapBattleTaskPreviewState

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaMapBattleTaskPreviewView _view`

- `RectTransform _btnBackRt`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void OpenEnemyHandbook()`

- `Void OpenSquad()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapBattleTaskPreviewState : PopupFloatState
{
	private SiracusaMapBattleTaskPreviewView _view; // 0x70
	private RectTransform _btnBackRt; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnExit; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x28
	private static DelegateBridge __Hotfix0_OpenEnemyHandbook; // 0x30
	private static DelegateBridge __Hotfix0_OpenSquad; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x23fdd58 VA: 0x7594a15d58
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23fddbc VA: 0x7594a15dbc
	protected override Void OnExit() { }
	// RVA: 0x23fdf34 VA: 0x7594a15f34
	protected override Void OnEnter() { }
	// RVA: 0x23fe10c VA: 0x7594a1610c
	private Void _InitIfNot() { }
	// RVA: 0x23fe3ac VA: 0x7594a163ac
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x23fe524 VA: 0x7594a16524
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x23fe774 VA: 0x7594a16774
	public Void OpenEnemyHandbook() { }
	// RVA: 0x23fe880 VA: 0x7594a16880
	public Void OpenSquad() { }
	// RVA: 0x23febb4 VA: 0x7594a16bb4
	public Void .ctor() { }
	// RVA: 0x23fec24 VA: 0x7594a16c24
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x23fec2c VA: 0x7594a16c2c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x23fec34 VA: 0x7594a16c34
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```