# FireworkPuzzleMapState

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `RectTransform _topMenuContainer`

- `FireworkPuzzleMapView _view`

- `UIAnimationLocation _enterAnim`

- `GameObject _btnFirstPuzzle`

- `FireworkPuzzleMapStateBean m_stateBean`

- `Boolean m_hasInited`

- `Tween m_enterAnimTween`

- `String m_cachedActId`


## Methods

- `Void _TryStartTutorial()`

- `Void _OpenGuideBook(Story)`

- `Void _InitIfNot()`

- `Boolean _IsUIStable()`

- `Void _EventOnBack()`

- `Void _RegisterToDetailState(IStateBean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnPuzzleClicked(String)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleMapState : State, IHotfixable, IValueMsgReceiver
{
	private const String GUIDE_SUB_SIGNAL; // 0x0
	public const Int32 ON_PUZZLE_CLICKED; // 0x0
	private RectTransform _topMenuContainer; // 0x50
	private FireworkPuzzleMapView _view; // 0x58
	private UIAnimationLocation _enterAnim; // 0x60
	private GameObject _btnFirstPuzzle; // 0x70
	private FireworkPuzzleMapStateBean m_stateBean; // 0x78
	private Boolean m_hasInited; // 0x80
	private Tween m_enterAnimTween; // 0x88
	private String m_cachedActId; // 0x90
	private List`1 m_cachedUnlockedPuzzleList; // 0x98
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__TryStartTutorial; // 0x8
	private static DelegateBridge __Hotfix0__OpenGuideBook; // 0x10
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x30
	private static DelegateBridge __Hotfix0__IsUIStable; // 0x38
	private static DelegateBridge __Hotfix0__EventOnBack; // 0x40
	private static DelegateBridge __Hotfix0__RegisterToDetailState; // 0x48
	private static DelegateBridge __Hotfix0_OnMessage; // 0x50
	private static DelegateBridge __Hotfix0__OnPuzzleClicked; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x28f7138 VA: 0x7594f0f138
	protected override Void OnEnter() { }
	// RVA: 0x28f75ac VA: 0x7594f0f5ac
	private Void _TryStartTutorial() { }
	// RVA: 0x28f76f8 VA: 0x7594f0f6f8
	private Void _OpenGuideBook(Story story) { }
	// RVA: 0x28f7794 VA: 0x7594f0f794
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x28f73f8 VA: 0x7594f0f3f8
	private Void _InitIfNot() { }
	// RVA: 0x28f7a34 VA: 0x7594f0fa34
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28f7a9c VA: 0x7594f0fa9c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x28f7c14 VA: 0x7594f0fc14
	private Boolean _IsUIStable() { }
	// RVA: 0x28f7cf0 VA: 0x7594f0fcf0
	private Void _EventOnBack() { }
	// RVA: 0x28f7dc8 VA: 0x7594f0fdc8
	private Void _RegisterToDetailState(IStateBean targetBean) { }
	// RVA: 0x28f7f30 VA: 0x7594f0ff30
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x28f7fd8 VA: 0x7594f0ffd8
	private Void _OnPuzzleClicked(String puzzleId) { }
	// RVA: 0x28f81a8 VA: 0x7594f101a8
	public Void .ctor() { }
	// RVA: 0x28f8300 VA: 0x7594f10300
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x28f8308 VA: 0x7594f10308
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x28f8314 VA: 0x7594f10314
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```