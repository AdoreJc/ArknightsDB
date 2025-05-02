# EnemyHandBookState

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `EnemyHandBookStateBean _stateBean`

- `EnemyHandBookScrollView _enemyScrollView`

- `EnemyHandBookShufflePanel _shufflePanel`

- `GameObject _pageBack`

- `Boolean m_hasInited`


## Methods

- `Void DismissWrapped()`

- `Void _InitView()`

- `Void _OnSelectedChanged(String, Boolean)`

- `Void OnSelectedChanged(String)`

- `Void OnSelectedChangedByClick(String)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandBookState : PopupFloatState
{
	private EnemyHandBookStateBean _stateBean; // 0x70
	private EnemyHandBookScrollView _enemyScrollView; // 0x78
	private EnemyHandBookShufflePanel _shufflePanel; // 0x80
	private GameObject _pageBack; // 0x88
	private Boolean m_hasInited; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_DismissWrapped; // 0x10
	private static DelegateBridge __Hotfix0__InitView; // 0x18
	private static DelegateBridge __Hotfix0__OnSelectedChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnSelectedChanged; // 0x28
	private static DelegateBridge __Hotfix0_OnSelectedChangedByClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x293be30 VA: 0x7594f53e30
	public override IStateBean GetCacheBean() { }
	// RVA: 0x293be98 VA: 0x7594f53e98
	protected override Void OnEnter() { }
	// RVA: 0x293c394 VA: 0x7594f54394
	public Void DismissWrapped() { }
	// RVA: 0x293c248 VA: 0x7594f54248
	private Void _InitView() { }
	// RVA: 0x293c594 VA: 0x7594f54594
	private Void _OnSelectedChanged(String enemyId, Boolean needScrollFlag) { }
	// RVA: 0x293c69c VA: 0x7594f5469c
	public Void OnSelectedChanged(String enemyId) { }
	// RVA: 0x293c720 VA: 0x7594f54720
	public Void OnSelectedChangedByClick(String enemyId) { }
	// RVA: 0x293c7a4 VA: 0x7594f547a4
	public Void .ctor() { }
	// RVA: 0x293c814 VA: 0x7594f54814
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```