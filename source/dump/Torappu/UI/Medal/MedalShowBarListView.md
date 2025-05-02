# MedalShowBarListView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Single _percentIncreaseInterval`

- `Single _percentIncreaseDelay`

- `MedalBarListRecycleList _adapter`

- `MedalBarListView _barListView`

- `Image _roundBgImage`

- `Image _roundCircleImage`

- `Text _percentCount`

- `Text _countPart`

- `Text _threePartCount`

- `Text _twoPartCount`

- `Text _onePartCount`

- `Text _threePartMax`

- `Text _twoPartMax`

- `Text _onePartMax`

- `Text _collectCount`

- `LoopVerticalScrollRect _scrollRect`

- `AnimationWrapper _animationWrapper`

- `MedalListViewModel m_cachedViewModel`

- `ListFilter m_cachedFilter`

- `UIPageListener m_pageListener`

- `Boolean m_isInited`

- `CountStyleAnimController m_countStyleController`

- `Tween m_cacheTween`

- `Boolean m_isTypeJumping`


## Properties

- `CountStyleAnimController countStyleController`


## Methods

- `CountStyleAnimController get_countStyleController()`

- `Void ApplyValueChange(Vector2)`

- `Void ToLeftBarType(String)`

- `IEnumerator _DisplayOwnCount()`

- `Void SwitchProgressDisplay()`

- `Void StopProgressAnim()`

- `Void ResetProgressAnim()`

- `Void KillTween()`

- `Void _ToBarPos(Int32, Action)`

- `Void _ToBarPosWithReset(Int32, Action)`

- `Int32 _FindListIdxByTypeId(String)`

- `Void ToBarType(String)`

- `Void ToBarGroup(String)`

- `IEnumerator ToBarGroupWhenScrollReady(String)`

- `Void OpenMedal(String)`

- `IEnumerator ToBarMedalWhenScrollReady(String)`

- `Void ToBarMedalAndOpen(String, Boolean)`

- `Void Render(MedalListViewModel)`

- `Void _RefreshProgressDisplay()`

- `Void _CoroutineWithPage(IEnumerator)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalShowBarListView : MonoBehaviour, IHotfixable
{
	private const Int32 LIST_NEAR_INDEX_DIST; // 0x0
	private const Single LIST_ITEM_HEIGHT; // 0x0
	private const String PROGRESS_SWITCH_ANIM; // 0x0
	private Single _percentIncreaseInterval; // 0x18
	private Single _percentIncreaseDelay; // 0x1c
	private MedalBarListRecycleList _adapter; // 0x20
	private MedalBarListView _barListView; // 0x28
	private Image _roundBgImage; // 0x30
	private Image _roundCircleImage; // 0x38
	private Text _percentCount; // 0x40
	private Text _countPart; // 0x48
	private Text _threePartCount; // 0x50
	private Text _twoPartCount; // 0x58
	private Text _onePartCount; // 0x60
	private Text _threePartMax; // 0x68
	private Text _twoPartMax; // 0x70
	private Text _onePartMax; // 0x78
	private Text _collectCount; // 0x80
	private LoopVerticalScrollRect _scrollRect; // 0x88
	private List`1 _btnList; // 0x90
	private AnimationWrapper _animationWrapper; // 0x98
	private List`1 m_cachedTypeList; // 0xa0
	private List`1 m_cachedBarListViewModel; // 0xa8
	private MedalListViewModel m_cachedViewModel; // 0xb0
	private ListFilter m_cachedFilter; // 0xb8
	private UIPageListener m_pageListener; // 0xc8
	private Boolean m_isInited; // 0xd0
	private CountStyleAnimController m_countStyleController; // 0xd8
	private Tween m_cacheTween; // 0xe0
	private Boolean m_isTypeJumping; // 0xe8
	private static DelegateBridge __Hotfix0_get_countStyleController; // 0x0
	private static DelegateBridge __Hotfix0_ApplyValueChange; // 0x8
	private static DelegateBridge __Hotfix0__CalcIndexFromScrollValue; // 0x10
	private static DelegateBridge __Hotfix0_ToLeftBarType; // 0x18
	private static DelegateBridge __Hotfix0__DisplayOwnCount; // 0x20
	private static DelegateBridge __Hotfix0_SwitchProgressDisplay; // 0x28
	private static DelegateBridge __Hotfix0_StopProgressAnim; // 0x30
	private static DelegateBridge __Hotfix0_ResetProgressAnim; // 0x38
	private static DelegateBridge __Hotfix0_KillTween; // 0x40
	private static DelegateBridge __Hotfix0__ToBarPos; // 0x48
	private static DelegateBridge __Hotfix0__ToBarPosWithReset; // 0x50
	private static DelegateBridge __Hotfix0__FindListIdxByTypeId; // 0x58
	private static DelegateBridge __Hotfix0_ToBarType; // 0x60
	private static DelegateBridge __Hotfix0_ToBarGroup; // 0x68
	private static DelegateBridge __Hotfix0_ToBarGroupWhenScrollReady; // 0x70
	private static DelegateBridge __Hotfix0_OpenMedal; // 0x78
	private static DelegateBridge __Hotfix0_ToBarMedalWhenScrollReady; // 0x80
	private static DelegateBridge __Hotfix0_ToBarMedalAndOpen; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x90
	private static DelegateBridge __Hotfix0__RefreshProgressDisplay; // 0x98
	private static DelegateBridge __Hotfix0__CoroutineWithPage; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	private CountStyleAnimController countStyleController { get; }

	// RVA: 0x27a4004 VA: 0x7594dbc004
	private CountStyleAnimController get_countStyleController() { }
	// RVA: 0x27a41ac VA: 0x7594dbc1ac
	public Void ApplyValueChange(Vector2 value) { }
	// RVA: 0x27a4310 VA: 0x7594dbc310
	private static Int32 _CalcIndexFromScrollValue(Single val, Int32 totalCount, Single countInOnePage) { }
	// RVA: 0x27a4464 VA: 0x7594dbc464
	public Void ToLeftBarType(String typeId) { }
	// RVA: 0x27a4788 VA: 0x7594dbc788
	private IEnumerator _DisplayOwnCount() { }
	// RVA: 0x27a485c VA: 0x7594dbc85c
	public Void SwitchProgressDisplay() { }
	// RVA: 0x27a4a94 VA: 0x7594dbca94
	public Void StopProgressAnim() { }
	// RVA: 0x27a4b70 VA: 0x7594dbcb70
	public Void ResetProgressAnim() { }
	// RVA: 0x27a4c94 VA: 0x7594dbcc94
	public Void KillTween() { }
	// RVA: 0x27a4d1c VA: 0x7594dbcd1c
	private Void _ToBarPos(Int32 index, Action finishAction) { }
	// RVA: 0x27a5008 VA: 0x7594dbd008
	private Void _ToBarPosWithReset(Int32 index, Action finishAction) { }
	// RVA: 0x27a5404 VA: 0x7594dbd404
	private Int32 _FindListIdxByTypeId(String typeId) { }
	// RVA: 0x27a5530 VA: 0x7594dbd530
	public Void ToBarType(String typeId) { }
	// RVA: 0x27a55e8 VA: 0x7594dbd5e8
	public Void ToBarGroup(String groupId) { }
	// RVA: 0x27a5724 VA: 0x7594dbd724
	public IEnumerator ToBarGroupWhenScrollReady(String groupId) { }
	// RVA: 0x27a581c VA: 0x7594dbd81c
	public Void OpenMedal(String medalId) { }
	// RVA: 0x27a58a8 VA: 0x7594dbd8a8
	public IEnumerator ToBarMedalWhenScrollReady(String medalId) { }
	// RVA: 0x27a59a0 VA: 0x7594dbd9a0
	public Void ToBarMedalAndOpen(String medalId, Boolean openMedal) { }
	// RVA: 0x27a5bd0 VA: 0x7594dbdbd0
	public Void Render(MedalListViewModel listViewModel) { }
	// RVA: 0x27a62e4 VA: 0x7594dbe2e4
	private Void _RefreshProgressDisplay() { }
	// RVA: 0x27a6bdc VA: 0x7594dbebdc
	private Void _CoroutineWithPage(IEnumerator coroutine) { }
	// RVA: 0x27a6d30 VA: 0x7594dbed30
	public Void .ctor() { }
}
```