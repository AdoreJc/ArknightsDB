# UIBattleSandboxNotificationItem

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Image _itemIcon`

- `GameObject _rarityRing`

- `Text _addOnText`

- `Transform _content`

- `Vector2 _upOffset`

- `Vector2 _downOffset`

- `Single _tweenTime`

- `Single _lifeTime`

- `CanvasGroup m_canvasGroup`

- `UIBattleSandboxItemNotification m_parent`

- `Int32 m_itemRarity`

- `AutoPackSpriteHub m_itemIconSpriteHub`

- `SandboxGameMode m_gameMode`

- `Coroutine m_tweenCoroutine`


## Properties

- `UIBattleSandboxItemNotification parent`

- `SandboxGameMode sandboxGameMode`


## Methods

- `UIBattleSandboxItemNotification get_parent()`

- `Void set_parent(UIBattleSandboxItemNotification)`

- `SandboxGameMode get_sandboxGameMode()`

- `Void Awake()`

- `Void BeginTweens()`

- `Void EndTweens()`

- `Void _OnBeginMoveTweenComplete()`

- `IEnumerator _ItemLife()`

- `Void _OnEndMoveTweenComplete()`

- `Void Init()`

- `Void SetData(String, Int32)`

- `Sprite _LoadBackpackItemIcon(String)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxNotificationItem : MonoBehaviour, IHotfixable
{
	private Image _itemIcon; // 0x18
	private GameObject _rarityRing; // 0x20
	private Text _addOnText; // 0x28
	private Transform _content; // 0x30
	private Vector2 _upOffset; // 0x38
	private Vector2 _downOffset; // 0x40
	private Single _tweenTime; // 0x48
	private Single _lifeTime; // 0x4c
	private CanvasGroup m_canvasGroup; // 0x50
	private UIBattleSandboxItemNotification m_parent; // 0x58
	private Int32 m_itemRarity; // 0x60
	private AutoPackSpriteHub m_itemIconSpriteHub; // 0x68
	private SandboxGameMode m_gameMode; // 0x70
	private Coroutine m_tweenCoroutine; // 0x78
	private static DelegateBridge __Hotfix0_get_parent; // 0x0
	private static DelegateBridge __Hotfix0_set_parent; // 0x8
	private static DelegateBridge __Hotfix0_get_sandboxGameMode; // 0x10
	private static DelegateBridge __Hotfix0_Awake; // 0x18
	private static DelegateBridge __Hotfix0_BeginTweens; // 0x20
	private static DelegateBridge __Hotfix0_EndTweens; // 0x28
	private static DelegateBridge __Hotfix0__OnBeginMoveTweenComplete; // 0x30
	private static DelegateBridge __Hotfix0__ItemLife; // 0x38
	private static DelegateBridge __Hotfix0__OnEndMoveTweenComplete; // 0x40
	private static DelegateBridge __Hotfix0_Init; // 0x48
	private static DelegateBridge __Hotfix0_SetData; // 0x50
	private static DelegateBridge __Hotfix0__LoadBackpackItemIcon; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public UIBattleSandboxItemNotification parent { get; set; }
	private SandboxGameMode sandboxGameMode { get; }

	// RVA: 0x20c1b84 VA: 0x75946d9b84
	public UIBattleSandboxItemNotification get_parent() { }
	// RVA: 0x20c1bec VA: 0x75946d9bec
	public Void set_parent(UIBattleSandboxItemNotification value) { }
	// RVA: 0x20c1c70 VA: 0x75946d9c70
	private SandboxGameMode get_sandboxGameMode() { }
	// RVA: 0x20c1d20 VA: 0x75946d9d20
	private Void Awake() { }
	// RVA: 0x20c1db0 VA: 0x75946d9db0
	public Void BeginTweens() { }
	// RVA: 0x20c2010 VA: 0x75946da010
	public Void EndTweens() { }
	// RVA: 0x20c2268 VA: 0x75946da268
	private Void _OnBeginMoveTweenComplete() { }
	// RVA: 0x20c2318 VA: 0x75946da318
	private IEnumerator _ItemLife() { }
	// RVA: 0x20c23ec VA: 0x75946da3ec
	private Void _OnEndMoveTweenComplete() { }
	// RVA: 0x20c24cc VA: 0x75946da4cc
	public Void Init() { }
	// RVA: 0x20c257c VA: 0x75946da57c
	public Void SetData(String itemId, Int32 count) { }
	// RVA: 0x20c26f4 VA: 0x75946da6f4
	private Sprite _LoadBackpackItemIcon(String itemId) { }
	// RVA: 0x20c27c0 VA: 0x75946da7c0
	private Void OnDestroy() { }
	// RVA: 0x20c2854 VA: 0x75946da854
	public Void .ctor() { }
}
```