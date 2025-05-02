# MedalGroupListView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `UIRecycleLayoutGroup _content`

- `MedalBarListView _barListView`

- `MedalGroupItemView _prefab`

- `ScrollRect _scroll`

- `UIMedalEvent _clickMedalEvent`

- `UIStringEvent _clickToGroupEvent`

- `Boolean _ableToGetFlag`

- `GameObject _emptyState`

- `String pageName`

- `ListFilter m_cachedFilter`

- `AsyncGameObjectLoader m_objLoader`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `Tween m_cacheTween`


## Methods

- `Void _InitIfNot()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void UpdateTime(Single)`

- `Void ToLeftBarType(String)`

- `Void _ToBarPos(Single, Action)`

- `Void OnValueChanged(Vector2)`

- `Void Render(MedalListViewModel, Boolean)`

- `Void Refresh()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalGroupListView : MonoBehaviour, IHotfixable, ITimeWatcher
{
	private const Int32 MEDAL_PER_FRAME; // 0x0
	private const Single SPACING_HEIGHT; // 0x0
	private UIRecycleLayoutGroup _content; // 0x18
	private MedalBarListView _barListView; // 0x20
	private MedalGroupItemView _prefab; // 0x28
	private ScrollRect _scroll; // 0x30
	private UIMedalEvent _clickMedalEvent; // 0x38
	private UIStringEvent _clickToGroupEvent; // 0x40
	private Boolean _ableToGetFlag; // 0x48
	private GameObject _emptyState; // 0x50
	public String pageName; // 0x58
	private ListFilter m_cachedFilter; // 0x60
	private AsyncGameObjectLoader m_objLoader; // 0x70
	private Adapter m_adapter; // 0x78
	private const Single DELTA_HEIGHT; // 0x0
	private Boolean m_isInited; // 0x80
	private Tween m_cacheTween; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge __Hotfix0_OnDisable; // 0x10
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x18
	private static DelegateBridge __Hotfix0_ToLeftBarType; // 0x20
	private static DelegateBridge __Hotfix0__ToBarPos; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0_Refresh; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x279bc8c VA: 0x7594db3c8c
	private Void _InitIfNot() { }
	// RVA: 0x279bee4 VA: 0x7594db3ee4
	private Void OnEnable() { }
	// RVA: 0x279bf54 VA: 0x7594db3f54
	private Void OnDisable() { }
	// RVA: 0x279bfc4 VA: 0x7594db3fc4
	public Void UpdateTime(Single delta) { }
	// RVA: 0x279c058 VA: 0x7594db4058
	public Void ToLeftBarType(String typeId) { }
	// RVA: 0x279c26c VA: 0x7594db426c
	private Void _ToBarPos(Single value, Action finishAction) { }
	// RVA: 0x279c4bc VA: 0x7594db44bc
	public Void OnValueChanged(Vector2 pos) { }
	// RVA: 0x279739c VA: 0x7594daf39c
	public Void Render(MedalListViewModel listViewModel, Boolean refreshFlag) { }
	// RVA: 0x2798458 VA: 0x7594db0458
	public Void Refresh() { }
	// RVA: 0x279caa8 VA: 0x7594db4aa8
	public Void .ctor() { }
}
```